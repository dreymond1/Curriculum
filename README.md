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
            <p class="text-lg text-slate-600 font-semibold mt-2">Analista de BI & Dados Pleno | Power BI (DAX/DirectQuery), Databricks & SQL</p>
            
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
                Cientista da Computação e Analista de Dados Pleno com amplo domínio em <strong>Power BI (DAX avançado, modelagem de dados complexa e DirectQuery)</strong>, <strong>SQL</strong> e ecossistemas analíticos em <strong>Databricks</strong>. Experiência na construção e consulta de dados organizados em arquitetura de camadas (<strong>Bronze, Silver e Gold</strong>), garantindo governança, alta performance e <strong>qualidade de dados</strong> por meio da criação de regras de validação, tratamento de exceções e investigação de inconsistências. Habilidade comprovada em traduzir regras de negócio complexas em dashboards executivos e aplicações analíticas interativas desenvolvidas em <strong>Python, PySpark e Streamlit</strong>.
            </p>
        </section>

        <!-- EXPERIÊNCIAS PROFISSIONAIS -->
        <section class="mb-8">
            <h2 class="text-[15px] font-bold text-slate-800 uppercase mb-4">Experiência Profissional</h2>

            <div class="space-y-6">

                <div>
                    <div class="flex justify-between items-baseline">
                        <h3 class="text-[15px] font-bold text-slate-800">Analista de Dados Pleno | BI & Estratégia Comercial</h3>
                        <span class="text-[13px] text-slate-500 font-medium">Jun/2025 – Atual</span>
                    </div>
                    <p class="text-[13px] italic text-slate-500">Grupo OLX, Brasil</p>
                    <ul class="mt-2 list-disc ml-4 space-y-1.5 text-[13.5px] text-slate-700">
                        <li><strong>Power BI Avançado & DirectQuery:</strong> Desenvolvimento e otimização de soluções em Power BI aplicando modelagem dimensional (Star Schema), fórmulas DAX avançadas e DirectQuery para acesso em tempo real a grandes volumes de dados.</li>
                        <li><strong>Databricks & Arquitetura Medallion:</strong> Consulta e manipulação de pipelines e relatórios consumindo dados organizados nas camadas Bronze (raw), Silver (trada/limpa) e Gold (agregada/negócio) no Databricks.</li>
                        <li><strong>Tradução de Regras de Negócio:</strong> Mapeamento direto de necessidades com gestores comerciais para transformar regras de negócio complexas em indicadores de performance (KPIs) confiáveis.</li>
                        <li><strong>Validação & Automação com Python/PySpark:</strong> Criação de scripts em Python e PySpark para tratamento automatizado de dados e validação de inconsistências, otimizando o tempo de execução de consultas em 50%.</li>
                    </ul>
                </div>

                <div>
                    <div class="flex justify-between items-baseline">
                        <h3 class="text-[15px] font-bold text-slate-800">Analista de Dados Junior | Qualidade de Dados & Analytics</h3>
                        <span class="text-[13px] text-slate-500 font-medium">Set/2023 – Jun/2025</span>
                    </div>
                    <p class="text-[13px] italic text-slate-500">Grupo OLX, Brasil</p>
                    <ul class="mt-2 list-disc ml-4 space-y-1.5 text-[13.5px] text-slate-700">
                        <li><strong>Qualidade de Dados & Governança:</strong> Implementação de rotinas de qualidade de dados com criação de regras de validação, detecção de exceções e investigação contínua de divergências entre bases operacionais.</li>
                        <li><strong>Aplicações em Streamlit & Python:</strong> Desenvolvimento de ferramentas e webapps internos com Streamlit para visualização rápida e prototipagem de dados para apoio às áreas de suporte e produto.</li>
                        <li><strong>Consultas SQL Avançadas:</strong> Manipulação e validação de dados utilizando SQL (Window Functions, CTEs, Joins complexos) sobre Data Lakes e bancos relacionais.</li>
                        <li><strong>Dashboards Executivos:</strong> Construção de painéis no Power BI e Tableau para monitoramento de métricas operacionais, reduzindo o tempo de identificação de falhas em até 80%.</li>
                    </ul>
                </div>

                <div>
                    <div class="flex justify-between items-baseline">
                        <h3 class="text-[15px] font-bold text-slate-800">Estagiário de Análise de Dados</h3>
                        <span class="text-[13px] text-slate-500 font-medium">Jan/2022 – Ago/2023</span>
                    </div>
                    <p class="text-[13px] italic text-slate-500">Grupo OLX, Brasil</p>
                    <ul class="mt-2 list-disc ml-4 space-y-1.5 text-[13.5px] text-slate-700">
                        <li><strong>Tratamento de Dados & Suporte:</strong> Extração, limpeza e cruzamento de dados via SQL e relatórios em Power BI/Google Sheets para identificação de inconsistências de cadastro.</li>
                        <li><strong>Acompanhamento de Processos:</strong> Apoio na documentação de regras de validação e validação quantitativa de indicadores operacionais da área.</li>
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
                    <span class="font-bold text-slate-800">Power BI & BI Avançado:</span>
                    <p class="text-slate-600">Power BI (DAX Avançado, Modelagem de Dados, DirectQuery, Performance Tuning), Tableau</p>
                </div>
                <div>
                    <span class="font-bold text-slate-800">Databricks & Arquitetura de Dados:</span>
                    <p class="text-slate-600">Databricks, Arquitetura Medallion (Bronze, Silver, Gold), Data Lakes, Data Warehouse</p>
                </div>
                <div>
                    <span class="font-bold text-slate-800">SQL & Qualidade de Dados:</span>
                    <p class="text-slate-600">SQL Avançado (Manipulação e Validação), Regras de Qualidade de Dados, Tratamento de Exceções</p>
                </div>
                <div>
                    <span class="font-bold text-slate-800">Linguagens & Aplicações:</span>
                    <p class="text-slate-600">Python, PySpark, Streamlit (Aplicações de Dados), Git/GitHub, Regras de Negócio</p>
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
