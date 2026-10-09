```html
<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Symon Kyle Garcia - Your Virtual Assistant</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">

    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
            transition: background-color 0.3s ease, color 0.3s ease;
        }
        .theme-card-transition {
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }
        .theme-card-transition:hover {
            transform: translateY(-4px);
        }
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #f1f1f1;
        }
        ::-webkit-scrollbar-thumb {
            background: #94a3b8;
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #64748b;
        }
    </style>
</head>
<body id="app-body" class="bg-slate-50 text-slate-800 antialiased selection:bg-blue-500 selection:text-white">

    <!-- Navigation Header -->
    <header class="sticky top-0 z-50 backdrop-blur-md bg-white/80 border-b border-slate-200 transition-colors duration-300" id="main-header">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
                <!-- Logo / Name -->
                <a href="#" class="flex items-center gap-3 group">
                    <div class="w-10 h-10 rounded-xl bg-gradient-to-tr from-blue-700 to-indigo-600 text-white flex items-center justify-center font-bold text-xl shadow-md shadow-blue-500/20 group-hover:scale-105 transition-transform">
                        SK
                    </div>
                    <div>
                        <span class="font-extrabold text-lg sm:text-xl tracking-tight text-slate-900 block leading-tight" id="logo-text">Symon Kyle Garcia</span>
                        <span class="text-xs font-semibold text-blue-600 tracking-wider uppercase block" id="logo-subtext">Your Virtual Assistant</span>
                </div>
            </a>

            <!-- Desktop Navigation Links -->
            <div class="flex items-center gap-8">
                <nav class="hidden md:flex items-center space-x-8 text-sm font-medium">
                    <a href="#about" class="text-slate-600 hover:text-blue-600 transition-colors py-2">About</a>
                    <a href="#services" class="text-slate-600 hover:text-blue-600 transition-colors py-2">Services</a>
                    <a href="#contact" class="text-slate-600 hover:text-blue-600 transition-colors py-2">Contact</a>
                </nav>

                <!-- Mobile Menu Button -->
                <button onclick="toggleMobileMenu()" class="md:hidden p-2 rounded-lg text-slate-600 hover:bg-slate-100" id="mobile-menu-btn" aria-label="Toggle Menu">
                    <i class="fa-solid fa-bars text-xl"></i>
                </button>
            </div>
        </div>
    </div>

    <!-- Mobile Navigation Menu -->
        <div id="mobile-menu" class="hidden md:hidden border-b border-slate-200 bg-white/95 backdrop-blur-md px-4 pt-2 pb-4 space-y-3">
            <a href="#about" onclick="toggleMobileMenu()" class="block text-slate-600 hover:text-blue-600 font-medium py-2">About</a>
            <a href="#services" onclick="toggleMobileMenu()" class="block text-slate-600 hover:text-blue-600 font-medium py-2">Services</a>
            <a href="#contact" onclick="toggleMobileMenu()" class="block text-slate-600 hover:text-blue-600 font-medium py-2">Contact</a>
        </div>
    </header>

    <!-- Hero & Profile Section -->
    <section id="about" class="py-12 lg:py-20 overflow-hidden">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 lg:gap-8 items-center">
                
                <!-- Left Column: Photo -->
                <div class="lg:col-span-5 flex flex-col items-center">
                    <div class="relative w-full max-w-md">
                        <div class="absolute -inset-2 bg-gradient-to-r from-blue-600 to-indigo-600 rounded-3xl blur-xl opacity-25" id="photo-glow"></div>
                        
                        <div class="relative bg-white rounded-2xl p-3 shadow-2xl border border-slate-100" id="photo-container">
                            <img 
                                src="1000004505.jpg" 
                                alt="Symon Kyle Garcia - Your Virtual Assistant" 
                                class="w-full h-[420px] object-cover object-top rounded-xl shadow-inner"
                                onerror="this.onerror=null; this.src='https://placehold.co/400x500/1e293b/ffffff?text=Symon+Kyle+Garcia';"
                            >
                            
                            <div class="absolute -bottom-4 -right-4 bg-white/95 backdrop-blur-md border border-slate-200/80 p-3 rounded-xl shadow-xl flex items-center gap-3" id="badge-experience">
                                <div class="w-10 h-10 rounded-lg bg-emerald-100 text-emerald-600 flex items-center justify-center font-bold text-lg">
                                    <i class="fa-solid fa-circle-check"></i>
                                </div>
                                <div>
                                    <p class="text-xs text-slate-500 font-medium">Status</p>
                                    <p class="text-sm font-bold text-slate-800">Available for Hire</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Right Column: Profile Text -->
                <div class="lg:col-span-7 space-y-6 text-center lg:text-left">
                    <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full text-xs font-semibold tracking-wide uppercase bg-blue-100 text-blue-800" id="title-badge">
                        <i class="fa-solid fa-user-check"></i> Dedicated Administrative Support
                    </div>

                    <h1 class="text-3xl sm:text-4xl lg:text-5xl font-black text-slate-900 tracking-tight leading-tight" id="hero-heading">
                        Symon Kyle Garcia
                    </h1>

                    <p class="text-xl sm:text-2xl font-bold text-blue-600" id="hero-subheading">
                        Your Virtual Assistant
                    </p>

                    <!-- Professional Summary -->
                    <div class="space-y-4 text-slate-600 text-base sm:text-lg leading-relaxed max-w-2xl mx-auto lg:mx-0" id="hero-description">
                        <p>
                            I am a reliable, proactive, and detail-oriented Virtual Assistant specializing in providing seamless administrative support to business owners, executives, and growing teams.
                        </p>
                        <p>
                            My goal is to optimize your daily workflow, eliminate operational friction, and handle administrative complexities so you can focus on driving business growth and high-level strategy.
                        </p>
                    </div>

                    <!-- Direct Contact Buttons (Read-Only) -->
                    <div class="flex flex-wrap items-center justify-center lg:justify-start gap-4 pt-4">
                        <a href="mailto:symonkyleg@gmail.com" class="px-6 py-3.5 rounded-xl text-base font-semibold text-white bg-blue-600 hover:bg-blue-700 shadow-lg shadow-blue-500/25 transition-all hover:scale-[1.02] flex items-center gap-2" id="btn-email-hero">
                            <i class="fa-solid fa-envelope"></i>
                            <span>Email Me</span>
                        </a>
                        <a href="tel:09391088094" class="px-6 py-3.5 rounded-xl text-base font-semibold text-slate-700 bg-white border border-slate-300 hover:bg-slate-50 shadow-sm transition-all flex items-center gap-2" id="btn-phone-hero">
                            <i class="fa-solid fa-phone text-emerald-600"></i>
                            <span>09391088094</span>
                        </a>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-16 sm:py-24 bg-slate-100/70 border-t border-b border-slate-200 transition-colors duration-300" id="services-section">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            
            <div class="text-center max-w-3xl mx-auto mb-16 space-y-4">
                <span class="px-3.5 py-1 rounded-full text-xs font-bold uppercase tracking-wider bg-blue-100 text-blue-800" id="services-badge">
                    Services Provided
                </span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-slate-900 tracking-tight" id="services-title">
                    How I Can Support You
                </h2>
                <p class="text-base sm:text-lg text-slate-600" id="services-subtitle">
                    Comprehensive virtual assistance designed to bring organization, efficiency, and clarity to your business operations.
                </p>
            </div>

            <!-- Services Grid -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 sm:gap-8">

                <!-- Service 1 -->
                <div class="theme-card-transition bg-white p-6 sm:p-8 rounded-2xl border border-slate-200 shadow-sm flex flex-col justify-between" id="service-card-1">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-blue-50 text-blue-600 flex items-center justify-center text-xl font-bold mb-6">
                            <i class="fa-solid fa-inbox"></i>
                        </div>
                        <h3 class="text-xl font-bold text-slate-900 mb-3">Email & Inbox Management</h3>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            Sorting, labeling, responding to routine inquiries, and maintaining a zero-inbox system.
                        </p>
                    </div>
                </div>

                <!-- Service 2 -->
                <div class="theme-card-transition bg-white p-6 sm:p-8 rounded-2xl border border-slate-200 shadow-sm flex flex-col justify-between" id="service-card-2">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-indigo-50 text-indigo-600 flex items-center justify-center text-xl font-bold mb-6">
                            <i class="fa-solid fa-calendar-check"></i>
                        </div>
                        <h3 class="text-xl font-bold text-slate-900 mb-3">Calendar & Schedule Management</h3>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            Setting appointments, managing meeting requests, sending reminders, and setting up Zoom or Google Meet links.
                        </p>
                    </div>
                </div>

                <!-- Service 3 -->
                <div class="theme-card-transition bg-white p-6 sm:p-8 rounded-2xl border border-slate-200 shadow-sm flex flex-col justify-between" id="service-card-3">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-sky-50 text-sky-600 flex items-center justify-center text-xl font-bold mb-6">
                            <i class="fa-solid fa-plane-departure"></i>
                        </div>
                        <h3 class="text-xl font-bold text-slate-900 mb-3">Travel Coordination</h3>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            Booking flights, accommodation, and ground transportation, as well as creating detailed travel itineraries.
                        </p>
                    </div>
                </div>

                <!-- Service 4 -->
                <div class="theme-card-transition bg-white p-6 sm:p-8 rounded-2xl border border-slate-200 shadow-sm flex flex-col justify-between" id="service-card-4">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-emerald-50 text-emerald-600 flex items-center justify-center text-xl font-bold mb-6">
                            <i class="fa-solid fa-folder-tree"></i>
                        </div>
                        <h3 class="text-xl font-bold text-slate-900 mb-3">File & Cloud Organization</h3>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            Keeping Google Drive, Dropbox, or OneDrive structured, labeled, and updated.
                        </p>
                    </div>
                </div>

                <!-- Service 5 -->
                <div class="theme-card-transition bg-white p-6 sm:p-8 rounded-2xl border border-slate-200 shadow-sm flex flex-col justify-between" id="service-card-5">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-violet-50 text-violet-600 flex items-center justify-center text-xl font-bold mb-6">
                            <i class="fa-solid fa-database"></i>
                        </div>
                        <h3 class="text-xl font-bold text-slate-900 mb-3">Data Entry</h3>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            Inputting customer details, updating CRM systems, transcribing meeting notes, and keeping spreadsheets organized.
                        </p>
                    </div>
                </div>

                <!-- Service 6 -->
                <div class="theme-card-transition bg-white p-6 sm:p-8 rounded-2xl border border-slate-200 shadow-sm flex flex-col justify-between" id="service-card-6">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-amber-50 text-amber-600 flex items-center justify-center text-xl font-bold mb-6">
                            <i class="fa-solid fa-magnifying-glass"></i>
                        </div>
                        <h3 class="text-xl font-bold text-slate-900 mb-3">Web & Topic Research</h3>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            Sourcing info on competitors, industry trends, products, or potential software/tools.
                        </p>
                    </div>
                </div>

                <!-- Service 7 -->
                <div class="theme-card-transition bg-white p-6 sm:p-8 rounded-2xl border border-slate-200 shadow-sm flex flex-col justify-between" id="service-card-7">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-rose-50 text-rose-600 flex items-center justify-center text-xl font-bold mb-6">
                            <i class="fa-solid fa-file-powerpoint"></i>
                        </div>
                        <h3 class="text-xl font-bold text-slate-900 mb-3">Document Formatting</h3>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            Formatting PDFs, Word documents, and creating clean Google Slides or PowerPoint presentations.
                        </p>
                    </div>
                </div>

                <!-- Service 8 -->
                <div class="theme-card-transition bg-white p-6 sm:p-8 rounded-2xl border border-slate-200 shadow-sm flex flex-col justify-between" id="service-card-8">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-teal-50 text-teal-600 flex items-center justify-center text-xl font-bold mb-6">
                            <i class="fa-solid fa-headset"></i>
                        </div>
                        <h3 class="text-xl font-bold text-slate-900 mb-3">Customer Support</h3>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            Responding to common customer inquiries via live chat, email, or ticketing systems like Zendesk.
                        </p>
                    </div>
                </div>

                <!-- Service 9 -->
                <div class="theme-card-transition bg-white p-6 sm:p-8 rounded-2xl border border-slate-200 shadow-sm flex flex-col justify-between" id="service-card-9">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-cyan-50 text-cyan-600 flex items-center justify-center text-xl font-bold mb-6">
                            <i class="fa-solid fa-file-invoice-dollar"></i>
                        </div>
                        <h3 class="text-xl font-bold text-slate-900 mb-3">Invoicing & Expense Tracking</h3>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            Generating basic invoices, following up on unpaid bills, and logging weekly business expenses in software like QuickBooks or Excel.
                        </p>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Read-Only Contact Section -->
    <section id="contact" class="py-16 sm:py-24">
        <div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-12 space-y-3">
                <span class="px-3.5 py-1 rounded-full text-xs font-bold uppercase tracking-wider bg-blue-100 text-blue-800" id="contact-badge">
                    Get In Touch
                </span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-slate-900 tracking-tight" id="contact-title">
                    Contact Details
                </h2>
                <p class="text-slate-600 text-base" id="contact-subtitle">
                    Reach out directly through email or phone to discuss how I can assist with your daily operations.
                </p>
            </div>

            <!-- Static Contact Display Cards -->
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <!-- Email Card -->
                <a href="mailto:symonkyleg@gmail.com" class="bg-white p-8 rounded-2xl border border-slate-200 shadow-sm hover:shadow-md transition-all flex items-center gap-5 group" id="contact-email-card">
                    <div class="w-14 h-14 rounded-2xl bg-blue-50 text-blue-600 flex items-center justify-center shrink-0 font-bold text-2xl group-hover:bg-blue-600 group-hover:text-white transition-colors">
                        <i class="fa-solid fa-envelope"></i>
                    </div>
                    <div class="overflow-hidden">
                        <p class="text-xs text-slate-500 font-semibold uppercase tracking-wider mb-1">Send an Email</p>
                        <p class="text-base sm:text-lg font-bold text-slate-900 group-hover:text-blue-600 transition-colors truncate">
                            symonkyleg@gmail.com
                        </p>
                    </div>
                </a>

                <!-- Phone Card -->
                <a href="tel:09391088094" class="bg-white p-8 rounded-2xl border border-slate-200 shadow-sm hover:s
