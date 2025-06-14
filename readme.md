# Avaliação Interativa de Lógica com JavaScript

**Este é um projeto de uma página (Single Page Application - SPA) que oferece uma avaliação interativa de lógica de programação utilizando JavaScript puro, HTML e Tailwind CSS. O objetivo é proporcionar uma ferramenta simples e eficaz para testar conhecimentos básicos de JavaScript e, ao mesmo tempo, servir como um exemplo prático de aplicação web interativa.**

## Funcionalidades

* **Questões Interativas:** Uma série de questões de lógica e sintaxe JavaScript, com campos para preencher código ou respostas.
* **Verificação de Resposta Imediata:** Feedback visual instantâneo (Correto/Incorreto) para cada questão.
* **Persistência de Progresso:** O progresso do usuário é salvo automaticamente no `<span class="selected">`localStorage do navegador, permitindo que o aluno continue de onde parou.
* **Resumo de Desempenho Visual:** Após "Finalizar Avaliação", um modal exibe um gráfico de pizza (usando Chart.js) mostrando a proporção de acertos, erros e questões não respondidas.
* **Geração de Respostas para Envio:** Um modal dedicado gera um resumo detalhado de todas as respostas do aluno, incluindo o status de cada questão, que pode ser facilmente copiado para envio ao professor via e-mail.
* **Reinício Claro da Avaliação:** Um botão específico "Reiniciar Avaliação" permite que o usuário apague todo o progresso e comece a avaliação do zero de forma intencional.
* **Dialog Suas Sespostas para Envio :** permite visualizar suas perguntas com status respondidos.

## Como Usar

1. **Abrir o Arquivo:** Simplesmente abra o arquivo <span class="selected">index.html</span> em qualquer navegador web moderno.
2. **Responder às Questões:** Para cada questão, preencha os campos de código ou texto com as suas respostas.
3. **Verificar Respostas:** Clique no botão "Verificar Resposta" para cada questão para obter feedback imediato sobre a sua tentativa.
4. **Finalizar Avaliação:** Ao terminar de responder (ou quando desejar ver o seu desempenho), clique no botão "Finalizar Avaliação". Um modal será exibido com um resumo do seu desempenho em formato de gráfico.
5. **Gerar Respostas para Envio:** Se desejar enviar o seu progresso, clique no botão "Gerar Respostas para Envio" (este botão só estará ativo após finalizar a avaliação). Um novo modal aparecerá com uma tabela de todas as suas respostas e um resumo.
6. **Copiar Resumo:** Dentro do modal de envio, clique em "Copiar Resumo Completo" para copiar todo o conteúdo da área de texto, que inclui suas respostas e o e-mail do professor para o qual enviar.
7. **Reiniciar:** Se quiser começar a avaliação do zero, clique no botão "Reiniciar Avaliação".

## Estrutura do Projeto

**O projeto é composto por um único arquivo HTML que contém todo o HTML, CSS (com Tailwind CSS) e JavaScript.**

* <span class="selected">index.html</span>: Contém a estrutura da página, os estilos e toda a lógica da aplicação.

## Tecnologias Utilizadas

* **HTML5:** Estrutura básica da página.
* **Tailwind CSS:** Framework CSS para estilização rápida e responsiva.
* **JavaScript (Vanilla JS):** Lógica interativa da aplicação, validação de respostas, manipulação do DOM e gestão do <span class="selected">localStorage</span>.
* **Chart.js:** Biblioteca JavaScript para a criação do gráfico de desempenho.

## Créditos

**Desenvolvido por Clayton.**
