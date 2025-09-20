# Demo DAO JDBC

**Demo DAO JDBC** é um projeto de exemplo que demonstra o uso de DAO (Data Access Object) com JDBC puro em Java, para realizar operações de persistência em banco de dados relacionais.  

---

## 🧰 Tecnologias utilizadas

- Java  
- JDBC (Java Database Connectivity)  
- Conexão com banco via arquivo de propriedades (`db.properties`)  
- Estrutura DAO para abstração do acesso a dados  

---

## 📂 Estrutura do projeto

```
demo-dao-jdbc/
├── src/
│   ├── main/
│   │   └── java/
│   │       └── (pacotes de entidades, DAOs, serviços, etc.)
│   └── resources/
│       └── db.properties      # configurações do banco (URL, usuário, senha)
├── .gitignore
└── README.md
```

---

## 🚀 Funcionalidades

- Inserção de dados no banco  
- Consulta de registros  
- Atualização de dados  
- Remoção de registros  
- Abstração do SQL através da camada DAO  

---

## ⚙️ Requisitos

- Java (versão compatível com o projeto)  
- Banco de dados relacional (ex: MySQL, PostgreSQL ou outro que suporte JDBC)  
- Driver JDBC correspondente ao banco escolhido  
- Configuração correta do arquivo `db.properties`, contendo URL, usuário e senha do banco  

---

## 🛠️ Como usar

1. Clone este repositório  
   ```bash
   git clone https://github.com/JoaoPedroBackEndDev/demo-dao-jdbc.git
   ```

2. Abra no seu IDE (Eclipse, IntelliJ, VS Code, etc.)

3. Configure o banco de dados:
   - Crie o banco no seu sistema gerenciador de BD  
   - Ajuste `db.properties` com URL, usuário e senha  

4. Compile e execute as classes principais (ex: classe que contém `main`) que invocam o DAO para testar inserção, listagem, atualização ou remoção de registros  

---

## 🔍 Possíveis melhorias

- Adicionar testes unitários (JUnit) para a camada DAO  
- Implementar transações para garantir consistência em operações múltiplas  
- Fazer tratamento de exceções mais refinado / mensagens de erro melhores  
- Utilizar uma framework ORM (como JPA/Hibernate) para abstração superior  
- Documentar rotas ou uso via API (caso o projeto evolua para API REST)  

---

## 📝 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usar, modificar e distribuir.

---

## 📌 Autor

- **João Pedro** — desenvolvedor Java backend  
- [GitHub](https://github.com/JoaoPedroBackEndDev)  
