# 💰 Calculadora de Investimentos Inteligente (FIIs)
Ferramenta em Excel desenvolvida para simulação de aportes mensais, projeção de patrimônio a longo prazo com juros compostos e alocação automatizada de ativos com base no perfil do investidor (Foco em Fundos Imobiliários - FIIs).
---
## 🚀 Sobre o Projeto
Este projeto tem como objetivo auxiliar no planejamento financeiro pessoal, permitindo que o usuário visualize o impacto de seus aportes mensais ao longo dos anos, estime os rendimentos passivos gerados (dividendos) e descubra como distribuir seus investimentos entre diferentes tipologias de FIIs de acordo com seu apetite ao risco.
---
## ⚙️ Funcionalidades Principais
1. **Configuração de Renda e Aportes:** 
   * Cálculo automático de sugestão de investimento baseado em uma porcentagem do salário (ex: 20%).
   * Definição manual do valor investido mensalmente, prazo em anos e taxa de rendimento esperada.
2. **Projeção de Cenários Temporais:** 
   * Tabelas automáticas que projetam o patrimônio acumulado e o retorno em dividendos para horizontes de 2, 5, 10, 20 e 30 anos.
3. **Alocação Dinâmica por Perfil (De-Para):** 
   * Distribuição percentual automatizada dos aportes entre categorias de FIIs com base no perfil escolhido (**Conservador**, **Moderado** ou **Agressivo**).
---
## 📂 Estrutura da Planilha
A planilha está dividida em duas abas principais:
### 1. `Calculadora`
Responsável pela interface de simulação e lógica financeira. Contém:
* **Parâmetros Iniciais:** Salário base, taxa de rendimento mensal (ex: 0,9% ao m.) e valor do aporte.
* **Simulador de Crescimento Patrimonial:** Aplicação da fórmula de juros compostos com aportes regulares.
* **Matriz de Alocação de Ativos:** Puxa os percentuais correspondentes ao perfil selecionado e calcula o valor exato (em moeda) a ser investido em cada classe de FII.
### 2. `DExPARA`
Tabela de referência que alimenta as regras de negócio da calculadora, mapeando os perfis de risco às respectivas fatias de alocação em:
* **Papel (CRIs)**
* **Tijolo (Lojas, Galpões, Lajes)**
* **Híbridos**
* **FOFs (Fundos de Fundos)**
* **Desenvolvimento**
* **Hotelarias**
---
## 📊 Regras de Alocação (Resumo)

| Perfil | Papel | Tijolo | Híbridos | FOFs | Desenvolvimento | Hotelarias |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Conservador** | 30% | 50% | 10% | 10% | 0% | 0% |
| **Moderado** | 32% | 35% | 8% | 5% | 10% | 10% |
| **Agressivo** | 50% | 10% | 5% | 5% | 20% | 10% |

---
## 🛠️ Tecnologias e Ferramentas Utilizadas
* **Microsoft Excel / Planilhas Google:** Criação de fórmulas financeiras, validação de dados e estruturação de tabelas dinâmicas.
* **Funções de Procura e Referência (Ex: PROCV / FILTRO):** Utilizadas na aba `DExPARA` para cruzar dados do perfil escolhido.
---
## 📥 Como Utilizar
1. Faça o download do arquivo `Calculadora de Investimento.xlsx` disponível neste repositório.
2. Abra a aba **Calculadora**.
3. Insira o seu **Salário** e ajuste o **Valor a ser investido por mês**, os **Anos** de projeção e o **Perfil de Investidor** desejado.
4. Acompanhe o crescimento do seu patrimônio projetado e os valores sugeridos para alocação em cada tipo de FII!
---
## 📌 Licença
Este projeto é de uso livre para estudos e planejamento financeiro pessoal. Sinta-se à vontade para clonar, sugerir melhorias ou adaptar para as suas necessidades!
