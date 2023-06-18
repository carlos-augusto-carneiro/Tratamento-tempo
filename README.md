# Tratamento tempo

Na tabela tempo.csv podemos observar algums problemas que precisão passar por um tratamento.
<img src="imagens/image.png"/>

# Coluna Aparencia
Inicialemnte comecei importando a tabela e salvando ela na variavel dataset. Logo em seguinda usei dataset.head() para vizualizar a tabela.
<img src="imagens/image-1.png"/>
Logo após iniciei o tratamento pela coluna Aparencia. Usei as funçoes groupby() e a size() para agrupar os resultados da coluna e a quantiade. Pode notar que a estava com um resultado diferente que seria o resultado menos.
<img src="imagens/image-2.png"/>
Então tive que colocar esse resultado em sol.
<img src="imagens/image-3.png"/>
Mais a frente do processo percebi que existia valores númericos salvos na coluna, então iniciei a alteração para o valor sol.
<img src="imagens/image-9.png"/>

# Coluna Umidade
Na coluna umidade percebi que usando a função groupby() e size() que existia um valor acima de 130, excedia o valor pedido.
<img src="imagens/image-4.png"/>
Também usei a função boxplot da biblioteca statistics para pdoer ver a mediana e os quartis.
<img src="imagens/image-5.png"/>
Então usei a função loc para poder ver o valor que passava de 130. Em seguida calculei a mediana e usei a função loc novamente para poder definir o novo valor.
<img src="imagens/image-6.png"/>

# Coluna Temperatura
Para a coluna fiz os mesmos procedimentos. Verifiquei se tinha algum valor fora do padrão e usei a função loc para definir o valor de acordo com a mediana
<img src="imagens/image-7.png"/>
Depois analisei de novo a tabela e pode ver que o existia um valor null. Então calculei a mediana e definir o novo valor como a mediana.
<img src="imagens/image-8.png"/>

# Coluna Vento
Na coluna vento a percebi que o erro era que existia números nas colunas, apos isso iniciei o tratamento para substituir os valores.
<img src="imagens/image-10.png"/>

# Coluna Jogar
E na coluna jogar as unicas alterações foram os numeros para sim.
<img src="imagens/image-11.png"/>