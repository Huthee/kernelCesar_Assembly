# Kernel no Cesar
Olá! Bem vindo ao meu trabalho da faculdade sobre Arquitetura de Computadores.

![Screenshot_2](https://github.com/Huthee/kernelCesar_Assembly/assets/89394453/0cf782c9-5dc9-41c6-8088-36302396e523)

Finalizado durante o segundo semestre de 2022, este projeto teve como intuito praticar implementar um protótipo de Kernel (boot de um processador) no processador hipotético Cesar16i. Com uma linguagem simplificada do Assembly, era preciso inicializar variáveis e funções internas como o ponteiro da pilha e do visor; programar as interruções dos periféricos e tratar o funcionamento de um timer.

## Ferramentas Utilizadas:

* Computador Cesar16i
* Montador Daedalus

A arquitetura do Cesar16i incorpora muitos dos principais conceitos da linguagem de programação de baixo-nível, o Assembly, tal como a estrutura LOAD/STORE, sub-rotinas, modos de endereçamento e registradores. A largura dos dados e dos endereços do processador é em 16 bits, no formato Big-Endian, além de sua memória atingir 64Kb. Ele possui 7 registradores e 8 modos de endereçamento. Todas as informações do Cesar16i podem ser encontradas em: https://www.inf.ufrgs.br/arq/wiki/doku.php?id=cesar

## Instruções para Execução:

* Instale o Daedalus e abra o arquivo .CED dentro dele (não esqueça de selecionar o computador Cesar);
* Salve o arquivo para o .MEM ser gerado;
* Instale o Simulador Cesar e abra o .MEM gerado para carregar o Kernel do simulador;
* Carregue os apps de exemplo disponíveis no repositório como carga parcial para testar as funcionalidades do Kernel desenvolvido (endereços em HEX: 8000, FFFBF, 8000)


## Feito Por:
###      Gabriel Alves Bohrer
