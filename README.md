# Explorando evolução de código

Neste exercício, iremos explorar a evolução de código em sistemas reais.

Iremos utilizar a ferramenta [GitEvo](https://github.com/andrehora/gitevo).
Essa ferramenta analisa a evolução de código em repositórios Git nas seguintes linguagens: Python, JavaScript, TypeScript e Java.

Você deve submeter via Moodle apenas o link do seu `fork`, conforme descrito abaixo.

# Passo 1: Selecionar repositório a ser analisado

Selecione um repositório relevante na linguagem de sua preferência (Python, JavaScript, TypeScript ou Java).
Você pode encontrar projetos interessantes nos links abaixo:

- Python: https://github.com/topics/python?l=python
- JavaScript: https://github.com/topics/javascript?l=javascript
- TypeScript: https://github.com/topics/typescript?l=typescript
- Java: https://github.com/topics/java?l=java

# Passo 2: Instalar e rodar a ferramenta GitEvo

Instale a ferramenta [GitEvo](https://github.com/andrehora/gitevo) com o comando:

```
pip install gitevo
```

Rode a ferramenta no repositório selecionado através do seguinte comando (dependendo da linguagem do projeto que escolheu):

```shell
# Python
$ gitevo -r python <git_url>

# JavaScript
$ gitevo -r js <git_url>

# TypeScript
$ gitevo -r ts <git_url>

# Java
$ gitevo -r java <git_url>
```

Onde `<git_url>` é URL do repositório a ser analisado.
Por exemplo, para analisar o projeto Flask escrito em Python:

```
$ gitevo -r python https://github.com/pallets/flask
```

# Passo 3: Explorar os gráficos de evolução de código (`index.html`)

Ao rodar a ferramenta [GitEvo](https://github.com/andrehora/gitevo), o arquivo `index.html` é gerado com diversos gráficos de evolução de código.

Abra o arquivo `index.html` e observe com atenção os gráficos gerados.

# Passo 4: Explicar um gráfico de evolução de código

Selecione um dos gráficos de evolução e explique-o com suas palavras.
Por exemplo, você pode:

- Detalhar a evolução ao longo do tempo, 
- Detalhar se as curvas estão de acordo com boas práticas,
- Explicar grandes alterações nas curvas,
- Explorar a documentação do repositório em busca de explicações para grandes alterações
- Etc.

Seja criativo!

# Exercício

Para responder este exercício, primeiramente, você deve fazer um `fork` deste repositório.
No Moodle, você deve submeter apenas a URL do seu `fork`.

Em seguida, adicione o arquivo gerado `index.html` no seu fork.

Por fim, responda as questões abaixo no seu `fork`: 

1. Repositório selecionado: https://github.com/home-assistant/core

2. Gráfico selecionado: Production and test files
  
3. Explicação: uivos de testes, já que, colocando que em 2020 a empresa possuía em torno de 3000 arquivos de produção e 1000 arquivos de teste, o que mostra que os arquivos de teste representam ¼ do total de arquivos, conclui-se que ela buscou aumentar o número de arquivos de teste sobre o número de arquivos de produção. Isso se evidencia quando verificamos que em 2025 ela possui em torno de 9000 arquivos de produção e 4500 arquivos de teste, o que demonstra que os arquivos de teste representam ⅓ do total de arquivos. 
Assim, acredito que a empresa tem buscado seguir boas práticas de engenharia de software, já que, não só manteve a criação de arquivos de teste ao longo dos anos, como também aumentou o número significativamente de arquivos de teste em 2025 quando comparado com 2025.
Por fim, vale ressaltar que ao verificar os commits feitos é fácil encontrar commits que envolvem arquivos de produção e teste, como os apresentados abaixo, o que comprova o compromisso dos desenvolvedores com os testes.
- https://github.com/home-assistant/core/commit/fb94f8ea189cb18e2b11c5166687e2b9ebb4bd60#diff-71bc54802b4d50c9b781d3102332098ddc5ca47e6da4398664ecb3fa5e661433
- https://github.com/home-assistant/core/commit/9732b8c0dd3b6ff85ad2a953eef1884dd0be5393
- https://github.com/home-assistant/core/commit/923300f4e7733a18100965407de1d7e96bf46381




