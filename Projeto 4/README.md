# Projeto 4

## Introdução
Para essa implmentação foi requisitado que o NAO identificasse, algum obstáculo a sua frente, estando essa obstáculo a sua frente, a sua direita ou a sua esquerda, depois de localizado a direção que se encontra o seu obstáculo. o NAO usando a sua função fala indicaria a presença de obstaculos a sua frente.

## Ideia
Para a realização dessa interação foi necessário a utilização correta dos sensores disposto na parte frontal do NAO.
![sensor nao frontal](https://github.com/lara-unb/Fundamentos_Robotica_Grupo2_NAO_Coreograph/assets/139188097/00643598-2ac1-4940-aa5a-9439dea3fc4b)
Cada sensor localiza o objeto a frente, se o objeto estiver frontalmente ao Robo, o sensor frontal indicara a presença de algo, se os demais sensores forem ativados o sensor da esquerda ou o sensor da direita estará ativado, 

## Implementação
Nessa implemntação o diagrama de blocos de porgramação usados foram os Utilizados na imagem abaixo 
![Diagrama de Blocos interação 4 Nao](https://github.com/lara-unb/Fundamentos_Robotica_Grupo2_NAO_Coreograph/assets/139188097/de7caac0-8e93-4faa-aeb6-3a4fb7e06627)
Idetificado os parametros  do sonar(alcance de detecção) foi realizado o conexão do bloco sonar com o bloco say(fala),para depois da detecção do obstáculo pelo sonar o NAO indicaria presença do mesmo, falando pelo comando say se o obstáculo está a sua frente, ou a direita, ou a esquerda.
## Conclusão
 A interação Reconhecimento de Obstáculos se mostrou satisfatória, tendo o NAO realizado  a mesma com exito, pois os comandos solicitados foram devidamente assertivos na realização da ação.
## Vídeo
[Clique aqui para assistir o vídeo](https://www.youtube.com/)
