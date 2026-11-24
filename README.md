```html
<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>JMD-DIGITAL &amp; CONTENT GROWTH | Kathua 184101 — Digital, Tech &amp; Career Hub</title>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Plus+Jakarta+Sans:wght@600;700;800&display=swap" rel="stylesheet" />
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'system-ui', 'sans-serif'],
            display: ['"Plus Jakarta Sans"', 'Inter', 'system-ui', 'sans-serif'],
          },
          colors: {
            obsidian: '#0B1120',
            surface: '#111827',
            goldleaf: '#EAB308',
            golddeep: '#CA8A04',
            indigoedge: '#4F46E5',
          },
          boxShadow: {
            'card-dark': '0 14px 34px -14px rgba(0, 0, 0, 0.55)',
            'gold-glow': '0 10px 28px -10px rgba(234, 179, 8, 0.35)',
          }
        }
      }
    };
  </script>
  <style>
    body {
      background-color: #0B1120;
      color: #F8FAFC;
      font-family: 'Inter', system-ui, sans-serif;
      overflow-x: hidden;
    }

    h1, h2, h3, .font-display {
      font-family: '"Plus Jakarta Sans"', 'Inter', system-ui, sans-serif;
    }

    .hero-surface {
      background-image:
        radial-gradient(at 10% 10%, rgba(234, 179, 8, 0.12) 0px, transparent 45%),
        radial-gradient(at 90% 15%, rgba(79, 70, 229, 0.16) 0px, transparent 45%),
        linear-gradient(180deg, #0F172A 0%, #0B1120 100%);
    }

    .page-view {
      animation: pageFadeIn 0.24s ease-out;
    }

    @keyframes pageFadeIn {
      from {
        opacity: 0;
        transform: translateY(6px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    .nav-page-active {
      background-color: rgba(234, 179, 8, 0.14);
      color: #FACC15;
      border-color: rgba(234, 179, 8, 0.45);
    }

    .filter-active {
      background-color: #EAB308;
      color: #0B1120;
      border-color: #EAB308;
    }

    /* High-craft founder portrait frame */
    .founder-frame {
      background: linear-gradient(135deg, rgba(234, 179, 8, 0.65), rgba(79, 70, 229, 0.55));
      padding: 3px;
      border-radius: 1.5rem;
    }
  </style>
</head>
<body class="min-h-screen antialiased selection:bg-amber-400 selection:text-slate-950">

  <!-- Non-blocking Toast Banner -->
  <div id="toastBanner" role="status" aria-live="polite"
    class="fixed bottom-5 right-5 z-50 hidden max-w-sm rounded-2xl border border-amber-400/40 bg-slate-900 px-4 py-3 text-sm font-medium text-white shadow-2xl">
    <div class="flex items-center gap-2.5">
      <span class="h-2.5 w-2.5 shrink-0 rounded-full bg-amber-400"></span>
      <span id="toastMessage">Ready</span>
    </div>
  </div>

  <!-- 1. TOP NAVIGATION BAR (Company Logo Emblem Only for Brand; Owner Portrait Only for Founder) -->
  <header class="sticky top-0 z-40 border-b border-slate-800/90 bg-slate-950/90 backdrop-blur-md">
    <div class="mx-auto flex max-w-7xl items-center justify-between gap-3 px-4 py-3 sm:px-6 lg:px-8">

      <!-- Company Logo Emblem + Brand Name (Never uses founder face here) -->
      <button type="button" data-navigate="home" class="nav-brand-btn flex items-center gap-3 text-left group min-w-0">
        <div class="relative flex h-11 w-11 shrink-0 items-center justify-center rounded-xl border border-amber-400/50 bg-gradient-to-br from-slate-900 via-blue-950 to-slate-900 shadow-md">
          <svg class="h-7 w-7" viewBox="0 0 48 48" fill="none" aria-hidden="true">
            <path d="M9 12L24 6L39 12V24C39 33.5 32.6 40.8 24 43.5C15.4 40.8 9 33.5 9 24V12Z" fill="#0F172A" stroke="#FACC15" stroke-width="2.4"/>
            <path d="M16 17H32M26 17V29.5C26 32.2 24.1 34 21.3 34C19.4 34 18 32.9 17.4 31.3" stroke="#FACC15" stroke-width="2.8" stroke-linecap="round" stroke-linejoin="round"/>
            <path d="M29.5 23L34 18.5M34 18.5H30.5M34 18.5V22" stroke="#38BDF8" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
        </div>
        <div class="min-w-0">
          <div class="flex flex-wrap items-center gap-1.5">
            <span class="truncate font-display text-sm font-extrabold tracking-tight text-white group-hover:text-amber-300 sm:text-base">
              JMD-DIGITAL &amp; CONTENT GROWTH
            </span>
            <span class="hidden rounded-md border border-amber-400/35 bg-amber-500/10 px-2 py-0.5 text-[10px] font-bold uppercase tracking-wider text-amber-300 sm:inline-block">
              Kathua 184101
            </span>
          </div>
          <p class="truncate text-[11px] font-medium text-slate-400">
            Sole Proprietorship &bull; 51,600+ Reach &bull; 7667747546
          </p>
        </div>
      </button>

      <!-- Dedicated Multi-Page View Switcher (Desktop) -->
      <nav aria-label="Primary Pages" class="hidden items-center gap-1.5 lg:flex">
        <button type="button" data-navigate="home"
          class="nav-page-btn nav-page-active rounded-xl border border-transparent px-3.5 py-2 text-xs font-bold tracking-wide text-slate-300 transition hover:border-slate-700 hover:text-white">
          Home
        </button>
        <button type="button" data-navigate="services"
          class="nav-page-btn rounded-xl border border-transparent px-3.5 py-2 text-xs font-bold tracking-wide text-slate-300 transition hover:border-slate-700 hover:text-white">
          Services &amp; Pricing
        </button>
        <button type="button" data-navigate="founder"
          class="nav-page-btn rounded-xl border border-transparent px-3.5 py-2 text-xs font-bold tracking-wide text-slate-300 transition hover:border-slate-700 hover:text-white">
          About Founder
        </button>
        <button type="button" data-navigate="contact"
          class="nav-page-btn rounded-xl border border-transparent px-3.5 py-2 text-xs font-bold tracking-wide text-slate-300 transition hover:border-slate-700 hover:text-white">
          Contact &amp; Lead Builder
        </button>
      </nav>

      <!-- Direct WhatsApp CTA + Mobile Menu Button -->
      <div class="flex items-center gap-2">
        <a href="https://wa.me/917667747546?text=GROW%20-%20Hi%20Hemant%2C%20I%20want%20to%20grow%20my%20business%20with%20JMD-DIGITAL%20%26%20CONTENT%20GROWTH%20(Kathua%20184101)."
           target="_blank" rel="noopener noreferrer"
           class="hidden items-center gap-2 rounded-xl bg-amber-400 px-3.5 py-2.5 text-xs font-extrabold text-slate-950 shadow-gold-glow transition hover:bg-amber-300 sm:inline-flex">
          <span>WhatsApp: 7667747546</span>
          <span>→</span>
        </a>

        <button id="mobileMenuToggle" type="button" aria-label="Toggle Menu" aria-expanded="false"
          class="inline-flex h-10 w-10 items-center justify-center rounded-xl border border-slate-800 bg-slate-900 text-slate-200 transition hover:border-amber-400/50 lg:hidden">
          <svg id="menuIconOpen" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
            <path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16M4 18h16"/>
          </svg>
          <svg id="menuIconClose" class="hidden h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
            <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/>
          </svg>
        </button>
      </div>
    </div>

    <!-- Mobile Navigation Drawer -->
    <div id="mobileMenuDrawer" class="hidden border-t border-slate-800 bg-slate-950 px-4 py-3.5 lg:hidden">
      <div class="flex flex-col gap-1.5">
        <button type="button" data-navigate="home"
          class="nav-page-btn nav-page-active flex w-full items-center justify-between rounded-xl border border-transparent px-3.5 py-2.5 text-left text-sm font-bold text-slate-200">
          <span>1. Home</span>
          <span class="text-xs text-amber-400">Overview</span>
        </button>
        <button type="button" data-navigate="services"
          class="nav-page-btn flex w-full items-center justify-between rounded-xl border border-transparent px-3.5 py-2.5 text-left text-sm font-bold text-slate-200">
          <span>2. Services &amp; Pricing</span>
          <span class="text-xs text-slate-400">15 Plans</span>
        </button>
        <button type="button" data-navigate="founder"
          class="nav-page-btn flex w-full items-center justify-between rounded-xl border border-transparent px-3.5 py-2.5 text-left text-sm font-bold text-slate-200">
          <span>3. About Founder</span>
          <span class="text-xs text-slate-400">Hemant Kumar</span>
        </button>
        <button type="button" data-navigate="contact"
          class="nav-page-btn flex w-full items-center justify-between rounded-xl border border-transparent px-3.5 py-2.5 text-left text-sm font-bold text-slate-200">
          <span>4. Contact &amp; Lead Builder</span>
          <span class="text-xs text-slate-400">7667747546</span>
        </button>
        <a href="https://wa.me/917667747546?text=GROW%20-%20Hi%20Hemant%2C%20I%20want%20to%20connect%20with%20JMD-DIGITAL%20%26%20CONTENT%20GROWTH."
           target="_blank" rel="noopener noreferrer"
           class="mt-2 inline-flex w-full items-center justify-center rounded-xl bg-amber-400 px-4 py-3 text-sm font-extrabold text-slate-950">
          Chat on WhatsApp: 7667747546
        </a>
      </div>
    </div>
  </header>

  <!-- MAIN MULTI-PAGE CONTAINER -->
  <main id="appMain">

    <!-- ===================================================================== -->
    <!-- PAGE 1: HOME VIEW                                                     -->
    <!-- ===================================================================== -->
    <section id="page-home" class="page-view">
      <!-- Hero Section -->
      <div class="hero-surface border-b border-slate-800/80 py-12 sm:py-16 lg:py-20">
        <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
          <div class="grid items-center gap-10 lg:grid-cols-12 lg:gap-12">

            <!-- Left Copy -->
            <div class="lg:col-span-7">
              <div class="inline-flex flex-wrap items-center gap-2 rounded-full border border-amber-400/35 bg-amber-400/10 px-3.5 py-1.5 text-xs font-bold text-amber-300">
                <span class="h-2 w-2 rounded-full bg-amber-400"></span>
                51,600+ Community Reach &bull; Kathua (184101) &bull; Sole Proprietorship
              </div>

              <h1 class="mt-4 font-display text-3xl font-extrabold tracking-tight text-white sm:text-4xl lg:text-5xl lg:leading-[1.12]">
                Grow Your Business in <span class="text-amber-400">Kathua (184101)</span> With Google, Social Content &amp; Complete Tech Solutions.
              </h1>

              <p class="mt-4 max-w-2xl text-base leading-relaxed text-slate-300 sm:text-lg">
                <strong>JMD-DIGITAL &amp; CONTENT GROWTH</strong> helps local shops, clinics, institutes, and creators get more calls and visibility—while delivering affordable MS Office, resume, logo, web, cybersecurity, travel, and hardware/network services.
              </p>

              <!-- Primary Page & WhatsApp CTAs -->
              <div class="mt-7 flex flex-col gap-3 sm:flex-row sm:flex-wrap sm:items-center">
                <button type="button" data-navigate="services"
                  class="inline-flex items-center justify-center gap-2 rounded-xl bg-amber-400 px-6 py-3.5 text-sm font-extrabold text-slate-950 shadow-gold-glow transition hover:bg-amber-300">
                  <span>Explore All Services &amp; Pricing</span>
                  <span>→</span>
                </button>

                <a href="https://wa.me/917667747546?text=GROW%20-%20Hi%20Hemant%2C%20I%20want%20a%20free%20profile%20check%20for%20my%20business%20in%20Kathua%20(184101)."
                   target="_blank" rel="noopener noreferrer"
                   class="inline-flex items-center justify-center gap-2 rounded-xl border border-indigo-400/50 bg-indigo-600 px-5 py-3.5 text-sm font-bold text-white transition hover:bg-indigo-500">
                  <span>Send "GROW" on WhatsApp (7667747546)</span>
                </a>

                <button type="button" data-navigate="contact"
                  class="inline-flex items-center justify-center gap-2 rounded-xl border border-slate-700 bg-slate-900 px-5 py-3.5 text-sm font-bold text-slate-200 transition hover:border-amber-400/50 hover:text-white">
                  <span>Open Lead Builder</span>
                </button>
              </div>

              <!-- Quick Trust Stats -->
              <div class="mt-8 grid grid-cols-2 gap-3.5 border-t border-slate-800 pt-6 sm:grid-cols-4">
                <div class="rounded-2xl border border-slate-800 bg-slate-900/70 p-3.5">
                  <p class="font-display text-xl font-extrabold text-amber-400">₹999</p>
                  <p class="mt-0.5 text-xs text-slate-400">GMB Setup Plan</p>
                </div>
                <div class="rounded-2xl border border-slate-800 bg-slate-900/70 p-3.5">
                  <p class="font-display text-xl font-extrabold text-white">₹1,499</p>
                  <p class="mt-0.5 text-xs text-slate-400">Monthly Posts Plan</p>
                </div>
                <div class="rounded-2xl border border-slate-800 bg-slate-900/70 p-3.5">
                  <p class="font-display text-xl font-extrabold text-amber-400">₹1,999</p>
                  <p class="mt-0.5 text-xs text-slate-400">Complete Growth Pack</p>
                </div>
                <div class="rounded-2xl border border-slate-800 bg-slate-900/70 p-3.5">
                  <p class="font-display text-xl font-extrabold text-indigo-400">51.6K+</p>
                  <p class="mt-0.5 text-xs text-slate-400">Social Family Reach</p>
                </div>
              </div>
            </div>

            <!-- Right Showcase: Brand Emblem Card + Founder Portrait Card (Strictly separated) -->
            <div class="lg:col-span-5 space-y-5">
              <!-- Company Logo Emblem Card -->
              <div class="rounded-3xl border border-slate-800 bg-slate-900/90 p-5 shadow-card-dark">
                <div class="flex items-center justify-between gap-3 border-b border-slate-800 pb-4">
                  <div class="flex items-center gap-3.5">
                    <div class="flex h-14 w-14 shrink-0 items-center justify-center rounded-2xl border border-amber-400/50 bg-gradient-to-br from-slate-950 via-blue-950 to-slate-900">
                      <svg class="h-9 w-9" viewBox="0 0 48 48" fill="none" aria-hidden="true">
                        <path d="M9 12L24 6L39 12V24C39 33.5 32.6 40.8 24 43.5C15.4 40.8 9 33.5 9 24V12Z" fill="#0B1120" stroke="#FACC15" stroke-width="2.5"/>
                        <path d="M16 17H32M26 17V29.5C26 32.2 24.1 34 21.3 34C19.4 34 18 32.9 17.4 31.3" stroke="#FACC15" stroke-width="2.8" stroke-linecap="round" stroke-linejoin="round"/>
                        <path d="M29.5 23L34 18.5M34 18.5H30.5M34 18.5V22" stroke="#38BDF8" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"/>
                      </svg>
                    </div>
                    <div>
                      <span class="rounded-md bg-amber-400/15 px-2 py-0.5 text-[10px] font-extrabold uppercase tracking-wider text-amber-300">
                        Company Logo Emblem
                      </span>
                      <h2 class="mt-1 font-display text-base font-extrabold text-white">
                        JMD-DIGITAL &amp; CONTENT GROWTH
                      </h2>
                      <p class="text-xs text-slate-400">Kathua 184101 &bull; One Stop Solution</p>
                    </div>
                  </div>
                </div>

                <div class="mt-4 grid grid-cols-2 gap-2.5 text-xs">
                  <div class="rounded-xl border border-slate-800 bg-slate-950/80 p-3">
                    <p class="text-slate-400">Direct Contact</p>
                    <p class="mt-0.5 font-extrabold text-amber-300">+91 7667747546</p>
                  </div>
                  <div class="rounded-xl border border-slate-800 bg-slate-950/80 p-3">
                    <p class="text-slate-400">Business Email</p>
                    <p class="mt-0.5 truncate font-semibold text-white">hnspy1999@gmail.com</p>
                  </div>
                </div>
              </div>

              <!-- Founder Portrait Card (Uses Circular Founder Portrait with clean frame) -->
              <div class="founder-frame shadow-card-dark">
                <div class="rounded-[1.35rem] bg-slate-900 p-5">
                  <div class="flex items-center gap-4">
                    <div class="relative h-20 w-20 shrink-0 overflow-hidden rounded-full border-2 border-amber-400/80 bg-slate-950 shadow-md">
                      <img
                        src="1000386775_5.jpg"
                        alt="Hemant Kumar — Founder of JMD-DIGITAL & CONTENT GROWTH"
                        data-fallback-portrait="true"
                        class="h-full w-full object-cover object-top"
                      />
                    </div>
                    <div class="min-w-0">
                      <span class="inline-block rounded-md border border-indigo-400/40 bg-indigo-500/20 px-2 py-0.5 text-[10px] font-bold uppercase tracking-wider text-indigo-200">
                        Founder &amp; Sole Proprietor
                      </span>
                      <h3 class="mt-1 truncate font-display text-lg font-extrabold text-white">Hemant Kumar</h3>
                      <p class="text-xs text-slate-300">Digital Growth, Content &amp; Technical Lead</p>
                      <button type="button" data-navigate="founder"
                        class="mt-2 inline-flex items-center gap-1 text-xs font-bold text-amber-400 hover:text-amber-300">
                        <span>View Founder Profile</span>
                        <span>→</span>
                      </button>
                    </div>
                  </div>
                </div>
              </div>
            </div>

          </div>
        </div>
      </div>

      <!-- Core 3 Growth Packages Preview on Home -->
      <div class="mx-auto max-w-7xl px-4 py-14 sm:px-6 lg:px-8">
        <div class="flex flex-col justify-between gap-4 sm:flex-row sm:items-end">
          <div>
            <span class="text-xs font-bold uppercase tracking-wider text-amber-400">Local Business Growth</span>
            <h2 class="mt-1 font-display text-2xl font-extrabold text-white sm:text-3xl">
              Featured Local Growth Plans (Kathua 184101)
            </h2>
          </div>
          <button type="button" data-navigate="services"
            class="inline-flex items-center gap-1.5 text-sm font-bold text-amber-400 hover:text-amber-300">
            <span>See all 15 services &amp; pricing</span>
            <span>→</span>
          </button>
        </div>

        <div class="mt-8 grid grid-cols-1 gap-6 md:grid-cols-3">
          <div class="rounded-2xl border border-slate-800 bg-slate-900/80 p-6 shadow-card-dark">
            <span class="rounded-md bg-indigo-500/20 px-2.5 py-1 text-xs font-bold text-indigo-300">Google Maps</span>
            <h3 class="mt-3 font-display text-lg font-extrabold text-white">GMB Optimization</h3>
            <p class="mt-1 text-sm text-slate-400">Profile setup, Kathua location &amp; hours fix, review strategy.</p>
            <p class="mt-4 font-display text-2xl font-extrabold text-amber-400">₹999</p>
            <button type="button" data-inqu