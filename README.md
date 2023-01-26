# Calculadora Flex para calcular se é mais vantajoso usar etanol ou gasolina em um veículo flex. Ele possui duas funções principais: "calcular()" e "resetar()".
A função "calcular()" é executada quando o usuário clica em um botão na página HTML, ela faz as seguintes ações:

Declara as variáveis "etanol" e "gasolina". Utiliza o método "parseFloat" para converter os valores de etanol e gasolina inseridos pelo usuário em números decimais. Utiliza o método "replace" para substituir vírgulas por pontos decimais, pois o "parseFloat" não aceita vírgulas. Verifica se os valores de etanol e gasolina são válidos (não estão vazios ou não são números) com as condicionais "if", caso sejam inválidos, a função é interrompida. Compara se o valor de etanol é menor que 70% do valor de gasolina, se for, então a imagem "status" na página HTML é alterada para "./assets/etanol.png". Caso contrário a imagem "status" é alterada para "./assets/gasolina.png". A função "resetar()" é executada quando o usuário clica em outro botão na página HTML, ela faz a seguinte ação:

Altera a imagem "status" na página HTML para "./assets/neutro.png". Essa função é usada para limpar a imagem anterior e retornar a página para o estado inicial. 🚀
