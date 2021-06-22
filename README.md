# Aprendizagem por Reforço para o jogo PacMan

Acadêmica: Lara Popov Zambiasi Bazzi Oberderfer, 2021

Trabalho apresentado para a disciplina de Aprendizado de Máquina, Doutorado de Engenharia de Automação e Sistemas (UFSC)

Implementação do agente pac-man a partir do material disponível em https://inst.eecs.berkeley.edu/~cs188/sp20/project3/

## Aprendizagem por Reforço

O Reinforcement Learning (Q-Learning) é um algoritmo na qual a ideia é o aprendizado de como o agente deve se comportar e como deve mapear suas situações para suas ações, para melhorar as suas recompensas.

O agente inicia não sabendo que ações deve tomar mas necessita encontrar que ações vão encontrar melhores recompensas. Dessa forma, esse agente é passado por um treinamento interagindo com um ambiente e descobrindo os melhores caminhos para alcançar esse objetivo.

Diferente de escolher o melhor resultado visualizando as escolhas de curto prazo, o Q-Learning realiza escolhas levando em consideração as recompensas a longo prazo. O objetivo deste treinamento com Q-Learning é encontrar os passos de ações que maximizam a soma de reforços futuros, para o caminho mais curto do início do jogo até o objetivo final.

No trabalho, o agente foi o Pacman, o ambiente foi o labirinto, passou por 2000 treinamentos, seu objetivo foi terminar o jogo com a maior recompensa possível, sem ser “pego” pelo fantasma.

Esta fase é dividida em duas partes: Treinamento, na qual o pacman irá começar a aprender os valores de posições e as ações. Leva muito tempo para aprender os valores precisos, mesmo para esse labirinto pequeno, então o framework realiza essa fase em modo silencioso, sem apresentar o console. E Teste, na qual, desabilita o Q-learning e a exploração (turning off epsilon and alpha) e utilize sua política aprendida. Os jogos teste são mostrados no console ao final.

## Resultados

Os resultados se encontram no relatório em anexo.

-------------------------------------------------------------------------------------------------
#### Autora
- Professora Lara Popov Zambiasi Bazzi Oberderfer
- Docente de Informática - Câmpus Chapecó
- Acadêmica do Doutorado de Automação e Sistemas da UFSC 2021  
- Instituto Federal de Santa Catarina - Câmpus Chapecó
- IFSC: http://www.chapeco.ifsc.edu.br
-------------------------------------------------------------------------------------------------
