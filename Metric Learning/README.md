![image](https://user-images.githubusercontent.com/29411828/211857257-ca1006ac-c5cb-4b54-becc-a19170e37b98.png)

Este exemplo mostra como implementar um modelo de reconhecimento facial utilizando aprendizado de métrica e TensorFlow. O conjunto de dados de rostos de famosos é usado para treinar o modelo e comparar as características do rosto com as do banco de dados. Também inclui a adição de novos rostos ao banco de dados e testando uma outra foto desse último rosto usando máscara facial, para verificar a eficiência da técnica.

![image](https://user-images.githubusercontent.com/29411828/212130187-303849b3-310f-4563-af84-0e947faaa88f.png)

## Pré-requisitos
- Ter uma conta no Google Colaboratory

## Como executar
1. Abra o arquivo `metric_learning.ipynb` no Google Colab
2. Ative a opção de runtime com uso de GPU
3. Execute cada célula do código para treinar e testar o modelo

## Bibliotecas necessárias
- TensorFlow
- NumPy
- OpenCV

## Resultados

Discussão             |  Imagens
:-------------------------:|:-------------------------:
Concluímos a partir de nossas experiências que o modelo é capaz de identificar rostos com precisão e rapidez. Isso é importante para várias aplicações, como reconhecimento facial e busca de pessoas, pois permite que o modelo identifique e localize rapidamente a pessoa desejada. Além disso, o modelo consegue localizar o nome da pessoa que foi identificada mesmo que ela esteja usando uma máscara. Isso é importante em situações onde as pessoas estão usando máscaras devido à pandemia, pois permite que o modelo continue funcionando de maneira eficaz. Em geral, os resultados da nossa pesquisa mostram que o modelo tem um desempenho excelente e pode ser usado para várias aplicações. |  ![image](https://user-images.githubusercontent.com/29411828/212130007-ddd1ceae-6571-4583-8704-b719293686a1.png)![image](https://user-images.githubusercontent.com/29411828/212129904-7a29c935-f019-4f66-9dbf-e73ddf6db145.png)



## Licença
Este exemplo está disponível sob a licença MIT.

![image](https://user-images.githubusercontent.com/29411828/211857370-34460358-6119-49b1-afc3-59b99c6afdc8.png)
