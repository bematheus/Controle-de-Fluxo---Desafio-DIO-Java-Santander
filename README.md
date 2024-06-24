Explicação do Código
Classe ParametrosInvalidosException: Define uma exceção customizada que será lançada quando o segundo parâmetro for menor ou igual ao primeiro.

Classe Contador:

Método main:
Lê os dois parâmetros do terminal usando um Scanner.
Tenta chamar o método contar.
Captura a exceção ParametrosInvalidosException e imprime a mensagem correspondente.
Fecha o Scanner no bloco finally para garantir que o recurso seja liberado.
Método contar:
Verifica se parametroUm é maior ou igual a parametroDois e lança a exceção ParametrosInvalidosException com a mensagem adequada se a condição for verdadeira.
Calcula a quantidade de interações (contagem) e usa um loop for para imprimir os números de 1 até contagem.
