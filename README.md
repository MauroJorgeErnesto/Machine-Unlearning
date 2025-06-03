Machine Unlearning em Modelos Supervisionados no Contexto da LGPD
⚠️ Projeto em desenvolvimento – este repositório está sendo atualizado continuamente conforme o progresso da pesquisa.

Este projeto explora técnicas de machine unlearning com foco na conformidade com a LGPD (Lei Geral de Proteção de Dados), ética em IA e eficiência computacional. A proposta busca garantir o direito ao esquecimento, permitindo a remoção de dados específicos de modelos treinados sem a necessidade de retrain completo.

🔍 Objetivo
Comparar estratégias de unlearning em tarefas de classificação de texto (detecção de discurso de ódio), avaliando impacto em desempenho, explicabilidade e viabilidade técnica.

⚙️ Tecnologias e Modelos Utilizados:
Python, scikit-learn, pandas, matplotlib

Random Forest: modelo base explicável e simbólico

SISA (Sharded, Isolated, Sliced, and Aggregated training): benchmark robusto

BERT (baseline NLP)

DaRE-RF: tentativa de uso da biblioteca oficial e desenvolvimento de versão simplificada

Tree-Based Selective Forgetting: abordagem própria com poda seletiva para unlearning eficiente e explicável

📊 Metodologia:
Simulação de pedidos de exclusão de dados com base no dataset HateBR

Avaliação das técnicas quanto ao:

🔹 Custo computacional

🔹 Fidelidade do esquecimento

🔹 Manutenção de métricas (acurácia, F1-score, precisão, recall)

🔹 Explicabilidade e rastreabilidade

📌 Destaques:
Implementação de unlearning sem retrain completo em modelos baseados em árvore

Alinhamento com regulamentações de privacidade e princípios de IA ética

Contribuição ativa em pesquisa aplicada com potencial de publicação científica

📁 Este repositório será atualizado conforme o avanço da implementação, testes e documentação.
