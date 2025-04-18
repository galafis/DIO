# 🧪 Desafio Prático: Configurando uma Instância de Banco de Dados no Azure

## 🚀 Sobre o Desafio

Esse desafio da DIO foi uma excelente forma de aprender na prática como configurar uma instância de banco de dados usando o **Microsoft Azure**. A proposta é simples, mas bem relevante: criar e documentar esse processo, compartilhando o que foi aprendido de forma que ajude nos estudos e também sirva de base para futuras aplicações.

---

## 🎓 O que eu aprendi com esse desafio?

A configuração de um banco de dados na nuvem é uma habilidade essencial, principalmente pra quem está trilhando o caminho da Ciência de Dados. Esse lab me ajudou a entender:

### 🧩 Conceitos importantes:

- **Instância de Banco de Dados**: é como se fosse o "servidor" que hospeda os bancos de dados, com configurações próprias.
- **Azure SQL Database**: um serviço de banco de dados relacional gerenciado, escalável, com alta disponibilidade.
- **Modelos de Compra**: vCore e DTU (importante escolher o modelo certo pro seu caso de uso).
- **Firewall e Autenticação**: como liberar acesso apenas para IPs confiáveis e configurar logins seguros.

---

## 🔧 Passo a Passo para Criar a Instância no Azure

1. Acesse o [Portal do Azure](https://portal.azure.com)
2. No menu de busca, digite **SQL Database** e clique em **Criar**
3. Escolha o grupo de recursos ou crie um novo
4. Dê um nome para seu banco de dados
5. Crie uma nova instância de servidor SQL (definindo login e senha de administrador)
6. Escolha a região onde os dados ficarão hospedados
7. Configure o plano de desempenho: vCore ou DTU (opte por uma opção básica se for apenas para testes)
8. Em **Networking**, configure o acesso ao banco (libere seu IP)
9. Clique em **Revisar + Criar** e depois em **Criar**
10. Espere alguns minutos e pronto! Sua instância estará ativa

---

## 💡 Dicas que anotei ao longo do caminho

- Use o **Data Studio** ou o **SSMS** pra conectar e testar a instância criada
- Sempre configure uma **regra de firewall** para seu IP, senão você não vai conseguir acessar o banco
- Prefira o modelo de consumo mais simples (DTU básico) se o objetivo for apenas aprendizado
- Mantenha os dados seguros e nunca exponha senhas em arquivos públicos

---

## 📁 Estrutura do Repositório

```
azure-sql-lab/
│
├── README.md          ← Documentação principal do desafio
├── /images            ← Prints e capturas de tela do processo
└── conexao.sql        ← Script de teste de conexão (opcional)
```

---

## 📸 Capturas de Tela (opcional)

Coloquei algumas imagens da criação da instância na pasta `/images`.
Você pode referenciar assim no README:

```markdown
![Criação do banco](images/criando-sql-db.png)
```

---

## ✅ Conclusão

Esse desafio foi super válido pra entender como funcionam bancos de dados na nuvem. A ideia de usar o GitHub pra documentar o processo também é muito boa, porque nos ensina a manter um histórico organizado das nossas experiências técnicas. Agora tenho um repositório que posso revisitar sempre que precisar refazer esse processo ou compartilhar com colegas.

Se quiser contribuir com melhorias ou tirar dúvidas, me chama ou manda um PR! 😄
