# 📊 Análise de Evasão de Clientes - TelecomX

Este projeto faz parte do **último Challenge do programa Oracle Next Education (ONE)**, desenvolvido em parceria com a **Alura**.  
O objetivo é analisar a evasão (churn) de clientes da **TelecomX** e identificar os principais fatores que influenciam na decisão de cancelamento. 

## 🛠️ Etapas do Projeto

1. **Preparação dos dados**  
   - Importação do dataset tratado  
   - Remoção de colunas irrelevantes  
   - Aplicação de encoding nas variáveis categóricas  
   - Verificação da proporção de evasão  

2. **Balanceamento dos dados**  
   - Utilização da técnica **over_sampling** para corrigir o desbalanceamento da variável alvo

3. **Treinamento do Modelo**  
   - Algoritmo escolhido: **RandomForestClassifier**  
   - Métrica principal: **Recall** (média ≈ 0,70)  

4. **Análise de Importância das Variáveis**  
   - Identificação dos fatores mais influentes na evasão:
     - **Tipo de contrato** (mês a mês ou longo prazo)  
     - **Forma de pagamento** escolhida pelo cliente  
     - **Assinatura do suporte técnico mais rápido**  
   - Outras variáveis apresentaram impacto menor, conforme a matriz e gráfico de importância.

## 💾 Modelos Salvos

- **Modelo de One-Hot Encoding** (`one_hot.pkl`)  
- **Modelo Treinado Final** (`modelo_definitivo.pkl`)  

Estes arquivos permitem reutilizar o pré-processamento e o modelo final em novas previsões, mantendo a consistência do pipeline.

## 📈 Conclusão

O estudo demonstrou que aspectos contratuais, forma de pagamento e suporte técnico são fatores decisivos para a permanência ou cancelamento do serviço. 
A abordagem utilizada garante boa capacidade de identificação de clientes em risco, permitindo ações preventivas pela empresa.

---
Desenvolvido por **Vitor Tavares**
