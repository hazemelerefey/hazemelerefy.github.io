# hazemelerefy.github.io
Hazem elerefy portfolio

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hazem Khaled Ezzat Abdelhalim | Business Intelligence Analyst</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <!-- Custom Styles -->
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        /* Smooth scroll behavior */
        html {
            scroll-behavior: smooth;
        }
        /* Custom gradient for hero */
        .hero-gradient {
            background: linear-gradient(135deg, #1e3a5f 0%, #0f172a 50%, #1e1b4b 100%);
        }
        /* Timeline connector line */
        .timeline-line::before {
            content: '';
            position: absolute;
            left: 24px;
            top: 0;
            bottom: 0;
            width: 2px;
            background: linear-gradient(to bottom, #3b82f6, #8b5cf6);
        }
        /* Card hover effect */
        .portfolio-card {
            transition: all 0.3s ease;
        }
        .portfolio-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.15);
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <!-- ============================================ -->
    <!-- NAVIGATION BAR                               -->
    <!-- ============================================ -->
    <!-- EDIT: Update navigation links if you add more sections -->
    <nav class="fixed top-0 left-0 right-0 bg-white/95 backdrop-blur-sm shadow-sm z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-16">
                <!-- Logo/Name -->
                <div class="font-bold text-xl text-slate-800">
                    Hazem<span class="text-blue-600">.</span>
                </div>
                <!-- Desktop Navigation -->
                <div class="hidden md:flex space-x-8">
                    <a href="#home" class="text-gray-600 hover:text-blue-600 transition-colors font-medium">Home</a>
                    <a href="#education" class="text-gray-600 hover:text-blue-600 transition-colors font-medium">Education</a>
                    <a href="#portfolio" class="text-gray-600 hover:text-blue-600 transition-colors font-medium">Portfolio</a>
                </div>
                <!-- Mobile Menu Button -->
                <button id="mobile-menu-btn" class="md:hidden p-2 rounded-lg hover:bg-gray-100">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
                    </svg>
                </button>
            </div>
        </div>
        <!-- Mobile Menu (Hidden by default) -->
        <div id="mobile-menu" class="hidden md:hidden bg-white border-t">
            <div class="px-4 py-3 space-y-2">
                <a href="#home" class="block py-2 text-gray-600 hover:text-blue-600">Home</a>
                <a href="#education" class="block py-2 text-gray-600 hover:text-blue-600">Education</a>
                <a href="#portfolio" class="block py-2 text-gray-600 hover:text-blue-600">Portfolio</a>
            </div>
        </div>
    </nav>

    <!-- ============================================ -->
    <!-- HERO SECTION                                 -->
    <!-- ============================================ -->
    <!-- EDIT: This is the main banner at the top     -->
    <section id="home" class="hero-gradient min-h-screen flex items-center justify-center pt-16">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            
            <!-- EDIT: Replace with your professional headshot photo -->
            <!-- PLACEHOLDER: Profile Photo -->
            <div class="mb-8">
                <div class="w-32 h-32 sm:w-40 sm:h-40 mx-auto rounded-full bg-gradient-to-br from-blue-400 to-purple-500 flex items-center justify-center text-white text-4xl sm:text-5xl font-bold shadow-2xl">
                    HK
                </div>
            </div>
            
            <!-- EDIT: Your full name -->
            <!-- PLACEHOLDER: Full Name -->
            <h1 class="text-4xl sm:text-5xl lg:text-6xl font-bold text-white mb-4 tracking-tight">
                Hazem Khaled Ezzat Abdelhalim
            </h1>
            
            <!-- EDIT: Your professional title -->
            <!-- PLACEHOLDER: Job Title -->
            <p class="text-xl sm:text-2xl text-blue-300 font-medium mb-6">
                Business Intelligence Analyst
            </p>
            
            <!-- EDIT: Your tagline/slogan -->
            <!-- PLACEHOLDER: Tagline -->
            <p class="text-lg sm:text-xl text-gray-300 max-w-2xl mx-auto mb-10 leading-relaxed">
                "Transitioning raw data into actionable, strategic insights using Power BI."
            </p>
            
            <!-- EDIT: Call-to-action button text and link -->
            <!-- PLACEHOLDER: CTA Button -->
            <a href="#portfolio" class="inline-flex items-center gap-2 bg-blue-600 hover:bg-blue-700 text-white font-semibold py-4 px-8 rounded-full transition-all duration-300 shadow-lg hover:shadow-blue-500/25 transform hover:scale-105">
                <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z"></path>
                </svg>
                View My Dashboards
            </a>
            
            <!-- Scroll indicator -->
            <div class="mt-16 animate-bounce">
                <svg class="w-6 h-6 mx-auto text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 14l-7 7m0 0l-7-7m7 7V3"></path>
                </svg>
            </div>
        </div>
    </section>

    <!-- ============================================ -->
    <!-- EDUCATION & TRAINING SECTION                 -->
    <!-- ============================================ -->
    <!-- EDIT: Add or remove education items here     -->
    <section id="education" class="py-20 bg-white">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            
            <!-- Section Header -->
            <div class="text-center mb-16">
                <h2 class="text-3xl sm:text-4xl font-bold text-slate-800 mb-4">Education & Training</h2>
                <div class="w-20 h-1 bg-gradient-to-r from-blue-600 to-purple-600 mx-auto rounded-full"></div>
            </div>
            
            <!-- Timeline Container -->
            <div class="relative timeline-line space-y-8">
                
                <!-- ============================================ -->
                <!-- EDUCATION ITEM 1                             -->
                <!-- ============================================ -->
                <!-- EDIT: Replace with your first education/training item -->
                <!-- PLACEHOLDER: Education Item 1 -->
                <div class="relative pl-16 sm:pl-20">
                    <!-- Timeline Dot -->
                    <div class="absolute left-4 sm:left-4 w-10 h-10 bg-blue-600 rounded-full flex items-center justify-center shadow-lg">
                        <svg class="w-5 h-5 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.747 0 3.332.477 4.5 1.253v13C19.832 18.477 18.247 18 16.5 18c-1.746 0-3.332.477-4.5 1.253"></path>
                        </svg>
                    </div>
                    <!-- Content Card -->
                    <div class="bg-gray-50 rounded-xl p-6 border border-gray-100 hover:shadow-md transition-shadow">
                        <!-- EDIT: Institution/Program name -->
                        <h3 class="text-lg sm:text-xl font-bold text-slate-800 mb-2">
                            Digilians (DEPI) Initiative
                        </h3>
                        <!-- EDIT: Certificate/Degree details -->
                        <p class="text-blue-600 font-medium mb-2">
                            Intensive Practical Training Program (equivalent to ITI)
                        </p>
                        <!-- EDIT: Add date if desired -->
                        <p class="text-gray-500 text-sm">
                            <!-- PLACEHOLDER: Add completion date here -->
                            <!-- Example: Completed: January 2024 -->
                        </p>
                    </div>
                </div>
                
                <!-- ============================================ -->
                <!-- EDUCATION ITEM 2                             -->
                <!-- ============================================ -->
                <!-- EDIT: Replace with your second education/training item -->
                <!-- PLACEHOLDER: Education Item 2 -->
                <div class="relative pl-16 sm:pl-20">
                    <!-- Timeline Dot -->
                    <div class="absolute left-4 sm:left-4 w-10 h-10 bg-purple-600 rounded-full flex items-center justify-center shadow-lg">
                        <svg class="w-5 h-5 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4M7.835 4.697a3.42 3.42 0 001.946-.806 3.42 3.42 0 014.438 0 3.42 3.42 0 001.946.806 3.42 3.42 0 013.138 3.138 3.42 3.42 0 00.806 1.946 3.42 3.42 0 010 4.438 3.42 3.42 0 00-.806 1.946 3.42 3.42 0 01-3.138 3.138 3.42 3.42 0 00-1.946.806 3.42 3.42 0 01-4.438 0 3.42 3.42 0 00-1.946-.806 3.42 3.42 0 01-3.138-3.138 3.42 3.42 0 00-.806-1.946 3.42 3.42 0 010-4.438 3.42 3.42 0 00.806-1.946 3.42 3.42 0 013.138-3.138z"></path>
                        </svg>
                    </div>
                    <!-- Content Card -->
                    <div class="bg-gray-50 rounded-xl p-6 border border-gray-100 hover:shadow-md transition-shadow">
                        <!-- EDIT: Institution/Program name -->
                        <h3 class="text-lg sm:text-xl font-bold text-slate-800 mb-2">
                            Google
                        </h3>
                        <!-- EDIT: Certificate/Degree details -->
                        <p class="text-purple-600 font-medium mb-2">
                            Google Data Analytics Professional Certificate
                        </p>
                        <!-- EDIT: Add date if desired -->
                        <p class="text-gray-500 text-sm">
                            <!-- PLACEHOLDER: Add completion date here -->
                            <!-- Example: Completed: March 2024 -->
                        </p>
                    </div>
                </div>
                
                <!-- ============================================ -->
                <!-- ADD MORE EDUCATION ITEMS HERE                -->
                <!-- ============================================ -->
                <!-- 
                TO ADD MORE ITEMS:
                1. Copy the entire "EDUCATION ITEM" block above
                2. Paste it below this comment
                3. Update the content (institution name, certificate, date)
                4. Choose a different icon color if desired (bg-blue-600, bg-purple-600, bg-green-600, etc.)
                -->
                
            </div>
        </div>
    </section>

    <!-- ============================================ -->
    <!-- PORTFOLIO GALLERY SECTION                    -->
    <!-- ============================================ -->
    <!-- EDIT: This is where you add your projects    -->
    <section id="portfolio" class="py-20 bg-gray-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            
            <!-- Section Header -->
            <div class="text-center mb-16">
                <h2 class="text-3xl sm:text-4xl font-bold text-slate-800 mb-4">Portfolio</h2>
                <div class="w-20 h-1 bg-gradient-to-r from-blue-600 to-purple-600 mx-auto rounded-full mb-4"></div>
                <p class="text-gray-600 max-w-2xl mx-auto">
                    Explore my Power BI dashboards and data visualization projects
                </p>
            </div>
            
            <!-- ============================================ -->
            <!-- PROJECT CARDS GRID                           -->
            <!-- ============================================ -->
            <!-- 
            GRID LAYOUT:
            - Desktop (lg): 3 cards per row
            - Tablet (md): 2 cards per row  
            - Mobile: 1 card per row (stacked vertically)
            -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                
                <!-- ============================================ -->
                <!-- PROJECT CARD 1                               -->
                <!-- ============================================ -->
                <!-- EDIT: Replace with your first project -->
                <!-- PLACEHOLDER: Project Card 1 -->
                <div class="portfolio-card bg-white rounded-2xl overflow-hidden shadow-lg">
                    <!-- 
                    IMAGE CONTAINER - 16:9 ASPECT RATIO
                    EDIT: Replace the div below with your actual dashboard screenshot
                    INSTRUCTIONS:
                    1. Save your dashboard image (PNG/JPG) in the same folder as this HTML file
                    2. Replace the <div class="bg-gray-800..."> block with:
                       <img src="your-image-name.png" alt="Project 1 Dashboard" class="w-full h-full object-cover">
                    -->
                    <div class="aspect-video bg-gray-800 flex items-center justify-center">
                        <div class="text-center p-6">
                            <svg class="w-12 h-12 text-gray-500 mx-auto mb-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M9 17V7m0 10a2 2 0 01-2 2H5a2 2 0 01-2-2V7a2 2 0 012-2h2a2 2 0 012 2m0 10a2 2 0 002 2h2a2 2 0 002-2M9 7a2 2 0 012-2h2a2 2 0 012 2m0 10V7m0 10a2 2 0 002 2h2a2 2 0 002-2V7a2 2 0 00-2-2h-2a2 2 0 00-2 2"></path>
                            </svg>
                            <p class="text-white font-medium">Dashboard Screenshot Placeholder</p>
                            <p class="text-gray-400 text-sm mt-1">16:9 Aspect Ratio</p>
                        </div>
                    </div>
                    <!-- Card Content -->
                    <div class="p-6">
                        <!-- EDIT: Project title -->
                        <h3 class="text-xl font-bold text-slate-800 mb-2">
                            Project Title Placeholder
                        </h3>
                        <!-- EDIT: Brief description of insights -->
                        <p class="text-gray-600 mb-4 text-sm leading-relaxed">
                            Brief description of insights generated from this dashboard. Explain what business problems were solved and key metrics analyzed.
                        </p>
                        <!-- EDIT: Button link and text -->
                        <a href="#" class="inline-flex items-center gap-2 text-blue-600 hover:text-blue-700 font-medium text-sm transition-colors">
                            View Dashboard
                            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"></path>
                            </svg>
                        </a>
                    </div>
                </div>
                
                <!-- ============================================ -->
                <!-- PROJECT CARD 2                               -->
                <!-- ============================================ -->
                <!-- EDIT: Replace with your second project -->
                <!-- PLACEHOLDER: Project Card 2 -->
                <div class="portfolio-card bg-white rounded-2xl overflow-hidden shadow-lg">
                    <!-- IMAGE CONTAINER - 16:9 ASPECT RATIO -->
                    <div class="aspect-video bg-gray-800 flex items-center justify-center">
                        <div class="text-center p-6">
                            <svg class="w-12 h-12 text-gray-500 mx-auto mb-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M9 17V7m0 10a2 2 0 01-2 2H5a2 2 0 01-2-2V7a2 2 0 012-2h2a2 2 0 012 2m0 10a2 2 0 002 2h2a2 2 0 002-2M9 7a2 2 0 012-2h2a2 2 0 012 2m0 10V7m0 10a2 2 0 002 2h2a2 2 0 002-2V7a2 2 0 00-2-2h-2a2 2 0 00-2 2"></path>
                            </svg>
                            <p class="text-white font-medium">Dashboard Screenshot Placeholder</p>
                            <p class="text-gray-400 text-sm mt-1">16:9 Aspect Ratio</p>
                        </div>
                    </div>
                    <!-- Card Content -->
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-slate-800 mb-2">
                            Project Title Placeholder
                        </h3>
                        <p class="text-gray-600 mb-4 text-sm leading-relaxed">
                            Brief description of insights generated from this dashboard. Explain what business problems were solved and key metrics analyzed.
                        </p>
                        <a href="#" class="inline-flex items-center gap-2 text-blue-600 hover:text-blue-700 font-medium text-sm transition-colors">
                            View Dashboard
                            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"></path>
                            </svg>
                        </a>
                    </div>
                </div>
                
                <!-- ============================================ -->
                <!-- PROJECT CARD 3                               -->
                <!-- ============================================ -->
                <!-- EDIT: Replace with your third project -->
                <!-- PLACEHOLDER: Project Card 3 -->
                <div class="portfolio-card bg-white rounded-2xl overflow-hidden shadow-lg">
                    <!-- IMAGE CONTAINER - 16:9 ASPECT RATIO -->
                    <div class="aspect-video bg-gray-800 flex items-center justify-center">
                        <div class="text-center p-6">
                            <svg class="w-12 h-12 text-gray-500 mx-auto mb-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="