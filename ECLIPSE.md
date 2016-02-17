# docs

I) Control + Espaço

O Control + Espaço (Ctrl + Espaço, abreviação) é o atalho utilizado, dentro do próprio editor de código do Eclipse, para verificar o nome de uma classe ou objeto. Se você está em dúvida acerca do nome daquela classe que criou no início do projeto e muito menos não lembra o nome por completo, digite apenas o início do nome e logo após o atalho “Ctrl + Espaço”, conforme mostrado na Figura 1 para a classe String, onde foi digitado apenas o “Str” da classe.

Note também que o mesmo atalho também consegue filtrar, em tempo real, o código que está procurando, neste caso, a classe. Para isso, basta continuar digitando o restante da classe ou removendo caracteres e o mesmo irá acompanhar e atualizar a listagem de opções em tempo real.

Além disso, o mesmo atalho serve para ver possíveis nomes para variáveis a partir do próprio nome do objeto.

Também é possível criar métodos predefinidos, como o método main.

Ou até mesmo criar estruturas e/ou blocos de comando dentro da lógica de programação em si.

II) Control + 1

Toda vez que o seu código tiver um erro o Eclipse o irá mostrar com uma linha vermelha em forma de underline. Para entender o que está acontecendo ou até mesmo resolver o problema, podemos utilizar o atalho “Ctrl + 1”. Este atalho (apelidado de Quick Fix – rápida correção) te dá uma lista de opções para o erro que está acontecendo (Figura 5).

Para usá-lo, basta colocar o cursor na linha do erro e selecionar o respectivo atalho.

Esse atalho é extremamente poderoso. Ele permite que você crie novas variáveis locais e campos, bem como novos métodos e novas classes. Eu posso colocar um try-catch em torno das exceções apenas selecionando esta opção. Ele pode atribuir uma declaração para uma variável e muito mais.

Além disso, outro uso bastante comum deste atalho é para a geração de getters e setters. Existem várias formas de se gerar os métodos get e set dos atributos de uma classe. Ao criar um novo atributo com modificador de acesso privado (private), é possível criar tais métodos logo após. Para tanto basta selecionar o atributo recém-criado (que vai estar com uma linha amarela abaixo, uma vez que acabou de ser criado e ainda não está sendo usado) e chamar o atalho “Ctrl + 1” (Figura 6).

Outra utilidade bem comum é querer criar uma nova referência de um objeto a partir da instanciação do mesmo. Por exemplo, criar uma nova referência a um objeto String a partir da instanciação bruta do mesmo, conforme mostrado na Figura 7.

III) Control + 3

Este atalho é utilizado para buscar algum recurso, geralmente comandos, janelas ou menus disponíveis através das janelas gráficas superiores da IDE. É o típico comando utilizado quando não se sabe exatamente onde está ou deseja ir.

Nas versões anteriores à versão Juno do Eclipse, esse comando habilitava uma janela com uma lista de opções filtradas de acordo com o valor fornecido. Na nova versão da IDE, é possível acessar esse atalho por uma caixa de texto fixa na parte superior do Eclipse chamada “Quick Access”. Basta digitar na caixa o recurso desejado.

Ao clicar na caixa, uma lista de opções será exibida te informando o que você pode selecionar através desse atalho: Editors, Views, Perspectivas, Comandos, Propriedades, etc.

Um exemplo do uso desse atalho é a geração dos métodos gets e sets. Após criar um atributo, selecione o atributo e digite umas das palavras chaves da opção principal de geração “Generate Getters and Setters” e a janela mostrada na Figura 8 será exibida.

Também é possível gerar o mesmo efeito, a partir das primeiras letras que constituem o comando. Digite “ggas” e o mesmo atalho será exibido.

Outros atalhos

O Elipse é um “berçário de atalhos”, por assim dizer. Existem inúmeros outros atalhos. Listemos então alguns outros importantes:

    Ctrl + Shift + R: Este atalho abre uma janela para busca por resources, arquivos que se encontrem no seu workspace.
    Ctrl + Shift + T: Este atalho habilita uma janela de busca de arquivos de código fonte, arquivos compiláveis, inclusive os que se encontram dentro dos jar’s usadas pela aplicação.
    Ctrl + Shift + F: Este atalho identa o teu código, baseado nos templates definidos nas preferências da IDE. Se não existir nenhum template, o padrão do eclipse será utilizado.
    Ctrl + I: Organiza o código selecionado, com relação ao espaçamento do mesmo.
    Ctrl + Alt + Seta para baixo/cima: Faz uma cópia da seleção do código para cima ou para baixo. Simula o Ctrl + C/Ctrl + V sem o esforço deste mesmo atalho.
    Alt + Seta para cima/baixo: Transporta o código selecionado para cima ou para baixo uma linha.
    Obs.: Os dois últimos atalhos são também utilizados por algumas placas gráficas de alguns monitores. Se acontecer de a tela ficar de cabeça para baixo, simplesmente desabilite o atalho no software das mesmas.
    Ctrl + E: Habilita seleção dos arquivos abertos no Editor de código fonte.

Concluindo

Apenas um artigo mais completo traria aqui todos os atalhos dessa ferramenta IDE. São muitos, alguns mais complexos até que outros, e menos usuais também. O grande segredo dos atalhos é, de fato, a agilidade que eles proporcionam, além do conforto em não ter que usar o mouse para fazer tudo.

Tempo e treino são fatores importantes para memorizá-los e torná-los seus amigos, ao invés de considerá-los apenas mais algo a se aprender.

No mais, espero que tenha atingido meu objetivo, incentivá-lo a usar mais atalhos, não só no Eclipse mas em outras IDEs também.

Referencia: http://www.devmedia.com.br/principais-atalhos-do-eclipse/25614

=====================================================================================================================================

 13 teclas de atalho muito importantes no Eclipse!

Para andar pelo código

    Ctrl+Shift+G - Procurar todas a ocorrências do código selecionado.
    Ctrl+Shift+T — Procurar por uma Classe, digitando uma parte do nome dela. (Muito útil)
    Ctrl+F6 — Mudar entre os últimos arquivos usados
    F3 — O Ctrl+Clique do mouse no teclado.
    Ctrl+Alt+H — Abrir Call Hierarchy
    Ctrl+O - Mostra o Outline, com os métodos da classe, os atributos etc.
    Alt+Seta - É tecla voltar como no browser.

Edição de código

    Ctrl+1 — Quick Fix: abre a janela de Quick fix, permitindo fazer refactorings, correções etc.
    Ctrl+Space — Context Assist: use depois de um ., ou pra usar macros (for, while, sysout, …). Utilize no escopo de classe  para criar automaticamente declarções de métodos.
    Ctrl+Shift+O — Organizar imports
    Ctrl+Shift+F — Ajustar o formato do código
    Alt+Shift+T — Abre o menu de refactorings.

Ah, e se você esquecer algum atalho,

Ctrl+Shift+L abre uma lista com todas as teclas pra você lembrar :)

Abraços!

referencia: http://pedrocavalero.blogspot.com.br/2009/10/13-teclas-de-atalho-muito-importantes.html

=====================================================================================================================================


Atalhos e configurações para ganhar produtividade com Eclipse
Postado por Normandes Júnior	em 13/12/2014	  ●   41 comentários	

Será que realmente você está usando o Eclipse da melhor forma possível?

Usando as teclas de atalho e configurações certas, você vai ganhar muita agilidade e produtividade.

Vou te mostrar aqui várias teclas de atalho que utilizo no meu dia a dia e as configurações que gosto de fazer para customizar meu ambiente de desenvolvimento com o Eclipse.

Quer ficar ninja em Java? Clique aqui!

Vou começar falando das teclas de atalho que mais utilizo, mas existem muitas outras! Por isso este é um post interativo, preciso muito que você contribua me dizendo o que você usa, ok?

Provavelmente algumas são muito básicas para quem já usa o Eclipse há algum tempo, mas para quem está iniciando pode ser bastante útil, então, se você já é mais experiente, não me obrigue a dizer, em homenagem ao Chaves (in memoriam): ninguém tem paciência comigo!

Para você conseguir testar o que vou te mostrar aqui, é preciso ter um projeto Java criado no seu workspace, ok?

Também vou tentar agradar os usuários de Windows, Linux e OS X, colocando a combinação de teclas de atalho para estes sistemas operacionais.
Completar código

Windows/Linux e OS X: Ctrl + Space

Esse atalho é usado para pedir para o Eclipse terminar de completar o código pra você.

Pode ser usado para auto completar o nome de uma variável:
int idade = 20;
// depois de algum código, você precisa dessa variável idade
fazAlgumaCoisaComAIdade(id // nesse momento você aperta Ctrl + space
1
2
3
	
int idade = 20;
// depois de algum código, você precisa dessa variável idade
fazAlgumaCoisaComAIdade(id // nesse momento você aperta Ctrl + space

Também ajuda a encontrar métodos de um objeto de uma classe da API do Java ou que você mesmo tenha criado.
String nome = "João Silva";
// E então você quer saber quantos caracteres existem nessa String
System.out.println(nome. // normalmente o Eclipse já mostra as opções aqui, mas se não mostrar use o Ctrl + space
1
2
3
	
String nome = "João Silva";
// E então você quer saber quantos caracteres existem nessa String
System.out.println(nome. // normalmente o Eclipse já mostra as opções aqui, mas se não mostrar use o Ctrl + space

Eu também uso para gerar o nome de uma variável. Imagine que você tenha uma classe chamada CalculadoraImpostos e irá utilizá-la como o tipo de um atributo em outra classe qualquer.
private CalculadoraImpostos // Ctrl + space agora. O Eclipse irá te sugerir o nome da variável como: calculadoraImpostos ou até impostos
1
	
private CalculadoraImpostos // Ctrl + space agora. O Eclipse irá te sugerir o nome da variável como: calculadoraImpostos ou até impostos

Criar um novo arquivo

Windows/Linux: Ctrl + N
OS X: Cmd + N

Para criar algo novo, como uma classe, interface, enumeração, etc. É útil para você não ter que pegar o mouse e ir em File -> New.
Formatar código-fonte

Windows/Linux: Ctrl + Shift + F
OS X: Cmd + Shift + F

As vezes, mas só as vezes mesmo, você copia o código de algum arquivo ou de um tutorial na internet para sua classe, não é? Ou então você está começando na programação agora e não se acostumou a indentar seu código corretamente, alinhando os espaços dentro dos métodos, if, for, etc…

Seus problemas acabaram! (use com moderação, porque se você precisar usar esse atalho o tempo todo, deve ter algo de errado)
Organizar importações

Windows/Linux: Ctrl + Shift + O
OS X: Cmd + Shift + O

E quando você está programando e sua classe está cheia de imports que não são mais usados? Ou então estão faltando alguns outros imports? É só usar esse atalho que o Eclipse organizará tudo pra você.
Renomear refatorando

Windows/Linux: Alt + Shift + R
OS X: Cmd + Option + R

Renomear uma classe, atributo, método ou variável pode ser simples, mas quando existem várias referências para esse nome, você precisa refatorar, e é isso que esse atalho faz pra você.

No exemplo abaixo, queremos alterar o nome da variável “valor” para “preco”, ao invés de trocar uma a uma, colocamos o cursor sobre qualquer uma das referências de “valor”, usamos o atalho e digitamos o novo nome. O Eclipse toma conta de todo trabalho de refatoração.
int valor = 10;
valor *= 1.1;
produto.valorVenda(valor);
1
2
3
	
int valor = 10;
valor *= 1.1;
produto.valorVenda(valor);

Fechar janela de edição

Windows/Linux: Ctrl + W
OS X: Cmd + W

Quando você quer fechar um arquivo que já terminou a edição, você pega o mouse e clica no pequeno “x”? Agora não precisa fazer mais isso usando esse atalho.
Fechar todas as janelas de edição

Windows/Linux: Ctrl + Shift + W
OS X: Cmd + Shift + W

Se tiver muitos arquivos abertos e você quiser fechar todos, esse é o comando.
Excluir linha de código

Windows/Linux: Ctrl + D
OS X: Cmd + D

Esse é um dos meus favoritos, ele serve para apagar uma linha inteira de código! E apagar código é sempre bom, né? hehe
Abrir código em tela cheia

Windows/Linux e OS X: Ctrl + M

Tem horas que eu gosto de ver o arquivo que estou editando em tela cheia, então é só usar esse atalho.
Mover linhas pelo código-fonte

Windows/Linux: Alt + Seta Up/Down
OS X: Option + Seta Up/Down

Enquanto estamos programando, é comum querermos mover alguma linha para cima ou para baixo. Ao invés de selecionarmos e fazermos um “Copiar e Colar”, podemos simplesmente segurar a tecla Alt / Option e então usar as setas para cima ou para baixo.

É legal que você consegue mover até mais de uma linha, para isso basta selecionar todas que você quer movimentar.
Corrigir código rapidamente

Windows/Linux: Ctrl + 1
OS X: Cmd + 1

Esse também é excelente! Ele é o atalho para o quick fix, ou seja, sempre que seu código estiver com algum erro de compilação ou aviso (warning), você pode tentar usar esse atalho para o Eclipse te sugerir o que você pode fazer para resolver o problema.

Por exemplo, enquanto escreve um código qualquer, você percebe que irá precisar se comunicar com uma nova classe, então, ao invés de criar um novo arquivo, você simplesmente digita o nome da classe (que ainda não existe) no código-fonte… e claro que o código não irá compilar, mas você pode usar o atalho para pedir para o Eclipse criar pra você.
Abrir o código de um tipo

Windows/Linux: Ctrl + Shift + T
OS X: Cmd + Shift + T

Esse atalho é útil para abrir o código de um tipo (classe, interface, enumeração ou anotação), fazendo a pesquisa pelo nome.
Abrir o código de um arquivo (recurso)

Windows/Linux: Ctrl + Shift + R
OS X: Cmd + Shift + R

Já este atalho serve para abrir um recurso no seu projeto, como um arquivo texto, XML ou até mesmo de um tipo Java.
Pesquisar e navegar em arquivos abertos

Windows/Linux: Ctrl + E
OS X: Cmd + E

Sabe quando você tem vários arquivos abertos e quer ficar navegando de um para outro? Ao invés de pegar o mouse para selecionar a aba, use esse atalho para abrir uma pesquisa destes arquivos.
Navegar entre arquivos abertos

Windows/Linux: Ctrl + F6
OS X: Cmd + Fn + F6

Esse é bem útil quando você está trabalhando em dois ou mais arquivos e quer ficar navegando de um para o outro.
Executar uma classe

Windows/Linux: Alt + Shift + X, J
OS X: Cmd + Option + X, J

Se você estiver em uma classe com um método main e desejar executá-la, pode usar esse atalho. Repare que o funcionamento dele é um pouco diferente, você deve pressionar as 3 primeiras teclas e soltar, vai aparecer uma janela pequena no canto inferior direito, e só então pressione a tecla “J”.
Executar testes unitários

Windows/Linux: Alt + Shift + X, T
OS X: Cmd + Alt/Option + X, T

Esse atalho é semelhante ao anterior, mas a diferença é que ele executa testes unitários.
Acesso rápido

Windows/Linux: Ctrl + 3
OS X: Cmd + 3

Esse atalho é ótimo também, muito útil para gerar os getters e setters, equals() e hashCode, construtores e diversos outros comandos do Eclipse.

O atalho te leva para a caixa de entrada no canto superior direito do Eclipse (Quick Access). Você só precisa pressionar, soltar e fazer a pesquisa da ação que deseja executar.

Por exemplo, para gerar os getters e setters, basta digitar: ggas.

Talvez você esteja pensando: “O que? Como assim?“

Tem uma explicação, essas são as iniciais de “Generate Getters and Setters”.

Os caras são bons, não é verdade? :)

Digite: ghcae para gerar o equals() e hashCode(), que significa “Generate hashCode and equals”.

E para gerar o construtor usando os atributos da classe, digite gcuf, que significa “Generate Constructor using Fields”.
Listar todos os atalhos do Eclipse

Windows/Linux: Ctrl + Shift + L
OS X: Cmd + Shift + L

Quer mais? Use esse atalho para ver a lista completa de todos atalhos do Eclipse.
Configurações

Eu também costumo fazer alterações de configurações (algumas são de gosto pessoal). Pode ser que você utilize outras, então, contribua aí nos comentários. :)
Mostrar o número das linhas

Eu gosto de ver o número das linhas do lado esquerdo do editor, porque facilita encontrar em qual linha deu algum erro quando analiso uma Stack Trace, por exemplo.

Acesse as preferências do Eclipse. No Windows ou Linux, fica no menu “Windows”, já no OS X, fica no menu “Eclipse”.

Depois, navegue em General -> Editors -> Text Editors e marque o checkbox “Show line numbers”. Veja a imagem abaixo:

Show line numbers
Aumentar o número de colunas do editor

Por padrão, o Eclipse sugere o uso de 80 colunas no editor de código. Talvez esse número seja bom para resoluções de monitores menores, mas nos dias de hoje eu acho pouco, fazendo com que a formatação automática (Ctrl + Shift + F) quebre as linhas muito cedo.

Para aumentar esse número, ainda nas preferências do Eclipse, vá em Java -> Code Style -> Formatter. Clique em “New…” e defina um novo nome para sua customização. No meu caso eu utilizo “custom”, ficando como a imagem abaixo:

Formatter

Depois clique em “Edit…” e vá na aba “Line Wrapping”. Altere a opção “Maximum line width” para um valor maior. Eu costumo usar 120, como mostra a imagem abaixo:

Line Wrapping
Desabilitar a correção ortográfica

Eu não gosto que o Eclipse fique me dizendo que estou escrevendo errado, por isso desabilito essa checagem.

Nas preferências do Eclipse, navegue em General -> Editors -> Text Editors -> Spelling e desmarque a opção “Enable spell checking”, como na imagem abaixo:

Spelling
Suspender validações

Algumas validações eu também gosto de desabilitar, para deixar o Eclipse mais rápido!

Nas preferências, navegue em General -> Validation e marque a opção “Suspend all validators”, como mostra a imagem abaixo:

Suspend all validators
Encoding e line delimiter

Essa dica vale mais para o pessoal do Windows, pois a configuração padrão para o Linux e OS X já está do jeito que eu gosto de usar.

Não sei se já aconteceu com você, mas as vezes quando importamos o projeto de outros desenvolvedores, alguns caracteres ficam bem doidos!

Para todo mundo usar o mesmo encoding e o line delimiter, nas preferências do Eclipse, navegue em General -> Workspace e lá embaixo deixe a opção “Text file encoding” como “UTF-8” e “New text file line delimiter” como “Unix”, como mostra a imagem abaixo:

Encoding e line delimiter
Manter configurações no novo workspace

É importante dizer que essas configurações são feitas por workspace, ou seja, se você criar um novo, terá que refazer tudo ou usar a dica abaixo. ;)

Dentro do workspace que você já configurou do jeito que gosta, localize e copie a pasta “.metadata/.plugins/org.eclipse.core.runtime/.settings” para o novo workspace. Mas atenção, só copie essa pasta, porque se copiar outras podem dar alguns erros estranhos no Eclipse, ok?

Assista ao vídeo que mostro cada uma das teclas de atalho em ação e o efeito das configurações que vou fazendo.

referencia: http://blog.algaworks.com/atalhos-e-configuracoes-para-ganhar-produtividade-com-eclipse/


=====================================================================================================================================



Teclas de atalho essenciais no Eclipse

Escrito em 15/09/2011
Eclipse IDE

Essa dica é obrigatória para todo desenvolvedor não só para os que utilizam o Eclipse, mas para os que utilizam qualquer outra IDE, por que nós da área de programação em muitos casos vivemos trabalhando com muitas tarefas e não há coisa mais improdutiva do que programar em um IDE como se estivesse utilizando um simples bloco de notas (Digitando palavra por palavra), pior que isso utilizando com frequência os comandos de copiar e colar, que em muitas vezes geram possíveis bugs no sistema devido a falta de atenção do programador que copiou certo trecho de código e esqueceu de adaptá-lo. Além dessa atitude ser improdutiva, você deixa de utilizar 90% dos recursos presentes na sua IDE.

Abaixo seguem não todos, mas as principais teclas de atalho encontradas no Eclipse IDE:

CTRL + Espaço: Auto-completa uma palavra, é o comando mais utilizado pois através dele você pode conhecer todos os métodos, classes ou comandos presentes da linguagem configurada em seu Eclipse, além de exibir toda documentação deles (Isso é quando existe documentação em um método ou classe de terceiros).

CTRL + Shift + S: Salva todos os arquivos, é mais produtivo do que realizar o comando CTRL + S que salva somente um único arquivo por vez.

CTRL + Shift + O: Busca e inclui todos os imports que serão utilizados no seu código. É muito útil, pois evita agente pesquisar import por import de cada framework instalado no projeto.

CTRL + Shift + F: Essa dica é para os programadores preguiçosos ou desorganizados que não consegue identar o próprio código corretamente, esse comando formata todo seu código, respeitando todas as tabulações e espaços, tornando seu código limpo, organizado e compreensivo.

Alt + Shift + R: Para realizar esse comando primeiro selecione o nome de qualquer variável, método ou classe e depois realize o comando para renomear todas as ocorrências da classe, método ou variável que existir no projeto.

Alt – Shift + M: Extrai uma determinada porção de código selecionado para um novo método, ou seja, selecione um conjunto de linhas, realize este comando que irá surgir uma janela para configurar o nome do método e as regras desse método (private, public, protected), é muito útil, pois ele evita que dupliquemos códigos repetitivos.

Obs.: Esses comandos são os essenciais, existem muitos outros que não foram citados aqui, além do próprio Eclipse permitir a configuração de novos comandos, para fazer isso acesse o menu: Window -> Preferences -> General Keys.

referencia: http://udgwebdev.com/teclas-de-atalho-essenciais-no-eclipse
