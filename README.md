# 🚀 Desafio Prático: Criando uma Máquina Virtual no Azure

## ✨ Sobre o Desafio

Esse desafio da DIO foi uma ótima oportunidade pra colocar a mão na massa e aprender como **criar e configurar uma máquina virtual (VM)** usando a **plataforma Microsoft Azure**. A ideia principal aqui é documentar toda essa experiência, desde o primeiro clique até a VM rodando, criando um material que ajude tanto eu quanto outras pessoas em futuras implementações.

---

## 📚 O que eu aprendi nesse desafio?

Durante as aulas e a prática, entendi vários conceitos fundamentais do Azure e de infraestrutura em nuvem. Aqui estão os principais pontos que anotei:

### ☁️ Conceitos Importantes

- **Azure Portal**: Interface web onde você gerencia seus recursos.
- **Máquina Virtual (VM)**: Computador virtualizado que roda no datacenter da Microsoft.
- **Grupos de Recursos**: Conjunto de recursos que são gerenciados juntos.
- **Região**: Datacenter físico onde os recursos vão ficar hospedados.
- **Imagem do SO**: Sistema operacional da VM (Windows, Ubuntu, etc.).
- **Tamanho da VM**: Define CPU, memória, e outras capacidades da máquina.

---

## 🛠️ Passo a Passo para Criar a VM

1. Acesse o [Portal do Azure](https://portal.azure.com)
2. No menu lateral, clique em **Máquinas Virtuais** > **+ Criar**
3. Escolha o grupo de recursos (ou crie um novo)
4. Configure o nome da VM, região, imagem do sistema e tipo de autenticação (senha ou chave SSH)
5. Escolha o tamanho da VM de acordo com o uso (testes = máquina pequena)
6. Deixe as configurações padrão de rede (ou personalize se quiser aprender mais)
7. Clique em **Revisar + Criar** e depois em **Criar**
8. Aguarde alguns minutos e… VM criada com sucesso!

---

## 🧠 Dicas que eu separei pra facilitar a vida

- Se for só pra estudar, escolha as opções gratuitas ou de menor custo (como as VMs da série B).
- Lembre de **parar ou excluir** a VM quando não estiver usando, senão a grana vai embora rápido!
- Dá pra acessar a VM via **RDP (no Windows)** ou **SSH (no Linux)**, conforme o sistema escolhido.
- Use **tags nos recursos** para organização e controle de gastos.

---

## 📁 Estrutura do Repositório

```
azure-vm-lab/
│
├── README.md          ← Este arquivo com toda a documentação
├── /images            ← Pasta com prints do processo (opcional, mas útil)
└── anotacoes.txt      ← Arquivo com minhas anotações brutas (se quiser deixar algo extra)
```

---

## 📸 Capturas de Tela

Se quiser turbinar esse repositório, crie uma pasta `/images` e salve nela prints do processo de criação da VM. Depois, use o Markdown pra exibir assim:

```markdown
![Criação da VM](images/criando-vm.png)
```

---

## ✅ Conclusão

Finalizar esse desafio foi uma experiência massa pra quem tá começando a lidar com nuvem. Ver uma VM rodando e saber que você mesmo configurou tudo é bem gratificante. Além disso, aprendi mais sobre documentação técnica e como deixar meu repositório GitHub mais organizado e útil pros outros.

---

Se quiser contribuir com melhorias, pode abrir um PR aqui no repositório! 😄
