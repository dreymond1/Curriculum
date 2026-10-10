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
            <p class="text-lg text-slate-600 font-semibold mt-2">Analista de Dados & IA Pleno | Python, Machine Learning, Power BI & SQL</p>
            
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
                Cientista da Computação e Analista de Dados Pleno com sólida experiência no manuseio de grandes volumes de dados, modelagem preditiva e projetos de <strong>transformação digital e automação inteligente</strong>. Domínio avançado em <strong>Python, SQL e Power BI</strong> para análise exploratória, construção de pipelines ETL e visualização de indicadores estratégicos. Atuação destacada no desenvolvimento de soluções de <strong>Machine Learning, Redes Neurais e IA Generativa (LLMs, RAG e agentes autônomos)</strong>, combinando estatística aplicada, <strong>simulação de cenários e otimização matemática</strong> para acelerar a tomada de decisão operacional e comercial.
            </p>
        </section>

        <!-- EXPERIÊNCIAS PROFISSIONAIS -->
        <section class="mb-8">
            <h2 class="text-[15px] font-bold text-slate-800 uppercase mb-4">Experiência Profissional</h2>

            <div class="space-y-6">

                <div>
                    <div class="flex justify-between items-baseline">
                        <h3 class="text-[15px] font-bold text-slate-800">Analista de Dados Pleno | Transformação Digital & Estratégia</h3>
                        <span class="text-[13px] text-slate-500 font-medium">Jun/2025 – Atual</span>
                    </div>
                    <p class="text-[13px] italic text-slate-500">Grupo OLX, Brasil</p>
                    <ul class="mt-2 list-disc ml-4 space-y-1.5 text-[13.5px] text-slate-700">
                        <li><strong>Automação de Dados & Pipelines ETL em Python:</strong> Desenvolvimento de rotinas em Python e SQL para extração, limpeza e automação de grandes volumes de dados, reduzindo em 50% o tempo operacional das atividades da área.</li>
                        <li><strong>Visualização de Indicadores no Power BI:</strong> Arquitetura de dashboards dinâmicos no Power BI e Tableau com foco em simulação de cenários comerciais, acompanhamento de KPIs de receita e eficiência de produto.</li>
                        <li><strong>Aplicações de IA & Otimização:</strong> Liderança técnica na implementação de fluxos apoiados por IA Generativa e algoritmos de otimização para apoio à decisão tática e estratégia comercial.</li>
                        <li><strong>Análise Estatística & Preditiva:</strong> Aplicação de modelos estatísticos e simulações para acompanhamento do mercado automotivo e imobiliário, identificando tendências e oportunidades de crescimento.</li>
                    </ul>
                </div>

                <div>
                    <div class="flex justify-between items-baseline">
                        <h3 class="text-[15px] font-bold text-slate-800">Analista de Dados Junior | Machine Learning & Analytics</h3>
                        <span class="text-[13px] text-slate-500 font-medium">Set/2023 – Jun/2025</span>
                    </div>
                    <p class="text-[13px] italic text-slate-500">Grupo OLX, Brasil</p>
                    <ul class="mt-2 list-disc ml-4 space-y-1.5 text-[13.5px] text-slate-700">
                        <li><strong>Modelos de Machine Learning & Redes Neurais:</strong> Desenvolvimento e implementação de modelos preditivos e de análise de sentimentos em Python (Scikit-learn, TensorFlow/PyTorch) para classificação automatizada de feedbacks e interações.</li>
                        <li><strong>Transformação Digital com IA Generativa:</strong> Implementação de aplicações baseadas em LLMs e arquiteturas RAG para automação de triagens analíticas e extração de insights de dados não estruturados do Data Lake.</li>
                        <li><strong>Estatística Aplicada & Detecção de Anomalidades:</strong> Aplicação de regressões, correlações e técnicas de detecção de outliers para ajuste de modelos e otimização de até 80% no tempo gasto em rotinas operacionais.</li>
                        <li><strong>Servimento via APIs & Cloud:</strong> Disponibilização de modelos de Machine Learning via REST APIs em ambiente de nuvem (AWS) para consumo por sistemas e dashboards internos.</li>
                    </ul>
                </div>

                <div>
                    <div class="flex justify-between items-baseline">
                        <h3 class="text-[15px] font-bold text-slate-800">Estagiário de Análise de Dados</h3>
                        <span class="text-[13px] text-slate-500 font-medium">Jan/2022 – Ago/2023</span>
                    </div>
                    <p class="text-[13px] italic text-slate-500">Grupo OLX, Brasil</p>
                    <ul class="mt-2 list-disc ml-4 space-y-1.5 text-[13.5px] text-slate-700">
                        <li><strong>Análises Quantitativas em SQL:</strong> Execução de consultas SQL e relatórios no Google Sheets/Excel para validação de hipóteses e suporte à tomada de decisão.</li>
                        <li><strong>Automação de Relatórios:</strong> Criação de visões analíticas automatizadas no Looker Studio, acelerando o tempo de resposta e acompanhamento de metas diárias.</li>
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
                    <span class="font-bold text-slate-800">Linguagens & Modelagem:</span>
                    <p class="text-slate-600">Python (Pandas, NumPy, Scikit-learn), SQL Avançado, Power BI (DAX, Modelagem)</p>
                </div>
                <div>
                    <span class="font-bold text-slate-800">Machine Learning & Inteligência Artificial:</span>
                    <p class="text-slate-600">Redes Neurais, Modelos Preditivos, Análise de Sentimentos, IA Generativa (LLMs, RAG, Agentes Autônomos)</p>
                </div>
                <div>
                    <span class="font-bold text-slate-800">Estatística & Otimização:</span>
                    <p class="text-slate-600">Estatística Aplicada, Regressão, Detecção de Outliers, Simulação de Cenários, Otimização Matemática</p>
                </div>
                <div>
                    <span class="font-bold text-slate-800">Engenharia de Dados & Nuvem:</span>
                    <p class="text-slate-600">Pipelines ETL, Grandes Volumes (Data Lake), AWS, REST APIs, Git/GitHub, Tableau, Streamlit</p>
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
