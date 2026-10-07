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
            <p class="text-lg text-slate-600 font-semibold mt-2">Analista de Dados & CRM Analytics Pleno | Databricks, BigQuery & BI</p>
            
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
                Cientista da Computação e Analista de Dados Pleno com mais de 3 anos de experiência em ambiente corporativo B2C de alto volume, atuando com análise de <strong>Funil de Vendas/Marketing, CRM Analytics e Business Intelligence</strong>. Especialista em <strong>SQL Avançado (CTEs, Window Functions, Joins complexos)</strong> em plataformas analíticas como <strong>Databricks e BigQuery</strong>. Domínio de <strong>Estatística Aplicada (Testes de Hipótese, Significância, Testes A/B e Grupos de Controle)</strong>, manipulação de dados com <strong>Python (Pandas, NumPy)</strong> e publicação autônoma de dashboards em <strong>Power BI, Tableau e Looker Studio</strong>. Forte habilidade na documentação de glossários de métricas e tradução de dados em decisões acionáveis para times de negócio.
            </p>
        </section>

        <!-- EXPERIÊNCIAS PROFISSIONAIS -->
        <section class="mb-8">
            <h2 class="text-[15px] font-bold text-slate-800 uppercase mb-4">Experiência Profissional</h2>

            <div class="space-y-6">

                <div>
                    <div class="flex justify-between items-baseline">
                        <h3 class="text-[15px] font-bold text-slate-800">Analista de Dados Pleno | Estratégia Comercial & Funil</h3>
                        <span class="text-[13px] text-slate-500 font-medium">Jun/2025 – Atual</span>
                    </div>
                    <p class="text-[13px] italic text-slate-500">Grupo OLX, Brasil (Ambiente B2C de Alto Volume)</p>
                    <ul class="mt-2 list-disc ml-4 space-y-1.5 text-[13.5px] text-slate-700">
                        <li><strong>Análise de Funil & Atribuição:</strong> Mapeamento do funil de vendas e conversão de marketing, definindo etapas, modelos de atribuição, safras e análises de cohort para identificação de gargalos em grandes volumes de transações.</li>
                        <li><strong>SQL Avançado em Databricks/BigQuery:</strong> Desenvolvimento e otimização de consultas SQL altamente complexas (CTEs, Window Functions, auditoria de dados) para extração de dados e geração de insights operacionais.</li>
                        <li><strong>Dashboards em Power BI & Tableau:</strong> Autonomia na modelagem, construção e publicação de painéis de performance comercial e eficiência de canais para suporte direto à tomada de decisão executiva.</li>
                        <li><strong>Automação com Python:</strong> Criação de rotinas em Python (Pandas/NumPy) para automação de extrações e relatórios recorrentes, reduzindo em 50% o tempo de processamento manual da equipe.</li>
                    </ul>
                </div>

                <div>
                    <div class="flex justify-between items-baseline">
                        <h3 class="text-[15px] font-bold text-slate-800">Analista de Dados Junior | Customer Experience & CRM Analytics</h3>
                        <span class="text-[13px] text-slate-500 font-medium">Set/2023 – Jun/2025</span>
                    </div>
                    <p class="text-[13px] italic text-slate-500">Grupo OLX, Brasil (Ambiente B2C de Alto Volume)</p>
                    <ul class="mt-2 list-disc ml-4 space-y-1.5 text-[13.5px] text-slate-700">
                        <li><strong>Estatística Aplicada & Experimentos A/B:</strong> Planejamento e validação de testes A/B, grupos de controle e testes de hipóteses estatísticas (análise de variância e significância) para otimização de jornadas de clientes e mensagens de CRM.</li>
                        <li><strong>Consultas em Plataformas de CRM & Data Lakes:</strong> Integração e análise de dados no Salesforce CRM e Databricks para avaliação de comportamento do usuário, retenção e churn.</li>
                        <li><strong>Modelagem & Looker Studio:</strong> Construção de relatórios analíticos dinâmicos no Looker Studio e Tableau com otimização de até 80% no tempo de consulta de bases volumosas.</li>
                        <li><strong>Documentação de Métricas:</strong> Elaboração de documentações funcionais, dicionários de dados e glossários do funil para padronização de conceitos entre áreas analíticas e de negócio.</li>
                    </ul>
                </div>

                <div>
                    <div class="flex justify-between items-baseline">
                        <h3 class="text-[15px] font-bold text-slate-800">Estagiário de Análise de Dados</h3>
                        <span class="text-[13px] text-slate-500 font-medium">Jan/2022 – Ago/2023</span>
                    </div>
                    <p class="text-[13px] italic text-slate-500">Grupo OLX, Brasil</p>
                    <ul class="mt-2 list-disc ml-4 space-y-1.5 text-[13.5px] text-slate-700">
                        <li><strong>Extração & Análise Quantitativa:</strong> Desenvolvimento de queries em SQL para extração de dados e suporte a diagnósticos quantitativos sobre interações de clientes.</li>
                        <li><strong>Automação de Relatórios:</strong> Construção e manutenção de painéis gerenciais no Google Sheets e Looker Studio para monitoramento diário de metas.</li>
                    </ul>
                </div>

            </div>
        </section>

        <hr class="my-6 border-slate-300">

        <!-- COMPETÊNCIAS TÉCNICAS -->
        <section class="mb-8">
            <h2 class="text-[15px] font-bold text-slate-800 uppercase mb-4">Habilidades Técnicas & Métodos</h2>
            <div class="grid grid-cols-2 gap-y-3 gap-x-8 text-[13.5px]">
                <div>
                    <span class="font-bold text-slate-800">SQL & Plataformas Analíticas:</span>
                    <p class="text-slate-600">SQL Avançado (CTEs, Window Functions, Otimização, Auditoria), Databricks, BigQuery, Synapse, Salesforce CRM</p>
                </div>
                <div>
                    <span class="font-bold text-slate-800">Estatística & Métodos Analíticos:</span>
                    <p class="text-slate-600">Testes A/B, Grupos de Controle, Testes de Hipótese, Significância, Análise de Funil, Cohort, Safras e Atribuição</p>
                </div>
                <div>
                    <span class="font-bold text-slate-800">Business Intelligence & BI:</span>
                    <p class="text-slate-600">Power BI, Tableau, Looker Studio (Modelagem, Publicação e Performance Tuning)</p>
                </div>
                <div>
                    <span class="font-bold text-slate-800">Programação & Documentação:</span>
                    <p class="text-slate-600">Python (Pandas, NumPy, Scikit-learn), Automação de Extrações, Git, Documentação de Glossários e Métricas</p>
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
