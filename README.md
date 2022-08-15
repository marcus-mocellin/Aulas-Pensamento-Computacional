# Pensamento Computacional

## BNCC e Pensamento Computacional
A **Base Nacional Comum Curricular ([BNCC](http://basenacionalcomum.mec.gov.br/))** é um documento de caráter normativo que define o conjunto orgânico e progressivo de aprendizagens essenciais que todos os alunos devem desenvolver ao longo das etapas e modalidades da Educação Básica.

Na BNCC, encontra-se estabelecido o seguinte:

O Ensino Médio deve garantir aos estudantes a compreensão dos fundamentos científico-tecnológicos dos processos produtivos, relacionando a teoria com a prática. Para tanto, a escola que acolhe as juventudes, por meio da articulação entre diferentes áreas do conhecimento, deve possibilitar aos estudantes, dentre outros aspectos, a apropriação das linguagens das tecnologias digitais e a aquisição da fluência em sua utilização.

É preciso garantir aos jovens aprendizagens para atuar em uma sociedade em constante mudança, prepará-los para profissões que ainda não existem, para usar tecnologias que ainda não foram inventadas e para resolver problemas que ainda não conhecemos. Certamente, grande parte das futuras profissões envolverá, direta ou indiretamente, computação e tecnologias digitais.

**O pensamento computacional**, juntamente com o mundo digital e a cultura digital, são temas que fazem parte das diferentes dimensões que caracterizam a computação e as tecnologias digitais; e **tem por objetivo desenvolver as capacidades de compreender, analisar, definir, modelar, resolver, comparar e automatizar problemas e suas soluções, de forma metódica e sistemática, por meio do desenvolvimento de algoritmos.**

No Ensino Médio, dada a intrínseca relação entre as culturas juvenis e a cultura digital, torna-se imprescindível ampliar e aprofundar as aprendizagens construídas nas etapas do Ensino Fundamental. Afinal, os jovens estão dinamicamente inseridos na cultura digital, não somente como consumidores, mas se engajando cada vez mais como protagonistas.

Portanto, o foco passa a estar no reconhecimento das potencialidades das tecnologias digitais para a realização de uma série de atividades relacionadas a todas as áreas do conhecimento, a diversas práticas sociais e ao mundo do trabalho. São definidas competências e habilidades, nas diferentes áreas, que permitem aos estudantes:
- Buscar dados e informações de forma crítica nas diferentes mídias, inclusive as sociais, analisando as vantagens do uso e da evolução da tecnologia na sociedade atual, como também seus riscos potenciais;
- Apropriar-se das linguagens da cultura digital, dos novos letramentos e dos multiletramentos para explorar e produzir conteúdos em diversas mídias, ampliando as possibilidades de acesso à ciência, à tecnologia, à cultura e ao trabalho;
- Usar diversas ferramentas de software e aplicativos para compreender e produzir conteúdos em diversas mídias, simular fenômenos e processos das diferentes áreas do conhecimento, e elaborar e explorar diversos registros de representação matemática;
- Utilizar, propor e/ou implementar soluções (processos e produtos) envolvendo diferentes tecnologias, para identificar, analisar, modelar e solucionar problemas complexos em diversas áreas da vida cotidiana, explorando de forma efetiva o raciocínio lógico, o pensamento computacional, o espírito de investigação e a criatividade.

## Fases do Pensamento Computacional
- **Decomposição**: dividir o problema em elementos menores, mais fáceis de serem resolvidos;
- **Padronização**: identificar os padrões que se repetem nas soluções propostas e/ou que já estão presentes em soluções anteriores;
- **Abstração ou generalização**: abstrair (descartar) detalhes desnecessários de uma solução de modo que ela possa ser válida para a solução de outros problemas;
- **Algoritmo**: determinar a sequência de passos necessários para a resolução do problema.

## Algoritmo

Um **algoritmo** é um conjunto ordenado de passos, não ambíguos e com a finalidade de resolver um determinado problema. Um algoritmo pode ser representado na forma ***narrativa***, através de ***fluxograma***, ***linguagem algorítmica*** ou ***Diagrama de Chapin Estruturado***.

<p align="center">
<img src="https://user-images.githubusercontent.com/100809861/177052433-a7b3bf2b-328f-4a26-a2ea-7c41c4fbc51b.png"/>
</p>

**Características básicas** de um algoritmo:
- Ser finito;
- Não apresentar ambiguidades;
- Ser capaz de receber dados de entrada do mundo exterior;
- Ser capaz de gerar informações de saída para o mundo externo, a partir do ambiente do algoritmo;
- Ser efetivo, ou seja, todas as etapas especificadas no algoritmo devem ser alcançáveis em um tempo finito.

**5 Q’s** - perguntas que ajudam a compreender o problema e, consequentemente, auxiliam a montagem de um algoritmo de qualidade:
- Quais são os dados de entrada necessários?
- Que devo fazer com esses dados?
- Quais são as restrições desse problema?
- Qual é o resultado esperado?
- Qual a sequência de passos a ser feita para chegar ao resultado esperado?

**Recursos especiais** que podem estar presentes em algoritmos:
- Algoritmos com sequências, seleções, decisões e repetições;
- Algoritmos com estruturas de dados: listas, vetores e matrizes;
- Algoritmos com abstração ou generalização;
- Algoritmos com decomposição e reuso;
- Algoritmo com recursividade.

## Álgebra Booleana

Em 1854, **George Boole** (matemático e filósofo britânico) introduziu o formalismo denominado **Álgebra Booleana** que é utilizado até hoje para o tratamento sistemático da lógica. Este formalismo compreende um conjunto de operadores e axiomas, assumidos verdadeiros sem necessidade de prova.

Diferentemente da álgebra ordinária dos reais, onde as variáveis podem assumir valores no intervalo (-&infin;;+&infin;), as variáveis Booleanas só podem assumir um número finito de valores. Em particular, na álgebra Booleana de dois valores, cada variável pode assumir um dentre dois valores possíveis, os quais podem ser denotados por [F,V] (falso ou verdadeiro), [L,H] (low or high) ou ainda [0,1].

Como o número de valores que cada variável Booleana pode assumir é finito (e pequeno), o número de estados que uma função Booleana pode assumir também será finito, o que significa que podemos descrever completamente as funções Booleanas utilizando tabelas. Devido a este fato, uma tabela que descreva uma função Booleana recebe o nome de **tabela verdade**, e nela são listadas todas as combinações que as variáveis (entrada) podem assumir, bem como os correspondentes valores da função (saídas).

Na álgebra Booleana existem três operações ou funções básicas: operação **OU**, operação **E** e **complementação**. Todas as funções Booleanas podem ser representadas em termos destas operações básicas.

### Operação OU (Adição Lógica)

- *“A operação **OU** resulta **1** se pelo menos uma das variáveis de entrada vale **1**”.*

De acordo com a definição acima, a operação **OU**, também denominada **adição lógica**, resulta **0** somente quando todas as variáveis de entrada valem **0**.

A operação **OU** pode ser representada pelo símbolo “**+**”, mesmo símbolo utilizado para a adição algébrica (dos reais). Outra notação bastante utilizada é “**&or;**”.

Apesar do uso comum do símbolo “**+**, não se trata de uma adição algébrica, mas sim de uma **adição lógica**.

Em uma operação **OU**, as possibilidades de combinações entre duas variáveis Booleanas de dois valores [0,1] e os seus respectivos resultados, são:

<p align="center"><strong>0 + 0 = 0</strong></p>
<p align="center"><strong>0 + 1 = 1</strong></p>
<p align="center"><strong>1 + 0 = 1</strong></p>
<p align="center"><strong>1 + 1 = 1</strong></p>

Note que a operação **OU** só pode ser definida se houver, pelo menos, duas variáveis envolvidas. Ou seja, não é possível realizar a operação com uma uníca variável. Devido a isso, o operador  “**+**” (**OU**) é dito **binário**.

Nas equações, não se costuma escrever todas as possibilidades de valores. Apenas adotamos uma letra (ou uma letra com um índice) para designar uma variável Booleana. Com isso, já se sabe que aquela variável pode assumir ou o valor **0** ou o valor **1**. Então, para demonstrar o comportamento da equação A+B (lê-se A ou B), utiliza-se uma tabela verdade da seguinte forma:

<p align="center">
<img src="https://user-images.githubusercontent.com/100809861/184516115-20075fa1-4d08-4b2b-80fd-41651805a736.png"/>
</p>

Da mesma forma, podemos demonstrar o comportamento da equação A+B+C (lê-se A ou B ou C). Como na equação há somente o símbolo “**+**”, trata-se da operação **OU** sobre três variáveis. Logo, pode-se aplicar diretamente a definição da operação **OU**: o resultado será **1** se pelo menos uma das variáveis de entrada vale **1**.

<p align="center">
<img src="https://user-images.githubusercontent.com/100809861/184516116-d61a2cb1-0282-41e1-b324-aba167fd1ee2.png"/>
</p>

É importante notar que, devido ao fato de haver somente um operador na equação, pode-se também avaliar a equação decompondo-a em pares. Por exemplo, pode-se primeiramente achar o resultado de A+B, para depois operar os valores resultantes com os respectivos valores de C. Esta propriedade é conhecida como **associativa**. Também a ordem em que são avaliadas as variáveis A, B e C é irrelevante (propriedade **comutativa**). Estas propriedades são ilustradas pela tabela verdade a seguir. Nela, os parêntesis indicam subexpressões já avaliadas em coluna imediatamente à esquerda. Note que os valores das colunas referentes às expressões A+B+C, (A+B)+C e (B+C)+A são os mesmos (na mesma ordem).

<p align="center">
<img src="https://user-images.githubusercontent.com/100809861/184516119-fe3a363b-bc12-470f-bbb6-981f294b2192.png"/>
</p>

### Operação E (Multiplicação Lógica)

- *“A operação **E** resulta **0** se pelo menos uma das variáveis de entrada vale **0**”.*

De acordo com a definição acima, a operação **E**, também denomina **multiplicação lógica**, resulta **1** somente quando todas as variáveis de entrada valem **1**.

A operação **E** pode ser representada pelo símbolo “**&middot;**”. Outra notação bastante utilizada é “**&and;**”.

Em uma operação **E**, as possibilidades de combinações entre duas variáveis Booleanas de dois valores [0,1] e os seus respectivos resultados, são:

<p align="center"><strong>0 &middot; 0 = 0</strong></p>
<p align="center"><strong>0 &middot; 1 = 0</strong></p>
<p align="center"><strong>1 &middot; 0 = 0</strong></p>
<p align="center"><strong>1 &middot; 1 = 1</strong></p>

Assim como a operação **OU**, a operação **E** só pode ser definida se houver, pelo menos, duas variáveis envolvidas. Ou seja, o operador “**&middot;**” (**E**) também é **binário**.

Para demonstrar o comportamento da equação A&middot;B (lê-se A e B), utiliza-se uma tabela verdade da seguinte forma:

<p align="center">
<img src="https://user-images.githubusercontent.com/100809861/184516358-eb4565b0-387e-427a-b25b-9adf4de18743.png"/>
</p>

De forma semelhante, pode-se determinar o resultado da equação A&middot;B&middot;C (lê-se A e B e C) utilizando diretamente a definição da operação **E**: o resultado será **0** se pelo menos uma das variáveis de entrada valer **0**.

<p align="center">
<img src="https://user-images.githubusercontent.com/100809861/184516389-b6652de3-498d-41b1-80ec-d413fe20c446.png"/>
</p>

Para a operação **E** também são válidas as propriedades **associativa** e **comutativa**. Então, a equação A&middot;B&middot;C pode ainda ser avaliada tomando-se as variáveis aos pares, em qualquer ordem. Veja a tabela verdade a seguir e compare os resultados.

<p align="center">
<img src="https://user-images.githubusercontent.com/100809861/184516417-f17d0a82-5101-4461-a35e-a167d5c39f55.png"/>
</p>

### Complementação (ou Negação, ou Inversão)

A operação **complementação** dispensa uma definição. É a operação cujo resultado é simplesmente o valor complementar ao que a variável apresenta. Também devido ao fato de uma variável Booleana poder assumir um entre somente dois valores, o valor complementar será **1** se a variável vale **0** e será **0** se a variável vale **1**.

Os símbolos utilizados para representar a operação complementação sobre uma variável Booleana A são Ã , ~A e A' (lê-se A negado). Nesta disciplina, adotaremos o primeiro símbolo. O resultado da operação complementação pode ser listado:

<p align="center"><strong>~0 = 1</strong></p>
<p align="center"><strong>~1 = 0</strong></p>

Diferentemente das operações **OU** e **E**, a **complementação** só é definida sobre uma variável, ou sobre o resultado de uma expressão. Ou seja,  o operador  **complementação** é dito **unário**. E a tabela verdade para A  é:

<p align="center">
<img src="https://user-images.githubusercontent.com/100809861/184516672-e10207b4-1fd0-4ab3-84da-cf82917b7df5.png"/>
</p>

### Avaliação de Expressões Booleanas

Dada a equação que descreve uma função Booleana qualquer, deseja-se saber detalhadamente como esta função se comporta para qualquer combinação das variáveis de entrada. O comportamento de uma função é descrito pela sua tabela verdade e este problema é conhecido como **avaliação** da função ou da expressão que descreve a função considerada. Em suma, deseja-se achar a tabela verdade para a função Booleana.

Uma tabela verdade consiste basicamente de um conjunto de colunas, nas quais são listadas todas as combinações possíveis entre as variáveis de entrada (à esquerda) e o resultado da função (à direita). Também, pode-se criar colunas intermediárias, onde são listados os resultados de subexpressões contidas na expressão principal. Isto normalmente facilita a avaliação, principalmente no caso de equações muito complexas e/ou contendo muitas variáveis.

Quando numa mesma equação Booleana aparecem operações **E** e **OU**, é necessário seguir a ordem de precedência. Tal como na álgebra dos reais, a multiplicação (lógica) tem precedência sobre a adição (lógica). Além disso, expressões entre parêntesis têm precedência sobre operadores **E** e **OU** que estejam no mesmo nível. Quanto à complementação, esta deve ser avaliada tão logo seja possível. Caso a complementação seja aplicada sobre uma subexpressão inteira, é necessário que se avalie primeiramente a subexpressão para, só após, inverter o seu resultado.

O número de combinações que as variáveis de entrada podem assumir pode ser n calculado por 2<sup>n</sup>, onde n é o número de variáveis de entrada.

O procedimento para a criação da tabela verdade a partir de uma equação Booleana é:

1. Criar colunas para as variáveis de entrada e listar todas as combinações o n possíveis, utilizando a fórmula n° de combinações = 2<sup>n</sup> (onde n é o número de variáveis de entrada);
2. Criar uma coluna para cada variável de entrada que apareça complementada na equação e anotar os valores resultantes;
3. Avaliar a equação seguindo a ordem de precedência, a partir do nível de parêntesis mais internos:
    
    1° multiplicação lógica
    
    2° adição lógica

Tomemos como exemplo a expressão W = X + Y &middot; ~Z . A variável W representa a função Booleana propriamente dita. Esta variável depende das variáveis que estão à direita do sinal =, ou seja, depende de X, Y e Z. Logo, são 3 as variáveis de entrada. O total de combinações entre 3 variáveis será 2<sup>3</sup> = 8. Então, a tabela verdade para W deverá ter 3 colunas para as variáveis de entrada, 2 colunas para as combinações dessas variáveis e 8 linhas para os resultados da função. Seguindo o procedimento dado acima, cria-se uma coluna na qual listam-se os valores para ~Z. Em seguida, resolve-se a subexpressão que envolve a operação **E**. No caso em questão, Y &middot; ~Z. Então, cria-se uma coluna para Y &middot; ~Z , na qual anotam-se os resultados para este produto. Finalmente, utilizam-se os resultados de Y &middot; ~Z, listados na coluna anterior, para operar o **OU** com a variável X. Repare os passos descritos na tabela verdade que segue.

<p align="center">
<img src="https://user-images.githubusercontent.com/100809861/184518577-8f5807bf-184a-4575-82ab-29b44f30afae.png"/>
</p>

## Sistema de Numeração Binária

Também denominado **sistema binário** ou **sistema de base 2**, o **sistema de numeração binária** é um sistema de numeração posicional em que todas as quantidades são representadas com base em arranjos que contêm apenas os números **zero** e **um** **[0,1]**. Estes dois números podem corresponder, respectivamente, a pares de estados (ou de condições), como por exemplo: **[não, sim]**, **[falso, verdadeiro]**, **[desligado, ligado]**.

A eletrônica digital e a computação se baseiam no **sistema de numeração binária** e na **álgebra Booleana** que, através de circuitos eletrônicos digitais, são capazes de representar números e caracteres, bem como realizar operações lógicas e aritméticas.

Os programas de computador são codificados na forma binária e armazenados em mídias como as memórias em estado sólido e os discos ópticos ou magnéticos.

Em um programa, o **bit (b)** é a menor unidade de informação do **sistema de numeração binária**, assim como a **letra** é a menor unidade de informação do **sistema de escrita alfabética**.

Os **bits** são agrupados, conforme a necessidade dos sistemas de computação, da seguinte forma:
- 4 bits = **Nibble** (24 = 16 combinações);
- 8 bits = **Byte** (28 = 256 combinações);
- 16 bits = **Word** (216 = 65.536 combinações);
- 32 bits = **Double Word** (232 = 4.294.967.296 combinações);
- 64 bits = **Quad Word** (264 = 18.446.744.073.709.551.616 combinações).

Os computadores digitais trabalham internamente com dois níveis de tensão que correspondem ao **[0]** e ao **[1]** do sistema de numeração binária. Um **processador** utiliza **blocos lógicos** complexos, formados por **portas lógicas** básicas, cujo funcionamento é amparado por um postulado fundamental da eletrônica digital que determina que um circuito opere apenas com dois níveis de tensão bem definidos. Por exemplo, em um circuito digital **TTL** (***Transistor Transistor Logic***), os dois níveis de tensão padronizados são **0 V** e **5 V**. Portanto, em um circuito **TTL**, o **0 V** será interpretado e representado como **[0]**, enquanto o **5 V** será interpretado e representado como **[1]**.

## Programa EduTech

Em um programa de parceria com o **[Governo do Estado do Paraná](https://www.parana.pr.gov.br/)** denominado **[Edutech](https://www.educacao.pr.gov.br/programacao)**, a **[Alura](https://www.alura.com.br/)** e a **Secretaria da Educação e do Esporte ([SEED-PR](https://www.educacao.pr.gov.br/))** oportunizam a aprendizagem da programação aos estudantes da rede estadual de educação, contemplando o pensamento computacional, a cultura e o letramento digital.

A quase totalidade das atividades de programação descritas neste repositório fazem parte dos cursos da Alura.

## Algumas Definições Úteis

**Computação desplugada**: ensino de ciência da computação sem o uso de equipamentos de computação. Para tanto, faz-se necessário o desenvolvimento de atividades apropriadas que possibilitem o desenvolvimento das habilidades de resolução de problemas e de comunicação.

**Hardware**: são os itens físicos e tangíveis de um sistema de computação, desde o gabinete do computador até as partes internas que o compõe.

**Equipamentos de computação**: desktop, notebook, tablet, smartphone, assistentes virtuais, controladores digitais, dentre outros.

**Dispositivos de entrada**: são dispositivos utilizados para inserir dados no computador (teclado, mouse, microfone, câmera, tela touchscreen, sensor de luminosidade, sensor biométrico, sensor de temperatura, sensor de batimento cardíaco, dentre outros).

**Dispositivos de saída**: são dispositivos utilizados para promover a saída de dados do computador (tela de vídeo, impressora, alto-falante, dentre outros).

**Memória**: componente onde são armazenados os dados e o programa. Todo dado fornecido ao computador é armazenado em memória, bem como os resultados das operações. Um dado armazenado na memória recebe o nome genérico de variável.

**CPU – Unidade Central de Processamento**: corresponde ao cérebro do computador, sendo composta por outras duas unidades menores: **ULA** e **UC**.

**ULA – Unidade Lógica e Aritmética**: componente responsável pelas operações matemática e avaliações lógicas;

**UC – Unidade de Controle**: componente responsável por gerenciar as demais partes do computador, distribuindo as tarefas de acordo com as instruções do programa.

**GPU – Unidade de Processamento Gráfico**: apesar da evolução das **CPUs** nos últimos anos, elas ainda apresentam uma certa deficiência em processamentos gráficos. Isso acontece porque os dados são transferidos de forma sequencial. Portanto, quando vários dados precisam ser processados simultaneamente a **GPU** entra em ação, reduzindo a pressão sobre a **CPU** e melhorando o desempenho. Em alguns computadores e notebooks, nos modelos mais baratos, a **GPU** está integrada à **CPU**, o que diminui a eficiência em tarefas pesadas. A **GPU** executa funções semelhantes à da **CPU**, mas a diferença está na forma como ela realiza seu trabalho. A estrutura é adaptada para processar bilhões de cálculos por segundo, uma tarefa extremamente importante em jogos. Ou seja, ela não funciona de maneira linear, mas sim como uma espécie de rede de neurônios que trabalham ao mesmo tempo para entregar um desempenho consideravelmente melhor. A **GPU** também tem sua própria memória **RAM** para salvar dados gerados. Esse componente cria um buffer para armazenar imagens concluídas até que você precise exibi-las novamente, agilizando assim o processo.

**Software**: parte inteligente de um sistema de computação, associada à programação.

**Software aplicativo**: utilizados pelo usuário para finalidades específicas, como os aplicativos de smartphones, os browser, o Microsoft Office, dentre outros.

**Software básico**: programas destinados a atividades intrínsecas do computador, como o sistema operacional.

**Compilador**: programa tradutor capaz de converter um **programa fonte**, escrito em **linguagem de alto nível** (C++, C#, JavaScript, Python, HTML, dentre outras), para um **programa executável**, escrito em **linguagem de máquina**, ou **linguagem de baixo nível**. A **linguagem de máquina** é a única linguagem que o computador pode entender. Antes de converter uma **linguagem de alto nível** em uma *linguagem de máquina**, o compilador a converte para uma **linguagem intermediária**, também denominada **linguagem de montagem** (***Assembly Language***). Para isso, faz uso de um **programa montador**.
