## Senai Areias

Recife, 31 de março de 2025
Professor: Leandro Andrade
Aluno: Pablo Miguel Santos Da Fonseca
UC: Programação de aplicativos
______________________________________________________



### Desafio 01
•	Com suas palavras defina o que é um sistema de controle de versões (VCS)
•	Cite 5 vantagens em utilizar VCS
•	Cite 3 exemplos de VCS


Com suas palavras defina o que é um sistema de controle de versões (VCS)

É um utilitário de software que monitora e gerencia as mudanças em um sistema de arquivos. Um VCS também oferece utilitários colaborativos para compartilhar e integrar essas mudanças do sistema de arquivos com outros usuários do VCS. Como os ambientes de desenvolvimento aceleraram, os sistemas de controle de versão ajudam as equipes de software a trabalhar de forma mais rápida e inteligente. Eles são ainda mais úteis para as equipes de DevOps, pois as auxiliam a reduzir o tempo de desenvolvimento e aumentar as implementações bem-sucedidas. Trabalhar com controle de versão significa ter sempre um backup. Atualizações de projetos individuais são reunidas periodicamente em um único grupo, conhecido como “commit”, antes de serem mescladas no código-fonte principal. Um software de controle de versão é essencial para rastrear toda as modificações em cada arquivo de projeto.

### Cite 5 vantagens em utilizar VCS

•	O controle de versão também ajuda os desenvolvedores a se mover mais rápido e permite que as equipes de software preservem a eficiência e a agilidade à medida que a equipe é escalonada para incluir mais desenvolvedores

•	Depois que um VCS começa a monitorar um sistema de arquivo de código fonte, ele mantém o estado do código fonte em um histórico do projeto. Isto permite a possibilidade de "desfazer" ou reverter um projeto de código fonte para o último estado conhecido

•	Um repositório central em um sistema de controle de versão atua como a fonte única de verdade, aumentando a transparência do projeto e o comprometimento da equipe com ele. Essa visão centralizada da evolução do projeto ajuda a melhorar o planejamento, o rastreamento e a colaboração, pois todos os membros da equipe têm acesso às atualizações mais recentes 

•	Cada software de controle de versão usa mecanismos desenvolvidos para evitar qualquer tipo de invasão de agentes mal-intencionados nos arquivos. Além do mais, somente usuários com permissão podem alterar o código.

•	além disso, o versionamento fornece uma maneira eficaz de gerenciar lançamentos e versões, facilitando a identificação das versões estáveis para usuários finais e a entrega de atualizações consistentes e confiáveis.



### Cite 3 exemplos de VCS

	Git
	CVS 
	MERCURIAL


### Referências

	https://www.locaweb.com.br/blog/temas/codigo-aberto/versionamento-de-software-importancia/

	https://learn.microsoft.com/pt-br/devops/develop/git/what-is-version-control

	https://pm3.com.br/blog/controle-de-versao/

	https://unity.com/pt/topics/what-is-version-control

	https://about.gitlab.com/pt-br/topics/version-control/#why-use-version-control

	https://bitbucket.org/product/br/version-control-software#:~:text=Um%20sistema%20de%20controle%20de%20vers%C3%A3o%20ou%20VCS%2C%20tamb%C3%A9m%20conhecido,em%20um%20sistema%20de%20arquivos.

	https://www.atlassian.com/br/git/tutorials/what-is-version-control

	https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Sobre-Controle-de-Vers%C3%A3o



# Desafio 02
Senai Areias
Recife, 03 de abril de 2025
Professor: Leandro Andrade
Aluno: Pablo Miguel Santos Da Fonseca
UC: Programação de aplicativos


### Com suas palavras defina o que é programação orientada a objetos (POO) e cite seus pilares? (mínimo 10 linhas)
Nesse mercado, existem diversas linguagens de programação, que seguem diferentes paradigmas. Um desses paradigmas é a Orientação a Objetos, que atualmente é o mais difundido entre todos. Isso acontece porque se trata de um padrão que tem evoluído muito, principalmente em questões voltadas para segurança e reaproveitamento de código, o que é muito importante no desenvolvimento de qualquer aplicação moderna.
A Programação Orientada a Objetos (POO) diz respeito a um padrão de desenvolvimento que é seguido por muitas linguagens, como C# e Java.É um paradigma de programação baseado no conceito de “objetos”, que podem conter dados na forma de campos, também conhecidos como atributos, e códigos, na forma de procedimentos, conhecidos como métodos. Um dos principais objetivos da POO é facilitar o entendimento e a modelagem de software complexo através da organização do código em unidades lógicas que representam entidades ou conceitos do mundo real.Os quatro pilares da POO são conceitos fundamentais que permitem aos desenvolvedores construírem sistemas de software flexíveis, reutilizáveis e de fácil manutenção. Vamos explorar cada um desses pilares em detalhe, os 4 pilares são abstração, encapsulamento, herança e polimorfismo.



 ### Exemplifique e explique um cenário de abstração

A abstração consiste em um dos pontos mais importantes dentro de qualquer linguagem Orientada a Objetos. Como estamos lidando com uma representação de um objeto real (o que dá nome ao paradigma), temos que imaginar o que esse objeto irá realizar dentro de nosso sistema. São três pontos que devem ser levados em consideração nessa abstração.

O primeiro ponto é darmos uma identidade ao objeto que iremos criar. Essa identidade deve ser única dentro do sistema para que não haja conflito.
Exemplo:Nessas linguagens, a identidade do objeto não pode ser repetida dentro do pacote, e não necessariamente no sistema inteiro. Nesses casos, a identidade real de cada objeto se dá por ..

A segunda parte diz respeito a características do objeto. Como sabemos, no mundo real qualquer objeto possui elementos que o definem. 
Exemplo: as propriedades de um objeto “Cachorro” poderiam ser “Tamanho”, “Raça” e “Idade”.

a terceira parte é definirmos as ações que o objeto irá executar. Essas ações, ou eventos, são chamados métodos. 
Exemplo: Esses métodos podem ser extremamente variáveis, desde “Acender()” em um objeto lâmpada até “Latir()” em um objeto cachorro.
Exemplo cenário: 
Abstração de uma bola de futebol
Ao abstrair uma bola de futebol de couro por uma bola de futebol, retiramos apenas a informação das suas propriedades e comportamentos. 



### Exemplifique e explique um cenário de encapsulamento
Se refere à construção do objeto de modo a proteger o acesso direto a seus dados internos. Ao encapsularmos um objeto estamos agrupando propriedades e métodos que estão diretamente relacionados dentro de um mesmo objeto, permitindo que essas propriedades sejam acessadas apenas através de métodos públicos. Desta forma tratamos de questões importantes como segurança e confiabilidade do estado do objeto
Exemplo: Protege-se os atributos e comportamentos de cada personagem, restringindo o acesso a partir de outras classes ou objetos. No caso, pode-se acessar a saúde de um personagem somente por métodos específicos, evitando a manipulação inadequada.



### Exemplifique e explique um cenário de herança
A Herança é uma forma de eliminar repetição de código onde, como o próprio nome sugere, um objeto pode herdar características (ou seja, propriedades e métodos) de outra classe, sem a necessidade de se reescrever essas mesmas características. Essa característica otimiza a produção da aplicação em tempo e linhas de código.
Exemplo: Cria-se classes específicas para cada tipo de personagem, como “Zumbi”, “Vampiro” e “Fantasma”, que herdem as características da classe “Personagem” e adicionam comportamentos e atributos específicos. Assim, um zumbi pode ter uma velocidade de movimento mais baixa do que um vampiro.



### Exemplifique e explique um cenário de polimorfismo
Em POO Polimorfismo é caracterizado quando duas ou mais classes possuem métodos com o mesmo nome, mas podendo ter implementações diferentes. Assim, é possível utilizar qualquer objeto que implemente o mesmo método sem nos preocuparmos com o tipo do objeto mas cada subclasse de uma forma diferente da outra derivada.
Exemplo: Utiliza-se o polimorfismo para que diferentes personagens respondam de maneiras diferentes a uma mesma mensagem, como “ataque”. Dessa forma, um zumbi pode realizar ataques físicos, enquanto um fantasma pode realizar ataques à distância com sua habilidade de passar através de obstáculos.



### Cite 5 vantagens da POO.
1- Reutilização de código: permite a reutilização do código em vários lugares, o que economiza tempo e aumenta a eficiência;
2- Facilidade de manutenção: ajuda a organizar o código em unidades menores e mais fáceis de entender, tornando-o mais fácil de manter e corrigir;
3- Melhor separação de responsabilidades: permite a distribuição das tarefas de maneira mais clara entre diferentes objetos;
4- Maior capacidade de escalabilidade: ajuda a tornar o código escalável, o que é importante em projetos de software de grande porte;
5- Maior facilidade de colaboração: permite que vários programadores trabalhem  juntos em projetos de software de maneira mais eficiente.


### Referencias

https://www.alura.com.br/artigos/poo-programacao-orientada-a-objetos?srsltid=AfmBOopTxpVpQiccldUmjXUohPu4aKMGQV4WecT6rdr0s1FhYDEhfVOL

https://www.devmedia.com.br/os-4-pilares-da-programacao-orientada-a-objetos/9264

https://www.dio.me/articles/os-4-pilares-da-programacao-orientada-a-objetos-Y0CN7G

https://blog.grancursosonline.com.br/pilares-da-poo/

https://hub.asimov.academy/blog/programacao-orientada-a-objetos-conceito-e-pilares/#quais-sao-as-vantagens-da-poo%3f





