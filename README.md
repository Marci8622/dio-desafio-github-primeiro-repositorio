

dio-desafio-github-primeiro-repositorio

Desafio de Projeto do Git/GitHub
Curso Java da Dio/Cognizant 

**:::Módulo 01 - Lógica de Programação Esssencial**

Nesse módulo foi estudado sobre conceitos de lógica, algoritmos e pseudocódigos, fluxograma (variáveis, constantes e concatenação), estrutura de repetição, desvios condicionais, laços de repetição, matrizes e vetores, utilização do Portugol, com o mentor **Denilson Bonatti**.



***:: Conceitos:***

**Algoritmo -** Sequências de passos que devemos seguir para atingir um propósito.

**Metacognição -** É a capacidade de um ser humano de compreender. Pode ser entendido como a ação de refletir sobre o que se aprendeu. "Pensar como você pensa".

**Abstração -** É a habilidade de concentrar nos aspectos essenciais de um contexto qualquer, ignorando características menos importantes ou acidentais. 

**Pseudocódigo -** É a uma forma genérica de escrever um algoritmo, utilizando uma linguagem simples.

**Fluxograma -** É uma ferramenta utilizada para representar graficamente o algoritmo, isto é, a sequência lógica e coerente do fluxo de dados.

<img src = "img/fluxo.png">

**Diagrama de blocos -** Utilizado para representar o método do fluxograma.

<img src = "img/diagrama.png">

**Variáveis -** Na programação, é um objeto (uma posição, frequentemente localizada na memória) capaz de reter e representar um valor ou  expressão. É um espaço na memória do computador destinado a um dado que é alterado durante a execução do algoritmo. 

**Constantes -** São valores imutáveis e não são alterados durante a vida útil do programa. As variáveis e constantes podem ser classificadas em quatro tipos: Numéricas, caracteres, alfanuméricas ou lógicas.

**Expressões aritméticas -** São expressões que utilizam operadores aritméticos e funções aritméticas envolvendo constantes e variáveis.

**Expressões literais -** São expressões com constantes e/ou variáveis que tem como resultado valores literais. 

**Operadores relacionais -** São expressões compostas por outras expressões ou variáveis numéricas com operadores relacioinais. Elas retornam valores lógicos (verdadeiro/falso).

**Concatenação -** É um termo usado em computação para  designar a operação de unir o conteúdo de duas strings. Agrupamento de duas ou mais células que, incluindo fórmulas, texto ou outras informações contidas no seu interior, dá origem a um único resultado.

**Strings -** É uma sequência de caracteres.

**Estrutura de repetição -** Dentro da lógica de programação é uma estrutura que permite executar mais de uma vez o mesmo comando ou conjunto de comandos, de acordo com uma condição ou com um contador.

**Lógica de programação -** Contextualização coesa de um programa de computador, buscando a melhor sequência de passos (ações) para solução de um problema. É a maneira como se escreve um algoritmo, utilizando uma determinada linguagem, para conclusão de um objetivo. É uma linguagem escrita e formal que específica um conjunto de instruções e regras usadas para gerar programas (software). 

Os tipos de linguagem de programação são: **Alto nível** - Essas são aquelas cuja sintaxe se aproxima mais da nossa linguagem e se distanciam mais da linguagem da máquina; **Baixo nível** - É aquela que se aproxima mais da linguagem de máquina. Essas são as que você precisa ter o conhecimento direto da arquitetura do computador para fazer alguma coisa.

As linguagens de programação podem ser: **Compiladas** - É uma linguagem em que o código fonte é executado diretamente pelo sistema operacional ou pelo processador, após ser traduzido por meio de um processo chamado compilação. Nelas é necessário transformar em um arquivo EXE. Exemplo: C#, Visual Basic, Delphi, C++; **Interpretadas** - É uma linguagem em que o código fonte é executado por um programa de computador chamado interpretador, que em seguida é executado pelo sistema operacional ou processador. Exemplo: PHP e Jarvas Script, Phython.

**Portugol -** É uma pseudolinguagem que permite ao leitor desenvolver algoritmos estruturados em português de forma simples e intuitiva, independentemente de linguagem de programação. Ele permite ao programador pensar no problema em si e não no equipamento que irá executar o algoritmo.

​	**::Utilização do "se"** (Verdadeiro)

		real nota1,nota2,nota3,nota4,media
		cadeia aluno
	
		escreva("Digite o nome do aluno:")
		leia(aluno)
		escreva("Digite a nota 1:")
		leia(nota1)
		escreva("Digite a nota 2:")
		leia(nota2)
		escreva("Digite a nota 3:")
		leia(nota3)
		escreva("Digite a nota 4:")
		leia(nota4)
	
		media = (nota1+nota2+nota3+nota4)/4
	
		escreva("Sua média é: " + media)
		
		"//Verifica se a média é maior ou igual a 7"
		se(media>=7) {
			escreva("\n" + "Parabéns!! Você foi aprovado")
		}


​	**::Utilização do se-senao** (Verdadeiro-Falso)

		real nota1,nota2,nota3,nota4,media
		cadeia aluno
	
		escreva("Digite o nome do aluno:")
		leia(aluno)
		escreva("Digite a nota 1:")
		leia(nota1)
		escreva("Digite a nota 2:")
		leia(nota2)
		escreva("Digite a nota 3:")
		leia(nota3)
		escreva("Digite a nota 4:")
		leia(nota4)
	
		media = (nota1+nota2+nota3+nota4)/4
	
		escreva("Sua média é: " + media)
		
		"//Verifica se a média é maior ou igual a 7"
		se(media>=7) {
			escreva("\n" + "Parabéns!! Você foi aprovado")
		}
		
		"//Caso se a média for menor do que 7"
		senao {
			escreva("\n" + "Infelizmente você foi reprovado")


​	**::Desvio Condicional - Caso**

	{
		escreva("Escolha uma das opções : 1 - Abrir Netflix 2 - Abrir Amazon Prime 3 - Abrir HBO GO 4 - Sair")
		inteiro menu=0
		escreva("\n" + "sua escolha:")
		leia (menu)
	
		escolha (menu)
		{
			caso 1:
			escreva("OK! Abrir Netflix")
			pare
	
			caso 2:
			escreva("OK! Abrir Amazon Prime")
			pare
	
			caso 3:
			escreva("OK! Abrir HBO GO")
	
			caso contrario:
			escreva("\n" + "Você deve escolher as opções 1, 2, 3 ou 4")	


​	**::Laços de Repetição**

	{
	   //Tabuada de acordo com o numero determinado pelo usuario, e ate o limite que o mesmo desejar.
	   //Marciana Oliveira
	   
		inteiro contador,limite,resultado,tabuada
	
		escreva("Digite qual tabuada você quer que seja calculada:")
		leia(tabuada)
	
		escreva("Qual o último limite a ser calculado?:")
		leia(limite)
	
		contador=0
		
		faca{
	
			resultado = tabuada * contador
			escreva(tabuada + " X " + contador + " = " + resultado + "\n")
			contador ++
			
		}enquanto (contador<=limite)


​	**::Vetores** (Matrizes de uma só dimensão)

	{
		cadeia frutas[4]
		inteiro contador = 0
	
		frutas[0] = "Maçã"
		frutas[1] = "Pera"
		frutas[2] = "Uva"
		frutas[3] = "Jaca"
	
		faca{
	
			escreva(frutas[contador] + "\n")
			contador++
			
		}enquanto (contador<=3)


​	**::Matrizes** (Coleção de variáveis de mesmo tipo, acessíveis com um único nome e armazenados contiguamente na memória)

	{
		inteiro contador=0
		cadeia cesta[][]={{"Pera","100"},{"Jaca","200"},{"Maçã","900"},{"Uva", "89"}}
	
		faca{
	
			escreva("Produto: " + cesta[contador][0] + " Quantidade: " + cesta[contador][1] + "\n")
			contador++
		}enquanto(contador<=3)



**:: Exercícios do módulo 01**

01- Resolver os desafios do jogo Minecraft - https://studio.code.org/s/mc/lessons/1/levels/1

02- Resolver o jogo Pinguins numa fria - https://rachacuca.com.br/jogos/pinguins-numa-fria/

03- No flowgorithm concatenar o nome do aluno e a média de notas dos quatro bimestres.

<img src = "img/fluxocont.png">

04-  No portugol determinar o nome do funcionário, o total de suas vendas em quatro meses e sua média.

	{
	real janeiro,fevereiro,marco,abril,total,media
	cadeia funcionario
	
	escreva("Digite o nome do funcionário:")
	leia(funcionario)
	escreva("Digite a venda de janeiro:")
	leia(janeiro)
	escreva("Digite a venda de fevereiro:")
	leia(fevereiro)
	escreva("Digite a venda de março:")
	leia(marco)
	escreva("Digite a venda de abril:")
	leia(abril)
	
	total = (janeiro+fevereiro+marco+abril)
	media = (janeiro+fevereiro+marco+abril)/4
	
	escreva("O funcionário: " + funcionario + " vendeu de janeiro a abril: " + total + " e teve uma média de: " + media)

05- No portugol determinar uma matriz de 3 colunas e 3 linhas, contendo o nome, cidade e telefone.

	{
		inteiro contador=0
		cadeia contato[][]={{"João","São Paulo","(11) 9999-5241"},{"Maria","São Caetano","(16) 9999-8596"},{"Ana","Manaus","(92) 9999-8574"}}
	
		faca{
	
			escreva("Nome: " + contato[contador][0] + " Cidade: " + contato[contador][1] + " Telefone: " + contato[contador][2] + "\n")
			contador++
		}enquanto(contador<=2)




**:::Módulo 02 - Estrutura de Dados e Algoritmos**

Nesse módulo foi estudado sobre o conceito e os tipos de estruturas de dados, com o mentor **Bruno Dias**.



**::Conteitos:**

**Estrutura de dados -** É uma estrutura organizada de dados na memória de um computador ou em qualquer dispositivo de armazenamento, de forma que os dados possam ser utilizados de forma correta. Usando as estruturas adequadas, através de algoritmos, podemos trabalhar com uma grande quantidade de dados, como aplicações em bancos de dados ou serviços de busca. As principais estruturas de dados são: Vetores e Matrizes; Registro; Lista; Pilha; Filha; Árvore; Tabela Hash; Grafos.

**Arrays** - São geralmente descritas como "lista de objetos"; elas são basicamente objetos que contêm múltiplos valores armazenados em uma lista

**Listas -** Estrutura de dados que armazena dados de um determinado tipo em uma ordem específica. A diferença entre listas e arrays é a de que as listas possuem tamanho ajustável, enquanto arrayas possuem tamanho fixo. Existem dois tipos de listas: **Ligadas** (Na estrutura do tipo lista existem os nós onde cada um dos nós conhece o valor que está sendo armazenado em seu interior, além de conhecer o elemento posteriior a ele) e **Duplamente ligadas** (Constituem uma variação das ligadas, sendo que a diferença desta para as ligadas é que elas são bidirecionais).

**Pilha -** É uma estrutura de dados que serve como uma coleção de elementos, e permite o acesso a somente um item de dados armazenado. O acesso aos itens é restrito, somente um item pode ser lido ou removido por vez. Os tipos de pilhas são: **LIFO ou UEPS** (O primeiro elemento a ser retirado é o último que tiver sido inserido), e **FIFO OU PEPS** (O primeiro elemento a ser retirado é o primeiro que tiver sido inserido).

**Fila -** A estrutura do tipo fila segue o mesmo conceito FIFO, ou seja, o elemento removido é o que está na estrutura há mais tempo, ou seja, o primeiro objeto inserido na fila é também o primeiro a ser removido.

**Árvore -** É uma estrutura de dados que organiza seus elementos de forma hierárquica, onde existe um elemento que fica no topo da árvore, chamado de raiz e existem os elementos subordinados a ele, que são chamados de nós ou folhas.

**Tabelas Hash -** De dispersão ou espalhamento, é uma estrutura de dados especial, que associa chaves de pesquisa a valores. Ela é uma generalização da ideia de array, porém utiliza uma função denominada Hashing para espalhar os elementos, fazendo com que os mesmos fiquem de forma não ordenada dentro do array que define a tabela. Essa estrutura permite a associação de valores a chaves.

**Valores -** É a posição ou índice onde o elemento se encontra.

**Chave -** Parte da informação que compõe o elemento a ser manipulado.

**Grafos -** São estruturas que permitem programar a relação entre objetos. Onde os objetos são vértices ou nós do grafo e os relacionamentos são arestas.

**Algoritmo -** É um conjunto de instruções estruturadas e ordenadas, seu objetivo é realizar uma tarefa ou operação específica. Eles são utilizados para manipular dados nas estruturas de várias formas, como por exemplo: inserir, excluir, procurar e ordenar dados. 





**:::Módulo 03 - Introdução ao Git e ao GitHub**

Nesse módulo estudamos sobre o que é Git e sua importância, os comandos básicos e seu funcionamento em um terminal, criação da chave SSH, ciclo de vida, e envio para o GitHub.



**::Conceitos:**

**Git -** É um sistema de controle de versão distribuído e amplamente adotado. 

**GitHub -** É um serviço de hospedagem na Web para repositórios git. Com a utilização dos dois (Git e GitHub), temos as seguintes vantagens: Controle de versão; Armazenamento em nuvem; Trablaho em equipe; Melhoria do código e Reconhecimento.

**SHA:** Significa Secure Hash Algorithm (Algoritmo de Hash Seguro). É um conjunto de funções hash criptográficas projetadas pela NSA (Agência de Segurança Nacional dos EUA).

**Markdown -** É uma linguagem simples de marcação originalmente criada por John Gruber e Aaron Swartz. Markdown converte seu texto em HTML válido. Markdown é frequentemente usado para formatar arquivos README, para escrever mensagens em fóruns de discussão online e para criar rich text usando um editor de texto simples.

**::Comandos básicos para um bom desempenho no terminal:**

* Windows:

**cd -** Navegar entre as pastas

**dir -** Listar todo o conteúdo dentro da pasta

**mkdir -** Criar uma pasta

**del/rmdir -** del: delata os arquivos contidos na pasta / rmdir: deleta a pasta e os arquivos.

**cls -** Limpar a tela do windows



* Linux:

**cd -** Navegar entre as pastas

**ls -** Listar todo o conteúdo dentro da pasta

**mkdir -** Criar uma pasta

**rm -rf -** Deleta a pasta e os arquivos

**clear -** Limpar a tela do windows



**::Tipos básicos de objetos do GIT:**

**Blob (Arquivos) -** Os arquivos ficam guardados dentro desse objeto, e eles contêm metadados dentro deles. Nele tem o tipo de objeto, o tamanho, a barra contrária e o conteúdo, porém não guarda o nome do arquivo.

**Tree (Pastas) -** Esse objeto armazena os blobs. Contêm metadados, e nele é guardado o nome do arquivo. Ele é responsável por montar toda a estrutura do arquivo e pode apontar para outra árvore.

**Commit -** É o mais importante dos objetos. Ele junta tudo para dá sentido. Ele aponta para uma árvore, para um parente (o último commit), para um autor e para a mensagem.



**::Comandos com o GIT:**

**Git init -** Iniciar o GIT. Esse comando cria um repositório vazio ou transforma uma pasta que você já tem, e que não está com controle de versão, em um repositório.

​	*git init*

**Git add -** Quando criamos, modificamos ou excluímos um arquivo, essas alterações ocorrerão em nosso ambiente local e não serão incluídas no próximo *commit* (a menos que alteremos as configurações). Precisamos usar o comando **git add **para incluir as alterações de um arquivo em nosso próximo *commit*. 

​	*git add arquivo*

**Git commit -** Criar um commit. 

​	*git commit -m "mensagem explicando a mudança no código"*

**Git clone -** Fazer o download do código fonte de um repositório remoto.

​	*git clone url-do-link*

**Git status -** Fornece informações sobre o status do arquivo no momento (untracked, modified ou staged)

​	*git status*

**Git push -** Esse comando envia as alterações do seu terminal para um servidor remoto.

​	*git push origin master*

**Git pull -** Esse comando puxa um arquivo já repositado em um servidor remoto para ajustar alterações realizadas nele.

​	*git pull origin master*



**::Ciclo de vida do GIT:**

**Untracked -** São arquivos não monitorados pelo GIT.

**Unmodifield -** São os arquivos não modificados.

**Modifield -** São os arquivos modificados.

**Staged -** São os arquivos que estão marcados para envio.



**::Links úteis:**

http://www.flowgorithm.org/download/index.html

https://git-scm.com/download/win

https://github.com/

https://www.markdownguide.org/basic-syntax/

