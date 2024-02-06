## Calculadora de IMC

Este é um projeto simples de uma calculadora de Índice de Massa Corporal (IMC) desenvolvida em HTML, CSS e JavaScript.
Este projeto foi criado como parte de curso de formação frontend.

## Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript

## Funcionalidades

Cálculo do IMC

    Entrada de Dados: Os usuários podem inserir sua altura e peso na calculadora. Cada campo é associado a uma variável no JavaScript para manipulação posterior.

    Cálculo Automático: Ao pressionar o botão "Calcular", o código calculará o IMC com base nos valores inseridos. Quando o botão é clicado, uma função JavaScript é acionada para calcular o IMC com base nos valores inseridos nos campos de altura e peso.

    Validação de Dados: Um evento de entrada (input) é associado aos campos de altura e peso para garantir que apenas números e vírgulas sejam aceitos. Isso é feito usando expressões regulares para substituir qualquer caractere que não seja um número ou vírgula por uma string vazia.

    Classificação do IMC: Após o cálculo, o IMC é classificado de acordo com as categorias estabelecidas pela OMS (Organização Mundial da Saúde). Com base no valor calculado do IMC, a função JavaScript determina a classificação apropriada e a exibe na interface.


- Exibição dos Resultados

    Feedback Visual: O resultado do IMC é exibido em um formato visualmente claro. A cor do texto é modificada dinamicamente com base na classificação de saúde, utilizando classes CSS específicas.

    Classificação de Saúde: Além do valor do IMC, é exibida a classificação da saúde do usuário. Esta classificação é exibida para fornecer ao usuário uma compreensão rápida de sua saúde com base no IMC calculado.

    Indicação de Obesidade: Caso o IMC indique obesidade, é fornecida a classificação de obesidade (se aplicável).

- Limpeza e Retorno

    Limpeza de Dados: O botão "Limpar" permite ao usuário limpar os campos de entrada.

    Retorno à Entrada: O botão "Voltar" retorna à tela de entrada para permitir novos cálculos.

## Estrutura do Projeto

- `index.html`: O arquivo HTML principal que contém a estrutura da página.
- `css/styles.css`: Estilos CSS para a aparência da página.
- `js/scripts.js`:  Arquivo JavaScript para adicionar interatividade à página.


## Autores

- [@RaquelGui](https://www.github.com/RaquelGui)

Sinta-se à vontade para utilizar, modificar e adaptar este conteúdo, de acordo com as necessidades específicas do seu projeto. 