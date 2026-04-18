<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>COBAS — Find Your Perfect Startup Partner</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&amp;family=Space+Grotesk:wght@500;600&amp;display=swap');
        
        :root {
            --primary-blue: #0A66C2;
            --primary-green: #10B981;
            --accent-orange: #F97316;
            --accent-purple: #8B5CF6;
        }
        
        body {
            font-family: 'Inter', system_ui, sans-serif;
        }
        
        .heading-font {
            font-family: 'Space Grotesk', sans-serif;
        }

        .hero-bg {
            background: linear-gradient(135deg, #0A66C2 0%, #10B981 100%);
        }

        .nav-link {
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }
        
        .nav-link:hover {
            color: #10B981;
            transform: translateY(-1px);
        }

        .card-hover {
            transition: all 0.4s cubic-bezier(0.4, 0.0, 0.2, 1);
        }
        
        .card-hover:hover {
            transform: translateY(-12px);
            box-shadow: 0 25px 50px -12px rgb(0 0 0 / 0.15);
        }

        .gradient-text {
            background: linear-gradient(90deg, #0A66C2, #10B981);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
    </style>
</head>
<body class="bg-zinc-50 text-zinc-800 overflow-x-hidden">
    <!-- NAVBAR -->
    <nav class="bg-white border-b border-zinc-100 sticky top-0 z-50">
        <div class="max-w-screen-2xl mx-auto">
            <div class="px-8 py-5 flex items-center justify-between">
                <!-- Logo -->
                <div class="flex items-center gap-x-3">
                    <div class="w-9 h-9 bg-gradient-to-br from-[#0A66C2] to-[#10B981] rounded-2xl flex items-center justify-center text-white font-bold text-2xl heading-font shadow-inner">C</div>
                    <div>
                        <span class="heading-font text-2xl font-semibold tracking-tighter">COBAS</span>
                    </div>
                </div>

                <!-- Menu -->
                <div class="hidden md:flex items-center gap-x-8 text-sm font-medium">
                    <a href="#home" onclick="navigateTo('home')" class="nav-link text-zinc-600 hover:text-zinc-900">Home</a>
                    <a href="#browse" onclick="navigateTo('browse')" class="nav-link text-zinc-600 hover:text-zinc-900">Find Partners</a>
                    <a href="#how" onclick="navigateTo('how')" class="nav-link text-zinc-600 hover:text-zinc-900">How it Works</a>
                    <a href="#ai" onclick="navigateTo('ai')" class="nav-link text-zinc-600 hover:text-zinc-900">Genius AI</a>
                    <a href="#pricing" onclick="navigateTo('pricing')" class="nav-link text-zinc-600 hover:text-zinc-900">Pricing</a>
                    <a href="#about" onclick="navigateTo('about')" class="nav-link text-zinc-600 hover:text-zinc-900">About</a>
                </div>

                <div class="flex items-center gap-x-4">
                    <button onclick="navigateTo('login')" 
                            class="px-6 py-2.5 text-sm font-semibold text-zinc-700 hover:text-zinc-900 transition-colors">
                        Log in
                    </button>
                    <button onclick="navigateTo('signup')" 
                            class="px-6 py-2.5 bg-[#0A66C2] hover:bg-[#08529b] text-white text-sm font-semibold rounded-2xl transition-all shadow-lg shadow-blue-200">
                        Join Free
                    </button>
                </div>
            </div>
        </div>
    </nav>

    <!-- HERO / HOME -->
    <section id="home" class="hero-bg text-white min-h-screen flex items-center relative overflow-hidden">
        <div class="absolute inset-0 bg-[radial-gradient(at_bottom_right,#ffffff10_0%,transparent_50%)]"></div>
        
        <div class="max-w-screen-2xl mx-auto px-8 pt-20 pb-16 grid md:grid-cols-2 gap-12 items-center relative z-10">
            <div class="space-y-8">
                <div class="inline-flex items-center gap-2 bg-white/20 backdrop-blur-md px-5 py-2 rounded-3xl text-sm font-medium">
                    <span class="relative flex h-3 w-3">
                        <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-white opacity-75"></span>
                        <span class="relative inline-flex rounded-full h-3 w-3 bg-white"></span>
                    </span>
                    Now connecting 12,450+ builders worldwide
                </div>
                
                <h1 class="heading-font text-6xl md:text-7xl leading-none font-semibold tracking-tighter">
                    Find your perfect<br>startup partner &amp;<br>collaborator
                </h1>
                
                <p class="text-xl text-white/90 max-w-lg">
                    COBAS connects ambitious founders, developers, marketers, and investors. 
                    Turn ideas into reality — together.
                </p>
                
                <div class="flex flex-wrap gap-4">
                    <button onclick="navigateTo('signup')" 
                            class="px-10 py-5 bg-white text-[#0A66C2] font-semibold text-lg rounded-3xl hover:shadow-2xl hover:scale-[1.03] transition-all flex items-center gap-x-3 group">
                        Join Free Today
                        <i class="fa-solid fa-arrow-right group-active:rotate-45 transition-transform"></i>
                    </button>
                    
                    <button onclick="navigateTo('browse')" 
                            class="px-8 py-5 border-2 border-white/70 hover:border-white font-medium text-lg rounded-3xl transition-all">
                        Browse People
                    </button>
                </div>
                
                <div class="flex items-center gap-x-8 text-sm pt-6">
                    <div class="flex -space-x-4">
                        <div class="w-8 h-8 bg-white rounded-2xl border-2 border-[#0A66C2] overflow-hidden">
                            <img src="https://picsum.photos/id/64/128/128" alt="" class="w-full h-full object-cover">
                        </div>
                        <div class="w-8 h-8 bg-white rounded-2xl border-2 border-[#0A66C2] overflow-hidden">
                            <img src="https://picsum.photos/id/201/128/128" alt="" class="w-full h-full object-cover">
                        </div>
                        <div class="w-8 h-8 bg-white rounded-2xl border-2 border-[#0A66C2] overflow-hidden">
                            <img src="https://picsum.photos/id/201/128/128" alt="" class="w-full h-full object-cover">
                        </div>
                    </div>
                    <div class="text-white/80 text-sm">
                        Trusted by builders from<br>
                        <span class="font-semibold text-white">Y Combinator • Techstars • 50+ countries</span>
                    </div>
                </div>
            </div>
            
            <!-- Hero visual -->
            <div class="relative hidden md:block">
                <div class="bg-white/10 backdrop-blur-3xl border border-white/30 rounded-3xl p-3 shadow-2xl">
                    <div class="bg-white rounded-3xl overflow-hidden shadow-inner">
                        <!-- Mock dashboard -->
                        <div class="p-8">
                            <div class="flex justify-between items-center mb-8">
                                <div>
                                    <div class="text-zinc-400 text-xs tracking-widest">MATCH SCORE</div>
                                    <div class="text-5xl heading-font font-semibold text-emerald-600">94%</div>
                                </div>
                                <div class="text-right">
                                    <div class="flex items-center gap-x-2 text-emerald-600">
                                        <i class="fa-solid fa-circle-check"></i>
                                        <span class="font-medium">Perfect Fit</span>
                                    </div>
                                </div>
                            </div>
                            
                            <div class="space-y-6">
                                <!-- Sample match cards -->
                                <div class="flex gap-5 bg-zinc-50 rounded-2xl p-5">
                                    <div class="w-14 h-14 bg-orange-100 rounded-2xl flex-none overflow-hidden">
                                        <img src="https://picsum.photos/id/201/128/128" alt="Sarah Chen" class="w-full h-full object-cover">
                                    </div>
                                    <div class="flex-1 min-w-0">
                                        <div class="flex justify-between">
                                            <div>
                                                <div class="font-semibold">Sarah Chen</div>
                                                <div class="text-zinc-500 text-sm">Full-stack Developer • Ex-Notion</div>
                                            </div>
                                            <div class="text-emerald-500 font-medium text-sm">Co-founder</div>
                                        </div>
                                        <div class="mt-3 text-sm text-zinc-600 line-clamp-2">
                                            Looking for a technical co-founder passionate about AI tools for non-technical founders.
                                        </div>
                                        <div class="flex gap-2 mt-4">
                                            <span class="text-[10px] bg-white px-3 py-1 rounded-full border">React</span>
                                            <span class="text-[10px] bg-white px-3 py-1 rounded-full border">AI/ML</span>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- Floating badges -->
                <div class="absolute -top-6 -left-6 bg-white rounded-3xl shadow-xl px-6 py-4 text-sm flex items-center gap-x-3">
                    <div class="text-2xl">🚀</div>
                    <div>
                        <div class="font-semibold text-zinc-900">New match found</div>
                        <div class="text-emerald-600 text-xs">2 minutes ago</div>
                    </div>
                </div>
                
                <div class="absolute -bottom-8 right-12 bg-white rounded-3xl shadow-2xl p-5 max-w-[220px]">
                    <div class="flex items-center gap-x-4">
                        <i class="fa-solid fa-handshake text-4xl text-[#10B981]"></i>
                        <div class="text-sm">
                            <span class="block font-medium">Deal closed</span>
                            <span class="text-zinc-500">with Alex Rivera • Marketing Partner</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        
        <div class="absolute bottom-10 left-1/2 hidden md:flex flex-col items-center">
            <div class="text-white/70 text-xs tracking-widest mb-2">SCROLL TO EXPLORE</div>
            <i class="fa-solid fa-chevron-down animate-bounce"></i>
        </div>
    </section>

    <!-- TRUST BAR -->
    <div class="bg-white py-6 border-b">
        <div class="max-w-screen-2xl mx-auto px-8">
            <div class="flex flex-wrap justify-center md:justify-between items-center gap-x-12 gap-y-6 opacity-75">
                <div class="flex items-center gap-x-8 text-zinc-400 text-xl">
                    <i class="fa-brands fa-y-combinator"></i>
                    <span class="font-medium text-base">Y Combinator</span>
                </div>
                <div class="h-8 w-px bg-zinc-200"></div>
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/44/BBC.svg/2560px-BBC.svg.png" alt="BBC" class="h-6">
                <div class="h-8 w-px bg-zinc-200"></div>
                <span class="font-semibold text-zinc-500">TechCrunch</span>
                <div class="h-8 w-px bg-zinc-200"></div>
                <span class="font-medium">Product Hunt</span>
            </div>
        </div>
    </div>

    <!-- BROWSE PEOPLE / FIND PARTNERS -->
    <section id="browse" class="py-24 bg-white">
        <div class="max-w-screen-2xl mx-auto px-8">
            <div class="flex flex-col md:flex-row justify-between items-end mb-12">
                <div>
                    <span class="uppercase text-[#10B981] text-sm font-medium tracking-widest">Discover talent</span>
                    <h2 class="heading-font text-5xl font-semibold tracking-tighter mt-2">Find the right people</h2>
                </div>
                <a href="#" onclick="navigateTo('browse')" class="mt-6 md:mt-0 inline-flex items-center gap-x-2 text-[#0A66C2] font-medium group">
                    Browse all profiles 
                    <span class="group-hover:translate-x-1 transition">→</span>
                </a>
            </div>
            
            <!-- Filters -->
            <div class="flex flex-wrap gap-3 mb-10">
                <div class="bg-white border border-zinc-200 px-5 py-3 rounded-3xl text-sm flex items-center gap-x-2 shadow-sm">
                    <i class="fa-solid fa-magnifying-glass"></i>
                    <input type="text" placeholder="Search by skill or role..." class="bg-transparent outline-none flex-1 min-w-[240px]">
                </div>
                
                <div onclick="fakeFilter(this)" class="cursor-pointer border border-zinc-200 hover:border-[#10B981] px-6 py-3 rounded-3xl text-sm font-medium transition-colors">Developer</div>
                <div onclick="fakeFilter(this)" class="cursor-pointer border border-zinc-200 hover:border-[#10B981] px-6 py-3 rounded-3xl text-sm font-medium transition-colors">Marketer</div>
                <div onclick="fakeFilter(this)" class="cursor-pointer border border-zinc-200 hover:border-[#10B981] px-6 py-3 rounded-3xl text-sm font-medium transition-colors">Co-founder</div>
                <div onclick="fakeFilter(this)" class="cursor-pointer border border-zinc-200 hover:border-[#10B981] px-6 py-3 rounded-3xl text-sm font-medium transition-colors">Investor</div>
                <div onclick="fakeFilter(this)" class="cursor-pointer border border-zinc-200 hover:border-[#10B981] px-6 py-3 rounded-3xl text-sm font-medium transition-colors">AI / ML</div>
            </div>
            
            <!-- Profile Grid -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-8">
                <!-- Profile 1 -->
                <div class="card-hover bg-white border border-zinc-100 rounded-3xl overflow-hidden">
                    <div class="h-52 bg-gradient-to-br from-orange-400 to-purple-500 relative">
                        <img src="https://picsum.photos/id/201/600/400" alt="Alex Rivera" class="absolute inset-0 w-full h-full object-cover opacity-90">
                        <div class="absolute top-6 right-6 bg-white text-emerald-600 text-xs font-semibold px-4 py-1 rounded-3xl shadow">Open to collab</div>
                    </div>
                    <div class="p-7">
                        <div class="flex justify-between items-start">
                            <div>
                                <div class="font-semibold text-xl">Alex Rivera</div>
                                <div class="text-zinc-500">Growth Marketer • Previously at Stripe</div>
                            </div>
                            <div class="text-right">
                                <div class="text-3xl">🇲🇽</div>
                            </div>
                        </div>
                        
                        <div class="mt-6 flex flex-wrap gap-2">
                            <span class="text-xs bg-zinc-100 px-4 py-2 rounded-3xl">SEO</span>
                            <span class="text-xs bg-zinc-100 px-4 py-2 rounded-3xl">Content</span>
                            <span class="text-xs bg-zinc-100 px-4 py-2 rounded-3xl">Growth</span>
                        </div>
                        
                        <div class="mt-8 text-sm text-zinc-600 line-clamp-3">
                            Building the next generation of creator economy tools. Looking for a technical co-founder who loves beautiful interfaces.
                        </div>
                        
                        <div class="mt-8 pt-8 border-t flex justify-between items-center text-xs">
                            <div class="flex items-center gap-x-1 text-emerald-600">
                                <i class="fa-solid fa-fire"></i>
                                <span>92% match</span>
                            </div>
                            <button onclick="alert('Profile view opened (demo)')" 
                                    class="text-[#0A66C2] font-medium hover:underline">View full profile →</button>
                        </div>
                    </div>
                </div>
                
                <!-- Profile 2 -->
                <div class="card-hover bg-white border border-zinc-100 rounded-3xl overflow-hidden">
                    <div class="h-52 bg-gradient-to-br from-blue-500 to-emerald-400 relative">
                        <img src="https://picsum.photos/id/64/600/400" alt="Priya Sharma" class="absolute inset-0 w-full h-full object-cover opacity-90">
                    </div>
                    <div class="p-7">
                        <div class="flex justify-between items-start">
                            <div>
                                <div class="font-semibold text-xl">Priya Sharma</div>
                                <div class="text-zinc-500">Full Stack Engineer • Ex-OpenAI</div>
                            </div>
                            <div class="text-right">
                                <div class="text-3xl">🇮🇳</div>
                            </div>
                        </div>
                        
                        <div class="mt-6 flex flex-wrap gap-2">
                            <span class="text-xs bg-zinc-100 px-4 py-2 rounded-3xl">Python</span>
                            <span class="text-xs bg-zinc-100 px-4 py-2 rounded-3xl">LLMs</span>
                            <span class="text-xs bg-zinc-100 px-4 py-2 rounded-3xl">TypeScript</span>
                        </div>
                        
                        <div class="mt-8 text-sm text-zinc-600 line-clamp-3">
                            Passionate about making AI accessible. Currently building an open-source agent framework. Seeking marketing &amp; business partner.
                        </div>
                        
                        <div class="mt-8 pt-8 border-t flex justify-between items-center text-xs">
                            <div class="flex items-center gap-x-1 text-emerald-600">
                                <i class="fa-solid fa-fire"></i>
                                <span>89% match</span>
                            </div>
                            <button onclick="alert('Profile view opened (demo)')" 
                                    class="text-[#0A66C2] font-medium hover:underline">View full profile →</button>
                        </div>
                    </div>
                </div>
                
                <!-- More profiles would go here in real site -->
            </div>
        </div>
    </section>

    <!-- HOW IT WORKS -->
    <section id="how" class="py-24 bg-zinc-900 text-white">
        <div class="max-w-screen-2xl mx-auto px-8">
            <div class="text-center max-w-xl mx-auto mb-16">
                <span class="text-emerald-400 text-sm font-medium">3 SIMPLE STEPS</span>
                <h2 class="heading-font text-5xl font-semibold tracking-tighter mt-3">From idea to launched startup — faster</h2>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-zinc-800/50 border border-zinc-700 rounded-3xl p-10">
                    <div class="w-12 h-12 bg-white/10 rounded-2xl flex items-center justify-center text-3xl mb-8">1</div>
                    <h3 class="text-2xl font-semibold mb-4">Create your profile</h3>
                    <p class="text-zinc-400">Tell the community about your skills, current project, and the big dream you're chasing. Completely free.</p>
                </div>
                <div class="bg-zinc-800/50 border border-zinc-700 rounded-3xl p-10">
                    <div class="w-12 h-12 bg-white/10 rounded-2xl flex items-center justify-center text-3xl mb-8">2</div>
                    <h3 class="text-2xl font-semibold mb-4">Discover &amp; match</h3>
                    <p class="text-zinc-400">Use smart filters or our AI recommendations to find people who complement your strengths perfectly.</p>
                </div>
                <div class="bg-zinc-800/50 border border-zinc-700 rounded-3xl p-10 relative">
                    <div class="w-12 h-12 bg-white/10 rounded-2xl flex items-center justify-center text-3xl mb-8">3</div>
                    <h3 class="text-2xl font-semibold mb-4">Connect &amp; build</h3>
                    <p class="text-zinc-400">Message your matches (Premium), make agreements, and turn your combined vision into reality.</p>
                    <div class="absolute -top-4 -right-4 bg-[#F97316] text-white text-xs font-bold px-6 py-2 rounded-3xl rotate-12 shadow">Premium messaging</div>
                </div>
            </div>
        </div>
    </section>

    <!-- GENIUS AI -->
    <section id="ai" class="py-24 bg-white">
        <div class="max-w-screen-2xl mx-auto px-8">
            <div class="grid lg:grid-cols-12 gap-16 items-center">
                <div class="lg:col-span-5">
                    <div class="sticky top-24">
                        <div class="inline-flex items-center gap-x-2 bg-emerald-100 text-emerald-700 text-sm font-semibold px-5 py-2 rounded-3xl">
                            <i class="fa-solid fa-sparkles"></i>
                            POWERED BY MULTIPLE AIs
                        </div>
                        <h2 class="heading-font text-5xl font-semibold tracking-tighter mt-6 leading-none">Meet Genius AI — your startup co-pilot</h2>
                        <p class="mt-6 text-xl text-zinc-600 max-w-md">
                            Get personalized action plans, partner recommendations, honest feedback, and insights from the world's best models.
                        </p>
                        
                        <div class="mt-12 flex flex-wrap gap-4">
                            <div class="flex items-center gap-x-3 bg-zinc-100 px-5 py-3 rounded-3xl">
                                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/04/ChatGPT_logo.svg/1200px-ChatGPT_logo.svg.png" alt="ChatGPT" class="h-6">
                            </div>
                            <div class="flex items-center gap-x-3 bg-zinc-100 px-5 py-3 rounded-3xl">
                                <span class="text-blue-600 font-bold">G</span><span class="font-medium">emini</span>
                            </div>
                            <div class="flex items-center gap-x-3 bg-zinc-100 px-5 py-3 rounded-3xl">
                                <span class="text-purple-600">Claude</span>
                            </div>
                            <div class="flex items-center gap-x-3 bg-zinc-100 px-5 py-3 rounded-3xl">
                                Grok
                            </div>
                        </div>
                        
                        <button onclick="alert('Genius AI demo would open here')" 
                                class="mt-10 flex items-center gap-x-4 group">
                            <div class="w-14 h-14 bg-gradient-to-br from-purple-500 to-pink-500 rounded-2xl flex items-center justify-center text-white text-3xl shadow-inner">✦</div>
                            <div>
                                <div class="font-semibold group-hover:underline">Try Genius AI now →</div>
                                <div class="text-sm text-zinc-500">Available on Premium plans</div>
                            </div>
                        </button>
                    </div>
                </div>
                
                <div class="lg:col-span-7 bg-zinc-900 rounded-3xl p-8 text-white">
                    <div class="bg-zinc-800 rounded-3xl p-8">
                        <div class="flex items-center gap-x-3 mb-8">
                            <div class="text-emerald-400">
                                <i class="fa-solid fa-robot text-2xl"></i>
                            </div>
                            <div class="font-medium">Genius AI</div>
                        </div>
                        
                        <div class="space-y-10">
                            <div class="bg-zinc-900 rounded-2xl p-6">
                                <div class="text-xs uppercase tracking-widest text-zinc-400 mb-2">You asked</div>
                                <div class="text-lg">"Help me create a 30-day launch plan for my AI productivity tool"</div>
                            </div>
                            
                            <div>
                                <div class="flex items-center gap-x-3 text-emerald-400 mb-4">
                                    <i class="fa-solid fa-sparkles"></i>
                                    <span class="font-medium">Genius AI Response</span>
                                </div>
                                <div class="text-zinc-300 leading-relaxed">
                                    Here's your personalized 30-day action plan:<br><br>
                                    • Week 1: Validate with 50 potential users via targeted LinkedIn outreach<br>
                                    • Week 2: Build MVP using no-code + integrate Grok API for advanced features<br>
                                    • Week 3: Find your first co-marketer on COBAS<br>
                                    ...and 12 more detailed steps
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- MY PROFILE EXAMPLE -->
    <section class="py-24 bg-zinc-100">
        <div class="max-w-screen-2xl mx-auto px-8">
            <div class="max-w-2xl mx-auto bg-white rounded-3xl shadow-xl overflow-hidden">
                <div class="h-56 bg-gradient-to-r from-[#0A66C2] via-[#10B981] to-[#F97316]"></div>
                
                <div class="px-10 -mt-12 relative">
                    <div class="flex justify-between">
                        <div class="w-28 h-28 bg-white rounded-3xl shadow-xl overflow-hidden border-4 border-white">
                            <img src="https://picsum.photos/id/201/300/300" alt="Your profile" class="w-full h-full object-cover">
                        </div>
                        <button class="self-end mb-4 px-8 py-3 bg-zinc-900 text-white rounded-3xl text-sm font-medium">Edit profile</button>
                    </div>
                    
                    <div class="mt-6">
                        <div class="font-semibold text-3xl">Jordan Kim</div>
                        <div class="text-zinc-500">Product Designer &amp; Aspiring Founder • Seoul / Remote</div>
                    </div>
                    
                    <div class="mt-10 grid grid-cols-2 gap-8">
                        <div>
                            <div class="uppercase text-xs text-zinc-500 mb-3 tracking-wider">Current Project</div>
                            <div class="font-medium">NoCodeFlow — Visual workflow builder for non-technical teams</div>
                        </div>
                        <div>
                            <div class="uppercase text-xs text-zinc-500 mb-3 tracking-wider">Big Dream</div>
                            <div class="font-medium">"Democratize automation so every small business can compete with giants"</div>
                        </div>
                    </div>
                    
                    <div class="my-12 border-t pt-12">
                        <div class="uppercase text-xs text-zinc-500 mb-4">Skills &amp; Interests</div>
                        <div class="flex flex-wrap gap-3">
                            <span class="px-6 py-3 bg-zinc-100 rounded-3xl text-sm">Figma</span>
                            <span class="px-6 py-3 bg-zinc-100 rounded-3xl text-sm">Webflow</span>
                            <span class="px-6 py-3 bg-zinc-100 rounded-3xl text-sm">User Research</span>
                            <span class="px-6 py-3 bg-zinc-100 rounded-3xl text-sm">Startup Storytelling</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- PRICING -->
    <section id="pricing" class="py-24 bg-white">
        <div class="max-w-screen-2xl mx-auto px-8">
            <div class="text-center mb-16">
                <h2 class="heading-font text-5xl font-semibold tracking-tighter">Simple, transparent pricing</h2>
                <p class="mt-4 text-xl text-zinc-600">Discovery is always free. Premium unlocks real conversations and AI superpowers.</p>
            </div>
            
            <div class="grid md:grid-cols-2 max-w-4xl mx-auto gap-8">
                <!-- Free -->
                <div class="border border-zinc-200 rounded-3xl p-10">
                    <div class="uppercase text-xs font-semibold tracking-widest text-zinc-500">Starter</div>
                    <div class="mt-6 flex items-baseline">
                        <span class="text-7xl font-semibold heading-font">$0</span>
                        <span class="text-zinc-400 ml-3">forever</span>
                    </div>
                    <ul class="mt-10 space-y-6 text-zinc-600">
                        <li class="flex gap-x-4"><i class="fa-solid fa-check text-emerald-500 mt-1"></i> Browse all public profiles</li>
                        <li class="flex gap-x-4"><i class="fa-solid fa-check text-emerald-500 mt-1"></i> Create your own profile</li>
                        <li class="flex gap-x-4"><i class="fa-solid fa-check text-emerald-500 mt-1"></i> Basic matching recommendations</li>
                        <li class="flex gap-x-4"><i class="fa-solid fa-check text-emerald-500 mt-1"></i> Community feed</li>
                    </ul>
                    <button onclick="navigateTo('signup')" 
                            class="w-full mt-12 py-7 border-2 border-zinc-900 rounded-3xl font-semibold">Get started free</button>
                </div>
                
                <!-- Premium -->
                <div class="border-2 border-[#0A66C2] rounded-3xl p-10 relative">
                    <div class="absolute -top-4 right-8 bg-[#0A66C2] text-white text-xs font-bold px-8 py-2 rounded-3xl">MOST POPULAR</div>
                    
                    <div class="uppercase text-xs font-semibold tracking-widest text-[#0A66C2]">Premium</div>
                    <div class="mt-6 flex items-baseline">
                        <span class="text-7xl font-semibold heading-font">$8.97</span>
                        <span class="text-zinc-400 ml-3">/month</span>
                    </div>
                    <div class="text-sm text-emerald-600 font-medium">or $98.70/year — save 8%</div>
                    
                    <ul class="mt-10 space-y-6 text-zinc-700">
                        <li class="flex gap-x-4"><i class="fa-solid fa-check text-emerald-500 mt-1"></i> Everything in Free</li>
                        <li class="flex gap-x-4"><i class="fa-solid fa-check text-emerald-500 mt-1"></i> <strong>Unlimited direct messaging</strong></li>
                        <li class="flex gap-x-4"><i class="fa-solid fa-check text-emerald-500 mt-1"></i> Full Genius AI access</li>
                        <li class="flex gap-x-4"><i class="fa-solid fa-check text-emerald-500 mt-1"></i> Advanced AI partner matching</li>
                        <li class="flex gap-x-4"><i class="fa-solid fa-check text-emerald-500 mt-1"></i> Priority visibility in search</li>
                        <li class="flex gap-x-4"><i class="fa-solid fa-check text-emerald-500 mt-1"></i> Deal templates &amp; contracts</li>
                    </ul>
                    <button onclick="alert('Checkout flow would start here')" 
                            class="w-full mt-12 py-7 bg-[#0A66C2] text-white rounded-3xl font-semibold shadow-xl">Upgrade to Premium</button>
                </div>
            </div>
        </div>
    </section>

    <!-- ABOUT -->
    <section id="about" class="py-24 bg-zinc-900 text-white">
        <div class="max-w-screen-2xl mx-auto px-8">
            <div class="max-w-3xl">
                <span class="text-emerald-400 text-sm font-medium">OUR MISSION</span>
                <h2 class="heading-font text-6xl font-semibold tracking-tighter leading-none mt-6">
                    Connecting ambitious builders to turn ideas into reality — together
                </h2>
                <p class="mt-12 text-xl text-zinc-300">
                    COBAS was born from the frustration of building alone. We believe the best companies are built by complementary teams who share vision and drive. 
                    Our platform makes finding those perfect collaborators simple, safe, and inspiring.
                </p>
                
                <div class="mt-16 grid grid-cols-3 gap-8">
                    <div>
                        <div class="text-5xl font-semibold text-emerald-400">12k+</div>
                        <div class="text-zinc-400 mt-3">Active builders</div>
                    </div>
                    <div>
                        <div class="text-5xl font-semibold text-emerald-400">430+</div>
                        <div class="text-zinc-400 mt-3">Successful matches</div>
                    </div>
                    <div>
                        <div class="text-5xl font-semibold text-emerald-400">47</div>
                        <div class="text-zinc-400 mt-3">Countries represented</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- FOOTER / CTA -->
    <footer class="bg-zinc-950 text-white py-20">
        <div class="max-w-screen-2xl mx-auto px-8">
            <div class="flex flex-col md:flex-row justify-between gap-y-16">
                <div>
                    <div class="flex items-center gap-x-3">
                        <div class="w-9 h-9 bg-gradient-to-br from-[#0A66C2] to-[#10B981] rounded-2xl flex items-center justify-center text-white font-bold text-2xl heading-font">C</div>
                        <span class="heading-font text-3xl font-semibold tracking-tighter">COBAS</span>
                    </div>
                    <div class="mt-8 max-w-xs text-zinc-400">
                        The modern collaboration platform for startup founders and business builders worldwide.
                    </div>
                    <div class="mt-12 text-xs text-zinc-500">© 2026 COBAS Inc. All rights reserved.</div>
                </div>
                
                <div class="grid grid-cols-2 md:grid-cols-4 gap-x-16 gap-y-12">
                    <div>
                        <div class="font-medium mb-6">Platform</div>
                        <div class="space-y-4 text-sm text-zinc-400">
                            <div>Browse People</div>
                            <div>Genius AI</div>
                            <div>Pricing</div>
                        </div>
                    </div>
                    <div>
                        <div class="font-medium mb-6">Company</div>
                        <div class="space-y-4 text-sm text-zinc-400">
                            <div>About Us</div>
                            <div>Blog &amp; Stories</div>
                            <div>Contact</div>
                        </div>
                    </div>
                    <div>
                        <div class="font-medium mb-6">Legal</div>
                        <div class="space-y-4 text-sm text-zinc-400">
                            <div>Privacy</div>
                            <div>Terms</div>
                            <div>Safety</div>
                        </div>
                    </div>
                    <div>
                        <div class="font-medium mb-6">Community</div>
                        <div class="flex gap-x-5 text-2xl">
                            <i class="fa-brands fa-x-twitter cursor-pointer"></i>
                            <i class="fa-brands fa-linkedin cursor-pointer"></i>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="mt-24 pt-8 border-t border-white/10 text-center text-xs text-zinc-500">
                Discovery &amp; browsing on COBAS is completely free. Messaging and advanced AI features require a Premium subscription.
            </div>
        </div>
    </footer>

    <script>
        // Tailwind script already included via CDN
        function navigateTo(section) {
            if (section === 'signup' || section === 'login') {
                alert(`✅ ${section === 'signup' ? 'Sign up' : 'Login'} flow would open here.\n\nIn a real build this would lead to authentication.`);
                return;
            }
            if (['home','browse','how','ai','pricing','about'].includes(section)) {
                document.getElementById(section).scrollIntoView({ behavior: 'smooth' });
            } else {
                alert('Page navigation demo: ' + section);
            }
        }
        
        function fakeFilter(el) {
            el.style.borderColor = '#10B981';
            el.style.backgroundColor = '#ecfdf5';
            setTimeout(() => {
                alert('Filter applied! Showing more relevant profiles (demo).');
            }, 300);
        }
        
        // Keyboard shortcut hint
        console.log('%cCOBAS demo ready 🚀\nTry clicking the buttons and sections!', 'color:#10B981; font-family:monospace');
        
        // Simple scroll progress for fun
        window.addEventListener('scroll', () => {
            if (window.scrollY > 300) {
                document.querySelector('nav').classList.add('shadow-sm');
            }
        });
    </script>
</body>
</html>
