</head>
<body>
  <h1>Projeto de Aplicação de Aprendizado de Máquina para a Companhia de Seguros Proteja Seu Amanhã</h1>

  <h2>Objetivo</h2>
  <p>O objetivo deste projeto é avaliar a possibilidade de aplicar técnicas de aprendizado de máquina para resolver algumas tarefas na companhia de seguros Proteja Seu Amanhã. As tarefas a serem abordadas são as seguintes:</p>
  <ol>
    <li>Encontrar clientes semelhantes a um determinado cliente, visando auxiliar os agentes da empresa nas tarefas de marketing.</li>
    <li>Predizer se um novo cliente provavelmente receberá um pagamento de seguro, comparando a eficácia de um modelo de predição com um modelo dummy.</li>
    <li>Predizer o número de pagamentos de seguro que um novo cliente provavelmente receberá utilizando um modelo de regressão linear.</li>
    <li>Proteger os dados pessoais dos clientes, aplicando um algoritmo de mascaramento de dados ou ofuscação de dados, a fim de dificultar a recuperação de informações pessoais por parte de terceiros, sem comprometer a qualidade dos modelos de aprendizado de máquina.</li>
  </ol>

  <h2>Instruções do Projeto</h2>
  <ol>
    <li>Carregar os dados do arquivo "/datasets/insurance_us.csv".</li>
    <li>Verificar se os dados estão livres de problemas, como dados ausentes, valores extremos, entre outros.</li>
    <li>Trabalhar em cada tarefa proposta e responder às perguntas apresentadas no modelo do projeto.</li>
    <li>Tirar conclusões com base na experiência adquirida durante o projeto.</li>
  </ol>

  <h2>Descrição dos Dados</h2>
  <p>O conjunto de dados está armazenado no arquivo "insurance_us.csv" e contém as seguintes características:</p>
  <ul>
    <li>Gênero (gender)</li>
    <li>Idade (age)</li>
    <li>Salário (income)</li>
    <li>Número de familiares (family_members)</li>
    <li>Número de pagamentos de seguro recebidos nos últimos cinco anos (insurance_benefits)</li>
  </ul>

  <h2>Bibliotecas Utilizadas</h2>
  <ul>
    <li>numpy</li>
    <li>pandas</li>
    <li>seaborn</li>
    <li>scikit-learn (sklearn)</li>
    <li>LinearRegression (sklearn.linear_model)</li>
    <li>metrics (sklearn.metrics)</li>
    <li>NearestNeighbors (sklearn.neighbors)</li>
    <li>StandardScaler (sklearn.preprocessing)</li>
    <li>train_test_split (sklearn.model_selection)</li>
    <li>math (biblioteca padrão do Python)</li>
  </ul>
</body>
</html>
