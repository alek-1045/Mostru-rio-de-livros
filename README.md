Mostruário de livros simples em C#

# TESTE FOA

## Erros encontrados

1. Erro...

	o Programa não localizava o AddRazorPages que adiciona serviços para páginas ao IServiceCollection especificado. Em starput as linhas 35 e 36 foi desmarcada.

2. Erro...

	Em views na parte de layout estava sendo escondido pela função hidden inserida na linha 34.

3. Erro...

	Após testar as funções dos autores foi percebido que na pasta models/authores as datas quando inserido sempre adicionava uma dia extra usando, a função addDays(1).		

4. Erro...

	Após isso foi testado a pasta de livros (books) onde os id novos inseridos não estavam aparecendo,
tanto em create e no edit. As linhas 34, 60, 78, 95 e 131 foram alteradas para ser inserido o nome. Além de estarem duplicadas.

5. Erro...
	
	O próximo erro na models/book que após ser criado ou editado um livro 
as informaçoes titulos, publisher, ISBN e Date apareciam erradas pois estavam todas privadas.

6. Erro...

O nós controllerrs do Books os create e edit estavam sem o title que mostra os títulos adicionados.

7. Erro...
	
	Por fim ainda nos controllers dos books as linhas 160 e 161 estavam alteradas, 
 fazendo assim que o comando de deletar livro não funcione corretamente. 
	
## Itens Bonus Completados
 Nenhum item bonus completado
