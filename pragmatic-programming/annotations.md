# Entropia de Software

> Entropia: nível de "desordem" de um sistema. As leis da termodinâmica garantem que a entropia no universo tende em direćão ao máximo.

> Deterioraćão de software: Quando a desordem - entropia - aumenta no software 

> "Teoria da Janela Quebrada": Não tolere *janelas quebradas*. Não deixe janelas quebradas (projetos insatisfátorios, decisões erradas ou código inadequado) sem reparos.

> Se um projeto tiver um código em estado imaculadamente adequado - escrito, bem projetado e elegante - outras pessoas vão tomar cuidado para não danificá-lo.

## Desafios:

1. Ajudar a fortalecer sua equipe examinando as "vizinhanćas". Selecione duas ou três "janelas quebradas" e discutir quais os problemas das mesmas e o que pode ser feito para melhorar.

# Sopa de Pedras e Sapos Cozidos

- Dica: *Seja um catalisador da mudanća*

> Mostre as pessoas um vislumbre do futuro e fará com que colaborem - elas se associam mais fácil a algo que vem obtendo êxito: É mais fácil pedir desculpas do que permissão

- Dica: *Lembre-se do cenário em larga escala*: Verifique frequentemente o que está acontecendo ao seu redor e não apenas o que você prórpio está fazendo.

# Software Satisfatório

> Atingir um estado satisfatório: não só produzir um software que atenda todos os requisitos, mas um software que o usuário tenha oportunidade de participar do processo de decisão, e seja capaz de decidir quando o que produzimos atingiu o satisfatório.

- Dica: *Torne a qualidade parte dos requisitos*

> Porém saiba quando parar: não estrague um programa que funcione perfeitamente efeitando e aprimorando-o excessivamente.

## Desafios

1. Observe o efeito da modularidade na distribuićão de software: Demora mais ou menos tempo obter um software monolítico com a qualidade requerida em comparacão com um software projetado em módulos?

# Sua carteira de conhecimentos

- Um investimento em conhecimento sempre paga os melhores juros.

- O conhecimento é um *bem expirável*: algo cujo valor diminui com o tempo.

> Devemos sempre estar estudando e aprimorando, pois o que sabemos hoje, amanhã pode não ter tanto valor em uma empresa.

- O gerencimento de uma carteira de conhecimentos é muito semelhante ao gerencimento de uma carteira de investimentos:

a) Investidores sérios investem regularmente - como um hábito.
b) A diversificacão é a chave para o sucesso a longo prazo.
c) Investidores astutos têm uma carteira equilibrada com investimentos conversadores e investimentos de alto risco e remuneracão.
d) Os investimentos tentam comprar barato e vender caro para obter o máximo em retorno.
e) As carteiras devem ser reexaminadas e reestruturas periodicamente.

Sendo assim:

- *Invista regularmente*: O hábito é tão importante quanto a soma.
- *Diversifique*: Quando mais coisas diferentes você souber, mais valor você terá. Quando mais tecnologias você conhecer, melhor conseguirá se adaptar à mudanca.
- *Gerencie o risco*: Não arrisque todas as suas apostas técnicas na mesma direcã́o
- *Compre barato, venda caro*: Aprender uma tecnologia emergente antes dela se tornar popular pode ser tão difícil quanto encontrar uma acão em baixa, mas os lucros podem ser igualmente recompensadores.
- *Reexamine e reestruture*: Sempre é bom estar reexaminando o que está trabalhando, e as tecnologias no qual está estudando.

A mais importante:

- Dica: *Invista regularmente em sua carteira de conhecimentos*

Sugestões:

- *Aprenda pelo menos uma nova linguagem todo ano* 
- *Leia um livro técnico a cada trimestre*
- *Leia também livros não técnicos*
- *Tenha aulas*
- *Participe de grupos de usuários locais*
- *Experimente ambientes difernetes*
- *Mantenha-se informado*: Assine revistas e periódicos e selecione algumas que abordem tecnologias diferentes da de seu projeto atual.
- *Mantenha-se conectado*

- Dica: *Analise criticamente o que você lê e ouve*

# Comunique-se

- Melhor ser olhada superficialmente do que ser ignorada.

> Anote as ideias que deseja comunicar e esboce algumas estratégias para transmití-las.

- Buscar o melhor momento para transmitir algo.

- Dica: *É o que você diz e a maneira como diz*

## Desafios

1. Ler livros sobre comunicacão: Tentar ler os três em até 18 meses.

# Os males da duplicaćão

- Dica: *NSR - Não se repita* - Cada bloco de infromacões deve ter uma representacão oficial, exclusiva e sem ambiguidades dentro de um sistema

Tipos de duplicacãO: 

- *Duplicacão imposta*: 

> Duplicacão entre sistemas por exemplo, geralmente acontece quando temos várias representacões da mesma coisa em vários ambientes. A solucão costuma ser um gerador de código ou filtro simples. Esquema de dados podem ser construídos a partir de metadados utilizados na construcão do esquema.

> Documentacão e código: geralmente devemos buscar maneiras para que a documentacão reflita o código. Uma estratégia é gerar testes a partir da documentacão inicial.

- *Duplicacão inadvertida*

> Geralmente acontece na especificacão do projeto, por falta de normalizacão de dados, por exemplo.

> Acontece também por conta de armazenarmos dados que podem ser calculados a partir de outros. Porém por questão de desempenho, podemos optar por mante-lo, ou desenvolver uma estratégica de cache descente.

- *Duplicacão impaciente*

> Geralmente causada pelo desenvolvedores, por conta de prazos apertados ou busca de atalhos para finalizar uma entrega.

- *Duplicacao entre desenvolvedores*

> Ter uma boa comunicacão e fóruns de discussão podem evitar esse tipo de duplicacão


# Ortogonalidade

É um conceito crítico quando queremos produzir sistemas que sejam fáceis de projetar, construir, testar e estender. 

- O que é ortogonalidade: Termo emprestado da geometria, diz a respeito de duas linhas que seu ponto de origem é um ângulo reto, como eixos de um gráfico. Em termos de vetor, as duas linhas não *independentes*.

- Em computacão, o termo diz a respeito de *independência* e *desvinculacão*. Duas coisas são ortogonais quando alteracões em uma não afeta as outras. Exemplo: um sistema bem projetado, você pode alterar o banco de dados sem afetar a interface do usuário e vice-versa.

- *Sistemas não ortogonais*: Os controles de um helicóptero são não ortogonais, pois cada acão em um controle, afeta diretamente a acão em outro controle, sendo assim um sistema complexo de se controlar.

> Quando componentes de um sistema são altamente interdependentes, não existe conceito de correcão local.

- Dica: *Elimine efeitos entre elementos não relacionados*

## Projeto

- Vantagem de se criar sistemas ortogonais: *maior produtividade e menor risco*

- 1. Ganhe produtividade:

> AlteracÕes são localizadas, portanto, os tempos de desenvolvimento e testes são menores. É mais fácil criar componentes autônomos relativamente pequenos do que um único e grande bloco de código.

> Abordagens ortogonais também favorecem a reutilizacão. Quanto menso dependências, os sitemas serão mais fáceis de reconfigurar e reconstruir.

> Ganho sutil de produtividade: Se um sistema realiza M coisas distintas e outro faz N coisas, se forem ortogonais, o resultado final fará M x N coisas.

- 2. Reduza o risco

> Secões de código danificadas ficam isoladas, sendo menor a probabilidade de espalhar efeitos para o resto do sistema, sendo fácil também removê-lo e inserir algo novo.

> Sistema é menos fácil, já que possíveis alteracões problemáticas podem ficar restritas a essa área.

> Sistemas ortogonais são testados com mais eficácia, pois é mais fácil projetar e testar.

- Conceito de *equipe ortogonal*: ter várias equipes e papéis com responsabilidades bem definidas.

- Técnica para verificar em um *projeto é ortogonal*: Ao finalizar um projeto de arquitetura, se pergunte "Se eu alterar dramaticamente os requisitos existentes por trás de uma funcão específica, quantos módulos serão afetados?"; Em um sistema ortogonal a resposta deve ser "um". Pergunte também a si mesmo o quanto o seu projeto está desvinculado de mudancas no mundo real. Exemplo: Você está utilizando um número de telefone como identificador de clientes? O que acotnece quando a empresa de telefonia reatribui códigos da área?

## Kits de Ferramentas e bibliotecas

- Atencão ao adicionar bibliotecas e kits de desenvolvimentos ao projeto, sempre se pergunte o quão esse projeto está afetando a ortogonalidade de um sistema.

- Sistemas *orientados a transacão* -> Código ou aplicativo tem que delinear o início e o fim de cada transacão.

- Variante da ortonogalidade: *Programacão Orientada a Aspectos (POA)*. Essa permite que expresse em um local, um comportamento que, de outra forma, seria distribuído por todo o seu código-fonte. Exeplo: Java POA para exibir _mensagens de log_ ao entrar em qualquer método.

## Codificacão 

> Sempre que está codificando, estará correndo o risco de reduzir a ortogonalidade de seu aplicativo. 

- Técnicas para manter a ortogonalidade durante a codificacão:

- 1. *Manter o código desvinculado*: Escreva código cautelosos, móduslo que não revelem nada de desnecessário para outros módulos e que não dependam de implementacões de outros módulos, _Lei de Deméter_.

- 2. *Evite dados Globais*: Sempre que o seu código referenciar dados globais, ele ficará vinculado aos outros componentes que compartilham esses dados - Um exemplo é o uso de Singletons. Sempre que alterar esse dados global, estará preocupado com todos os módulos que o utilizam.

- 3. *Evnite funcões semelhantes*: Funcões com aparência semelhante, mas cada uma terá um algoritmo central diferentes, sendo um sintoma de problemas estruturais. O padrão _Strategy de Design Patterns_ pode obter uma implementacão melhor.

## Testando

> Um sistema projetado e implementado ortogonalmente é mais fácil para testar.Um teste em nível de módulo, é mais fácil do que um teste de integraćão. É interessante cada módulo ter seu teste unitário e que sejam executado automaticamente.

- A construcão de teste de unidade ja é um teste interessante de ortogonalidade: Se para produzir uma unidade de teste é necessário um grande percentual do resto do sistema, você encontrou um módulo que não está tão desvinculado do resto do sistema.

- Durante a correcão de erros também é um momento importante para discutir sobre ortogonalidade de software. Quanto mais módulos forem necessários alterar para corrigir erros, menos ortogonal um software será.

 
