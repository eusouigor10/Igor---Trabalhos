# Trabalho de Física - 1º bimestre - Igor Gabriel Daré Grubisich


## Descrição do trabalho: 
   O trabalho de física do primeiro bimestre se define em escolher um exercício do livro base da matéria, resolvê-lo e programá-lo, generalizando todas as situações possíveis as quais o exercício não contempla. No meu caso, escolhi o exercício 8 do capítulo 5 e fiz uma abstração da matéria do capítulo. A interface programada disponibiliza o cálculo de algumas resultantes a partir da entrada de uma determinada quantidade de forças (*int*), de uma determinada massa para um corpo (*double*) e das forças nos eixos x e y (*int*), numericamente proporcionais à primeira variável inserida. A cada nova iteração de inserção de força, uma variável ao lado do **F** (indicativo de força) aumenta de acordo com o índice da força a ser inserida, com o intuito de direcionar o usuário e para sua melhor organização. Além disso, para auxiliar também nesses quesitos citados, todas as forças já inseridas são visualmente registradas logo abaixo. Todas as verificações de possíveis erros de entrada ocorrem, com o aparecimento de uma janela indicando o erro que possivelmente aconteça.

   As resultantes calculadas são, da primeira até a última, força resultante em cada eixo, força resultante dos eixos, aceleração resultante do corpo, ângulo de saída do corpo e o quadrante do círculo trigonométrico, demonstrando a direção e o sentido da saída. Para a força resultante nos eixos, foi usada uma simples soma dos elementos dos vetores que contém x e y. Já para a resultante entre esses vetores, foi usado o Teorema de Pitágoras. Na aceleração resultante, a Segunda Lei de Newton se fez presente por meio da fórmula *F = m * a*. Por fim, para o ângulo e o quadrante de saída, utilizei respectivamente a arctangente com os dados calculados e uma simples lógica de entendimento dos quadrantes. Para finalizar o programa e reiniciá-lo, há o botão *reset* em vermelho.

   
## Imagens da interface:
![Captura de tela 2025-05-12 214550](https://github.com/user-attachments/assets/99069d67-c25d-4231-bd96-249776b1ba80)
![Captura de tela 2025-05-12 214638](https://github.com/user-attachments/assets/8bc3dcac-b316-4b32-abe4-b5b2f21152ce)
![Captura de tela 2025-05-12 214656](https://github.com/user-attachments/assets/bc088267-facc-4810-a65e-5e8f305e862b)


