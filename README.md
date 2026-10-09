
symon Kyle garcia <symonkyleg@gmail.com>
4:34 PM (0 minutes ago)
to me

```html
<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Symon Kyle Garcia | Virtual Assistant & Executive Support Specialist</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Lucide Icons CDN -->
    <script src="https://unpkg.com/lucide@latest"></script>
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
   
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Plus Jakarta Sans', 'sans-serif'],
                    },
                    colors: {
                        accent: {
                            50: 'var(--color-accent-50)',
                            100: 'var(--color-accent-100)',
                            500: 'var(--color-accent-500)',
                            600: 'var(--color-accent-600)',
                            700: 'var(--color-accent-700)',
                        }
                    }
                }
            }
        }
    </script>
    <style>
        /* Theme Definitions */
        :root[data-theme="navy"] {
            --bg-primary: #0b132b;
            --bg-secondary: #1c2541;
            --bg-card: rgba(28, 37, 65, 0.7);
            --bg-card-hover: rgba(58, 80, 107, 0.5);
            --text-main: #ffffff;
            --text-muted: #94a3b8;
            --border-color: rgba(255, 255, 255, 0.1);
            --color-accent-50: #eff6ff;
            --color-accent-100: #dbeafe;
            --color-accent-500: #3b82f6;
            --color-accent-600: #2563eb;
            --color-accent-700: #1d4ed8;
            --badge-bg: rgba(59, 130, 246, 0.15);
            --badge-text: #60a5fa;
        }

        :root[data-theme="slate"] {
            --bg-primary: #0f172a;
            --bg-secondary: #1e293b;
            --bg-card: rgba(30, 41, 59, 0.7);
            --bg-card-hover: rgba(51, 65, 85, 0.6);
            --text-main: #f8fafc;
            --text-muted: #94a3b8;
            --border-color: rgba(255, 255, 255, 0.1);
            --color-accent-50: #f0fdf4;
            --color-accent-100: #dcfce7;
            --color-accent-500: #06b6d4;
            --color-accent-600: #0891b2;
            --color-accent-700: #0e7490;
            --badge-bg: rgba(6, 182, 212, 0.15);
            --badge-text: #22d3ee;
        }

        :root[data-theme="gold"] {
            --bg-primary: #12100e;
            --bg-secondary: #241f1c;
            --bg-card: rgba(36, 31, 28, 0.8);
            --bg-card-hover: rgba(54, 46, 41, 0.7);
            --text-main: #fafaf9;
            --text-muted: #a8a29e;
            --border-color: rgba(217, 119, 6, 0.2);
            --color-accent-50: #fffbeb;
            --color-accent-100: #fef3c7;
            --color-accent-500: #d97706;
            --color-accent-600: #b45309;
            --color-accent-700: #92400e;
            --badge-bg: rgba(217, 119, 6, 0.15);
            --badge-text: #fbbf24;
        }

        :root[data-theme="emerald"] {
            --bg-primary: #062016;
            --bg-secondary: #0b3826;
            --bg-card: rgba(11, 56, 38, 0.7);
            --bg-card-hover: rgba(18, 84, 57, 0.6);
            --text-main: #f0fdf4;
            --text-muted: #86efac;
            --border-color: rgba(34, 197, 94, 0.2);
            --color-accent-50: #f0fdf4;
            --color-accent-100: #dcfce7;
            --color-accent-500: #10b981;
            --color-accent-600: #059669;
            --color-accent-700: #047857;
            --badge-bg: rgba(16, 185, 129, 0.15);
            --badge-text: #34d399;
        }

        :root[data-theme="light"] {
            --bg-primary: #f8fafc;
            --bg-secondary: #ffffff;
            --bg-card: #ffffff;
            --bg-card-hover: #f1f5f9;
            --text-main: #0f172a;
            --text-muted: #64748b;
            --border-color: rgba(0, 0, 0, 0.1);
            --color-accent-50: #eff6ff;
            --color-accent-100: #dbeafe;
            --color-accent-500: #2563eb;
            --color-accent-600: #1d4ed8;
            --color-accent-700: #1e40af;
            --badge-bg: rgba(37, 99, 235, 0.1);
            --badge-text: #1d4ed8;
        }

        body {
            background-color: var(--bg-primary);
            color: var(--text-main);
            transition: background-color 0.3s ease, color 0.3s ease;
        }

        .theme-card {
            background-color: var(--bg-card);
            border-color: var(--border-color);
        }

        .theme-card:hover {
            background-color: var(--bg-card-hover);
        }

        .theme-secondary {
            background-color: var(--bg-secondary);
        }

        .theme-text-muted {
            color: var(--text-muted);
        }

        .theme-border {
            border-color: var(--border-color);
        }

        .theme-badge {
            background-color: var(--badge-bg);
            color: var(--badge-text);
        }

        .glass-header {
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
            background-color: rgba(11, 19, 43, 0.75);
        }
    </style>
</head>
<body class="font-sans antialiased min-h-screen flex flex-col justify-between selection:bg-blue-500 selection:text-white">

    <!-- Navigation Header -->
    <header class="fixed top-0 left-0 right-0 z-40 border-b theme-border transition-all duration-300 backdrop-blur-md bg-opacity-80" id="navbar">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
                <!-- Brand / Logo -->
                <a href="#" class="flex items-center gap-3 group">
                    <div class="w-10 h-10 rounded-xl bg-gradient-to-tr from-blue-600 to-indigo-500 flex items-center justify-center text-white font-bold text-lg shadow-lg shadow-blue-500/20 group-hover:scale-105 transition-transform duration-300">
                        SG
                    </div>
                    <div>
                        <span class="text-lg font-bold tracking-tight block leading-tight">Symon Kyle Garcia</span>
                        <span class="text-xs theme-text-muted font-medium block">Executive Assistant</span>
                    </div>
                </a>

                <!-- Desktop Nav Links -->
                <nav class="hidden md:flex items-center gap-8 text-sm font-medium">
                    <a href="#about" class="hover:text-blue-500 transition-colors">About</a>
                    <a href="#services" class="hover:text-blue-500 transition-colors">Services</a>
                    <a href="#workflow" class="hover:text-blue-500 transition-colors">How I Work</a>
                    <a href="#contact" class="hover:text-blue-500 transition-colors">Contact</a>
                </nav>

                <!-- Action Button -->
                <div class="hidden sm:flex items-center gap-4">
                    <a href="#contact" class="px-5 py-2.5 rounded-full text-sm font-semibold text-white bg-gradient-to-r from-blue-600 to-indigo-600 hover:from-blue-500 hover:to-indigo-500 shadow-md shadow-blue-500/20 transition-all hover:scale-105 active:scale-95">
                        Hire Me
                    </a>
                </div>

                <!-- Mobile menu button -->
                <button id="mobile-menu-btn" class="md:hidden p-2 rounded-lg theme-card border theme-border text-gray-300 hover:text-white focus:outline-none">
                    <i data-lucide="menu" class="w-6 h-6"></i>
                </button>
            </div>
        </div>

        <!-- Mobile Navigation Menu -->
        <div id="mobile-menu" class="hidden md:hidden border-b theme-border px-4 pt-2 pb-6 space-y-3 theme-secondary">
            <a href="#about" class="block py-2 text-base font-medium border-b theme-border">About</a>
            <a href="#services" class="block py-2 text-base font-medium border-b theme-border">Services</a>
            <a href="#workflow" class="block py-2 text-base font-medium border-b theme-border">How I Work</a>
            <a href="#contact" class="block py-2 text-base font-medium border-b theme-border">Contact</a>
            <a href="#contact" class="inline-block w-full text-center mt-2 px-5 py-3 rounded-xl text-sm font-semibold text-white bg-blue-600">
                Hire Me
            </a>
        </div>
    </header>

    <main class="pt-24">
        <!-- Hero Section -->
        <section class="relative min-h-[85vh] flex items-center justify-center px-4 sm:px-6 lg:px-8 py-12 overflow-hidden">
            <!-- Background Decorative Glows -->
            <div class="absolute top-1/4 left-1/2 -translate-x-1/2 -translate-y-1/2 w-[500px] h-[500px] bg-blue-500/10 rounded-full blur-3xl pointer-events-none"></div>
           
            <div class="max-w-7xl mx-auto w-full grid grid-cols-1 lg:grid-cols-12 gap-12 items-center relative z-10">
               
                <!-- Hero Left Column: Intro Text -->
                <div class="lg:col-span-7 text-center lg:text-left space-y-6">
                    <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full text-xs font-semibold theme-badge border theme-border">
                        <span class="w-2 h-2 rounded-full bg-emerald-500 animate-pulse"></span>
                        Available for Full-time & Project Roles
                    </div>

                    <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold tracking-tight leading-tight">
                        Hi, I'm <span class="bg-clip-text text-transparent bg-gradient-to-r from-blue-400 via-indigo-400 to-purple-400">Symon Kyle Garcia</span>
                    </h1>

                    <p class="text-xl sm:text-2xl font-medium text-blue-400/90">
                        Virtual Assistant & Executive Support Specialist
                    </p>

                    <p class="text-base sm:text-lg theme-text-muted max-w-2xl leading-relaxed">
                        Helping business leaders, executives, and remote teams streamline daily operations, organize digital workflows, and regain valuable time through dependable administrative excellence.
                    </p>

                    <!-- CTAs & Stats -->
                    <div class="pt-4 flex flex-col sm:flex-row items-center justify-center lg:justify-start gap-4">
                        <a href="#services" class="w-full sm:w-auto px-8 py-4 rounded-xl text-base font-semibold text-white bg-gradient-to-r from-blue-600 to-indigo-600 hover:from-blue-500 hover:to-indigo-500 shadow-lg shadow-blue-500/25 transition-all hover:-translate-y-0.5 active:translate-y-0 flex items-center justify-center gap-2">
                            <span>Explore Services</span>
                            <i data-lucide="arrow-down" class="w-4 h-4"></i>
                        </a>
                        <a href="#contact" class="w-full sm:w-auto px-8 py-4 rounded-xl text-base font-semibold theme-card border theme-border hover:border-blue-500/50 transition-all flex items-center justify-center gap-2">
                            <span>Get In Touch</span>
                            <i data-lucide="mail" class="w-4 h-4"></i>
                        </a>
                    </div>

                    <!-- Quick Metrics -->
                    <div class="pt-8 border-t theme-border grid grid-cols-3 gap-4 text-center lg:text-left">
                        <div>
                            <div class="text-2xl sm:text-3xl font-extrabold text-blue-400">100%</div>
                            <div class="text-xs theme-text-muted mt-1">Zero-Inbox Commitment</div>
                        </div>
                        <div>
                            <div class="text-2xl sm:text-3xl font-extrabold text-indigo-400">24/7</div>
                            <div class="text-xs theme-text-muted mt-1">Reliable Support</div>
                        </div>
                        <div>
                            <div class="text-2xl sm:text-3xl font-extrabold text-purple-400">9+</div>
                            <div class="text-xs theme-text-muted mt-1">Core Operational Services</div>
                        </div>
                    </div>
                </div>

                <!-- Hero Right Column: Photo Avatar & Interactive Image Picker -->
                <div class="lg:col-span-5 flex justify-center">
                    <div class="relative group max-w-md w-full">
                        <!-- Card Border Glow -->
                        <div class="absolute -inset-1 bg-gradient-to-r from-blue-600 to-indigo-600 rounded-3xl blur opacity-30 group-hover:opacity-60 transition duration-500"></div>
                       
                        <div class="relative theme-card border theme-border rounded-3xl p-6 sm:p-8 flex flex-col items-center text-center shadow-2xl">
                            <!-- Image Frame -->
                            <div class="relative w-48 h-48 sm:w-56 sm:h-56 rounded-full overflow-hidden border-4 border-blue-500/30 shadow-xl mb-6 bg-slate-800 flex items-center justify-center group-hover:border-blue-500 transition-colors">
                                <img id="profile-img" src="https://images.unsplash.com/photo-1534528741775-53994a69daeb?auto=format&fit=crop&q=80&w=800" alt="Symon Kyle Garcia" class="w-full h-full object-cover">
                               
                                <!-- Hover Upload Overlay -->
                                <label for="image-upload" class="absolute inset-0 bg-black/60 opacity-0 group-hover:opacity-100 flex flex-col items-center justify-center text-white cursor-pointer transition-opacity duration-300 p-2">
                                    <i data-lucide="camera" class="w-8 h-8 mb-1"></i>
                                    <span class="text-xs font-semibold">Change Photo</span>
                                </label>
                                <input type="file" id="image-upload" accept="image/*" class="hidden">
                            </div>

                            <h3 class="text-xl font-bold">Symon Kyle Garcia</h3>
                            <p class="text-sm text-blue-400 font-medium mb-3">Professional Virtual Assistant</p>
                           
                            <p class="text-xs theme-text-muted leading-relaxed mb-6">
                                Specialized in calendar management, data handling, customer response systems, and seamless remote operations.
                            </p>

                            <!-- Social / Quick Links -->
                            <div class="flex items-center gap-3">
                                <a href="mailto:symonkyleg@gmail.com" class="p-2.5 rounded-xl theme-card border theme-border hover:border-blue-500 hover:text-blue-400 transition-colors" title="Email Symon">
                                    <i data-lucide="mail" class="w-5 h-5"></i>
                                </a>
                                <a href="tel:09391088094" class="p-2.5 rounded-xl theme-card border theme-border hover:border-blue-500 hover:text-blue-400 transition-colors" title="Call Symon">
                                    <i data-lucide="phone" class="w-5 h-5"></i>
                                </a>
                                <button onclick="copyEmail()" class="p-2.5 rounded-xl theme-card border theme-border hover:border-blue-500 hover:text-blue-400 transition-colors flex items-center gap-1.5 text-xs font-medium" title="Copy Email">
                                    <i data-lucide="copy" class="w-4 h-4"></i>
                                    <span id="copy-text">Copy Email</span>
                                </button>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </section>

        <!-- About Section -->
        <section id="about" class="py-20 px-4 sm:px-6 lg:px-8 theme-secondary border-y theme-border">
            <div class="max-w-5xl mx-auto">
                <div class="text-center max-w-3xl mx-auto mb-12">
                    <h2 class="text-xs font-bold uppercase tracking-widest text-blue-400 mb-2">About Me</h2>
                    <h3 class="text-3xl sm:text-4xl font-extrabold tracking-tight">Your Partner in Operational Efficiency</h3>
                    <p class="text-base sm:text-lg theme-text-muted mt-4">
                        I bridge the gap between overwhelmed schedules and seamless administrative harmony.
                    </p>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                    <div class="p-6 rounded-2xl theme-card border theme-border space-y-3">
                        <div class="w-12 h-12 rounded-xl bg-blue-500/10 text-blue-400 flex items-center justify-center">
                            <i data-lucide="zap" class="w-6 h-6"></i>
                        </div>
                        <h4 class="text-lg font-bold">Proactive Execution</h4>
                        <p class="text-sm theme-text-muted">Anticipating executive needs before bottlenecks happen, keeping projects moving forward smoothly.</p>
                    </div>

                    <div class="p-6 rounded-2xl theme-card border theme-border space-y-3">
                        <div class="w-12 h-12 rounded-xl bg-indigo-500/10 text-indigo-400 flex items-center justify-center">
                            <i data-lucide="shield-check" class="w-6 h-6"></i>
                        </div>
                        <h4 class="text-lg font-bold">Reliable & Confidential</h4>
                        <p class="text-sm theme-text-muted">Handling sensitive executive data, client communications, and financials with complete discretion.</p>
                    </div>

                    <div class="p-6 rounded-2xl theme-card border theme-border space-y-3">
                        <div class="w-12 h-12 rounded-xl bg-purple-500/10 text-purple-400 flex items-center justify-center">
                            <i data-lucide="sliders" class="w-6 h-6"></i>
                        </div>
                        <h4 class="text-lg font-bold">Organized & Systematic</h4>
                        <p class="text-sm theme-text-muted">Transforming chaotic drives, inboxes, and schedules into structured, easy-to-navigate systems.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Services Section -->
        <section id="services" class="py-24 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-xs font-bold uppercase tracking-widest text-blue-400 mb-2">Services Provided</h2>
                <h3 class="text-3xl sm:text-5xl font-extrabold tracking-tight">Core Competencies & Support</h3>
                <p class="text-base sm:text-lg theme-text-muted mt-4">
                    Comprehensive virtual assistance designed to give you hours back in your workweek.
                </p>
            </div>

            <!-- 9 Services Grid -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
               
                <!-- Service 1 -->
                <div class="p-8 rounded-2xl theme-card border theme-border hover:border-blue-500/50 transition-all duration-300 hover:-translate-y-1 group flex flex-col justify-between">
                    <div>
                        <div class="w-14 h-14 rounded-2xl bg-blue-500/10 text-blue-400 flex items-center justify-center mb-6 group-hover:scale-110 transition-transform">
                            <i data-lucide="mail" class="w-7 h-7"></i>
                        </div>
                        <h4 class="text-xl font-bold mb-3">Email & Inbox Management</h4>
                        <p class="text-sm theme-text-muted leading-relaxed">
                            Sorting, labeling, responding to routine inquiries, and maintaining a strict zero-inbox system so you never miss crucial correspondence.
                        </p>
                    </div>
                    <div class="mt-6 pt-4 border-t theme-border flex items-center text-xs font-semibold text-blue-400 gap-1">
                        <span>Zero Inbox Guarantee</span>
                    </div>
                </div>

                <!-- Service 2 -->
                <div class="p-8 rounded-2xl theme-card border theme-border hover:border-blue-500/50 transition-all duration-300 hover:-translate-y-1 group flex flex-col justify-between">
                    <div>
                        <div class="w-14 h-14 rounded-2xl bg-indigo-500/10 text-indigo-400 flex items-center justify-center mb-6 group-hover:scale-110 transition-transform">
                            <i data-lucide="calendar" class="w-7 h-7"></i>
                        </div>
                        <h4 class="text-xl font-bold mb-3">Calendar & Schedule Management</h4>
                        <p class="text-sm theme-text-muted leading-relaxed">
                            Setting appointments, managing meeting requests, sending reminders, and seamlessly setting up Zoom or Google Meet links.
                        </p>
                    </div>
                    <div class="mt-6 pt-4 border-t theme-border flex items-center text-xs font-semibold text-indigo-400 gap-1">
                        <span>Conflict-Free Scheduling</span>
                    </div>
                </div>

                <!-- Service 3 -->
                <div class="p-8 rounded-2xl theme-card border theme-border hover:border-blue-500/50 transition-all duration-300 hover:-translate-y-1 group flex flex-col justify-between">
                    <div>
                        <div class="w-14 h-14 rounded-2xl bg-purple-500/10 text-purple-400 flex items-center justify-center mb-6 group-hover:scale-110 transition-transform">
                            <i data-lucide="plane" class="w-7 h-7"></i>
                        </div>
                        <h4 class="text-xl font-bold mb-3">Travel Coordination</h4>
                        <p class="text-sm theme-text-muted leading-relaxed">
                            Booking flights, accommodation, and ground transportation, as well as creating detailed, hassle-free travel itineraries.
                        </p>
                    </div>
                    <div class="mt-6 pt-4 border-t theme-border flex items-center text-xs font-semibold text-purple-400 gap-1">
                        <span>End-to-End Itineraries</span>
                    </div>
                </div>

                <!-- Service 4 -->
                <div class="p-8 rounded-2xl theme-card border theme-border hover:border-blue-500/50 transition-all duration-300 hover:-translate-y-1 group flex flex-col justify-between">
                    <div>
                        <div class="w-14 h-14 rounded-2xl bg-cyan-500/10 text-cyan-400 flex items-center justify-center mb-6 group-hover:scale-110 transition-transform">
                            <i data-lucide="folder-tree" class="w-7 h-7"></i>
                        </div>
                        <h4 class="text-xl font-bold mb-3">File & Cloud Organization</h4>
                        <p class="text-sm theme-text-muted leading-relaxed">
                            Keeping Google Drive, Dropbox, or OneDrive structured, meticulously labeled, permission-controlled, and regularly updated.
                        </p>
                    </div>
                    <div class="mt-6 pt-4 border-t theme-border flex items-center text-xs font-semibold text-cyan-400 gap-1">
                        <span>Structured Repositories</span>
                    </div>
                </div>

                <!-- Service 5 -->
                <div class="p-8 rounded-2xl theme-card border theme-border hover:border-blue-500/50 transition-all duration-300 hover:-translate-y-1 group flex flex-col justify-between">
                    <div>
                        <div class="w-14 h-14 rounded-2xl bg-emerald-500/10 text-emerald-400 flex items-center justify-center mb-6 group-hover:scale-110 transition-transform">
                            <i data-lucide="database" class="w-7 h-7"></i>
                        </div>
                        <h4 class="text-xl font-bold mb-3">Data Entry & CRM Updates</h4>
                        <p class="text-sm theme-text-muted leading-relaxed">
                            Inputting customer details, updating CRM systems, transcribing meeting notes, and keeping tracking spreadsheets completely organized.
                        </p>
                    </div>
                    <div class="mt-6 pt-4 border-t theme-border flex items-center text-xs font-semibold text-emerald-400 gap-1">
                        <span>High Accuracy & Precision</span>
                    </div>
                </div>

                <!-- Service 6 -->
                <div class="p-8 rounded-2xl theme-card border theme-border hover:border-blue-500/50 transition-all duration-300 hover:-translate-y-1 group flex flex-col justify-between">
                    <div>
                        <div class="w-14 h-14 rounded-2xl bg-amber-500/10 text-amber-400 flex items-center justify-center mb-6 group-hover:scale-110 transition-transform">
                            <i data-lucide="globe" class="w-7 h-7"></i>
                        </div>
                        <h4 class="text-xl font-bold mb-3">Web & Topic Research</h4>
                        <p class="text-sm theme-text-muted leading-relaxed">
                            Sourcing accurate information on competitors, industry trends, market opportunities, products, or potential software/tools.
                        </p>
                    </div>
                    <div class="mt-6 pt-4 border-t theme-border flex items-center text-xs font-semibold text-amber-400 gap-1">
                        <span>Actionable Insights</span>
                    </div>
                </div>

                <!-- Service 7 -->
                <div class="p-8 rounded-2xl theme-card border theme-border hover:border-blue-500/50 transition-all duration-300 hover:-translate-y-1 group flex flex-col justify-between">
                    <div>
                        <div class="w-14 h-14 rounded-2xl bg-rose-500/10 text-rose-400 flex items-center justify-center mb-6 group-hover:scale-110 transition-transform">
                            <i data-lucide="file-text" class="w-7 h-7"></i>
                        </div>
                        <h4 class="text-xl font-bold mb-3">Document Formatting</h4>
                        <p class="text-sm theme-text-muted leading-relaxed">
                            Formatting PDFs, Word documents, and creating clean, visually engaging Google Slides or PowerPoint presentations for meetings.
                        </p>
                    </div>
                    <div class="mt-6 pt-4 border-t theme-border flex items-center text-xs font-semibold text-rose-400 gap-1">
                        <span>Polished Presentations</span>
                    </div>
                </div>

                <!-- Service 8 -->
                <div class="p-8 rounded-2xl theme-card border theme-border hover:border-blue-500/50 transition-all duration-300 hover:-translate-y-1 group flex flex-col justify-between">
                    <div>
                        <div class="w-14 h-14 rounded-2xl bg-teal-500/10 text-teal-400 flex items-center justify-center mb-6 group-hover:scale-110 transition-transform">
                            <i data-lucide="headphones" class="w-7 h-7"></i>
                        </div>
                        <h4 class="text-xl font-bold mb-3">Customer Support</h4>
                        <p class="text-sm theme-text-muted leading-relaxed">
                            Responding promptly to common customer inquiries via live chat, email, or ticketing systems like Zendesk with empathy and clarity.
                        </p>
                    </div>
                    <div class="mt-6 pt-4 border-t theme-border flex items-center text-xs font-semibold text-teal-400 gap-1">
                        <span>Zendesk & Chat Ready</span>
                    </div>
                </div>

                <!-- Service 9 -->
                <div class="p-8 rounded-2xl theme-card border theme-border hover:border-blue-500/50 transition-all duration-300 hover:-translate-y-1 group flex flex-col justify-between">
                    <div>
                        <div class="w-14 h-14 rounded-2xl bg-orange-500/10 text-orange-400 flex items-center justify-center mb-6 group-hover:scale-110 transition-transform">
                            <i data-lucide="receipt" class="w-7 h-7"></i>
                        </div>
                        <h4 class="text-xl font-bold mb-3">Invoicing & Expense Tracking</h4>
                        <p class="text-sm theme-text-muted leading-relaxed">
                            Generating basic invoices, following up on unpaid bills, and logging weekly business expenses in software like QuickBooks or Excel.
                        </p>
                    </div>
                    <div class="mt-6 pt-4 border-t theme-border flex items-center text-xs font-semibold text-orange-400 gap-1">
                        <span>QuickBooks & Sheet Management</span>
                    </div>
                </div>

            </div>
        </section>

        <!-- Workflow Section -->
        <section id="workflow" class="py-20 px-4 sm:px-6 lg:px-8 theme-secondary border-y theme-border">
            <div class="max-w-5xl mx-auto">
                <div class="text-center max-w-3xl mx-auto mb-16">
                    <h2 class="text-xs font-bold uppercase tracking-widest text-blue-400 mb-2">Workflow Integration</h2>
                    <h3 class="text-3xl sm:text-4xl font-extrabold tracking-tight">How We'll Work Together</h3>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-4 gap-6 relative">
                    <div class="text-center space-y-3">
                        <div class="w-10 h-10 rounded-full bg-blue-600 text-white font-bold flex items-center justify-center mx-auto text-sm">1</div>
                        <h4 class="font-bold">Discovery</h4>
                        <p class="text-xs theme-text-muted">Understanding your current bottlenecks, tools, and preferred communication style.</p>
                    </div>

                    <div class="text-center space-y-3">
                        <div class="w-10 h-10 rounded-full bg-indigo-600 text-white font-bold flex items-center justify-center mx-auto text-sm">2</div>
                        <h4 class="font-bold">Setup & Access</h4>
                        <p class="text-xs theme-text-muted">Setting up secure logins, delegate permissions, and task management channels.</p>
                    </div>

                    <div class="text-center space-y-3">
                        <div class="w-10 h-10 rounded-full bg-purple-600 text-white font-bold flex items-center justify-center mx-auto text-sm">3</div>
                        <h4 class="font-bold">Execution</h4>
                        <p class="text-xs theme-text-muted">Daily proactive management of your inbox, schedule, and recurring tasks.</p>
                    </div>

                    <div class="text-center space-y-3">
                        <div class="w-10 h-10 rounded-full bg-emerald-600 text-white font-bold flex items-center justify-center mx-auto text-sm">4</div>
                        <h4 class="font-bold">Review & Adapt</h4>
                        <p class="text-xs theme-text-muted">Regular check-ins to refine workflows and adapt as your business expands.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="py-24 px-4 sm:px-6 lg:px-8 max-w-5xl mx-auto">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-start">
               
                <!-- Contact Info -->
                <div class="lg:col-span-5 space-y-6">
                    <div>
                        <h2 class="text-xs font-bold uppercase tracking-widest text-blue-400 mb-2">Get In Touch</h2>
                        <h3 class="text-3xl font-extrabold tracking-tight">Let's Simplify Your Workday</h3>
                        <p class="text-sm theme-text-muted mt-3 leading-relaxed">
                            Ready to delegate tasks and streamline your operations? Reach out via phone or email, and I'll get back to you promptly.
                        </p>
                    </div>

                    <div class="space-y-4 pt-4">
                        <!-- Email Card -->
                        <div class="flex items-center justify-between p-4 rounded-xl theme-card border theme-border">
                            <div class="flex items-center gap-4">
                                <div class="p-3 rounded-lg bg-blue-500/10 text-blue-400">
                                    <i data-lucide="mail" class="w-5 h-5"></i>
                                </div>
                                <div>
                                    <div class="text-xs theme-text-muted">Email Directly</div>
                                    <div class="text-sm font-semibold select-all">symonkyleg@gmail.com</div>
                                </div>
                            </div>
                            <a href="mailto:symonkyleg@gmail.com" class="p-2 rounded-lg bg-blue-600 hover:bg-blue-500 text-white transition-colors" title="Send Email">
                                <i data-lucide="send" class="w-4 h-4"></i>
                            </a>
                        </div>

                        <!-- Phone Card -->
                        <div class="flex items-center justify-between p-4 rounded-xl theme-card border theme-border">
                            <div class="flex items-center gap-4">
                                <div class="p-3 rounded-lg bg-emerald-500/10 text-emerald-400">
                                    <i data-lucide="phone" class="w-5 h-5"></i>
                                </div>
                                <div>
                                    <div class="text-xs theme-text-muted">Mobile / Call / Viber</div>
                                    <div class="text-sm font-semibold select-all">09391088094</div>
                                </div>
                            </div>
                            <a href="tel:09391088094" class="p-2 rounded-lg bg-emerald-600 hover:bg-emerald-500 text-white transition-colors" title="Call Now">
                                <i data-lucide="phone-call" class="w-4 h-4"></i>
                            </a>
                        </div>

                        <!-- Availability Card -->
                        <div class="flex items-center gap-4 p-4 rounded-xl theme-card border theme-border">
                            <div class="p-3 rounded-lg bg-indigo-500/10 text-indigo-400">
                                <i data-lucide="clock" class="w-5 h-5"></i>
                            </div>
                            <div>
                                <div class="text-xs theme-text-muted">Availability</div>
                                <div class="text-sm font-semibold">Flexible / Full-Time Remote</div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Contact Form -->
                <div class="lg:col-span-7">
                    <form id="contact-form" onsubmit="handleFormSubmit(event)" class="p-8 rounded-3xl theme-card border theme-border space-y-6">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-6">
                            <div>
                                <label class="block text-xs font-semibold mb-2">Your Name</label>
                                <input type="text" required placeholder="John Doe" class="w-full px-4 py-3 rounded-xl theme-secondary border theme-border focus:outline-none focus:border-blue-500 text-sm">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold mb-2">Your Email</label>
                                <input type="email" required placeholder="john@example.com" class="w-full px-4 py-3 rounded-xl theme-secondary border theme-border focus:outline-none focus:border-blue-500 text-sm">
                            </div>
                        </div>

                        <div>
                            <label class="block text-xs font-semibold mb-2">Services Needed</label>
                            <select class="w-full px-4 py-3 rounded-xl theme-secondary border theme-border focus:outline-none focus:border-blue-500 text-sm">
                                <option>General Administrative & Inbox Support</option>
                                <option>Calendar & Travel Management</option>
                                <option>Data Entry & CRM Organization</option>
                                <option>Customer Support & Invoicing</option>
                                <option>Full-Time Dedicated VA Support</option>
                            </select>
                        </div>

                        <div>
                            <label class="block text-xs font-semibold mb-2">Message</label>
                            <textarea rows="4" required placeholder="Tell me about your business goals and what tasks you'd like to delegate..." class="w-full px-4 py-3 rounded-xl theme-secondary border theme-border focus:outline-none focus:border-blue-500 text-sm"></textarea>
                        </div>

                        <button type="submit" class="w-full py-4 rounded-xl text-base font-semibold text-white bg-gradient-to-r from-blue-600 to-indigo-600 hover:from-blue-500 hover:to-indigo-500 shadow-lg shadow-blue-500/25 transition-all">
                            Send Message
                        </button>
                       
                        <div id="form-status" class="hidden text-center text-sm font-medium text-emerald-400 pt-2">
                            ✓ Thank you! Your message has been prepared.
                        </div>
                    </form>
                </div>

            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="border-t theme-border py-8 px-4 text-center text-xs theme-text-muted">
        <div class="max-w-7xl mx-auto flex flex-col sm:flex-row items-center justify-between gap-4">
            <div>
                © <span id="year"></span> Symon Kyle Garcia. All rights reserved.
            </div>
            <div class="flex items-center gap-6">
                <a href="#about" class="hover:underline">About</a>
                <a href="#services" class="hover:underline">Services</a>
                <a href="#contact" class="hover:underline">Contact</a>
            </div>
        </div>
    </footer>

    <!-- Floating Dynamic Theme Controls Bar -->
    <div class="fixed bottom-6 right-6 z-50">
        <div class="relative group">
            <button id="theme-toggle-btn" class="p-3.5 rounded-full bg-blue-600 text-white shadow-xl hover:scale-105 active:scale-95 transition-all flex items-center justify-center">
                <i data-lucide="palette" class="w-6 h-6"></i>
            </button>

            <!-- Theme Picker Popover Menu -->
            <div id="theme-menu" class="hidden absolute bottom-16 right-0 w-56 p-3 rounded-2xl theme-card border theme-border shadow-2xl space-y-2">
                <div class="text-xs font-bold uppercase tracking-wider text-gray-400 px-2 py-1">Select Color Theme</div>
               
                <button onclick="setTheme('navy')" class="w-full flex items-center justify-between p-2 rounded-xl hover:bg-white/10 text-xs font-medium transition-colors">
                    <span class="flex items-center gap-2">
                        <span class="w-3 h-3 rounded-full bg-blue-500"></span> Executive Navy
                    </span>
                </button>

                <button onclick="setTheme('slate')" class="w-full flex items-center justify-between p-2 rounded-xl hover:bg-white/10 text-xs font-medium transition-colors">
                    <span class="flex items-center gap-2">
                        <span class="w-3 h-3 rounded-full bg-cyan-500"></span> Modern Slate
                    </span>
                </button>

                <button onclick="setTheme('gold')" class="w-full flex items-center justify-between p-2 rounded-xl hover:bg-white/10 text-xs font-medium transition-colors">
                    <span class="flex items-center gap-2">
                        <span class="w-3 h-3 rounded-full bg-amber-500"></span> Corporate Gold
                    </span>
                </button>

                <button onclick="setTheme('emerald')" class="w-full flex items-center justify-between p-2 rounded-xl hover:bg-white/10 text-xs font-medium transition-colors">
                    <span class="flex items-center gap-2">
                        <span class="w-3 h-3 rounded-full bg-emerald-500"></span> Emerald Clean
                    </span>
                </button>

                <button onclick="setTheme('light')" class="w-full flex items-center justify-between p-2 rounded-xl hover:bg-slate-200/50 text-xs font-medium transition-colors">
                    <span class="flex items-center gap-2">
                        <span class="w-3 h-3 rounded-full bg-slate-800"></span> Modern Light
                    </span>
                </button>
            </div>
        </div>
    </div>

    <script>
        // Initialize Lucide Icons
        lucide.createIcons();

        // Set Current Year in Footer
        document.getElementById('year').textContent = new Date().getFullYear();

        // Theme Toggle Functionality
        const themeBtn = document.getElementById('theme-toggle-btn');
        const themeMenu = document.getElementById('theme-menu');

        themeBtn.addEventListener('click', () => {
            themeMenu.classList.toggle('hidden');
        });

        function setTheme(themeName) {
            document.documentElement.setAttribute('data-theme', themeName);
            localStorage.setItem('symon_portfolio_theme', themeName);
            themeMenu.classList.add('hidden');
        }

        // Restore Stored Theme or default to Navy
        const savedTheme = localStorage.getItem('symon_portfolio_theme') || 'navy';
        setTheme(savedTheme);

        // Profile Image Upload / Customization
        const imageUpload = document.getElementById('image-upload');
        const profileImg = document.getElementById('profile-img');

        imageUpload.addEventListener('change', function(e) {
            const file = e.target.files[0];
            if (file) {
                const reader = new FileReader();
                reader.onload = function(event) {
                    profileImg.src = event.target.result;
                }
                reader.readAsDataURL(file);
            }
        });

        // Copy Email Helper
        function copyEmail() {
            const email = "symonkyleg@gmail.com";
            navigator.clipboard.writeText(email).then(() => {
                const copyText = document.getElementById('copy-text');
                copyText.textContent = "Copied!";
                setTimeout(() => {
                    copyText.textContent = "Copy Email";
                }, 2000);
            });
        }

        // Mobile Menu Toggle
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');

        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Form Submit Handler Mock
        function handleFormSubmit(event) {
            event.preventDefault();
            const status = document.getElementById('form-status');
            status.classList.remove('hidden');
            setTimeout(() => {
                status.classList.add('hidden');
            }, 4000);
        }
    </script>
</body>
</html>
