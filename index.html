<!DOCTYPE html>
<html lang="en" class="light">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hembrom Books | हेम्ब्रम बुक्स Online Store</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        amber: {
                            50: '#fffbeb',
                            100: '#fef3c7',
                            200: '#fde68a',
                            600: '#d97706',
                            700: '#b45309',
                            800: '#92400e',
                            900: '#78350f',
                            950: '#451a03',
                        }
                    },
                    fontFamily: {
                        serif: ['Merriweather', 'Georgia', 'serif'],
                        sans: ['Inter', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <!-- Google Fonts & Lucide Icons -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Merriweather:ital,wght@0,300;0,400;0,700;1,300;1,400&display=swap" rel="stylesheet">
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        body { font-family: 'Inter', sans-serif; scroll-behavior: smooth; }
        h1, h2, h3, .font-serif-heading { font-family: 'Merriweather', Georgia, serif; }
        ::-webkit-scrollbar { width: 8px; }
        ::-webkit-scrollbar-track { background: rgba(0,0,0,0.05); }
        ::-webkit-scrollbar-thumb { background: #d97706; border-radius: 4px; }
        @keyframes slideUp { from { transform: translateY(100%); opacity: 0; } to { transform: translateY(0); opacity: 1; } }
        .toast-animate { animation: slideUp 0.3s cubic-bezier(0.16, 1, 0.3, 1) forwards; }
    </style>
</head>
<body class="bg-[#fdfbf7] text-slate-800 dark:bg-slate-950 dark:text-slate-100 transition-colors duration-300 min-h-screen flex flex-col">

    <!-- Toast Notifications Container -->
    <div id="toastContainer" class="fixed bottom-5 right-5 z-50 flex flex-col gap-2 pointer-events-none"></div>

    <!-- Admin Top Status Banner -->
    <div id="adminTopBanner" class="hidden bg-amber-800 text-amber-100 text-xs px-4 py-2 border-b border-amber-700 flex items-center justify-between z-40">
        <div class="flex items-center gap-2">
            <span class="w-2.5 h-2.5 rounded-full bg-green-400 animate-pulse"></span>
            <span class="font-bold">Logged in as Admin (5635hembrom@gmail.com)</span>
            <span class="hidden sm:inline text-amber-300">• You have full editing and publishing rights.</span>
        </div>
        <div class="flex items-center gap-2">
            <button onclick="openAddBookModal()" class="bg-amber-600 hover:bg-amber-500 text-white px-2.5 py-1 rounded text-[11px] font-bold flex items-center gap-1">
                <i data-lucide="plus-circle" class="w-3.5 h-3.5"></i> Add Book
            </button>
            <button onclick="adminLogout()" class="bg-red-600/80 hover:bg-red-600 text-white px-2.5 py-1 rounded text-[11px] font-bold flex items-center gap-1">
                <i data-lucide="log-out" class="w-3.5 h-3.5"></i> Logout
            </button>
        </div>
    </div>

    <!-- Navigation Bar -->
    <header class="sticky top-0 z-40 bg-[#fdfbf7]/90 dark:bg-slate-900/90 backdrop-blur-md border-b border-amber-200/60 dark:border-slate-800 transition-colors">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20 gap-4">
                
                <!-- Logo -->
                <a href="#" class="flex items-center gap-3 group shrink-0">
                    <div class="w-11 h-11 rounded-2xl bg-gradient-to-tr from-amber-700 to-amber-500 flex items-center justify-center text-white shadow-lg shadow-amber-600/20 group-hover:scale-105 transition-transform">
                        <i data-lucide="book-open" class="w-6 h-6"></i>
                    </div>
                    <div>
                        <span class="font-serif-heading font-bold text-xl sm:text-2xl text-amber-900 dark:text-amber-100 tracking-tight block">Hembrom Books</span>
                        <span class="text-[10px] uppercase tracking-widest text-amber-600 dark:text-amber-400 font-bold block -mt-1">हेम्ब्रम बुक्स • Literary Hub</span>
                    </div>
                </a>

                <!-- Nav Links Desktop -->
                <nav class="hidden lg:flex items-center space-x-6 text-sm font-medium text-slate-700 dark:text-slate-300">
                    <a href="#featured" class="hover:text-amber-600 dark:hover:text-amber-400 transition-colors">Featured Book</a>
                    <a href="#catalog" class="hover:text-amber-600 dark:hover:text-amber-400 transition-colors">Catalog</a>
                    <a href="#author-spotlight" class="hover:text-amber-600 dark:hover:text-amber-400 transition-colors flex items-center gap-1.5">
                        <span class="w-2 h-2 rounded-full bg-amber-500 animate-pulse"></span>
                        Joel Hembrom
                    </a>
                    <a href="#about" class="hover:text-amber-600 dark:hover:text-amber-400 transition-colors">About</a>
                </nav>

                <!-- Action Controls -->
                <div class="flex items-center gap-2 sm:gap-3">
                    
                    <!-- Admin Login/Manage Button -->
                    <button id="adminActionBtn" onclick="toggleAdminModal()" class="px-3 py-2 rounded-xl bg-amber-700 hover:bg-amber-800 text-white font-semibold text-xs shadow-md shadow-amber-700/20 transition-all flex items-center gap-1.5">
                        <i data-lucide="shield-check" class="w-4 h-4"></i>
                        <span id="adminActionBtnText" class="hidden sm:inline">Admin Login</span>
                    </button>

                    <!-- Search Input (Desktop) -->
                    <div class="relative hidden md:block w-44 lg:w-52">
                        <input type="text" id="searchInput" oninput="handleSearch(this.value)" placeholder="Search title, author..." 
                            class="w-full pl-8 pr-3 py-2 rounded-xl text-xs bg-amber-100/50 dark:bg-slate-800 border border-amber-200 dark:border-slate-700 focus:outline-none focus:ring-2 focus:ring-amber-500 text-slate-800 dark:text-slate-200">
                        <i data-lucide="search" class="w-3.5 h-3.5 absolute left-2.5 top-3 text-slate-400"></i>
                    </div>

                    <!-- Theme Toggle -->
                    <button id="themeToggle" onclick="toggleTheme()" class="p-2.5 rounded-xl bg-amber-100/60 dark:bg-slate-800 text-slate-700 dark:text-slate-300 hover:bg-amber-200/60 dark:hover:bg-slate-700 transition-all" title="Toggle Theme">
                        <i data-lucide="sun" id="sunIcon" class="w-5 h-5 hidden"></i>
                        <i data-lucide="moon" id="moonIcon" class="w-5 h-5"></i>
                    </button>

                    <!-- Wishlist Count Button -->
                    <button id="wishlistBtn" onclick="filterWishlistOnly()" class="relative p-2.5 rounded-xl bg-amber-100/60 dark:bg-slate-800 text-amber-800 dark:text-amber-300 hover:bg-amber-200 transition-all" title="View Wishlist">
                        <i data-lucide="heart" class="w-5 h-5"></i>
                        <span id="wishlistBadge" class="absolute -top-1 -right-1 bg-amber-600 text-white text-[10px] font-bold w-4 h-4 rounded-full flex items-center justify-center hidden">0</span>
                    </button>

                    <!-- Cart Button -->
                    <button id="cartBtn" onclick="openCartModal()" class="relative p-2.5 rounded-xl bg-slate-900 dark:bg-amber-600 text-white shadow-md transition-all flex items-center justify-center">
                        <i data-lucide="shopping-bag" class="w-5 h-5"></i>
                        <span id="cartBadge" class="absolute -top-1.5 -right-1.5 bg-red-500 text-white text-[10px] font-bold w-5 h-5 rounded-full flex items-center justify-center hidden">0</span>
                    </button>

                    <!-- Mobile Menu Button -->
                    <button id="mobileMenuBtn" onclick="toggleMobileNav()" class="lg:hidden p-2.5 rounded-xl bg-amber-100/60 dark:bg-slate-800 text-slate-700 dark:text-slate-300">
                        <i data-lucide="menu" class="w-5 h-5"></i>
                    </button>
                </div>
            </div>

            <!-- Mobile Search Bar -->
            <div class="md:hidden pb-3">
                <div class="relative w-full">
                    <input type="text" id="mobileSearchInput" oninput="handleSearch(this.value)" placeholder="Search title, author, category..." 
                        class="w-full pl-9 pr-4 py-2 rounded-xl text-xs bg-amber-100/50 dark:bg-slate-800 border border-amber-200 dark:border-slate-700 focus:outline-none focus:ring-2 focus:ring-amber-500">
                    <i data-lucide="search" class="w-4 h-4 absolute left-3 top-2.5 text-slate-400"></i>
                </div>
            </div>
        </div>

        <!-- Mobile Navigation Menu -->
        <div id="mobileNav" class="hidden lg:hidden border-t border-amber-200/50 dark:border-slate-800 bg-[#fdfbf7] dark:bg-slate-900 px-6 py-4 space-y-2">
            <a href="#featured" onclick="toggleMobileNav()" class="mobile-nav-link block text-sm font-medium py-1.5">Featured Book</a>
            <a href="#catalog" onclick="toggleMobileNav()" class="mobile-nav-link block text-sm font-medium py-1.5">Book Catalog</a>
            <a href="#author-spotlight" onclick="toggleMobileNav()" class="mobile-nav-link block text-sm font-medium py-1.5 text-amber-600 dark:text-amber-400">Joel Hembrom Spotlight</a>
            <a href="#about" onclick="toggleMobileNav()" class="mobile-nav-link block text-sm font-medium py-1.5">About Store</a>
        </div>
    </header>

    <main class="flex-grow">
        <!-- Hero Section featuring "Love is Part of Life" -->
        <section id="featured" class="relative py-12 md:py-20 overflow-hidden bg-gradient-to-b from-amber-100/50 via-amber-50/20 to-transparent dark:from-slate-900/80">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-10 items-center">
                    
                    <!-- Left Column: Book Info & Details -->
                    <div class="lg:col-span-7 space-y-6 text-center lg:text-left">
                        <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-amber-500/10 border border-amber-500/30 text-amber-800 dark:text-amber-300 text-xs font-semibold uppercase tracking-wider">
                            <i data-lucide="sparkles" class="w-4 h-4 text-amber-600"></i> Author's Spotlight • बेस्टसेलर
                        </div>

                        <h1 class="text-4xl sm:text-5xl font-bold text-slate-900 dark:text-white tracking-tight leading-tight font-serif-heading">
                            Love is Part of Life
                        </h1>

                        <p class="text-xs uppercase tracking-widest font-bold text-amber-700 dark:text-amber-400">
                            Written by <span class="text-slate-900 dark:text-white text-sm">Joel Hembrom (जोवेल हेम्ब्रम)</span>
                        </p>

                        <p class="text-sm sm:text-base text-slate-600 dark:text-slate-300 leading-relaxed max-w-2xl mx-auto lg:mx-0">
                            An inspiring and heart-touching exploration of modern relationships, emotional growth, and finding true passion through life's unexpected turns. A deep story that bridges logic, ambition, and unconditional heart.
                        </p>

                        <!-- Pricing Badge & Call to Action -->
                        <div class="flex flex-wrap items-center justify-center lg:justify-start gap-4 pt-2">
                            <div class="flex items-baseline gap-2">
                                <span class="text-3xl font-bold text-amber-700 dark:text-amber-400">₹299</span>
                                <span class="text-sm text-slate-400 line-through">₹399</span>
                                <span class="text-xs font-bold bg-green-100 text-green-800 dark:bg-green-900/40 dark:text-green-300 px-2 py-0.5 rounded">25% OFF</span>
                            </div>

                            <button onclick="addToCart('featured-1')" class="px-6 py-3 rounded-xl bg-amber-700 hover:bg-amber-800 text-white font-bold text-xs uppercase tracking-wider shadow-lg shadow-amber-700/25 transition-all flex items-center gap-2">
                                <i data-lucide="shopping-cart" class="w-4 h-4"></i> Add to Cart
                            </button>

                            <button onclick="openExcerptModal('featured-1')" class="px-6 py-3 rounded-xl bg-white dark:bg-slate-800 border border-slate-300 dark:border-slate-700 text-slate-800 dark:text-slate-200 hover:bg-slate-100 transition-all font-bold text-xs uppercase tracking-wider flex items-center gap-2">
                                <i data-lucide="book-open" class="w-4 h-4 text-amber-600"></i> Read Sample Excerpt
                            </button>
                        </div>

                        <!-- Highlights -->
                        <div class="pt-6 grid grid-cols-3 gap-2 border-t border-amber-200/60 dark:border-slate-800 text-[11px] text-slate-500 dark:text-slate-400">
                            <div class="flex items-center justify-center lg:justify-start gap-1.5">
                                <i data-lucide="check-circle" class="w-3.5 h-3.5 text-amber-600"></i> Paperback & E-Book
                            </div>
                            <div class="flex items-center justify-center lg:justify-start gap-1.5">
                                <i data-lucide="truck" class="w-3.5 h-3.5 text-amber-600"></i> Fast Delivery
                            </div>
                            <div class="flex items-center justify-center lg:justify-start gap-1.5">
                                <i data-lucide="star" class="w-3.5 h-3.5 text-amber-600"></i> Top Rated
                            </div>
                        </div>
                    </div>

                    <!-- Right Column: Styled Cover Card -->
                    <div class="lg:col-span-5 flex justify-center">
                        <div class="relative group max-w-xs sm:max-w-sm w-full">
                            <div class="absolute -inset-3 bg-gradient-to-r from-amber-600 via-amber-400 to-amber-700 rounded-3xl opacity-30 blur-xl group-hover:opacity-50 transition duration-500"></div>
                            
                            <div class="relative bg-gradient-to-br from-amber-900 via-amber-950 to-slate-950 rounded-2xl p-6 text-white shadow-2xl border border-amber-600/40 aspect-[3/4.2] flex flex-col justify-between overflow-hidden">
                                <div class="flex justify-between items-start">
                                    <span class="text-[9px] uppercase font-bold tracking-widest bg-amber-500/20 text-amber-300 px-2.5 py-1 rounded-full border border-amber-400/30">
                                        Bestseller
                                    </span>
                                    <span class="text-xs font-serif italic text-amber-200">Fiction / Life</span>
                                </div>

                                <div class="my-auto space-y-3 py-4 text-center">
                                    <h2 class="text-3xl font-serif-heading font-bold leading-tight text-white drop-shadow">Love is Part of Life</h2>
                                    <div class="w-12 h-0.5 bg-amber-500 mx-auto"></div>
                                    <p class="text-xs text-amber-200 italic font-serif">"Finding true passion through life's unexpected turns."</p>
                                </div>

                                <div class="pt-4 border-t border-amber-800/80 flex items-center justify-between text-xs">
                                    <div>
                                        <span class="text-[9px] uppercase text-amber-400 block">Author</span>
                                        <span class="font-bold text-white">Joel Hembrom</span>
                                    </div>
                                    <button onclick="addToCart('featured-1')" class="px-3 py-1.5 rounded bg-amber-500 hover:bg-amber-400 text-amber-950 font-bold text-xs flex items-center gap-1">
                                        <i data-lucide="shopping-bag" class="w-3.5 h-3.5"></i> Buy ₹299
                                    </button>
                                </div>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </section>

        <!-- Main Catalog Section with Filters -->
        <section id="catalog" class="py-12 bg-white dark:bg-slate-900/50 border-y border-amber-200/50 dark:border-slate-800">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                
                <div class="flex flex-col md:flex-row md:items-end justify-between mb-8 gap-4">
                    <div>
                        <span class="text-xs font-bold uppercase tracking-widest text-amber-600 dark:text-amber-400">Complete Collection</span>
                        <h2 class="text-2xl sm:text-3xl font-bold text-slate-900 dark:text-white font-serif-heading">Book Catalog (किताबें)</h2>
                    </div>

                    <!-- Category Pills -->
                    <div class="flex flex-wrap gap-2" id="categoryFilters">
                        <button onclick="filterCategory('all', this)" class="cat-pill active px-3.5 py-1.5 rounded-xl text-xs font-semibold bg-amber-700 text-white shadow-sm">All Books</button>
                        <button onclick="filterCategory('Romance & Life', this)" class="cat-pill px-3.5 py-1.5 rounded-xl text-xs font-semibold bg-amber-100 dark:bg-slate-800 text-slate-700 dark:text-slate-300 hover:bg-amber-200 dark:hover:bg-slate-700">Romance & Life</button>
                        <button onclick="filterCategory('Automotive & Tech', this)" class="cat-pill px-3.5 py-1.5 rounded-xl text-xs font-semibold bg-amber-100 dark:bg-slate-800 text-slate-700 dark:text-slate-300 hover:bg-amber-200 dark:hover:bg-slate-700">Automotive & Tech</button>
                        <button onclick="filterCategory('Santali Heritage', this)" class="cat-pill px-3.5 py-1.5 rounded-xl text-xs font-semibold bg-amber-100 dark:bg-slate-800 text-slate-700 dark:text-slate-300 hover:bg-amber-200 dark:hover:bg-slate-700">Santali Heritage</button>
                        <button onclick="filterCategory('Poetry & Literature', this)" class="cat-pill px-3.5 py-1.5 rounded-xl text-xs font-semibold bg-amber-100 dark:bg-slate-800 text-slate-700 dark:text-slate-300 hover:bg-amber-200 dark:hover:bg-slate-700">Poetry & Literature</button>
                        <button onclick="filterCategory('Educational', this)" class="cat-pill px-3.5 py-1.5 rounded-xl text-xs font-semibold bg-amber-100 dark:bg-slate-800 text-slate-700 dark:text-slate-300 hover:bg-amber-200 dark:hover:bg-slate-700">Educational</button>
                    </div>
                </div>

                <!-- Book Cards Grid -->
                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6" id="bookGrid">
                    <!-- Dynamic rendering handled by JS -->
                </div>

                <!-- Empty Search / Catalog Reset State -->
                <div id="noResults" class="hidden py-16 text-center space-y-4">
                    <i data-lucide="book-x" class="w-12 h-12 text-slate-400 mx-auto"></i>
                    <h3 class="text-base font-bold text-slate-700 dark:text-slate-300">No books found matching your criteria</h3>
                    <p class="text-xs text-slate-500">Try clearing search filters or selecting another category.</p>
                    <button onclick="resetFilters()" class="px-4 py-2 bg-amber-700 text-white rounded-xl text-xs font-semibold">Reset Filters</button>
                </div>
            </div>
        </section>

        <!-- Author Spotlight Section -->
        <section id="author-spotlight" class="py-16 bg-amber-900 text-amber-50 dark:bg-slate-900 dark:text-slate-100 border-b border-amber-800/50">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                    <div class="lg:col-span-4 flex justify-center">
                        <div class="w-48 h-48 sm:w-56 sm:h-56 rounded-full bg-gradient-to-tr from-amber-600 to-amber-400 p-1.5 shadow-2xl">
                            <div class="w-full h-full rounded-full bg-slate-900 flex flex-col items-center justify-center text-center p-6 border-2 border-amber-300/30">
                                <i data-lucide="user-check" class="w-12 h-12 text-amber-400 mb-2"></i>
                                <h3 class="font-bold text-lg text-white">Joel Hembrom</h3>
                                <p class="text-xs text-amber-300 italic font-serif">जोवेल हेम्ब्रम</p>
                                <span class="text-[10px] mt-2 px-2 py-0.5 rounded-full bg-amber-500/20 text-amber-200">Author & Engineer</span>
                            </div>
                        </div>
                    </div>
                    <div class="lg:col-span-8 space-y-4 text-center lg:text-left">
                        <span class="text-xs uppercase tracking-widest font-bold text-amber-400">About the Author</span>
                        <h2 class="text-3xl font-bold font-serif-heading text-white">Exploring Life, Technology & Literature</h2>
                        <p class="text-xs sm:text-sm text-amber-100/90 leading-relaxed">
                            Joel Hembrom weaves together personal reflections, cultural roots, and technical understanding. From modern fiction like <em>"Love is Part of Life"</em> to guides on mechanical concepts and Santali literature, his writings speak directly to readers looking for depth, clarity, and heart.
                        </p>
                        <div class="flex flex-wrap gap-4 pt-2 justify-center lg:justify-start text-xs text-amber-200 font-semibold">
                            <div class="flex items-center gap-1.5"><i data-lucide="feather" class="w-4 h-4 text-amber-400"></i> Storyteller & Poet</div>
                            <div class="flex items-center gap-1.5"><i data-lucide="wrench" class="w-4 h-4 text-amber-400"></i> Automotive Craftsman</div>
                            <div class="flex items-center gap-1.5"><i data-lucide="heart" class="w-4 h-4 text-amber-400"></i> Passionate Creator</div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- About Store Section -->
        <section id="about" class="py-12 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="bg-amber-100/40 dark:bg-slate-800/40 border border-amber-200/70 dark:border-slate-700/60 rounded-3xl p-8 sm:p-10 text-center space-y-4">
                <i data-lucide="book-open-check" class="w-10 h-10 text-amber-700 dark:text-amber-400 mx-auto"></i>
                <h2 class="text-2xl font-bold font-serif-heading text-slate-900 dark:text-white">Welcome to Hembrom Books</h2>
                <p class="text-xs sm:text-sm text-slate-600 dark:text-slate-300 max-w-2xl mx-auto leading-relaxed">
                    Hembrom Books (हेम्ब्रम बुक्स) is an independent publishing and online book store committed to bringing inspiring original titles, technical references, and cultural literature closer to readers across India.
                </p>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-slate-950 text-slate-400 text-xs py-8 border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col sm:flex-row items-center justify-between gap-4 text-center sm:text-left">
            <div>
                <p class="font-bold text-white text-sm">Hembrom Books • हेम्ब्रम बुक्स</p>
                <p class="text-[11px] text-slate-500 mt-0.5">© 2026 Hembrom Books. Built for Readers & Thinkers.</p>
            </div>
            <div class="flex gap-4 text-slate-400">
                <a href="#featured" class="hover:text-amber-400">Featured</a>
                <a href="#catalog" class="hover:text-amber-400">Catalog</a>
                <a href="#author-spotlight" class="hover:text-amber-400">Author Spotlight</a>
            </div>
        </div>
    </footer>

    <!-- Cart Modal -->
    <div id="cartModal" class="fixed inset-0 bg-slate-950/60 backdrop-blur-sm z-50 flex justify-end hidden">
        <div class="w-full max-w-md bg-white dark:bg-slate-900 h-full shadow-2xl flex flex-col justify-between p-6 overflow-y-auto">
            <div>
                <div class="flex items-center justify-between pb-4 border-b border-slate-200 dark:border-slate-800">
                    <h3 class="font-serif-heading font-bold text-lg text-slate-900 dark:text-white flex items-center gap-2">
                        <i data-lucide="shopping-bag" class="w-5 h-5 text-amber-600"></i> Your Cart
                    </h3>
                    <button onclick="closeCartModal()" class="p-1 rounded-lg hover:bg-slate-100 dark:hover:bg-slate-800 text-slate-500">
                        <i data-lucide="x" class="w-5 h-5"></i>
                    </button>
                </div>
                <div id="cartItemsList" class="py-4 space-y-4">
                    <!-- Rendered by JS -->
                </div>
            </div>

            <div class="pt-4 border-t border-slate-200 dark:border-slate-800 space-y-4">
                <div class="flex justify-between items-center text-sm font-bold">
                    <span class="text-slate-600 dark:text-slate-400">Total Amount:</span>
                    <span id="cartTotalPrice" class="text-xl text-amber-700 dark:text-amber-400">₹0</span>
                </div>
                <button onclick="openCheckoutModal()" id="checkoutBtn" class="w-full py-3 bg-amber-700 hover:bg-amber-800 text-white font-bold rounded-xl text-xs uppercase tracking-wider flex items-center justify-center gap-2">
                    Proceed to Checkout <i data-lucide="arrow-right" class="w-4 h-4"></i>
                </button>
            </div>
        </div>
    </div>

    <!-- Checkout Modal -->
    <div id="checkoutModal" class="fixed inset-0 bg-slate-950/60 backdrop-blur-sm z-50 flex items-center justify-center p-4 hidden">
        <div class="bg-white dark:bg-slate-900 w-full max-w-lg rounded-2xl p-6 shadow-2xl border border-amber-200/50 dark:border-slate-800 max-h-[90vh] overflow-y-auto">
            <div class="flex justify-between items-center pb-4 border-b border-slate-200 dark:border-slate-800">
                <h3 class="font-serif-heading font-bold text-lg text-slate-900 dark:text-white">Shipping & Payment Details</h3>
                <button onclick="closeCheckoutModal()" class="text-slate-400 hover:text-slate-600"><i data-lucide="x" class="w-5 h-5"></i></button>
            </div>
            <form id="checkoutForm" onsubmit="handlePlaceOrder(event)" class="space-y-4 py-4">
                <div>
                    <label class="block text-xs font-semibold mb-1">Full Name</label>
                    <input type="text" required class="w-full px-3 py-2 text-xs rounded-xl border border-slate-300 dark:border-slate-700 bg-slate-50 dark:bg-slate-800 focus:outline-none focus:ring-2 focus:ring-amber-500">
                </div>
                <div>
                    <label class="block text-xs font-semibold mb-1">Mobile Number</label>
                    <input type="tel" required class="w-full px-3 py-2 text-xs rounded-xl border border-slate-300 dark:border-slate-700 bg-slate-50 dark:bg-slate-800 focus:outline-none focus:ring-2 focus:ring-amber-500">
                </div>
                <div>
                    <label class="block text-xs font-semibold mb-1">Delivery Address</label>
                    <textarea required rows="2" class="w-full px-3 py-2 text-xs rounded-xl border border-slate-300 dark:border-slate-700 bg-slate-50 dark:bg-slate-800 focus:outline-none focus:ring-2 focus:ring-amber-500"></textarea>
                </div>
                <div>
                    <label class="block text-xs font-semibold mb-1">Payment Method</label>
                    <select id="paymentMethod" onchange="toggleUPIRef()" class="w-full px-3 py-2 text-xs rounded-xl border border-slate-300 dark:border-slate-700 bg-slate-50 dark:bg-slate-800 focus:outline-none focus:ring-2 focus:ring-amber-500">
                        <option value="cod">Cash on Delivery (COD)</option>
                        <option value="upi">UPI / Online Payment (Google Pay, PhonePe, Paytm)</option>
                    </select>
                </div>
                <div id="upiInfoBox" class="hidden p-3 bg-amber-50 dark:bg-amber-950/40 border border-amber-300 rounded-xl space-y-2 text-xs">
                    <p class="font-bold text-amber-900 dark:text-amber-200">Pay via UPI ID: <span class="font-mono text-amber-700 dark:text-amber-400">hembrom@upi</span></p>
                    <p class="text-slate-600 dark:text-slate-400">Enter transaction reference number after paying:</p>
                    <input type="text" id="upiRefInput" placeholder="Transaction Ref ID / UTR" class="w-full px-3 py-1.5 text-xs rounded-lg border border-slate-300 dark:border-slate-700">
                </div>
                <button type="submit" class="w-full py-3 bg-amber-700 hover:bg-amber-800 text-white font-bold rounded-xl text-xs uppercase tracking-wider">
                    Confirm Order
                </button>
            </form>
        </div>
    </div>

    <!-- Admin Login Modal -->
    <div id="adminModal" class="fixed inset-0 bg-slate-950/60 backdrop-blur-sm z-50 flex items-center justify-center p-4 hidden">
        <div class="bg-white dark:bg-slate-900 w-full max-w-md rounded-2xl p-6 shadow-2xl border border-amber-200/50 dark:border-slate-800">
            <div class="flex justify-between items-center pb-3 border-b border-slate-200 dark:border-slate-800">
                <h3 class="font-serif-heading font-bold text-base text-slate-900 dark:text-white flex items-center gap-2">
                    <i data-lucide="shield-check" class="w-5 h-5 text-amber-600"></i> Admin Access
                </h3>
                <button onclick="toggleAdminModal()" class="text-slate-400 hover:text-slate-600"><i data-lucide="x" class="w-5 h-5"></i></button>
            </div>
            <form onsubmit="handleAdminLogin(event)" class="space-y-4 py-4">
                <div>
                    <label class="block text-xs font-semibold mb-1">Admin Email</label>
                    <input type="email" id="adminEmailInput" value="5635hembrom@gmail.com" required class="w-full px-3 py-2 text-xs rounded-xl border border-slate-300 dark:border-slate-700 bg-slate-50 dark:bg-slate-800 focus:outline-none focus:ring-2 focus:ring-amber-500">
                </div>
                <div>
                    <label class="block text-xs font-semibold mb-1">Passcode</label>
                    <input type="password" id="adminPasswordInput" placeholder="Enter passcode (default: 1234)" required class="w-full px-3 py-2 text-xs rounded-xl border border-slate-300 dark:border-slate-700 bg-slate-50 dark:bg-slate-800 focus:outline-none focus:ring-2 focus:ring-amber-500">
                </div>
                <button type="submit" class="w-full py-2.5 bg-amber-700 hover:bg-amber-800 text-white font-bold rounded-xl text-xs uppercase tracking-wider">
                    Log In
                </button>
            </form>
        </div>
    </div>

    <!-- Add/Edit Book Modal (Admin Only) -->
    <div id="addBookModal" class="fixed inset-0 bg-slate-950/60 backdrop-blur-sm z-50 flex items-center justify-center p-4 hidden">
        <div class="bg-white dark:bg-slate-900 w-full max-w-md rounded-2xl p-6 shadow-2xl border border-amber-200/50 dark:border-slate-800 max-h-[90vh] overflow-y-auto">
            <div class="flex justify-between items-center pb-3 border-b border-slate-200 dark:border-slate-800">
                <h3 class="font-serif-heading font-bold text-base text-slate-900 dark:text-white" id="bookModalTitle">Add New Book</h3>
                <button onclick="closeAddBookModal()" class="text-slate-400 hover:text-slate-600"><i data-lucide="x" class="w-5 h-5"></i></button>
            </div>
            <form onsubmit="handleSaveBook(event)" class="space-y-3 py-4 text-xs">
                <input type="hidden" id="editBookId">
                <div>
                    <label class="block font-semibold mb-1">Book Title</label>
                    <input type="text" id="bookTitleInput" required class="w-full px-3 py-2 rounded-xl border border-slate-300 dark:border-slate-700 bg-slate-50 dark:bg-slate-800">
                </div>
                <div>
                    <label class="block font-semibold mb-1">Author Name</label>
                    <input type="text" id="bookAuthorInput" required class="w-full px-3 py-2 rounded-xl border border-slate-300 dark:border-slate-700 bg-slate-50 dark:bg-slate-800">
                </div>
                <div class="grid grid-cols-2 gap-2">
                    <div>
                        <label class="block font-semibold mb-1">Price (₹)</label>
                        <input type="number" id="bookPriceInput" required class="w-full px-3 py-2 rounded-xl border border-slate-300 dark:border-slate-700 bg-slate-50 dark:bg-slate-800">
                    </div>
                    <div>
                        <label class="block font-semibold mb-1">Original Price (₹)</label>
                        <input type="number" id="bookOrigPriceInput" class="w-full px-3 py-2 rounded-xl border border-slate-300 dark:border-slate-700 bg-slate-50 dark:bg-slate-800">
                    </div>
                </div>
                <div>
                    <label class="block font-semibold mb-1">Category</label>
                    <select id="bookCategoryInput" class="w-full px-3 py-2 rounded-xl border border-slate-300 dark:border-slate-700 bg-slate-50 dark:bg-slate-800">
                        <option value="Romance & Life">Romance & Life</option>
                        <option value="Automotive & Tech">Automotive & Tech</option>
                        <option value="Santali Heritage">Santali Heritage</option>
                        <option value="Poetry & Literature">Poetry & Literature</option>
                        <option value="Educational">Educational</option>
                    </select>
                </div>
                <div>
                    <label class="block font-semibold mb-1">Short Description</label>
                    <textarea id="bookDescInput" rows="2" class="w-full px-3 py-2 rounded-xl border border-slate-300 dark:border-slate-700 bg-slate-50 dark:bg-slate-800"></textarea>
                </div>
                <div>
                    <label class="block font-semibold mb-1">Sample Excerpt</label>
                    <textarea id="bookExcerptInput" rows="3" class="w-full px-3 py-2 rounded-xl border border-slate-300 dark:border-slate-700 bg-slate-50 dark:bg-slate-800"></textarea>
                </div>
                <button type="submit" class="w-full py-2.5 bg-amber-700 hover:bg-amber-800 text-white font-bold rounded-xl uppercase tracking-wider text-xs">
                    Save Book to Catalog
                </button>
            </form>
        </div>
    </div>

    <!-- Excerpt Reader Modal -->
    <div id="excerptModal" class="fixed inset-0 bg-slate-950/60 backdrop-blur-sm z-50 flex items-center justify-center p-4 hidden">
        <div class="bg-white dark:bg-slate-900 w-full max-w-xl rounded-2xl p-6 sm:p-8 shadow-2xl border border-amber-200/50 dark:border-slate-800 max-h-[85vh] overflow-y-auto">
            <div class="flex justify-between items-start pb-4 border-b border-slate-200 dark:border-slate-800">
                <div>
                    <span class="text-[10px] uppercase font-bold text-amber-600 dark:text-amber-400">Sample Preview</span>
                    <h3 id="excerptTitle" class="font-serif-heading font-bold text-xl text-slate-900 dark:text-white">Love is Part of Life</h3>
                    <p id="excerptAuthor" class="text-xs text-slate-500 dark:text-slate-400">By Joel Hembrom</p>
                </div>
                <button onclick="closeExcerptModal()" class="text-slate-400 hover:text-slate-600"><i data-lucide="x" class="w-5 h-5"></i></button>
            </div>
            <div id="excerptText" class="py-6 font-serif leading-relaxed text-sm text-slate-700 dark:text-slate-300 whitespace-pre-line border-b border-slate-100 dark:border-slate-800">
                <!-- Excerpt text rendered dynamically -->
            </div>
            <div class="pt-4 flex justify-end gap-3">
                <button onclick="closeExcerptModal()" class="px-4 py-2 rounded-xl border border-slate-300 dark:border-slate-700 text-xs font-semibold">Close</button>
                <button id="excerptBuyBtn" class="px-5 py-2 bg-amber-700 text-white rounded-xl text-xs font-semibold flex items-center gap-1.5">
                    <i data-lucide="shopping-bag" class="w-4 h-4"></i> Add to Cart
                </button>
            </div>
        </div>
    </div>

    <!-- JavaScript Application Logic -->
    <script>
        // Initial Book State
        const defaultBooks = [
            {
                id: 'featured-1',
                title: 'Love is Part of Life',
                author: 'Joel Hembrom (जोवेल हेम्ब्रम)',
                price: 299,
                origPrice: 399,
                category: 'Romance & Life',
                tag: 'Bestseller',
                desc: 'An inspiring and heart-touching exploration of modern relationships, emotional growth, and finding true passion.',
                excerpt: `"Love is not merely an emotion we experience when circumstances are simple; it is the fundamental force that guides us through our hardest transitions. In every choice, in every moment of quiet decision, love shapes who we become."\n\n— Excerpt from Chapter 1: The First Step by Joel Hembrom`
            },
            {
                id: 'book-2',
                title: 'Automotive Mechanics & Systems Guide',
                author: 'Joel Hembrom',
                price: 450,
                origPrice: 550,
                category: 'Automotive & Tech',
                tag: 'Technical Guide',
                desc: 'A complete handbook on engine mechanisms, backlash tuning, and modern BS4 to BS6 systems.',
                excerpt: `"Precision backlash adjustments ensure long gear life and minimal noise operational tolerance. Understanding the thermal expansion of gear meshes is essential..."`
            },
            {
                id: 'book-3',
                title: 'Santali Heritage & Folk Traditions',
                author: 'Joel Hembrom',
                price: 350,
                origPrice: 420,
                category: 'Santali Heritage',
                tag: 'Cultural History',
                desc: 'A rich compilation celebrating traditional music, instruments like the Madal & Tiriyo, and stories.',
                excerpt: `"The rhythm of the Madal echo across the evening hills, bringing people together in unity and rhythmic expression..."`
            },
            {
                id: 'book-4',
                title: 'Poems of Heart and Purpose',
                author: 'Joel Hembrom',
                price: 199,
                origPrice: 250,
                category: 'Poetry & Literature',
                tag: 'Poetry',
                desc: 'Expressive Hindi and English poetry dedicated to friendship, journey, and inner resilience.',
                excerpt: `"सपनों की दिशा में कदम बढ़ाना,\nहर मुश्किल राह को आसान बनाना,\nदिल में सच्चाई और आँखों में विश्वास..."`
            }
        ];

        let books = JSON.parse(localStorage.getItem('hembrom_books')) || defaultBooks;
        let cart = JSON.parse(localStorage.getItem('hembrom_cart')) || [];
        let wishlist = JSON.parse(localStorage.getItem('hembrom_wishlist')) || [];
        let isAdmin = localStorage.getItem('hembrom_admin') === 'true';
        let activeCategory = 'all';
        let searchQuery = '';
        let showingWishlistOnly = false;

        // Initialize App
        document.addEventListener('DOMContentLoaded', () => {
            renderCatalog();
            updateCartBadge();
            updateWishlistBadge();
            checkAdminStatus();
            lucide.createIcons();
        });

        // Save State Helpers
        function saveBooks() { localStorage.setItem('hembrom_books', JSON.stringify(books)); }
        function saveCart() { localStorage.setItem('hembrom_cart', JSON.stringify(cart)); updateCartBadge(); }
        function saveWishlist() { localStorage.setItem('hembrom_wishlist', JSON.stringify(wishlist)); updateWishlistBadge(); }

        // Render Catalog Function
        function renderCatalog() {
            const grid = document.getElementById('bookGrid');
            const noRes = document.getElementById('noResults');
            grid.innerHTML = '';

            let filtered = books.filter(book => {
                const matchCat = activeCategory === 'all' || book.category === activeCategory;
                const matchSearch = book.title.toLowerCase().includes(searchQuery.toLowerCase()) || 
                                    book.author.toLowerCase().includes(searchQuery.toLowerCase()) ||
                                    book.category.toLowerCase().includes(searchQuery.toLowerCase());
                const matchWish = showingWishlistOnly ? wishlist.includes(book.id) : true;
                return matchCat && matchSearch && matchWish;
            });

            if (filtered.length === 0) {
                grid.classList.add('hidden');
                noRes.classList.remove('hidden');
                return;
            }

            grid.classList.remove('hidden');
            noRes.classList.add('hidden');

            filtered.forEach(book => {
                const isWish = wishlist.includes(book.id);
                const card = document.createElement('div');
                card.className = "bg-amber-50/40 dark:bg-slate-800/60 rounded-2xl border border-amber-200/60 dark:border-slate-700/60 p-5 flex flex-col justify-between hover:shadow-xl transition-all relative group";

                card.innerHTML = `
                    <div>
                        <div class="flex justify-between items-start mb-3">
                            <span class="text-[10px] font-bold uppercase tracking-wider bg-amber-200/60 dark:bg-amber-900/40 text-amber-900 dark:text-amber-300 px-2 py-0.5 rounded-full">
                                ${book.tag || book.category}
                            </span>
                            <button onclick="toggleWishlist('${book.id}')" class="text-slate-400 hover:text-red-500 transition-colors">
                                <i data-lucide="heart" class="w-4 h-4 ${isWish ? 'fill-red-500 text-red-500' : ''}"></i>
                            </button>
                        </div>
                        <h3 class="font-serif-heading font-bold text-slate-900 dark:text-white text-base leading-snug mb-1">${book.title}</h3>
                        <p class="text-xs text-amber-700 dark:text-amber-400 font-semibold mb-2">By ${book.author}</p>
                        <p class="text-xs text-slate-600 dark:text-slate-300 line-clamp-2 mb-4">${book.desc || ''}</p>
                    </div>

                    <div>
                        <div class="flex items-baseline gap-2 mb-3">
                            <span class="text-lg font-bold text-slate-900 dark:text-white">₹${book.price}</span>
                            ${book.origPrice ? `<span class="text-xs text-slate-400 line-through">₹${book.origPrice}</span>` : ''}
                        </div>
                        
                        <div class="grid ${isAdmin ? 'grid-cols-3' : 'grid-cols-2'} gap-1.5">
                            <button onclick="openExcerptModal('${book.id}')" class="py-2 bg-amber-100 dark:bg-slate-700 text-amber-900 dark:text-amber-200 rounded-xl text-[11px] font-bold hover:bg-amber-200 text-center">Excerpt</button>
                            <button onclick="addToCart('${book.id}')" class="py-2 bg-amber-700 hover:bg-amber-800 text-white rounded-xl text-[11px] font-bold flex items-center justify-center gap-1">
                                <i data-lucide="shopping-cart" class="w-3.5 h-3.5"></i> Add
                            </button>
                            ${isAdmin ? `<button onclick="editBook('${book.id}')" class="py-2 bg-slate-900 text-amber-400 rounded-xl text-[11px] font-bold">Edit</button>` : ''}
                        </div>
                    </div>
                `;
                grid.appendChild(card);
            });
            lucide.createIcons();
        }

        // Search & Category Filters
        function handleSearch(val) {
            searchQuery = val;
            showingWishlistOnly = false;
            renderCatalog();
        }

        function filterCategory(cat, btn) {
            activeCategory = cat;
            showingWishlistOnly = false;
            document.querySelectorAll('.cat-pill').forEach(b => {
                b.className = "cat-pill px-3.5 py-1.5 rounded-xl text-xs font-semibold bg-amber-100 dark:bg-slate-800 text-slate-700 dark:text-slate-300 hover:bg-amber-200 dark:hover:bg-slate-700";
            });
            btn.className = "cat-pill active px-3.5 py-1.5 rounded-xl text-xs font-semibold bg-amber-700 text-white shadow-sm";
            renderCatalog();
        }

        function filterWishlistOnly() {
            showingWishlistOnly = !showingWishlistOnly;
            if (showingWishlistOnly) showToast("Filtering Wishlist Items");
            renderCatalog();
        }

        function resetFilters() {
            activeCategory = 'all';
            searchQuery = '';
            showingWishlistOnly = false;
            document.getElementById('searchInput').value = '';
            document.getElementById('mobileSearchInput').value = '';
            renderCatalog();
        }

        // Cart Actions
        function addToCart(id) {
            const item = books.find(b => b.id === id);
            if (!item) return;
            const existing = cart.find(c => c.id === id);
            if (existing) {
                existing.qty += 1;
            } else {
                cart.push({ id: item.id, title: item.title, price: item.price, qty: 1 });
            }
            saveCart();
            showToast(`Added "${item.title}" to cart`);
        }

        function updateCartBadge() {
            const totalQty = cart.reduce((acc, i) => acc + i.qty, 0);
            const badge = document.getElementById('cartBadge');
            if (totalQty > 0) {
                badge.innerText = totalQty;
                badge.classList.remove('hidden');
            } else {
                badge.classList.add('hidden');
            }
        }

        function openCartModal() {
            renderCartList();
            document.getElementById('cartModal').classList.remove('hidden');
        }

        function closeCartModal() {
            document.getElementById('cartModal').classList.add('hidden');
        }

        function renderCartList() {
            const container = document.getElementById('cartItemsList');
            const totalEl = document.getElementById('cartTotalPrice');
            container.innerHTML = '';

            if (cart.length === 0) {
                container.innerHTML = `<p class="text-xs text-slate-500 text-center py-8">Your cart is empty.</p>`;
                totalEl.innerText = `₹0`;
                return;
            }

            let total = 0;
            cart.forEach(item => {
                total += item.price * item.qty;
                const row = document.createElement('div');
                row.className = "flex items-center justify-between gap-3 text-xs p-2 bg-slate-50 dark:bg-slate-800/50 rounded-xl";
                row.innerHTML = `
                    <div class="flex-grow">
                        <p class="font-bold text-slate-900 dark:text-white">${item.title}</p>
                        <p class="text-slate-500">₹${item.price} x ${item.qty}</p>
                    </div>
                    <div class="flex items-center gap-2">
                        <button onclick="changeQty('${item.id}', -1)" class="w-6 h-6 rounded bg-slate-200 dark:bg-slate-700 font-bold">-</button>
                        <span>${item.qty}</span>
                        <button onclick="changeQty('${item.id}', 1)" class="w-6 h-6 rounded bg-slate-200 dark:bg-slate-700 font-bold">+</button>
                    </div>
                `;
                container.appendChild(row);
            });
            totalEl.innerText = `₹${total}`;
        }

        function changeQty(id, delta) {
            const item = cart.find(c => c.id === id);
            if (!item) return;
            item.qty += delta;
            if (item.qty <= 0) {
                cart = cart.filter(c => c.id !== id);
            }
            saveCart();
            renderCartList();
        }

        // Checkout Modal & Logic
        function openCheckoutModal() {
            if (cart.length === 0) return showToast("Cart is empty!");
            closeCartModal();
            document.getElementById('checkoutModal').classList.remove('hidden');
        }

        function closeCheckoutModal() {
            document.getElementById('checkoutModal').classList.add('hidden');
        }

        function toggleUPIRef() {
            const method = document.getElementById('paymentMethod').value;
            const box = document.getElementById('upiInfoBox');
            if (method === 'upi') box.classList.remove('hidden');
            else box.classList.add('hidden');
        }

        function handlePlaceOrder(e) {
            e.preventDefault();
            showToast("Order placed successfully! Thank you.");
            cart = [];
            saveCart();
            closeCheckoutModal();
        }

        // Wishlist System
        function toggleWishlist(id) {
            if (wishlist.includes(id)) {
                wishlist = wishlist.filter(w => w !== id);
                showToast("Removed from Wishlist");
            } else {
                wishlist.push(id);
                showToast("Added to Wishlist");
            }
            saveWishlist();
            renderCatalog();
        }

        function updateWishlistBadge() {
            const badge = document.getElementById('wishlistBadge');
            if (wishlist.length > 0) {
                badge.innerText = wishlist.length;
                badge.classList.remove('hidden');
            } else {
                badge.classList.add('hidden');
            }
        }

        // Excerpt Modal
        function openExcerptModal(id) {
            const book = books.find(b => b.id === id);
            if (!book) return;
            document.getElementById('excerptTitle').innerText = book.title;
            document.getElementById('excerptAuthor').innerText = `By ${book.author}`;
            document.getElementById('excerptText').innerText = book.excerpt || "Excerpt preview coming soon.";
            document.getElementById('excerptBuyBtn').onclick = () => { addToCart(book.id); closeExcerptModal(); };
            document.getElementById('excerptModal').classList.remove('hidden');
        }

        function closeExcerptModal() {
            document.getElementById('excerptModal').classList.add('hidden');
        }

        // Admin Management
        function checkAdminStatus() {
            const banner = document.getElementById('adminTopBanner');
            const btnText = document.getElementById('adminActionBtnText');
            if (isAdmin) {
                banner.classList.remove('hidden');
                btnText.innerText = 'Admin Active';
            } else {
                banner.classList.add('hidden');
                btnText.innerText = 'Admin Login';
            }
        }

        function toggleAdminModal() {
            if (isAdmin) {
                openAddBookModal();
            } else {
                document.getElementById('adminModal').classList.remove('hidden');
            }
        }

        function handleAdminLogin(e) {
            e.preventDefault();
            const pass = document.getElementById('adminPasswordInput').value;
            if (pass === '1234' || pass === 'admin') {
                isAdmin = true;
                localStorage.setItem('hembrom_admin', 'true');
                checkAdminStatus();
                document.getElementById('adminModal').classList.add('hidden');
                showToast("Logged in as Admin");
                renderCatalog();
            } else {
                showToast("Invalid passcode! Try '1234'");
            }
        }

        function adminLogout() {
            isAdmin = false;
            localStorage.setItem('hembrom_admin', 'false');
            checkAdminStatus();
            showToast("Logged out from Admin");
            renderCatalog();
        }

        function openAddBookModal() {
            document.getElementById('bookModalTitle').innerText = "Add New Book";
            document.getElementById('editBookId').value = "";
            document.getElementById('bookTitleInput').value = "";
            document.getElementById('bookAuthorInput').value = "Joel Hembrom";
            document.getElementById('bookPriceInput').value = "";
            document.getElementById('bookOrigPriceInput').value = "";
            document.getElementById('bookDescInput').value = "";
            document.getElementById('bookExcerptInput').value = "";
            document.getElementById('addBookModal').classList.remove('hidden');
        }

        function closeAddBookModal() {
            document.getElementById('addBookModal').classList.add('hidden');
        }

        function editBook(id) {
            const book = books.find(b => b.id === id);
            if (!book) return;
            document.getElementById('bookModalTitle').innerText = "Edit Book";
            document.getElementById('editBookId').value = book.id;
            document.getElementById('bookTitleInput').value = book.title;
            document.getElementById('bookAuthorInput').value = book.author;
            document.getElementById('bookPriceInput').value = book.price;
            document.getElementById('bookOrigPriceInput').value = book.origPrice || '';
            document.getElementById('bookCategoryInput').value = book.category;
            document.getElementById('bookDescInput').value = book.desc || '';
            document.getElementById('bookExcerptInput').value = book.excerpt || '';
            document.getElementById('addBookModal').classList.remove('hidden');
        }

        function handleSaveBook(e) {
            e.preventDefault();
            const id = document.getElementById('editBookId').value;
            const title = document.getElementById('bookTitleInput').value;
            const author = document.getElementById('bookAuthorInput').value;
            const price = parseFloat(document.getElementById('bookPriceInput').value);
            const origPrice = parseFloat(document.getElementById('bookOrigPriceInput').value) || null;
            const category = document.getElementById('bookCategoryInput').value;
            const desc = document.getElementById('bookDescInput').value;
            const excerpt = document.getElementById('bookExcerptInput').value;

            if (id) {
                const book = books.find(b => b.id === id);
                if (book) {
                    book.title = title;
                    book.author = author;
                    book.price = price;
                    book.origPrice = origPrice;
                    book.category = category;
                    book.desc = desc;
                    book.excerpt = excerpt;
                }
            } else {
                books.push({
                    id: 'book-' + Date.now(),
                    title, author, price, origPrice, category, desc, excerpt,
                    tag: 'New'
                });
            }
            saveBooks();
            renderCatalog();
            closeAddBookModal();
            showToast("Book saved successfully!");
        }

        // Theme Toggle Functionality
        function toggleTheme() {
            const html = document.documentElement;
            const sun = document.getElementById('sunIcon');
            const moon = document.getElementById('moonIcon');
            if (html.classList.contains('dark')) {
                html.classList.remove('dark');
                sun.classList.add('hidden');
                moon.classList.remove('hidden');
            } else {
                html.classList.add('dark');
                moon.classList.add('hidden');
                sun.classList.remove('hidden');
            }
        }

        // Mobile Nav Toggle
        function toggleMobileNav() {
            const nav = document.getElementById('mobileNav');
            nav.classList.toggle('hidden');
        }

        // Toast Helper
        function showToast(msg) {
            const container = document.getElementById('toastContainer');
            const toast = document.createElement('div');
            toast.className = "bg-slate-900 text-white dark:bg-amber-600 px-4 py-2.5 rounded-xl text-xs font-semibold shadow-xl toast-animate flex items-center gap-2 pointer-events-auto";
            toast.innerHTML = `<i data-lucide="info" class="w-4 h-4 text-amber-400 dark:text-amber-100"></i> ${msg}`;
            container.appendChild(toast);
            lucide.createIcons();
            setTimeout(() => toast.remove(), 3000);
        }
    </script>
</body>
</html>
