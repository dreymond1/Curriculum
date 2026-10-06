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
            <p class="text-lg text-slate-600 font-semibold mt-2">Pleno Analytics Engineer & Data Analyst | BI, BigQuery & IA</p>
            
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
                Cientista da Computação e Analista de Dados Pleno com sólida atuação em <strong>Analytics Engineering, Business Intelligence e Otimização de Dados</strong>. Forte domínio em <strong>SQL Avançado (BigQuery)</strong>, modelagem analítica/semântica, governança de KPIs e construção de dashboards de alta performance em <strong>Tableau, Looker e Power BI</strong>. Experiência na condução autônoma de análises diagnósticas, formulação de hipóteses e estruturação de pipelines/automações em Python. Atuação destacada na conexão entre dados analíticos e aplicações de <strong>IA Generativa e Agentes de IA</strong> (serving-ready datasets e features), combinando excelência técnica com Storytelling executivo.
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
                        <li><strong>SQL Avançado & Performance em BigQuery:</strong> Desenvolvimento e otimização de consultas SQL complexas utilizando CTEs, Window Functions, particionamento e clustering no Data Lake/BigQuery, focando na redução de custos de consulta e ganho de performance.</li>
                        <li><strong>Modelagem Analítica & Dashboards de BI:</strong> Arquitetura de dashboards dinâmicos em Tableau e Google Sheets/Looker, estabelecendo a camada de métricas executivas (LTV, Churn, Receita) com rigorosa governança.</li>
                        <li><strong>Análise Diagnóstica & Storytelling:</strong> Formulação de hipóteses, segmentações e avaliação de impacto para direcionamento tático e estratégico das áreas de negócio comercial (Automotivo e Imobiliário).</li>
                        <li><strong>Automação & Pipelines:</strong> Criação de rotinas em Python e scripts automatizados para alimentação contínua de bases analíticas, reduzindo em 50% o tempo operacional de atualização de dados.</li>
                    </ul>
                </div>

                <div>
                    <div class="flex justify-between items-baseline">
                        <h3 class="text-[15px] font-bold text-slate-800">Analista de Dados Junior | Customer Experience</h3>
                        <span class="text-[13px] text-slate-500 font-medium">Set/2023 – Jun/2025</span>
                    </div>
                    <p class="text-[13px] italic text-slate-500">Grupo OLX, Brasil</p>
                    <ul class="mt-2 list-disc ml-4 space-y-1.5 text-[13.5px] text-slate-700">
                        <li><strong>Modelagem Semântica & Datasets para IA:</strong> Estruturação de tabelas de consumo e serving-ready datasets para suporte a modelos de IA, Machine Learning e Agentes de IA, garantindo a qualidade e rastreabilidade dos dados.</li>
                        <li><strong>Qualidade, Governança & FinOps de Dados:</strong> Validação e consistência entre diferentes fontes no Data Lake, aplicando testes de dados, regras de qualidade e práticas de governança de indicadores.</li>
                        <li><strong>BI Avançado & Visualização:</strong> Desenvolvimento e manutenção de dashboards em Tableau, Looker Studio e Power BI, otimizando o tempo de resposta e consulta de relatórios analíticos em até 80%.</li>
                        <li><strong>Integrações & Versionamento:</strong> Versionamento de soluções analíticas via Git/GitHub, além de integrar modelos de ML via REST APIs e criar fluxos de dados automatizados em nuvem.</li>
                    </ul>
                </div>

                <div>
                    <div class="flex justify-between items-baseline">
                        <h3 class="text-[15px] font-bold text-slate-800">Estagiário de Análise de Dados</h3>
                        <span class="text-[13px] text-slate-500 font-medium">Jan/2022 – Ago/2023</span>
                    </div>
                    <p class="text-[13px] italic text-slate-500">Grupo OLX, Brasil</p>
                    <ul class="mt-2 list-disc ml-4 space-y-1.5 text-[13.5px] text-slate-700">
                        <li><strong>Alinhamento com Áreas Usuárias:</strong> Condução de reuniões de alinhamento com áreas de negócio para refinamento de requisitos, tradução de regras operacionais e entrega de diagnósticos quantitativos.</li>
                        <li><strong>Automação em Looker Studio & SQL:</strong> Construção e automação de relatórios analíticos recorrentes, reduzindo o esforço manual da equipe e aumentando a velocidade de geração de insights.</li>
                    </ul>
                </div>

            </div>
        </section>

        <hr class="my-6 border-slate-300">

        <!-- COMPETÊNCIAS TÉCNICAS -->
        <section class="mb-8">
            <h2 class="text-[15px] font-bold text-slate-800 uppercase mb-4">Habilidades Técnicas & Tecnologias</h2>
            <div class="grid grid-cols-2 gap-y-3 gap-x-8 text-[13.5px]">
                <div>
                    <span class="font-bold text-slate-800">SQL & Data Warehousing:</span>
                    <p class="text-slate-600">SQL Avançado, BigQuery (CTEs, Window Functions, Otimização, Particionamento), Snowflake, PostgreSQL</p>
                </div>
                <div>
                    <span class="font-bold text-slate-800">Business Intelligence (BI):</span>
                    <p class="text-slate-600">Tableau, Looker / Looker Studio, Power BI, Governança de Métricas & Camada Semântica</p>
                </div>
                <div>
                    <span class="font-bold text-slate-800">Analytics Engineering & Nuvem:</span>
                    <p class="text-slate-600">Python (Pandas, NumPy), dbt / Dataform, Git/GitHub, Composer, Docker, AWS, APIs REST</p>
                </div>
                <div>
                    <span class="font-bold text-slate-800">IA & Modelagem de Dados:</span>
                    <p class="text-slate-600">Serving-Ready Datasets para Agentes de IA, Feature Engineering, Análise Diagnóstica, Storytelling</p>
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
                    <p><strong>Inglês:</strong> Avançado / Fluente</p>
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
