<p align="center">
    <img src="https://camo.githubusercontent.com/d25397e9df01fe7882dcc1cbc96bdf052ffd7d0c/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f676f6c64656e2d77696e642f626f6f7463616d702d676f737461636b2f6865616465722d6465736166696f732e706e67" alt="NLW" />
</p>
<p align="center">
    <a href="https://github.com/fajzanetti">
        <img src="https://img.shields.io/badge/GitHub-fajzanetti-34CB79?logo=GitHub"/>
    </a>
    <a href="https://www.linkedin.com/in/felipezanetti/">
        <img src="https://img.shields.io/badge/Linkedin-felipezanetti-34CB79?logo=linkedin"/>
    </a>
    <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/fajzanetti/desafio-database-upload?color=34CB79" />
    <img alt="GitHub language top" src="https://img.shields.io/github/languages/top/fajzanetti/desafio-database-upload?color=34CB79" />
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/fajzanetti/desafio-database-upload?color=34CB79" />
    <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/fajzanetti/desafio-database-upload?color=34CB79" />
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/fajzanetti/desafio-database-upload?color=34CB79" />
    <img alt="Nota Rocketseat" src="https://img.shields.io/badge/Nota-10-34CB79" />
    <img alt="Data de entrega" src="https://img.shields.io/badge/Data%20de%20entrega-28%2F06%2F2020-34CB79" />
</p>
<p align="center">
  <a href="#-Sobre-o-desafio">🚀 Sobre o desafio</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-Projeto">🚧 Projeto</a>
</p>

# 🚀 Sobre o desafio

Nesse desafio, você deve continuar desenvolvendo a aplicação de gestão de transações, treinando o que você aprendeu até agora no Node.js junto ao TypeScript, mas dessa vez incluindo o uso de banco de dados com o TypeORM e envio de arquivos com o Multer!

Essa será uma aplicação que deve armazenar transações financeiras de entrada e saída e permitir o cadastro e a listagem dessas transações, além de permitir a criação de novos registros no banco de dados a partir do envio de um arquivo csv.

# 🚧 Projeto
<div align="center">
    <p align="left">Utilizando insomnia para ter uma resposta visual:</br></br></p>
    <p align="left">⚪ Arquivo <strong>CSV</strong>.</p>
    <p align="left">🟣 Requisição GET.</p>
    <p align="left">🟢 Requisição POST.</p>
    <p align="left">🔴 Requisição DELETE.</br></br></p>
    <p align="left">🟣 Inicialmente é feita uma requisição GET á API, como não ha dados no <strong>Banco de Dados</strong> a lista fica vazia e com o <i>balance</i> zerado. </p>
    <img alt="Get Repos" title="Get Repos" src=".github/01.PNG" />
    <p align="left">🟢 Requisição POST realizada em seguida, fazendo um depósito (<i>income</i>) de <i>value</i> 3000.</p>
    <img alt="Get Repos" title="Get Repos" src=".github/02.PNG" />
    <p align="left">🟢 Requisição POST realizada em seguida, fazendo uma operação de pagamento exemplo de uma televisão, (<i>outcome</i>) de <i>value</i> 1890.90.</p>
    <img alt="Get Repos" title="Get Repos" src=".github/03.PNG" />
    <p align="left">🟣 Requisição GET mostrando todas <i>transactions</i> cadastradas, ja realizando o <i>balance</i>.</p>
    <img alt="Get Repos" title="Get Repos" src=".github/04.PNG" />
    <p align="left">⚪ Arquivo <strong>import_template.csv</strong>, utilizado para exemplo, na próxima figura.</p>
    <img alt="Get Repos" title="Get Repos" src=".github/CSV.PNG" />
    <p align="left">🟢 Requisição POST fazendo a importação do arquivo .csv acima.</p>
    <img alt="Get Repos" title="Get Repos" src=".github/05.PNG" />
    <p align="left">🟣 Requisição GET mostrando todas <i>transactions</i> cadastradas, ja realizando o <i>balance</i> e com a importação do arquivo .csv.<br>🔴 ID em destaque selecionado apenas para exemplificar a rota DELETE.</p>
    <img alt="Get Repos" title="Get Repos" src=".github/06.PNG" />
    <p align="left">🔴 Requisição DELETE.</p>
    <img alt="Get Repos" title="Get Repos" src=".github/07.PNG" />
    <p align="left">🟣 Requisição GET, fazendo a ultima listagem para mostra como ficou depois de todas as requisições.</p>
    <img alt="Get Repos" title="Get Repos" src=".github/08.PNG" />
</div>

---

Desenvolvido com 💚 por [Felipe Zanetti!](https://www.linkedin.com/in/felipezanetti/)
