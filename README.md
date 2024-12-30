Lista de Tarefas 🔧🏠

Este projeto foi desenvolvido como parte do curso "Criação de Apps Android/iOS/Web com Flutter - 5 cursos em 1".

Trata-se de uma aplicação simples para gerenciar tarefas (“To-Do List”), utilizando Flutter, com funcionalidades como adicionar, marcar como concluído e excluir tarefas, além de salvar os dados localmente.

✨ Funcionalidades

Adicionar tarefas: Digite o título de uma tarefa e clique no botão "ADD" para adicioná-la à lista.

Marcar como concluído: Use a caixa de seleção para indicar que uma tarefa foi finalizada.

Excluir tarefas: Deslize uma tarefa para a direita para removê-la.

Desfazer exclusão: Um "Snackbar" permite desfazer a exclusão de uma tarefa.

Salvar e carregar tarefas: As tarefas são salvas localmente em um arquivo JSON, garantindo que estejam disponíveis ao reiniciar o app.

Atualização rápida: Puxe a lista para baixo para reorganizar as tarefas, colocando as concluídas no final.

📚 Estrutura do Código

Principais componentes:

Home: Componente principal que gerencia o estado do aplicativo e exibe a interface do usuário.

_addToDo: Adiciona uma nova tarefa à lista.

_refresh: Reorganiza a lista de tarefas para destacar as pendentes.

_saveData** e ****_readData**: Gerenciam o salvamento e leitura de dados no armazenamento local usando a biblioteca path_provider.

🎨 Design

Barra superior: Exibe o título “Lista de Tarefas”.

Campo de entrada e botão: Adicione novas tarefas facilmente.

Lista de tarefas: Visualize e gerencie suas tarefas com uma interface intuitiva.

Estilo: Cores e ícones simples e agradáveis, destacando a usabilidade.

⚡ Como executar o projeto

Clone o repositório:

git clone https://github.com/ericdiasblu/lista_de_tarefas_remake_flutter

Acesse a pasta do projeto:

cd lista_de_tarefas_remake_flutter

Instale as dependências:

flutter pub get

Execute o app:

flutter run

🔧 Tecnologias utilizadas

Linguagem: Dart

Framework: Flutter

Pacotes:

path_provider**: Para localizar o caminho dos diretórios no dispositivo.

dart:convert**: Para manipulação de dados JSON.
