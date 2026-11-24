<!DOCTYPE html>
<html lang="fr" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Envol Travel | Agence de Voyage Agréée à Bir Mourad Raïs, Alger — Billetterie, Omra, Visa & Séjours</title>
    <meta name="description" content="Envol Travel, agence de voyage agréée située à Cité les vergers Bt 46, Bir Mourad Raïs, Alger. Billetterie aérienne, voyages organisés en DZD, Omra & Hajj et assistance Visa.">
    
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Lucide Icons -->
    <script src="https://unpkg.com/lucide@latest"></script>

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['"Plus Jakarta Sans"', 'sans-serif'],
                    },
                    colors: {
                        navy: {
                            800: '#132743',
                            900: '#0B192C',
                            950: '#060F1C',
                        },
                        brand: {
                            orange: '#EA580C',
                            amber: '#F59E0B',
                            gold: '#FBBF24',
                            blue: '#1D4ED8',
                            sky: '#0284C7',
                        }
                    }
                }
            }
        }
    </script>

    <style>
        .logo-gradient-text {
            background: linear-gradient(135deg, #EA580C 0%, #F97316 55%, #FBBF24 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .btn-solar {
            background: linear-gradient(135deg, #EA580C 0%, #F59E0B 100%);
            transition: all 0.25s ease;
        }
        .btn-solar:hover {
            background: linear-gradient(135deg, #C2410C 0%, #D97706 100%);
            transform: translateY(-2px);
            box-shadow: 0 12px 25px -5px rgba(234, 88, 12, 0.45);
        }
        .btn-royal {
            background: linear-gradient(135deg, #1D4ED8 0%, #0284C7 100%);
            transition: all 0.25s ease;
        }
        .btn-royal:hover {
            background: linear-gradient(135deg, #1E40AF 0%, #0369A1 100%);
            transform: translateY(-2px);
            box-shadow: 0 12px 25px -5px rgba(29, 78, 216, 0.35);
        }
        .glass-dark {
            background: rgba(11, 25, 44, 0.88);
            backdrop-filter: blur(14px);
            -webkit-backdrop-filter: blur(14px);
        }
        .card-hover {
            transition: transform 0.3s cubic-bezier(0.22, 1, 0.36, 1), box-shadow 0.3s ease;
        }
        .card-hover:hover {
            transform: translateY(-6px);
            box-shadow: 0 22px 45px -12px rgba(11, 25, 44, 0.15);
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased selection:bg-orange-500 selection:text-white">

    <!-- Top Info Bar -->
    <div class="bg-navy-950 text-slate-300 text-xs py-2.5 px-4 border-b border-white/10">
        <div class="max-w-7xl mx-auto flex flex-wrap justify-between items-center gap-2">
            <div class="flex flex-wrap items-center gap-4">
                <a href="https://maps.app.goo.gl/v4kpj6zxQAFnYjrq7?g_st=ic" target="_blank" rel="noopener noreferrer" class="flex items-center gap-1.5 text-slate-200 hover:text-amber-400 transition">
                    <i data-lucide="map-pin" class="w-3.5 h-3.5 text-amber-400 shrink-0"></i>
                    <span>Cité les vergers Bt 46, Bir Mourad Raïs, Alger</span>
                </a>
                <a href="mailto:envoltravel@gmail.com" class="hidden md:flex items-center gap-1.5 hover:text-amber-400 transition">
                    <i data-lucide="mail" class="w-3.5 h-3.5 text-amber-400"></i>
                    <span>envoltravel@gmail.com</span>
                </a>
                <span class="hidden lg:inline-flex items-center gap-1.5 bg-white/10 text-amber-300 px-2.5 py-0.5 rounded-full font-semibold">
                    <i data-lucide="shield-check" class="w-3.5 h-3.5"></i> Agence de Voyage Agréée
                </span>
            </div>
            <div class="flex items-center gap-4">
                <span class="hidden sm:inline text-slate-400">Dim – Jeu : 10h00–18h00 | Sam : 14h00–18h00</span>
                <a href="tel:+213781000046" class="font-bold text-amber-400 hover:text-amber-300 transition flex items-center gap-1">
                    <i data-lucide="phone" class="w-3.5 h-3.5"></i> +213 781 00 00 46
                </a>
            </div>
        </div>
    </div>

    <!-- Navigation -->
    <header class="sticky top-0 z-50 glass-dark border-b border-white/10 shadow-lg">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-20 md:h-24">
                <!-- Official Logo + Direct Media Upload Trigger -->
                <div class="flex items-center gap-2.5 shrink-0">
                    <a href="#accueil" class="flex items-center group">
                        <div class="bg-white rounded-2xl px-3.5 py-2 shadow-md border border-amber-300/60 flex items-center justify-center transition-transform duration-300 group-hover:scale-105 min-w-[130px] min-h-[54px]">
                            <img src="logo.jpeg"
                                 onerror="handleLogoError(this)"
                                 alt="Envol Travel"
                                 class="brand-logo-img h-12 sm:h-14 md:h-16 w-auto object-contain block">
                            <span class="brand-logo-fallback hidden font-extrabold text-xl tracking-tight">
                                <span class="logo-gradient-text">EnVol</span> <span class="text-blue-700">Travel</span>
                            </span>
                        </div>
                    </a>
                    <!-- Bouton pour importer le logo et la vidéo directement -->
                    <button type="button" onclick="openMediaUploader()" title="Importer le logo et la vidéo MP4"
                            class="bg-white/10 hover:bg-orange-500 text-amber-300 hover:text-white border border-white/15 px-3 py-2 rounded-xl transition flex items-center gap-1.5 text-xs font-bold">
                        <i data-lucide="upload-cloud" class="w-4 h-4"></i>
                        <span class="hidden sm:inline">Logo & Vidéo</span>
                    </button>
                </div>

                <!-- Desktop Menu -->
                <nav class="hidden lg:flex items-center space-x-7 font-semibold text-sm text-slate-200">
                    <a href="#accueil" class="hover:text-amber-400 transition">Accueil</a>
                    <a href="#video-promo" class="hover:text-amber-400 transition flex items-center gap-1.5">
                        <span class="w-2 h-2 rounded-full bg-orange-500 animate-ping"></span> Spot Vidéo
                    </a>
                    <a href="#prestations" class="hover:text-amber-400 transition">Prestations</a>
                    <a href="#destinations" class="hover:text-amber-400 transition">Voyages Organisés</a>
                    <a href="#omra-visa" class="hover:text-amber-400 transition">Omra & Visa</a>
                    <a href="#avis" class="hover:text-amber-400 transition">Avis Clients</a>
                    <a href="#contact" class="hover:text-amber-400 transition">Localisation</a>
                </nav>

                <!-- CTA Button -->
                <div class="hidden sm:flex items-center gap-3">
                    <a href="https://wa.me/213781000046?text=Bonjour%20Envol%20Travel%2C%20je%20souhaite%20avoir%20un%20renseignement%20pour%20un%20voyage."
                       target="_blank" rel="noopener noreferrer"
                       class="btn-solar text-white font-bold text-sm px-5 py-3 rounded-xl shadow-lg flex items-center gap-2">
                        <i data-lucide="message-circle" class="w-4 h-4"></i>
                        <span>Devis WhatsApp</span>
                    </a>
                </div>

                <!-- Mobile Menu Button -->
                <button id="mobile-menu-btn" aria-label="Menu principal" class="lg:hidden p-2.5 rounded-xl text-white hover:bg-white/10 transition">
                    <i data-lucide="menu" class="w-7 h-7"></i>
                </button>
            </div>
        </div>

        <!-- Mobile Dropdown -->
        <div id="mobile-menu" class="hidden lg:hidden bg-navy-900 border-t border-white/10 px-4 pt-3 pb-6 space-y-2 shadow-2xl">
            <a href="#accueil" class="mobile-link block py-2.5 px-3 rounded-xl font-semibold text-slate-200 hover:bg-white/10 hover:text-amber-400">Accueil</a>
            <a href="#video-promo" class="mobile-link block py-2.5 px-3 rounded-xl font-semibold text-slate-200 hover:bg-white/10 hover:text-amber-400">Vidéo Présentation</a>
            <a href="#prestations" class="mobile-link block py-2.5 px-3 rounded-xl font-semibold text-slate-200 hover:bg-white/10 hover:text-amber-400">Nos Prestations</a>
            <a href="#destinations" class="mobile-link block py-2.5 px-3 rounded-xl font-semibold text-slate-200 hover:bg-white/10 hover:text-amber-400">Voyages Organisés</a>
            <a href="#omra-visa" class="mobile-link block py-2.5 px-3 rounded-xl font-semibold text-slate-200 hover:bg-white/10 hover:text-amber-400">Omra, Hajj & Visa</a>
            <a href="#avis" class="mobile-link block py-2.5 px-3 rounded-xl font-semibold text-slate-200 hover:bg-white/10 hover:text-amber-400">Avis Clients & Agrément</a>
            <a href="#contact" class="mobile-link block py-2.5 px-3 rounded-xl font-semibold text-slate-200 hover:bg-white/10 hover:text-amber-400">Localisation & Contact</a>
            <button type="button" onclick="openMediaUploader()" class="w-full text-left py-2.5 px-3 rounded-xl font-bold text-amber-400 bg-white/5 hover:bg-white/10 flex items-center gap-2">
                <i data-lucide="upload-cloud" class="w-4 h-4"></i> Importer mon Logo & Vidéo MP4
            </button>
            <div class="pt-3 grid grid-cols-2 gap-2.5">
                <a href="tel:+213781000046" class="text-center bg-white/10 text-white font-bold py-3 rounded-xl text-sm">
                    Appeler
                </a>
                <a href="https://wa.me/213781000046" target="_blank" rel="noopener noreferrer" class="text-center bg-emerald-600 text-white font-bold py-3 rounded-xl text-sm">
                    WhatsApp Direct
                </a>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="accueil" class="relative overflow-hidden bg-navy-900 pt-10 pb-24 lg:pt-16 lg:pb-32">
        <div class="absolute inset-0 z-0">
            <img src="https://images.unsplash.com/photo-1436491865332-7a61a109cc05?auto=format&fit=crop&w=1920&q=80"
                 alt="Avion en plein vol - Envol Travel Bir Mourad Raïs Alger"
                 class="w-full h-full object-cover opacity-20">
            <div class="absolute inset-0 bg-gradient-to-br from-navy-950/95 via-navy-900/90 to-blue-950/85"></div>
            <div class="absolute -top-24 -right-24 w-96 h-96 bg-orange-500/20 rounded-full blur-3xl"></div>
            <div class="absolute bottom-0 left-1/4 w-96 h-96 bg-blue-600/20 rounded-full blur-3xl"></div>
        </div>

        <div class="relative z-10 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-10 lg:gap-12 items-center">
                
                <!-- Left Column: Copy & Actions -->
                <div class="lg:col-span-7 text-white">
                    <a href="https://maps.app.goo.gl/v4kpj6zxQAFnYjrq7?g_st=ic" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-2 px-4 py-1.5 rounded-full bg-white/10 border border-amber-400/30 text-amber-300 text-xs sm:text-sm font-semibold mb-6 hover:bg-white/15 transition">
                        <i data-lucide="map-pin" class="w-4 h-4 text-orange-400"></i>
                        <span>Cité les vergers Bt 46, Bir Mourad Raïs • Alger</span>
                    </a>

                    <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold tracking-tight leading-[1.12] mb-6">
                        Votre prochain voyage commence ici avec <span class="logo-gradient-text">EnVol</span> <span class="text-sky-400">Travel</span>
                    </h1>

                    <p class="text-base sm:text-lg text-slate-300 leading-relaxed mb-8 max-w-2xl">
                        Votre agence de voyage de confiance à <strong class="text-white">Bir Mourad Raïs (Alger)</strong> : billetterie aérienne au meilleur tarif, voyages organisés tout compris en Dinars Algériens (DZD), formules Omra & Hajj et accompagnement complet pour vos visas.
                    </p>

                    <div class="flex flex-col sm:flex-row gap-4">
                        <a href="#destinations" class="btn-solar text-white font-bold px-8 py-4 rounded-2xl shadow-xl flex items-center justify-center gap-2.5 text-base">
                            <i data-lucide="compass" class="w-5 h-5"></i>
                            <span>Découvrir nos Voyages Organisés</span>
                        </a>
                        <a href="https://wa.me/213781000046?text=Bonjour%20Envol%20Travel%2C%20je%20souhaite%20un%20devis%20personnalis%C3%A9."
                           target="_blank" rel="noopener noreferrer"
                           class="bg-white/10 hover:bg-white/20 text-white border border-white/20 font-bold px-8 py-4 rounded-2xl flex items-center justify-center gap-2.5 text-base transition">
                            <i data-lucide="message-circle" class="w-5 h-5 text-emerald-400"></i>
                            <span>Devis Express WhatsApp</span>
                        </a>
                    </div>

                    <!-- Trust Metrics -->
                    <div class="grid grid-cols-3 gap-4 mt-10 pt-8 border-t border-white/10 max-w-xl">
                        <div>
                            <div class="text-2xl sm:text-3xl font-extrabold text-amber-400">+50</div>
                            <div class="text-xs sm:text-sm text-slate-300">Destinations & Vols</div>
                        </div>
                        <div>
                            <div class="text-2xl sm:text-3xl font-extrabold text-sky-400">100%</div>
                            <div class="text-xs sm:text-sm text-slate-300">Suivi Visa & Omra</div>
                        </div>
                        <div>
                            <div class="text-2xl sm:text-3xl font-extrabold text-white">7j/7</div>
                            <div class="text-xs sm:text-sm text-slate-300">Assistance WhatsApp</div>
                        </div>
                    </div>
                </div>

                <!-- Right Column: Vertical Promo Video (9:16) -->
                <div class="lg:col-span-5 flex justify-center">
                    <div class="relative w-full max-w-[310px] sm:max-w-[330px]">
                        <div class="absolute -inset-2 bg-gradient-to-tr from-orange-600 via-amber-400 to-blue-600 rounded-[2.2rem] blur-lg opacity-60"></div>
                        
                        <div class="relative bg-navy-950 rounded-[2rem] p-2.5 shadow-2xl border border-white/15">
                            <div class="relative aspect-[9/16] w-full rounded-[1.5rem] overflow-hidden bg-navy-900">
                                <video id="hero-video" class="brand-promo-video w-full h-full object-cover" src="promo.mp4" autoplay muted loop playsinline poster="https://images.unsplash.com/photo-1507525428034-b723cf961d3e?auto=format&fit=crop&w=800&q=80"></video>
                                
                                <!-- Top Badge -->
                                <div class="absolute top-3 left-3 right-3 flex items-center justify-between z-10">
                                    <span class="bg-navy-950/75 backdrop-blur-md text-white text-[11px] font-bold px-3 py-1 rounded-full flex items-center gap-1.5 border border-white/10 pointer-events-none">
                                        <span class="w-2 h-2 rounded-full bg-orange-500 animate-pulse"></span> Spot Officiel
                                    </span>
                                    <div class="flex items-center gap-1.5">
                                        <button type="button" onclick="openMediaUploader()" class="bg-orange-600/90 hover:bg-orange-600 text-white p-2 rounded-full transition shadow" title="Importer la vidéo MP4">
                                            <i data-lucide="video" class="w-4 h-4"></i>
                                        </button>
                                        <button type="button" onclick="toggleMute('hero-video', 'hero-mute-icon')" class="bg-navy-950/75 hover:bg-navy-950 backdrop-blur-md text-white p-2 rounded-full transition border border-white/10" title="Activer / Couper le son">
                                            <i id="hero-mute-icon" data-lucide="volume-x" class="w-4 h-4"></i>
                                        </button>
                                    </div>
                                </div>

                                <!-- Bottom Overlay -->
                                <div class="absolute inset-x-0 bottom-0 bg-gradient-to-t from-navy-950 via-navy-950/80 to-transparent p-4 pt-12 text-center pointer-events-none">
                                    <div class="inline-flex items-center justify-center bg-white rounded-xl px-3 py-1.5 mb-2 shadow-md min-h-[38px]">
                                        <img src="logo.jpeg"
                                             onerror="handleLogoError(this)"
                                             alt="Envol Travel"
                                             class="brand-logo-img h-8 w-auto object-contain mx-auto">
                                        <span class="brand-logo-fallback hidden font-extrabold text-sm">
                                            <span class="logo-gradient-text">EnVol</span> <span class="text-blue-700">Travel</span>
                                        </span>
                                    </div>
                                    <p class="text-white font-bold text-xs leading-snug">Billets d'avion • Séjours • Omra • Visa</p>
                                    <p class="text-amber-400 font-extrabold text-xs mt-0.5">Bir Mourad Raïs, Alger</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Quick Quote Bar -->
    <section class="relative z-20 max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 -mt-12">
        <div class="bg-white rounded-3xl shadow-2xl border border-slate-100 p-6 sm:p-8">
            <div class="flex flex-wrap items-center justify-between gap-2 mb-5">
                <div class="flex items-center gap-2.5">
                    <span class="w-9 h-9 rounded-xl bg-orange-100 text-orange-600 flex items-center justify-center">
                        <i data-lucide="search" class="w-5 h-5"></i>
                    </span>
                    <div>
                        <h2 class="font-extrabold text-navy-900 text-base sm:text-lg">Demande de Tarif & Disponibilité Rapide</h2>
                        <p class="text-xs text-slate-500">Réponse immédiate de notre équipe à Cité les vergers Bt 46, Bir Mourad Raïs</p>
                    </div>
                </div>
                <span class="text-xs font-bold text-blue-700 bg-blue-50 px-3 py-1 rounded-full border border-blue-100">Tarifs actualisés en DZD</span>
            </div>

            <form id="quick-search-form" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-5 gap-4">
                <div>
                    <label class="block text-xs font-bold text-slate-500 uppercase mb-1.5">Prestation</label>
                    <select id="qs-service" class="w-full rounded-xl border border-slate-200 bg-slate-50 px-3.5 py-3 text-sm font-semibold text-navy-900 focus:outline-none focus:border-orange-500">
                        <option value="Voyage Organisé">Voyage Organisé</option>
                        <option value="Billetterie (Vols)">Billetterie (Vols)</option>
                        <option value="Omra & Hajj">Omra & Hajj</option>
                        <option value="Assistance Visa">Assistance Visa</option>
                    </select>
                </div>

                <div>
                    <label class="block text-xs font-bold text-slate-500 uppercase mb-1.5">Destination</label>
                    <input type="text" id="qs-destination" placeholder="Ex: Istanbul, Dubaï, Tunisie..." required class="w-full rounded-xl border border-slate-200 bg-slate-50 px-3.5 py-3 text-sm font-semibold text-navy-900 focus:outline-none focus:border-orange-500">
                </div>

                <div>
                    <label class="block text-xs font-bold text-slate-500 uppercase mb-1.5">Date souhaitée</label>
                    <input type="date" id="qs-date" class="w-full rounded-xl border border-slate-200 bg-slate-50 px-3.5 py-3 text-sm font-semibold text-navy-900 focus:outline-none focus:border-orange-500">
                </div>

                <div>
                    <label class="block text-xs font-bold text-slate-500 uppercase mb-1.5">Voyageurs</label>
                    <select id="qs-guests" class="w-full rounded-xl border border-slate-200 bg-slate-50 px-3.5 py-3 text-sm font-semibold text-navy-900 focus:outline-none focus:border-orange-500">
                        <option value="1 Adulte">1 Adulte</option>
                        <option value="2 Adultes" selected>2 Adultes</option>
                        <option value="Famille (+ Enfants)">Famille (+ Enfants)</option>
                        <option value="Groupe (5+ pers.)">Groupe (5+ pers.)</option>
                    </select>
                </div>

                <div class="flex items-end">
                    <button type="submit" class="w-full btn-solar text-white font-bold py-3.5 px-4 rounded-xl shadow-lg flex items-center justify-center gap-2 text-sm">
                        <i data-lucide="send" class="w-4 h-4"></i>
                        <span>Demander le tarif</span>
                    </button>
                </div>
            </form>
        </div>
    </section>

    <!-- Services Section -->
    <section id="prestations" class="py-20 bg-slate-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-14">
                <span class="text-orange-600 font-bold text-sm uppercase tracking-wider">Nos Métiers</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-navy-900 mt-2">Nos Prestations Sur Mesure</h2>
                <p class="text-slate-600 mt-3">De l'émission de votre billet d'avion jusqu'à votre retour, l'équipe d'Envol Travel à Bir Mourad Raïs s'occupe de chaque détail.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-7">
                <!-- Service 1 -->
                <div class="bg-white rounded-3xl p-7 shadow-sm border border-slate-100 card-hover flex flex-col justify-between">
                    <div>
                        <div class="w-14 h-14 rounded-2xl bg-sky-100 text-sky-700 flex items-center justify-center mb-6">
                            <i data-lucide="plane" class="w-7 h-7"></i>
                        </div>
                        <h3 class="text-xl font-extrabold text-navy-900 mb-3">Billetterie Aérienne</h3>
                        <p class="text-slate-600 text-sm leading-relaxed mb-6">
                            Vols internationaux et nationaux (Air Algérie, Tassili Airlines et compagnies internationales) aux tarifs les plus compétitifs au départ d'Alger.
                        </p>
                    </div>
                    <button onclick="selectServiceAndScroll('Billetterie (Vols internationaux & nationaux)')" class="inline-flex items-center gap-1.5 text-sky-700 font-bold text-sm hover:gap-2.5 transition-all">
                        <span>Réserver un vol</span> <i data-lucide="arrow-right" class="w-4 h-4"></i>
                    </button>
                </div>

                <!-- Service 2 -->
                <div class="bg-white rounded-3xl p-7 shadow-sm border border-slate-100 card-hover flex flex-col justify-between">
                    <div>
                        <div class="w-14 h-14 rounded-2xl bg-orange-100 text-orange-600 flex items-center justify-center mb-6">
                            <i data-lucide="palmtree" class="w-7 h-7"></i>
                        </div>
                        <h3 class="text-xl font-extrabold text-navy-900 mb-3">Voyages Organisés</h3>
                        <p class="text-slate-600 text-sm leading-relaxed mb-6">
                            Séjours clés en main vers la Turquie, Dubaï, la Tunisie, l'Égypte, la Malaisie... Hôtels sélectionnés, transferts et excursions inclus.
                        </p>
                    </div>
                    <a href="#destinations" class="inline-flex items-center gap-1.5 text-orange-600 font-bold text-sm hover:gap-2.5 transition-all">
                        <span>Voir nos séjours</span> <i data-lucide="arrow-right" class="w-4 h-4"></i>
                    </a>
                </div>

                <!-- Service 3 -->
                <div class="bg-white rounded-3xl p-7 shadow-sm border border-slate-100 card-hover flex flex-col justify-between">
                    <div>
                        <div class="w-14 h-14 rounded-2xl bg-amber-100 text-amber-700 flex items-center justify-center mb-6">
                            <i data-lucide="moon" class="w-7 h-7"></i>
                        </div>
                        <h3 class="text-xl font-extrabold text-navy-900 mb-3">Omra & Hajj</h3>
                        <p class="text-slate-600 text-sm leading-relaxed mb-6">
                            Formules Confort et VIP à proximité immédiate du Haram à La Mecque et Médine, vols directs, visa Omra et encadrement expérimenté.
                        </p>
                    </div>
                    <button onclick="selectServiceAndScroll('Omra & Hajj (Formules Confort & VIP)')" class="inline-flex items-center gap-1.5 text-amber-700 font-bold text-sm hover:gap-2.5 transition-all">
                        <span>Demander le programme</span> <i data-lucide="arrow-right" class="w-4 h-4"></i>
                    </button>
                </div>

                <!-- Service 4 -->
                <div class="bg-white rounded-3xl p-7 shadow-sm border border-slate-100 card-hover flex flex-col justify-between">
                    <div>
                        <div class="w-14 h-14 rounded-2xl bg-blue-100 text-blue-700 flex items-center justify-center mb-6">
                            <i data-lucide="file-check-2" class="w-7 h-7"></i>
                        </div>
                        <h3 class="text-xl font-extrabold text-navy-900 mb-3">Assistance Visa</h3>
                        <p class="text-slate-600 text-sm leading-relaxed mb-6">
                            Constitution complète de vos dossiers (Schengen, Turquie, E-visas Dubaï, Égypte, Arabie Saoudite...), rendez-vous et assurance voyage agréée.
                        </p>
                    </div>
                    <button onclick="selectServiceAndScroll('Assistance Visa (Schengen, Turquie, E-visas)')" class="inline-flex items-center gap-1.5 text-blue-700 font-bold text-sm hover:gap-2.5 transition-all">
                        <span>Préparer mon dossier</span> <i data-lucide="arrow-right" class="w-4 h-4"></i>
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- Premiers Voyages Organisés Section -->
    <section id="destinations" class="py-20 bg-white border-y border-slate-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col lg:flex-row lg:items-end justify-between mb-10 gap-6">
                <div>
                    <span class="text-orange-600 font-bold text-sm uppercase tracking-wider">Nos Départs Confirmés</span>
                    <h2 class="text-3xl sm:text-4xl font-extrabold text-navy-900 mt-2">Nos Premiers Voyages Organisés</h2>
                    <p class="text-slate-600 mt-2 max-w-2xl">Séjours sélectionnés au départ d'Alger avec tarifs en Dinars Algériens (DZD). Réservez votre place en un clic sur WhatsApp ou passez nous voir à Bir Mourad Raïs.</p>
                </div>

                <!-- Filter Buttons -->
                <div class="flex flex-wrap gap-2" id="trip-filters">
                    <button type="button" data-filter="all" class="filter-btn active px-4 py-2 rounded-xl text-xs sm:text-sm font-bold bg-navy-900 text-white shadow-sm transition">
                        Toutes les offres (6)
                    </button>
                    <button type="button" data-filter="moyen-orient" class="filter-btn px-4 py-2 rounded-xl text-xs sm:text-sm font-bold bg-slate-100 text-slate-700 hover:bg-orange-100 hover:text-orange-700 transition">
                        Turquie & Émirats
                    </button>
                    <button type="button" data-filter="maghreb-afrique" class="filter-btn px-4 py-2 rounded-xl text-xs sm:text-sm font-bold bg-slate-100 text-slate-700 hover:bg-orange-100 hover:text-orange-700 transition">
                        Tunisie & Égypte
                    </button>
                    <button type="button" data-filter="asie" class="filter-btn px-4 py-2 rounded-xl text-xs sm:text-sm font-bold bg-slate-100 text-slate-700 hover:bg-orange-100 hover:text-orange-700 transition">
                        Évasion Asie
                    </button>
                    <button type="button" data-filter="omra" class="filter-btn px-4 py-2 rounded-xl text-xs sm:text-sm font-bold bg-slate-100 text-slate-700 hover:bg-orange-100 hover:text-orange-700 transition">
                        Omra & Lieux Saints
                    </button>
                </div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8" id="trips-grid">
                
                <!-- Card 1: Istanbul -->
                <div class="trip-card bg-white rounded-3xl overflow-hidden shadow-md border border-slate-100 card-hover flex flex-col justify-between" data-category="moyen-orient">
                    <div>
                        <div class="relative h-60 overflow-hidden">
                            <img src="https://images.unsplash.com/photo-1524231757912-21f4fe3a7200?auto=format&fit=crop&w=900&q=80" alt="Voyage organisé Istanbul Turquie Envol Travel" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                            <div class="absolute top-4 left-4 bg-navy-900/90 backdrop-blur-sm text-white text-xs font-bold px-3 py-1.5 rounded-full">
                                8 Jours / 7 Nuits
                            </div>
                            <div class="absolute top-4 right-4 btn-solar text-white text-xs font-extrabold px-3 py-1.5 rounded-full shadow">
                                Offre Phare
                            </div>
                        </div>
                        <div class="p-6">
                            <div class="flex items-center justify-between mb-2">
                                <h3 class="text-xl font-extrabold text-navy-900">Istanbul, Turquie</h3>
                                <span class="text-xs font-bold text-blue-700 bg-blue-50 px-2.5 py-1 rounded-lg">Vol Direct Alger</span>
                            </div>
                            <p class="text-slate-600 text-sm mb-4">
                                Hôtel 4★ à Taksim ou Sultanahmet avec petit-déjeuner, transferts aéroport A/R et guide francophone.
                            </p>
                            <ul class="space-y-1.5 text-xs text-slate-600 mb-5 border-t border-slate-100 pt-3">
                                <li class="flex items-center gap-2"><i data-lucide="check" class="w-4 h-4 text-emerald-500"></i> Billet d'avion A/R + Bagages 23 kg</li>
                                <li class="flex items-center gap-2"><i data-lucide="check" class="w-4 h-4 text-emerald-500"></i> Croisière Bosphore & Îles des Princes</li>
                                <li class="flex items-center gap-2"><i data-lucide="check" class="w-4 h-4 text-emerald-500"></i> Assistance Visa Turquie disponible</li>
                            </ul>
                        </div>
                    </div>
                    <div class="px-6 pb-6">
                        <div class="flex items-center justify-between pt-4 border-t border-slate-100">
                            <div>
                                <span class="text-xs text-slate-400 block">À partir de</span>
                                <span class="text-xl font-extrabold text-orange-600">119 000 DZD</span>
                            </div>
                            <a href="https://wa.me/213781000046?text=Bonjour%20Envol%20Travel%2C%20je%20souhaite%20r%C3%A9server%20le%20voyage%20organis%C3%A9%20%C3%A0%20Istanbul%20(8J%2F7N%20%C3%A0%20119%20000%20DZD)."
                               target="_blank" rel="noopener noreferrer"
                               class="btn-solar text-white font-bold text-sm px-4 py-2.5 rounded-xl flex items-center gap-1.5 shadow">
                                <span>Réserver</span> <i data-lucide="arrow-up-right" class="w-4 h-4"></i>
                            </a>
                        </div>
                    </div>
                </div>

                <!-- Card 2: Dubaï -->
                <div class="trip-card bg-white rounded-3xl overflow-hidden shadow-md border border-slate-100 card-hover flex flex-col justify-between" data-category="moyen-orient">
                    <div>
                        <div class="relative h-60 overflow-hidden">
                            <img src="https://images.unsplash.com/photo-1512453979798-5ea266f8880c?auto=format&fit=crop&w=900&q=80" alt="Voyage organisé Dubaï Émirats Envol Travel" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                            <div class="absolute top-4 left-4 bg-navy-900/90 backdrop-blur-sm text-white text-xs font-bold px-3 py-1.5 rounded-full">
                                7 Jours / 6 Nuits
                            </div>
                            <div class="absolute top-4 right-4 bg-emerald-600 text-white text-xs font-extrabold px-3 py-1.5 rounded-full shadow">
                                Visa Inclus
                            </div>
                        </div>
                        <div class="p-6">
                            <div class="flex items-center justify-between mb-2">
                                <h3 class="text-xl font-extrabold text-navy-900">Dubaï, Émirats</h3>
                                <span class="text-xs font-bold text-blue-700 bg-blue-50 px-2.5 py-1 rounded-lg">Hôtel 4★ / 5★</span>
                            </div>
                            <p class="text-slate-600 text-sm mb-4">
                                Séjour tout confort avec visa touristique inclus, petit-déjeuner buffet et excursions incontournables.
                            </p>
                            <ul class="space-y-1.5 text-xs text-slate-600 mb-5 border-t border-slate-100 pt-3">
                                <li class="flex items-center gap-2"><i data-lucide="check" class="w-4 h-4 text-emerald-500"></i> Visa Émirats + Assurance inclus</li>
                                <li class="flex items-center gap-2"><i data-lucide="check" class="w-4 h-4 text-emerald-500"></i> Safari Désert 4x4 avec Dîner BBQ</li>
                                <li class="flex items-center gap-2"><i data-lucide="check" class="w-4 h-4 text-emerald-500"></i> City Tour Dubaï Marina & Burj Khalifa</li>
                            </ul>
                        </div>
                    </div>
                    <div class="px-6 pb-6">
                        <div class="flex items-center justify-between pt-4 border-t border-slate-100">
                            <div>
                                <span class="text-xs text-slate-400 block">À partir de</span>
                                <span class="text-xl font-extrabold text-orange-600">165 000 DZD</span>
                            </div>
                            <a href="https://wa.me/213781000046?text=Bonjour%20Envol%20Travel%2C%20je%20souhaite%20r%C3%A9server%20le%20voyage%20organis%C3%A9%20%C3%A0%20Duba%C3%AF%20(7J%2F6N%20%C3%A0%20165%20000%20DZD)."
                               target="_blank" rel="noopener noreferrer"
                               class="btn-solar text-white font-bold text-sm px-4 py-2.5 rounded-xl flex items-center gap-1.5 shadow">
                                <span>Réserver</span> <i data-lucide="arrow-up-right" class="w-4 h-4"></i>
                            </a>
                        </div>
                    </div>
                </div>

                <!-- Card 3: Tunisie -->
                <div class="trip-card bg-white rounded-3xl overflow-hidden shadow-md border border-slate-100 card-hover flex flex-col justify-between" data-category="maghreb-afrique">
                    <div>
                        <div class="relative h-60 overflow-hidden">
                            <img src="https://images.unsplash.com/photo-1540541338287-41700207dee6?auto=format&fit=crop&w=900&q=80" alt="Séjour Tunisie Hammamet Sousse Envol Travel" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                            <div class="absolute top-4 left-4 bg-navy-900/90 backdrop-blur-sm text-white text-xs font-bold px-3 py-1.5 rounded-full">
                                6 Jours / 5 Nuits
                            </div>
                            <div class="absolute top-4 right-4 bg-amber-500 text-navy-950 text-xs font-extrabold px-3 py-1.5 rounded-full shadow">
                                Spécial Famille
                            </div>
                        </div>
                        <div class="p-6">
                            <div class="flex items-center justify-between mb-2">
                                <h3 class="text-xl font-extrabold text-navy-900">Tunis & Hammamet</h3>
                                <span class="text-xs font-bold text-blue-700 bg-blue-50 px-2.5 py-1 rounded-lg">Demi-Pension</span>
                            </div>
                            <p class="text-slate-600 text-sm mb-4">
                                Détente en bord de mer dans des complexes hôteliers 4★ et 5★ à Yasmine Hammamet ou Sousse.
                            </p>
                            <ul class="space-y-1.5 text-xs text-slate-600 mb-5 border-t border-slate-100 pt-3">
                                <li class="flex items-center gap-2"><i data-lucide="check" class="w-4 h-4 text-emerald-500"></i> Transport Bus Confort ou Avion au choix</li>
                                <li class="flex items-center gap-2"><i data-lucide="check" class="w-4 h-4 text-emerald-500"></i> Hôtel 4★/5★ Pieds dans l'eau</li>
                                <li class="flex items-center gap-2"><i data-lucide="check" class="w-4 h-4 text-emerald-500"></i> Sorties Sidi Bou Saïd, Carthage & Nabeul</li>
                            </ul>
                        </div>
                    </div>
                    <div class="px-6 pb-6">
                        <div class="flex items-center justify-between pt-4 border-t border-slate-100">
                            <div>
                                <span class="text-xs text-slate-400 block">À partir de</span>
                                <span class="text-xl font-extrabold text-orange-600">54 000 DZD</span>
                            </div>
                            <a href="https://wa.me/213781000046?text=Bonjour%20Envol%20Travel%2C%20je%20souhaite%20r%C3%A9server%20le%20s%C3%A9jour%20en%20Tunisie%20Hammamet%20(6J%2F5N%20%C3%A0%2054%20000%20DZD)."
                               target="_blank" rel="noopener noreferrer"
                               class="btn-solar text-white font-bold text-sm px-4 py-2.5 rounded-xl flex items-center gap-1.5 shadow">
                                <span>Réserver</span> <i data-lucide="arrow-up-right" class="w-4 h-4"></i>
                            </a>
                        </div>
                    </div>
                </div>

                <!-- Card 4: Égypte -->
                <div class="trip-card bg-white rounded-3xl overflow-hidden shadow-md border border-slate-100 card-hover flex flex-col justify-between" data-category="maghreb-afrique">
                    <div>
                        <div class="relative h-60 overflow-hidden">
                            <img src="https://images.unsplash.com/photo-1539650116574-8efeb43e2750?auto=format&fit=crop&w=900&q=80" alt="Voyage organisé Le Caire Pyramides Égypte" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                            <div class="absolute top-4 left-4 bg-navy-900/90 backdrop-blur-sm text-white text-xs font-bold px-3 py-1.5 rounded-full">
                                8 Jours / 7 Nuits
                            </div>
                        </div>
                        <div class="p-6">
                            <div class="flex items-center justify-between mb-2">
                                <h3 class="text-xl font-extrabold text-navy-900">Le Caire & Charm</h3>
                                <span class="text-xs font-bold text-blue-700 bg-blue-50 px-2.5 py-1 rounded-lg">Culture & Mer</span>
                            </div>
                            <p class="text-slate-600 text-sm mb-4">
                                Visite des Pyramides de Gizeh, du Musée Égyptien et dîner-croisière sur le Nil avec accompagnement visa.
                            </p>
                            <ul class="space-y-1.5 text-xs text-slate-600 mb-5 border-t border-slate-100 pt-3">
                                <li class="flex items-center gap-2"><i data-lucide="check" class="w-4 h-4 text-emerald-500"></i> Vol Direct Alger – Le Caire A/R</li>
                                <li class="flex items-center gap-2"><i data-lucide="check" class="w-4 h-4 text-emerald-500"></i> Excursions Pyramides & Khan El-Khalili</li>
                                <li class="flex items-center gap-2"><i data-lucide="check" class="w-4 h-4 text-emerald-500"></i> Assistance complète Visa Égypte</li>
                            </ul>
                        </div>
                    </div>
                    <div class="px-6 pb-6">
                        <div class="flex items-center justify-between pt-4 border-t border-slate-100">
                            <div>
                                <span class="text-xs text-slate-400 block">À partir de</span>
                                <span class="text-xl font-extrabold text-orange-600">128 000 DZD</span>
                            </div>
                            <a href="https://wa.me/213781000046?text=Bonjour%20Envol%20Travel%2C%20je%20souhaite%20r%C3%A9server%20le%20voyage%20organis%C3%A9%20en%20%C3%89gypte%20(8J%2F7N%20%C3%A0%20128%20000%20DZD)."
                               target="_blank" rel="noopener noreferrer"
                               class="btn-solar text-white font-bold text-sm px-4 py-2.5 rounded-xl flex items-center gap-1.5 shadow">
                                <span>Réserver</span> <i data-lucide="arrow-up-right" class="w-4 h-4"></i>
                            </a>
                        </div>
                    </div>
                </div>

                <!-- Card 5: Malaisie -->
                <div class="trip-card bg-white rounded-3xl overflow-hidden shadow-md border border-slate-100 card-hover flex flex-col justify-between" data-category="asie">
                    <div>
                        <div class="relative h-60 overflow-hidden">
                            <img src="https://images.unsplash.com/photo-1596422846543-75c6fc197f07?auto=format&fit=crop&w=900&q=80" alt="Voyage organisé Kuala Lumpur Langkawi Malaisie" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                            <div class="absolute top-4 left-4 bg-navy-900/90 backdrop-blur-sm text-white text-xs font-bold px-3 py-1.5 rounded-full">
                                10 Jours / 9 Nuits
                            </div>
                            <div class="absolute top-4 right-4 btn-royal text-white text-xs font-extrabold px-3 py-1.5 rounded-full shadow">
                                Sans Visa
                            </div>
                        </div>
                        <div class="p-6">
                            <div class="flex items-center justify-between mb-2">
                                <h3 class="text-xl font-extrabold text-navy-900">Malaisie Combinée</h3>
                                <span class="text-xs font-bold text-blue-700 bg-blue-50 px-2.5 py-1 rounded-lg">Kuala & Langkawi</span>
                            </div>
                            <p class="text-slate-600 text-sm mb-4">
                                Découvrez les tours Petronas à Kuala Lumpur et les plages paradisiaques de Langkawi avec vols internes.
                            </p>
                            <ul class="space-y-1.5 text-xs text-slate-600 mb-5 border-t border-slate-100 pt-3">
                                <li class="flex items-center gap-2"><i data-lucide="check" class="w-4 h-4 text-emerald-500"></i> Entrée sans visa pour les Algériens</li>
                                <li class="flex items-center gap-2"><i data-lucide="check" class="w-4 h-4 text-emerald-500"></i> Hôtels 4★ avec petit-déjeuner</li>
                                <li class="flex items-center gap-2"><i data-lucide="check" class="w-4 h-4 text-emerald-500"></i> Excursions Batu Caves & Genting</li>
                            </ul>
                        </div>
                    </div>
                    <div class="px-6 pb-6">
                        <div class="flex items-center justify-between pt-4 border-t border-slate-100">
                            <div>
                                <span class="text-xs text-slate-400 block">À partir de</span>
                                <span class="text-xl font-extrabold text-orange-600">245 000 DZD</span>
                            </div>
                            <a href="https://wa.me/213781000046?text=Bonjour%20Envol%20Travel%2C%20je%20souhaite%20r%C3%A9server%20le%20voyage%20organis%C3%A9%20en%20Malaisie%20(10J%2F9N%20%C3%A0%20245%20000%20DZD)."
                               target="_blank" rel="noopener noreferrer"
                               class="btn-solar text-white font-bold text-sm px-4 py-2.5 rounded-xl flex items-center gap-1.5 shadow">
                                <span>Réserver</span> <i data-lucide="arrow-up-right" class="w-4 h-4"></i>
                            </a>
                        </div>
                    </div>
                </div>

                <!-- Card 6: Omra -->
                <div class="trip-card bg-gradient-to-br from-navy-900 to-navy-950 text-white rounded-3xl overflow-hidden shadow-xl border border-amber-500/30 card-hover flex flex-col justify-between" data-category="omra">
                    <div>
                        <div class="relative h-60 overflow-hidden">
                            <img src="https://images.unsplash.com/photo-1591604129939-f1efa4d9f7fa?auto=format&fit=crop&w=900&q=80" alt="Omra La Mecque et Médine Envol Travel" class="w-full h-full object-cover opacity-85 hover:scale-105 transition duration-500">
                            <div class="absolute top-4 left-4 bg-amber-500 text-navy-950 text-xs font-extrabold px-3 py-1.5 rounded-full">
                                Confort & VIP
                            </div>
                        </div>
                        <div class="p-6">
                            <div class="flex items-center justify-between mb-2">
                                <h3 class="text-xl font-extrabold text-white">Omra La Mecque & Médine</h3>
                            </div>
                            <p class="text-slate-300 text-sm mb-4">
                                Formules Confort et VIP à proximité immédiate du Haram. Billet d'avion, visa Omra, transferts et guides qualifiés inclus.
                            </p>
                            <ul class="space-y-1.5 text-xs text-slate-300 mb-5 border-t border-white/10 pt-3">
                                <li class="flex items-center gap-2"><i data-lucide="check" class="w-4 h-4 text-amber-400"></i> Hôtels 4★ et 5★ proches du Haram</li>
                                <li class="flex items-center gap-2"><i data-lucide="check" class="w-4 h-4 text-amber-400"></i> Ziyarates & Encadrement religieux</li>
                                <li class="flex items-center gap-2"><i data-lucide="check" class="w-4 h-4 text-amber-400"></i> Visa Omra & Assurance inclus</li>
                            </ul>
                        </div>
                    </div>
                    <div class="px-6 pb-6">
                        <div class="flex items-center justify-between pt-4 border-t border-white/15">
                            <div>
                                <span class="text-xs text-slate-400 block">Formules dès</span>
                                <span class="text-xl font-extrabold text-amber-400">195 000 DZD</span>
                            </div>
                            <a href="https://wa.me/213781000046?text=Bonjour%20Envol%20Travel%2C%20je%20souhaite%20conna%C3%AEtre%20vos%20prochains%20d%C3%A9parts%20Omra%20(Confort%20%2F%20VIP)."
                               target="_blank" rel="noopener noreferrer"
                               class="bg-amber-500 hover:bg-amber-400 text-navy-950 font-extrabold text-sm px-4 py-2.5 rounded-xl flex items-center gap-1.5 transition shadow">
                                <span>Programme</span> <i data-lucide="arrow-up-right" class="w-4 h-4"></i>
                            </a>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Video Showcase Section -->
    <section id="video-promo" class="py-20 bg-slate-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="bg-gradient-to-br from-navy-900 via-navy-950 to-blue-950 rounded-[2.5rem] p-8 sm:p-12 lg:p-14 shadow-2xl border border-white/10 relative overflow-hidden">
                <div class="absolute top-0 right-0 w-96 h-96 bg-orange-500/15 rounded-full blur-3xl pointer-events-none"></div>
                <div class="absolute bottom-0 left-0 w-80 h-80 bg-blue-500/15 rounded-full blur-3xl pointer-events-none"></div>

                <div class="relative z-10 grid grid-cols-1 lg:grid-cols-12 gap-10 items-center">
                    <div class="lg:col-span-7 text-white">
                        <span class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-orange-500/20 border border-orange-400/30 text-amber-300 text-xs font-bold uppercase tracking-wider mb-5">
                            <i data-lucide="film" class="w-4 h-4 text-orange-400"></i> Découvrez Envol Travel en images
                        </span>
                        <h2 class="text-3xl sm:text-4xl font-extrabold leading-tight mb-5">
                            Toutes vos envies de voyage au même endroit !
                        </h2>
                        <p class="text-slate-300 text-base sm:text-lg leading-relaxed mb-8">
                            De l'envol vers de nouveaux horizons jusqu'aux plus beaux hôtels en bord de mer, en passant par nos séjours à la carte et nos offres de billetterie : notre équipe vous accueille à <strong class="text-white">Cité les vergers Bt 46, Bir Mourad Raïs</strong>.
                        </p>

                        <div class="grid grid-cols-1 sm:grid-cols-3 gap-4 mb-8">
                            <div class="bg-white/5 border border-white/10 rounded-2xl p-4">
                                <div class="w-10 h-10 rounded-xl bg-orange-500/20 text-orange-400 flex items-center justify-center mb-3">
                                    <i data-lucide="ticket" class="w-5 h-5"></i>
                                </div>
                                <h3 class="font-bold text-white text-sm">Billets d'Avion</h3>
                                <p class="text-xs text-slate-400 mt-1">Vols directs et escales au meilleur tarif.</p>
                            </div>
                            <div class="bg-white/5 border border-white/10 rounded-2xl p-4">
                                <div class="w-10 h-10 rounded-xl bg-amber-500/20 text-amber-400 flex items-center justify-center mb-3">
                                    <i data-lucide="building-2" class="w-5 h-5"></i>
                                </div>
                                <h3 class="font-bold text-white text-sm">Hôtels & Séjours</h3>
                                <p class="text-xs text-slate-400 mt-1">Hébergements sélectionnés vue mer & centre-ville.</p>
                            </div>
                            <div class="bg-white/5 border border-white/10 rounded-2xl p-4">
                                <div class="w-10 h-10 rounded-xl bg-sky-500/20 text-sky-400 flex items-center justify-center mb-3">
                                    <i data-lucide="map" class="w-5 h-5"></i>
                                </div>
                                <h3 class="font-bold text-white text-sm">Voyage à la Carte</h3>
                                <p class="text-xs text-slate-400 mt-1">Programmes personnalisés selon vos envies.</p>
                            </div>
                        </div>

                        <div class="flex flex-wrap items-center gap-4">
                            <a href="tel:+213781000046" class="btn-solar text-white font-bold px-6 py-3.5 rounded-xl flex items-center gap-2 shadow-lg">
                                <i data-lucide="phone-call" class="w-5 h-5"></i>
                                <span>07 81 00 00 46</span>
                            </a>
                            <a href="https://wa.me/213781000046?text=Bonjour%20Envol%20Travel%2C%20je%20viens%20de%20voir%20votre%20vid%C3%A9o%20et%20je%20souhaite%20un%20devis."
                               target="_blank" rel="noopener noreferrer"
                               class="bg-emerald-600 hover:bg-emerald-500 text-white font-bold px-6 py-3.5 rounded-xl flex items-center gap-2 transition shadow-lg">
                                <i data-lucide="message-circle" class="w-5 h-5"></i>
                                <span>Réserver sur WhatsApp</span>
                            </a>
                        </div>
                    </div>

                    <div class="lg:col-span-5 flex justify-center">
                        <div class="w-full max-w-[300px] bg-navy-950 rounded-[2rem] p-2.5 border border-white/15 shadow-2xl">
                            <div class="relative aspect-[9/16] rounded-[1.5rem] overflow-hidden bg-navy-900">
                                <video id="showcase-video" class="brand-promo-video w-full h-full object-cover" src="promo.mp4" controls playsinline preload="metadata" poster="https://images.unsplash.com/photo-1507525428034-b723cf961d3e?auto=format&fit=crop&w=800&q=80"></video>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Omra & Visa Highlights -->
    <section id="omra-visa" class="py-20 bg-white border-t border-slate-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-8">
                
                <!-- Omra Box -->
                <div class="bg-gradient-to-br from-navy-900 to-navy-950 text-white rounded-3xl p-8 sm:p-10 shadow-xl relative overflow-hidden">
                    <div class="absolute -right-10 -bottom-10 w-56 h-56 bg-amber-500/15 rounded-full blur-2xl"></div>
                    <div class="relative z-10">
                        <span class="inline-flex items-center gap-2 text-amber-400 font-bold text-xs uppercase tracking-wider bg-amber-500/10 px-3 py-1 rounded-full mb-4">
                            <i data-lucide="sparkles" class="w-4 h-4"></i> Pèlerinage & Spiritualité
                        </span>
                        <h3 class="text-2xl sm:text-3xl font-extrabold mb-4">Omra & Hajj en toute sérénité</h3>
                        <p class="text-slate-300 text-sm sm:text-base leading-relaxed mb-6">
                            Envol Travel vous accompagne vers les Lieux Saints avec des formules Confort et VIP adaptées à vos besoins, encadrées par des professionnels.
                        </p>
                        <ul class="space-y-3 text-sm text-slate-200 mb-8">
                            <li class="flex items-center gap-3">
                                <i data-lucide="check-circle-2" class="w-5 h-5 text-amber-400 shrink-0"></i>
                                <span>Hôtels 4★ et 5★ à proximité immédiate du Haram à Médine et La Mecque</span>
                            </li>
                            <li class="flex items-center gap-3">
                                <i data-lucide="check-circle-2" class="w-5 h-5 text-amber-400 shrink-0"></i>
                                <span>Guides expérimentés, visites (Ziyarates) et transferts climatisés</span>
                            </li>
                            <li class="flex items-center gap-3">
                                <i data-lucide="check-circle-2" class="w-5 h-5 text-amber-400 shrink-0"></i>
                                <span>Visa Omra, billet d'avion et assurance pris en charge intégralement</span>
                            </li>
                        </ul>
                        <button onclick="selectServiceAndScroll('Omra & Hajj (Formules Confort & VIP)')" class="bg-amber-500 hover:bg-amber-400 text-navy-950 font-extrabold px-6 py-3.5 rounded-xl transition inline-flex items-center gap-2">
                            <span>Consulter nos formules Omra</span>
                            <i data-lucide="arrow-right" class="w-4 h-4"></i>
                        </button>
                    </div>
                </div>

                <!-- Visa Box -->
                <div class="bg-slate-50 border border-slate-200 rounded-3xl p-8 sm:p-10 shadow-sm relative overflow-hidden">
                    <div class="relative z-10">
                        <span class="inline-flex items-center gap-2 text-blue-700 font-bold text-xs uppercase tracking-wider bg-blue-100 px-3 py-1 rounded-full mb-4">
                            <i data-lucide="shield-check" class="w-4 h-4"></i> Service Consulaire & Visa
                        </span>
                        <h3 class="text-2xl sm:text-3xl font-extrabold text-navy-900 mb-4">Assistance Visa complète depuis Alger</h3>
                        <p class="text-slate-600 text-sm sm:text-base leading-relaxed mb-6">
                            Gagnez du temps et sécurisez vos démarches administratives. Nous montons votre dossier de A à Z selon les exigences officielles.
                        </p>
                        <ul class="space-y-3 text-sm text-slate-700 mb-8">
                            <li class="flex items-center gap-3">
                                <i data-lucide="check-circle-2" class="w-5 h-5 text-blue-600 shrink-0"></i>
                                <span>Rendez-vous et dossiers Schengen (VFS Global, TLScontact, Capago, BLS)</span>
                            </li>
                            <li class="flex items-center gap-3">
                                <i data-lucide="check-circle-2" class="w-5 h-5 text-blue-600 shrink-0"></i>
                                <span>E-Visas rapides : Turquie, Dubaï, Égypte, Qatar, Arabie Saoudite</span>
                            </li>
                            <li class="flex items-center gap-3">
                                <i data-lucide="check-circle-2" class="w-5 h-5 text-blue-600 shrink-0"></i>
                                <span>Réservations d'hôtels, billets d'avion et assurance voyage agréée</span>
                            </li>
                        </ul>
                        <button onclick="selectServiceAndScroll('Assistance Visa (Schengen, Turquie, E-visas)')" class="btn-royal text-white font-bold px-6 py-3.5 rounded-xl transition inline-flex items-center gap-2">
                            <span>Vérifier les documents requis</span>
                            <i data-lucide="arrow-right" class="w-4 h-4"></i>
                        </button>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Avis Clients & Agrément Officiel Section -->
    <section id="avis" class="py-20 bg-slate-50 border-t border-slate-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-14">
                <span class="text-orange-600 font-bold text-sm uppercase tracking-wider">Confiance & Transparence</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-navy-900 mt-2">Ce que disent nos voyageurs</h2>
                <p class="text-slate-600 mt-3">Des centaines de familles et voyageurs accompagnés depuis notre agence de Bir Mourad Raïs, Alger.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-7 mb-12">
                <!-- Review 1 -->
                <div class="bg-white rounded-3xl p-7 shadow-sm border border-slate-100">
                    <div class="flex items-center gap-1 text-amber-400 mb-4">
                        <i data-lucide="star" class="w-4 h-4 fill-amber-400"></i>
                        <i data-lucide="star" class="w-4 h-4 fill-amber-400"></i>
                        <i data-lucide="star" class="w-4 h-4 fill-amber-400"></i>
                        <i data-lucide="star" class="w-4 h-4 fill-amber-400"></i>
                        <i data-lucide="star" class="w-4 h-4 fill-amber-400"></i>
                    </div>
                    <p class="text-slate-600 text-sm leading-relaxed mb-5">
                        « Excellent séjour organisé à Istanbul avec toute ma famille. L'hôtel à Taksim était impeccable, les transferts ponctuels et l'équipe d'Envol Travel très réactive sur WhatsApp. »
                    </p>
                    <div class="flex items-center gap-3 pt-4 border-t border-slate-100">
                        <div class="w-10 h-10 rounded-full bg-orange-100 text-orange-700 font-extrabold flex items-center justify-center text-sm">KB</div>
                        <div>
                            <div class="font-bold text-navy-900 text-sm">Karim B.</div>
                            <div class="text-xs text-slate-400">Voyage Organisé Istanbul • Alger</div>
                        </div>
                    </div>
                </div>

                <!-- Review 2 -->
                <div class="bg-white rounded-3xl p-7 shadow-sm border border-slate-100">
                    <div class="flex items-center gap-1 text-amber-400 mb-4">
                        <i data-lucide="star" class="w-4 h-4 fill-amber-400"></i>
                        <i data-lucide="star" class="w-4 h-4 fill-amber-400"></i>
                        <i data-lucide="star" class="w-4 h-4 fill-amber-400"></i>
                        <i data-lucide="star" class="w-4 h-4 fill-amber-400"></i>
                        <i data-lucide="star" class="w-4 h-4 fill-amber-400"></i>
                    </div>
                    <p class="text-slate-600 text-sm leading-relaxed mb-5">
                        « J'ai confié mon dossier de visa Schengen et mes billets d'avion à l'agence de Bir Mourad Raïs. Tout a été préparé avec sérieux et rapidité. Je recommande vivement ! »
                    </p>
                    <div class="flex items-center gap-3 pt-4 border-t border-slate-100">
                        <div class="w-10 h-10 rounded-full bg-blue-100 text-blue-700 font-extrabold flex items-center justify-center text-sm">SM</div>
                        <div>
                            <div class="font-bold text-navy-900 text-sm">Samira M.</div>
                            <div class="text-xs text-slate-400">Assistance Visa & Billetterie • Hydra</div>
                        </div>
                    </div>
                </div>

                <!-- Review 3 -->
                <div class="bg-white rounded-3xl p-7 shadow-sm border border-slate-100">
                    <div class="flex items-center gap-1 text-amber-400 mb-4">
                        <i data-lucide="star" class="w-4 h-4 fill-amber-400"></i>
                        <i data-lucide="star" class="w-4 h-4 fill-amber-400"></i>
                        <i data-lucide="star" class="w-4 h-4 fill-amber-400"></i>
                        <i data-lucide="star" class="w-4 h-4 fill-amber-400"></i>
                        <i data-lucide="star" class="w-4 h-4 fill-amber-400"></i>
                    </div>
                    <p class="text-slate-600 text-sm leading-relaxed mb-5">
                        « Omra inoubliable avec mes parents. Hôtels très proches du Haram à La Mecque et Médine, encadrement bienveillant du départ jusqu'au retour à Alger. Baraka Allahou fikoum. »
                    </p>
                    <div class="flex items-center gap-3 pt-4 border-t border-slate-100">
                        <div class="w-10 h-10 rounded-full bg-amber-100 text-amber-700 font-extrabold flex items-center justify-center text-sm">YT</div>
                        <div>
                            <div class="font-bold text-navy-900 text-sm">Yacine T.</div>
                            <div class="text-xs text-slate-400">Formule Omra Confort • Kouba</div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Agrément & Guarantees Banner -->
            <div class="bg-white rounded-3xl p-6 sm:p-8 border border-slate-200 shadow-sm grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
                <div class="flex items-start gap-3.5">
                    <div class="w-11 h-11 rounded-2xl bg-orange-100 text-orange-600 flex items-center justify-center shrink-0">
                        <i data-lucide="award" class="w-5 h-5"></i>
                    </div>
                    <div>
                        <h4 class="font-extrabold text-navy-900 text-sm">Agence Agréée</h4>
                        <p class="text-xs text-slate-500 mt-1">Ministère du Tourisme et de l'Artisanat — Algérie.</p>
                    </div>
                </div>
                <div class="flex items-start gap-3.5">
                    <div class="w-11 h-11 rounded-2xl bg-blue-100 text-blue-700 flex items-center justify-center shrink-0">
                        <i data-lucide="map-pin" class="w-5 h-5"></i>
                    </div>
                    <div>
                        <h4 class="font-extrabold text-navy-900 text-sm">Bureau à Alger</h4>
                        <p class="text-xs text-slate-500 mt-1">Cité les vergers Bt 46, Bir Mourad Raïs.</p>
                    </div>
                </div>
                <div class="flex items-start gap-3.5">
                    <div class="w-11 h-11 rounded-2xl bg-emerald-100 text-emerald-700 flex items-center justify-center shrink-0">
                        <i data-lucide="headphones" class="w-5 h-5"></i>
                    </div>
                    <div>
                        <h4 class="font-extrabold text-navy-900 text-sm">Assistance 7j/7</h4>
                        <p class="text-xs text-slate-500 mt-1">Suivi continu au +213 781 00 00 46.</p>
                    </div>
                </div>
                <div class="flex items-start gap-3.5">
                    <div class="w-11 h-11 rounded-2xl bg-amber-100 text-amber-700 flex items-center justify-center shrink-0">
                        <i data-lucide="banknote" class="w-5 h-5"></i>
                    </div>
                    <div>
                        <h4 class="font-extrabold text-navy-900 text-sm">Tarifs Clairs en DZD</h4>
                        <p class="text-xs text-slate-500 mt-1">Paiement en agence ou réservation à distance.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact, Map & Quote Form Section -->
    <section id="contact" class="py-20 bg-white border-t border-slate-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12">
                
                <!-- Contact Info & Google Maps -->
                <div class="lg:col-span-5 space-y-6">
                    <div>
                        <span class="text-orange-600 font-bold text-sm uppercase tracking-wider">Nous Trouver & Contacter</span>
                        <h2 class="text-3xl sm:text-4xl font-extrabold text-navy-900 mt-2">Votre prochain voyage commence ici !</h2>
                        <p class="text-slate-600 mt-3 leading-relaxed">
                            Rendez-nous visite à notre agence à <strong class="text-navy-900">Bir Mourad Raïs</strong> ou contactez-nous directement par téléphone, WhatsApp ou Email.
                        </p>
                    </div>

                    <div class="space-y-3.5">
                        <a href="https://maps.app.goo.gl/v4kpj6zxQAFnYjrq7?g_st=ic"
                           target="_blank" rel="noopener noreferrer"
                           class="flex items-start gap-4 p-4 rounded-2xl bg-orange-50 border border-orange-200 hover:bg-orange-100/70 transition group">
                            <div class="w-12 h-12 rounded-xl btn-solar text-white flex items-center justify-center shrink-0">
                                <i data-lucide="map-pin" class="w-6 h-6"></i>
                            </div>
                            <div class="flex-1">
                                <div class="text-xs font-bold text-orange-700 uppercase flex items-center justify-between">
                                    <span>Adresse de l'Agence</span>
                                    <span class="underline group-hover:text-orange-900 flex items-center gap-1">Ouvrir GPS <i data-lucide="external-link" class="w-3 h-3"></i></span>
                                </div>
                                <div class="text-base font-extrabold text-navy-900 mt-0.5">Cité les vergers Bt 46, Bir Mourad Raïs, Alger</div>
                                <div class="text-xs text-slate-600 mt-1">Dim–Jeu : 10h00–18h00 • Sam : 14h00–18h00</div>
                            </div>
                        </a>

                        <a href="https://wa.me/213781000046?text=Bonjour%20Envol%20Travel%2C%20je%20souhaite%20avoir%20des%20informations."
                           target="_blank" rel="noopener noreferrer"
                           class="flex items-center gap-4 p-4 rounded-2xl bg-emerald-50 border border-emerald-200 hover:bg-emerald-100/70 transition">
                            <div class="w-12 h-12 rounded-xl bg-emerald-600 text-white flex items-center justify-center shrink-0">
                                <i data-lucide="message-circle" class="w-6 h-6"></i>
                            </div>
                            <div>
                                <div class="text-xs font-bold text-emerald-700 uppercase">WhatsApp Direct (Réponse rapide)</div>
                                <div class="text-lg font-extrabold text-navy-900">+213 781 00 00 46</div>
                            </div>
                        </a>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                            <a href="tel:+213781000046" class="flex items-center gap-3 p-4 rounded-2xl bg-slate-50 border border-slate-200 hover:border-orange-300 transition">
                                <div class="w-10 h-10 rounded-xl bg-navy-900 text-white flex items-center justify-center shrink-0">
                                    <i data-lucide="phone" class="w-5 h-5"></i>
                                </div>
                                <div>
                                    <div class="text-[11px] font-bold text-slate-500 uppercase">Téléphone</div>
                                    <div class="text-sm font-extrabold text-navy-900">07 81 00 00 46</div>
                                </div>
                            </a>

                            <a href="mailto:envoltravel@gmail.com" class="flex items-center gap-3 p-4 rounded-2xl bg-slate-50 border border-slate-200 hover:border-blue-300 transition">
                                <div class="w-10 h-10 rounded-xl bg-blue-600 text-white flex items-center justify-center shrink-0">
                                    <i data-lucide="mail" class="w-5 h-5"></i>
                                </div>
                                <div class="min-w-0">
                                    <div class="text-[11px] font-bold text-slate-500 uppercase">Email</div>
                                    <div class="text-sm font-extrabold text-navy-900 truncate">envoltravel@gmail.com</div>
                                </div>
                            </a>
                        </div>
                    </div>

                    <!-- Interactive Google Map pointing directly to Envol Travel -->
                    <div class="rounded-2xl overflow-hidden border border-slate-200 shadow-sm h-56 relative group">
                        <iframe
                            title="Localisation Envol Travel - Cité les vergers Bt 46, Bir Mourad Raïs, Alger"
                            src="https://maps.google.com/maps?q=Envol%20Travel%20Cit%C3%A9%20les%20vergers%20Bt%2046%20Bir%20Mourad%20Ra%C3%AFs%20Alger&t=&z=16&ie=UTF8&iwloc=&output=embed"
                            class="w-full h-full border-0"
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                        <a href="https://maps.app.goo.gl/v4kpj6zxQAFnYjrq7?g_st=ic"
                           target="_blank" rel="noopener noreferrer"
                           class="absolute bottom-3 right-3 bg-navy-900/90 hover:bg-navy-900 text-white text-xs font-bold px-3.5 py-2 rounded-xl shadow-lg flex items-center gap-1.5 backdrop-blur-sm transition">
                            <i data-lucide="navigation" class="w-3.5 h-3.5 text-amber-400"></i>
                            <span>Itinéraire Google Maps</span>
                        </a>
                    </div>
                </div>

                <!-- Interactive Booking / Quote Form -->
                <div class="lg:col-span-7">
                    <div class="bg-slate-50 rounded-3xl p-8 sm:p-10 shadow-lg border border-slate-200/80">
                        <h3 class="text-2xl font-extrabold text-navy-900 mb-2">Demande de Devis & Réservation</h3>
                        <p class="text-sm text-slate-500 mb-6">Remplissez les informations ci-dessous pour générer automatiquement votre message pré-rempli vers WhatsApp ou Email.</p>

                        <form id="contact-form" class="space-y-5">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-5">
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 uppercase mb-1.5">Nom & Prénom *</label>
                                    <input type="text" id="cf-name" required placeholder="Votre nom complet" class="w-full rounded-xl border border-slate-200 bg-white px-4 py-3 text-sm font-medium focus:outline-none focus:border-orange-500">
                                </div>
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 uppercase mb-1.5">Téléphone *</label>
                                    <input type="tel" id="cf-phone" required placeholder="Ex: 0550 00 00 00" class="w-full rounded-xl border border-slate-200 bg-white px-4 py-3 text-sm font-medium focus:outline-none focus:border-orange-500">
                                </div>
                            </div>

                            <div>
                                <label class="block text-xs font-bold text-slate-700 uppercase mb-1.5">Prestation Souhaitée</label>
                                <select id="cf-service" class="w-full rounded-xl border border-slate-200 bg-white px-4 py-3 text-sm font-semibold text-navy-900 focus:outline-none focus:border-orange-500">
                                    <option value="Billetterie (Vols internationaux & nationaux)">Billetterie (Vols internationaux & nationaux)</option>
                                    <option value="Voyage Organisé (Turquie, Dubaï, Tunisie, Égypte, Malaisie...)">Voyage Organisé (Turquie, Dubaï, Tunisie, Égypte, Malaisie...)</option>
                                    <option value="Omra & Hajj (Formules Confort & VIP)">Omra & Hajj (Formules Confort & VIP)</option>
                                    <option value="Assistance Visa (Schengen, Turquie, E-visas)">Assistance Visa (Schengen, Turquie, E-visas)</option>
                                    <option value="Autre renseignement">Autre renseignement</option>
                                </select>
                            </div>

                            <div>
                                <label class="block text-xs font-bold text-slate-700 uppercase mb-1.5">Détails de votre voyage *</label>
                                <textarea id="cf-message" rows="4" required placeholder="Indiquez votre destination, les dates souhaitées, le nombre d'adultes et d'enfants..." class="w-full rounded-xl border border-slate-200 bg-white px-4 py-3 text-sm font-medium focus:outline-none focus:border-orange-500"></textarea>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 pt-2">
                                <button type="submit" class="w-full bg-emerald-600 hover:bg-emerald-700 text-white font-bold py-4 px-6 rounded-xl shadow-lg flex items-center justify-center gap-2 transition">
                                    <i data-lucide="message-circle" class="w-5 h-5"></i>
                                    <span>Envoyer sur WhatsApp</span>
                                </button>
                                <button type="button" id="send-email-btn" class="w-full bg-navy-900 hover:bg-navy-800 text-white font-bold py-4 px-6 rounded-xl shadow-lg flex items-center justify-center gap-2 transition">
                                    <i data-lucide="mail" class="w-5 h-5"></i>
                                    <span>Envoyer par Email</span>
                                </button>
                            </div>
                        </form>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-navy-950 text-slate-300 pt-16 pb-8 border-t border-white/10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-10 pb-12 border-b border-white/10">
                
                <!-- Brand -->
                <div>
                    <div class="inline-flex items-center justify-center bg-white rounded-2xl px-4 py-2.5 mb-5 shadow-md min-w-[140px] min-h-[60px]">
                        <img src="logo.jpeg"
                             onerror="handleLogoError(this)"
                             alt="Envol Travel"
                             class="brand-logo-img h-14 sm:h-16 w-auto object-contain">
                        <span class="brand-logo-fallback hidden font-extrabold text-xl">
                            <span class="logo-gradient-text">EnVol</span> <span class="text-blue-700">Travel</span>
                        </span>
                    </div>
                    <p class="text-sm text-slate-400 leading-relaxed">
                        Toutes vos envies de voyage au même endroit ! Agence de voyage agréée située à Cité les vergers Bt 46, Bir Mourad Raïs, Alger.
                    </p>
                </div>

                <!-- Quick Links -->
                <div>
                    <h4 class="text-white font-bold text-base mb-4">Navigation</h4>
                    <ul class="space-y-2.5 text-sm">
                        <li><a href="#accueil" class="hover:text-amber-400 transition">Accueil</a></li>
                        <li><a href="#video-promo" class="hover:text-amber-400 transition">Vidéo Présentation</a></li>
                        <li><a href="#prestations" class="hover:text-amber-400 transition">Nos Prestations</a></li>
                        <li><a href="#destinations" class="hover:text-amber-400 transition">Voyages Organisés</a></li>
                        <li><a href="#omra-visa" class="hover:text-amber-400 transition">Omra, Hajj & Visa</a></li>
                        <li><a href="#contact" class="hover:text-amber-400 transition">Localisation & Contact</a></li>
                    </ul>
                </div>

                <!-- Services -->
                <div>
                    <h4 class="text-white font-bold text-base mb-4">Nos Prestations</h4>
                    <ul class="space-y-2.5 text-sm">
                        <li class="flex items-center gap-2"><i data-lucide="chevron-right" class="w-4 h-4 text-orange-500"></i> Billetterie (Vols A/R)</li>
                        <li class="flex items-center gap-2"><i data-lucide="chevron-right" class="w-4 h-4 text-orange-500"></i> Voyages Organisés en DZD</li>
                        <li class="flex items-center gap-2"><i data-lucide="chevron-right" class="w-4 h-4 text-orange-500"></i> Omra & Hajj (Confort & VIP)</li>
                        <li class="flex items-center gap-2"><i data-lucide="chevron-right" class="w-4 h-4 text-orange-500"></i> Assistance Visa & Assurance</li>
                    </ul>
                </div>

                <!-- Contact -->
                <div>
                    <h4 class="text-white font-bold text-base mb-4">Agence Bir Mourad Raïs</h4>
                    <ul class="space-y-3 text-sm">
                        <li>
                            <a href="https://maps.app.goo.gl/v4kpj6zxQAFnYjrq7?g_st=ic" target="_blank" rel="noopener noreferrer" class="flex items-start gap-2.5 hover:text-amber-400 transition">
                                <i data-lucide="map-pin" class="w-4 h-4 text-orange-500 shrink-0 mt-1"></i>
                                <span>Cité les vergers Bt 46, Bir Mourad Raïs, Alger</span>
                            </a>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i data-lucide="phone" class="w-4 h-4 text-orange-500 shrink-0"></i>
                            <a href="tel:+213781000046" class="hover:text-white transition font-semibold">+213 781 00 00 46</a>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i data-lucide="mail" class="w-4 h-4 text-orange-500 shrink-0"></i>
                            <a href="mailto:envoltravel@gmail.com" class="hover:text-white transition">envoltravel@gmail.com</a>
                        </li>
                        <li class="flex items-start gap-2.5">
                            <i data-lucide="clock" class="w-4 h-4 text-orange-500 shrink-0 mt-1"></i>
                            <span>Dim–Jeu : 10h00–18h00<br>Sam : 14h00–18h00</span>
                        </li>
                    </ul>
                </div>
            </div>

            <div class="pt-8 flex flex-col sm:flex-row justify-between items-center gap-4 text-xs text-slate-500">
                <p>© <span id="current-year"></span> Envol Travel — Tous droits réservés. Agence de Voyage Agréée à Bir Mourad Raïs, Alger.</p>
                <div class="flex items-center gap-6">
                    <button type="button" onclick="openModal('mentions')" class="hover:text-slate-300 transition">Mentions Légales</button>
                    <button type="button" onclick="openModal('confidentialite')" class="hover:text-slate-300 transition">Confidentialité</button>
                    <button type="button" onclick="openMediaUploader()" class="hover:text-amber-400 transition">Importer Logo & Vidéo</button>
                </div>
            </div>
        </div>
    </footer>

    <!-- Floating WhatsApp Button -->
    <a href="https://wa.me/213781000046?text=Bonjour%20Envol%20Travel%2C%20je%20souhaite%20avoir%20un%20renseignement."
       target="_blank" rel="noopener noreferrer"
       aria-label="Contacter Envol Travel sur WhatsApp"
       class="fixed bottom-6 right-6 z-50 bg-emerald-500 hover:bg-emerald-600 text-white p-4 rounded-full shadow-2xl hover:scale-110 transition flex items-center gap-2 group">
        <i data-lucide="message-circle" class="w-7 h-7"></i>
        <span class="max-w-0 overflow-hidden group-hover:max-w-xs transition-all duration-300 whitespace-nowrap font-bold text-sm">
            WhatsApp Direct
        </span>
    </a>

    <!-- Direct Logo & Video MP4 Uploader Modal -->
    <div id="media-uploader-modal" class="fixed inset-0 z-50 hidden bg-navy-950/80 backdrop-blur-sm items-center justify-center p-4">
        <div class="bg-white rounded-3xl max-w-md w-full p-6 sm:p-7 shadow-2xl relative">
            <button type="button" onclick="closeMediaUploader()" class="absolute top-5 right-5 text-slate-400 hover:text-slate-700">
                <i data-lucide="x" class="w-6 h-6"></i>
            </button>
            <div class="flex items-center gap-2.5 mb-2">
                <span class="w-9 h-9 rounded-xl bg-orange-100 text-orange-600 flex items-center justify-center">
                    <i data-lucide="upload-cloud" class="w-5 h-5"></i>
                </span>
                <h3 class="text-lg font-extrabold text-navy-900">Importer votre Logo & Vidéo MP4</h3>
            </div>
            <p class="text-xs text-slate-500 mb-5 leading-relaxed">
                Sélectionnez votre logo et votre vidéo MP4 depuis votre téléphone ou ordinateur. Ils s'intégreront directement dans le fichier <strong>index.html</strong> téléchargé.
            </p>

            <div class="space-y-4">
                <!-- Logo File Input -->
                <div class="p-4 rounded-2xl border-2 border-dashed border-orange-300 bg-orange-50/50">
                    <label class="block text-xs font-extrabold text-navy-900 uppercase mb-2">1. Choisir votre Logo (.jpeg, .png, .jpg)</label>
                    <input type="file" id="logo-file-input" accept="image/*" class="block w-full text-xs text-slate-600 file:mr-3 file:py-2 file:px-4 file:rounded-xl file:border-0 file:text-xs file:font-bold file:bg-orange-600 file:text-white hover:file:bg-orange-700 cursor-pointer">
                    <p id="logo-status-msg" class="hidden text-[11px] font-bold text-emerald-700 mt-2">✓ Logo chargé avec succès !</p>
                </div>

                <!-- Video File Input -->
                <div class="p-4 rounded-2xl border-2 border-dashed border-blue-300 bg-blue-50/50">
                    <label class="block text-xs font-extrabold text-navy-900 uppercase mb-2">2. Choisir votre Vidéo Promo (.mp4)</label>
                    <input type="file" id="video-file-input" accept="video/mp4,video/*" class="block w-full text-xs text-slate-600 file:mr-3 file:py-2 file:px-4 file:rounded-xl file:border-0 file:text-xs file:font-bold file:bg-blue-700 file:text-white hover:file:bg-blue-800 cursor-pointer">
                    <p id="video-status-msg" class="hidden text-[11px] font-bold text-emerald-700 mt-2">✓ Vidéo MP4 chargée avec succès !</p>
                </div>

                <!-- Export Embedded HTML Button -->
                <div id="export-html-box" class="hidden pt-2 border-t border-slate-100">
                    <button type="button" onclick="downloadEmbeddedHtml()" class="w-full btn-solar text-white font-bold text-xs py-3.5 px-4 rounded-xl shadow-lg flex items-center justify-center gap-2">
                        <i data-lucide="download" class="w-4 h-4"></i>
                        <span>Télécharger index.html complet (avec Logo & Vidéo intégrés)</span>
                    </button>
                    <p class="text-[11px] text-slate-400 mt-1.5 text-center">Glissez ensuite ce seul fichier <strong>index.html</strong> sur Netlify : le logo et la vidéo fonctionneront immédiatement pour tous vos clients.</p>
                </div>
            </div>
        </div>
    </div>

    <!-- Legal Modal -->
    <div id="legal-modal" class="fixed inset-0 z-50 hidden bg-navy-950/75 backdrop-blur-sm items-center justify-center p-4">
        <div class="bg-white rounded-3xl max-w-lg w-full p-6 sm:p-8 shadow-2xl relative">
            <button onclick="closeModal()" class="absolute top-5 right-5 text-slate-400 hover:text-slate-700">
                <i data-lucide="x" class="w-6 h-6"></i>
            </button>
            <h3 id="modal-title" class="text-xl font-extrabold text-navy-900 mb-3">Mentions Légales</h3>
            <div id="modal-body" class="text-sm text-slate-600 space-y-2 leading-relaxed"></div>
            <div class="mt-6 text-right">
                <button onclick="closeModal()" class="bg-navy-900 text-white font-bold text-sm px-5 py-2.5 rounded-xl">Fermer</button>
            </div>
        </div>
    </div>

    <script>
        // Initialize Lucide icons
        lucide.createIcons();

        // Set dynamic year
        document.getElementById('current-year').textContent = new Date().getFullYear();

        // Fallback handler if logo.jpeg / logo.png is not yet in folder
        function handleLogoError(img) {
            if (!img.dataset.triedPng) {
                img.dataset.triedPng = '1';
                img.src = 'logo.png';
                return;
            }
            if (!img.dataset.triedJpg) {
                img.dataset.triedJpg = '1';
                img.src = 'logo.jpg';
                return;
            }
            img.style.display = 'none';
            const fallback = img.parentElement.querySelector('.brand-logo-fallback');
            if (fallback) fallback.classList.remove('hidden');
        }

        let currentEmbeddedLogoDataUrl = null;
        let currentEmbeddedVideoDataUrl = null;

        function showExportButton() {
            const exportBox = document.getElementById('export-html-box');
            if (exportBox) exportBox.classList.remove('hidden');
        }

        function applyLogoToPage(dataUrl) {
            currentEmbeddedLogoDataUrl = dataUrl;
            document.querySelectorAll('.brand-logo-img').forEach(img => {
                img.src = dataUrl;
                img.style.display = 'block';
                const fallback = img.parentElement.querySelector('.brand-logo-fallback');
                if (fallback) fallback.classList.add('hidden');
            });
            const status = document.getElementById('logo-status-msg');
            if (status) status.classList.remove('hidden');
            showExportButton();
        }

        function applyVideoToPage(dataUrl) {
            currentEmbeddedVideoDataUrl = dataUrl;
            document.querySelectorAll('.brand-promo-video').forEach(video => {
                video.src = dataUrl;
                video.load();
                video.play().catch(() => {});
            });
            const status = document.getElementById('video-status-msg');
            if (status) status.classList.remove('hidden');
            showExportButton();
        }

        // Restore saved logo from localStorage if available
        try {
            const savedLogo = localStorage.getItem('envol_travel_logo_data');
            if (savedLogo) applyLogoToPage(savedLogo);
        } catch (e) {}

        // Media Uploader Modal controls
        function openMediaUploader() {
            const modal = document.getElementById('media-uploader-modal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }
        function closeMediaUploader() {
            const modal = document.getElementById('media-uploader-modal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        // Handle Logo Upload directly in browser
        document.getElementById('logo-file-input').addEventListener('change', function(e) {
            const file = e.target.files && e.target.files[0];
            if (!file) return;
            const reader = new FileReader();
            reader.onload = function(evt) {
                const dataUrl = evt.target.result;
                applyLogoToPage(dataUrl);
                try {
                    localStorage.setItem('envol_travel_logo_data', dataUrl);
                } catch (err) {}
            };
            reader.readAsDataURL(file);
        });

        // Handle Video MP4 Upload directly in browser (as embedded DataURL)
        document.getElementById('video-file-input').addEventListener('change', function(e) {
            const file = e.target.files && e.target.files[0];
            if (!file) return;
            const reader = new FileReader();
            reader.onload = function(evt) {
                const dataUrl = evt.target.result;
                applyVideoToPage(dataUrl);
            };
            reader.readAsDataURL(file);
        });

        // Download a self-contained index.html with BOTH Logo & Video MP4 embedded
        function downloadEmbeddedHtml() {
            const clone = document.documentElement.cloneNode(true);

            if (currentEmbeddedLogoDataUrl) {
                clone.querySelectorAll('.brand-logo-img').forEach(img => {
                    img.setAttribute('src', currentEmbeddedLogoDataUrl);
                    img.style.display = 'block';
                });
                clone.querySelectorAll('.brand-logo-fallback').forEach(fb => fb.classList.add('hidden'));
            }

            if (currentEmbeddedVideoDataUrl) {
                clone.querySelectorAll('.brand-promo-video').forEach(video => {
                    video.setAttribute('src', currentEmbeddedVideoDataUrl);
                });
            }

            const modal = clone.querySelector('#media-uploader-modal');
            if (modal) {
                modal.classList.add('hidden');
                modal.classList.remove('flex');
            }

            const htmlContent = '<!DOCTYPE html>\n' + clone.outerHTML;
            const blob = new Blob([htmlContent], { type: 'text/html;charset=utf-8' });
            const link = document.createElement('a');
            link.href = URL.createObjectURL(blob);
            link.download = 'index.html';
            document.body.appendChild(link);
            link.click();
            document.body.removeChild(link);
        }

        // Video Mute/Unmute Toggle
        function toggleMute(videoId, iconId) {
            const video = document.getElementById(videoId);
            const icon = document.getElementById(iconId);
            if (!video) return;
            video.muted = !video.muted;
            icon.setAttribute('data-lucide', video.muted ? 'volume-x' : 'volume-2');
            lucide.createIcons();
        }

        // Trip Category Filtering
        const filterButtons = document.querySelectorAll('.filter-btn');
        const tripCards = document.querySelectorAll('.trip-card');

        filterButtons.forEach(btn => {
            btn.addEventListener('click', () => {
                filterButtons.forEach(b => {
                    b.classList.remove('bg-navy-900', 'text-white');
                    b.classList.add('bg-slate-100', 'text-slate-700');
                });
                btn.classList.remove('bg-slate-100', 'text-slate-700');
                btn.classList.add('bg-navy-900', 'text-white');

                const selected = btn.getAttribute('data-filter');
                tripCards.forEach(card => {
                    if (selected === 'all' || card.getAttribute('data-category') === selected) {
                        card.style.display = 'flex';
                    } else {
                        card.style.display = 'none';
                    }
                });
            });
        });

        // Mobile menu toggle
        const mobileBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');
        mobileBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });
        document.querySelectorAll('.mobile-link').forEach(link => {
            link.addEventListener('click', () => mobileMenu.classList.add('hidden'));
        });

        // Pre-select service from cards & scroll to form
        function selectServiceAndScroll(serviceName) {
            const select = document.getElementById('cf-service');
            for (let i = 0; i < select.options.length; i++) {
                if (select.options[i].value === serviceName) {
                    select.selectedIndex = i;
                    break;
                }
            }
            document.getElementById('contact').scrollIntoView({ behavior: 'smooth' });
        }

        // Quick Search Bar -> WhatsApp
        document.getElementById('quick-search-form').addEventListener('submit', function(e) {
            e.preventDefault();
            const service = document.getElementById('qs-service').value;
            const destination = document.getElementById('qs-destination').value.trim();
            const date = document.getElementById('qs-date').value || 'À définir';
            const guests = document.getElementById('qs-guests').value;

            const text = `Bonjour Envol Travel,\nJe souhaite un devis rapide :\n• Prestation : ${service}\n• Destination : ${destination}\n• Date souhaitée : ${date}\n• Voyageurs : ${guests}`;
            window.open(`https://wa.me/213781000046?text=${encodeURIComponent(text)}`, '_blank', 'noopener,noreferrer');
        });

        // Contact Form -> WhatsApp
        document.getElementById('contact-form').addEventListener('submit', function(e) {
            e.preventDefault();
            const name = document.getElementById('cf-name').value.trim();
            const phone = document.getElementById('cf-phone').value.trim();
            const service = document.getElementById('cf-service').value;
            const details = document.getElementById('cf-message').value.trim();

            const text = `Bonjour Envol Travel,\nNom : ${name}\nTéléphone : ${phone}\nPrestation : ${service}\nDétails : ${details}`;
            window.open(`https://wa.me/213781000046?text=${encodeURIComponent(text)}`, '_blank', 'noopener,noreferrer');
        });

        // Contact Form -> Email
        document.getElementById('send-email-btn').addEventListener('click', function() {
            const name = document.getElementById('cf-name').value.trim() || 'Client';
            const phone = document.getElementById('cf-phone').value.trim() || 'Non précisé';
            const service = document.getElementById('cf-service').value;
            const details = document.getElementById('cf-message').value.trim() || 'Demande de renseignements';

            const subject = `Demande de devis - ${service} (${name})`;
            const body = `Bonjour Envol Travel,\n\nNom : ${name}\nTéléphone : ${phone}\nPrestation : ${service}\n\nDétails de la demande :\n${details}`;
            window.location.href = `mailto:envoltravel@gmail.com?subject=${encodeURIComponent(subject)}&body=${encodeURIComponent(body)}`;
        });

        // Modal Legal / Privacy
        function openModal(type) {
            const modal = document.getElementById('legal-modal');
            const title = document.getElementById('modal-title');
            const body = document.getElementById('modal-body');

            if (type === 'mentions') {
                title.textContent = 'Mentions Légales';
                body.innerHTML = `
                    <p><strong>Raison sociale :</strong> Envol Travel — Agence de Voyage et de Tourisme Agréée</p>
                    <p><strong>Adresse :</strong> Cité les vergers Bt 46, Bir Mourad Raïs, Alger, Algérie</p>
                    <p><strong>Téléphone / WhatsApp :</strong> +213 781 00 00 46</p>
                    <p><strong>Email :</strong> envoltravel@gmail.com</p>
                    <p>Les tarifs affichés sur le site sont indicatifs en Dinars Algériens (DZD) et confirmés lors de l'émission du devis.</p>
                `;
            } else {
                title.textContent = 'Politique de Confidentialité';
                body.innerHTML = `
                    <p>Les informations saisies dans nos formulaires sont utilisées uniquement pour traiter votre demande de devis ou de réservation auprès d'<strong>Envol Travel</strong>.</p>
                    <p>Aucune donnée personnelle n'est revendue ou transmise à des tiers non liés à l'exécution de votre voyage.</p>
                `;
            }
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeModal() {
            const modal = document.getElementById('legal-modal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }
    </script>
</body>
</html>
