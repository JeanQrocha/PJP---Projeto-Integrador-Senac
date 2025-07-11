# 💰 Sistema de Controle Financeiro Pessoal (WinForms em C#)

Este é um projeto de um **sistema de controle financeiro pessoal**, desenvolvido em C# com Windows Forms. O sistema permite que usuários registrem, editem e visualizem transações financeiras como entradas e saídas, mantendo um saldo atualizado e gerando relatórios personalizados.

## 📌 Funcionalidades

- ✅ Cadastro de usuários com validação de senha
- 🔐 Login seguro com hash de senha
- 👤 Edição de conta do usuário
- 💸 Registro de transações financeiras (entrada ou saída)
- 📊 Relatório completo com resumo de saldo, entradas e saídas
- 📆 Histórico de transações exibido em tabela
- 📂 Separação por categorias: Alimentação, Transporte, Lazer, Salário, Saúde, Outros

## 🖥️ Tecnologias Utilizadas

- Linguagem: **C#**
- Interface gráfica: **Windows Forms (WinForms)**
- Arquitetura em camadas: `Model`, `View`, `Controller`, `Repository`

## 🧱 Estrutura do Projeto

```
├── View
│   ├── ViewLogin.cs           # Tela de login
│   ├── ViewCadastro.cs        # Cadastro de novos usuários
│   ├── ViewEditarConta.cs     # Edição de conta do usuário logado
│   ├── ViewTransacao.cs       # Tela principal para registrar transações
│   └── ViewRelatorio.cs       # Relatório geral das transações
├── Controller
│   └── ControllerTransacao.cs # Lógica para gerenciar transações
├── Repository
│   └── RepositoryUsuario.cs   # Acesso aos dados de usuário
│   └── RepositoryTransacao.cs# Acesso aos dados de transações
├── Model
│   ├── Usuario.cs             # Classe do modelo de usuário
│   └── Transacao.cs           # Classe do modelo de transações
```

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. Abra o projeto no **Visual Studio**
3. Compile e execute (`F5`)
4. Faça o cadastro de um usuário e comece a registrar suas transações

## 📸 Capturas de Tela (Opcional)

Adicione aqui screenshots das telas de Login, Cadastro, Transações e Relatório, se desejar.

## 🛠️ Futuras Melhorias

- Armazenamento em banco de dados (atualmente em memória/arquivos?)
- Exportar relatório em PDF
- Suporte a múltiplas moedas
- Autenticação com token JWT para versão web futura

## 📄 Licença

Este projeto está sob a licença MIT. Sinta-se livre para utilizar, modificar e distribuir.

---

Feito com 💻 e ☕ por [Seu Nome]
