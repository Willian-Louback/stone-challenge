Algoritmo Genético criado especialmente para o Desafio do Labirinto Autômato Stone.

O que é o Desafio do Labirinto Autômato Stone? Neste desafio, tive a missão de criar um algoritmo capaz de encontrar caminhos em um labirinto complexo que se modifica a cada movimento. Utilizei conceitos de genética, seleção natural e evolução para otimizar a busca por soluções. 

O tabuleiro conta com casas azuis, verdes e amarelas.

Casa amarela: A casa amarela é imutável e totalmente segura.

Casa verde: A casa verde representa uma célula viva, ela é perigosa, se o jogador passar por ela, ele é eliminado.

Casa azul: A casa azul representa uma célula morta, ela é inofensiva.

Ritmo: O jogador pode se mover em quatro direções: direita, esquerda, cima e baixo. Toda vez que o jogador faz um movimento, as casas se modificam de acordo com as regras de propagação propostas pelo desafio.

Objetivo: Para o jogador vencer, é necessário sair da casa amarela no canto superior esquerdo e chegar na casa amarela do canto inferior direito sem passar por células vivas.

Como funciona o Algoritmo Genético?

1. População Inicial: Comecei com uma população de soluções aleatórias.
2. Avaliação: Cada solução foi avaliada quanto à sua adequação (fitness) para resolver o labirinto.
2. Seleção: As soluções mais aptas foram selecionadas para reprodução.
4. Mutação: Combinei características das soluções selecionadas para gerar novas soluções.
5. Iteração: Repeti os passos anteriores por várias gerações até encontrar a melhor solução.

Resultados e Aprendizados: Meu algoritmo evoluiu ao longo das gerações, aprendendo com os erros e se adaptando ao ambiente do labirinto. Fiquei impressionado com a capacidade do algoritmo em encontrar diferentes soluções para o mesmo desafio.

Agradecimentos: Quero agradecer à Stone e à SigmaGeek por promoverem desafios tão estimulantes.
