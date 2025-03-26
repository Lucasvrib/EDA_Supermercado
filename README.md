# 📌 Análise Exploratória de Dados (EDA) - Supermercado 🛒📊  

Este repositório contém uma análise exploratória detalhada dos dados de estoque e vendas de um supermercado, explorando padrões de vendas, giro de estoque, fornecedores e problemas de gestão de estoque.  

---

## 📊 Objetivo do Projeto  
O objetivo desta análise é entender melhor os padrões de estoque e vendas do supermercado, respondendo a perguntas como:  

✔ Existe alguma sazonalidade nas vendas?  
✔ Quais são os produtos e categorias mais vendidos?  
✔ Produtos mais caros vendem menos?  
✔ Quais produtos possuem maior taxa de giro?  
✔ Há problemas de excesso ou ruptura de estoque?  
✔ Os fornecedores entregam no prazo adequado?  

---

## 📂 Conjunto de Dados  
O conjunto de dados contém informações detalhadas sobre **990 produtos**, incluindo:  

- 📌 **Produto** → Nome, categoria e preço unitário  
- 📌 **Estoque** → Quantidade disponível, nível de reposição  
- 📌 **Vendas** → Volume de vendas e taxa de giro  
- 📌 **Fornecedores** → Nome, frequência de entrega  
- 📌 **Datas** → Último pedido, data de recebimento  

---

## 📌 Principais Descobertas  

### **1️⃣ Sazonalidade nas Vendas**  
📊 **As vendas são mais altas nos meses de fevereiro, junho e outubro**, indicando picos sazonais trimestrais, onde há aumento na demanda aproximadamente a cada quatro meses.

🔹 **Ações recomendadas:**  
✅ Aumentar pedidos antes dos meses de alta demanda.  
✅ Criar promoções nos meses de menor venda.  

---

### **2️⃣ Produtos e Categorias Mais Vendidos**  
📊 O **produto mais vendido** foi **"Bread Flour"**, seguido por **"Pomegranate"** e **"Cauliflower"**.  

📊 **As categorias que mais vendem são:**  
1️⃣ **Fruits & Vegetables**  
2️⃣ **Dairy**  
3️⃣ **Grains & Pulses**  

🔹 **Ações recomendadas:**  
✅ Reabastecer com prioridade esses produtos populares.  
✅ Ajustar o volume de compras de acordo com a demanda.  

---

### **3️⃣ Relação entre Preço e Volume de Vendas**  
📊 **Não há uma relação forte entre preço e vendas.**  
- Produtos **até $10** apresentam alta variação nas vendas.  
- Produtos **acima de $50** vendem menos.  

🔹 **Ações recomendadas:**  
✅ Testar promoções para produtos acima de $50.  
✅ Ajustar estoques para evitar excesso em produtos mais caros.  

---

### **4️⃣ Produtos com Maior e Menor Taxa de Giro**  
📊 **Top 5 produtos com maior taxa de giro (vendem rapidamente):**  
1️⃣ **Tilapia**  
2️⃣ **Black Tea**  
3️⃣ **Wild Rice**  
4️⃣ **Butter Biscuit**  
5️⃣ **Egg (Turkey)**  

📊 **Produtos com menor giro de estoque (vendem devagar):**  
❌ **Mushrooms**  
❌ **Lemon**  

🔹 **Ações recomendadas:**  
✅ Aumentar estoque dos produtos de alto giro para evitar rupturas.  
✅ Criar promoções para reduzir estoques de produtos de baixo giro.  

---

### **5️⃣ Confiabilidade dos Fornecedores**  
📊 **Os fornecedores mais rápidos:**  
✔ **Kwinu** → Entrega em **2 dias**  
✔ **Skippad** → Entrega em **3 dias**  

📊 **Os fornecedores mais lentos:**  
❌ **Divape** → Entrega em **14 dias**  
❌ **Skiptube** → Entrega em **15 dias**  

🔹 **Ações recomendadas:**  
✅ Negociar prazos menores com fornecedores lentos.  
✅ Manter estoque de segurança para produtos de fornecedores com prazo longo.  

---

### **6️⃣ Problemas de Estoque (Excesso e Ruptura)**  
📊 **Produtos com excesso de estoque (acima do dobro do nível de reposição):**  
❗ **Chocolate Biscuit** → 100 unidades (nível de reposição: 1)  
❗ **Onion** → 98 unidades (nível de reposição: 40)  

📊 **Produtos com ruptura de estoque:**  
❌ **Basmati Rice** → Estoque abaixo do nível mínimo.  

🔹 **Ações recomendadas:**  
✅ Criar promoções para vender produtos em excesso.  
✅ Melhorar previsões de compra para evitar ruptura.  

---

## 📷 Exemplos de Gráficos  

Os gráficos gerados nesta análise incluem:  

📊 **Vendas por Mês**  
![Vendas por Mês](EDA_Supermercado/imagens/Vendas%20por%20Mês.png)  

📊 **Volume de Vendas por Produto**  
![Volume de Vendas por Produto](EDA_Supermercado/imagens/Volume%20de%20Vendas%20por%20Produto.png)  

📊 **Volume de Vendas por Categoria**  
![Volume de Vendas por Categoria](EDA_Supermercado/imagens/Volume%20de%20Vendas%20por%20Categoria.png)  

📊 **Distribuição do Volume de Vendas por Categoria**  
![Distribuição do Volume de Vendas por Categoria](EDA_Supermercado/imagens/Distribuição%20do%20Volume%20de%20Vendas%20por%20Categoria.png)  

📊 **Preço vs Volume de Vendas**  
![Preço vs Volume de Vendas](EDA_Supermercado/imagens/Preço%20vs%20Volume%20de%20Vendas.png)  

📊 **Produtos Ativos com Maior Taxa de Giro**  
![Produtos Ativos com Maior Taxa de Giro](EDA_Supermercado/imagens/Produtos%20Ativos%20com%20Maior%20Taxa%20de%20Giro.png)  

📊 **Produtos Ativos com Menor Taxa de Giro**  
![Produtos Ativos com Menor Taxa de Giro](EDA_Supermercado/imagens/Produtos%20Ativos%20com%20Menor%20Taxa%20de%20Giro.png)  

📊 **Produtos Descontinuados - Preço vs. Taxa de Giro**  
![Produtos Descontinuados](EDA_Supermercado/imagens/Produtos%20Descontinuados%20-%20Preço%20vs.%20Taxa%20de%20Giro.png)  

📊 **Fornecedores que Entregam com Mais Frequência**  
![Fornecedores Frequentes](EDA_Supermercado/imagens/Fornecedores%20que%20Entregam%20com%20Mais%20Frequência.png)  

📊 **Problemas de Estoque - Excesso vs Ruptura**  
![Problemas de Estoque](EDA_Supermercado/imagens/Problemas%20de%20Estoque%20-%20Excesso%20vs%20Ruptura.png)  

---

## 🚀 Tecnologias Utilizadas  

✅ **Python** → Linguagem principal da análise  
✅ **Pandas** → Manipulação e análise de dados  
✅ **Seaborn & Matplotlib** → Criação de gráficos  
✅ **Jupyter Notebook** → Execução do código e visualização  

---

## 📧 Contato  
📌 Criado por **Lucas Viana Ribeiro**  
💼 Conecte-se no **[LinkedIn](https://www.linkedin.com/in/lucasvrib/)**  

---

🌟 **Se gostou do projeto, deixe uma estrela no repositório!** ⭐  
