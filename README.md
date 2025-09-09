## Projeto 18 - Botão com Animação de Efeito Arco-íris

### 🚀 Sobre o Projeto

O projeto consiste em uma página minimalista com um único botão. Ao passar o mouse sobre ele, uma animação de efeito de arco-íris é ativada, criando um visual rotativo e colorido.

### 🛠️ Tecnologias e Conceitos Abordados

#### HTML5

O HTML é direto e minimalista. Eu usei a estrutura de um div pai (.btn) envolvendo a tag <a> com um span dentro. Essa hierarquia me permitiu aplicar a estilização e a animação em camadas, separando o efeito do background do texto do botão.

#### CSS3

Neste projeto, explorei alguns conceitos de animação. O uso de linear-gradient foi fundamental para criar o fundo colorido inicial. A propriedade filter: hue-rotate() é a estrela do projeto, pois ela me permitiu rotacionar as cores do elemento, criando o efeito de arco-íris sem precisar de múltiplas etapas de cor na animação. A animação foi ativada com a pseudoclasse :hover, e a regra @keyframes foi usada para definir a animação de rotação de 360 graus. Além disso, a combinação de position: relative e position: absolute com transform: translate() foi utilizada para centralizar perfeitamente o texto do botão sobre o fundo animado, criando a ilusão de que apenas a borda está se movendo.

### 💻 Como Executar:

Instale o arquivo no seu computador, e abra no seu navegador de preferencia.
