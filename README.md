# Livraria
Tema do trabalho de Engenharia de Software II

- Título: 
	Livraria
- Descrição do projeto: 
		A livraria tem como objetivo criar um sistema, que consulte e cadastre 
	cada livro, revista, CD's, DVD's, jogos, funcionários, clientes, editora, transportadoras e 
	vendedores.
		Um sistema que gerencie a venda e reserva de cada produto,
	gere relatórios sobre total de vendas, contas a receber, estoque de livros, 
	promoções para clientes fiés e aniversáriantes. Consulta de disponibilidade no estoque, 
	preços e previsão de chegada de cada produto.
	

- NOMES:			R.A.:
	Matheus Pitta - 		1840481622036
	Victor Galeano - 		1840481422038
-----------------------------
- Trabalhadores de negócio:
		Funcionários, é realizado um breve cadastro de cada funcionário, apenas
	na primeira vez em que acessar o sistema com nome, telefone, e um código único
	interno, cada funcionário poderá cadastrar livros e realizar a venda do mesmo.
	Vendedor (editoras/ gravadoras), que fornece os produtos para a loja.
	
- Atores: 
		Clientes - Fornecedor - Funcionário - Computador externo. 

- Dados descritivos do negócio:					
		A livraria é uma média empresa, que tem sua sede física e um site
	na internet, conforta muito bem seus clientes, com uma area para uma breve leitura 
	de livros, com capacidade total de até 30 pessoas. Possui produtos para todas as faixas 
	etárias. Tem como uma de suas políticas de negócio a fidelização do cliente, oferencendo
	melhorias e vantagens aos mais fiéis. Possui alas em cada andar separando os produtos por categoria(os mais vendidos,
	infantil, lançamentos, video games, didádicos[humanas, exatas e biológicas], religião, pets, esportes, biografias, HQs, 
	filosofia, dicionários, humor, literatura nacional e internacional). 

	

- Principal atividade do negócio:
	Realizar o cadastro de produtos organizadas por categorias, registrar a venda dos mesmos, gerar relatórios financeiros e de 
	estoque. Consultar disponibilidade, preço, previsão de chegada dos itens vendidos. Calcular descontos de acordo com a promoção


- ASTAH pegar uma atividade e detalhar ela: Ex. compra de livro.	*************


- REGRAS DE NEGÓCIO:

  RN01 -	Categoria de produtos
	Existem várias categorias de produtos: Cds, Dvds, jogos, livros, revistas.
	são organizados por alas fisicas.
  
  RN02 - 	Promoções de Lançamento
	Realizar uma promoção de lançamento para novos produtos que chegarem a loja.

  RN03 - 	Cadastrar Cliente
	Cada cliente deve ser previamente cadastrado pelo funcionário da loja. Deverá informar os seguintes dados:
	(Nome completo, cpf, endereço, telefone, email, data de nascimento,para promoções do aniversáriante do mês além de
	Autorizar ou não o recebimento de notificações sobre lançamentos (de 
	acordo com a preferência) via email.

  RN04 - 	Promoção de fidelidade
	Para cada compra realizada é creditado pontos acumulativos com validade
	de um ano ao cadastro do cliente, que poderão ser trocados por descontos ou brindes.

  RN05 - 	Sistema de busca de produtos
	Haverá um sitema de busca, também dísponivel para os clientes em um computador na loja, que consulte preços, 
	disponibilidade no estoque, previsão de chegada de cada produto da loja e simule potenciais descontos de acordo com os pontos acumulados pelo cliente.


  RN06 - 	Reserva de produtos
	O cliente poderá reservar produtos que ainda não chegaram á loja. Pelo 
	sistema disponibilizado na loja ou no site.
