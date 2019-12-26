# Seguidor de Linha - Portas Lógicas
Projeto de um carrinho seguidor de linha utilizando portas lógicas e motores de passo de 12V.

# Funcionamento
Por meio de três sensores na dianteira do carrinho, obtém-se as direções em que o carrinho deve seguir para completar um circuito fechado construído a partir de uma fita isolante preta. \
Seu funcionamento completo está descrito no arquivo **relatorio-projeto.pdf** contido no repositório.

# Lógica
A lógica de rotação das rodas seguiu o mesmo princípio do projeto [Carro Remoto](https://github.com/luiseduardobr1/remotecar/), que utilizou um microprocessador para realização da energização das bobinas do motor de passo. Para o presente projeto, essa energização se deu a partir das saídas dos Flip-Flop's durante as bordas de subida do *clock*. 

# Esquemáticos
Todos os esquemáticos das montagens estão contidos no repositório, os quais estão divididos em:
* **sensores.PDF** - Esquemático de ligação dos sensores de entrada 
* **divisor-frequencia.PDF** - Esquemático de ligação do sinal de clock com divisor de frequência 
* **Controle-Passo.PDF** - Esquemático de ligação do controle do motor de passo 
* **projeto-completo.PDF** - Esquemático geral de ligação do projeto completo 

# Simulação
O circuito foi simulado no *software* Proteus, o qual o arquivo está contido em **Projeto-Final.pdsprj**

# Montagem e Teste
O carrinho conseguiu completar o circuito em 1min37s durante a avaliação da disciplina de Eletrônica Digital (UFC - 2019) sendo o mais rápido dentre os apresentados, como mostrado no vídeo abaixo:\

[![Seguidor de Linha Portas Lógicas](https://img.youtube.com/vi/th3yvXdkAdE/0.jpg)](https://www.youtube.com/watch?v=th3yvXdkAdE)
