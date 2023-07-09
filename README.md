# Lista de Tarefas

Aplicativo para gerenciar as tarefas do dia-a-dia criado para disciplina de Programação Mobile.

<p align="center">
    <img src="https://miro.medium.com/max/1440/1*oUhhTFGunBMuh4Av-7rR7A.png" width="800"/>
</p>

## Como clonar e importar

-   Faça um fork do projeto
-   Abra o terminal do Visual Studio Code
-   Digite (troque kleberandrade pelo nome do seu usuários): git clone https://github.com/kleberandrade/todo-list-aulas-flutter todo_list

## Desafios

-   Na lista de tarefas, adicionar divisões entre as linhas (use [ListView.separated](https://api.flutter.dev/flutter/widgets/ListView/ListView.separated.html))
-   Adicionar validações no cadastro de uma atividade (lembre-se que é preciso utilizar o widget [TextFormField](https://api.flutter.dev/flutter/material/TextFormField-class.html) para isso)
-   Campo descrição precisar aceitar múltiplas linhas
-   Criar um campo para nível de prioridades que aceita valores entre 1 (baixa prioridade) e 5 (alta prioridade). Representar isso no card da forma como achar mais interessante.
-   Adicionar um [PercentIndicator](https://pub.dev/packages/percent_indicator) circular na barra de navegação para indicar a porcentagem de tarefas concluídas