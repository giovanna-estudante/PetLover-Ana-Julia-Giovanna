PetLover

Aplicativo mobile desenvolvido em equipe com o objetivo de facilitar o gerenciamento dos cuidados e serviços relacionados aos pets.

O projeto foi desenvolvido utilizando **React Native com Expo** e integração com **Firebase**, oferecendo autenticação de usuários, cadastro de pets, agendamento de serviços, notificações e gerenciamento de perfil.

---

Sobre o projeto

O **PetLover** é uma aplicação mobile criada para reunir, em um único lugar, funcionalidades relacionadas aos cuidados com animais de estimação.

A aplicação permite que o usuário crie sua conta, cadastre seus pets, consulte serviços disponíveis, realize agendamentos, acompanhe notificações e gerencie suas informações.

O projeto também foi desenvolvido com uma estrutura organizada em telas, componentes, navegação e serviços, buscando separar as responsabilidades da aplicação.

---

Funcionalidades

Autenticação

- Cadastro de novos usuários;
- Login;
- Logout;
- Autenticação utilizando **Firebase Authentication**.

Home

A tela inicial apresenta acesso aos principais recursos do aplicativo:

- Agendamento de banho;
- Agendamento de tosa;
- Agendamento de consulta;
- Acesso à loja de produtos;
- Gerenciamento dos pets.

Pets

O usuário pode:

- Cadastrar seus pets;
- Visualizar os pets cadastrados;
- Editar informações;
- Excluir pets.

Agendamentos

O aplicativo permite realizar agendamentos de serviços para os pets, com informações relacionadas ao serviço e à data escolhida.

Notificações

O sistema possui uma área dedicada às notificações, permitindo:

- Visualizar notificações recebidas;
- Registrar notificações relacionadas aos serviços;
- Exibir informações sobre agendamentos;
- Trabalhar com notificações armazenadas no Firebase.

Perfil

Na área de perfil, o usuário pode:

- Visualizar seus dados;
- Gerenciar informações relacionadas à conta;
- Acessar os pets cadastrados;
- Realizar logout.

Loja

A aplicação também possui uma área destinada à apresentação de produtos e ofertas para os pets.

---

Tecnologias utilizadas

- **React Native**
- **Expo**
- **JavaScript**
- **Firebase Authentication**
- **Cloud Firestore**
- **React Navigation**
- **Expo Notifications**
- **AsyncStorage**
- **React Native Calendars**

---

Para rodar use cd PetLover
Em seguida npx expo start --tunnel

---

Estrutura do projeto

```text
PetLover/
│
├── src/
│   │
│   ├── components/
│   │   ├── Botao.js
│   │   ├── CardOferta.js
│   │   ├── CardProduto.js
│   │   ├── CardServicos.js
│   │   └── Input.js
│   │
│   ├── config/
│   │   └── firebase.js
│   │
│   ├── navigation/
│   │   ├── AuthNavigator.js
│   │   ├── BottomNavigator.js
│   │   └── RootNavigator.js
│   │
│   ├── notificacoes/
│   │   └── notification.js
│   │
│   ├── screens/
│   │   ├── Agendamento.js
│   │   ├── Cadastro.js
│   │   ├── Home.js
│   │   ├── Login.js
│   │   ├── Loja.js
│   │   ├── Notificacoes.js
│   │   ├── Perfil.js
│   │   └── Servicos.js
│   │
│   ├── services/
│   │   ├── agendamento.js
│   │   ├── auth.js
│   │   ├── notificacaoService.js
│   │   └── pets.js
│   │
│   └── styles/
│       └── theme.js
│
├── App.js
├── index.js
├── app.json
├── package.json
└── README.md
