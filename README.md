# 📊 Manipulação de Dados em Julia — Checklist

## 📁 Estrutura do Conteúdo

### **1. Contextualização**
- [ ] O que é manipulação de dados  
- [ ] Por que utilizar Julia para análise  
- [ ] Principais pacotes utilizados

---

### **2. Inspeção Inicial**
- [ ] Carregamento de dados com `CSV.jl`  
- [ ] Visualização inicial (`first`, `describe`, `names`)  
- [ ] Checagem de tipos (`schema`, `eltype`)

---

### **3. Estrutura do Dataset**
- [ ] Dimensões (`size`, `nrow`, `ncol`)  
- [ ] Tipos de variáveis  
- [ ] Verificação de valores faltantes (`ismissing`)

---

### **4. Manipulação Básica com DataFrames**

#### **4.1 Criação de DataFrames**
- [ ] Criação manual  
- [ ] Criação a partir de CSV

#### **4.2 Seleção e Ordenação**
- [ ] Selecionar colunas (`select`)  
- [ ] Selecionar linhas (`subset`)  
- [ ] Ordenar (`sort`)

#### **4.3 Renomear e Transformar**
- [ ] Renomear colunas (`rename`)  
- [ ] Criar novas colunas (`transform`)  
- [ ] Modificar colunas existentes (`@transform!`)

---

### **5. Filtragem e Limpeza**

#### **5.1 Filtragem Condicional**
- [ ] Uso de `filter`  
- [ ] Filtragem com múltiplas condições

#### **5.2 Tratamento de Valores Faltantes**
- [ ] Remover faltantes (`dropmissing`)  
- [ ] Substituir (`coalesce`, `passmissing`)

#### **5.3 Outliers**
- [ ] Detectar outliers (Z-score / IQR)  
- [ ] Remover outliers (`subset`)

---

### **6. Conclusão**
- [ ] Resumo das transformações  
- [ ] Vantagens de Julia  
- [ ] Possíveis extensões

---

