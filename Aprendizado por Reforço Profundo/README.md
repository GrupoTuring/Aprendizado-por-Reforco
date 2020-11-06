# 🧠 Aprendizado por Reforço Profundo

## [Deep Q-Learning](Deep%20Q-Learning)

Um dos algoritmos mais comuns em aprendizado por reforço, quando se trata de aprendizado profundo, é o **Deep Q-Learning**, ou DQN na forma abreviada. DQN é a versão profunda do algoritmo clássico de Q-Learning, em que agora utilizamos uma rede neural que recebe nosso estado e devolve os Q-Valores para cada possível ação do nosso agente.

DQN's são alternativas muito boas ao Q-Learning quando precisamos lidar com problemas que contém diversos estados, tornando a computação mais leve e o aprendizado mais eficaz.


## [Policy Gradient](Policy%20Gradient)

Quase todos os métodos vistos anteriormente ([métodos tabulares](../Aprendizado%20por%20Reforço$20Clássico) e [DQN](#Deep%20Q-Learning)) estimam a função de valor ótima _Q_\*(_s_,_a_) e, a partir de de _Q_\*, obtém uma política (&epsilon;-)gulosa. Os métodos de policy gradient tem uma proposta alternativa: eles estimam diretamente a política ótima.
