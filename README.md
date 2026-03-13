
## Bootcamp Heineken — Inteligência Artificial Aplicada a Dados com Copilot · DIO

![Screenshot_20250614-182332](https://github.com/user-attachments/assets/62d1fc18-9185-4875-a839-fa42809e7139)

---

# 🎮 Dashboard de Vendas Xbox — Análise de Assinaturas em Excel

## 1. Problema de Negócio

Uma empresa distribuidora de planos Xbox precisa entender como sua receita está distribuída entre os diferentes tipos de assinatura e avaliar o impacto da **auto renovação** no faturamento.

Sem uma visão consolidada dos dados, a gestão comercial toma decisões com base em percepção — e não em evidências. O desafio central é: **quais planos geram mais receita? E quanto da receita anual está garantida por contratos com renovação automática?**

---

## 2. Contexto

A base de dados contém **295 assinantes ativos**, distribuídos em três tipos de plano (Monthly, Quarterly e Annual) e três categorias de produto (Core, Standard e Ultimate). Cada assinatura possui variáveis como preço base, cupom de desconto, Season Passes adicionais (EA Play e Minecraft) e status de auto renovação.

Os dados estavam disponíveis em formato bruto no arquivo `base1.xlsx`, sem nenhuma análise ou visualização aplicada. A empresa não utilizava essas informações de forma estruturada para apoiar decisões comerciais.

---

## 3. Premissas da Análise

- O campo **Total Value** representa o valor efetivo pago pelo assinante, já considerando descontos de cupom e adicionais de Season Pass.
- O campo **Auto Renewal** (Yes/No) é a fonte oficial para identificar contratos com renovação garantida.
- A análise foca nos planos **anuais** como principal KPI de receita recorrente.
- Os dados representam um recorte válido da operação, adequado para análise descritiva e tomada de decisão.

---

## 4. Estratégia da Solução

A construção do dashboard seguiu uma abordagem estruturada em quatro etapas:

**Etapa 1 — Entendimento dos dados:** mapeamento das 13 colunas da base, identificação dos campos de negócio relevantes (tipo de plano, auto renovação, valor total) e verificação de consistência.

**Etapa 2 — Definição das perguntas de negócio:** com base nos dados disponíveis, foram priorizadas duas questões críticas: o faturamento total dos planos anuais e sua decomposição por status de auto renovação.

**Etapa 3 — Estruturação das métricas (aba Cálculos):** criação de fórmulas e segmentações com SOMASE para isolar planos anuais e cruzar com o status de renovação.

**Etapa 4 — Visualização (aba Dashboard):** construção de cards de KPI, gráfico de colunas comparativas e gráfico de rosca, usando a paleta de cores Xbox extraída da aba Assets.

---

## 5. Insights da Análise

Os dados revelaram padrões relevantes para a operação comercial:

- O faturamento total dos planos anuais é de **R$ 1.754**, representando a principal fatia de receita recorrente do portfólio.
- Dos planos anuais, **R$ 1.537 (87,6%) vêm de contratos com auto renovação ativa** — o que indica alta previsibilidade de receita para esse segmento.
- Apenas **R$ 217 (12,4%)** dos planos anuais não possuem auto renovação, sinalizando risco de churn para este grupo.
- O tipo de assinatura **Monthly** é o mais frequente (139 assinantes), mas fragmenta a receita em tickets menores — o que reforça o valor estratégico dos planos anuais.
- A distribuição entre os planos Core (101), Ultimate (98) e Standard (96) é praticamente uniforme, sem dominância clara de nenhum produto.

---

## 6. Resultados

O dashboard entrega uma visão executiva e acionável para a equipe comercial:

- **Faturamento anual total:** R$ 1.754
- **Faturamento anual com auto renovação:** R$ 1.537
- **Faturamento anual sem auto renovação:** R$ 217
- **Recomendação:** priorizar ações de conversão dos 147 assinantes sem auto renovação para contratos renováveis — especialmente nos planos anuais, onde o impacto na receita garantida é mais alto.

O projeto demonstra como uma análise descritiva simples, aplicada com rigor, gera informações suficientes para orientar decisões de retenção e precificação.

---

## 7. Próximos Passos

- Conectar a base ao **Power BI** para atualização dinâmica e distribuição do dashboard para stakeholders.
- Criar análise de **churn por cohort**: identificar quando os assinantes sem auto renovação tendem a cancelar.
- Incluir análise de **LTV (Lifetime Value)** por tipo de plano para comparar rentabilidade real ao longo do tempo.
- Expandir o dashboard com segmentação por **Season Pass** (EA Play e Minecraft) para avaliar o impacto dos adicionais na receita total.

---

## 🧩 Estrutura do Arquivo Excel

| Aba | Descrição |
|-----|-----------|
| **Assets** | Paleta de cores, ícones e elementos visuais (Verde Xbox `#9BC848`, Verde-menta `#5BF6A8`) |
| **Bases** | 295 registros de assinantes com 13 variáveis comerciais |
| **Cálculos** | Métricas segmentadas por tipo de plano e auto renovação |
| **Dashboard** | Visualização final com cards de KPI, gráficos e filtros interativos |

---

## 📁 Arquivos no Repositório

| Arquivo | Descrição |
|---------|-----------|
| `base1.xlsx` | Base de dados original com abas para edição |
| `ok11_dashboard_xbox_finalizado.xlsx` | Dashboard completo e finalizado |
| `README.md` | Documentação do projeto |

---

## 🖼️ Painel de Vendas — Xbox

![copilot_image_1750055936160](https://github.com/user-attachments/assets/1b6c8478-dadc-4edf-b8f8-9e55b76c67a7)

---

**Contato:**

[![Portfólio Sérgio Santos](https://img.shields.io/badge/Portfólio-Sérgio_Santos-111827?style=for-the-badge&logo=githubpages&logoColor=00eaff)](https://portfoliosantossergio.vercel.app)

[![LinkedIn Sérgio Santos](https://img.shields.io/badge/LinkedIn-Sérgio_Santos-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/santossergioluiz)
