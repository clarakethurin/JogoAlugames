# JogoAlugames
Sistema de Aluguel de Jogos

Este repositório contém o código JavaScript responsável pela lógica do sistema AluGames, uma aplicação simples que simula o aluguel e devolução de jogos. O usuário pode alternar o status de cada jogo com apenas um clique, e o sistema controla automaticamente o total de jogos alugados.

🚀 Funcionalidades

Alternar o status de um jogo entre Alugar e Devolver

Confirmação ao devolver um jogo

Contador automático de jogos alugados

Atualização visual do botão conforme o status

Leitura dos jogos já alugados ao carregar a página

🧠 Como funciona
alterarStatus(id)

Altera o status do jogo selecionado:

Marca ou desmarca como alugado

Troca o texto do botão

Adiciona ou remove classes CSS

Atualiza o contador de jogos alugados

Exibe confirmação ao devolver

mostrarJogosAlugados()

Exibe no console a quantidade total de jogos alugados.

Evento DOMContentLoaded

Inicializa o sistema contando quantos jogos já estão marcados como alugados.

📂 Estrutura esperada no HTML

O JavaScript espera elementos com esta estrutura:

<div class="dashboard__item" id="game-1">
    <img class="dashboard__item__img" src="..." />
    <h2 class="dashboard__item__name">Nome do Jogo</h2>
    <button class="dashboard__item__button" onclick="alterarStatus(1)">Alugar</button>
</div>


Classes utilizadas:

.dashboard__item__img

.dashboard__item__img--rented

.dashboard__item__button

.dashboard__item__button--return

.dashboard__item__name

📌 Tecnologias utilizadas

JavaScript (Vanilla JS)

DOM API

Eventos

Manipulação de classes

Funções modulares

▶️ Como executar

Clone o repositório:

git clone https://github.com/SEU-USUARIO/alugames


Abra o arquivo index.html no navegador.

Clique nos botões para alugar ou devolver jogos.

👩‍💻 Autora

Clara Kethurin
Desenvolvedora Front-end
Estudante de Análise e Desenvolvimento de Sistemas
