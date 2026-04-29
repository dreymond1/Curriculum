<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Andrey Alves - Currículo</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap');
        
        body {
            font-family: 'Inter', sans-serif;
            color: #334155;
        }

        @media print {
            .no-print { display: none; }
            body { background-color: white; padding: 0; margin: 0; }
            .content-box { 
                box-shadow: none !important; 
                border: none !important; 
                width: 100% !important; 
                max-width: 100% !important; 
                padding: 0 !important;
            }
            @page { margin: 1.5cm; }
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
            <p class="text-lg text-slate-500 mt-2">Data Analyst & Data Engineer</p>
            
            <div class="mt-4 flex flex-wrap gap-x-5 gap-y-2 text-[13px] text-slate-600">
                <span class="flex items-center gap-1">✉️ <a href="mailto:andrey.alves9@gmail.com" class="hover:underline">andrey.alves9@gmail.com</a></span>
                <span class="flex items-center gap-1">📱 +55 21 979345896</span>
                <span class="flex items-center gap-1">🔗 <a href="https://www.linkedin.com/in/andrey-de-abreu-9a499b154/" target="_blank" class="hover:underline">linkedin.com/in/andreydeabreu</a></span>
            </div>
            <div class="mt-2 text-[13px] text-slate-600">
                <span>📍 Nova Iguaçu, RJ, Brazil</span>
            </div>
        </header>

        <hr class="my-6 border-slate-300">

        <section class="mb-8">
            <h2 class="text-[15px] font-bold text-slate-800 uppercase mb-3">Resumo Profissional</h2>
            <p class="text-[14px] leading-relaxed text-slate-700 text-justify">
                Especialista em automatizar e extrair valor de grandes volumes de dados através de automação e inteligência artificial. Unindo o rigor técnico da Engenharia de Dados (Python/SQL) com a visão estratégica da Análise de Dados, projeto soluções que otimizam processos e operações em até 80%. Expertise em arquitetar dashboards de alto impacto e implementar modelos de Redes Neurais e ML para suporte à decisão crítica.
            </p>
        </section>

        <section class="mb-8">
            <h2 class="text-[15px] font-bold text-slate-800 uppercase mb-4">Experiências Profissionais</h2>

            <div class="space-y-6">

                <div>
                    <div class="flex justify-between items-baseline">
                        <h3 class="text-[15px] font-bold text-slate-800">Analista de Dados Pleno | Estratégia Comercial</h3>
                        <span class="text-[13px] text-slate-400 font-medium">Junho 2025 - atualmente</span>
                    </div>
                    <p class="text-[13px] italic text-slate-500">Grupo OLX, Brasil</p>
                    <ul class="mt-2 list-disc ml-4 space-y-1 text-[13.5px] text-slate-700">
                        <li>Automação de processos com Python, reduzindo ~50% do tempo operacional.</li>
                        <li>Análise estratégica de KPIs comerciais (clientes, receita, performance).</li>
                        <li>Criação de dashboards em Tableau e Google Sheets com foco executivo.</li>
                        <li>Análises de mercado no setor automotivo (tendências e comportamento).</li>
                        <li>Experiência complementar no mercado imobiliário.</li>
                    </ul>
                </div>

                <div>
                    <div class="flex justify-between items-baseline">
                        <h3 class="text-[15px] font-bold text-slate-800">Analista de Dados Junior | Customer Experience</h3>
                        <span class="text-[13px] text-slate-400 font-medium">Setembro 2023 - Junho 2025</span>
                    </div>
                    <p class="text-[13px] italic text-slate-500">OLX Brasil, Brasil</p>
                    <ul class="mt-2 list-disc ml-4 space-y-1 text-[13.5px] text-slate-700">
                        <li>Dashboards em Tableau, Looker e Sheets para decisão estratégica.</li>
                        <li>Análise de grandes volumes de dados (datalake).</li>
                        <li>Automação com Python e SQL.</li>
                        <li>Modelos de ML e análise de sentimentos com redes neurais.</li>
                        <li>Criação de APIs para modelos em nuvem.</li>
                        <li>Uso de IA generativa para geração de insights.</li>
                        <li>Técnicas estatísticas (regressão, correlação, outliers).</li>
                        <li>Relatórios avançados no Salesforce.</li>
                    </ul>
                </div>

                <div>
                    <div class="flex justify-between items-baseline">
                        <h3 class="text-[15px] font-bold text-slate-800">Estágio em Dados</h3>
                        <span class="text-[13px] text-slate-400 font-medium">Janeiro 2022 - Agosto 2023</span>
                    </div>
                    <p class="text-[13px] italic text-slate-500">OLX Brasil, Brasil</p>
                    <ul class="mt-2 list-disc ml-4 space-y-1 text-[13.5px] text-slate-700">
                        <li>Relatórios em Sheets, Excel e SQL.</li>
                        <li>Análises quantitativas e qualitativas.</li>
                        <li>Monitoramento de mercado e concorrência.</li>
                        <li>Automação no Looker Studio.</li>
                    </ul>
                </div>

            </div>
        </section>

        <hr class="my-6 border-slate-300">

        <section class="mb-8">
            <h2 class="text-[15px] font-bold text-slate-800 uppercase mb-4">Technical Skills</h2>
            <div class="grid grid-cols-2 gap-8">
                <div>
                    <h4 class="text-[14px] font-bold text-slate-700 mb-1">Linguagens & Frameworks:</h4>
                    <p class="text-[13.5px] text-slate-600">Python, JavaScript, SQL</p>
                </div>
                <div>
                    <h4 class="text-[14px] font-bold text-slate-700 mb-1">Ferramentas:</h4>
                    <p class="text-[13.5px] text-slate-600">Tableau, Sheets, Data Studio, Git, Spark, Airflow, Docker, Kafka, AWS</p>
                </div>
            </div>
        </section>

        <div class="grid grid-cols-2 gap-6 pt-4 border-t border-slate-300">
            <section>
                <h2 class="text-[13px] font-bold uppercase mb-2">Educação</h2>
                <p class="text-[13px] font-bold">Ciência da Computação</p>
                <p class="text-[12px] text-slate-500">CEFET/RJ | 2019 - 2024</p>
            </section>
            
            <section>
                <h2 class="text-[13px] font-bold uppercase mb-2">Línguas</h2>
                <div class="text-[13px] flex gap-4">
                    <p><strong>Português:</strong> Nativo</p>
                    <p><strong>Inglês:</strong> Avançado</p>
                    <p><strong>Espanhol:</strong> Médio</p>
                </div>
            </section>
        </div>

    </div>

    <div class="max-w-[850px] mx-auto mt-6 text-right no-print">
        <button onclick="window.print()" class="bg-slate-800 text-white px-8 py-2 text-sm font-semibold rounded hover:bg-slate-700">
            Exportar como PDF
        </button>
    </div>

</body>
</html>
