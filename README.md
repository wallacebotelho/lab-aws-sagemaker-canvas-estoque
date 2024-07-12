# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

### 1. Dataset selecionado

- canvas-sample-diabetic-readmission.csv
  ![image](https://github.com/user-attachments/assets/c0f28830-b101-42ab-a9f6-70482e73441a)

### 2. Construir/Treinar

- Importado um tabela sobre diabetes em um hospital, selecionei a coluna de time_in_hospital para a previsão do tempo comparando diversas colunas.

### 3. Analise

- Verificado que a coluna com maior impacto é a coluna de num_medications em 33.763%, Impacto dos medicamentos numéricos na previsão do tempo de internação.
  ![image](https://github.com/user-attachments/assets/940ff89e-665f-4145-9f0d-fda49b5cf309)
- A metrica Accurary, uma análise usando essa metrica, estima que será capaz de prever corretamente o tempo na coluna time_in_hospital 26,214%.

### 4. Previsão

- O número de medicamentos por padrão está (11) 16,781% de chance de o tempo de internação ser de 1 . As alterações no valor da coluna tornaram esta classe 1,587% mais provável do que a última previsão.
- Caso o número de medicamentos for (22) 6,034% de chance de o tempo de internação ser de 1 . As alterações no valor da coluna tornaram esta classe 10,747% menos provável do que a última previsão.
  ![image](https://github.com/user-attachments/assets/8129c701-bd4b-4dd9-a840-62e042b3c380)

