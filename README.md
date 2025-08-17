# 📊 Análise de Evasão de Clientes – TelecomX

## 📄 Descrição
Este projeto analisa o churn de clientes da TelecomX, investigando padrões de cancelamento de planos e comportamento de gastos. O objetivo é identificar perfis de clientes com maior risco de desistência e propor estratégias de retenção.

## 📊 Dados
O dataset contém **7267 registros** com informações sobre:

- Identificação do cliente  
- Status do plano (ativo ou cancelado)  
- Tipo de contrato (Mensal, Anual, Bienal)  
- Método de pagamento  
- Pagamento em papel ou digital  
- Gasto mensal e total do cliente  
- Tempo de contrato (em meses)  
- Status de cliente sênior  

Foram selecionadas apenas as colunas relevantes para análise de churn.

## 🔍 Análise Exploratória

### Churn Geral
- **Cancelamentos:** 25,7% dos clientes  
- **Assinantes ativos:** 74,3%  

### Padrões observados
- **Método de pagamento:** maior churn entre clientes que utilizam **cheque eletrônico**  
- **Tipo de contrato:** cancelamentos mais frequentes em **planos mensais**  
- **Pagamento em papel:** alto churn entre clientes que utilizam boleto em papel  

### Gastos e Tempo de Contrato
- **Média de gastos mensais:** 64,72  
- **Mediana:** 70,30  
- **Moda:** 20,05  
- **Desvio padrão:** 30,12  

**Insights:**  
- Mediana maior que a média → muitos clientes gastam pouco, puxando a média para baixo  
- A maioria dos cancelamentos ocorre em contratos curtos, principalmente abaixo de 30 meses

## 🛠 Tecnologias
- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

## ⚙️ Instalação
1. Clone o repositório:
   git clone <link-do-repo>
2. Entre na pasta do projeto:
   cd nome-do-repo
3. Instale as dependências:
   pip install -r requirements.txt

## 📝 Dependências
- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook ou Google Colab

## ▶️ Como executar
1. Abra o projeto no Jupyter Notebook ou Google Colab.
2. Execute as células na ordem apresentada.
3. Analise os gráficos e resultados da exploração de dados.

## 💡 Conclusões e Recomendações
- Clientes com **planos mensais**, **baixo gasto** e pagamento em **cheque ou boleto em papel** são mais propensos a cancelar  
- Estratégias sugeridas:  
  - Incentivar pagamentos automáticos com descontos ou benefícios  
  - Criar programas de fidelidade para os primeiros meses  
  - Oferecer promoções progressivas nos primeiros meses para facilitar adaptação ao serviço  

**Objetivo:** tornar o serviço mais acessível e valioso, evitando cancelamentos nos primeiros meses
