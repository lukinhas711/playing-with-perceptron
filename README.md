# playing-with-perceptron

## English

a simple neural network which aims to make the decision to go to an Iron Maiden show, based on three simple factors: `i1 = do I have money?, i2 = do i have friends to go to?, i3 = do I have locomotion?` these conditions will have their own weights to balance the decision making, I'll call the weight `w`. The neuron will make an account by multiplying the w1 with the i1 + w2 * i2 + w3 + i3 + bias (some bias so as not to let the result be purely mathematical), then we will check if the result of this algorithm was >= a threshold ( yes) or if it is < than the threshold (no)

## Português BR

Uma rede neural simples, que visa tomar a decisão de ir a um show do Iron Maiden com base em três fatores simples: `i1 = eu tenho dinheiro?, i2 = eu tenho amigos para ir?, i3 = eu tenho locomoção?` essas condições terão pesos próprios para balancear a tomada de decisão, vou chamar o peso de `w`. O neurônio vai fazer uma conta multiplicando o w1 pelo i1 + w2 * i2 + w3 + i3 + o viés (alguns víes para não deixe o resultado ser puramente matemático) então vamos verificar se o resultado deste algoritmo foi >= ao limiar (sim) ou se é < que o limiar (não)

![image](https://user-images.githubusercontent.com/49355209/215239808-92322cdf-a1f2-453c-83f4-b32e00a32f38.png)
