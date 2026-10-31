
<html lang="en" class="scroll-smooth dark">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Criminally Custom Builds | 50cc–400cc Garage & Lawnmowers | Wesley, AR</title>
    <meta name="google-site-verification" content="0wrhAEaLqsKlxr77CC12N0DWpNW15Y8AifQ9fsDt8eU" />

    <!-- SEO & Social Meta Tags -->
    <meta name="description" content="Criminally Custom Builds - Northwest Arkansas garage specializing in 50cc to 400cc small bike engines, GY6 big bores, Predator swaps, off-road custom builds, and lawnmower repair. Call/text (479) 397-0534.">
    <meta property="og:title" content="Criminally Custom Builds | Unapologetically Modified">
    <meta property="og:description" content="Small engine performance, off-road custom fabrication, and lawnmower repair shop located at 1610 Madison County Rd 6345, Wesley, AR 72773.">
    <meta property="og:image" content="https://i.postimg.cc/SR6BPY2D/1791984296717-1.png">
    <meta property="og:type" content="website">

    <!-- Favicon -->
    <link rel="icon" type="image/png" href="https://i.postimg.cc/SR6BPY2D/1791984296717-1.png">

    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>

    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=JetBrains+Mono:wght@500;700&family=Space+Grotesk:wght@600;700;800&display=swap" rel="stylesheet">
    
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        display: ['Space Grotesk', 'sans-serif'],
                        mono: ['JetBrains Mono', 'monospace'],
                    },
                    colors: {
                        crimson: {
                            500: '#ef4444',
                            600: '#dc2626',
                            700: '#b91c1c',
                        },
                        obsidian: {
                            950: '#070709',
                            900: '#0c0c10',
                            800: '#14141b',
                            700: '#1f1f29',
                        }
                    }
                }
            }
        }
    </script>
    <style>
        body {
            background-color: #070709;
            color: #f8fafc;
        }
        .glass-header {
            background: rgba(7, 7, 9, 0.92);
            backdrop-filter: blur(16px);
        }
        .caution-stripes {
            background: repeating-linear-gradient(
                -45deg,
                #dc2626,
                #dc2626 12px,
                #070709 12px,
                #070709 24px
            );
        }
        .hero-mesh {
            background-image: 
                radial-gradient(at 80% 15%, rgba(220, 38, 38, 0.20) 0px, transparent 50%),
                radial-gradient(at 15% 85%, rgba(245, 158, 11, 0.14) 0px, transparent 50%),
                linear-gradient(to bottom, rgba(7, 7, 9, 0.4), #070709);
        }
        .grid-bg {
            background-size: 36px 36px;
            background-image: 
                linear-gradient(to right, rgba(255, 255, 255, 0.03) 1px, transparent 1px),
                linear-gradient(to bottom, rgba(255, 255, 255, 0.03) 1px, transparent 1px);
        }
        .red-glow:hover {
            box-shadow: 0 0 28px -5px rgba(220, 38, 38, 0.45);
        }
    </style>
</head>
<body class="bg-obsidian-950 text-zinc-100 antialiased selection:bg-crimson-600 selection:text-white overflow-x-hidden">

    <!-- Toast Notification -->
    <div id="toast" class="fixed bottom-6 right-6 z-50 transform translate-y-32 opacity-0 transition-all duration-300 bg-obsidian-800 text-white px-6 py-4 rounded-xl shadow-2xl flex items-center space-x-4 border border-crimson-600/60 max-w-sm pointer-events-none">
        <div class="w-10 h-10 rounded-lg bg-crimson-600/20 border border-crimson-500 flex items-center justify-center flex-shrink-0">
            <i id="toast-icon" class="fa-solid fa-wrench text-crimson-500 text-lg"></i>
        </div>
        <div>
            <h4 id="toast-title" class="font-display font-bold text-sm uppercase tracking-wider text-white">Work Order Logged</h4>
            <p id="toast-msg" class="text-xs text-zinc-400 mt-0.5">We'll review your specs and contact you to schedule drop-off.</p>
        </div>
    </div>

    <!-- Hazard Accent Bar -->
    <div class="h-1.5 w-full caution-stripes"></div>

    <!-- Navigation Bar -->
    <header class="sticky top-0 z-40 glass-header border-b border-zinc-800/80">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
                <!-- Brand Logo -->
                <a href="#home" class="flex items-center space-x-3.5 group">
                    <img src="https://i.postimg.cc/SR6BPY2D/1791984296717-1.png" alt="Criminally Custom Builds Logo" class="w-12 h-12 rounded-full border-2 border-amber-500/80 object-cover shadow-lg group-hover:scale-105 transition-transform">
                    <div>
                        <div class="flex items-center space-x-2">
                            <span class="text-xl font-display font-extrabold tracking-wider text-white leading-none">CRIMINALLY CUSTOM</span>
                            <span class="hidden sm:inline-block px-1.5 py-0.5 text-[10px] font-mono font-bold bg-zinc-800 text-amber-400 rounded border border-zinc-700">&le;400CC + MOWERS</span>
                        </div>
                        <span class="text-xs font-mono uppercase tracking-widest text-crimson-500 font-semibold block mt-0.5">CC Builds // 1610 Madison County Rd 6345, Wesley, AR</span>
                    </div>
                </a>

                <!-- Desktop Navigation Links -->
                <div class="hidden md:flex items-center space-x-7">
                    <a href="#rates" class="text-sm font-medium text-zinc-400 hover:text-white transition-colors">Labor Rates</a>
                    <a href="#services" class="text-sm font-medium text-zinc-400 hover:text-white transition-colors">Services</a>
                    <a href="#calculator" class="text-sm font-medium text-zinc-400 hover:text-white transition-colors">Deposit Estimator</a>
                    <a href="#policies" class="text-sm font-medium text-zinc-400 hover:text-white transition-colors">Shop Location</a>
                </div>

                <!-- Call to Action -->
                <div class="hidden md:flex items-center space-x-4">
                    <a href="tel:4793970534" class="px-4 py-2.5 rounded-xl bg-obsidian-800 hover:bg-obsidian-700 text-zinc-200 border border-zinc-700 font-mono text-xs flex items-center space-x-2 transition-all">
                        <i class="fa-solid fa-phone text-amber-400"></i>
                        <span>(479) 397-0534</span>
                    </a>
                    <a href="#calculator" class="px-5 py-2.5 rounded-xl bg-crimson-600 hover:bg-crimson-500 text-white font-display text-xs font-bold uppercase tracking-wider shadow-lg shadow-crimson-600/25 transition-all transform hover:-translate-y-0.5 flex items-center space-x-2">
                        <span>Estimate Work Order</span>
                        <i class="fa-solid fa-calculator text-amber-300"></i>
                    </a>
                </div>

                <!-- Mobile Menu Button -->
                <div class="md:hidden flex items-center">
                    <button id="mobile-menu-btn" aria-label="Toggle Menu" class="p-2.5 rounded-xl bg-obsidian-800 text-zinc-300 hover:text-white border border-zinc-700">
                        <i class="fa-solid fa-bars-staggered text-lg"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- Mobile Navigation Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-obsidian-900 border-b border-zinc-800 px-4 pt-3 pb-6 space-y-2">
            <a href="#rates" class="block px-4 py-2.5 rounded-xl text-sm font-semibold text-zinc-300 hover:bg-obsidian-800 hover:text-white">Shop Labor Rates</a>
            <a href="#services" class="block px-4 py-2.5 rounded-xl text-sm font-semibold text-zinc-300 hover:bg-obsidian-800 hover:text-white">Services & Lawnmowers</a>
            <a href="#calculator" class="block px-4 py-2.5 rounded-xl text-sm font-semibold text-zinc-300 hover:bg-obsidian-800 hover:text-white">Labor & Deposit Calculator</a>
            <a href="#policies" class="block px-4 py-2.5 rounded-xl text-sm font-semibold text-zinc-300 hover:bg-obsidian-800 hover:text-white">Shop Policies & Map</a>
            <div class="pt-3 space-y-2">
                <a href="tel:4793970534" class="w-full block text-center px-5 py-3 rounded-xl bg-obsidian-800 text-zinc-200 border border-zinc-700 font-mono text-xs font-bold">
                    Call / Text: (479) 397-0534
                </a>
                <a href="#calculator" class="w-full block text-center px-5 py-3.5 rounded-xl bg-crimson-600 text-white font-display text-xs font-bold uppercase tracking-wider">
                    Estimate Labor & Deposit
                </a>
            </div>
        </div>
    </header>

    <!-- 1. Hero Section -->
    <section id="home" class="relative pt-14 pb-20 md:pt-24 md:pb-32 hero-mesh grid-bg overflow-hidden border-b border-zinc-900">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
                <!-- Hero Text -->
                <div class="lg:col-span-7 space-y-6 text-center lg:text-left">
                    <div class="inline-flex items-center space-x-2.5 px-4 py-1.5 rounded-full bg-obsidian-800/90 border border-crimson-500/40 text-crimson-400 text-xs font-mono uppercase tracking-widest">
                        <span class="h-2 w-2 rounded-full bg-crimson-500 animate-ping"></span>
                        <span>Wesley, Arkansas // Small Engines & Lawnmowers</span>
                    </div>

                    <div>
                        <p class="text-xs sm:text-sm font-mono uppercase tracking-[0.25em] text-amber-500 font-bold mb-2">
                            CRIMINALLY CUSTOM BUILDS (CC BUILDS)
                        </p>
                        <h1 class="text-4xl sm:text-6xl lg:text-7xl font-display font-extrabold text-white tracking-tight leading-[1.03] uppercase">
                            Unapologetically <span class="text-transparent bg-clip-text bg-gradient-to-r from-crimson-500 via-rose-500 to-amber-500">Modified.</span>
                        </h1>
                    </div>

                    <p class="text-base sm:text-xl text-zinc-300 max-w-2xl mx-auto lg:mx-0 font-normal leading-relaxed">
                        Exclusively built for <strong class="text-white">small bike engines up to 400cc, off-road custom builds, and lawnmowers</strong> in Northwest Arkansas. GY6 big bores, Predator swaps, trail vehicles, and lawnmower engine repair.
                    </p>

                    <div class="flex flex-wrap items-center justify-center lg:justify-start gap-2 pt-1">
                        <span class="px-3 py-1 rounded-lg bg-obsidian-800 border border-zinc-700 text-xs font-mono text-zinc-300">50cc–150cc GY6 Scooters</span>
                        <span class="px-3 py-1 rounded-lg bg-obsidian-800 border border-zinc-700 text-xs font-mono text-zinc-300">Off-Road Custom Builds</span>
                        <span class="px-3 py-1 rounded-lg bg-obsidian-800 border border-zinc-700 text-xs font-mono text-zinc-300">Predator & Small Engines</span>
                        <span class="px-3 py-1 rounded-lg bg-obsidian-800 border border-zinc-700 text-xs font-mono text-zinc-300">Lawnmowers</span>
                    </div>

                    <div class="flex flex-col sm:flex-row items-center justify-center lg:justify-start space-y-4 sm:space-y-0 sm:space-x-4 pt-3">
                        <a href="#calculator" class="w-full sm:w-auto px-8 py-4 rounded-xl bg-crimson-600 hover:bg-crimson-500 text-white font-display font-bold text-sm uppercase tracking-wider shadow-xl shadow-crimson-600/30 transition-all transform hover:-translate-y-0.5 flex items-center justify-center space-x-3">
                            <i class="fa-solid fa-sliders"></i>
                            <span>Labor & Deposit Calculator</span>
                        </a>
                        <a href="#services" class="w-full sm:w-auto px-8 py-4 rounded-xl bg-obsidian-800 hover:bg-obsidian-700 text-zinc-200 font-display font-bold text-sm uppercase tracking-wider border border-zinc-700 transition-all flex items-center justify-center space-x-3">
                            <i class="fa-solid fa-wrench text-amber-500"></i>
                            <span>Explore Services</span>
                        </a>
                    </div>

                    <!-- Clear Labor Rates Snapshot -->
                    <div class="pt-8 grid grid-cols-3 gap-4 border-t border-zinc-800/80 text-center lg:text-left">
                        <div>
                            <p class="text-2xl sm:text-3xl font-display font-extrabold text-white">$85<span class="text-amber-500">/hr</span></p>
                            <p class="text-xs font-mono uppercase tracking-wider text-zinc-500 mt-1">General Repair / Mowers</p>
                        </div>
                        <div>
                            <p class="text-2xl sm:text-3xl font-display font-extrabold text-white">$100<span class="text-crimson-500">/hr</span></p>
                            <p class="text-xs font-mono uppercase tracking-wider text-zinc-500 mt-1">Performance / Big Bore</p>
                        </div>
                        <div>
                            <p class="text-2xl sm:text-3xl font-display font-extrabold text-white">$200<span class="text-amber-400">/hr</span></p>
                            <p class="text-xs font-mono uppercase tracking-wider text-amber-400 mt-1">Off-Road Custom Builds</p>
                        </div>
                    </div>
                </div>

                <!-- Featured Card with Map Pin Link -->
                <div class="lg:col-span-5 relative">
                    <div class="absolute -inset-2 bg-gradient-to-r from-crimson-600 to-amber-500 rounded-3xl blur-2xl opacity-25"></div>
                    <div class="relative bg-obsidian-900 border border-zinc-800 rounded-2xl overflow-hidden shadow-2xl">
                        <div class="px-5 py-3.5 bg-obsidian-950 border-b border-zinc-800 flex items-center justify-between">
                            <div class="flex items-center space-x-2">
                                <span class="w-3 h-3 rounded-full bg-crimson-500"></span>
                                <span class="w-3 h-3 rounded-full bg-amber-500"></span>
                                <span class="w-3 h-3 rounded-full bg-emerald-500"></span>
                            </div>
                            <span class="text-xs font-mono text-zinc-400">CRIMINALLY CUSTOM // WESLEY AR</span>
                        </div>
                        
                        <div class="p-8 text-center bg-gradient-to-b from-obsidian-950 to-obsidian-900 flex flex-col items-center">
                            <img src="https://i.postimg.cc/SR6BPY2D/1791984296717-1.png" alt="Criminally Custom Builds" class="w-48 h-48 sm:w-56 sm:h-56 object-contain rounded-2xl shadow-2xl border border-zinc-800/80 p-2 bg-obsidian-950/60 mb-4">
                            <h3 class="text-xl font-display font-bold text-white uppercase">Criminally Custom Builds</h3>
                            <a href="https://www.google.com/maps/search/?api=1&query=1610+Madison+County+Rd+6345,+Wesley,+AR+72773" target="_blank" rel="noopener noreferrer" class="text-xs font-mono text-zinc-300 hover:text-amber-400 mt-1 flex items-center space-x-1.5 transition-colors">
                                <i class="fa-solid fa-location-dot text-crimson-500"></i>
                                <span>1610 Madison County Rd 6345, Wesley, AR 72773</span>
                            </a>
                            <a href="tel:4793970534" class="text-sm font-mono text-amber-400 font-bold mt-2 hover:underline flex items-center space-x-1.5">
                                <i class="fa-solid fa-phone text-xs"></i>
                                <span>(479) 397-0534</span>
                            </a>
                        </div>

                        <div class="p-4 bg-obsidian-900 grid grid-cols-3 gap-2 text-center border-t border-zinc-800">
                            <div class="p-2.5 rounded-xl bg-obsidian-800/80 border border-zinc-800">
                                <i class="fa-solid fa-wrench text-amber-500 text-sm mb-1"></i>
                                <p class="text-[11px] font-bold text-white">$85/hr Repair</p>
                            </div>
                            <div class="p-2.5 rounded-xl bg-obsidian-800/80 border border-zinc-800">
                                <i class="fa-solid fa-fire text-crimson-500 text-sm mb-1"></i>
                                <p class="text-[11px] font-bold text-white">$100/hr Big Bore</p>
                            </div>
                            <div class="p-2.5 rounded-xl bg-obsidian-800/80 border border-zinc-800">
                                <i class="fa-solid fa-motorcycle text-amber-400 text-sm mb-1"></i>
                                <p class="text-[11px] font-bold text-white">$200/hr Custom</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 2. Labor Rates & Deposit Structure -->
    <section id="rates" class="py-16 bg-obsidian-900 border-b border-zinc-800 relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row md:items-end justify-between mb-10">
                <div>
                    <span class="text-crimson-500 font-mono text-xs uppercase tracking-widest block mb-2">// 01. STRAIGHT LABOR & DEPOSIT POLICY</span>
                    <h2 class="text-3xl sm:text-4xl font-display font-extrabold text-white uppercase tracking-tight">
                        Labor Rates & <span class="text-crimson-500">Deposit Rules.</span>
                    </h2>
                </div>
                <p class="text-zinc-400 text-sm max-w-md mt-2 md:mt-0 font-mono">
                    Clear hourly labor tiers. Your parts deposit goes straight toward covering parts.
                </p>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
                <!-- Tier 1: General Repair & Lawnmowers -->
                <div class="p-6 rounded-2xl bg-obsidian-950 border border-zinc-800 hover:border-amber-500/60 transition-all flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between mb-4">
                            <span class="px-2.5 py-1 rounded bg-zinc-800 border border-zinc-700 text-zinc-300 font-mono text-xs font-bold">STANDARD LABOR</span>
                            <i class="fa-solid fa-seedling text-amber-500 text-lg"></i>
                        </div>
                        <p class="text-4xl font-display font-extrabold text-white">$85<span class="text-lg text-zinc-400 font-mono">/hr</span></p>
                        <h3 class="text-base font-display font-bold text-zinc-100 mt-1 uppercase">General Repair & Mowers</h3>
                        <p class="text-xs text-zinc-400 mt-3 leading-relaxed">
                            OEM carb rebuilds, valve lash adjustments, drive belt replacements, brake/tire service, stock engine refreshes, and complete lawnmower engine repair & deck maintenance.
                        </p>
                    </div>
                    <div class="mt-5 pt-3 border-t border-zinc-800/80 text-[11px] font-mono text-amber-400">
                        MAINTENANCE, REPAIR & LAWNMOWERS
                    </div>
                </div>

                <!-- Tier 2: Performance & Big Bore -->
                <div class="p-6 rounded-2xl bg-obsidian-950 border border-crimson-600/60 hover:border-crimson-500 transition-all flex flex-col justify-between shadow-lg shadow-crimson-600/10">
                    <div>
                        <div class="flex items-center justify-between mb-4">
                            <span class="px-2.5 py-1 rounded bg-crimson-600/20 border border-crimson-500/40 text-crimson-400 font-mono text-xs font-bold">MODIFIED ENGINES</span>
                            <i class="fa-solid fa-fire-flame-curved text-crimson-500 text-lg"></i>
                        </div>
                        <p class="text-4xl font-display font-extrabold text-white">$100<span class="text-lg text-crimson-400 font-mono">/hr</span></p>
                        <h3 class="text-base font-display font-bold text-zinc-100 mt-1 uppercase">Performance / Big Bore</h3>
                        <p class="text-xs text-zinc-400 mt-3 leading-relaxed">
                            50cc-to-100cc+ GY6 conversions, high-lift cams, performance CVT clutch tuning, flat-slide carb swaps, Predator governor deletes, and small engine swaps.
                        </p>
                    </div>
                    <div class="mt-5 pt-3 border-t border-zinc-800/80 text-[11px] font-mono text-crimson-400">
                        PERFORMANCE TUNING & BIG BORES
                    </div>
                </div>

                <!-- Tier 3: Fully Custom Builds (Available Off-Road Only) -->
                <div class="p-6 rounded-2xl bg-obsidian-950 border border-amber-500/60 hover:border-amber-400 transition-all flex flex-col justify-between relative overflow-hidden">
                    <div class="absolute -right-12 top-6 bg-amber-500 text-obsidian-950 font-mono text-[10px] font-bold py-1 px-12 rotate-45 uppercase">
                        Off-Road Only
                    </div>
                    <div>
                        <div class="flex items-center justify-between mb-4">
                            <span class="px-2.5 py-1 rounded bg-amber-500/10 border border-amber-500/30 text-amber-400 font-mono text-xs font-bold">CUSTOM FAB</span>
                            <i class="fa-solid fa-motorcycle text-amber-400 text-lg"></i>
                        </div>
                        <p class="text-4xl font-display font-extrabold text-white">$200<span class="text-lg text-zinc-400 font-mono">/hr</span></p>
                        <h3 class="text-base font-display font-bold text-zinc-100 mt-1 uppercase">Off-Road Custom Builds</h3>
                        <p class="text-xs text-zinc-400 mt-3 leading-relaxed">
                            Ground-up off-road trail vehicles, go-karts, and custom chassis fabrication. Requires upfront quote covering labor & all parts.
                        </p>
                    </div>
                    <div class="mt-5 pt-3 border-t border-zinc-800/80 text-[11px] font-mono text-amber-400 font-bold">
                        AVAILABLE OFF-ROAD ONLY
                    </div>
                </div>

                <!-- Tier 4: Deposit Rate Rule -->
                <div class="p-6 rounded-2xl bg-gradient-to-b from-obsidian-950 to-crimson-950/25 border-2 border-crimson-600/70 flex flex-col justify-between relative">
                    <div>
                        <div class="flex items-center justify-between mb-4">
                            <span class="px-2.5 py-1 rounded bg-crimson-600 text-white font-mono text-xs font-bold uppercase">DEPOSIT RULE</span>
                            <i class="fa-solid fa-piggy-bank text-amber-400 text-lg"></i>
                        </div>
                        <p class="text-3xl font-display font-extrabold text-amber-400">$50 + $0.50/cc</p>
                        <h3 class="text-base font-display font-bold text-white mt-1 uppercase">Parts Deposit Policy</h3>
                        <p class="text-xs text-zinc-300 mt-3 leading-relaxed">
                            Standard drop-offs require a deposit of <strong class="text-white">$50 plus $0.50 per engine cc</strong> for parts. Off-road custom builds require an upfront quote covering all parts and labor.
                        </p>
                    </div>
                    <div class="mt-5 pt-3 border-t border-crimson-800/50 text-[11px] font-mono text-amber-300">
                        DEPOSIT COVERS PARTS // PAY REMAINDER
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 3. Interactive Labor & Deposit Estimator -->
    <section id="calculator" class="py-24 bg-obsidian-950 border-b border-zinc-900 relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="text-center max-w-3xl mx-auto mb-14">
                <span class="text-crimson-500 font-mono text-xs uppercase tracking-widest block mb-2">// 02. QUOTE & WORK ORDER ESTIMATOR</span>
                <h2 class="text-3xl sm:text-5xl font-display font-extrabold text-white uppercase tracking-tight">
                    Labor & Deposit <span class="text-crimson-500">Estimator.</span>
                </h2>
                <p class="text-zinc-400 text-sm sm:text-base mt-3">
                    Select your service tier, displacement, provide your project description and budget, and submit your work order specs.
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-start">
                <!-- Form Inputs -->
                <form id="quote-form" class="lg:col-span-7 p-6 sm:p-9 rounded-2xl bg-obsidian-900 border border-zinc-800 shadow-2xl space-y-6">
                    <div class="flex items-center justify-between border-b border-zinc-800 pb-4">
                        <span class="font-mono text-xs uppercase tracking-widest text-zinc-400">CC BUILDS // WORK ORDER</span>
                        <span class="px-2.5 py-1 rounded bg-crimson-600/20 text-crimson-400 border border-crimson-500/30 font-mono text-[11px]">MAX 400CC + MOWERS</span>
                    </div>

                    <!-- Service Tier -->
                    <div>
                        <label class="block text-xs font-mono uppercase tracking-wider text-zinc-300 mb-3">1. Select Service / Labor Rate Tier *</label>
                        <div class="grid grid-cols-1 sm:grid-cols-3 gap-3">
                            <label class="cursor-pointer">
                                <input type="radio" name="service_rate" value="85" class="peer sr-only" id="rate-repair">
                                <div class="p-3.5 rounded-xl bg-obsidian-950 border-2 border-zinc-800 peer-checked:border-amber-500 peer-checked:bg-amber-500/10 transition-all h-full flex flex-col justify-between">
                                    <span class="font-display font-bold text-white text-xs uppercase block">Repair / Mower</span>
                                    <span class="font-mono font-bold text-amber-400 text-sm mt-1">$85/hr</span>
                                </div>
                            </label>

                            <label class="cursor-pointer">
                                <input type="radio" name="service_rate" value="100" class="peer sr-only" id="rate-performance" checked>
                                <div class="p-3.5 rounded-xl bg-obsidian-950 border-2 border-zinc-800 peer-checked:border-crimson-500 peer-checked:bg-crimson-600/10 transition-all h-full flex flex-col justify-between">
                                    <span class="font-display font-bold text-white text-xs uppercase block">Performance</span>
                                    <span class="font-mono font-bold text-crimson-400 text-sm mt-1">$100/hr</span>
                                </div>
                            </label>

                            <label class="cursor-pointer">
                                <input type="radio" name="service_rate" value="200" class="peer sr-only" id="rate-custom">
                                <div class="p-3.5 rounded-xl bg-obsidian-950 border-2 border-zinc-800 peer-checked:border-amber-400 peer-checked:bg-amber-400/10 transition-all h-full flex flex-col justify-between">
                                    <div class="flex items-center justify-between">
                                        <span class="font-display font-bold text-white text-xs uppercase">Off-Road Custom</span>
                                        <span class="text-[9px] font-mono text-amber-400 uppercase font-bold">Quote</span>
                                    </div>
                                    <span class="font-mono font-bold text-amber-400 text-sm mt-1">$200/hr</span>
                                </div>
                            </label>
                        </div>
                    </div>

                    <!-- Engine CC (For Deposit Calculation) -->
                    <div class="p-4 rounded-xl bg-obsidian-950 border border-zinc-800">
                        <div class="flex justify-between items-center mb-2">
                            <label for="cc-slider" class="text-xs font-mono uppercase tracking-wider text-zinc-300">2. Engine Displacement (Cubic Centimeters)</label>
                            <span class="px-3 py-1 rounded-lg bg-obsidian-900 border border-zinc-700 font-mono font-bold text-sm text-amber-400">
                                <span id="cc-display">100</span> cc
                            </span>
                        </div>
                        <input type="range" id="cc-slider" min="50" max="400" step="5" value="100" class="w-full accent-amber-500 cursor-pointer">
                        <div class="flex justify-between text-[10px] font-mono text-zinc-500 mt-1.5">
                            <span>50cc ($75 dep)</span>
                            <span>150cc ($125)</span>
                            <span>250cc ($175)</span>
                            <span>400cc ($250 dep)</span>
                        </div>
                        <p class="text-[11px] font-mono text-zinc-400 mt-2">
                            Formula: $50 base + ($0.50 × <span id="formula-cc">100</span>cc) = <strong id="formula-deposit" class="text-amber-400 font-bold">$100.00</strong> parts deposit (Standard builds).
                        </p>
                    </div>

                    <!-- Estimated Labor Hours -->
                    <div class="p-4 rounded-xl bg-obsidian-950 border border-zinc-800">
                        <div class="flex justify-between items-center mb-2">
                            <label for="hours-slider" class="text-xs font-mono uppercase tracking-wider text-zinc-300">3. Estimated Labor Hours</label>
                            <span class="px-3 py-1 rounded-lg bg-obsidian-900 border border-zinc-700 font-mono font-bold text-sm text-white">
                                <span id="hours-display">4</span> hrs
                            </span>
                        </div>
                        <input type="range" id="hours-slider" min="1" max="40" step="0.5" value="4" class="w-full accent-crimson-600 cursor-pointer">
                        <div class="flex justify-between text-[10px] font-mono text-zinc-500 mt-1.5">
                            <span>1 hr</span>
                            <span>10 hrs</span>
                            <span>25 hrs</span>
                            <span>40 hrs (Custom Off-Road)</span>
                        </div>
                    </div>

                    <!-- Project Description & Budget -->
                    <div class="pt-2 border-t border-zinc-800 space-y-4">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label for="rider-name" class="block text-xs font-mono uppercase tracking-wider text-zinc-300 mb-1.5">Your Name *</label>
                                <input type="text" id="rider-name" required placeholder="Colton Vance" class="w-full px-4 py-3 rounded-xl bg-obsidian-950 border border-zinc-700 text-white text-sm focus:outline-none focus:border-crimson-500">
                            </div>
                            <div>
                                <label for="rider-phone" class="block text-xs font-mono uppercase tracking-wider text-zinc-300 mb-1.5">Phone / Text *</label>
                                <input type="tel" id="rider-phone" required placeholder="(479) 397-0534" class="w-full px-4 py-3 rounded-xl bg-obsidian-950 border border-zinc-700 text-white text-sm focus:outline-none focus:border-crimson-500">
                            </div>
                        </div>

                        <div>
                            <label for="build-description" class="block text-xs font-mono uppercase tracking-wider text-zinc-300 mb-1.5">Detailed Description of What You Want Built / Repaired *</label>
                            <textarea id="build-description" required rows="3" placeholder="Describe your machine, engine type (scooter, pit bike, lawnmower, off-road custom), and exact work needed..." class="w-full px-4 py-3 rounded-xl bg-obsidian-950 border border-zinc-700 text-white text-sm focus:outline-none focus:border-crimson-500"></textarea>
                        </div>

                        <div>
                            <label for="project-budget" class="block text-xs font-mono uppercase tracking-wider text-amber-400 mb-1.5">Target Budget ($) *</label>
                            <input type="text" id="project-budget" required placeholder="$500 - $1,500" class="w-full px-4 py-3 rounded-xl bg-obsidian-950 border border-amber-500/50 text-white text-sm focus:outline-none focus:border-amber-400">
                        </div>
                    </div>

                    <button type="submit" class="w-full py-4 px-8 rounded-xl bg-crimson-600 hover:bg-crimson-500 text-white font-display font-bold text-sm uppercase tracking-wider shadow-xl shadow-crimson-600/25 transition-all transform hover:-translate-y-0.5 flex items-center justify-center space-x-3">
                        <i class="fa-solid fa-paper-plane"></i>
                        <span>Submit Quote & Work Order</span>
                    </button>
                </form>

                <!-- Receipt Breakdown -->
                <div class="lg:col-span-5 lg:sticky lg:top-28 space-y-6">
                    <div class="rounded-2xl bg-obsidian-900 border-2 border-zinc-800 overflow-hidden shadow-2xl">
                        <div class="p-5 bg-obsidian-950 border-b border-zinc-800 flex items-center justify-between">
                            <div>
                                <span class="text-[11px] font-mono text-crimson-500 uppercase tracking-widest block">WORK ORDER SUMMARY</span>
                                <h3 class="text-xl font-display font-extrabold text-white uppercase">Estimate & Quote</h3>
                            </div>
                            <i class="fa-solid fa-receipt text-2xl text-zinc-600"></i>
                        </div>

                        <div class="p-6 space-y-5">
                            <!-- Deposit / Quote Breakdown -->
                            <div class="p-4 rounded-xl bg-amber-500/10 border border-amber-500/40 space-y-2">
                                <div class="flex items-center justify-between">
                                    <span class="text-xs font-mono font-bold uppercase text-amber-400">PARTS DEPOSIT / UPFRONT QUOTE</span>
                                    <span class="px-2 py-0.5 rounded bg-amber-500 text-obsidian-950 font-mono text-[10px] font-bold">REQUIRED</span>
                                </div>
                                <div class="flex justify-between text-xs text-zinc-300 pt-1">
                                    <span>Base Drop-Off Fee:</span>
                                    <span class="font-mono text-zinc-200">$50.00</span>
                                </div>
                                <div class="flex justify-between text-xs text-zinc-300">
                                    <span>Displacement Rate (<span id="calc-cc-label">100</span>cc × $0.50):</span>
                                    <span id="calc-cc-charge" class="font-mono text-amber-400">+$50.00</span>
                                </div>
                                <div class="pt-2 border-t border-amber-500/30 flex justify-between items-baseline">
                                    <span class="text-xs font-display font-bold uppercase text-white">Parts Deposit Total:</span>
                                    <span id="summary-deposit-total" class="text-2xl font-mono font-bold text-amber-400">$100.00</span>
                                </div>
                                <p class="text-[10px] text-zinc-400 italic pt-1 leading-relaxed">
                                    * Off-road custom builds require an upfront quote covering all labor and parts.
                                </p>
                            </div>

                            <!-- Labor Estimate -->
                            <div class="space-y-2.5 text-sm border-b border-zinc-800 pb-5">
                                <div class="flex justify-between text-xs text-zinc-400">
                                    <span>Selected Service Tier:</span>
                                    <span id="summary-rate-label" class="font-mono text-zinc-200">$100/hr (Performance)</span>
                                </div>
                                <div class="flex justify-between text-xs text-zinc-400">
                                    <span>Estimated Labor Hours:</span>
                                    <span id="summary-hours-label" class="font-mono text-zinc-200">4.0 hrs</span>
                                </div>
                                <div class="flex justify-between items-baseline pt-1">
                                    <span class="text-xs font-display font-bold uppercase text-zinc-300">Estimated Labor Total:</span>
                                    <span id="summary-labor-total" class="text-xl font-mono font-bold text-white">$400.00</span>
                                </div>
                            </div>

                            <!-- Estimated Total Commitment -->
                            <div class="flex justify-between items-center pt-1">
                                <div>
                                    <span class="text-xs font-mono font-bold uppercase text-zinc-300 block">ESTIMATED TOTAL</span>
                                    <span class="text-[11px] text-zinc-500">Deposit (Parts) + Estimated Labor</span>
                                </div>
                                <span id="summary-grand-total" class="text-3xl font-display font-extrabold text-crimson-500">$500.00</span>
                            </div>
                        </div>

                        <div class="px-6 py-4 bg-obsidian-950 border-t border-zinc-800 text-[11px] text-zinc-400 leading-relaxed">
                            <i class="fa-solid fa-triangle-exclamation text-amber-500 mr-1"></i>
                            <strong>Note:</strong> All custom off-road builds require a comprehensive upfront quote detailing parts and labor before wrenching begins.
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 4. Specialized Services & Lawnmowers -->
    <section id="services" class="py-24 bg-obsidian-900 border-b border-zinc-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row md:items-end justify-between mb-16">
                <div>
                    <span class="text-crimson-500 font-mono text-xs uppercase tracking-widest block mb-2">// 03. SPECIALIZED SMALL ENGINES & MOWERS</span>
                    <h2 class="text-3xl sm:text-5xl font-display font-extrabold text-white uppercase tracking-tight">
                        Built For <span class="text-crimson-500">50cc To 400cc & Mowers.</span>
                    </h2>
                </div>
                <p class="text-zinc-400 text-sm sm:text-base max-w-md mt-4 md:mt-0">
                    From performance GY6 scooters and off-road custom builds to lawnmower engine repair and blade sharpening.
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-3 gap-8">
                <!-- Service 1 -->
                <div class="rounded-2xl bg-obsidian-950 border border-zinc-800 hover:border-crimson-500/60 transition-all duration-300 flex flex-col justify-between overflow-hidden group red-glow">
                    <div>
                        <div class="h-52 overflow-hidden relative bg-obsidian-900">
                            <img src="https://images.unsplash.com/photo-1568772585407-9361f9bf3a87?auto=format&fit=crop&w=800&q=80" 
                                 onerror="this.src='https://placehold.co/600x400/14141b/dc2626?text=BIG+BORE+TOP+ENDS'"
                                 alt="Big Bore Cylinder and Top End Build" 
                                 class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500 opacity-85">
                            <div class="absolute inset-0 bg-gradient-to-t from-obsidian-950 via-obsidian-950/30 to-transparent"></div>
                            <span class="absolute top-4 left-4 px-3 py-1 rounded-lg bg-obsidian-900/90 border border-zinc-700 text-crimson-500 font-mono text-xs font-bold">$100/HR LABOR</span>
                        </div>
                        <div class="p-7">
                            <div class="flex items-center justify-between mb-3">
                                <h3 class="text-2xl font-display font-bold text-white">Big Bore & Top-End Conversions</h3>
                                <i class="fa-solid fa-piston text-crimson-500 text-xl"></i>
                            </div>
                            <p class="text-zinc-400 text-sm leading-relaxed mb-6">
                                Turn a sluggish 50cc into a 100cc sleeper, or rebuild your blown small-bore motor up to 400cc.
                            </p>
                            <ul class="space-y-2.5 text-xs text-zinc-300 border-t border-zinc-800 pt-5">
                                <li class="flex items-start space-x-2.5">
                                    <i class="fa-solid fa-check text-crimson-500 mt-0.5"></i>
                                    <span>50cc to 80cc / 100cc+ GY6 Big Bore Kits</span>
                                </li>
                                <li class="flex items-start space-x-2.5">
                                    <i class="fa-solid fa-check text-crimson-500 mt-0.5"></i>
                                    <span>Ported Heads & Performance A9/A14 Cams</span>
                                </li>
                                <li class="flex items-start space-x-2.5">
                                    <i class="fa-solid fa-check text-crimson-500 mt-0.5"></i>
                                    <span>Predator 212 / 224 Billet Rods & Governor Deletes</span>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>

                <!-- Service 2 -->
                <div class="rounded-2xl bg-obsidian-950 border border-zinc-800 hover:border-amber-500/60 transition-all duration-300 flex flex-col justify-between overflow-hidden group red-glow">
                    <div>
                        <div class="h-52 overflow-hidden relative bg-obsidian-900">
                            <img src="https://images.unsplash.com/photo-1592417817098-8f3d692ad4b5?auto=format&fit=crop&w=800&q=80" 
                                 onerror="this.src='https://placehold.co/600x400/14141b/f59e0b?text=LAWNMOWER+REPAIR'"
                                 alt="Lawnmower and Small Engine Repair" 
                                 class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500 opacity-85">
                            <div class="absolute inset-0 bg-gradient-to-t from-obsidian-950 via-obsidian-950/30 to-transparent"></div>
                            <span class="absolute top-4 left-4 px-3 py-1 rounded-lg bg-obsidian-900/90 border border-zinc-700 text-amber-400 font-mono text-xs font-bold">$85/HR LABOR</span>
                        </div>
                        <div class="p-7">
                            <div class="flex items-center justify-between mb-3">
                                <h3 class="text-2xl font-display font-bold text-white">Lawnmower & General Repair</h3>
                                <i class="fa-solid fa-seedling text-amber-500 text-xl"></i>
                            </div>
                            <p class="text-zinc-400 text-sm leading-relaxed mb-6">
                                Complete lawnmower engine diagnostics, carburetor cleaning, belt replacements, deck maintenance, and blade sharpening.
                            </p>
                            <ul class="space-y-2.5 text-xs text-zinc-300 border-t border-zinc-800 pt-5">
                                <li class="flex items-start space-x-2.5">
                                    <i class="fa-solid fa-check text-amber-500 mt-0.5"></i>
                                    <span>Riding & Push Lawnmower Engine Repair</span>
                                </li>
                                <li class="flex items-start space-x-2.5">
                                    <i class="fa-solid fa-check text-amber-500 mt-0.5"></i>
                                    <span>Carb Cleanouts & Fuel System Flushes</span>
                                </li>
                                <li class="flex items-start space-x-2.5">
                                    <i class="fa-solid fa-check text-amber-500 mt-0.5"></i>
                                    <span>Blade Sharpening & Deck Belt Swaps</span>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>

                <!-- Service 3 -->
                <div class="rounded-2xl bg-obsidian-950 border border-zinc-800 hover:border-amber-500/60 transition-all duration-300 flex flex-col justify-between overflow-hidden group red-glow">
                    <div>
                        <div class="h-52 overflow-hidden relative bg-obsidian-900">
                            <img src="https://images.unsplash.com/photo-1504917595217-d4dc5ebe6122?auto=format&fit=crop&w=800&q=80" 
                                 onerror="this.src='https://placehold.co/600x400/14141b/dc2626?text=OFF-ROAD+CUSTOMS'"
                                 alt="Off-Road Custom Builds" 
                                 class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500 opacity-85">
                            <div class="absolute inset-0 bg-gradient-to-t from-obsidian-950 via-obsidian-950/30 to-transparent"></div>
                            <span class="absolute top-4 left-4 px-3 py-1 rounded-lg bg-obsidian-900/90 border border-zinc-700 text-amber-400 font-mono text-xs font-bold">$200/HR (OFF-ROAD ONLY)</span>
                        </div>
                        <div class="p-7">
                            <div class="flex items-center justify-between mb-3">
                                <h3 class="text-2xl font-display font-bold text-white">Off-Road Custom Builds</h3>
                                <i class="fa-solid fa-motorcycle text-amber-400 text-xl"></i>
                            </div>
                            <p class="text-zinc-400 text-sm leading-relaxed mb-6">
                                Ground-up trail vehicles, go-karts, and engine swaps up to 400cc.
                            </p>
                            <ul class="space-y-2.5 text-xs text-zinc-300 border-t border-zinc-800 pt-5">
                                <li class="flex items-start space-x-2.5">
                                    <i class="fa-solid fa-check text-amber-400 mt-0.5"></i>
                                    <span>Off-Road Trail Vehicles & Go-Karts</span>
                                </li>
                                <li class="flex items-start space-x-2.5">
                                    <i class="fa-solid fa-check text-amber-400 mt-0.5"></i>
                                    <span>Custom Engine Swaps & Chain Drives</span>
                                </li>
                                <li class="flex items-start space-x-2.5">
                                    <i class="fa-solid fa-check text-amber-400 mt-0.5"></i>
                                    <span>Upfront Quoted Labor & Parts Packages</span>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 5. Shop Policies & Location -->
    <section id="policies" class="py-20 bg-obsidian-950 border-b border-zinc-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-10 items-center">
                <!-- Shop Rules -->
                <div class="lg:col-span-7 space-y-6">
                    <div class="inline-flex items-center space-x-2 text-amber-400 font-mono text-xs uppercase tracking-widest">
                        <i class="fa-solid fa-gavel"></i>
                        <span>// 04. SHOP POLICIES & QUOTE RULES</span>
                    </div>
                    <h2 class="text-3xl sm:text-4xl font-display font-extrabold text-white uppercase tracking-tight">
                        Clear Terms. <span class="text-crimson-500">No BS.</span>
                    </h2>

                    <div class="space-y-4">
                        <div class="p-5 rounded-xl bg-obsidian-900 border-l-4 border-crimson-600 border border-zinc-800">
                            <h4 class="font-display font-bold text-white text-sm uppercase">1. Parts Deposit & Upfront Quotes</h4>
                            <p class="text-xs text-zinc-400 mt-1 leading-relaxed">
                                Standard repairs and big bores require a parts deposit of <strong class="text-zinc-200">$50 + $0.50/cc</strong>. Off-road custom builds require a comprehensive upfront quote covering all labor and parts before work begins.
                            </p>
                        </div>

                        <div class="p-5 rounded-xl bg-obsidian-900 border-l-4 border-amber-500 border border-zinc-800">
                            <h4 class="font-display font-bold text-white text-sm uppercase">2. Upfront Hourly Labor Rates</h4>
                            <p class="text-xs text-zinc-400 mt-1 leading-relaxed">
                                General repair & lawnmowers: <strong class="text-zinc-200">$85/hr</strong>. Performance & big bore tuning: <strong class="text-zinc-200">$100/hr</strong>. Off-road custom fabrication: <strong class="text-zinc-200">$200/hr</strong>.
                            </p>
                        </div>

                        <div class="p-5 rounded-xl bg-obsidian-900 border-l-4 border-zinc-600 border border-zinc-800">
                            <h4 class="font-display font-bold text-white text-sm uppercase">3. Completion & Appointment Policy</h4>
                            <p class="text-xs text-zinc-400 mt-1 leading-relaxed">
                                Once finished, you have 7 calendar days to settle remaining balances and pick up your machine. All drop-offs and pick-ups are strictly by appointment.
                            </p>
                        </div>
                    </div>
                </div>

                <!-- Business Address Box -->
                <div class="lg:col-span-5">
                    <div class="p-7 sm:p-8 rounded-2xl bg-obsidian-900 border border-zinc-800 shadow-2xl space-y-6">
                        <div class="flex items-center justify-between border-b border-zinc-800 pb-4">
                            <div>
                                <span class="text-xs font-mono text-crimson-500 uppercase">OFFICIAL SHOP LOCATION</span>
                                <h3 class="text-2xl font-display font-extrabold text-white uppercase">Wesley, Arkansas</h3>
                            </div>
                            <div class="w-12 h-12 rounded-xl bg-crimson-600/15 border border-crimson-500/40 flex items-center justify-center text-crimson-500">
                                <i class="fa-solid fa-location-dot text-xl"></i>
                            </div>
                        </div>

                        <div class="space-y-4 text-sm">
                            <div class="flex items-start space-x-3.5">
                                <i class="fa-solid fa-map-location-dot text-crimson-500 mt-1"></i>
                                <div>
                                    <p class="font-display font-bold text-white uppercase">Shop Address</p>
                                    <a href="https://www.google.com/maps/search/?api=1&query=1610+Madison+County+Rd+6345,+Wesley,+AR+72773" target="_blank" rel="noopener noreferrer" class="text-sm font-mono text-amber-400 font-bold mt-0.5 hover:underline block">
                                        1610 Madison County Rd 6345<br>Wesley, Arkansas 72773
                                    </a>
                                    <p class="text-xs text-zinc-400 mt-1">Serving Washington & Madison Counties and NWA.</p>
                                </div>
                            </div>

                            <div class="flex items-start space-x-3.5">
                                <i class="fa-solid fa-gauge text-amber-500 mt-1"></i>
                                <div>
                                    <p class="font-display font-bold text-white uppercase">Engine Capacity</p>
                                    <p class="text-xs text-zinc-400 mt-0.5">50cc to 400cc small engines & lawnmowers.</p>
                                </div>
                            </div>

                            <div class="flex items-start space-x-3.5">
                                <i class="fa-solid fa-envelope text-crimson-500 mt-1"></i>
                                <div>
                                    <p class="font-display font-bold text-white uppercase">Direct Dispatch</p>
                                    <a href="mailto:CCBuilds@pm.me" class="text-xs font-mono text-zinc-300 hover:text-white mt-0.5 block transition-colors" id="shop-email">CCBuilds@pm.me</a>
                                </div>
                            </div>

                            <div class="flex items-start space-x-3.5">
                                <i class="fa-solid fa-phone text-amber-500 mt-1"></i>
                                <div>
                                    <p class="font-display font-bold text-white uppercase">Shop Phone / Text</p>
                                    <a href="tel:4793970534" class="text-xs font-mono text-amber-400 hover:underline mt-0.5 block font-bold">(479) 397-0534</a>
                                </div>
                            </div>
                        </div>

                        <div class="pt-4 border-t border-zinc-800">
                            <a href="#calculator" class="w-full py-3.5 px-6 rounded-xl bg-crimson-600 hover:bg-crimson-500 text-white font-display font-bold text-xs uppercase tracking-wider transition-all flex items-center justify-center space-x-2">
                                <i class="fa-solid fa-calculator"></i>
                                <span>Calculate Labor & Deposit</span>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-obsidian-950 py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row items-center justify-between gap-6">
                <div class="flex items-center space-x-3">
                    <img src="https://i.postimg.cc/SR6BPY2D/1791984296717-1.png" alt="Criminally Custom Builds" class="w-10 h-10 rounded-full border border-amber-500/80 object-cover">
                    <div>
                        <span class="text-base font-display font-extrabold tracking-wider text-white">CRIMINALLY CUSTOM BUILDS (CC BUILDS)</span>
                        <p class="text-xs text-zinc-500">1610 Madison County Rd 6345, Wesley, AR 72773 // Phone: (479) 397-0534</p>
                    </div>
                </div>

                <div class="text-center md:text-right text-xs font-mono text-zinc-500 space-y-1">
                    <p>Labor: $85/hr Repair & Mowers | $100/hr Performance | $200/hr Off-Road Custom</p>
                    <p>Deposit: $50 + $0.50/cc | Email: CCBuilds@pm.me</p>
                </div>
            </div>
        </div>
    </footer>

    <!-- Interactive Logic -->
    <script>
        // Mobile Menu
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');

        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        mobileMenu.querySelectorAll('a').forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });

        // Toast Helper
        function showToast(title, message) {
            const toast = document.getElementById('toast');
            document.getElementById('toast-title').textContent = title;
            document.getElementById('toast-msg').textContent = message;
            toast.classList.remove('translate-y-32', 'opacity-0');
            setTimeout(() => {
                toast.classList.add('translate-y-32', 'opacity-0');
            }, 4500);
        }

        // Estimator Calculation Logic
        const rateRadios = document.querySelectorAll('input[name="service_rate"]');
        const ccSlider = document.getElementById('cc-slider');
        const ccDisplay = document.getElementById('cc-display');
        const formulaCc = document.getElementById('formula-cc');
        const formulaDeposit = document.getElementById('formula-deposit');
        const calcCcLabel = document.getElementById('calc-cc-label');
        const calcCcCharge = document.getElementById('calc-cc-charge');

        const hoursSlider = document.getElementById('hours-slider');
        const hoursDisplay = document.getElementById('hours-display');

        const summaryDepositTotal = document.getElementById('summary-deposit-total');
        const summaryRateLabel = document.getElementById('summary-rate-label');
        const summaryHoursLabel = document.getElementById('summary-hours-label');
        const summaryLaborTotal = document.getElementById('summary-labor-total');
        const summaryGrandTotal = document.getElementById('summary-grand-total');

        function formatCurrency(num) {
            return '$' + num.toFixed(2).replace(/\B(?=(\d{3})+(?!\d))/g, ',');
        }

        function updateCalculator() {
            const selectedRate = parseFloat(document.querySelector('input[name="service_rate"]:checked').value);
            const cc = parseFloat(ccSlider.value) || 50;
            const hours = parseFloat(hoursSlider.value) || 0;

            const ccVariableDeposit = cc * 0.50;
            const totalDeposit = 50 + ccVariableDeposit;
            const laborTotal = hours * selectedRate;
            const grandTotal = totalDeposit + laborTotal;

            ccDisplay.textContent = cc;
            formulaCc.textContent = cc;
            calcCcLabel.textContent = cc;
            calcCcCharge.textContent = '+' + formatCurrency(ccVariableDeposit);
            formulaDeposit.textContent = formatCurrency(totalDeposit);
            summaryDepositTotal.textContent = formatCurrency(totalDeposit);

            hoursDisplay.textContent = hours % 1 === 0 ? hours : hours.toFixed(1);
            summaryHoursLabel.textContent = (hours % 1 === 0 ? hours : hours.toFixed(1)) + ' hrs';

            let rateText = `$${selectedRate}/hr (General Repair & Mowers)`;
            if (selectedRate === 100) rateText = `$100/hr (Performance / Big Bore)`;
            if (selectedRate === 200) rateText = `$200/hr (Off-Road Custom Builds - Quoted)`;

            summaryRateLabel.textContent = rateText;
            summaryLaborTotal.textContent = formatCurrency(laborTotal);
            summaryGrandTotal.textContent = formatCurrency(grandTotal);
        }

        rateRadios.forEach(radio => radio.addEventListener('change', updateCalculator));
        ccSlider.addEventListener('input', updateCalculator);
        hoursSlider.addEventListener('input', updateCalculator);

        updateCalculator();

        // Form Submit
        const quoteForm = document.getElementById('quote-form');
        quoteForm.addEventListener('submit', (e) => {
            e.preventDefault();
            const riderName = document.getElementById('rider-name').value;
            const budget = document.getElementById('project-budget').value;
            showToast(
                `Quote Request Logged // ${riderName}`,
                `Submitted successfully! Target Budget: ${budget}. We will review your build description and contact you.`
            );
        });
    </script>
</body>
</html>
