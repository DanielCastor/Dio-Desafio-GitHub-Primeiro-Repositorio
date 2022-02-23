# Estrutura de Dados

é o ramo da computação que estuda os diversos mecanismos de organização de **dados** para atender aos diferentes requisitos de processamento. As **estruturas de dados** definem a organização, métodos de acesso e opções de processamento para a informação manipulada pelo programa.



#### Principais Estruturas de Dados

1. Vetores e Matrizes: são coleções de variáveis contínuas na memória e acessadas através de um número de índice. A diferença entre **vetores e matrizes** é que **vetores** são de uma única dimensão, enquanto **matrizes** podem conter várias dimensões.

	funcao inicio()
	{
		inteiro contador=0
		cadeia contatos[][] = {{"João","São Paulo","(11) 9999-5241"},{"Maria","Ribeirão Preto","(16) 9999-8596"},{"Ana","Manaus","(92) 9999-8574"}}
	
		faca {
	
			escreva ("Nome: " + contatos[contador][0] + " Cidade: " + contatos[contador][1] + " Telefone: " + contatos[contador][2] + "\n")
			contador ++
		}enquanto(contador<=2)
		
	}
2. Registro: Armazena dados diferentes. É um valor que contém outros valores, tipicamente em número fixo e sequência e normalmente indexados por nomes.

3. Listas: é uma estrutura de dados abstrata que implementa uma coleção ordenada de valores, onde o mesmo valor pode ocorrer mais de uma vez. Uma instância de uma **lista** é uma representação computacional do conceito matemático de uma sequência finita.

4. Pilhas: Se trata de uma coleção de elementos onde se acessa apenas 1 item por vez. Estruturas do tipo LIFO (UEPS - Último a entrar, primeiro a sair) ou FIFO (PEPS - Primeiro a entra, primeiro a sair)

5. Filas: são estruturas de dados bastante utilizadas na computação, onde o primeiro elemento a ser inserido, será também o primeiro a ser retirado. Desta forma, serão adicionados elementos no fim e removê-los pelo início.

6. Árvore: é uma estrutura de dados que herda as características das topologias em **árvore**. Conceptualmente diferente das listas encadeadas, em que os dados se encontram numa sequência, nas **árvores** os dados estão dispostos de forma hierárquica.

7. Tabela Hash: é uma estrutura de dados especial, que associa chaves de pesquisa a valores. Seu objetivo é, a partir de uma chave simples, fazer uma busca rápida e obter o valor desejado.

8. Grafo: é uma coleção de vértices e uma coleção de arcos constituídos por pares de vértices. É uma estrutura usada para representar um modelo em que existem relações entre os objetos de uma certa coleção.





