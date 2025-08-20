## 📊 Análise de Vendas

## 🔍 Objetivo
Este projeto faz uma análise descritiva de um dataset fictício de vendas, contemplando:
- Ranking de produtos mais vendidos  
- Faturamento mensal  
- Ticket médio por cliente  

## ▶️ Como executar
1. Clone este repositório ou baixe os arquivos.  
2. Instale as dependências:  

```bash
pip install pandas
pip install matplotlib
```

## 📚 Bibliotecas utilizadas

Pandas,

Matplotlib (opcional para gráficos)

### 🧠 Decisões de implementação

- Foi utilizada a biblioteca pandas para manipulação e agregações.
- Para o cálculo do ticket médio, dividiu-se a soma da receita total pelo número de transações totais distintas.
- O gráfico de faturamento mensal foi gerado com matplotlib para melhor visualização temporal.
- Utilizou-se um gráfico de barra horizontal para facilitar a leitura do top 10 produtos.
- Uma barra única empilhada foi usada para mostrar a proporção de clientes acima e abaixo da média.


## 📊 Resultados

### Top 10 Produtos com Maior Faturamento
<img width="1393" height="755" alt="image" src="https://github.com/user-attachments/assets/1ff1aa91-dde5-4767-97ab-994aa15dd2a7" />

### Top 10 Produtos Mais Vendidos (por Volume)
<img width="1414" height="774" alt="image" src="https://github.com/user-attachments/assets/2ad750cb-6be5-4fab-9c98-e474f9c5bb80" />

### Proporção Itens Vendidos
<img width="776" height="277" alt="image" src="https://github.com/user-attachments/assets/827c65ca-0cb7-44b0-a733-407d2cb4d65b" />

### Gastos por cliente X TM Geral 
<img width="876" height="251" alt="image" src="https://github.com/user-attachments/assets/9b1b49f2-d624-4f84-9daf-683781dc9ffb" />

## 📈 Conclusões

- O produto `4509.202` lidera tanto em faturamento quanto em volume, mostrando grande relevância no portfólio.  
- O código `KP.211.17` aparece no ranking de faturamento, mas não no de volume — indicando alto valor unitário.  
- A receita está concentrada em poucos produtos, o que sugere dependência de um portfólio limitado.  
- Há oportunidade de explorar melhor produtos de médio volume para diversificação. 

## 📦 Dados do Case
Os dados utilizados neste projeto estão disponíveis no link abaixo:
https://drive.google.com/file/d/1LoXUj9gMZcJ9tBWplp1_ovV2vUKrjX-0/view?usp=sharing
