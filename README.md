<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Andrey Alves</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap');
        
        body {
            font-family: 'Inter', sans-serif;
            color: #334155;
        }

        @media print {
            .no-print { display: none; }
            body { background-color: white; padding: 0; }
            .content-box { box-shadow: none !important; border: none !important; width: 100% !important; max-width: 100% !important; }
        }

        h2 {
            letter-spacing: 0.05em;
        }
    </style>
</head>
<body class="bg-gray-50 py-12 px-4">

    <div class="max-w-[850px] mx-auto bg-white p-10 shadow-sm content-box">
        
        <header>
            <h1 class="text-[32px] font-bold text-slate-800 leading-none">Andrey Alves</h1>
            <p class="text-lg text-slate-500 mt-2">Data Analyst</p>
            
            <div class="mt-4 flex flex-wrap gap-x-5 gap-y-2 text-[13px] text-slate-600">
                <span class="flex items-center gap-1">✉️ <a href="mailto:andrey.alves9@gmail.com" class="hover:underline">andrey.alves9@gmail.com</a></span>
                <span class="flex items-center gap-1">📱 +55 21 979345896</span>
                <span class="flex items-center gap-1">🔗 <a href="[https://www.linkedin.com/in/andrey-de-abreu-9a499b154/" class="hover:underline">linkedin.com/in/andreydeabreu</a></span>
                
            </div>
            <div class="mt-2 text-[13px] text-slate-600">
                <span>📍 Nova Iguaçu, RJ, Brazil</span>
            </div>
        </header>

        <hr class="my-6 border-slate-300">

        <section class="mb-8">
            <h2 class="text-[15px] font-bold text-slate-800 uppercase mb-3">Professional Summary</h2>
            <p class="text-[14px] leading-relaxed text-slate-700 text-justify">
                Especialista automatizar e em extrair valor de grandes volumes de dados através de automação e inteligência artificial. Unindo o rigor técnico da Engenharia de Dados (Python/SQL) com a visão estratégica da Análise de Dados, projeto soluções que otimizam processos e operações em até 80%. Expertise em arquitetar dashboards de alto impacto e implementar modelos de Redes Neurais e ML para suporte à decisão crítica.
            </p>
        </section>

        <section class="mb-8">
            <h2 class="text-[15px] font-bold text-slate-800 uppercase mb-4">Experiências Profissionais</h2>
            
            <div class="space-y-6">
                <div>
                    <div class="flex justify-between items-baseline">
                        <h3 class="text-[15px] font-bold text-slate-800">Data Analyst & Data Engineer</h3>
                        <span class="text-[13px] text-slate-400 font-medium">February 2024 - November 2025</span>
                    </div>
                    <p class="text-[13px] italic text-slate-500">Three60 Energy / Maiella, Norway/Italy</p>
                    <ul class="mt-2 list-disc list-outside ml-4 space-y-1 text-[13.5px] text-slate-700">
                        <li>Led a 3 person frontend team developing BI solutions for oil & gas industry, owning architecture decisions and delivery strategy</li>
                        <li>Built design system and component library with Storybook achieving 90%+ test coverage across multiple products</li>
                        <li>Reduced infrastructure costs by 80% replacing Chromatic with custom Playwright based visual regression testing solution</li>
                        <li>Architected end-to-end type safety using Elysia + Eden Treaty, eliminating API contract bugs across monorepo</li>
                        <li>Built data visualization dashboards using React, TypeScript, and ECharts; contributed Python backend services</li>
                        <li>Developed CI/CD pipelines with GitHub Actions and Azure DevOps with intelligent caching</li>
                    </ul>
                </div>

                <div>
                    <div class="flex justify-between items-baseline">
                        <h3 class="text-[15px] font-bold text-slate-800">Mid Software Engineer</h3>
                        <span class="text-[13px] text-slate-400 font-medium">July 2022 - February 2024</span>
                    </div>
                    <p class="text-[13px] italic text-slate-500">Zoolatech / Procore, USA</p>
                    <ul class="mt-2 list-disc list-outside ml-4 space-y-1 text-[13.5px] text-slate-700">
                        <li>Consultant for Procore's 20-year-old Rails/React enterprise construction management platform</li>
                        <li>Improved test coverage by 40% and delivered critical features for budget management module</li>
                        <li>Led cross-team data exposure initiatives; integrated DBT for Reports team</li>
                        <li>Won internal hackathon with landing page solution reducing user navigation by 30%</li>
                        <li>Partnered with PMs and designers throughout feature lifecycle from requirements to delivery</li>
                    </ul>
                </div>

                <div>
                    <div class="flex justify-between items-baseline">
                        <h3 class="text-[15px] font-bold text-slate-800">CTO & Co-founder</h3>
                        <span class="text-[13px] text-slate-400 font-medium">May 2021 - July 2022</span>
                    </div>
                    <p class="text-[13px] italic text-slate-500">Avaliei!, Brazil</p>
                    <ul class="mt-2 list-disc list-outside ml-4 space-y-1 text-[13.5px] text-slate-700">
                        <li>Technical co-founder after being a finalist in Hacking.Rio 2019 (700+ participants); transformed concept into venture-backed startup</li>
                        <li>Architected full-stack solutions in partnership with Vibra Energia S.A.</li>
                        <li>Achieved low operational costs through serverless architecture and automated pipelines</li>
                    </ul>
                </div>

                <div>
                    <div class="flex justify-between items-baseline">
                        <h3 class="text-[15px] font-bold text-slate-800">Junior Full-stack Developer</h3>
                        <span class="text-[13px] text-slate-400 font-medium">January 2019 - July 2022</span>
                    </div>
                    <p class="text-[13px] italic text-slate-500">Odda Digital System, Norway</p>
                    <ul class="mt-2 list-disc list-outside ml-4 space-y-1 text-[13.5px] text-slate-700">
                        <li>Built GraphQL API gateway unifying multiple backend services; developed microservices with Node.js, React, Ruby on Rails</li>
                        <li>Architected event-driven automation using Azure Service Bus, replacing manual ERP data entry</li>
                        <li>Promoted from frontend to full-stack within 6 months</li>
                    </ul>
                </div>
            </div>
        </section>

        <hr class="my-6 border-slate-300">

        <section class="mb-8">
            <h2 class="text-[15px] font-bold text-slate-800 uppercase mb-4 tracking-tighter">Technical Skills</h2>
            <div class="grid grid-cols-2 gap-8">
                <div>
                    <h4 class="text-[14px] font-bold text-slate-700 mb-1">Languages & Frameworks:</h4>
                    <p class="text-[13.5px] text-slate-600">TypeScript, React.js, Ruby on Rails, Python, Node.js, SQL, GraphQL</p>
                </div>
                <div>
                    <h4 class="text-[14px] font-bold text-slate-700 mb-1">Tools & Infrastructure:</h4>
                    <p class="text-[13.5px] text-slate-600">Storybook, Playwright, Jest, Cypress, Docker, Git, CI/CD, AWS, Azure DevOps, PostgreSQL, MongoDB, Redux</p>
                </div>
            </div>
        </section>

        <div class="grid grid-cols-3 gap-6 pt-4 border-t border-slate-300">
            <section>
                <h2 class="text-[13px] font-bold text-slate-800 uppercase mb-2">Educação</h2>
                <p class="text-[13px] font-bold text-slate-700 leading-tight">Bacharelado em Ciência da Computação</p>
                <p class="text-[12px] text-slate-500">CEFET/RJ - Brazil | 2019 - 2024</p>
            </section>
            
            <section>
                <h2 class="text-[13px] font-bold text-slate-800 uppercase mb-2">Languages</h2>
                <div class="text-[13px] text-slate-700">
                    <p><strong>Portuguese:</strong> Nativo</p>
                    <p><strong>English:</strong> Avançado</p>
                    <p><strong>Spanish:</strong> Médio</p>
                </div>
            </section>
        </div>

    </div>

    <div class="max-w-[850px] mx-auto mt-6 text-right no-print">
        <button onclick="window.print()" class="bg-slate-800 text-white px-8 py-2 text-sm font-semibold rounded hover:bg-slate-700 transition">
            Exportar como PDF
        </button>
    </div>

</body>
</html>
