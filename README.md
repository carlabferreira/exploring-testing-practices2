# Explorando Práticas de Teste

Neste exercício, vamos explorar práticas de teste em sistemas reais utilizando a ferramenta [TestMiner](https://andrehora.github.io/testminer).

O TestMiner permite visualizar e analisar testes de software em repositórios do GitHub, fornecendo dados sobre como os projetos organizam seus testes, como eles evoluem entre versões e quais bibliotecas de teste são utilizadas.
Explore a ferramenta antes de começar para se familiarizar com seu funcionamento.

Mais detalhes no GitHub da ferramenta: https://github.com/andrehora/testminer.

---

## Passo 1: Selecionar DOIS repositórios

Escolha dois repositórios reais que possuam testes de software.
Abaixo estão alguns links para ajudá-lo a encontrar projetos interessantes:

- Python: https://github.com/topics/python?l=python
- JavaScript: https://github.com/topics/javascript?l=javascript
- TypeScript: https://github.com/topics/typescript?l=typescript
- Java: https://github.com/topics/java?l=java

- Tópicos: [ai](https://andrehora.github.io/testminer/#topic:ai), [llm](https://andrehora.github.io/testminer/#topic:llm), [api](https://andrehora.github.io/testminer/#topic:api), [nodejs](https://andrehora.github.io/testminer/#topic:nodejs), [android](https://andrehora.github.io/testminer/#topic:android)

- Por organização: [Google](https://andrehora.github.io/testminer/#google), [Microsoft](https://andrehora.github.io/testminer/#microsoft), [Apple](https://andrehora.github.io/testminer/#apple), [Facebook](https://andrehora.github.io/testminer/#facebook), [Netflix](https://andrehora.github.io/testminer/#netflix), 
[GitHub](https://andrehora.github.io/testminer/#github), [Apache](https://andrehora.github.io/testminer/#apache), [HuggingFace](https://andrehora.github.io/testminer/#huggingface)

## Passo 2: Explorar os repositórios selecionados

Busque os repositórios escolhidos no [TestMiner](https://andrehora.github.io/testminer) e analise os dados de teste gerados pela ferramenta.

## Passo 3: Explicar as prática de teste

Para cada repositório, escolha uma prática ou dado de teste relevante e explique com suas próprias palavras.

---

## Instruções de entrega

1. Faça um `fork` deste repositório (saiba mais sobre forks [aqui](https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo)).
2. Responda às questões abaixo diretamente neste arquivo `README.md` do seu fork. Pode adicionar imagens para enriquecer sua explicação.
3. No Moodle, submeta apenas a URL do seu fork.

---

## Respostas

### Repositório 1 

Repositório: [https://github.com/huggingface/transformers](https://github.com/huggingface/transformers)

URL TestMiner: [https://andrehora.github.io/testminer/#huggingface/transformers](https://andrehora.github.io/testminer/#huggingface/transformers)

Explicação: 

O crescimento de testes acompanha o crescimento de source, indicando como a medida que o sistema vai crescendo há a necessidade de adicionar mais testes para aquele código novo e como a coleção de testes tem o objetivo de auxiliar na manutenção do código. Na imagem abaixo podemos observar a quantidade de arquivos de testes por versão (3, 645 e 1139) em comparação com a quantidade em source (19, 2473 e 4408), cerca de 1/4 e com o comportamento muito semelhante.


<img width="656" height="364" alt="image" src="https://github.com/user-attachments/assets/823c7f23-333c-4a1e-a4fe-7dcab27e8360" />
<img width="646" height="317" alt="image" src="https://github.com/user-attachments/assets/9d6b360c-288f-4b68-a4cb-c8fdeaa41750" />


Além disso, 97% (1111/1145) dos teste estão localizados no diretório "tests", enquanto o restante está dividido entre docs (com arquivos .md), benchmarks e github workflows, utils e semelhantes, que parecem representar informações auxiliares sobre os testes, como lista de testes disponíveis, relatórios e comparação entre os testes (deduzido pelos nomes dos arquivos).

<img width="628" height="446" alt="image" src="https://github.com/user-attachments/assets/ad9ca0ba-c917-4c3c-86d6-8d0b4916c003" />



### Repositório 2

Repositório: `<URL_DO_REPOSITÓRIO>`

URL TestMiner: `<URL_NO_TESTMINER>`

Explicação: `<SUA_EXPLICAÇÃO>`
