---
title: "shak: uma proposta para descentralização dos serviços de internet"
---

# Motivação

Desde a sua origem, a _internet_ foi projetada para ser uma rede
descentralizada. A grande maioria dos protocolos utilizados na rede não
dependem de pontos centrais para funcionar. De fato, é de conhecimento geral
que, por exemplo, usuários com contas de emails em provedores diferentes podem
trocar mensagens entre si sem qualquer problema.

O mesmo vale para outras aplicações, em especial para aquelas que utilização a
_web_: um blog, rede social ou site de notícias pode estar hospedado em
qualquer provedor, e não existe nenhuma razão técnica pela qual usuários que
utilizam outros provedores de acesso à rede não possam acessá-los.

Apesar disso, existe atualmente uma tendência de centralização da internet. A
imensa maioria dos usuários individuais utilizam contas de email em algum
poucos grandes provedores. O mesmo acontece com utilitários como armazenamento
de documentos/arquivos/fotos, agenda, etc.

# Consequências da centralização da internet

Essa excessiva centralização traz os seguintes problemas para a sociedade.
Entre eles, podemos citar:

* **Riscos à privacidade.**
  A quantidade de informações pessoais fornecidas a serviços _online_
  centralizados por uma quantidade imensa de pessoas faz com que estes serviços
  representem um risco muito grande à privacidade destas pessoas. Diversos
  destes provedores mencionam explicitamente em seus termos de serviço que
  informações pessoais serão usadas para fins de marketing como exibição de
  propaganda, e não há forma de saber se são feitos outros usos dessas
  informações. Mesmo com a premissa de que os provedores de serviços são
  confiáveis, eventuais problemas de segurança em seus sistemas podem deixar
  muitas informações pessoais de muitos usuários à mercê de atacantes
  mal-intencionados (_crackers_, criminosos, que são popular e incorretamente
  denominados de _hackers_). Se essas informações estivessem dispersas em
  diversos provedores de serviços, uma eventual invasão afetaria uma quantidade
  muito menor de pessoas.

* **Subordinação dos usuários aos provedores**.
  Os grandes provedores de serviços acumulam uma quantidade excessiva de poder
  sobre a sociedade. Uma vez que a imensa maioria dos usuários da internet usa
  os seus serviços, estas empresas têm a capacidade de unilateralmente definir
  o que é e o que não é possível com base puramente em seus interesses
  comerciais.

* **Pontos centrais de falha**.
  Provedores centralizados também se tornam pontos centrais de falha, e uma
  eventual indisponibilidade de seus serviços podem consequências econômicas
  gravíssimas. Na medida em que mais e mais pessoas e negócios dependem do seu
  bom andamento de suas atividades, os riscos à economia mundial se tornam cada
  vez maiores.

Mesmo que toda a sociedade tivesse plena consciência destes problemas causados
pela centralização dos serviços digitais, a maioria dos usuários ainda
continuaria utilizando-os, devido a um fator que acaba sendo decisivo na adoção
de provedores de serviço: a conveniência. Qualquer solução para esta questão
precisa ser no mínimo tão conveniente quanto as alternativas centralizadas
existentes na atualidade.

Este projeto visa fornecer uma alternativa à centralização da internet através
de uma solução que elimina barreira técnica para que usuários interessados
possam ter servidores próprios com aplicações sem a necessidade de conhecimento
técnico especializado. Esta solução está também norteada na maior conveniência
possível, sem sacrifício da segurança e proteção à privacidade.

# Causas da centralização da internet

Nos últimos anos a demanda por soluções na internet vem crescendo de forma
impressionante. Por um lado, o acesso à internet aumenta mais e mais, tanto em
função do aumento da disponibilidade de conexões de banda larga, quanto a
explosão na utilização de dispositivos móveis.

Em paralelo, o tecnologia para desenvolvimento de soluções na internet avança a
passos largos, tanto no que diz respeito a possibilidades, quanto no que diz
respeito à complexidade necessária para tornar novas funcionalidades possíveis.
Serviços de alta sofisticação implicam numa alta complexidade de
desenvolvimento e manutenção.

Esta complexidade faz com que a implantação e manutenção de serviços exija
conhecimento técnico especializado. Para organizações, isto implica num maior
custo para manter sistemas e aplicações. Para indivíduos, isto quase sempre
impossibilita a manutenção de serviços próprios e leva à procura por serviços
"gratuitos". Estes serviços podem ser gratuitos do ponto de vista estritamente
financeiro e imediato, mas os termos com os quais os usuários concordam, muitas
vezes inadvertidamente, ao usar estes serviços, permitem aos provedores fazerem
uso de informações pessoais dos usuários que podem vir a ter um alto custo
tanto para o próprio indivíduo quanto para a sociedade em geral.

# Software livre como uma alternativa para a descentralização

O conceito de Software Livre foi cunhado na década de 1980. Um Software Livre
fornece aos seus usuários 4 liberdades fundamentais:

* Executar o software para qualquer finalidade;
* Estudar o funcionamento do software e adaptá-lo às necessidades do usuário;
* Redistribuir cópias do software;
* Distribuir cópias de versões modificadas do software.

Desde lá, o software livre se tornou parte importante da infraestrutura da
internet. [Segundo a consultoria
Netcraft](http://news.netcraft.com/archives/category/web-server-survey/), em
Junho de 2015 mais da metade dos servidores da internet utilizam servidores
HTTP livres. Os dos principais navegadores web (Firefox e Google Chrome) são
softwares livres, assim como é livre o sistema operacional Android, utilizado
na maioria esmagadora dos _smartphones_ disponíveis no mercado.

Sistemas operacionais livres, como o [Debian
GNU/Linux](http://www.debian.org/), permitem que usuários com conhecimento
técnico para tal possam hospedar os seus próprios serviços de internet,
utilizando exatamente a mesma tecnologia que é empregada nos maiores sites
profissionais.  Todo tipo de serviço pode ser hospedado com sistemas
operacionais livres, mas esta realidade ainda está longe do usuário final.

O usuários final tem a opção de ou contratar um técnico qualificado para
fazê-lo, no entanto esta é uma barreira que é muito mais difícil de transpor,
por não ser conveniente em comparação com a alternativa: simplesmente utilizar
serviços "gratuitos" de grandes _players_ da internet, em troca de acesso às
suas informações pessoais, cedidas de forma consciente ou não, e com todas as
consequências negativas já mencionadas anteriormente.

# Barateamento da infraestrutura

Um outro impeditivo para que usuários possam hospedar os seus próprios serviços
de internet é o custo de manutenção do servidor em si, e de sua conectividade.
Nos últimos anos, no entanto, este fator vem perdendo relevância em função de
dois fenômenos. Por um lado, o barateamento do acesso a servidores virtuais
privados decorrente os avanços da "computação em nuvem". Por outro lado, a
disponibilidade de servidores físicos de dimensão reduzida e baixo consumo de
energia, em conjunto com o barateamento de conexões de banda larga à internet.

As inovações na computação em nuvem (especialmente em virtualização e
armazenamento) fazem com que atualmente seja possível alugar servidores
virtuais privados (VPS, da singla em inglês "_virtual private server_") em
provedores comerciais por valores tão baixos quanto 5 dólares por mês. Mesmo
que o valor não pareça ser tão baixo, a depender do serviço um único VPS pode
servir uma quantidade razoável de usuários, possibilitando que um grupo de
usuários possam dividir este custo.

Por outro lado, servidores virtuais em data centers comerciais também deixam
uma pula atrás da orelha dos usuários mais preocupados com a sua privacidade. A
segurança e a integridade dos dados hospedados em um VPS estão sujeitos à
confiabilidade do provedor: sendo o dono do _hardware_ onde o VPS está
hospedado, o provedor teria em tese acesso total a tudo que está hospedado nele
mesmo num VPS individual.

Em situações onde nem um VPS oferece as garantias de privacidade necessárias,
usuários têm ainda a alternativa de hospedar os serviçoes em hardware próprio
em casa, utilizando a conectividade oferecida por uma conexão banda larga.
Existem hoje no mercado uma grande quantidade de servidores de dimensão
reduzida (e.g. do tamanho de um modem ADSL, ou menores), que possuem um consumo
de energia mínimo. Projetos como
[Freedombox](http://www.freedomboxfoundation.org/) apostam em servidores
físicos e privados hospedados em domicílios, em conjunto com a utilização de
criptografia, como uma saída para privacidade de fato nas comunicações
_online_.

# Proposta: shak

Este projeto visa a desenvolver uma plataforma chamada **shak** cujo objetivo é
facilitar ao máximo que usuários sem conhecimento técnico possam ter os seus
próprios serviços de internet, garantindo sua privacidade e segurança. Esta
plataforma está concebida de acordo com os seguintes princípios:

## Base: pacotes Debian

A plataforma *shak* é baseada no sistema de pacotes do Debian, uma das
distribuições GNU/Linux mais consolidadas e com maior comunidade internacional.

Os pacotes do Debian fornecem atualizações consistentes de correção e de
segurança, e são utilizados por uma grande quantidade de usuários que
reportam problemas a serem resolvidos. Porém, para garantirem uma
flexibilidade e suportar diferentes casos de uso, normalmente os pacotes não
realizam a configuração completa do ambiente, deixando os detalhes finais
para o administrador do sistema.

Além disso, normalmente aplicações são compostas de diversos pacotes, e
requerem configurações que dizem respeitos a mais de um deles e que por
consequencia não poderiam ser feitas automaticamente de uma forma sustentável
em nenhum dos pacotes.

## Nova abstração: aplicação

Para resolver as questões que não podem ser resolvidas no nível de pacotes, o
*shak* introduz uma nova abstração: a *aplicação*. Uma aplicação geralmente
contém mais de um pacote, e é responsável por toda a configuração, inclusive
configurações em múltiplos pacotes.

Concretamente, uma vez que o usuário seleciona uma determinada aplicação para
ser instalada, os pacotes necessários são instalados e as configurações
necessárias são feitas de forma automática, fornecendo de fato um "instalador
de um clique" para aplicações suportadas.

Todas as configurações são feitas de forma consistente utilizando um framework
comum, buscando o maior nível de segurança possível, e assumindo premissas que
não poderiam ser assumidas no nível da abstração *pacote*.

## Diferencial para outras soluções existentes

Existem outras soluções disponíveis para "instaladores de um clique" no
mercado, mas o *shak* se diferencia delas nos seguintes aspectos:

* O *shak* pode ser implantando em um VPS na nuvem ou em servidores físicos
  próprios, a critério do usuário.

* O *shak* reutiliza o trabalho dos mantenedores Debian, que fornecem pacotes
  de alta qualidade.

  Por outro lado, apenas software que esteja empacotado no Debian estará
  disponível, mas isso pode ser visto de forma positiva também: o shak
  fornecerá um incentivo para que ainda mais software esteja disponível no
  Debian, o que é um benefício coletivo para o ecossistema do software livre, e
  para os seus usuários.

* O *shak* reutiliza a infraestrutura do projeto Debian.

  O Debian possui espelhos do seu repositório espalhados por todo o mundo,
  fornecendo links para downloads mais rápidos aonde quer que o usuário esteja.

  Atualizações de defeitos e correções de segurança realizadas no Debian
  estarão automaticamente disponíveis para usuários do shak de forma
  transparente.

  Além disso, o próprio shak estará disponível como um pacote dentro do próprio
  repositório oficial do Debian.

## Andamento atual do projeto

No momento, o projeto vem sendo desenvolvido nas horas vagas, e portanto num
ritmo aquém do ideal. Apesar disso, já possuimos um protótipo funcional, capaz
de configurar 3 aplicações:

* Websites em HTML estático.
* [Wordpress](http://www.wordpress.org/), uma ferramenta poderosa para websites
  e blogs.
* [Owncloud](https://owncloud.org/), uma plataforma de "nuvem pessoal" com
  funcionalidades como armazenamento de arquivos, agenda, edição de documentos
  online, etc.

Suporte ao Wordpress e ao Owncloud foram desenvolvidos por um estudante que
está trabalhando no projeto como parte do programa [Google Summer of
Code](https://developers.google.com/open-source/gsoc/) no contexto do projeto
Debian como organização mentora, e sob orientação o líder do projeto shak. Este
estudante também já fez contribuições de melhorias na ferramenta.

Também está em vista a participação de uma estagiária no programa
[Outreachy](https://www.gnome.org/outreachy/) para segundo semestre de 2015,
também no contexto do projeto Debian e sob orientação do líder do projeto shak.

# Cronograma

... _adaptar para cada projeto submetido (?)_


# Orçamento

... _adaptar para cada projeto submetido (?)_
