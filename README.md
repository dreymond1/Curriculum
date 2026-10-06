<!DOCTYPE html>
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
        
        <!-- CABEÇALHO -->
        <header>
            <h1 class="text-[32px] font-bold text-slate-800 leading-none">Andrey Alves</h1>
            <p class="text-lg text-slate-600 font-semibold mt-2">Analista de Dados Senior / Pleno | Especialista em BI & SQL</p>
            
            <div class="mt-4 flex flex-wrap gap-x-5 gap-y-2 text-[13px] text-slate-600">
                <span>E-mail: <a href="mailto:andrey.alves9@gmail.com" class="hover:underline text-slate-800">andrey.alves9@gmail.com</a></span>
                <span>Telefone: +55 (21) 97934-5896</span>
                <span>LinkedIn: <a href="https://www.linkedin.com/in/andrey-de-abreu-9a499b154/" target="_blank" class="hover:underline text-slate-800">linkedin.com/in/andreydeabreu</a></span>
            </div>
            <div class="mt-2 text-[13px] text-slate-600">
                <span>Localização: Nova Iguaçu, RJ - Brasil</span>
            </div>
        </header>

        <hr class="my-6 border-slate-300">

        <!-- RESUMO PROFISSIONAL -->
        <section class="mb-8">
            <h2 class="text-[15px] font-bold text-slate-800 uppercase mb-3">Resumo Profissional</h2>
            <p class="text-[14px] leading-relaxed text-slate-700 text-justify">
                Cientista da Computação e Analista de Dados Pleno com sólida experiência em <strong>SQL Avançado (Snowflake, PostgreSQL)</strong>, <strong>Power BI (DAX, Modelagem de Dados)</strong> e inteligência de negócios. Especialista no <strong>levantamento de requisitos junto às áreas de negócio</strong> e stakeholders, traduzindo necessidades operacionais e estratégicas em dashboards de alto impacto e soluções analíticas robustas. Atuação destacada em geração de insights para tomada de decisão crítica, governança de dados, automação de rotinas em Python e otimização de processos em até 80%.
            </p>
        </section>

        <!-- EXPERIÊNCIAS PROFISSIONAIS -->
        <section class="mb-8">
            <h2 class="text-[15px] font-bold text-slate-800 uppercase mb-4">Experiência Profissional</h2>

            <div class="space-y-6">

                <div>
                    <div class="flex justify-between items-baseline">
                        <h3 class="text-[15px] font-bold text-slate-800">Analista de Dados Pleno | Estratégia Comercial</h3>
                        <span class="text-[13px] text-slate-500 font-medium">Jun/2025 – Atual</span>
                    </div>
                    <p class="text-[13px] italic text-slate-500">Grupo OLX, Brasil</p>
                    <ul class="mt-2 list-disc ml-4 space-y-1.5 text-[13.5px] text-slate-700">
                        <li><strong>Levantamento de Requisitos & Parceria com Negócio:</strong> Atuação próxima aos gestores e áreas comerciais, conduzindo o levantamento de necessidades e traduzindo desafios de negócio em soluções de Business Intelligence.</li>
                        <li><strong>SQL Avançado & Data Warehouse:</strong> Criação e otimização de queries complexas em SQL (ambientes Snowflake e Data Lakes) para extração, preparação e análise de dados de alto volume.</li>
                        <li><strong>Power BI & Modelagem de Dados:</strong> Desenvolvimento de dashboards dinâmicos e relatórios executivos em Power BI e Tableau, aplicando modelagem de dados eficiente e cálculos avançados em DAX para acompanhamento de KPIs estratégicos (receita, churn e LTV).</li>
                        <li><strong>Geração de Insights & Automação:</strong> Identificação de padrões de mercado e melhorias operacionais, além de automatizar rotinas analíticas em Python com ganho de 50% de produtividade na equipe.</li>
                    </ul>
                </div>

                <div>
                    <div class="flex justify-between items-baseline">
                        <h3 class="text-[15px] font-bold text-slate-800">Analista de Dados Junior | Customer Experience</h3>
                        <span class="text-[13px] text-slate-500 font-medium">Set/2023 – Jun/2025</span>
                    </div>
                    <p class="text-[13px] italic text-slate-500">Grupo OLX, Brasil</p>
                    <ul class="mt-2 list-disc ml-4 space-y-1.5 text-[13.5px] text-slate-700">
                        <li><strong>Dashboards Executivos em Power BI:</strong> Arquitetura de soluções em Power BI (Modelagem de Dados e DAX) e Looker Studio para monitoramento contínuo de KPIs de experiência do cliente e suporte à tomada de decisão.</li>
                        <li><strong>Governança e Qualidade de Dados:</strong> Aplicação de práticas de validação, qualidade de dados e detecção de anomalias para garantir a confiabilidade dos relatórios e bases analíticas operacionais.</li>
                        <li><strong>Análise de Dados Avançada & SQL:</strong> Manipulação e consultas em SQL sobre grandes volumes de dados para suporte a diagnósticos quantitativos, reduzindo o tempo de análise em até 80%.</li>
                        <li><strong>Modelos Preditivos & Machine Learning:</strong> Desenvolvimento de modelos preditivos e análise de sentimentos via Python e APIs REST para automação de triagem de feedbacks.</li>
                    </ul>
                </div>

                <div>
                    <div class="flex justify-between items-baseline">
                        <h3 class="text-[15px] font-bold text-slate-800">Estagiário de Análise de Dados</h3>
                        <span class="text-[13px] text-slate-500 font-medium">Jan/2022 – Ago/2023</span>
                    </div>
                    <p class="text-[13px] italic text-slate-500">Grupo OLX, Brasil</p>
                    <ul class="mt-2 list-disc ml-4 space-y-1.5 text-[13.5px] text-slate-700">
                        <li><strong>Suporte às Áreas de Negócio:</strong> Mapeamento de demandas da equipe de atendimento e criação de relatórios analíticos em SQL e ferramentas de BI.</li>
                        <li><strong>Geração de Insights Acionáveis:</strong> Realização de análises quantitativas para diagnóstico de problemas de produto e identificação de oportunidades de melhoria contínua.</li>
                    </ul>
                </div>

            </div>
        </section>

        <hr class="my-6 border-slate-300">

        <!-- COMPETÊNCIAS TÉCNICAS -->
        <section class="mb-8">
            <h2 class="text-[15px] font-bold text-slate-800 uppercase mb-4">Habilidades Técnicas & Competências</h2>
            <div class="grid grid-cols-2 gap-y-3 gap-x-8 text-[13.5px]">
                <div>
                    <span class="font-bold text-slate-800">Business Intelligence & BI:</span>
                    <p class="text-slate-600">Power BI (DAX, Modelagem de Dados), Tableau, Looker Studio</p>
                </div>
                <div>
                    <span class="font-bold text-slate-800">Bancos de Dados & SQL:</span>
                    <p class="text-slate-600">SQL Avançado, Snowflake, PostgreSQL, Data Warehouse, Data Lake</p>
                </div>
                <div>
                    <span class="font-bold text-slate-800">Análise de Negócios & Governança:</span>
                    <p class="text-slate-600">Levantamento de Requisitos, Governança de Dados, Qualidade de Dados, KPIs</p>
                </div>
                <div>
                    <span class="font-bold text-slate-800">Programação & Automação:</span>
                    <p class="text-slate-600">Python (Pandas, NumPy, Scikit-learn), ETL, Git, Docker, REST APIs</p>
                </div>
            </div>
        </section>

        <!-- EDUCAÇÃO E IDIOMAS -->
        <div class="grid grid-cols-2 gap-6 pt-4 border-t border-slate-300">
            <section>
                <h2 class="text-[13px] font-bold uppercase mb-2 text-slate-800">Formação Acadêmica</h2>
                <p class="text-[13px] font-bold text-slate-800">Bacharelado em Ciência da Computação</p>
                <p class="text-[12px] text-slate-500">CEFET/RJ | Concluído em 2024</p>
            </section>
            
            <section>
                <h2 class="text-[13px] font-bold uppercase mb-2 text-slate-800">Idiomas</h2>
                <div class="text-[13px] space-y-0.5 text-slate-700">
                    <p><strong>Português:</strong> Nativo</p>
                    <p><strong>Inglês:</strong> Avançado </p>
                    <p><strong>Espanhol:</strong> Intermediário</p>
                </div>
            </section>
        </div>

    </div>

    <!-- BOTÃO IMPRIMIR / PDF -->
    <div class="max-w-[850px] mx-auto mt-6 text-right no-print">
        <button onclick="window.print()" class="bg-slate-800 text-white px-8 py-2 text-sm font-semibold rounded hover:bg-slate-700 transition-colors">
            Exportar como PDF
        </button>
    </div>

</body>
</html>
