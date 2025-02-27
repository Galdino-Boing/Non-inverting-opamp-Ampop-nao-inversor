# Non inverting Op-Amp  
This project explores the versatility of operational amplifiers (Op-Amps) in various configurations, such as non inverting amplifiers, with the goal of studying and applying different signal amplification techniques. Using Op-Amps creatively, the project involves the construction and analysis of amplifier circuits.

# Ampop não Inversor  
Este projeto explora a versatilidade dos amplificadores operacionais (AMPops) em diversas configurações, como amplificadores não inversores, com o objetivo de estudar e aplicar diferentes técnicas de amplificação de sinal. Utilizando AMPops de forma criativa, o projeto envolve a construção e análise de circuitos amplificadores.

# Objetivo  
Alterar a forma da onda de saída, com o propósito de não inverter e amplificar o sinal, utilizando um amplificador operacional em configuração não inversora.

# Utilidade  
Em vez de precisar criar uma fonte de tensão específica, este circuito utiliza um amplificador operacional 741 com três resistores para alterar a organização dos semiciclos do sinal de entrada, ajustando a forma da onda e controlando a tensão de saída.

**Mudança de polaridade e ganho:** Um amplificador operacional não inversor mantém a polaridade do sinal de entrada, amplificando-o sem inverter a fase. Isso é útil em sistemas que requerem amplificação sem alteração de polaridade, como em circuitos de amplificação de sinais fracos. Entre as aplicações práticas, destacam-se:

- Amplificação de Sinal de Áudio
- Amplificação de Sensores e Instrumentos
- Circuitos de Medição de Alta Impedância
- Amplificadores de Instrumentação
- Geradores de Sinal e Osciladores
- Filtros Ativos
- Circuitos de Comparação de Tensão

# Materiais  
O circuito é projetado utilizando três resistores e um amplificador operacional 741, com o objetivo de não inverter e amplificar o sinal de saída de forma eficiente.  

A alimentação do CI 741 é fornecida com +12V na perna 7 e -12V na perna 4. A perna 3 do CI é conectada ao sinal de entrada. Um resistor é conectado a perna 2 do ci e então conectado ao terra. Um resistor é então conectado entre a entrada negativa de sinal (perna 2) e a saída do amplificador operacional (perna 6), estabelecendo o ganho do circuito. Finalmente, outro resistor é conectado da saída (perna 6) ao terra, completando o circuito de feedback e ajustando o comportamento do amplificador não inversor.
