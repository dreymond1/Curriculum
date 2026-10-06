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
            <p class="text-lg text-slate-600 font-semibold mt-2">Data Engineer & Data Analyst Pleno | Databricks, PySpark & CRM Analytics</p>
            
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
                Cientista da Computação e Analista/Engenheiro de Dados Pleno com sólida experiência no desenvolvimento de <strong>pipelines de dados (ETL/ELT) em Databricks (PySpark, Spark SQL e Jobs)</strong>. Especialista em <strong>SQL Analítico Avançado (CTEs, Window Functions QUALIFY, MERGE incremental e deduplicação)</strong> para criação de atributos e eventos voltados a plataformas de CRM/CDP (Salesforce, Insider e similares). Atuação destacada na sustentação de fluxos, observabilidade de volumetria, investigação de causa raiz, governança de dados cadastrais (Golden Record/MDM) e otimização de performance e custos em arquiteturas de nuvem.
            </p>
        </section>

        <!-- EXPERIÊNCIAS PROFISSIONAIS -->
        <section class="mb-8">
            <h2 class="text-[15px] font-bold text-slate-800 uppercase mb-4">Experiência Profissional</h2>

            <div class="space-y-6">

                <div>
                    <div class="flex justify-between items-baseline">
                        <h3 class="text-[15px] font-bold text-slate-800">Analista de Dados Pleno | Estratégia Comercial & Engenharia</h3>
                        <span class="text-[13px] text-slate-500 font-medium">Jun/2025 – Atual</span>
                    </div>
                    <p class="text-[13px] italic text-slate-500">Grupo OLX, Brasil</p>
                    <ul class="mt-2 list-disc ml-4 space-y-1.5 text-[13.5px] text-slate-700">
                        <li><strong>Pipelines em Databricks & Spark SQL:</strong> Desenvolvimento e manutenção de jobs agendados e notebooks em PySpark e Spark SQL para ingestão e transformação de grandes volumes de dados no Data Lake.</li>
                        <li><strong>SQL Avançado & Operações Incrementais:</strong> Escrita de consultas complexas utilizando CTEs, Window Functions (QUALIFY, ROW_NUMBER) e rotinas de MERGE/upsert incremental para deduplicação e tratamento de divergências.</li>
                        <li><strong>Automação de Atributos & Métricas:</strong> Construção e automação de fluxos analíticos que geram regras de negócio e eventos operacionais (KPIs de recompra, churn e comportamento de uso), reduzindo em 50% o tempo manual de atualização.</li>
                        <li><strong>Observabilidade & Qualidade de Dados:</strong> Monitoramento contínuo de volumetria, validação entre visões de origem e destino, além do ajuste de parâmetros para garantia da consistência dos dados.</li>
                    </ul>
                </div>

                <div>
                    <div class="flex justify-between items-baseline">
                        <h3 class="text-[15px] font-bold text-slate-800">Analista de Dados Junior | Customer Experience & CRM Analytics</h3>
                        <span class="text-[13px] text-slate-500 font-medium">Set/2023 – Jun/2025</span>
                    </div>
                    <p class="text-[13px] italic text-slate-500">Grupo OLX, Brasil</p>
                    <ul class="mt-2 list-disc ml-4 space-y-1.5 text-[13.5px] text-slate-700">
                        <li><strong>Gestão de Atributos de CRM & Salesforce:</strong> Criação e manutenção de relatórios e atributos de clientes (como NPS, comportamento de interação e ciclo de vida) integrados ao Salesforce CRM.</li>
                        <li><strong>Higienização Cadastral & Governança (MDM):</strong> Tratamento e padronização de dados sensíveis e cadastrais (CPF, e-mail, telefone, tratamento de fuso/timestamps e nulos) garantindo consistência no Data Lake.</li>
                        <li><strong>Investigação de Incidentes & Sustentação:</strong> Análise de divergências de dados entre origem e destino, atuando na investigação de causa raiz e reprocessamento contínuo de dados operacionais.</li>
                        <li><strong>Dashboards & Monitoramento:</strong> Construção de painéis de acompanhamento de performance em Tableau e Looker Studio com otimização de até 80% do tempo de execução de rotinas de análise.</li>
                    </ul>
                </div>

                <div>
                    <div class="flex justify-between items-baseline">
                        <h3 class="text-[15px] font-bold text-slate-800">Estagiário de Análise de Dados</h3>
                        <span class="text-[13px] text-slate-500 font-medium">Jan/2022 – Ago/2023</span>
                    </div>
                    <p class="text-[13px] italic text-slate-500">Grupo OLX, Brasil</p>
                    <ul class="mt-2 list-disc ml-4 space-y-1.5 text-[13.5px] text-slate-700">
                        <li><strong>Consultas SQL & Tratamento de Origens:</strong> Extração e análise de dados operacionais via SQL para identificar inconsistências cadastrais e suportar o time de atendimento.</li>
                        <li><strong>Versionamento & Métodos Ágeis:</strong> Participação ativa em squads ágeis (Scrum/Kanban) utilizando controle de versão com Git (pull requests) e automação de relatórios.</li>
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
                    <span class="font-bold text-slate-800">Engenharia de Dados & Big Data:</span>
                    <p class="text-slate-600">Databricks (Notebooks/Jobs), Apache Spark (PySpark), Python, ETL/ELT, Pipelines Incrementais</p>
                </div>
                <div>
                    <span class="font-bold text-slate-800">SQL Avançado & Manipulação:</span>
                    <p class="text-slate-600">Spark SQL, CTEs, Window Functions (QUALIFY), MERGE/Upsert, Deduplicação, Query Tuning</p>
                </div>
                <div>
                    <span class="font-bold text-slate-800">CRM, CDP & Observabilidade:</span>
                    <p class="text-slate-600">Salesforce, Integração de Eventos/Atributos de CRM, Validação de Volumetria, Golden Record (MDM)</p>
                </div>
                <div>
                    <span class="font-bold text-slate-800">Ferramentas & Metodologias:</span>
                    <p class="text-slate-600">Git/GitHub (Pull Requests), Azure DevOps, Scrum/Kanban, REST APIs, Tableau, Databricks SQL</p>
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
