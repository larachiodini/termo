Esse código usa a lista de palavras oficial e na ordem do jogo Termo(term.ooo), afim de descobrir qual a palavra do dia.

No código fonte do site, você pode buscar pela função "Pf()" para encontrar a lista de palavras. Além disso, buscando a função "Eh()", é possível encontrar a lógica de contagem de dias, iniciando do primeiro dia de lançamento do jogo (02/01/2022) até hoje.

O código calcula o índice do dia atual: dia atual % número de palavras na lista (1442) = o resto da divisão é o índice de hoje. E busca qual a palavra correspondente na lista, fornecendo a palavra do jogo do dia de hoje.
