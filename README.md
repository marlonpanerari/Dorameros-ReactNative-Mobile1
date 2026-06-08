# Dorameros

Projeto de **Frontend Mobile** desenvolvido como trabalho final da disciplina de **Mobile 1** — ETEC de Guarulhos

---

## 📖 Sobre o Projeto

Dorameros é um aplicativo mobile de catálogo de doramas (dramas asiáticos) desenvolvido com foco em **Frontend Mobile** utilizando **React Native** e **Expo**. O app permite navegar por títulos, visualizar detalhes, favoritar doramas e acessar um chat.

---

## 🎯 Funcionalidades

- **Login** - Tela de autenticação com campos de e-mail e senha
- **Home** - Vitrine com poster em destaque e acesso ao perfil do usuário
- **Filmes** - Grade com 14 títulos, com navegação para tela de detalhes
- **Favoritos / Ranking** - Lista de doramas favoritos com sistema de ranking
- **Chat** - Tela de mensagens integrada

---

## 🗂️ Estrutura de Navegação

```
App
├── Login
└── Routes (Bottom Tab Navigator)
    ├── Home
    │   ├── Play
    │   └── Profile
    ├── Movie
    │   └── Details
    ├── Favorite
    │   └── Ranking
    └── Chat
```

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Uso |
|---|---|
| React Native | Estrutura e componentes da interface mobile |
| Expo | Ambiente de desenvolvimento e build |
| React Navigation v5 | Stack Navigator e Bottom Tab Navigator |
| Material Top Tabs | Navegação por abas superiores |
| React Native Paper | Biblioteca de componentes de UI |

---

## 📋 Exigências Atendidas

- ✅ Interface 100% construída em Frontend com React Native
- ✅ Tela de Login
- ✅ Navegação entre múltiplas telas
- ✅ Catálogo com 14 títulos e tela de detalhes
- ✅ Sistema de favoritos com ranking
- ✅ Tela de chat
- ✅ Navegação por abas (Bottom Tab + Stack + Material Top Tabs)

---

## 🚀 Como Executar

**Pré-requisitos:** Node.js e Expo CLI instalados.

```bash
# Instalar dependências
npm install

# Iniciar o projeto
npx expo start
```

Escaneie o QR Code com o aplicativo **Expo Go** no seu celular (Android ou iOS).

---

## 👤 Autor
**Marlon Panerari**
