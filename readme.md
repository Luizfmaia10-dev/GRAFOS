🖥️ Teoria dos Grafos - Engenharia de Software
Repositório destinado ao armazenamento de estudos, resumos e implementações práticas desenvolvidos na disciplina de Teoria dos Grafos.

------------------------------------------------------------------------------------------------------------------------------

👤 Identificação do Autor

Nome: Luiz Fernando Maia

Curso: Engenharia de Software (4º Período)

Ano/Semestre: 2026/2

**📌 Sobre a Disciplina**
A Teoria dos Grafos estuda as relações e conexões existentes entre diferentes objetos discretos. Na engenharia de software, este campo é a base fundamental para a modelagem e otimização de sistemas complexos, como redes de computadores, malhas rodoviárias, diagramas filogenéticos, redes sociais e bancos de dados orientados a grafos.

**📚 Estrutura Teórica da Matéria Primeira Prova (Slides 01 a 10)**

*📂 Slide 01: Introdução à Teoria dos Grafos*

*📂 Slide 02: Conceitos Fundamentais*

*📂 Slide 03: Representação de Grafos*


📂 Slide 07: Busca em Profundidade
Busca em Profundidade para grafo NÃO direcionado:
A busca em profundidade ou DFS e um tipo de busca em que nos temos tres tipos diferentes de arestas:

 - Aresta de Retorno:Nos usamos para conectar um vertice ja explorado a outro vertice e que não tem relação de aresta de arvore ou alguma relação de pai ou filho

 -Aresta de arvore :Geralemnte usada para pais e filhos essa aresta tem como intuito explorar os vertices de forma linear

 Tambem temos que saber conceitos importantes como Termpo de Descoberta(TD) e tempo de termino(TT) são conceitos em que o TD começa quando nos inicamos um vertice e o TT quando nos ja o exploramos por completo,lembrando que esses dois conceitos dividem o mesmo contador global,lembrando tambem que a escolha da raiz é arbritaria

 Quando nos começamos a DFS fazemos pilha com os vertice que o conectam,por exemplo a pilha do vertice V BP(V)={A,B,C},estou dizendo que o vertice V se conecta com os vertices ABC,a escolha da ordem é arbritaria ,seguindo a ordem o proximo elemento a ser explorado seria o A então ficaria BP(A)={conjunto de vertices que conectam com o A} e do V para o A teria uma aresta de arvore,alem disso por começamos a busca pelo V nos teriamos no V um tempo de descoberta =1 e o seu pai nulo ja que ele e o primeiro ,deposi que a egnte foi para o A teriamos no vertice A um Tempo de descoberta = 2 e o o seu pai será o Ve por ai seguimos com o conjunto do vertice A

 
