<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Robert P Batzinger | Praeceptor Emeritus</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Configure Tailwind for custom colors and font -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'primary': '#1e3a8a', // Dark Blue
                        'secondary': '#3b82f6', // Brighter Blue
                        'background': '#f1f5f9', // Light Gray/Slate
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                }
            }
        }
    </script>
    <!-- Use Inter font -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap" rel="stylesheet">
    <style>
        /* Custom styles for professional look */
        .card {
            /* Applies bg-white, padding, rounded, shadow, and hover effect */
            @apply bg-white p-6 rounded-xl shadow-lg transition duration-300 hover:shadow-xl;
        }
        .section-title {
            /* Applies large text, bold font, bottom border, and colors */
            @apply text-2xl font-bold mb-4 border-b-2 border-secondary pb-2 text-primary;
        }
        .list-item {
            @apply mb-2 flex items-start;
        }
        .list-item::before {
            content: '•';
            @apply text-secondary font-extrabold mr-3 text-lg leading-none;
        }
    </style>
</head>
<body class="bg-background font-sans min-h-screen">

    <!-- Header Section -->
    <header class="bg-primary text-white shadow-xl">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4 flex flex-col sm:flex-row justify-between items-center">
            <!-- Title and Subtitle -->
            <div class="text-center sm:text-left mb-4 sm:mb-0">
                <h1 class="text-4xl font-extrabold tracking-tight">Robert P Batzinger</h1>
                <p class="text-xl opacity-90 mt-1">Praeceptor Emeritus | Computer Solutions Developer</p>
                <p class="text-base opacity-70">Payap University, Amphur Muang, Chiang Mai 50000, Thailand</p>
            </div>
            
            <!-- External Links (Top Right) -->
            <div class="flex space-x-4">
                <a href="#" class="bg-secondary hover:bg-blue-700 text-white font-semibold py-2 px-4 rounded-lg shadow-md transition duration-300 flex items-center">
                    <svg class="w-5 h-5 mr-1" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10 0C4.477 0 0 4.484 0 10.017c0 4.417 2.865 8.163 6.83 9.497.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.37-1.34-3.37-1.34-.454-1.157-1.11-1.46-1.11-1.46-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.828.092-.643.35-1.088.636-1.338-2.22-.253-4.555-1.116-4.555-4.949 0-1.092.39-1.983 1.03-2.675-.104-.252-.448-1.266.098-2.638 0 0 .84-.268 2.75 1.022A9.61 9.61 0 0110 4.844c.85.008 1.7.11 2.5.326 1.91-1.29 2.75-1.022 2.75-1.022.546 1.372.202 2.386.098 2.638.64.692 1.028 1.583 1.028 2.675 0 3.84-2.338 4.69-4.562 4.94.358.307.678.915.678 1.849 0 1.335-.013 2.41-.013 2.744 0 .267.18.577.688.484 3.96-1.335 6.825-5.082 6.825-9.497C20 4.484 15.522 0 10 0z" clip-rule="evenodd"></path></svg>
                    View On GitHub
                </a>
                <!-- You can add other links here if desired, like GitHub Profile, LinkedIn, etc. -->
            </div>
        </div>
    </header>

    <!-- Main Content Area -->
    <main class="max-w-7xl mx-auto p-4 sm:p-8 lg:p-10">

        <!-- Grid Layout for Content and Contact Info -->
        <div class="grid grid-cols-1 lg:grid-cols-3 gap-8">
            
            <!-- Column 1 & 2: Main Content (Takes 2/3 width on large screens) -->
            <div class="lg:col-span-2 space-y-8">

                <!-- Profile Summary -->
                <section class="card">
                    <h2 class="section-title">Profile Summary</h2>
                    <p class="text-gray-700 leading-relaxed text-lg">
                        Computer Solutions Developer with decades of experience in **Data Science** and **Big Data Analytics**, **Natural Language Processing**, **Document Publishing Systems**, and **Web Community Development** as well as mutagenic and carcinogenic activities of anthelmintics.
                    </p>
                </section>

                <!-- Education -->
                <section class="card">
                    <h2 class="section-title">Education</h2>
                    <ul class="space-y-4">
                        <li class="list-item">
                            <span class="font-semibold text-gray-800">MS Applied Mathematics and Computer Science</span> - Indiana University - South Bend
                        </li>
                        <li class="list-item">
                            <span class="font-semibold text-gray-800">PhD Pathobiology</span> - Johns Hopkins University
                        </li>
                        <li class="list-item">
                            <span class="font-semibold text-gray-800">SB Chemistry</span> - Massachusetts Institute of Technology
                        </li>
                        <li class="list-item">
                            <span class="font-semibold text-gray-800">NIH Post-Doctoral Fellow</span> - University of Wisconsin at Madison
                        </li>
                    </ul>
                </section>

                <!-- Experience -->
                <section class="card">
                    <h2 class="section-title">Professional Experience</h2>
                    <ul class="space-y-4 text-gray-700">
                        <li class="list-item">Praceptor Emeritus - IT Department, International College, Payap University</li>
                        <li class="list-item">IT Director - IT Services, Payap University</li>
                        <li class="list-item">Computer Science Instructor - Payap University</li>
                        <li class="list-item">Informatics Lab Manager - Indiana University South Bend</li>
                        <li class="list-item">Office Manager - Martin Kehoe Law Office - Guilderland, NY</li>
                        <li class="list-item">Director - United Bible Society Asia-Pacific Regional Computer-Assisted Text Processing Center</li>
                        <li class="list-item">Software Development Lead - Computer-Assisted Text Processing Center, Thailand Bible Society</li>
                        <li class="list-item">Acting Dean - Faculty of Science, Payap University</li>
                        <li class="list-item">Project Head - Faculty of Pharmacy, Payap University</li>
                        <li class="list-item">Post Doctoral Fellow - McArdle Laboratory, University of Wisconsin at Madison</li>
                        <li class="list-item">Research Assistant - Wellcome Laboratory, Johns Hopkins University</li>
                        <li class="list-item">Urban Vehicle Design Competition - Team communications and logistics officer, Massachusetts Institute of Technology</li>
                        <li class="list-item">Undergraduate Research Opportunity Intern - Environmental Health Sciences Center, Massachusetts Institute of Technology</li>
                        <li class="list-item">Summer Intern - New York State Rabies Screening Laboratory</li>
                    </ul>
                </section>

                <!-- Interests -->
                <section class="card">
                    <h2 class="section-title">Interests & Research Focus</h2>
                    <ul class="space-y-4 text-gray-700">
                        <li class="list-item">Applied machine learning, data science, modeling, and forecasting to assist decision-making</li>
                        <li class="list-item">Natural language processing to automate prepublication editing support</li>
                        <li class="list-item">Web and online community development and e-business</li>
                        <li class="list-item">Blended and online education for higher education and lifelong learning</li>
                        <li class="list-item">Bible study and its life applications</li>
                    </ul>
                </section>

            </div>

            <!-- Column 3: Contact & Technical Proficiency (Takes 1/3 width on large screens) -->
            <div class="space-y-8 lg:col-span-1">
                
                <!-- Contact Info -->
                <section class="card bg-primary text-white shadow-xl">
                    <h2 class="text-xl font-bold mb-4 border-b-2 border-white pb-2">Contact & Online Presence</h2>
                    <ul class="space-y-3 text-sm">
                        <li><a href="#" class="flex items-center hover:text-secondary transition duration-150">
                            <svg class="w-4 h-4 mr-2" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path d="M10 2a8 8 0 100 16 8 8 0 000-16zM6.5 9.5a1.5 1.5 0 110-3 1.5 1.5 0 010 3zM10 16a6 6 0 01-6-6 1 1 0 012 0 4 4 0 008 0 1 1 0 012 0 6 6 0 01-6 6z"></path></svg>
                            Web Page
                        </a></li>
                        <li><a href="#" class="flex items-center hover:text-secondary transition duration-150">
                            <svg class="w-4 h-4 mr-2" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M16.3 3.6c.3-.3.8-.3 1.1 0 .3.3.3.8 0 1.1l-6.5 6.5a.75.75 0 01-1.06 0L2.6 4.7c-.3-.3-.3-.8 0-1.1s.8-.3 1.1 0L10 9.5l6.3-6.2z" clip-rule="evenodd"></path></svg>
                            LinkedIn
                        </a></li>
                        <li><a href="#" class="flex items-center hover:text-secondary transition duration-150">
                            <svg class="w-4 h-4 mr-2" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path d="M17.7 5.2c-.6.3-1.2.5-1.9.6.7-.4 1.2-1.1 1.4-1.9-.6.4-1.3.6-2.1.8-.6-.6-1.4-1-2.4-1-1.8 0-3.3 1.5-3.3 3.3 0 .3.03.6.1.9C7.8 8.8 4.1 6.9 1.6 4c-.3.5-.5 1-.5 1.7 0 1.1.5 2.1 1.3 2.7-.5 0-1-.2-1.4-.4v.05c0 1.6 1.1 3 2.6 3.3-.3.08-.6.12-.9.12-.2 0-.4 0-.6-.05.4 1.3 1.6 2.3 3 2.3-1.1.9-2.5 1.4-4.1 1.4-.3 0-.6 0-.8-.05C2.5 16 4.3 17 6.2 17c7.4 0 11.5-6.1 11.5-11.4 0-.2 0-.4-.01-.6.8-.6 1.4-1.3 1.9-2.1z"></path></svg>
                            Twitter
                        </a></li>
                        <li><a href="#" class="flex items-center hover:text-secondary transition duration-150">
                            <svg class="w-4 h-4 mr-2" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M11 3a1 1 0 100 2h2.586l-6.293 6.293a1 1 0 101.414 1.414L15 6.414V9a1 1 0 102 0V4a1 1 0 00-1-1h-5z" clip-rule="evenodd"></path><path fill-rule="evenodd" d="M5 5a2 2 0 00-2 2v8a2 2 0 002 2h8a2 2 0 002-2v-3a1 1 0 10-2 0v3H5V7h3a1 1 0 000-2H5z" clip-rule="evenodd"></path></svg>
                            Google Scholar
                        </a></li>
                        <li><a href="#" class="flex items-center hover:text-secondary transition duration-150">
                            <svg class="w-4 h-4 mr-2" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path d="M10 12a2 2 0 100-4 2 2 0 000 4z"></path><path fill-rule="evenodd" d="M.458 10C1.732 5.943 5.522 3 10 3s8.268 2.943 9.542 7c-1.274 4.057-5.064 7-9.542 7S1.732 14.057.458 10zM14 10a4 4 0 11-8 0 4 4 0 018 0z" clip-rule="evenodd"></path></svg>
                            Research Gate
                        </a></li>
                    </ul>
                    <p class="mt-4 text-xs opacity-70">
                        *Note: Placeholder links are used. Update the href="#" attributes with your actual URLs.
                    </p>
                </section>

                <!-- Technical Proficiency -->
                <section class="card">
                    <h2 class="section-title">Technical Proficiency</h2>

                    <div class="space-y-5">
                        <!-- Programming Languages -->
                        <div>
                            <h3 class="font-semibold text-lg text-primary mb-2">Programming & Scripting</h3>
                            <p class="text-sm text-gray-700 leading-relaxed">
                                Fortran 4, 6809 Assembler, C, MS BASIC, Forth, Z80 Assembler, Pascal, Lisp, C++, AWK, SNOBOL, APL, troff, SPITBOL, Perl, SmallTalk, Icon, Fortran 77, TeX, Metafont, XLISP, Visual Basic, SQL, **Python**, **LaTeX**, VBA, **Ruby**, Java, **PHP**, Ruby on Rails, **R**, **JavaScript**, Angular JS, Node JS, NoSQL, Bender, Julia.
                            </p>
                        </div>
                        
                        <!-- Open Standards -->
                        <div>
                            <h3 class="font-semibold text-lg text-primary mb-2">Web & Open Standards</h3>
                            <p class="text-sm text-gray-700 leading-relaxed">
                                **HTML**, **CSS**, **XML**, RSS, GPX, **Unicode**, ISO9001, ISO29110.
                            </p>
                        </div>

                        <!-- OS & Shells -->
                        <div>
                            <h3 class="font-semibold text-lg text-primary mb-2">OS & Shells</h3>
                            <p class="text-sm text-gray-700 leading-relaxed">
                                CP/M, **UNIX**, MSDOS, MS Windows, OsX, **Linux**, KSH, BASH, SSH, Ardunio, Android.
                            </p>
                        </div>

                        <!-- Version Control -->
                        <div>
                            <h3 class="font-semibold text-lg text-primary mb-2">Version Control</h3>
                            <p class="text-sm text-gray-700 leading-relaxed">
                                RCS, CVS, Subversion, Bazaar, **GIT**.
                            </p>
                        </div>
                        
                        <!-- Human Languages -->
                        <div>
                            <h3 class="font-semibold text-lg text-primary mb-2">Human Languages</h3>
                            <p class="text-sm text-gray-700 leading-relaxed">
                                English, Thai, French, German.
                            </p>
                        </div>
                    </div>
                </section>
                
            </div>
        </div>

    </main>
    
    <!-- Footer Section -->
    <footer class="bg-primary text-white p-4 text-center mt-10">
        <div class="max-w-7xl mx-auto text-sm opacity-80">
            &copy; 2025 Robert P Batzinger. All rights reserved. | <a href="#" class="underline hover:text-secondary">Privacy Policy</a>
        </div>
    </footer>

</body>
</html>
