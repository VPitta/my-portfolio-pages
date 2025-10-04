# 🌐 Portfólio Pessoal

Este é o meu **Portfólio Pessoal**, criado do zero utilizando **HTML, CSS e JavaScript** como parte do desafio da **DIO**.  
O diferencial deste projeto é que os dados do portfólio são consumidos dinamicamente via **API do GitHub**, permitindo que o conteúdo seja facilmente atualizado.

---

## 🔹 Tecnologias Utilizadas
- **HTML5** – Estrutura do site
- **CSS3** – Estilização responsiva e moderna
- **JavaScript** – Consumo de API e manipulação de dados
- **GitHub Pages** – Hospedagem gratuita do portfólio
- **GitHub API** – Puxando dados do próprio repositório JSON

---

## 🔹 Funcionalidades
- Exibição dinâmica de informações do portfólio a partir de um **arquivo JSON hospedado no GitHub**.  
- Layout moderno e responsivo, adequado para diferentes dispositivos.  
- Estrutura limpa, permitindo fácil manutenção e atualização.  

---

## 🔹 Como Funciona
1. O portfólio contém um arquivo JSON com os dados pessoais e profissionais (`profile.json`).  
2. O **JavaScript** faz um `fetch()` deste arquivo no **GitHub Raw URL**, transformando o JSON em conteúdo dinâmico na página.  
3. Toda vez que você atualizar o JSON no GitHub, as alterações são refletidas automaticamente no portfólio.

```javascript
fetch("https://raw.githubusercontent.com/SEU-USUARIO/NOME-REPOSITORIO/main/src/data/meu-dados.json")
  .then(response => response.json())
  .then(data => {
    // código para renderizar os dados no HTML
  })

```
🔹 Como Usar
Clone este repositório:

```bash
Copiar código
git clone https://github.com/SEU-USUARIO/NOME-REPOSITORIO.git
Abra o arquivo index.html no navegador ou suba para o GitHub Pages.

Atualize o JSON hospedado no GitHub para modificar os dados exibidos no portfólio.
```

🔹 Demo Online
O portfólio está disponível via GitHub Pages:
https://SEU-USUARIO.github.io/NOME-REPOSITORIO

