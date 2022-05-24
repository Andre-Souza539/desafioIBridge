# DesafioIByte by André Souza :space_invader:



**DESAFIO PAINEL DE ACOMPANHAMENTO**
	A iBridge atua no fornecimento de Sistemas de Gestão para Centrais de Teleatendimento, dentre os nossos produtos possuímos um Discador Automático para Televendas. Ele funciona no seguinte formato, o cliente faz upload de uma lista de pessoas que deseja localizar, o sistema vai discando e quando alguém atende, ele transfere para o atendente que faz a negociação e fechamento da venda.Os nossos sistemas podem rodar de modo On-premise (instalado no cliente) ou em Nuvem. Neste segundo caso, geralmente rodam em ambientes compartilhados.Diariamente, um sistema exporta as estatísticas de utilização de cada um dos servidores em formato JSON. No link abaixo você vai encontrar uma amostra dos dados de um destes servidores, contendo 8 clientes x 5 dias.



**Link dos dados:** https://www.ibridge.com.br/dados.json
Seu desafio é:



- [ ] Criar um script para carga e armazenamento dos dados disponibilizados;

- [ ] Estruturar um banco de dados para receber estes dados utilizando PHP, Laravel e MySQL;

- [ ] Criar um painel de acompanhamento apresentando os dados, com filtro por data e cliente.
  	

  ## Abaixo uma explicação a respeito dos dados disponibilizados no JSON. 

  

  ![img](https://lh4.googleusercontent.com/-Ppoz3vebbRWca-Qkhjyf7I9_rl9kWMEQJI2mYCznOcue2382yeZqUpsZwvRocedmGPC9xf7CXF_G8i2V3dV3lpzQL4siCzyYqCTUA9zZF0AufKwLcmn2bHNTGNRv3SHT0USKcSogdGgtWbqSQ)

  

  ​	O JSON possui blocos de dados diários, para cada dia, existe um bloco chamado "geral" com dados consolidados (somatórios) e um bloco "clientes" com dados detalhados de cada cliente. Cada bloco de cliente possui os campos data, hora, dados de chamadas (que consiste em cada ligação realizada pelo discador automático) e dados de ocorrências (quando uma pessoa atende a chamada, o sistema transfere automaticamente para um atendente, nessa hora ele tabula/classifica a conversa, gerando uma ocorrência).

  

  

  **Sugestão do Layout**

  

  **![img](https://lh6.googleusercontent.com/q2cB19isfNBL8bhQfde7-pwy6NStQkzXOhNmHh6NHj0LsJYj0RVg5hQaSMxkVVxfALHDP0r13MXLAlQjKkYYOn-zWSM7dHacTx8NNMMEtbXEM3_YbRkZcqYq8iS3ibHxJNrFJfH3F0nWcAhYLQ)**

  

<hr><br>













