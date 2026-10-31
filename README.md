
<html lang="en" class="dark">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Criminally Custom Builds - Shop Sign</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@700;800&family=Space+Grotesk:wght@700;900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    fontFamily: {
                        display: ['Space Grotesk', 'sans-serif'],
                        mono: ['JetBrains Mono', 'monospace'],
                    },
                    colors: {
                        crimson: { 500: '#ef4444', 600: '#dc2626' },
                        obsidian: { 950: '#070709', 900: '#0c0c10', 800: '#14141b' }
                    }
                }
            }
        }
    </script>
    <style>
        body { background-color: #030305; color: #ffffff; }
        .caution-stripes {
            background: repeating-linear-gradient(-45deg, #dc2626, #dc2626 16px, #070709 16px, #070709 32px);
        }
        .sign-glow {
            box-shadow: 0 0 60px -10px rgba(220, 38, 38, 0.35), inset 0 0 40px rgba(0, 0, 0, 0.8);
        }
        .metal-plate {
            background: linear-gradient(135deg, #14141b 0%, #0c0c10 50%, #070709 100%);
        }
    </style>
</head>
<body class="min-h-screen flex items-center justify-center p-4 sm:p-8">

    <!-- Printable / Displayable Shop Sign Container -->
    <div class="w-full max-w-4xl metal-plate border-4 border-zinc-800 rounded-3xl sign-glow overflow-hidden relative">
        
        <!-- Top Hazard Stripe -->
        <div class="h-3 w-full caution-stripes"></div>

        <!-- Bolt Accents (Visual Hardware) -->
        <div class="absolute top-6 left-6 w-4 h-4 rounded-full bg-zinc-700 border-2 border-zinc-900 shadow-inner flex items-center justify-center text-[8px] text-zinc-500 font-mono">+</div>
        <div class="absolute top-6 right-6 w-4 h-4 rounded-full bg-zinc-700 border-2 border-zinc-900 shadow-inner flex items-center justify-center text-[8px] text-zinc-500 font-mono">+</div>

        <!-- Sign Content -->
        <div class="p-8 sm:p-14 text-center flex flex-col items-center space-y-6">

            <!-- Logo & Header Group -->
            <div class="flex flex-col items-center space-y-4">
                <img src="https://i.postimg.cc/SR6BPY2D/1791984296717-1.png" alt="Criminally Custom Builds Logo" class="w-28 h-28 sm:w-36 sm:h-36 object-contain rounded-full border-2 border-amber-500/80 shadow-2xl bg-obsidian-950 p-2">
                
                <div>
                    <span class="text-xs sm:text-sm font-mono uppercase tracking-[0.3em] text-amber-500 font-bold block mb-1">
                        EST. WESLEY, ARKANSAS
                    </span>
                    <h1 class="text-3xl sm:text-5xl lg:text-6xl font-display font-black tracking-wider text-white uppercase leading-none">
                        Criminally Custom <span class="text-transparent bg-clip-text bg-gradient-to-r from-crimson-500 to-amber-500">Builds</span>
                    </h1>
                </div>
            </div>

            <!-- Tagline Pill -->
            <div class="px-6 py-2 rounded-full bg-crimson-600/15 border border-crimson-500/50 text-crimson-400 font-mono text-xs sm:text-sm uppercase tracking-widest font-bold">
                // Unapologetically Modified //
            </div>

            <!-- Specs Grid -->
            <div class="w-full grid grid-cols-1 sm:grid-cols-3 gap-4 pt-4 border-t border-zinc-800/80 max-w-2xl text-center">
                <div class="p-3 rounded-xl bg-obsidian-950/80 border border-zinc-800">
                    <span class="text-[10px] font-mono text-zinc-500 uppercase block">Engine Capacity</span>
                    <span class="text-sm font-mono font-bold text-white">50cc – 250cc Only</span>
                </div>
                <div class="p-3 rounded-xl bg-obsidian-950/80 border border-zinc-800">
                    <span class="text-[10px] font-mono text-zinc-500 uppercase block">Specialty</span>
                    <span class="text-sm font-mono font-bold text-amber-400">GY6 Big Bores & Swaps</span>
                </div>
                <div class="p-3 rounded-xl bg-obsidian-950/80 border border-zinc-800">
                    <span class="text-[10px] font-mono text-zinc-500 uppercase block">Direct Dispatch</span>
                    <span class="text-sm font-mono font-bold text-crimson-400">(479) 397-0534</span>
                </div>
            </div>

            <!-- Footer Address & Notice -->
            <div class="pt-2 text-xs font-mono text-zinc-400 space-y-1">
                <p class="text-zinc-300 font-bold">1610 Madison 6345, Wesley, AR 72773</p>
                <p class="text-[11px] text-zinc-500">Drop-Offs & Pick-Ups Strictly By Appointment • CCBuilds@pm.me</p>
            </div>

        </div>

        <!-- Bottom Hazard Stripe -->
        <div class="h-3 w-full caution-stripes"></div>

        <!-- Bolt Accents (Visual Hardware) -->
        <div class="absolute bottom-6 left-6 w-4 h-4 rounded-full bg-zinc-700 border-2 border-zinc-900 shadow-inner flex items-center justify-center text-[8px] text-zinc-500 font-mono">+</div>
        <div class="absolute bottom-6 right-6 w-4 h-4 rounded-full bg-zinc-700 border-2 border-zinc-900 shadow-inner flex items-center justify-center text-[8px] text-zinc-500 font-mono">+</div>

    </div>

</body>
</html>
