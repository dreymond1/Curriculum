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
        
        <!-- CABEÇALHO (Otimizado sem emojis para ATS) -->
        <header>
            <h1 class="text-[32px] font-bold text-slate-800 leading-none">Andrey Alves</h1>
            <p class="text-lg text-slate-600 font-semibold mt-2">Data Analyst & Data Engineer</p>
            
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
                Cientista da Computação e Analista de Dados Pleno com sólida atuação em Engenharia de Dados, Business Intelligence e Inteligência Artificial. Especialista na automação de pipelines analíticos e extração de valor de grandes volumes de dados (Data Lake), unindo o rigor técnico de Python e SQL à visão estratégica de negócios. Histórico comprovado na otimização de processos operacionais em até 80%, arquitetura de dashboards executivos (Tableau/Looker) e desenvolvimento de aplicações de IA Generativa (LLMs, RAG e agentes autônomos) voltadas para suporte à tomada de decisão estratégica.
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
                        <li><strong>Automação & Processos:</strong> Automatizei rotinas e processos operacionais críticos utilizando Python e SQL, eliminando atualizações manuais e reduzindo em 50% o tempo de execução das atividades da equipe.</li>
                        <li><strong>Análise Estratégica & Business Intelligence:</strong> Liderei o acompanhamento dos principais KPIs comerciais (receita, churn, LTV e performance de produto), estruturando visões analíticas para a alta gestão.</li>
                        <li><strong>Data Visualization & Performance:</strong> Desenvolvi e otimizei dashboards executivos em Tableau e Google Sheets, identificando e corrigindo gargalos de performance em bases de dados complexas.</li>
                        <li><strong>Inteligência de Mercado:</strong> Conduzi análises preditivas e comportamentais nos setores Automotivo e Imobiliário, gerando insights acionáveis para direcionamento de estratégias de vendas e posicionamento.</li>
                    </ul>
                </div>

                <div>
                    <div class="flex justify-between items-baseline">
                        <h3 class="text-[15px] font-bold text-slate-800">Analista de Dados Junior | Customer Experience</h3>
                        <span class="text-[13px] text-slate-500 font-medium">Set/2023 – Jun/2025</span>
                    </div>
                    <p class="text-[13px] italic text-slate-500">Grupo OLX, Brasil</p>
                    <ul class="mt-2 list-disc ml-4 space-y-1.5 text-[13.5px] text-slate-700">
                        <li><strong>Machine Learning & IA Generativa:</strong> Implementei modelos preditivos e de análise de sentimentos baseados em Redes Neurais e LLMs para classificação automatizada de feedbacks, otimizando o tempo de análise em até 80%.</li>
                        <li><strong>Engenharia de Analytics & APIs:</strong> Desenvolvi e disponibilizei REST APIs em ambiente de nuvem (AWS) para integração de modelos de ML com sistemas operacionais internos.</li>
                        <li><strong>Data Lake & Análise Exploratória:</strong> Analisei grandes volumes de dados não estruturados no Data Lake, identificando padrões, anomalias de produto e gargalos de eficiência operacional.</li>
                        <li><strong>Dashboards & CRM Analytics:</strong> Estruturei painéis dinâmicos no Tableau, Looker Studio e Salesforce, unificando métricas de CX e facilitando a tomada de decisão entre diferentes stakeholders.</li>
                        <li><strong>Análise Estatística Avançada:</strong> Apliquei modelagem estatística (regressão, correlação e detecção de outliers) para garantir maior acurácia nas projeções e diagnósticos operacionais.</li>
                    </ul>
                </div>

                <div>
                    <div class="flex justify-between items-baseline">
                        <h3 class="text-[15px] font-bold text-slate-800">Estagiário de Análise de Dados</h3>
                        <span class="text-[13px] text-slate-500 font-medium">Jan/2022 – Ago/2023</span>
                    </div>
                    <p class="text-[13px] italic text-slate-500">Grupo OLX, Brasil</p>
                    <ul class="mt-2 list-disc ml-4 space-y-1.5 text-[13.5px] text-slate-700">
                        <li><strong>Automação de Relatórios:</strong> Automatizei a geração de relatórios periódicos no Looker Studio e Google Sheets via queries SQL, garantindo atualização em tempo real e maior ganho de eficiência.</li>
                        <li><strong>Suporte Operacional & Insights:</strong> Realizei análises quantitativas e qualitativas para suporte direto às operações de atendimento, identificando causas raízes de inconsistências.</li>
                        <li><strong>Benchmarking & Mercado:</strong> Conduzi o monitoramento contínuo de concorrência e tendências de mercado para respaldar o planejamento estratégico de melhorias do produto.</li>
                    </ul>
                </div>

            </div>
        </section>

        <hr class="my-6 border-slate-300">

        <!-- COMPETÊNCIAS TÉCNICAS (Agrupadas e ricas em palavras-chave para ATS) -->
        <section class="mb-8">
            <h2 class="text-[15px] font-bold text-slate-800 uppercase mb-4">Habilidades Técnicas & Tecnologias</h2>
            <div class="grid grid-cols-2 gap-y-3 gap-x-8 text-[13.5px]">
                <div>
                    <span class="font-bold text-slate-800">Linguagens & Scripts:</span>
                    <p class="text-slate-600">Python (Pandas, NumPy, Scikit-learn), SQL, JavaScript, HTML/CSS</p>
                </div>
                <div>
                    <span class="font-bold text-slate-800">Engenharia de Dados & Cloud:</span>
                    <p class="text-slate-600">ETL/ELT, Apache Spark, Airflow, Docker, Kafka, AWS, Git/GitHub</p>
                </div>
                <div>
                    <span class="font-bold text-slate-800">Data Visualization & BI:</span>
                    <p class="text-slate-600">Tableau, Looker Studio (Data Studio), Google Sheets Avançado, Salesforce</p>
                </div>
                <div>
                    <span class="font-bold text-slate-800">Inteligência Artificial & Machine Learning:</span>
                    <p class="text-slate-600">LLMs, Arquiteturas RAG, Agentes Autônomos, Redes Neurais, Streamlit, REST APIs</p>
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
