<h1 align="center">Estrutura de código usando: pattern Factory + Princípio Dependency Injection + Testes</h1>
<p><br></p>

**Descrição:** Esta aplicação visa demonstrar o uso do patern Factory + Princípio Dependency Injection + Testes, dentro de uma estrutura de aplicação. Você percebera a fluxo das mensagens entre as UNIDADES DE CÓDIGO. Aqui o importante é viisualizar o aninhamento das Factorys. NÃO HÁ IMPLEMENTAÇÕES dos métodos da aplicação, em seu lugar existe somente a escrita do resultado em console.
<p><br></p>

**Tabela de Conteúdo:**

1. Pré-requisitos e como rodar a aplicação/testes
    1. Pré-requisitos
        1. Ambiente de front-end da aplicação
        1. Ambiente de back-end da aplicação
    1. Como rodar
        1. Passo 01: Instalar dependências
        1. Passo 02: Rodar os testes
    1. Aplicação
        1. Arquivos de desenvolvimento
            1. Local files
            1. Remote files
        1. Arquivos de teste
            1. Local files
            1. Remote files
1. Descrição dos objetivos e comportamentos de cada arquivo
    1. arquivo 01
        1. Descrição dos objetivos
        1. Descrição dos comportamentos
    1. arquivo 02
        1. Descrição dos objetivos
        1. Descrição dos comportamentos
1. Live demonstração da Aplicação
1. Contribuição
1. Badges e Tecnologias utilizadas
1. Créditos
1. Licenças
1. Autor

<p><br></p>

<h2 style="color: #007398">1. Pré-requisitos e como rodar a aplicação/testes</h2><p><br></p>

<h3 style="color: #0667d3">1.1 Pré-requisitos</h3><br>

<h4 style="color: #0090ff">1.1.1 Ambiente de front-end da aplicação</h4><br>

Liguagem: javascript

<h4 style="color: #0090ff">1.1.2 Ambiente de back-end da aplicação</h4><p><br></p>

<h3 style="color: #0667d3">1.2 Como rodar</h3><p><br></p>
<h4 style="color: #0090ff">1.2.1 Passo 01: Instalar dependências</h4><p><br></p>

[Jest](https://jestjs.io/docs/getting-started) - comando de instalação deve ser executado no diretório root da aplicação
```
    npm install --save-dev jest
```


<h4>1.2.2 Passo 02: rodar os testes</h4><p><br></p>

Para rodar os testes, você deve:
    - instalar o modulo jest, conforme mencionado no Passo 01.
    - Adicionar a seguinte seção no arquivo package.json:

```
    {
        "scripts": {
        "test": "jest"
        }
    }
```

>Obs.: Não esqueça de adicionar a vírgula entre seções

No terminal, digite o comando: "npm run test", os testes devem ser executados.


<h3 style="color: #0667d3">1.3 Aplicação:</h3><p><br></p>

<h4 style="color: #0090ff">1.3.1 Arquivos de desenvolvimento:</h4><p><br></p>

 <h5 style="color: #05bfe5">1.3.1.1 Local files</h5><p><br></p>

1. index.js (entrypoint / ponto de entrada)
1. assemblyEdge.js (montador de borda)
1. core.js
1. awebserverLayer.js (abstraction webserver Layer)
1. adLayer.js (abstraction Database Layer)
1. database.js
1. webserver.js

<h5>1.3.1.2 Remote files</h5><p><br></p>

<h4>1.3.2 Arquivos de teste utilizados:</h4><p><br></p>

<h5>1.3.2.1 Local files:</h5><p><br></p>

1. core.test.js

<h5>1.3.2.2 Remote files:</h5><p><br></p>


<h2 style="color: #007398">2. Descrição dos objetivos e comportamentos de cada arquivo</h2><p><br></p>

<h3 style="color: #0667d3">2.1 arquivo 01</h3><p><br></p>

<h4 style="color: #0090ff">2.1.1 Descrição dos objetivos</h4><p><br></p>

<h4 style="color: #0090ff">2.1.2 Descrição dos comportamentos</h4><p><br></p>

<h3 style="color: #0667d3">2.2 arquivo 02</h3><p><br></p>

<h4 style="color: #0090ff">2.2.1 Descrição dos objetivos</h4><p><br></p>

<h4 style="color: #0090ff">2.2.2 Descrição dos comportamentos</h4><p><br></p>


<h2 style="color: #007398">3. Live demonstração da Aplicação</h2><p><br></p>


<h2 style="color: #007398">4. Contribuição</h2><p><br></p>


<h2 style="color: #007398">5. Badges e Tecnologias utilizadas</h2><p><br></p>


<h2 style="color: #007398">6. Créditos</h2><p><br></p>


<h2 style="color: #007398">7. Licenças</h2><p><br></p>

![Licença MIT para Jest](https://img.shields.io/badge/JEST-Licence%20MIT-green)

![Laguage Javascript](https://img.shields.io/badge/Language-Javascript-yellow)

<h2 style="color: #007398">8. Autor</h2><p><br></p>

> Baseado no treinamento "Combinação Extremamente Poderosa Para Qualquer Programador (Factory + Injeção de Dependência)" -- https://www.youtube.com/watch?v=uyOJ2jjBtBs -- Canal: Filipe Deschamps -- Publicação: 11 de mai. De 2020.
<p><br></p>

<h2> Feito com ❤️ por  <a href="https://blog.dominio.com.br/author/ricardo//" title="Programador"><b>Ricardo Martins</b></a> <a href="https://blog.dominio.com.br/author/ricardo//" title="Programador">🚀</a><br> </h2>

<h2> 👋🏽 Entre em contato! 

[![Twitter Badge](https://img.shields.io/badge/-@renachev?style=flat-square&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/tgmarinho)](https://twitter.com/renachev) [![Linkedin Badge](https://img.shields.io/badge/-Ricardo-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/renachev/)](https://www.linkedin.com/in/renachev/) 
[![Gmail Badge](https://img.shields.io/badge/-chev.net@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:chev.net@gmail.com)](mailto:chev.net@gmail.com)

</h2>
