## 1. MLP
### A. Perceptron
- 다수의 input을 입력 받아 하나의 output을 출력한다.
- 아래 그림에서 원을 뉴런 또는 노드라고 말한다. 
<figure>
    <img src="https://github.com/msjeong97/tensorflow-practice/blob/main/perceptron.jpeg" alt="perceptron">
</figure>
- input이 뉴런에 전해질 때 weight가 곱해진다. 
- input과 weight의 곱과 bias의 합이 activation function을 거쳐 출력 된다. 

### B. Multi Layer Perceptron
- neural netowrk model 중 하나.
- perceptron으로 AND, OR, NAND 게이트는 구현이 가능하다. 하지만 XOR은 단일 perceptron으로 구현할 수 없다.
- 단일 perceptron은 선형적으로 공간을 나누기 때문이다. 
- 비선형식으로 공간을 나누기 위해 perceptron 여러개를 결합 한다.
<figure>
    <img src="https://github.com/msjeong97/tensorflow-practice/blob/main/mlp.jpeg" alt="multi layer perceptron">
</figure>
- 다층으로 perceptron을 쌓아 로직을 구성하면 복잡한 로직도 처리할 수 있다.
- input에 대한 output을 가장 잘 예측하는 weights를 찾는 것 이 목표.
- 학습셋으로 output의 error를 구하고, error가 줄어들도록 weights를 update하는 backpropagation을 반복.

## 2. Tensorflow
- neural network model을 코드로 구성하기 위해 사용할 framework
