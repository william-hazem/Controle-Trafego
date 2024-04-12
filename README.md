# Controle de Tráfego em Cruzamento de Quatro Vias

Este projeto visa desenvolver um sistema de controle de tráfego para um cruzamento de quatro vias utilizando a ferramenta Supremica.

## Objetivos

- Desenvolver um sistema de controle de tráfego eficiente que gerencie o fluxo de veículos e pedestres em um cruzamento de quatro vias, minimizando o tempo de espera e evitando congestionamentos.
- Garantir a segurança de todos os usuários da via, incluindo veículos e pedestres.

## Requisitos

- O sistema deve controlar semáforos para veículos e pedestres em todas as quatro vias.
- Deve haver uma lógica de controle que priorize a segurança e a eficiência, evitando colisões e minimizando o tempo de espera.
- O sistema deve ser capaz de adaptar-se a diferentes fluxos de tráfego, considerando horários de pico.

### Especificações de Controle

- Evitar colisão dos veículos permitindo a travessia em três direções (direita, reto e esquerda), garantindo que apenas um dos sinais abra por vez.
- Evitar a colisão com pedestres, garantindo que os sinais de tráfego para veículos (S1, S2, S3 e S4) estejam simultaneamente fechados durante o tráfego dos pedestres.
- Reduzir o tempo de espera dos pedestres dando prioridade para a sua circulação quando necessário.
- Se detectados veículos de emergência, o sistema precisa conceder-lhes passagem na via em que eles se encontram, interrompendo o ciclo regular de funcionamento dos semáforos caso necessário.

## Equipe

- [Julia Ramalho](https://github.com/ramalhocsjulia)
- [Samara Cardoso](https://github.com/SamaraLimaCardoso)
- [William Henrique](https://github.com/william-hazem)
