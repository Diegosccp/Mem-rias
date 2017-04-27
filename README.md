# Memorias

Memórias
Conceito de Memória RAM

A memória RAM ou de acesso aleatório é utilizada frequentemente na informática para o armazenamento de programas e dados informativos.
A sigla RAM significa em inglês "Random Access Memory" e é traduzida como "Memória de Aceso Aleatório" ou, em alguns casos, "Direto". Uma memória deste tipo é uma peça composta por um ou mais chips que faz parte do sistema de um computador.
A característica diferencial deste tipo de memória é que se trata de uma memória volátil, ou seja, ela perde seus dados quando deixa de receber energia, normalmente quando o computador está desligado. Assim, é diferente de outras memórias, tal como o ROM, que tem a capacidade de armazenar informação independentemente das condições de energia disponíveis.
Então, a memória RAM é um dispositivo utilizado para o gerenciamento de dados e informações circunstancialmente com programas e software. Esta memória permite o funcionamento destas aplicações e uma vez desligada ou interrompida o funcionamento do sistema a informação se perde, pois muitas vezes não se trata de arquivos ou dados guardados por importância, mas simplesmente de dados necessários para o desempenho do software em questão.
As memórias desta índole podem ser dividas em estáticas e dinâmicas. As primeiras mantêm seu conteúdo inalterado desde que exista uma fonte de energia. As segundas, ao contrário, envolvem uma "leitura destrutiva", ou seja, a informação é perdida ao ser lida e para evitar isso deve-se restaurar os dados com uma operação de "refresco".
Uma RAM pode ter diversos tamanhos expressos em megabytes ou gigabytes e, desta forma, permite usos de menor ou maior nível. Por exemplo, a utilização simultânea de vários programas, ou então, o acréscimo da velocidade de conexão ou de funcionamento do computador.
Em geral, ao adquirir um computador, a memória RAM vem inclusa, mas muitas vezes pode ser prolongada caso o usuário queira fazer um uso maior da mesma.



Conceito de Memória ROM

O termo memória ROM se refere a uma memória de armazenamento que permite apenas a leitura da informação e não de sua destruição, independente da presença ou não de uma fonte de energia que a alimente.
ROM é uma sigla em inglês que se refere ao termo “Read Only Memory” ou “Memória de Apenas uma Leitura”. Trata-se de uma memória de semicondutor que facilita a conservação da informação que pode ser lida, mas que não pode ser destruída. Diferentemente da memória RAM, os dados contidos em uma memória ROM não são destruídos nem perdidos em caso de interrupção da energia elétrica, por isso, é chamada de “memória não volátil”.
Frequentemente as memórias ROM são usadas como principal meio de armazenamento de dados dos computadores. Por ser uma memória que protege os dados e impede sua substituição, as memórias ROM são empregadas para armazenar informação da configuração do sistema, dos programas de arranque ou início, suporte físico e outros programas que não precisam de atualização constante.
Embora durante as primeiras décadas dos computadores, o sistema operacional era armazenado totalmente na memória ROM, atualmente estes sistemas tendem a ser guardados nas novas memórias flash.
Anteriormente, não havia alternativas eficientes para a memória ROM e da necessidade de mais memória, ou então, de uma atualização dos programas e do sistema; era preciso substituir a memória velha por um novo chip de ROM.
Hoje em dia os computadores podem conservar alguns de seus programas em ROM, mas a memória flash está cada vez mais difundida, inclusive nos celulares e dispositivos PDA.
Além dos computadores, os jogos de videogames continuam utilizando programas baseados na memória ROM, como Nintendo 64, Super Nintendo ou Game Boy.
Por causa da velocidade de uso, a informação contida em uma memória ROM pode passar para a RAM quando exigida no funcionamento do sistema.


SWAP

*No Linux, o swap é a memória virtual (também é conhecido como área de troca). A memória virtual funciona como uma extensão da memória RAM, que fica armazenada no disco. O porquê da memória swap precisar existir é simples: o sistema operacional precisa de memória para funcionar, e se a memória acabar, o sistema falha. O swap fica como uma reserva emergencial caso a memória RAM acabe. A memória swap era bastante útil em tempos passados onde memória RAM era algo mais escasso. Hoje em dia, tanto a RAM quanto espaço em disco estão baratos. É sempre recomendado utilizar swap, mesmo com muita memória RAM.

O swap pode ficar tanto em uma partição, quanto em um arquivo no disco. No caso de ficar numa partição em um disco comum (não-SSD), recomenda-se colocar a partição no início do disco, assim a leitura durante a rotação do disco magnético é mais rápida. No caso de partições em disco SSD, tanto faz pois não há rotações como um disco comum. Algumas distribuições, como Debian e Ubuntu, tem no instalador uma opção para colocar a partição no início do disco.

Importante: lembre-se que o swap é bem mais lento que a memória RAM. Se você colocar swap demais num sistema e começar a usá-lo muito você vai ganhar uma grande de uma lentidão! (muita lentidão em discos convencionais e mesmo assim lentidão em discos SSD)

*No Windows
No sistema da Microsoft o SWAP é um arquivo dentro da raiz do sistema (C:/) chamado PAGEFILE.SYS e ele é criado sem que você saiba durante a instalação do Windows, normalmente colocando a mesma quantidade de memória RAM que você tem no computador realmente, ou seja, se você tem 2GB RAM, vai ter 2048 MB no PAGEFILE.SYS, se tiver 4GB de RAM vai ter mais ou menos 4096 MB de SWAP e assim por diante, sendo que é possível alterar esses valores para mais ou para menos ou mesmo desabilitar o SWAP.


Paginação

A paginação permite que o programa possa ser espalhado por áreas não contíguas de memória. Com isso, o espaço de endereçamento lógico de um processo é dividido em páginas lógicas de tamanho fixo e a memória física é dividida em páginas com tamanho fixo, com tamanho igual ao da página lógica. Nisso, o programa é carregado página a página, cada página lógica ocupa uma página física e as páginas físicas não são necessariamente contíguas. 
O endereço lógico é inicialmente dividido em duas partes: um número de página lógica (usado como índice no acesso a tabela de páginas, de forma a obter o número da página física correspondente) e um deslocamento dentro da página. Não existe fragmentação externa, porém existe fragmentação interna (Ex: um programa que ocupe 201kb, o tamanho de página é de 4 kb, serão alocadas 51 páginas resultando uma fragmentação interna de 3kb). Além da localização a tabela de páginas armazena também o bit de validade, (1 ou TRUE) se a página está na memória (0 ou FALSE) se a página não está na memória. 
E a transferência das páginas de processo podem ser transferidas para a memória por demanda, levando apenas o que é necessário para a execução do programa ou por paginação antecipada, onde o sistema tenta prever as páginas que serão necessárias à execução do programa.

Referências bibliográficas:
http://queconceito.com.br/memoria-ram       
                                           http://queconceito.com.br/memoria-rom
                                           http://www.devin.com.br/linux-swap/
                  


