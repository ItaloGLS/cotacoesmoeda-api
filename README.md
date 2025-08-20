# 📱 Projeto: Consulta de Cotação de Moedas

## 📌 Resumo Geral
Este aplicativo Android permite ao usuário **digitar a sigla de uma moeda** (ex: `USD`, `EUR`, `BTC`) e consultar uma **API** que retorna a cotação em relação ao **Real brasileiro (BRL)**.  
O app exibe os seguintes dados:

- 💲 Valor **máximo**  
- 💲 Valor **mínimo**  
- 💲 Valor **atual**  
- 📅 **Data da última atualização**

---

## 📂 Estrutura do Projeto

### 1. `MainActivity.kt`
- Gerencia a tela principal do aplicativo.  
- Captura a sigla digitada pelo usuário.  
- Faz a consulta à API.  
- Exibe os resultados na tela.  

### 2. `MoedaApi.kt`
- Define como o aplicativo consulta a API.  
- Implementa o uso do **Retrofit** para chamadas HTTP.  

### 3. `MoedaResponse.kt`
- Define o **formato dos dados** retornados pela API.  
- Estrutura o mapeamento do JSON para objetos Kotlin.  

### 4. `activity_main.xml`
- Define a **interface visual do app**.  
- Campos para digitar a sigla da moeda.  
- Botão de busca.  
- Área para exibir os resultados da cotação.  

---

## 🚀 Tecnologias Utilizadas
- **Kotlin**  
- **Android Studio**  
- **Retrofit**  
- **API de Cotação (economia.awesomeapi.com.br)**  

---

## 📸 Exemplo de Uso
1. O usuário digita: `USD`  
2. O app consulta a API.  
3. O app retorna:  
   - Máximo: `5.20`  
   - Mínimo: `5.05`  
   - Atual: `5.10`  
   - Última atualização: `20/08/2025 11:30`  

---
