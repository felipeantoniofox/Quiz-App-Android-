🧠 My Personal Quiz App (React Native/Expo & Firestore)
[Insert an image or GIF of your running app here!]

This is a complete mobile quiz application, developed with React Native (Expo), which allows the user to not only play but also create and manage their own question and answer content in real-time.

The project uses Firebase Firestore as the backend for dynamic data storage. This feature is the main differentiator, as it allows the quiz content to be updated instantly without requiring application redeployment.

✨ Featured Functionality
1. Dynamic Content Management
Theme Creation: The user can create new quiz categories (e.g., "History," "Technology") and customize them with a color and an icon.

Question Registration: Add multiple-choice questions to any theme, defining the question text and marking the correct alternative.

Deletion and Cleanup: Remove themes and individual questions through the Management screen.

2. Game Experience (Under Development)
Custom Selection: Choose themes and the number of questions to start a customized quiz.

Scoring Mechanism: Track the score and progress during the game.

🚀 Technologies Used
Category

Technology

Main Use

Mobile Framework

React Native (with Expo)

Development of the native user interface for Android and iOS.

Backend / DB

Firebase Firestore

Real-time NoSQL database for storing themes and questions.

Navigation

Expo Router

Application route and screen management.

Styling

React Native Styling

Creation of responsive and aesthetically pleasing layouts.

Components

Vector Icons

Use of icons for theme customization.

🛠️ How to Install and Run the Project
Prerequisites
Node.js (LTS version recommended).

Expo CLI (installed globally).

A Firebase account and a configured project (with the Firestore service enabled).

Setup Steps
Clone the Repository:

git clone [YOUR_REPO_LINK]
cd your-repo-name

Install Dependencies:

npm install

Firebase Configuration (.env file)
Create a file named .env in the root of the project and insert your Firebase project credentials (found in your project settings):

# .env
EXPO_PUBLIC_FIREBASE_API_KEY="YOUR_API_KEY"
EXPO_PUBLIC_FIREBASE_AUTH_DOMAIN="YOUR_AUTH_DOMAIN"
EXPO_PUBLIC_FIREBASE_PROJECT_ID="YOUR_PROJECT_ID"
EXPO_PUBLIC_FIREBASE_STORAGE_BUCKET="YOUR_STORAGE_BUCKET"
EXPO_PUBLIC_FIREBASE_MESSAGING_SENDER_ID="YOUR_MESSAGING_SENDER_ID"
EXPO_PUBLIC_FIREBASE_APP_ID="YOUR_APP_ID"

Run the Application:

npx expo start

Scan the QR Code that appears in the terminal (or browser) using the Expo Go app on your phone to view and test the app in real-time.



🧠 My Personal Quiz App (React Native/Expo & Firestore)

Este é um aplicativo móvel de quiz completo, desenvolvido com React Native (Expo), que permite ao usuário não apenas jogar, mas também criar e gerenciar seu próprio conteúdo de perguntas e respostas em tempo real.

O projeto utiliza o Firebase Firestore como backend para armazenamento dinâmico de dados. Este recurso é o grande diferencial, pois permite que o conteúdo do quiz seja atualizado instantaneamente sem a necessidade de reimplantação do aplicativo.

✨ Funcionalidades em Destaque
1. Gerenciamento de Conteúdo Dinâmico
Criação de Temas: O usuário pode criar novas categorias de quiz (ex: "História", "Tecnologia") e personalizá-las com cor e ícone.

Cadastro de Perguntas: Adicione perguntas de múltipla escolha a qualquer tema, definindo o texto da pergunta e marcando a alternativa correta.

Exclusão e Limpeza: Remova temas e perguntas individualmente através da tela de Gerenciamento.

2. Experiência de Jogo (Em Desenvolvimento)
Seleção Personalizada: Escolha os temas e a quantidade de perguntas para iniciar um quiz customizado.

Mecanismo de Pontuação: Acompanhe a pontuação e o progresso durante o jogo.

🚀 Tecnologias Utilizadas
Categoria

Tecnologia

Uso Principal

Framework Mobile

React Native (com Expo)

Desenvolvimento da interface do usuário nativa para Android e iOS.

Backend / DB

Firebase Firestore

Banco de dados NoSQL em tempo real para armazenamento de temas e perguntas.

Navegação

Expo Router

Gerenciamento de rotas e telas do aplicativo.

Estilização

React Native Styling

Criação de layouts responsivos e esteticamente agradáveis.

Componentes

Vector Icons

Utilização de ícones para personalização dos temas.

🛠️ Como Instalar e Rodar o Projeto
Pré-requisitos
Node.js (versão LTS recomendada).

Expo CLI (instalado globalmente).

Uma conta no Firebase e um projeto configurado (com o serviço Firestore ativado).

Passos de Configuração
Clone o Repositório:

git clone [SEU_LINK_DO_REPOSITORIO]
cd nome-do-seu-repositorio

Instale as Dependências:

npm install

Configuração do Firebase (Arquivo .env)
Crie um arquivo chamado .env na raiz do projeto e insira as suas credenciais do projeto Firebase (encontradas nas configurações do seu projeto):

# .env
EXPO_PUBLIC_FIREBASE_API_KEY="SUA_API_KEY"
EXPO_PUBLIC_FIREBASE_AUTH_DOMAIN="SEU_AUTH_DOMAIN"
EXPO_PUBLIC_FIREBASE_PROJECT_ID="SEU_PROJECT_ID"
EXPO_PUBLIC_FIREBASE_STORAGE_BUCKET="SEU_STORAGE_BUCKET"
EXPO_PUBLIC_FIREBASE_MESSAGING_SENDER_ID="SEU_MESSAGING_SENDER_ID"
EXPO_PUBLIC_FIREBASE_APP_ID="SEU_APP_ID"

Execute o Aplicativo:

npx expo start

Escaneie o QR Code que aparece no terminal (ou no navegador) usando o aplicativo Expo Go no seu celular para visualizar e testar o app em tempo real.
