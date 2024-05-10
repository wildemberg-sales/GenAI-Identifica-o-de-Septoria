# GenAI-Identifica-o-de-Septoria
O código contido neste repositório destina-se a utilizar o GenAI para identificação da doença septoria em folhas de tomateiro a partir de um breve treinamento do modelo, e a utilização de novas imagens que o usuário envia.

## Lógica Implementada:
Utilizo um pequeno treinamento do modelo com Few-shot prompting, fornecendo imagens de folhas de tomate com septoria e sem septoria, e seus respectivos rótulos, para que o modelo já tenha uma base do que irei querer como resposta.

Após o treinamento, abro o espaço para que o usuário forneça uma imagem de uma folha de tomate, e deixo a IA pensar e responder, logo em seguida, ela já guarda essa imagem e o rótulo dela no dataset para aumentar seu conhecimento.

**OBS**: Esse modelo foi desenvolvido somente para utilização de identificação da doença septoria, ou de uma folha saudável, ou seja, caso haja alguma outra doença ou imagem, o modelo pode não funcionar corretamente

## Como Usar
* Copie as imagens da pasta dataset disponibilizadas neste repositório, e cole elas abaixo da pasta sample_data do colab.
* Após isso pode executar os códigos do arquivo e subir suas imagens.
