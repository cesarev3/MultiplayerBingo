# SerMaisTech - MultiplayerBingo
Projeto de conclusão do módulo Lógica de Programação I do Programa Ser Mais<br>
Tech da ADA Tech / Núclea<br>

# Descrição do Projeto
Etapa 1 - Apresentação e Jogadores<br>
1. Mensagem de boas vindas e mostrar opções de comando<br>
2. Dar um design bacana para o visual e dê um nome ao jogo<br>
3. Considerar o modo multiplayer automático com 1 ou mais jogadores<br>
4. Separar por hifen o nickname: player1-player2-player3<br>

Etapa 2 - Cartelas
1. Gerar as cartelas desejadas<br>
2. Opções de comando para cartelas geradas RANDOM ou MANUAL<br>
3. Para MANUAL localizar o nickname preencher a cartela<br>
4. O input deverá ser: "1,2,3,4,5-6,7,8,9,1-2,3,4,5,6"<br>
5. Para RANDOM será gerado automaticamente aleatórias cartelas não repetidas<br>
6. A cartela não pode ter números repetidos<br>

Etapa 3 - Números Sorteados
1. Opções de comando do sorteio podem ser RANDOM ou MANUAL<br>
2. Para MANUAL os números sorteados entrarão via Scanner<br>
3. O input deverá seguir a sintaxe: "1,2,3,4,5"<br>
4. Para RANDOM serão números aleatórios não repetidos na cartela<br>
5. A cada round deverá imprimir:<br>
   *    Um ranking dos top 3 mais bem pontuados no game<br>
   *    Um pedido de pressionar a tecla para continuar via Scanner<br>
   *    Se pressionar X aborta o game<br>

Etapa 4 - Fim do Jogo
1. Cada jogador terá um array para indicar os números acertados<br>
2. Esse array indica a posição de cada número na cartela<br>
3. Aqui temos os dois ultimos números acertados, ex: 0,0,0,1,1<br>
4. O bingo será eleito quando o jogador tiver todos com número 1<br>
5. Ao final do game exibir o ranking geral e estatísticas do game:<br>
   * Quantidade de rounds<br>
   * Cartela premiada com números ordenados e nome do vencedor<br>
   * Quantidade e números sorteados em ordem<br>
   * Ranking geral ordenado pelo número de acertos<br>

Etapa 5 - Regras Gerais e Sugestões para implementar
1. Não usar classes e derivadas de Collections, use array/matriz
2. Pode usar classes utilitárias do java.util como Random e Arrays
3. Estruture seu código em métodos por responsabilidade

# Desafio
O projeto ficou muito bem especificado pelo professor, contudo traduzi todos os<br>
passos para um diagrama de blocos para facilitar a visualização.<br>

![Alt text](/src/resources/MultiplayerBingo0.png "Diagrama de Blocos")<br>

Neste módulo ainda havíamos aprendido POO, deixando o código em apenas uma classe, porém<br>
utilizei Enum para facilitar a mensagem de entrada de dados, métodos e os princípios de<br>
Clean Code.<br>

# Funcionalidades
As informações são guardadas em memória, as entradas são realizadas pela classe Scanner,<br>
as validações de duplicidade são tratadas e as excessões verificadas por Try-Catch.<br>

Cada jogador participa com apenas uma cartela com 5 dezenas e a entrada de dados pode<br>
ser realizada em bloco com a separação dos nomes ou dezenas por "-".<br>

![Alt text](/src/resources/MultiplayerBingo1.png "Tela principal do programa")<br>

Para a impressão da tela de sorteio, optei por usar 4 colunas para distribuir melhor as cartelas<br>
e no relatório final usei 3 colunas;

![Alt text](/src/resources/MultiplayerBingo3.png "Tela principal do programa")<br>

![Alt text](/src/resources/MultiplayerBingo5.png "Tela principal do programa")<br>


# Conclusão
Este projeto foi divertido, mas muito trabalhoso, porque o projeto é bem completo e<br>
a satisfação de ver tudo rodando corretamente foi incrível!<br>

Com certeza, este cógido poderá ser refatorado e otimizado com a evolução<br>
do conhecimento ao longo do programa de formação. Esta é a beleza da nossa<br>
área<br>

Espero que este projeto possa inspirar outros DEVs iniciantes com eu.<br>
