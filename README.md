# UNO Strategy Simulator 🎮

Este repositório contém um simulador computacional do jogo UNO, desenvolvido com o objetivo de avaliar o desempenho de diferentes estratégias através de simulações em larga escala (Monte Carlo). Inclui o código-fonte, resultados das simulações e documentação analítica.

---

## 📁 Estrutura do Projeto

| Tipo             | Arquivo                                | Descrição                                       |
|------------------|----------------------------------------|-------------------------------------------------|
| 💻 Código        | `UNO_Simulator.ipynb`                   | Notebook Jupyter contendo o simulador UNO, as estratégias e a análise inicial dos resultados. |
| 📊 Resultados    | `csv/resultados_simulacaoUNO_10000x9.csv`   | Resultados de 10.000 partidas simuladas com 9 bots. |
|                  | `csv/resultados_simulacaoUNO_10000x6.csv`   | Resultados de 10.000 partidas simuladas com 6 bots. |
|                  | `csv/resultados_simulacaoUNO_10000x3.csv`   | Resultados de 10.000 partidas simuladas com 3 bots. |
| 📄 Documentos    | `Relatório Estatístico do UNO`          | Análise estatística das simulações e discussão dos resultados. |
|                  | `Estratégias no Jogo UNO`               | Descrição detalhada das estratégias implementadas e suas lógicas. |

---

## 🔍 Descrição dos Arquivos

### `UNO_Simulator.ipynb`
- Implementação da mecânica básica do UNO.
- Definição de múltiplas estratégias.
- Simulação de milhares de partidas.
- Exportação automática de resultados.
- Análises estatísticas e geração de gráficos.

---

### Arquivos CSV de Resultados
- Contêm dados detalhados das partidas simuladas:
  - Estratégia vencedora.
  - Quantidade de turnos por partida.
  - Número de cartas puxadas.
  - Estado final das mãos.
- Podem ser utilizados para análises externas (Python, R, Excel).

---

### Documentos PDF / Google Docs
- **Relatório Estatístico do UNO**: apresenta os resultados quantitativos das simulações.
- **Estratégias no Jogo UNO**: explica as estratégias usadas no projeto, incluindo lógica, vantagens e limitações.

---

