<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vishanth Ashok | Product & Strategy</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #111827; /* bg-gray-900 */
            color: #d1d5db; /* text-gray-300 */
        }
        .glass-effect {
            background: rgba(31, 41, 55, 0.5); /* bg-gray-800 with opacity */
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        .accent-color { color: #38bdf8; } /* text-sky-400 */
        .accent-bg { background-color: #38bdf8; } /* bg-sky-400 */
        .accent-border { border-color: #38bdf8; } /* border-sky-400 */
    </style>
</head>
<body class="antialiased">

    <!-- Header -->
    <header class="fixed top-0 left-0 right-0 z-50 glass-effect">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="text-xl font-bold text-white">Vishanth Ashok</a>
            <nav class="hidden md:flex space-x-8">
                <a href="#about" class="hover:text-sky-400 transition-colors duration-300">About</a>
                <a href="#experience" class="hover:text-sky-400 transition-colors duration-300">Experience</a>
                <a href="#projects" class="hover:text-sky-400 transition-colors duration-300">Projects</a>
                <a href="#skills" class="hover:text-sky-400 transition-colors duration-300">Skills</a>
                <a href="#contact" class="hover:text-sky-400 transition-colors duration-300">Contact</a>
            </nav>
            <button id="mobile-menu-button" class="md:hidden text-white">
                <i data-lucide="menu"></i>
            </button>
        </div>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-gray-800">
            <a href="#about" class="block py-2 px-6 text-center hover:bg-gray-700">About</a>
            <a href="#experience" class="block py-2 px-6 text-center hover:bg-gray-700">Experience</a>
            <a href="#projects" class="block py-2 px-6 text-center hover:bg-gray-700">Projects</a>
            <a href="#skills" class="block py-2 px-6 text-center hover:bg-gray-700">Skills</a>
            <a href="#contact" class="block py-2 px-6 text-center hover:bg-gray-700">Contact</a>
        </div>
    </header>

    <main class="container mx-auto px-6">

        <!-- Hero Section -->
        <section id="home" class="min-h-screen flex flex-col justify-center items-start pt-24 md:pt-0">
            <div class="max-w-3xl">
                <h1 class="text-4xl md:text-6xl font-extrabold text-white leading-tight">
                    Aspiring <span class="accent-color">Product Manager</span> with a passion for data-driven strategy.
                </h1>
                <p class="mt-6 text-lg md:text-xl text-gray-400">
                    Economics & Mathematics student at UT Austin, leveraging analytical skills to build impactful products. I thrive at the intersection of technology, business, and user experience.
                </p>
                <div class="mt-10 flex flex-col sm:flex-row gap-4">
                    <a href="#contact" class="px-8 py-3 bg-sky-500 text-white font-semibold rounded-lg hover:bg-sky-600 transition-all duration-300 text-center">Get In Touch</a>
                    <!-- IMPORTANT: Replace 'Vishanth Ashok G.pdf' with the actual path to your resume file in the repo -->
                    <a href="./Vishanth Ashok G.pdf" download class="px-8 py-3 bg-gray-700 text-white font-semibold rounded-lg hover:bg-gray-600 transition-all duration-300 text-center">Download Resume</a>
                </div>
            </div>
        </section>

        <!-- About Section -->
        <section id="about" class="py-20">
            <h2 class="text-3xl font-bold text-center text-white mb-12">About Me</h2>
            <div class="flex flex-col md:flex-row items-center gap-10 md:gap-16">
                <div class="w-full md:w-2/3">
                    <p class="mb-4">
                        I'm a highly motivated student at The University of Texas at Austin, pursuing a double major in Economics and Mathematics. My academic background has equipped me with a strong quantitative and analytical toolkit, which I've applied in various internships focused on data analysis, financial modeling, and investment strategy.
                    </p>
                    <p class="mb-4">
                        My passion for technology and problem-solving led me to pursue and achieve an <span class="text-white font-semibold">IBM Product Management Certification</span>. This experience solidified my interest in product development, where I learned to translate customer pain points into actionable product roadmaps, prioritize features based on business impact, and collaborate within an agile framework using tools like Jira and Miro.
                    </p>
                    <p>
                        I am eager to apply my unique blend of analytical rigor and product intuition to a dynamic product team, helping to create solutions that are not only technically sound but also strategically successful and user-centric.
                    </p>
                </div>
                 <div class="w-full md:w-1/3 p-4">
                    <div class="glass-effect rounded-xl p-6 text-center">
                         <i data-lucide="target" class="mx-auto h-16 w-16 accent-color mb-4"></i>
                         <h3 class="text-xl font-bold text-white">Core Philosophy</h3>
                         <p class="mt-2 text-gray-400 text-sm">
                             Use data to ask the right questions, and empathy to build the right answers.
                         </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Experience Section -->
        <section id="experience" class="py-20">
            <h2 class="text-3xl font-bold text-center text-white mb-16">Career Journey</h2>
            <div class="relative border-l-2 border-gray-700 ml-4 md:ml-0">
                <!-- Timeline Item -->
                <div class="mb-10 ml-8">
                    <span class="absolute flex items-center justify-center w-8 h-8 bg-sky-500 rounded-full -left-4 ring-8 ring-gray-900">
                        <i data-lucide="briefcase" class="w-4 h-4 text-white"></i>
                    </span>
                    <h3 class="flex items-center mb-1 text-lg font-semibold text-white">IBM Certified Product Manager <span class="accent-bg text-blue-800 text-sm font-medium mr-2 px-2.5 py-0.5 rounded ml-3">Certification</span></h3>
                    <time class="block mb-2 text-sm font-normal leading-none text-gray-500">Completed August 2025</time>
                    <ul class="list-disc list-inside mt-2 text-gray-400 space-y-1">
                        <li>Designed and presented a product roadmap for a mock SaaS platform.</li>
                        <li>Mastered agile tools like Jira, Trello, and Miro for product tracking.</li>
                        <li>Utilized data-driven decision-making via cohort analysis and customer feedback.</li>
                    </ul>
                </div>
                <!-- Timeline Item -->
                <div class="mb-10 ml-8">
                    <span class="absolute flex items-center justify-center w-8 h-8 bg-gray-800 rounded-full -left-4 ring-8 ring-gray-900 border border-sky-400">
                        <i data-lucide="bar-chart-3" class="w-4 h-4 accent-color"></i>
                    </span>
                    <h3 class="text-lg font-semibold text-white">PNTHR Funds</h3>
                    <p class="text-md font-normal text-gray-400">Investment and Data Analyst Intern</p>
                    <time class="block mb-2 text-sm font-normal leading-none text-gray-500">March 2025 - May 2025</time>
                    <ul class="list-disc list-inside mt-2 text-gray-400 space-y-1">
                        <li>Automated portfolio tracking, reducing reporting time by 80%.</li>
                        <li>Designed Python-based risk models to simulate macroeconomic scenarios.</li>
                        <li>Improved stress-testing accuracy by 30% through data modeling.</li>
                    </ul>
                </div>
                <!-- Timeline Item -->
                <div class="mb-10 ml-8">
                     <span class="absolute flex items-center justify-center w-8 h-8 bg-gray-800 rounded-full -left-4 ring-8 ring-gray-900 border border-sky-400">
                        <i data-lucide="lightbulb" class="w-4 h-4 accent-color"></i>
                    </span>
                    <h3 class="text-lg font-semibold text-white">Fund Launch</h3>
                     <p class="text-md font-normal text-gray-400">Fund Management Intern</p>
                    <time class="block mb-2 text-sm font-normal leading-none text-gray-500">Jan 2025 - March 2025</time>
                     <ul class="list-disc list-inside mt-2 text-gray-400 space-y-1">
                        <li>Improved deal sourcing efficiency by 40% by optimizing CRM pipeline.</li>
                        <li>Built LBO models and conducted financial analysis for 7+ acquisition targets.</li>
                    </ul>
                </div>
            </div>
        </section>
        
        <!-- Projects Section -->
        <section id="projects" class="py-20">
            <h2 class="text-3xl font-bold text-center text-white mb-12">Featured Project</h2>
            <div class="grid grid-cols-1 md:grid-cols-1 gap-8">
                <div class="glass-effect rounded-lg p-6 hover:border-sky-400 transition-all duration-300 transform hover:-translate-y-1">
                    <div class="flex justify-between items-start">
                        <h3 class="text-xl font-bold text-white">Options Volatility Analyzer</h3>
                        <a href="#" class="text-gray-400 hover:text-sky-400">
                            <!-- Replace with your GitHub repo link for the project -->
                            <i data-lucide="github" class="w-6 h-6"></i>
                        </a>
                    </div>
                    <p class="mt-2 text-gray-400">A Python-based tool to analyze options market sentiment by visualizing volatility smiles and skews.</p>
                    <div class="mt-4">
                        <p class="text-white font-semibold">Key Featues:</p>
                        <ul class="list-disc list-inside mt-2 text-gray-400 space-y-1">
                            <li>Processed 1,000+ S&P 500 option contracts across 30 expirations.</li>
                            <li>Generated over 500 volatility surface plots to analyze market dynamics.</li>
                            <li>Provided actionable insights into implied volatility trends.</li>
                        </ul>
                    </div>
                    <div class="mt-4 flex flex-wrap gap-2">
                        <span class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-sky-600 bg-sky-200">Python</span>
                        <span class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-sky-600 bg-sky-200">yfinance</span>
                        <span class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-sky-600 bg-sky-200">Matplotlib</span>
                        <span class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-sky-600 bg-sky-200">Data Analysis</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- Skills Section -->
        <section id="skills" class="py-20">
            <h2 class="text-3xl font-bold text-center text-white mb-12">Technical Skills</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="glass-effect rounded-lg p-6">
                    <h3 class="text-xl font-bold text-white text-center mb-4">Product & Design</h3>
                    <div class="flex flex-wrap justify-center gap-4">
                        <div class="text-center"><i data-lucide="layout-template" class="mx-auto h-8 w-8 accent-color"></i><p>Jira</p></div>
                        <div class="text-center"><i data-lucide="trello" class="mx-auto h-8 w-8 accent-color"></i><p>Trello</p></div>
                        <div class="text-center"><i data-lucide="pen-tool" class="mx-auto h-8 w-8 accent-color"></i><p>Miro</p></div>
                        <div class="text-center"><i data-lucide="figma" class="mx-auto h-8 w-8 accent-color"></i><p>Wireframing</p></div>
                        <div class="text-center"><i data-lucide="mouse-pointer-2" class="mx-auto h-8 w-8 accent-color"></i><p>Prototyping</p></div>
                    </div>
                </div>
                <div class="glass-effect rounded-lg p-6">
                    <h3 class="text-xl font-bold text-white text-center mb-4">Data & Analytics</h3>
                    <div class="flex flex-wrap justify-center gap-4">
                        <div class="text-center"><i data-lucide="database" class="mx-auto h-8 w-8 accent-color"></i><p>SQL</p></div>
                        <div class="text-center"><i data-lucide="file-spreadsheet" class="mx-auto h-8 w-8 accent-color"></i><p>Excel</p></div>
                        <div class="text-center"><i data-lucide="pie-chart" class="mx-auto h-8 w-8 accent-color"></i><p>Power BI</p></div>
                        <div class="text-center"><i data-lucide="line-chart" class="mx-auto h-8 w-8 accent-color"></i><p>Google Analytics</p></div>
                    </div>
                </div>
                <div class="glass-effect rounded-lg p-6">
                    <h3 class="text-xl font-bold text-white text-center mb-4">Programming</h3>
                    <div class="flex flex-wrap justify-center gap-4">
                        <div class="text-center"><i data-lucide="braces" class="mx-auto h-8 w-8 accent-color"></i><p>Python</p></div>
                        <div class="text-center"><i data-lucide="variable" class="mx-auto h-8 w-8 accent-color"></i><p>R</p></div>
                        <div class="text-center"><i data-lucide="terminal-square" class="mx-auto h-8 w-8 accent-color"></i><p>VBA</p></div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="py-20 text-center">
            <h2 class="text-3xl font-bold text-white">Let's Connect</h2>
            <p class="mt-4 mb-8 max-w-xl mx-auto text-gray-400">I'm currently seeking Product Management internship opportunities. If you have a role that could be a good fit, or just want to talk about tech and strategy, feel free to reach out!</p>
            <div class="flex justify-center items-center space-x-6">
                <!-- IMPORTANT: Replace '#' with your actual links -->
                <a href="mailto:vishanthashok@utexas.edu" class="text-gray-400 hover:text-sky-400 transition-colors duration-300">
                    <i data-lucide="mail" class="w-8 h-8"></i>
                </a>
                <a href="#" target="_blank" class="text-gray-400 hover:text-sky-400 transition-colors duration-300">
                    <i data-lucide="linkedin" class="w-8 h-8"></i>
                </a>
                <a href="#" target="_blank" class="text-gray-400 hover:text-sky-400 transition-colors duration-300">
                    <i data-lucide="github" class="w-8 h-8"></i>
                </a>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="border-t border-gray-800">
        <div class="container mx-auto px-6 py-6 text-center text-gray-500">
            <p>&copy; 2025 Vishanth Ashok. Designed with passion and code.</p>
        </div>
    </footer>

    <script>
        // Initialize Lucide Icons
        lucide.createIcons();

        // Mobile Menu Toggle
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');
        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Close mobile menu when a link is clicked
        document.querySelectorAll('#mobile-menu a').forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });
    </script>
</body>
</html>
