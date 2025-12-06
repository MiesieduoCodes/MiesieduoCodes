<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GoofyCodes - GitHub Profile README</title>
  <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&family=Fira+Code:wght@400;500&display=swap" rel="stylesheet">
  <style>
    * { font-family: 'Inter', sans-serif; }
    code, .mono { font-family: 'Fira Code', monospace; }
    
    @keyframes float {
      0%, 100% { transform: translateY(0px); }
      50% { transform: translateY(-10px); }
    }
    
    @keyframes pulse-glow {
      0%, 100% { box-shadow: 0 0 20px rgba(99, 102, 241, 0.4); }
      50% { box-shadow: 0 0 40px rgba(99, 102, 241, 0.8); }
    }
    
    @keyframes gradient-shift {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }
    
    @keyframes typing {
      from { width: 0; }
      to { width: 100%; }
    }
    
    @keyframes blink {
      50% { border-color: transparent; }
    }
    
    @keyframes slide-up {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }
    
    .animate-float { animation: float 3s ease-in-out infinite; }
    .animate-pulse-glow { animation: pulse-glow 2s ease-in-out infinite; }
    .animate-gradient { 
      background-size: 200% 200%;
      animation: gradient-shift 5s ease infinite;
    }
    
    .typing-effect {
      overflow: hidden;
      white-space: nowrap;
      border-right: 3px solid #6366f1;
      animation: typing 3s steps(40) 1s forwards, blink 0.75s step-end infinite;
    }
    
    .slide-up {
      animation: slide-up 0.6s ease-out forwards;
      opacity: 0;
    }
    
    .delay-100 { animation-delay: 0.1s; }
    .delay-200 { animation-delay: 0.2s; }
    .delay-300 { animation-delay: 0.3s; }
    .delay-400 { animation-delay: 0.4s; }
    .delay-500 { animation-delay: 0.5s; }
    
    .glass-card {
      background: rgba(255, 255, 255, 0.05);
      backdrop-filter: blur(10px);
      border: 1px solid rgba(255, 255, 255, 0.1);
    }
    
    .tech-badge:hover {
      transform: translateY(-3px) scale(1.05);
      box-shadow: 0 10px 30px -10px rgba(99, 102, 241, 0.5);
    }
    
    .project-card:hover {
      transform: translateY(-8px);
      box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.5);
    }
    
    .gradient-text {
      background: linear-gradient(135deg, #6366f1, #8b5cf6, #d946ef);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
    }
    
    .hero-gradient {
      background: linear-gradient(135deg, #0f0f23 0%, #1a1a3e 50%, #2d1b4e 100%);
    }
    
    .section-divider {
      height: 2px;
      background: linear-gradient(90deg, transparent, #6366f1, transparent);
    }
    
    ::-webkit-scrollbar { width: 8px; }
    ::-webkit-scrollbar-track { background: #1a1a2e; }
    ::-webkit-scrollbar-thumb { 
      background: linear-gradient(180deg, #6366f1, #8b5cf6);
      border-radius: 4px;
    }
  </style>
</head>
<body class="bg-[#0d1117] text-gray-100 min-h-screen">
  
  <!-- Hero Section -->
  <section class="hero-gradient min-h-screen flex items-center justify-center relative overflow-hidden">
    <!-- Animated background orbs -->
    <div class="absolute top-20 left-20 w-72 h-72 bg-purple-500/20 rounded-full blur-3xl animate-pulse"></div>
    <div class="absolute bottom-20 right-20 w-96 h-96 bg-indigo-500/20 rounded-full blur-3xl animate-pulse" style="animation-delay: 1s;"></div>
    <div class="absolute top-1/2 left-1/2 w-64 h-64 bg-pink-500/10 rounded-full blur-3xl animate-pulse" style="animation-delay: 2s;"></div>
    
    <div class="text-center z-10 px-4">
      <div class="mb-8 slide-up">
        <div class="relative inline-block">
          <img src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" 
               class="w-32 h-32 rounded-full border-4 border-indigo-500 animate-pulse-glow" alt="Avatar">
          <div class="absolute -bottom-2 -right-2 bg-green-500 w-8 h-8 rounded-full border-4 border-[#0d1117] flex items-center justify-center">
            <span class="text-xs">✓</span>
          </div>
        </div>
      </div>
      
      <h1 class="text-5xl md:text-7xl font-bold mb-4 slide-up delay-100">
        Hey <span class="animate-float inline-block">👋</span>, I'm <span class="gradient-text">GoofyCodes</span>!
      </h1>
      
      <div class="h-8 mb-6 slide-up delay-200">
        <p class="text-xl md:text-2xl text-gray-400 mono typing-effect inline-block">
          Full-Stack Developer | Drummer | Nature Photographer
        </p>
      </div>
      
      <div class="flex flex-wrap justify-center gap-3 mb-8 slide-up delay-300">
        <a href="https://github.com/MiesieduoCodes" class="glass-card px-4 py-2 rounded-full flex items-center gap-2 hover:bg-white/10 transition-all">
          <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24"><path d="M12 0C5.37 0 0 5.37 0 12c0 5.31 3.435 9.795 8.205 11.385.6.105.825-.255.825-.57 0-.285-.015-1.23-.015-2.235-3.015.555-3.795-.735-4.035-1.41-.135-.345-.72-1.41-1.23-1.695-.42-.225-1.02-.78-.015-.795.945-.015 1.62.87 1.845 1.23 1.08 1.815 2.805 1.305 3.495.99.105-.78.42-1.305.765-1.605-2.67-.3-5.46-1.335-5.46-5.925 0-1.305.465-2.385 1.23-3.225-.12-.3-.54-1.53.12-3.18 0 0 1.005-.315 3.3 1.23.96-.27 1.98-.405 3-.405s2.04.135 3 .405c2.295-1.56 3.3-1.23 3.3-1.23.66 1.65.24 2.88.12 3.18.765.84 1.23 1.905 1.23 3.225 0 4.605-2.805 5.625-5.475 5.925.435.375.81 1.095.81 2.22 0 1.605-.015 2.895-.015 3.3 0 .315.225.69.825.57A12.02 12.02 0 0024 12c0-6.63-5.37-12-12-12z"/></svg>
          <span>@MiesieduoCodes</span>
        </a>
        <span class="glass-card px-4 py-2 rounded-full bg-green-500/20 text-green-400 border-green-500/30">
          ✨ Available for Hire
        </span>
        <span class="glass-card px-4 py-2 rounded-full bg-indigo-500/20 text-indigo-400 border-indigo-500/30">
          🏆 Code Quality A+
        </span>
      </div>
      
      <div class="flex justify-center gap-4 slide-up delay-400">
        <a href="#about" class="bg-gradient-to-r from-indigo-600 to-purple-600 px-8 py-3 rounded-full font-semibold hover:opacity-90 transition-all hover:scale-105">
          Explore My Work →
        </a>
        <a href="#contact" class="glass-card px-8 py-3 rounded-full font-semibold hover:bg-white/10 transition-all">
          Get In Touch
        </a>
      </div>
    </div>
    
    <!-- Scroll indicator -->
    <div class="absolute bottom-8 left-1/2 -translate-x-1/2 animate-bounce">
      <svg class="w-6 h-6 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 14l-7 7m0 0l-7-7m7 7V3"/>
      </svg>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="py-20 px-4 md:px-8 max-w-6xl mx-auto">
    <div class="section-divider mb-16"></div>
    
    <div class="flex items-center gap-3 mb-8">
      <span class="text-4xl">💫</span>
      <h2 class="text-4xl font-bold gradient-text">About Me</h2>
    </div>
    
    <div class="glass-card rounded-2xl p-8 mb-8">
      <blockquote class="border-l-4 border-indigo-500 pl-6 py-2 text-xl italic text-gray-300">
        "Code is like humor. When you have to explain it, it's bad."
        <footer class="text-indigo-400 mt-2 not-italic">— Cory House</footer>
      </blockquote>
    </div>
    
    <p class="text-lg text-gray-300 leading-relaxed mb-8">
      Hello! I'm <span class="text-indigo-400 font-semibold">Goofy</span>, a passionate full-stack developer with a creative spirit that extends beyond coding. My journey in tech is driven by a desire to build solutions that make a difference. When I'm not crafting code, you'll find me behind a drum set creating rhythms or in nature capturing its beauty through my camera lens.
    </p>
    
    <div class="grid md:grid-cols-2 gap-4">
      <div class="glass-card rounded-xl p-5 hover:bg-white/10 transition-all group">
        <span class="text-2xl mb-2 block">🔭</span>
        <p>Currently building <a href="https://anim8.com.ng" class="text-indigo-400 hover:underline font-semibold">Anim8</a> - an innovative animation platform</p>
      </div>
      <div class="glass-card rounded-xl p-5 hover:bg-white/10 transition-all group">
        <span class="text-2xl mb-2 block">🌱</span>
        <p>Expanding my skills with <span class="text-purple-400">C#</span> and <span class="text-purple-400">PHP</span></p>
      </div>
      <div class="glass-card rounded-xl p-5 hover:bg-white/10 transition-all group">
        <span class="text-2xl mb-2 block">🥁</span>
        <p>Professional drummer with <span class="text-green-400 font-bold">8+ years</span> of experience</p>
      </div>
      <div class="glass-card rounded-xl p-5 hover:bg-white/10 transition-all group">
        <span class="text-2xl mb-2 block">📸</span>
        <p>Nature photography enthusiast with <span class="text-pink-400 font-bold">500+</span> published photos</p>
      </div>
      <div class="glass-card rounded-xl p-5 hover:bg-white/10 transition-all group">
        <span class="text-2xl mb-2 block">💡</span>
        <p>Open source contributor and community mentor</p>
      </div>
      <div class="glass-card rounded-xl p-5 hover:bg-white/10 transition-all group">
        <span class="text-2xl mb-2 block">🌍</span>
        <p>Passionate about accessible and inclusive web experiences</p>
      </div>
    </div>
    
    <div class="mt-6 glass-card rounded-xl p-5 bg-gradient-to-r from-amber-500/10 to-orange-500/10 border-amber-500/20">
      <span class="text-2xl">⚡</span>
      <span class="text-amber-300 font-medium ml-2">Fun fact:</span>
      <span class="text-gray-300"> I keep night shift switched on at all times because I believe the warm colors help reduce eye strain during those late-night coding sessions!</span>
    </div>
  </section>

  <!-- Tech Stack Section -->
  <section class="py-20 px-4 md:px-8 max-w-6xl mx-auto">
    <div class="section-divider mb-16"></div>
    
    <div class="flex items-center gap-3 mb-12">
      <span class="text-4xl">🛠️</span>
      <h2 class="text-4xl font-bold gradient-text">Tech Stack</h2>
    </div>
    
    <div class="space-y-10">
      <!-- Frontend -->
      <div class="glass-card rounded-2xl p-8">
        <h3 class="text-xl font-semibold mb-6 flex items-center gap-2">
          <span class="w-3 h-3 bg-cyan-400 rounded-full"></span>
          Frontend
        </h3>
        <div class="flex flex-wrap gap-3">
          <span class="tech-badge bg-[#20232A] px-4 py-2 rounded-lg flex items-center gap-2 transition-all cursor-default">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" class="w-6 h-6" alt="React">
            React
          </span>
          <span class="tech-badge bg-black px-4 py-2 rounded-lg flex items-center gap-2 transition-all cursor-default">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" class="w-6 h-6 invert" alt="Next.js">
            Next.js
          </span>
          <span class="tech-badge bg-[#3178C6] px-4 py-2 rounded-lg flex items-center gap-2 transition-all cursor-default">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" class="w-6 h-6" alt="TypeScript">
            TypeScript
          </span>
          <span class="tech-badge bg-[#F7DF1E] text-black px-4 py-2 rounded-lg flex items-center gap-2 transition-all cursor-default">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" class="w-6 h-6" alt="JavaScript">
            JavaScript
          </span>
          <span class="tech-badge bg-[#E34F26] px-4 py-2 rounded-lg flex items-center gap-2 transition-all cursor-default">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" class="w-6 h-6" alt="HTML5">
            HTML5
          </span>
          <span class="tech-badge bg-[#1572B6] px-4 py-2 rounded-lg flex items-center gap-2 transition-all cursor-default">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" class="w-6 h-6" alt="CSS3">
            CSS3
          </span>
          <span class="tech-badge bg-[#06B6D4] px-4 py-2 rounded-lg flex items-center gap-2 transition-all cursor-default">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original.svg" class="w-6 h-6" alt="Tailwind">
            Tailwind CSS
          </span>
        </div>
      </div>
      
      <!-- Backend -->
      <div class="glass-card rounded-2xl p-8">
        <h3 class="text-xl font-semibold mb-6 flex items-center gap-2">
          <span class="w-3 h-3 bg-green-400 rounded-full"></span>
          Backend
        </h3>
        <div class="flex flex-wrap gap-3">
          <span class="tech-badge bg-[#339933] px-4 py-2 rounded-lg flex items-center gap-2 transition-all cursor-default">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" class="w-6 h-6" alt="Node.js">
            Node.js
          </span>
          <span class="tech-badge bg-[#777BB4] px-4 py-2 rounded-lg flex items-center gap-2 transition-all cursor-default">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" class="w-6 h-6" alt="PHP">
            PHP
          </span>
          <span class="tech-badge bg-[#00599C] px-4 py-2 rounded-lg flex items-center gap-2 transition-all cursor-default">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" class="w-6 h-6" alt="C++">
            C++
          </span>
          <span class="tech-badge bg-[#512BD4] px-4 py-2 rounded-lg flex items-center gap-2 transition-all cursor-default">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" class="w-6 h-6" alt="C#">
            C#
          </span>
        </div>
      </div>
      
      <!-- Database & Tools -->
      <div class="glass-card rounded-2xl p-8">
        <h3 class="text-xl font-semibold mb-6 flex items-center gap-2">
          <span class="w-3 h-3 bg-purple-400 rounded-full"></span>
          Database & Tools
        </h3>
        <div class="flex flex-wrap gap-3">
          <span class="tech-badge bg-[#47A248] px-4 py-2 rounded-lg flex items-center gap-2 transition-all cursor-default">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" class="w-6 h-6" alt="MongoDB">
            MongoDB
          </span>
          <span class="tech-badge bg-[#4479A1] px-4 py-2 rounded-lg flex items-center gap-2 transition-all cursor-default">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" class="w-6 h-6" alt="MySQL">
            MySQL
          </span>
          <span class="tech-badge bg-[#F05032] px-4 py-2 rounded-lg flex items-center gap-2 transition-all cursor-default">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" class="w-6 h-6" alt="Git">
            Git
          </span>
          <span class="tech-badge bg-[#21759B] px-4 py-2 rounded-lg flex items-center gap-2 transition-all cursor-default">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/wordpress/wordpress-original.svg" class="w-6 h-6" alt="WordPress">
            WordPress
          </span>
          <span class="tech-badge bg-[#222222] px-4 py-2 rounded-lg flex items-center gap-2 transition-all cursor-default">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/unity/unity-original.svg" class="w-6 h-6" alt="Unity">
            Unity
          </span>
          <span class="tech-badge bg-[#2496ED] px-4 py-2 rounded-lg flex items-center gap-2 transition-all cursor-default">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" class="w-6 h-6" alt="Docker">
            Docker
          </span>
        </div>
      </div>
    </div>
  </section>

  <!-- Featured Projects -->
  <section class="py-20 px-4 md:px-8 max-w-6xl mx-auto">
    <div class="section-divider mb-16"></div>
    
    <div class="flex items-center gap-3 mb-12">
      <span class="text-4xl">🏆</span>
      <h2 class="text-4xl font-bold gradient-text">Featured Projects</h2>
    </div>
    
    <div class="grid md:grid-cols-2 gap-8">
      <!-- Anim8 -->
      <div class="project-card glass-card rounded-2xl overflow-hidden transition-all duration-300">
        <div class="h-48 bg-gradient-to-br from-indigo-600 to-purple-700 flex items-center justify-center relative overflow-hidden">
          <div class="absolute inset-0 opacity-20">
            <div class="absolute top-4 left-4 w-20 h-20 border-2 border-white rounded-lg rotate-12"></div>
            <div class="absolute bottom-4 right-4 w-16 h-16 border-2 border-white rounded-full"></div>
            <div class="absolute top-1/2 left-1/2 w-24 h-24 border-2 border-white rounded-lg -rotate-12 -translate-x-1/2 -translate-y-1/2"></div>
          </div>
          <span class="text-5xl font-bold text-white z-10">Anim8</span>
        </div>
        <div class="p-6">
          <h3 class="text-2xl font-bold mb-3">Anim8</h3>
          <p class="text-gray-400 mb-4">An innovative animation platform built with React, Three.js, and Node.js that enables creators to bring their ideas to life.</p>
          <div class="flex flex-wrap gap-2 mb-4">
            <span class="text-xs px-2 py-1 bg-indigo-500/20 text-indigo-300 rounded">React</span>
            <span class="text-xs px-2 py-1 bg-indigo-500/20 text-indigo-300 rounded">Three.js</span>
            <span class="text-xs px-2 py-1 bg-indigo-500/20 text-indigo-300 rounded">Node.js</span>
          </div>
          <div class="flex gap-3">
            <a href="https://github.com/MiesieduoCodes/anim8" class="flex items-center gap-2 text-sm text-gray-300 hover:text-white transition-colors">
              <svg class="w-4 h-4" fill="currentColor" viewBox="0 0 24 24"><path d="M12 0C5.37 0 0 5.37 0 12c0 5.31 3.435 9.795 8.205 11.385.6.105.825-.255.825-.57 0-.285-.015-1.23-.015-2.235-3.015.555-3.795-.735-4.035-1.41-.135-.345-.72-1.41-1.23-1.695-.42-.225-1.02-.78-.015-.795.945-.015 1.62.87 1.845 1.23 1.08 1.815 2.805 1.305 3.495.99.105-.78.42-1.305.765-1.605-2.67-.3-5.46-1.335-5.46-5.925 0-1.305.465-2.385 1.23-3.225-.12-.3-.54-1.53.12-3.18 0 0 1.005-.315 3.3 1.23.96-.27 1.98-.405 3-.405s2.04.135 3 .405c2.295-1.56 3.3-1.23 3.3-1.23.66 1.65.24 2.88.12 3.18.765.84 1.23 1.905 1.23 3.225 0 4.605-2.805 5.625-5.475 5.925.435.375.81 1.095.81 2.22 0 1.605-.015 2.895-.015 3.3 0 .315.225.69.825.57A12.02 12.02 0 0024 12c0-6.63-5.37-12-12-12z"/></svg>
              View Source
            </a>
            <a href="https://anim8.com.ng" class="flex items-center gap-2 text-sm text-indigo-400 hover:text-indigo-300 transition-colors">
              <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"/></svg>
              Live Demo
            </a>
          </div>
        </div>
      </div>
      
      <!-- EcoTracker -->
      <div class="project-card glass-card rounded-2xl overflow-hidden transition-all duration-300">
        <div class="h-48 bg-gradient-to-br from-emerald-500 to-teal-600 flex items-center justify-center relative overflow-hidden">
          <div class="absolute inset-0 opacity-20">
            <div class="absolute top-6 right-8 w-12 h-12 border-2 border-white rounded-full"></div>
            <div class="absolute bottom-8 left-6 w-8 h-16 border-2 border-white rounded-full"></div>
            <div class="absolute top-12 left-12 w-6 h-6 bg-white rounded-full"></div>
          </div>
          <span class="text-4xl font-bold text-white z-10">🌿 EcoTracker</span>
        </div>
        <div class="p-6">
          <h3 class="text-2xl font-bold mb-3">EcoTracker</h3>
          <p class="text-gray-400 mb-4">A sustainability app that helps users track and reduce their carbon footprint through daily habits and challenges.</p>
          <div class="flex flex-wrap gap-2 mb-4">
            <span class="text-xs px-2 py-1 bg-emerald-500/20 text-emerald-300 rounded">React Native</span>
            <span class="text-xs px-2 py-1 bg-emerald-500/20 text-emerald-300 rounded">MongoDB</span>
            <span class="text-xs px-2 py-1 bg-emerald-500/20 text-emerald-300 rounded">Node.js</span>
          </div>
          <div class="flex gap-3">
            <a href="https://github.com/MiesieduoCodes/eco-tracker" class="flex items-center gap-2 text-sm text-gray-300 hover:text-white transition-colors">
              <svg class="w-4 h-4" fill="currentColor" viewBox="0 0 24 24"><path d="M12 0C5.37 0 0 5.37 0 12c0 5.31 3.435 9.795 8.205 11.385.6.105.825-.255.825-.57 0-.285-.015-1.23-.015-2.235-3.015.555-3.795-.735-4.035-1.41-.135-.345-.72-1.41-1.23-1.695-.42-.225-1.02-.78-.015-.795.945-.015 1.62.87 1.845 1.23 1.08 1.815 2.805 1.305 3.495.99.105-.78.42-1.305.765-1.605-2.67-.3-5.46-1.335-5.46-5.925 0-1.305.465-2.385 1.23-3.225-.12-.3-.54-1.53.12-3.18 0 0 1.005-.315 3.3 1.23.96-.27 1.98-.405 3-.405s2.04.135 3 .405c2.295-1.56 3.3-1.23 3.3-1.23.66 1.65.24 2.88.12 3.18.765.84 1.23 1.905 1.23 3.225 0 4.605-2.805 5.625-5.475 5.925.435.375.81 1.095.81 2.22 0 1.605-.015 2.895-.015 3.3 0 .315.225.69.825.57A12.02 12.02 0 0024 12c0-6.63-5.37-12-12-12z"/></svg>
              View Source
            </a>
            <span class="flex items-center gap-2 text-sm text-amber-400">
              <span class="w-2 h-2 bg-amber-400 rounded-full animate-pulse"></span>
              Coming Soon
            </span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- GitHub Stats -->
  <section class="py-20 px-4 md:px-8 max-w-6xl mx-auto">
    <div class="section-divider mb-16"></div>
    
    <div class="flex items-center gap-3 mb-12">
      <span class="text-4xl">📊</span>
      <h2 class="text-4xl font-bold gradient-text">GitHub Stats</h2>
    </div>
    
    <div class="text-center mb-8">
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=MiesieduoCodes&theme=tokyonight&hide_border=true&background=0D111700" 
           alt="GitHub Streak" class="inline-block rounded-xl max-w-full">
    </div>
    
    <div class="grid md:grid-cols-2 gap-6">
      <div class="glass-card rounded-xl p-4 flex items-center justify-center">
        <img src="https://github-readme-stats.vercel.app/api?username=MiesieduoCodes&show_icons=true&count_private=true&theme=tokyonight&hide_border=true&bg_color=0D111700" 
             alt="GitHub Stats" class="max-w-full">
      </div>
      <div class="glass-card rounded-xl p-4 flex items-center justify-center">
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MiesieduoCodes&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D111700" 
             alt="Top Languages" class="max-w-full">
      </div>
    </div>
  </section>

  <!-- Creative Side -->
  <section class="py-20 px-4 md:px-8 max-w-6xl mx-auto">
    <div class="section-divider mb-16"></div>
    
    <div class="flex items-center gap-3 mb-12">
      <span class="text-4xl">🎵</span>
      <h2 class="text-4xl font-bold gradient-text">My Creative Side</h2>
    </div>
    
    <div class="grid md:grid-cols-2 gap-8">
      <div class="glass-card rounded-2xl overflow-hidden group">
        <div class="h-48 bg-gradient-to-br from-indigo-600 via-purple-600 to-pink-500 flex items-center justify-center relative">
          <span class="text-8xl group-hover:scale-110 transition-transform">🥁</span>
        </div>
        <div class="p-6">
          <h3 class="text-2xl font-bold mb-3">Drumming</h3>
          <p class="text-gray-400">Performing with local bands and teaching rhythm to aspiring musicians. My drumming style blends jazz, rock, and African beats.</p>
        </div>
      </div>
      
      <div class="glass-card rounded-2xl overflow-hidden group">
        <div class="h-48 bg-gradient-to-br from-amber-500 via-orange-500 to-red-500 flex items-center justify-center relative">
          <span class="text-8xl group-hover:scale-110 transition-transform">📷</span>
        </div>
        <div class="p-6">
          <h3 class="text-2xl font-bold mb-3">Photography</h3>
          <p class="text-gray-400">Capturing the beauty of wildlife and landscapes. My work has been featured in local exhibitions and nature magazines.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Currently Vibing -->
  <section class="py-20 px-4 md:px-8 max-w-6xl mx-auto">
    <div class="section-divider mb-16"></div>
    
    <div class="flex items-center justify-center gap-3 mb-12">
      <span class="text-4xl">🎧</span>
      <h2 class="text-4xl font-bold gradient-text">Currently Vibing To</h2>
    </div>
    
    <div class="flex justify-center">
      <a href="https://spotify-github-profile.kittinanx.com/api/view?uid=31tnn4kym737p5yqxubls6xokqdu&redirect=true" class="glass-card rounded-2xl p-4 hover:bg-white/10 transition-all">
        <img src="https://spotify-github-profile.kittinanx.com/api/view?uid=31tnn4kym737p5yqxubls6xokqdu&cover_image=true&theme=default&show_offline=false&background_color=121212&interchange=false&bar_color=53b14f&bar_color_cover=false" alt="Spotify" class="rounded-xl">
      </a>
    </div>
  </section>

  <!-- Blog Posts -->
  <section class="py-20 px-4 md:px-8 max-w-6xl mx-auto">
    <div class="section-divider mb-16"></div>
    
    <div class="flex items-center gap-3 mb-12">
      <span class="text-4xl">📝</span>
      <h2 class="text-4xl font-bold gradient-text">Latest Blog Posts</h2>
    </div>
    
    <div class="space-y-4">
      <a href="#" class="glass-card rounded-xl p-6 block hover:bg-white/10 transition-all group">
        <div class="flex items-center justify-between">
          <div>
            <h3 class="text-lg font-semibold group-hover:text-indigo-400 transition-colors">How I Built a Real-time Animation Platform with React and Three.js</h3>
            <p class="text-gray-500 text-sm mt-1">Deep dive into modern web animation techniques</p>
          </div>
          <svg class="w-5 h-5 text-gray-500 group-hover:text-indigo-400 group-hover:translate-x-1 transition-all" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"/></svg>
        </div>
      </a>
      <a href="#" class="glass-card rounded-xl p-6 block hover:bg-white/10 transition-all group">
        <div class="flex items-center justify-between">
          <div>
            <h3 class="text-lg font-semibold group-hover:text-indigo-400 transition-colors">The Intersection of Music and Coding: My Journey as a Developer and Drummer</h3>
            <p class="text-gray-500 text-sm mt-1">Finding rhythm in code and creativity</p>
          </div>
          <svg class="w-5 h-5 text-gray-500 group-hover:text-indigo-400 group-hover:translate-x-1 transition-all" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"/></svg>
        </div>
      </a>
      <a href="#" class="glass-card rounded-xl p-6 block hover:bg-white/10 transition-all group">
        <div class="flex items-center justify-between">
          <div>
            <h3 class="text-lg font-semibold group-hover:text-indigo-400 transition-colors">5 Essential Tips for Optimizing React Performance</h3>
            <p class="text-gray-500 text-sm mt-1">Boost your React apps to the next level</p>
          </div>
          <svg class="w-5 h-5 text-gray-500 group-hover:text-indigo-400 group-hover:translate-x-1 transition-all" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"/></svg>
        </div>
      </a>
    </div>
  </section>

  <!-- Certifications -->
  <section class="py-20 px-4 md:px-8 max-w-6xl mx-auto">
    <div class="section-divider mb-16"></div>
    
    <div class="flex items-center gap-3 mb-12">
      <span class="text-4xl">🎓</span>
      <h2 class="text-4xl font-bold gradient-text">Certifications</h2>
    </div>
    
    <div class="grid md:grid-cols-3 gap-6">
      <div class="glass-card rounded-xl p-6 text-center hover:bg-white/10 transition-all">
        <div class="w-16 h-16 mx-auto mb-4 bg-orange-500/20 rounded-full flex items-center justify-center">
          <span class="text-3xl">☁️</span>
        </div>
        <h3 class="font-semibold text-orange-400">AWS Certified</h3>
        <p class="text-gray-500 text-sm">Developer Associate</p>
      </div>
      <div class="glass-card rounded-xl p-6 text-center hover:bg-white/10 transition-all">
        <div class="w-16 h-16 mx-auto mb-4 bg-green-500/20 rounded-full flex items-center justify-center">
          <span class="text-3xl">🍃</span>
        </div>
        <h3 class="font-semibold text-green-400">MongoDB Certified</h3>
        <p class="text-gray-500 text-sm">Database Administrator</p>
      </div>
      <div class="glass-card rounded-xl p-6 text-center hover:bg-white/10 transition-all">
        <div class="w-16 h-16 mx-auto mb-4 bg-cyan-500/20 rounded-full flex items-center justify-center">
          <span class="text-3xl">⚛️</span>
        </div>
        <h3 class="font-semibold text-cyan-400">React Certified</h3>
        <p class="text-gray-500 text-sm">Advanced Concepts</p>
      </div>
    </div>
  </section>

  <!-- Connect Section -->
  <section id="contact" class="py-20 px-4 md:px-8 max-w-6xl mx-auto">
    <div class="section-divider mb-16"></div>
    
    <div class="flex items-center justify-center gap-3 mb-12">
      <span class="text-4xl">🌐</span>
      <h2 class="text-4xl font-bold gradient-text">Connect With Me</h2>
    </div>
    
    <div class="flex flex-wrap justify-center gap-4 mb-12">
      <a href="https://github.com/MiesieduoCodes" class="glass-card px-6 py-3 rounded-xl flex items-center gap-3 hover:bg-white/10 transition-all hover:scale-105">
        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24"><path d="M12 0C5.37 0 0 5.37 0 12c0 5.31 3.435 9.795 8.205 11.385.6.105.825-.255.825-.57 0-.285-.015-1.23-.015-2.235-3.015.555-3.795-.735-4.035-1.41-.135-.345-.72-1.41-1.23-1.695-.42-.225-1.02-.78-.015-.795.945-.015 1.62.87 1.845 1.23 1.08 1.815 2.805 1.305 3.495.99.105-.78.42-1.305.765-1.605-2.67-.3-5.46-1.335-5.46-5.925 0-1.305.465-2.385 1.23-3.225-.12-.3-.54-1.53.12-3.18 0 0 1.005-.315 3.3 1.23.96-.27 1.98-.405 3-.405s2.04.135 3 .405c2.295-1.56 3.3-1.23 3.3-1.23.66 1.65.24 2.88.12 3.18.765.84 1.23 1.905 1.23 3.225 0 4.605-2.805 5.625-5.475 5.925.435.375.81 1.095.81 2.22 0 1.605-.015 2.895-.015 3.3 0 .315.225.69.825.57A12.02 12.02 0 0024 12c0-6.63-5.37-12-12-12z"/></svg>
        GitHub
      </a>
      <a href="https://linkedin.com/in/miesieduo-veria" class="glass-card px-6 py-3 rounded-xl flex items-center gap-3 hover:bg-blue-500/20 transition-all hover:scale-105 hover:text-blue-400">
        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24"><path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/></svg>
        LinkedIn
      </a>
      <a href="https://twitter.com/GoofyCodes" class="glass-card px-6 py-3 rounded-xl flex items-center gap-3 hover:bg-sky-500/20 transition-all hover:scale-105 hover:text-sky-400">
        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24"><path d="M23.953 4.57a10 10 0 01-2.825.775 4.958 4.958 0 002.163-2.723c-.951.555-2.005.959-3.127 1.184a4.92 4.92 0 00-8.384 4.482C7.69 8.095 4.067 6.13 1.64 3.162a4.822 4.822 0 00-.666 2.475c0 1.71.87 3.213 2.188 4.096a4.904 4.904 0 01-2.228-.616v.06a4.923 4.923 0 003.946 4.827 4.996 4.996 0 01-2.212.085 4.936 4.936 0 004.604 3.417 9.867 9.867 0 01-6.102 2.105c-.39 0-.779-.023-1.17-.067a13.995 13.995 0 007.557 2.209c9.053 0 13.998-7.496 13.998-13.985 0-.21 0-.42-.015-.63A9.935 9.935 0 0024 4.59z"/></svg>
        Twitter
      </a>
      <a href="https://www.instagram.com/goofy_did_this/" class="glass-card px-6 py-3 rounded-xl flex items-center gap-3 hover:bg-pink-500/20 transition-all hover:scale-105 hover:text-pink-400">
        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24"><path d="M12 0C8.74 0 8.333.015 7.053.072 5.775.132 4.905.333 4.14.63c-.789.306-1.459.717-2.126 1.384S.935 3.35.63 4.14C.333 4.905.131 5.775.072 7.053.012 8.333 0 8.74 0 12s.015 3.667.072 4.947c.06 1.277.261 2.148.558 2.913.306.788.717 1.459 1.384 2.126.667.666 1.336 1.079 2.126 1.384.766.296 1.636.499 2.913.558C8.333 23.988 8.74 24 12 24s3.667-.015 4.947-.072c1.277-.06 2.148-.262 2.913-.558.788-.306 1.459-.718 2.126-1.384.666-.667 1.079-1.335 1.384-2.126.296-.765.499-1.636.558-2.913.06-1.28.072-1.687.072-4.947s-.015-3.667-.072-4.947c-.06-1.277-.262-2.149-.558-2.913-.306-.789-.718-1.459-1.384-2.126C21.319 1.347 20.651.935 19.86.63c-.765-.297-1.636-.499-2.913-.558C15.667.012 15.26 0 12 0zm0 2.16c3.203 0 3.585.016 4.85.071 1.17.055 1.805.249 2.227.415.562.217.96.477 1.382.896.419.42.679.819.896 1.381.164.422.36 1.057.413 2.227.057 1.266.07 1.646.07 4.85s-.015 3.585-.074 4.85c-.061 1.17-.256 1.805-.421 2.227-.224.562-.479.96-.899 1.382-.419.419-.824.679-1.38.896-.42.164-1.065.36-2.235.413-1.274.057-1.649.07-4.859.07-3.211 0-3.586-.015-4.859-.074-1.171-.061-1.816-.256-2.236-.421-.569-.224-.96-.479-1.379-.899-.421-.419-.69-.824-.9-1.38-.165-.42-.359-1.065-.42-2.235-.045-1.26-.061-1.649-.061-4.844 0-3.196.016-3.586.061-4.861.061-1.17.255-1.814.42-2.234.21-.57.479-.96.9-1.381.419-.419.81-.689 1.379-.898.42-.166 1.051-.361 2.221-.421 1.275-.045 1.65-.06 4.859-.06l.045.03zm0 3.678c-3.405 0-6.162 2.76-6.162 6.162 0 3.405 2.76 6.162 6.162 6.162 3.405 0 6.162-2.76 6.162-6.162 0-3.405-2.76-6.162-6.162-6.162zM12 16c-2.21 0-4-1.79-4-4s1.79-4 4-4 4 1.79 4 4-1.79 4-4 4zm7.846-10.405c0 .795-.646 1.44-1.44 1.44-.795 0-1.44-.646-1.44-1.44 0-.794.646-1.439 1.44-1.439.793-.001 1.44.645 1.44 1.439z"/></svg>
        Instagram
      </a>
      <a href="https://www.facebook.com/Miesieduo-Veria" class="glass-card px-6 py-3 rounded-xl flex items-center gap-3 hover:bg-blue-600/20 transition-all hover:scale-105 hover:text-blue-500">
        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24"><path d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.47h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.47h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z"/></svg>
        Facebook
      </a>
    </div>
    
    <div class="flex flex-wrap justify-center gap-4">
      <a href="mailto:contact@goofycodes.dev" class="bg-gradient-to-r from-red-500 to-orange-500 px-8 py-4 rounded-xl flex items-center gap-3 font-semibold hover:opacity-90 transition-all hover:scale-105">
        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"/></svg>
        Send Email
      </a>
      <a href="https://calendly.com/goofycodes/30min" class="bg-gradient-to-r from-blue-500 to-indigo-500 px-8 py-4 rounded-xl flex items-center gap-3 font-semibold hover:opacity-90 transition-all hover:scale-105">
        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"/></svg>
        Schedule a Meeting
      </a>
    </div>
  </section>

  <!-- Support -->
  <section class="py-20 px-4 md:px-8 max-w-6xl mx-auto">
    <div class="section-divider mb-16"></div>
    
    <div class="text-center">
      <span class="text-6xl mb-6 block">☕</span>
      <h2 class="text-3xl font-bold mb-4">Support My Work</h2>
      <p class="text-gray-400 mb-8">If you like my projects and want to support me, you can buy me a coffee!</p>
      <a href="https://www.buymeacoffee.com/goofycodes" class="inline-flex items-center gap-3 bg-[#FFDD00] text-black px-8 py-4 rounded-xl font-bold hover:bg-[#ffed4a] transition-all hover:scale-105">
        <svg class="w-6 h-6" viewBox="0 0 24 24" fill="currentColor"><path d="M20.216 6.415l-.132-.666c-.119-.598-.388-1.163-1.001-1.379-.197-.069-.42-.098-.57-.241-.152-.143-.196-.366-.231-.572-.065-.378-.125-.756-.192-1.133-.057-.325-.102-.69-.25-.987-.195-.4-.597-.634-.996-.788a5.723 5.723 0 00-.626-.194c-1-.263-2.05-.36-3.077-.416a25.834 25.834 0 00-3.7.062c-.915.083-1.88.184-2.75.5-.318.116-.646.256-.888.501-.297.302-.393.77-.177 1.146.154.267.415.456.692.58.36.162.737.284 1.123.366 1.075.238 2.189.331 3.287.37 1.218.05 2.437.01 3.65-.118.299-.033.598-.073.896-.119.352-.054.578-.513.474-.834-.124-.383-.457-.531-.834-.473-.466.074-.96.108-1.382.146-1.177.08-2.358.082-3.536.006a22.228 22.228 0 01-1.157-.107c-.086-.01-.18-.025-.258-.036-.243-.036-.484-.08-.724-.13-.111-.027-.111-.185 0-.212h.005c.277-.06.557-.108.838-.147h.002c.131-.009.263-.032.394-.048a25.076 25.076 0 013.426-.12c.674.019 1.347.067 2.017.144l.228.031c.267.04.533.088.798.145.392.085.895.113 1.07.542.055.137.08.288.111.431l.319 1.484a.237.237 0 01-.199.284h-.003c-.037.006-.075.01-.112.015a36.704 36.704 0 01-4.743.295 37.059 37.059 0 01-4.699-.304c-.14-.017-.293-.042-.417-.06-.326-.048-.649-.108-.973-.161-.393-.065-.768-.032-1.123.161-.29.16-.527.404-.675.701-.154.316-.199.66-.267 1-.069.34-.176.707-.135 1.056.087.753.613 1.365 1.37 1.502a39.69 39.69 0 0011.343.376.483.483 0 01.535.53l-.071.697-1.018 9.907c-.041.41-.047.832-.125 1.237-.122.637-.553 1.028-1.182 1.171-.577.131-1.165.2-1.756.205-.656.004-1.31-.025-1.966-.022-.699.004-1.556-.06-2.095-.58-.475-.458-.54-1.174-.605-1.793l-.731-7.013-.322-3.094c-.037-.351-.286-.695-.678-.678-.336.015-.718.3-.678.679l.228 2.185.949 9.112c.147 1.344 1.174 2.068 2.446 2.272.742.12 1.503.144 2.257.156.966.016 1.942.053 2.892-.122 1.408-.258 2.465-1.198 2.616-2.657.34-3.332.683-6.663 1.024-9.995l.215-2.087a.484.484 0 01.39-.426c.402-.078.787-.212 1.074-.518.455-.488.546-1.124.385-1.766zm-1.478.772c-.145.137-.363.201-.578.233-2.416.359-4.866.54-7.308.46-1.748-.06-3.477-.254-5.207-.498-.17-.024-.353-.055-.47-.18-.22-.236-.111-.71-.054-.995.052-.26.152-.609.463-.646.484-.057 1.046.148 1.526.22.577.088 1.156.159 1.737.212 2.48.226 5.002.19 7.472-.14.45-.06.899-.13 1.345-.21.399-.072.84-.206 1.08.206.166.281.188.657.162.974a.544.544 0 01-.169.364z"/></svg>
        Buy Me A Coffee
      </a>
    </div>
  </section>

  <!-- Footer -->
  <footer class="py-12 px-4 border-t border-white/10">
    <div class="max-w-6xl mx-auto text-center">
      <div class="flex justify-center mb-6">
        <img src="https://komarev.com/ghpvc/?username=MiesieduoCodes&style=for-the-badge&color=6366F1" alt="Profile Views" class="rounded-lg">
      </div>
      <p class="text-gray-500 mb-4">Made with 💜 by GoofyCodes</p>
      <p class="text-gray-600 text-sm">© 2024 All rights reserved</p>
    </div>
  </footer>

  <script>
    // Smooth scroll
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
      anchor.addEventListener('click', function (e) {
        e.preventDefault();
        document.querySelector(this.getAttribute('href')).scrollIntoView({
          behavior: 'smooth'
        });
      });
    });

    // Intersection Observer for animations
    const observerOptions = {
      threshold: 0.1,
      rootMargin: '0px 0px -50px 0px'
    };

    const observer = new IntersectionObserver((entries) => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.style.opacity = '1';
          entry.target.style.transform = 'translateY(0)';
        }
      });
    }, observerOptions);

    document.querySelectorAll('section').forEach(section => {
      section.style.opacity = '0';
      section.style.transform = 'translateY(20px)';
      section.style.transition = 'opacity 0.6s ease, transform 0.6s ease';
      observer.observe(section);
    });

    // First section visible by default
    document.querySelector('section').style.opacity = '1';
    document.querySelector('section').style.transform = 'translateY(0)';
  </script>
</body>
</html>
