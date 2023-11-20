# Health-Track
Projeto temático desenvolvido durante a graduação: sistema de saúde voltado para a dieta. 
ATIVIDADE: EXIBIR E CADASTRAR INFORMAÇÕES DE UMA LISTAGEM DO HEALTH TRACK, AGORA COM BANCO DE DADOS.

** Faça a classe DAO que você criou acessar o banco de dados, de fato. Ao invés de criar dez objetos “MOCK”, agora o método getAll() deve acessar o banco de dados, realizar um SELECT e receber a consulta, armazenando na mesma coleção de objetos criada anteriormente.
Como os vários passos do acesso ao banco de dados podem ter problemas (tais como o banco estar fora do ar, a tabela ter sido apagada, entre outros), é indispensável realizar o tratamento de exceções.

Crie também um método insert() na classe do tipo DAO, que realize um INSERT e registre uma nova informação. Como você precisa testar o getAll() solicitado acima, utilize seu comando insert() para cadastrar pelo menos cinco novos registros. 
Utilize a própria classe Teste, método main(), para inserir os registros e chamar a consulta.
