# 🎥 ScreenMatch - Frases Clássicas de Filmes e Séries 🎬

## ✨ Descrição
Bem-vindo(a) ao **ScreenMatch - Frases Clássicas**! Neste projeto, você encontrará frases icônicas de filmes e séries, integrando um backend e um frontend para gerar uma experiência imersiva e divertida. 🌟

Esta aplicação foi criada como um desafio para consolidar os conhecimentos em desenvolvimento de software, incluindo conceitos aprendidos em backend e frontend. 🧑‍💻

---

## 🚀 Funcionalidades
- 🎲 Gerar frases aleatórias de filmes e séries famosas.
- 🖼️ Exibir o pôster e informações sobre o filme ou série da frase.
- 🛠️ Integração completa entre backend e frontend.

---

## 🛑 Pré-requisitos
Antes de começar, você precisará das seguintes ferramentas:
- 🐍 **Java** (versão 17 ou superior).
- 📦 **Maven** ou **Gradle** para gerenciar dependências.
- 🛢️ Banco de dados **MySQL** (ou qualquer outro configurado no `application.properties`).
- 🌐 Navegador para visualizar o frontend.

---

## ⚙️ Configuração do Projeto

### 1️⃣ Clonar o repositório
```bash
git clone https://github.com/seu-usuario/screenmatch-frases.git
```

2️⃣ Configurar o backend
1. Abra o arquivo application.properties em src/main/resources.
2. Configure as informações do banco de dados:
```spring.datasource.url=jdbc:mysql://localhost:3306/nome_do_banco
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha
spring.jpa.hibernate.ddl-auto=update
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQLDialect
```

3. Execute o comando para rodar o backend:

```
./mvnw spring-boot:run
```
3️⃣ Configurar o frontend
1. Navegue até a pasta do frontend:
```
cd frontend
```
2. Abra o arquivo index.html no navegador ou use um servidor local.

📦 Estrutura do Projeto

• backend/ - Código-fonte do backend em Spring Boot.
• frontend/ - Arquivos do frontend em HTML, CSS e JavaScript

💡 Tecnologias Utilizadas
• Backend:

- ☕ Java com Spring Boot.
- 🛢️ Hibernate para ORM.
- 🗄️ MySQL para banco de dados.

• Frontend:
- 🌐 HTML5, CSS3 e JavaScript.

🤝 Contribuições
Contribuições são bem-vindas! 💻✨ Sinta-se à vontade para abrir uma issue ou enviar um pull request.


## 📧 Contato

📌 Desenvolvido por Jeisa Boaventura.  
📩 Email: caaarolboa@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/-caroline-boaventura/)




