API SafeGuard 🛡️
📖 Sobre o Projeto
O API SafeGuard é uma aplicação web segura e minimalista projetada para armazenar e gerenciar coleções de API do Postman. A ferramenta foi criada para resolver a necessidade de um repositório central e seguro para dados de API de clientes, que pode ser acessado sob demanda por membros autorizados da equipe, garantindo que informações sensíveis não permaneçam em bases de dados de produção após a entrega de um projeto.

A aplicação utiliza o ecossistema do Firebase para oferecer autenticação de usuários e um banco de dados em tempo real, tudo isso envolvido em uma interface de usuário moderna, responsiva e intuitiva.

✨ Funcionalidades Principais
Autenticação Segura: Sistema completo de login e cadastro de usuários utilizando o Firebase Authentication.

Gerenciamento de Clientes (CRUD):

Adicionar: Cadastre novos clientes com suas respectivas coleções de API em formato JSON.

Visualizar: Veja a lista de clientes e os detalhes formatados de cada coleção.

Excluir: Remova clientes e seus dados de forma segura.

Busca em Tempo Real: Filtre e encontre clientes instantaneamente.

Interface Moderna: Design responsivo e intuitivo, com tema escuro para maior conforto visual.

Feedback ao Usuário: Notificações (toasts) para ações como sucesso ou erro.

Segurança: Acesso aos dados protegido por meio das Regras de Segurança do Firebase.

🛠️ Tecnologias Utilizadas
Frontend:

HTML5

CSS3

JavaScript (Vanilla JS)

Estilização:

Tailwind CSS: Para uma prototipagem rápida e um design moderno.

Ícones:

Lucide Icons: Para ícones SVG leves e customizáveis.

Backend & Banco de Dados (BaaS):

Firebase Authentication: Para gerenciamento de usuários.

Firebase Realtime Database: Como banco de dados NoSQL para armazenar os dados dos clientes.

Firebase Hosting: Para uma hospedagem global, rápida e segura.

🚀 Como Executar o Projeto Localmente
Para rodar este projeto no seu próprio ambiente, siga os passos abaixo:

1. Pré-requisitos
Ter uma conta Google para acessar o Firebase.

Ter o Node.js instalado (necessário para as ferramentas de deploy do Firebase).

Um editor de código como o VS Code com a extensão Live Server.

2. Configuração do Firebase
Crie um Projeto: Vá ao Console do Firebase e crie um novo projeto.

Habilite a Autenticação: No menu Build > Authentication, clique em "Primeiros passos" e habilite o provedor "E-mail/senha".

Habilite o Realtime Database: No menu Build > Realtime Database, crie um novo banco de dados no modo de teste para começar.

Registre seu App Web:

Volte para a tela principal do projeto, clique no ícone da web (</>).

Dê um apelido ao seu app e registre-o.

Copie o objeto firebaseConfig que será exibido.

3. Configuração do Código
Clone este repositório ou simplesmente baixe o arquivo index.html.

Abra o index.html no seu editor de código.

Procure pelo objeto firebaseConfig dentro da tag <script type="module">.

Cole as suas credenciais do Firebase que você copiou no passo anterior, substituindo os valores de exemplo.

4. Execução
Com a extensão Live Server no VS Code, clique com o botão direito no arquivo index.html e selecione "Open with Live Server".

A aplicação abrirá no seu navegador, pronta para ser usada!

☁️ Como Fazer o Deploy
A maneira recomendada para publicar esta aplicação é utilizando o Firebase Hosting.

Instale o Firebase CLI:

npm install -g firebase-tools

Faça o login:

firebase login

Inicie o projeto na pasta raiz:

firebase init

Selecione Hosting.

Conecte ao projeto Firebase que você criou.

Use . como diretório público e configure como um "single-page app".

Publique o site:

firebase deploy
