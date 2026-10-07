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
            <p class="text-lg text-slate-600 font-semibold mt-2">Data Engineer Pleno | Cloud (AWS, GCP, Azure), Spark & Pipelines ETL/ELT</p>
            
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
                Engenheiro e Analista de Dados Pleno com graduação em <strong>Ciência da Computação (CEFET/RJ)</strong> e ampla experiência na construção, automação e otimização de pipelines de dados (<strong>ETL/ELT</strong>). Sólidos conhecimentos em programação orientada a objetos com <strong>Python, SQL avançado e processamento distribuído (Apache Spark, Kafka)</strong>. Atuação com arquiteturas em nuvem (<strong>AWS, GCP e Azure</strong>), orquestração de dados via <strong>Airflow e Glue</strong>, além da criação e consumo de <strong>APIs REST</strong>. Experiência na prestação de serviços analíticos remotos para grandes clientes corporativos, construindo pontes entre times técnicos, plataformas como <strong>Google Looker Studio</strong> e a <strong>liderança executiva</strong>.
            </p>
        </section>

        <!-- EXPERIÊNCIAS PROFISSIONAIS -->
        <section class="mb-8">
            <h2 class="text-[15px] font-bold text-slate-800 uppercase mb-4">Experiência Profissional</h2>

            <div class="space-y-6">

                <div>
                    <div class="flex justify-between items-baseline">
                        <h3 class="text-[15px] font-bold text-slate-800">Engenheiro & Analista de Dados Pleno</h3>
                        <span class="text-[13px] text-slate-500 font-medium">Jun/2025 – Atual</span>
                    </div>
                    <p class="text-[13px] italic text-slate-500">Grupo OLX, Brasil</p>
                    <ul class="mt-2 list-disc ml-4 space-y-1.5 text-[13.5px] text-slate-700">
                        <li><strong>Pipelines ETL/ELT & Processamento Distribuído:</strong> Desenho, implementação e otimização de pipelines de dados escaláveis utilizando Python (Orientação a Objetos) e Apache Spark para ingestão de grandes volumes.</li>
                        <li><strong>Orquestração em Nuvem & Cloud (AWS/GCP):</strong> Configuração de rotinas automatizadas e fluxos de trabalho via Airflow e AWS Glue, reduzindo em 50% o tempo operacional de atualização de bases.</li>
                        <li><strong>Apresentações Executivas & Stakeholders:</strong> Interface direta com liderança executiva e diretores para apresentação de KPIs estratégicos, garantindo alinhamento de requisitos e decisões orientadas a dados.</li>
                        <li><strong>Visualização & Dashboards:</strong> Desenvolvimento de visões executivas e relatórios em Google Looker Studio e Tableau para acompanhamento de métricas de negócio e performance de produtos.</li>
                    </ul>
                </div>

                <div>
                    <div class="flex justify-between items-baseline">
                        <h3 class="text-[15px] font-bold text-slate-800">Analista de Dados Junior | Engenharia de Dados</h3>
                        <span class="text-[13px] text-slate-500 font-medium">Set/2023 – Jun/2025</span>
                    </div>
                    <p class="text-[13px] italic text-slate-500">Grupo OLX, Brasil</p>
                    <ul class="mt-2 list-disc ml-4 space-y-1.5 text-[13.5px] text-slate-700">
                        <li><strong>Desenvolvimento de APIs REST & Integrações:</strong> Construção e disponibilização de APIs REST em ambiente Cloud para servir modelos analíticos e integrar dados entre sistemas corporativos.</li>
                        <li><strong>Streaming & Arquitetura de Eventos:</strong> Apoio na sustentação de fluxos de dados distribuídos com Apache Kafka e Data Lakes corporativos.</li>
                        <li><strong>Trabalho Remoto com Clientes Corporativos:</strong> Atuação em squad remota prestando suporte técnico e soluções analíticas de alta disponibilidade para diferentes áreas de negócio.</li>
                        <li><strong>Qualidade de Dados & SQL:</strong> Execução de consultas SQL avançadas (Window Functions, CTEs, Joins complexos) para auditoria e garantia da consistência dos pipelines.</li>
                    </ul>
                </div>

                <div>
                    <div class="flex justify-between items-baseline">
                        <h3 class="text-[15px] font-bold text-slate-800">Estagiário de Dados</h3>
                        <span class="text-[13px] text-slate-500 font-medium">Jan/2022 – Ago/2023</span>
                    </div>
                    <p class="text-[13px] italic text-slate-500">Grupo OLX, Brasil</p>
                    <ul class="mt-2 list-disc ml-4 space-y-1.5 text-[13.5px] text-slate-700">
                        <li><strong>Automação em Looker Studio & SQL:</strong> Desenvolvimento de relatórios e automação de extrações em SQL e Google Looker Studio para equipes operacionais.</li>
                        <li><strong>Versionamento & Processos:</strong> Documentação técnica de rotinas e controle de versão de código utilizando Git e métodos ágeis.</li>
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
                    <span class="font-bold text-slate-800">Linguagens & Engenharia de Dados:</span>
                    <p class="text-slate-600">Python (Orientação a Objetos), SQL Avançado, Desenvolvimento e Criação de APIs REST</p>
                </div>
                <div>
                    <span class="font-bold text-slate-800">Engenharia Cloud & Orquestração:</span>
                    <p class="text-slate-600">Cloud (AWS, GCP, Azure), Apache Airflow, AWS Glue, Arquiteturas ETL/ELT</p>
                </div>
                <div>
                    <span class="font-bold text-slate-800">Sistemas Distribuídos & Big Data:</span>
                    <p class="text-slate-600">Apache Spark (PySpark), Apache Kafka, Hadoop, Data Lakes, Docker, Git</p>
                </div>
                <div>
                    <span class="font-bold text-slate-800">Visualização & Gestão Executiva:</span>
                    <p class="text-slate-600">Google Looker Studio, Tableau, Interface com Liderança Executiva, Atendimento Corporativo Remoto</p>
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
