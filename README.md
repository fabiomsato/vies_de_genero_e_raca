Viés de Gênero e Raça em Imagens Geradas por IA

📌 Sobre o Projeto

Este repositório apresenta um método estatisticamente fundamentado para detecção e mitigação de vieses demográficos (gênero e raça) em imagens geradas por Inteligência Artificial.

O estudo combina:

- Testes formais de hipótese

- Intervalos de confiança (incluindo BCa)

- Bootstrap

- Simulações de Monte Carlo

- Ajuste iterativo de prompts

O objetivo é avaliar a confiabilidade estatística da detecção de vieses e propor uma estratégia prática de mitigação por meio da otimização automatizada de prompts.

🎯 Objetivos

- Detectar desequilíbrios de gênero e raça em coleções de imagens geradas por IA.

- Quantificar incerteza estatística por meio de reamostragem.

- Comparar diferentes plataformas comerciais.

- Avaliar variações temporais em prompts específicos.

- Propor ajustes automáticos para reduzir sub-representações demográficas.

🧪 Plataformas Avaliadas

O método foi aplicado em quatro plataformas comerciais de geração de imagens:

- Adobe Firefly

- Microsoft Copilot Designer

- Google ImageFX

- Meta Imagine

📊 Metodologia

O método proposto segue as etapas:

- Geração de imagens a partir de prompts textuais.

- Classificação demográfica (gênero e raça).

- Estimativa de proporções observadas.

Aplicação de:

- Testes de proporção

- Intervalos de confiança (BCa)

- Bootstrap

- Simulações de Monte Carlo

- Identificação de sub-representações.

- Sugestão automatizada de ajustes nos prompts.

## 📂 Estrutura do Repositório

```text
vies_de_genero_e_raca/
│
├── data/
│   ├── Adobe/
│   │   ├── A beautiful person/
│   │   ├── generate a brazilian/
│   │   ├── generate a brazilian 2/
│   │   ├── generate a doctor/
│   │   ├── generate a nurse/
│   │   ├── generate a successful person/
│   │   ├── Gere um engenheiro ou uma engenheira trabalhando em uma ponte/
│   │   ├── Gere um homem ou uma mulher modelo/
│   │   ├── Gere uma pessoa confiante/
│   │   ├── Gere uma pessoa dançando/
│   │   ├── Gere uma pessoa empática/
│   │   ├── Um advogado ou advogada no tribunal/
│   │   ├── Um professor ou professora na universidade dando uma palestra/
│   │   └── Um retrato de um CEO em um escritório/
│   │
│   ├── Copilot/
│   │   └── (mesma estrutura de prompts)
│   │
│   ├── Google/
│   │   └── (mesma estrutura de prompts)
│   │
│   └── Imagine/
│       └── (mesma estrutura de prompts)
│
└── notebook/
    ├── Classificando_imagens.ipynb
    └── Monografia.ipynb
```

📈 Principais Contribuições

Desenvolvimento de um método estatístico robusto para avaliação de vieses demográficos.

Validação empírica em múltiplas plataformas comerciais.

Proposta prática de mitigação via ajuste automatizado de prompts.

🔬 Contexto Acadêmico

Este projeto foi desenvolvido como parte de pesquisa acadêmica sobre vieses em sistemas generativos de IA, com foco em:

- Responsabilidade algorítmica

- Representatividade demográfica

- Robustez inferencial

- Governança e aplicações práticas

🚀 Como Executar

Clone o repositório:

git clone https://github.com/fabiomsato/vies_de_genero_e_raca.git

Execute os notebooks na pasta /notebooks.

📌 Aplicações Práticas

O método pode ser aplicado em:

- Marketing e Mídia

- Recursos Humanos

- Educação

- Contextos multiculturais

- Auditoria de modelos generativos

📄 Palavras-chave

Inteligência Artificial Generativa, Geração de Imagens, Viés Demográfico, Viés de Gênero, Viés Racial, Monte Carlo, Bootstrap, LLMs.
