<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Abdelrahman Eid | STEM High School Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
  <script>
    tailwind.config = {
      darkMode: 'class',
      theme: {
        extend: {
          colors: {
            brand: {
              50: '#f0fdf4',
              500: '#10b981',
              600: '#059669',
              700: '#047857',
              900: '#064e3b',
            }
          }
        }
      }
    }
  </script>
</head>
<body class="bg-slate-50 text-slate-800 dark:bg-slate-900 dark:text-slate-100 transition-colors duration-300 font-sans antialiased">

  <!-- Header / Navigation -->
  <header class="sticky top-0 z-50 backdrop-blur-md bg-white/80 dark:bg-slate-900/80 border-b border-slate-200 dark:border-slate-800">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-16 flex items-center justify-between">
      <a href="#" class="text-xl font-bold tracking-tight text-emerald-600 dark:text-emerald-400">
        Abdelrahman<span class="text-slate-800 dark:text-slate-100">.Eid</span>
      </a>
      
      <nav class="hidden md:flex space-x-8 text-sm font-medium">
        <a href="#about" class="hover:text-emerald-600 dark:hover:text-emerald-400 transition">About</a>
        <a href="#certificates" class="hover:text-emerald-600 dark:hover:text-emerald-400 transition">Certificates</a>
        <a href="#projects" class="hover:text-emerald-600 dark:hover:text-emerald-400 transition">Projects</a>
        <a href="#skills" class="hover:text-emerald-600 dark:hover:text-emerald-400 transition">Skills</a>
        <a href="#contact" class="hover:text-emerald-600 dark:hover:text-emerald-400 transition">Contact</a>
      </nav>

      <div class="flex items-center space-x-4">
        <button id="themeToggle" class="p-2 rounded-lg bg-slate-100 dark:bg-slate-800 text-slate-600 dark:text-slate-300 hover:text-emerald-500">
          <i class="fa-solid fa-moon dark:hidden"></i>
          <i class="fa-solid fa-sun hidden dark:inline"></i>
        </button>
      </div>
    </div>
  </header>

  <!-- Hero Section -->
  <section id="about" class="py-20 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
    <div class="grid md:grid-cols-2 gap-12 items-center">
      <div>
        <span class="px-3 py-1 text-xs font-semibold uppercase tracking-wider text-emerald-700 bg-emerald-100 dark:bg-emerald-950 dark:text-emerald-300 rounded-full">
          STEM High School Student
        </span>
        <h1 class="mt-4 text-4xl sm:text-5xl font-extrabold text-slate-900 dark:text-white tracking-tight">
          Hi, I'm Abdelrahman Eid
        </h1>
        <p class="mt-4 text-lg text-slate-600 dark:text-slate-300">
          Student at STEM High School for Boys in 6th of October City. Enthusiastic about Astrophysics, Data Science, Networking, and Engineering Capstone Solutions.
        </p>
        <div class="mt-6 flex flex-wrap gap-4">
          <a href="#certificates" class="px-6 py-3 rounded-lg bg-emerald-600 text-white font-medium hover:bg-emerald-700 transition">View Certificates</a>
          <a href="#contact" class="px-6 py-3 rounded-lg border border-slate-300 dark:border-slate-700 font-medium hover:bg-slate-100 dark:hover:bg-slate-800 transition">Contact Me</a>
        </div>
      </div>
      <div class="bg-gradient-to-tr from-emerald-500 to-teal-700 rounded-2xl p-1 shadow-xl">
        <div class="bg-slate-900 rounded-xl p-6 text-slate-200">
          <div class="flex items-center space-x-2 mb-4">
            <div class="w-3 h-3 rounded-full bg-red-500"></div>
            <div class="w-3 h-3 rounded-full bg-yellow-500"></div>
            <div class="w-3 h-3 rounded-full bg-green-500"></div>
            <span class="text-xs text-slate-400 ml-2">student_profile.json</span>
          </div>
          <pre class="text-sm font-mono overflow-x-auto text-emerald-400"><code>{
  "name": "Abdelrahman Eid",
  "school": "STEM High School for Boys - 6th October",
  "interests": ["Astrophysics", "Data Science", "Cisco Networks"],
  "certifications": 4,
  "status": "Active Learner & Innovator"
}</code></pre>
        </div>
      </div>
    </div>
  </section>

  <!-- Certificates Section -->
  <section id="certificates" class="py-16 bg-slate-100 dark:bg-slate-800/50 transition-colors">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="text-center max-w-3xl mx-auto mb-12">
        <h2 class="text-3xl font-bold text-slate-900 dark:text-white">Certificates & Credentials</h2>
        <p class="mt-2 text-slate-600 dark:text-slate-400">Verified accomplishments in competitions, networking, data science, and management.</p>
      </div>

      <div class="grid gap-6 md:grid-cols-2 lg:grid-cols-2">
        
        <!-- IAAC Certificate -->
        <div class="bg-white dark:bg-slate-900 p-6 rounded-xl border border-slate-200 dark:border-slate-800 shadow-sm hover:shadow-md transition">
          <div class="flex items-start justify-between">
            <div class="p-3 rounded-lg bg-indigo-50 dark:bg-indigo-950/50 text-indigo-600 dark:text-indigo-400">
              <i class="fa-solid fa-user-astronaut text-2xl"></i>
            </div>
            <span class="text-xs font-semibold px-2.5 py-1 rounded-full bg-indigo-100 text-indigo-800 dark:bg-indigo-900 dark:text-indigo-200">May 2026</span>
          </div>
          <h3 class="mt-4 text-xl font-bold text-slate-900 dark:text-white">International Astronomy and Astrophysics Competition</h3>
          <p class="text-sm text-indigo-600 dark:text-indigo-400 font-medium">Qualification Round Certificate</p>
          <p class="mt-2 text-sm text-slate-600 dark:text-slate-400">
            Successfully passed the qualification round. Received special honour for submitting solutions as a digitally written document.
          </p>
          <div class="mt-4 pt-4 border-t border-slate-100 dark:border-slate-800 flex items-center justify-between text-xs text-slate-500 dark:text-slate-400">
            <span>Verify ID: <code class="text-slate-700 dark:text-slate-300 font-mono">QR-2026-1027F18E9E27</code></span>
            <a href="https://iaac.space/verify" target="_blank" class="text-emerald-600 hover:underline flex items-center gap-1 font-medium">Verify <i class="fa-solid fa-external-link text-[10px]"></i></a>
          </div>
        </div>

        <!-- Cisco Stakeholders -->
        <div class="bg-white dark:bg-slate-900 p-6 rounded-xl border border-slate-200 dark:border-slate-800 shadow-sm hover:shadow-md transition">
          <div class="flex items-start justify-between">
            <div class="p-3 rounded-lg bg-blue-50 dark:bg-blue-950/50 text-blue-600 dark:text-blue-400">
              <i class="fa-solid fa-people-group text-2xl"></i>
            </div>
            <span class="text-xs font-semibold px-2.5 py-1 rounded-full bg-blue-100 text-blue-800 dark:bg-blue-900 dark:text-blue-200">Apr 2026</span>
          </div>
          <h3 class="mt-4 text-xl font-bold text-slate-900 dark:text-white">Engaging Stakeholders for Success</h3>
          <p class="text-sm text-blue-600 dark:text-blue-400 font-medium">Cisco Networking Academy</p>
          <p class="mt-2 text-sm text-slate-600 dark:text-slate-400">
            Proficient in business value discovery, stakeholder trust models, Power Interest Grid prioritization, and structured interviewing.
          </p>
          <div class="mt-4 pt-4 border-t border-slate-100 dark:border-slate-800 flex items-center justify-between text-xs text-slate-500 dark:text-slate-400">
            <span>Cert ID: <code class="text-slate-700 dark:text-slate-300 font-mono">ed3fd7ea-...-e6caf660d655</code></span>
            <span class="text-emerald-600 font-medium"><i class="fa-solid fa-circle-check"></i> Verified</span>
          </div>
        </div>

        <!-- Cisco Data Science -->
        <div class="bg-white dark:bg-slate-900 p-6 rounded-xl border border-slate-200 dark:border-slate-800 shadow-sm hover:shadow-md transition">
          <div class="flex items-start justify-between">
            <div class="p-3 rounded-lg bg-emerald-50 dark:bg-emerald-950/50 text-emerald-600 dark:text-emerald-400">
              <i class="fa-solid fa-chart-line text-2xl"></i>
            </div>
            <span class="text-xs font-semibold px-2.5 py-1 rounded-full bg-emerald-100 text-emerald-800 dark:bg-emerald-900 dark:text-emerald-200">Apr 2026</span>
          </div>
          <h3 class="mt-4 text-xl font-bold text-slate-900 dark:text-white">Introduction to Data Science</h3>
          <p class="text-sm text-emerald-600 dark:text-emerald-400 font-medium">Cisco Networking Academy</p>
          <p class="mt-2 text-sm text-slate-600 dark:text-slate-400">
            Covered promises and challenges of data analytics, data foundations for AI/ML, and data analytics career pathways.
          </p>
          <div class="mt-4 pt-4 border-t border-slate-100 dark:border-slate-800 flex items-center justify-between text-xs text-slate-500 dark:text-slate-400">
            <span>Cert ID: <code class="text-slate-700 dark:text-slate-300 font-mono">425725e9-...-4f4616f4d165</code></span>
            <span class="text-emerald-600 font-medium"><i class="fa-solid fa-circle-check"></i> Verified</span>
          </div>
        </div>

        <!-- Cisco Packet Tracer -->
        <div class="bg-white dark:bg-slate-900 p-6 rounded-xl border border-slate-200 dark:border-slate-800 shadow-sm hover:shadow-md transition">
          <div class="flex items-start justify-between">
            <div class="p-3 rounded-lg bg-teal-50 dark:bg-teal-950/50 text-teal-600 dark:text-teal-400">
              <i class="fa-solid fa-network-wired text-2xl"></i>
            </div>
            <span class="text-xs font-semibold px-2.5 py-1 rounded-full bg-teal-100 text-teal-800 dark:bg-teal-900 dark:text-teal-200">Apr 2026</span>
          </div>
          <h3 class="mt-4 text-xl font-bold text-slate-900 dark:text-white">Getting Started with Cisco Packet Tracer</h3>
          <p class="text-sm text-teal-600 dark:text-teal-400 font-medium">Cisco Networking Academy</p>
          <p class="mt-2 text-sm text-slate-600 dark:text-slate-400">
            Gained foundational knowledge in simulation, visualization, and network modeling using Cisco Packet Tracer.
          </p>
          <div class="mt-4 pt-4 border-t border-slate-100 dark:border-slate-800 flex items-center justify-between text-xs text-slate-500 dark:text-slate-400">
            <span>Cert ID: <code class="text-slate-700 dark:text-slate-300 font-mono">42528ad5-...-c82817685f5c</code></span>
            <span class="text-emerald-600 font-medium"><i class="fa-solid fa-circle-check"></i> Verified</span>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="py-16 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="bg-emerald-600 text-white rounded-2xl p-8 md:p-12 text-center">
      <h2 class="text-3xl font-bold">Let's Connect & Collaborate</h2>
      <p class="mt-2 text-emerald-100">STEM High School for Boys, 6th of October City, Egypt</p>
      <a href="mailto:abdelrahman-1025022@stemoctober.moe.edu.eg" class="mt-6 inline-block bg-white text-emerald-700 font-semibold px-6 py-3 rounded-lg hover:bg-slate-100 transition">
        Send Email
      </a>
    </div>
  </section>

  <footer class="py-6 border-t border-slate-200 dark:border-slate-800 text-center text-sm text-slate-500">
    &copy; 2026 Abdelrahman Eid. All rights reserved.
  </footer>

  <script>
    const themeToggleBtn = document.getElementById('themeToggle');
    themeToggleBtn.addEventListener('click', () => {
      document.documentElement.classList.toggle('dark');
    });
  </script>
</body>
</html>
