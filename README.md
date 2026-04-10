# 🚀 RegistroDeUsuariosComRecompensa

Smart Contract desenvolvido em **Solidity** com o objetivo de simular um sistema de registro de usuários e distribuição de recompensas em tokens fictícios.

---

## 📌 Objetivo

Demonstrar na prática o funcionamento de um Smart Contract na blockchain Ethereum, utilizando conceitos fundamentais como:

- Smart Contracts
- Ethereum Virtual Machine (EVM)
- Structs e Mappings
- Eventos
- Validações com require()
- Simulação de token

---

## ⚙️ Funcionalidades

✔ Registro de usuários  
✔ Consulta de dados cadastrados  
✔ Sistema de recompensa em tokens simulados  
✔ Emissão de eventos na blockchain  
✔ Validação de segurança (evita duplicidade e erros)

---

## 🧪 Testes realizados

O contrato foi testado no **Remix IDE**, validando:

- Registro de usuários com sucesso  
- Bloqueio de cadastro duplicado  
- Distribuição de recompensas  
- Emissão de eventos (`UsuarioRegistrado` e `RecompensaEnviada`)  
- Controle de saldo por usuário  

---

## 🧠 Como funciona

O contrato utiliza:

- `mapping` para armazenar usuários e saldos  
- `struct` para representar os dados do usuário  
- `require()` para garantir segurança nas operações  
- `event` para registrar ações na blockchain  

---

## 💡 Caso de uso real

Este contrato pode ser aplicado em:

- 🏋️ Academias (recompensa por desafios)
- 📚 Plataformas educacionais (incentivo ao aprendizado)
- 📈 Apps de produtividade (gamificação de tarefas)
- 🌐 Sistemas Web3

---

## 🛠️ Tecnologias utilizadas

- Solidity  
- Remix IDE  
- Ethereum (simulação)

---

## 👤 Autor

**Carlos Eduardo Alves da Silva**  
GitHub: https://github.com/Eduprogrammer  

---

## 📌 Observação

Este projeto tem caráter educacional e foi desenvolvido como parte do estudo de conceitos fundamentais de Web3 e Smart Contracts.