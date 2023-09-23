Orientação a Objetos e UML: Diagramação de Classes do iPhone

Este é um diagrama UML que representa a estrutura de classes e interfaces para um sistema que inclui a modelagem do iPhone, um dispositivo que incorpora funcionalidades de um reprodutor de música, 
um telefone e um navegador de internet. Este diagrama foi criado como parte do desafio de projeto do Santander Bootcamp 2023 - Fullstack Java+Angular na DIO.me.

![UML Iphone](https://github.com/Gerleidson/UML_Iphone/assets/88213553/a0f91d4f-5d41-4a6b-8568-129986d4863b)

Descrição:

## Reprodutor Musical

Interface responsável por implementar a funcionalidade de reprodução de arquivos de áudio.
Ela possui métodos como tocar(), pausar(), e selecionarMusica().
A classe Musica armazena informações sobre as músicas.

## Aparelho Telefônico 

Interface responsável por implementar a funcionalidade de um telefone.
Ela possui métodos como ligar(), atender(), e iniciarCorreioVoz().
A classe Contato armazena informações de contatos como nome e numero.

## Navegador de Internet

Interface responsável por implementar a funcionalidade de um navegador web. 
Ela possui métodos como exibirPagina(), adicionarNovaAba(), e atualizarPagina().
