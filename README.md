======================================
Calculadora em ANSI C89
======================================

Uma calculadora completa desenvolvida em linguagem C seguindo o padrão ANSI C89, o mais portável entre todos os compiladores. O programa oferece calculadora aritmética com as quatro operações básicas e calculadora do programador para conversão entre bases hexadecimal, decimal, octal e binária.

===========================================
Funcionalidades
===========================================

Calculadora Aritmética: realiza adição, subtração, multiplicação e divisão com verificação de divisão por zero.

Calculadora do Programador: converte números entre as bases hexadecimal, decimal, octal e binária. O usuário pode digitar o valor em qualquer base e o programa exibe o equivalente nas quatro bases simultaneamente.

===========================================
Estrutura do Código
===========================================

O código é organizado em funções específicas para cada operação. As funções de conversão de decimal para outras bases utilizam recursão. As funções de conversão inversa percorrem as strings da direita para a esquerda aplicando pesos posicionais. Uma função dedicada limpa o buffer do teclado para evitar problemas de leitura.

===========================================
Requisitos
===========================================

Nenhuma biblioteca externa é necessária. Apenas um compilador C compatível com ANSI C89 e um terminal para execução.

===========================================
Licença
===========================================

Este projeto é de código aberto e pode ser livremente utilizado para fins educacionais ou práticos.

===========================================
Autor  Manoel (Titto) Pereira de Lima Filho
===========================================

Desenvolvido como projeto para estudo da linguagem C, demonstrando recursão, conversão entre bases, manipulação de strings e portabilidade de código.
