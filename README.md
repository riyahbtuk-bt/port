<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Riya Singh | Portfolio</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        html { scroll-behavior: smooth; }
    </style>
</head>
<body class="bg-gray-50 text-gray-800 font-sans">

    <!-- Navigation Bar -->
    <nav class="bg-white shadow-md sticky top-0 z-50">
        <div class="max-w-6xl mx-auto px-4 py-4 flex flex-col sm:flex-row justify-between items-center gap-4">
            <a href="#" class="text-xl font-bold text-teal-600 tracking-wide">RIYA SINGH</a>
            <div class="flex space-x-6 text-sm font-medium text-gray-600">
                <a href="#about" class="hover:text-teal-600 transition">About</a>
                <a href="#education" class="hover:text-teal-600 transition">Education</a>
                <a href="#experience" class="hover:text-teal-600 transition">Experience</a>
                <a href="#skills" class="hover:text-teal-600 transition">Skills</a>
                <a href="#achievements" class="hover:text-teal-600 transition">Achievements</a>
            </div>
        </div>
    </nav>

    <!-- Hero / Header Section -->
    <header id="about" class="bg-gradient-to-br from-teal-50 to-emerald-50 py-20 px-4">
        <div class="max-w-4xl mx-auto text-center">
            <h1 class="text-4xl md:text-5xl font-extrabold text-gray-900 mb-4">Riya Singh</h1>
            <p class="text-lg md:text-xl text-teal-700 font-medium mb-6">Second Year Undergraduate | Department of Biotechnology, HBTU Kanpur</p>
            <p class="text-gray-600 max-w-2xl mx-auto leading-relaxed mb-8">
                Enthusiastic student pursuing a B.Tech in Biotechnology with a prior Diploma in Food Technology. 
                Eager to learn and contribute to innovative breakthroughs across biotech, food safety, and laboratory research operations.
            </p>
            
            <!-- Contact / Social Info -->
            <div class="flex flex-wrap justify-center gap-6 text-gray-600 text-sm md:text-base">
                <a href="mailto:riyasingh2759355@gmail.com" class="flex items-center gap-2 hover:text-teal-600 transition">
                    <i class="fa-solid fa-envelope text-teal-600"></i> riyasingh2759355@gmail.com
                </a>
                <a href="tel:+916386135504" class="flex items-center gap-2 hover:text-teal-600 transition">
                    <i class="fa-solid fa-phone text-teal-600"></i> +91-6386135504
                </a>
                <a href="https://in.linkedin.com/in/riya-singh-37b663384" target="_blank" class="flex items-center gap-2 hover:text-teal-600 transition">
                    <i class="fa-brands fa-linkedin text-teal-600"></i> LinkedIn Profile
                </a>
                <span class="flex items-center gap-2">
                    <i class="fa-solid fa-location-dot text-teal-600"></i> Siddharthnagar, UP, India
                </span>
            </div>
        </div>
    </header>

    <main class="max-w-5xl mx-auto px-4 py-16 space-y-20">

        <!-- Education Section -->
        <section id="education">
            <h2 class="text-2xl font-bold text-gray-900 border-b-2 border-teal-500 pb-2 mb-8 inline-block">Education</h2>
            <div class="space-y-6">
                <div class="bg-white p-6 rounded-lg shadow-sm border border-gray-100 flex flex-col md:flex-row justify-between gap-2">
                    <div>
                        <h3 class="text-lg font-bold text-gray-800">B.Tech (Biotechnology)</h3>
                        <p class="text-gray-600">Harcourt Butler Technical University, Kanpur UP</p>
                    </div>
                    <div class="md:text-right">
                        <span class="inline-block bg-teal-100 text-teal-800 text-xs px-2.5 py-1 rounded-full font-semibold mb-1">2025 - Present</span>
                        <p class="text-sm font-medium text-gray-500">Status: Pursuing</p>
                    </div>
                </div>

                <div class="bg-white p-6 rounded-lg shadow-sm border border-gray-100 flex flex-col md:flex-row justify-between gap-2">
                    <div>
                        <h3 class="text-lg font-bold text-gray-800">Diploma (Food Technology)</h3>
                        <p class="text-gray-600">M.M.I.T. Siddharthnagar (B.T.E.U.P.)</p>
                    </div>
                    <div class="md:text-right">
                        <span class="inline-block bg-teal-100 text-teal-800 text-xs px-2.5 py-1 rounded-full font-semibold mb-1">2022 - 2025</span>
                        <p class="text-sm font-medium text-teal-700">Score: 75.80%</p>
                    </div>
                </div>

                <div class="bg-white p-6 rounded-lg shadow-sm border border-gray-100 flex flex-col md:flex-row justify-between gap-2">
                    <div>
                        <h3 class="text-lg font-bold text-gray-800">Class X (CBSE)</h3>
                        <p class="text-gray-600">Christuraja Public Jr High School, Gorakhpur</p>
                    </div>
                    <div class="md:text-right">
                        <span class="inline-block bg-teal-100 text-teal-800 text-xs px-2.5 py-1 rounded-full font-semibold mb-1">Passout: 2022</span>
                        <p class="text-sm font-medium text-teal-700">Score: 73.80%</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Experience & Projects Section -->
        <section id="experience" class="grid md:grid-cols-2 gap-10">
            <!-- Internship -->
            <div>
                <h2 class="text-2xl font-bold text-gray-900 border-b-2 border-teal-500 pb-2 mb-6 inline-block">Internship & Training</h2>
                <div class="bg-white p-6 rounded-lg shadow-sm border border-gray-100 h-full">
                    <span class="text-xs font-semibold text-teal-600 uppercase tracking-wider">1-Month Industrial Training</span>
                    <h3 class="text-lg font-bold text-gray-800 mt-1">Trainee (Food Processing & Quality Control)</h3>
                    <p class="text-sm font-medium text-gray-600 mb-4">Basti Milk Producers Co-operative Union Ltd., UP</p>
                    <ul class="text-sm text-gray-600 space-y-2.5 list-disc pl-4">
                        <li>Focused on milk processing, pasteurization, and packaging operations.</li>
                        <li>Gained hands-on experience in quality testing, hygiene maintenance, and dairy product analysis.</li>
                        <li>Learned standard operating procedures (SOPs) for production efficiency and food safety compliance.</li>
                        <li>Collaborated with technical staff to understand supply chain, storage, and product quality management.</li>
                    </ul>
                </div>
            </div>

            <!-- Leadership / Volunteer -->
            <div>
                <h2 class="text-2xl font-bold text-gray-900 border-b-2 border-teal-500 pb-2 mb-6 inline-block">Responsibilities</h2>
                <div class="bg-white p-6 rounded-lg shadow-sm border border-gray-100 h-full">
                    <span class="text-xs font-semibold text-teal-600 uppercase tracking-wider">Community Outreach</span>
                    <h3 class="text-lg font-bold text-gray-800 mt-1">Volunteer - Sewa Pakhwada</h3>
                    <p class="text-sm font-medium text-gray-600 mb-4">Organized by Department of Biotechnology, HBTU</p>
                    <ul class="text-sm text-gray-600 space-y-2.5 list-disc pl-4">
                        <li>Participated in planning and executing community service and development activities during Sewa Pakhwada.</li>
                        <li>Coordinated a team of volunteers to ensure smooth execution of interactive outreach initiatives.</li>
                        <li>Engaged in vital awareness campaigns and departmental initiatives to actively promote social responsibility.</li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- Skills Section -->
        <section id="skills">
            <h2 class="text-2xl font-bold text-gray-900 border-b-2 border-teal-500 pb-2 mb-8 inline-block">Skills & Expertise</h2>
            <div class="grid sm:grid-cols-2 lg:grid-cols-4 gap-6">
                
                <!-- Skill Category 1 -->
                <div class="bg-white p-5 rounded-lg shadow-sm border-t-4 border-teal-500">
                    <h3 class="font-bold text-gray-800 mb-3 flex items-center gap-2"><i class="fa-solid fa-microscope text-teal-600"></i> Instrumentation</h3>
                    <div class="flex flex-wrap gap-2">
                        <span class="bg-gray-100 text-gray-700 text-xs px-2.5 py-1 rounded">Spectrophotometer</span>
                        <span class="bg-gray-100 text-gray-700 text-xs px-2.5 py-1 rounded">Centrifuge</span>
                        <span class="bg-gray-100 text-gray-700 text-xs px-2.5 py-1 rounded">Autoclave</span>
                        <span class="bg-gray-100 text-gray-700 text-xs px-2.5 py-1 rounded">Microscope</span>
                        <span class="bg-gray-100 text-gray-700 text-xs px-2.5 py-1 rounded">pH Meter</span>
                        <span class="bg-gray-100 text-gray-700 text-xs px-2.5 py-1 rounded">BOD/COD Analysis</span>
                    </div>
                </div>

                <!-- Skill Category 2 -->
                <div class="bg-white p-5 rounded-lg shadow-sm border-t-4 border-teal-500">
                    <h3 class="font-bold text-gray-800 mb-3 flex items-center gap-2"><i class="fa-solid fa-dna text-teal-600"></i> Biotech Ops</h3>
                    <div class="flex flex-wrap gap-2">
                        <span class="bg-gray-100 text-gray-700 text-xs px-2.5 py-1 rounded">PCR</span>
                        <span class="bg-gray-100 text-gray-700 text-xs px-2.5 py-1 rounded">ELISA</span>
                        <span class="bg-gray-100 text-gray-700 text-xs px-2.5 py-1 rounded">Microbial Culture</span>
                        <span class="bg-gray-100 text-gray-700 text-xs px-2.5 py-1 rounded">Cell Culture</span>
                        <span class="bg-gray-100 text-gray-700 text-xs px-2.5 py-1 rounded">Fermentation</span>
                        <span class="bg-gray-100 text-gray-700 text-xs px-2.5 py-1 rounded">Quality Assurance</span>
                    </div>
                </div>

                <!-- Skill Category 3 -->
                <div class="bg-white p-5 rounded-lg shadow-sm border-t-4 border-teal-500">
                    <h3 class="font-bold text-gray-800 mb-3 flex items-center gap-2"><i class="fa-solid fa-wheat-awn text-teal-600"></i> Food Tech</h3>
                    <div class="flex flex-wrap gap-2">
                        <span class="bg-gray-100 text-gray-700 text-xs px-2.5 py-1 rounded">Food Processing</span>
                        <span class="bg-gray-100 text-gray-700 text-xs px-2.5 py-1 rounded">Quality Control</span>
                        <span class="bg-gray-100 text-gray-700 text-xs px-2.5 py-1 rounded">HACCP Standards</span>
                        <span class="bg-gray-100 text-gray-700 text-xs px-2.5 py-1 rounded">Nutritional Analysis</span>
                        <span class="bg-gray-100 text-gray-700 text-xs px-2.5 py-1 rounded">Process Optimization</span>
                    </div>
                </div>

                <!-- Skill Category 4 -->
                <div class="bg-white p-5 rounded-lg shadow-sm border-t-4 border-teal-500">
                    <h3 class="font-bold text-gray-800 mb-3 flex items-center gap-2"><i class="fa-solid fa-laptop-code text-teal-600"></i> Data & Tools</h3>
                    <div class="flex flex-wrap gap-2">
                        <span class="bg-gray-100 text-gray-700 text-xs px-2.5 py-1 rounded">Data Analysis</span>
                        <span class="bg-gray-100 text-gray-700 text-xs px-2.5 py-1 rounded">Reporting</span>
                        <span class="bg-gray-100 text-gray-700 text-xs px-2.5 py-1 rounded">Documentation</span>
                        <span class="bg-gray-100 text-gray-700 text-xs px-2.5 py-1 rounded">LIMS</span>
                        <span class="bg-gray-100 text-gray-700 text-xs px-2.5 py-1 rounded">M.S. Office</span>
                        <span class="bg-gray-100 text-gray-700 text-xs px-2.5 py-1 rounded">Python (Basic)</span>
                    </div>
                </div>

            </div>
        </section>

        <!-- Achievements & Certifications -->
        <section id="achievements">
            <h2 class="text-2xl font-bold text-gray-900 border-b-2 border-teal-500 pb-2 mb-8 inline-block">Achievements & Certifications</h2>
            <div class="grid md:grid-cols-2 gap-6">
                <!-- Highlighted Achievement Card -->
                <div class="bg-gradient-to-r from-teal-600 to-emerald-600 text-white p-6 rounded-lg shadow-sm flex items-start gap-4">
                    <div class="bg-white/20 p-3 rounded-md text-xl">
                        <i class="fa-solid fa-trophy"></i>
                    </div>
                    <div>
                        <h3 class="font-bold text-lg">All India Rank-193</h3>
                        <p class="text-teal-100 text-sm mt-1">Achieved in CUET-UG 2025 (Secured admission for HBTU B.Tech program).</p>
                    </div>
                </div>

                <!-- Certifications Card -->
                <div class="bg-white p-6 rounded-lg shadow-sm border border-gray-100 flex items-start gap-4">
                    <div class="bg-teal-50 text-teal-600 p-3 rounded-md text-xl">
                        <i class="fa-solid fa-certificate"></i>
                    </div>
                    <div class="space-y-2">
                        <h3 class="font-bold text-gray-800 text-lg">Professional Certifications</h3>
                        <ul class="text-sm text-gray-600 list-disc pl-4 space-y-1">
                            <li>Industrial Training Certificate from Basti Milk Producers</li>
                            <li>Python Programming & Data Analysis Certification</li>
                            <li>Online Courses in Biotech, Molecular Biology, & Food Tech (Coursera/NPTEL/edX)</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-gray-900 text-gray-400 py-8 border-t border-gray-800 text-center text-sm">
        <p>&copy; 2026 Riya Singh. Built with Tailwind CSS.</p>
    </footer>

</body>
</html>
