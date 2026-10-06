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
            <p class="text-lg text-slate-600 font-semibold mt-2">CRM Analytics & BI Specialist | MarTech, Databricks & Salesforce</p>
            
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
                Cientista da Computação e Analista de Dados Pleno com mais de 3 anos de experiência em ambiente corporativo B2C de alto volume, atuando na interseção entre <strong>CRM Analytics, Business Intelligence e MarTech</strong>. Especialista em traduzir perguntas complexas de negócio em análises diagnósticas, frameworks de mensuração de funil e recomendações acionáveis. Forte domínio de <strong>SQL Avançado (Databricks, PostgreSQL)</strong>, <strong>Estatística Aplicada (Testes A/B/N e Grupos de Controle)</strong>, modelagem em <strong>Power BI, Tableau e Looker Studio</strong>, além de integração de dados em ecossistemas Salesforce (Sales Cloud & Marketing Cloud Engagement). Atuação consultiva e remota com facilidade em Storytelling, alinhamento com stakeholders e governança/LGPD.
            </p>
        </section>

        <!-- EXPERIÊNCIAS PROFISSIONAIS -->
        <section class="mb-8">
            <h2 class="text-[15px] font-bold text-slate-800 uppercase mb-4">Experiência Profissional</h2>

            <div class="space-y-6">

                <div>
                    <div class="flex justify-between items-baseline">
                        <h3 class="text-[15px] font-bold text-slate-800">Analista de Dados Pleno | Estratégia Comercial & CRM Analytics</h3>
                        <span class="text-[13px] text-slate-500 font-medium">Jun/2025 – Atual</span>
                    </div>
                    <p class="text-[13px] italic text-slate-500">Grupo OLX, Brasil</p>
                    <ul class="mt-2 list-disc ml-4 space-y-1.5 text-[13.5px] text-slate-700">
                        <li><strong>Análise de Funil & Performance de Vendas:</strong> Estruturação de frameworks de mensuração de funil de conversão (origem, etapa, canal e safra/cohort), identificando gargalos e gerando recomendações que aumentaram a produtividade comercial.</li>
                        <li><strong>SQL Avançado em Databricks & Data Lake:</strong> Elaboração de queries complexas (CTEs, Window Functions, Joins avançados) no Databricks para exploração, segmentação e auditoria de volumetria e conversão assistida vs. digital.</li>
                        <li><strong>Dashboards Executivos em Power BI & Tableau:</strong> Arquitetura de painéis operacionais e executivos de acompanhamento de KPIs, SLAs e eficiência de canais para tomada de decisão em ritos de revisão estratégica.</li>
                        <li><strong>Especificação de Requisitos & Parceria Técnica:</strong> Tradução de necessidades de CRM/Comercial em requisitos de dados (campos, eventos e sinais), repassando especificações técnicas ao time de Engenharia de Dados.</li>
                    </ul>
                </div>

                <div>
                    <div class="flex justify-between items-baseline">
                        <h3 class="text-[15px] font-bold text-slate-800">Analista de Dados Junior | Customer Experience & CRM</h3>
                        <span class="text-[13px] text-slate-500 font-medium">Set/2023 – Jun/2025</span>
                    </div>
                    <p class="text-[13px] italic text-slate-500">Grupo OLX, Brasil</p>
                    <ul class="mt-2 list-disc ml-4 space-y-1.5 text-[13.5px] text-slate-700">
                        <li><strong>Estatística Aplicada & Desenho de Experimentos:</strong> Planejamento e avaliação de testes A/B/N, grupos de controle e significância estatística para mensuração do impacto de novas abordagens e réguas de comunicação.</li>
                        <li><strong>Segmentação de Audiências & Lead Scoring:</strong> Construção de segmentações dinâmicas por perfil e comportamento no Salesforce CRM, aplicando regras de elegibilidade, supressão, opt-in/opt-out e conformidade com LGPD.</li>
                        <li><strong>Auditoria & Qualidade de Dados:</strong> Auditoria contínua de duplicidades e completude de bases de Leads e Contatos, otimizando em até 80% o tempo de processamento das rotinas analíticas.</li>
                        <li><strong>Prototipagem em Python:</strong> Utilização de Python (Pandas, NumPy) para análise exploratória, tratamento estatístico e automação de extrações de dados.</li>
                    </ul>
                </div>

                <div>
                    <div class="flex justify-between items-baseline">
                        <h3 class="text-[15px] font-bold text-slate-800">Estagiário de Análise de Dados</h3>
                        <span class="text-[13px] text-slate-500 font-medium">Jan/2022 – Ago/2023</span>
                    </div>
                    <p class="text-[13px] italic text-slate-500">Grupo OLX, Brasil</p>
                    <ul class="mt-2 list-disc ml-4 space-y-1.5 text-[13.5px] text-slate-700">
                        <li><strong>Geração de Reports & Visualização:</strong> Desenvolvimento e publicação de relatórios analíticos em Looker Studio, Google Sheets e SQL para acompanhamento de indicadores operacionais.</li>
                        <li><strong>Documentação & Glossário de Métricas:</strong> Mapeamento de regras de negócio e criação de glossários de indicadores para padronização de conceitos entre times técnicos e de atendimento.</li>
                    </ul>
                </div>

            </div>
        </section>

        <hr class="my-6 border-slate-300">

        <!-- COMPETÊNCIAS TÉCNICAS -->
        <section class="mb-8">
            <h2 class="text-[15px] font-bold text-slate-800 uppercase mb-4">Habilidades Técnicas & Domínio de Negócio</h2>
            <div class="grid grid-cols-2 gap-y-3 gap-x-8 text-[13.5px]">
                <div>
                    <span class="font-bold text-slate-800">SQL & Plataformas Analíticas:</span>
                    <p class="text-slate-600">SQL Avançado (CTEs, Window Functions, Joins), Databricks, BigQuery, PostgreSQL</p>
                </div>
                <div>
                    <span class="font-bold text-slate-800">BI & Visualização de Dados:</span>
                    <p class="text-slate-600">Power BI (DAX, Modelagem), Tableau, Looker Studio, Apresentações Executivas</p>
                </div>
                <div>
                    <span class="font-bold text-slate-800">MarTech, CRM & Governança:</span>
                    <p class="text-slate-600">Salesforce (Sales Cloud, Marketing Cloud), Análise de Funil, Atribuição, Lead Scoring, LGPD</p>
                </div>
                <div>
                    <span class="font-bold text-slate-800">Estatística & Programação:</span>
                    <p class="text-slate-600">Python (Pandas, NumPy), Testes A/B/N, Grupos de Controle, Cohort/Safras, Git, Métodos Ágeis</p>
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
                    <p><strong>Inglês:</strong> Avançado</p>
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
