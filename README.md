🛡️ Projecto Zuber: Auditoria Técnica e Análise de Produção (Chicago)

Responsável Técnico: André Vinagre

Este repositório contém o relatório técnico e a análise estatística desenvolvida para a entrada da empresa Zuber no mercado competitivo de Chicago. O projecto foi construído sob uma ótica de auditoria rigorosa, transformando dados brutos de um ambiente de aprendizagem em insights valiosos de nível executivo.

📊 Dashboard Interactivo

Pode visualizar os resultados finais através do link:
👉 Visualizar Dashboard em Produção
 https://andrevinagre77-dev.github.io/zuber-chicago-analysis/

🛠️ Metodologia de Auditoria (Padrão André Vinagre)

Seguindo o princípio de "No Data, No Audit", a análise foi estruturada em três pilares fundamentais:

1. Veto GIGO (Garbage In, Garbage Out)

Antes de qualquer análise, os dados foram submetidos a um processo de limpeza profunda:

Deduplicação: Remoção de 18,4% de entradas redundantes detectadas nos resultados de SQL.

Sanitização: Verificação de tipos de dados para evitar erros de cálculo em volumes de viagens e médias de tempo.

2. Validação Estatística

A tomada de decisão não foi baseada em suposições, mas em evidência matemática:

Teste de Hipótese: Avaliámos se a duração das viagens muda nos sábados chuvosos.

Protocolo: Aplicação do Teste t de Student para amostras independentes.

Rigor: Teste de Levene prévio para certificar a igualdade de variâncias.

Resultado: p-value de 6.51e-12, resultando na rejeição da Hipótese Nula (H0).

3. Análise de Performance e Mercado

Market Share: Identificação do monopólio da Flash Cab como principal barreira competitiva.

Densidade Geográfica: Mapeamento dos clusters de maior procura (Loop e River North).

📂 Estrutura do Repositório

index.html: Dashboard executivo construído com Tailwind CSS e Chart.js.

notebooks/: Análise exploratória em Python (Jupyter Notebook) com estatísticas detalhadas.

data/: Datasets auditados em formato CSV (project_sql_result_01.csv, 04.csv, 07.csv).

🚀 Como Executar

Clone o repositório: git clone https://github.com/seu-usuario/seu-repositorio.git

Abra o index.html em qualquer navegador moderno para ver as visualizações.

Os dados originais e o código de limpeza estão na pasta notebooks.

✍️ Conclusão Técnica

O clima em Chicago é um driver de custo. A análise estatística provou que a Zuber deve implementar algoritmos de Preço Dinâmico durante condições climáticas adversas para proteger a margem de lucro e garantir a disponibilidade de motoristas.

"Dados sem auditoria são apenas opiniões. Esta análise garante a base matemática para a expansão da Zuber." — André Vinagre

© 2024 Projecto Zuber Chicago - Propriedade de André Vinagre.
