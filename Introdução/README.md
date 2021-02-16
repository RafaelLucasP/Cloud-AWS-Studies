
# Uma breve introdução a Cloud Computing

## O que é Cloud Computing ?

São serviços prestados por empresas, geralmente de grande porte, relacionados a infraestrutura e serviços de TI, basicamente são meios de alugar uma infraestrutura de um data center, reduzindo os custos para o consumidor.

Gerir a infraestrutura de uma empresa gera alto custo e geralmente investimentos desnecessários, hardware super dimensionado, muitos switch e investimentos nas estruturas de rede, além dos altos custos de uma estrutura física, manutenção e protocolos de segurança. Cloud computing vem para gerir esse segmento, disponibilizando recursos de TI sob demanda (você paga pelo que usa) por meio da internet, dessa forma o contratante não tem mais um alto investimento em um data center próprio, ou pelo menos reduz drásticamente esses custos, contando com uma estrutura na nuvem com alta escalabilidade e flexibilidade, de forma que os gasto são apenas os necessários.


## Quais as vantagens de usar Cloud Computing ?

- **Capital expense *vs* Varible expense**

> Contextualizando *Capital expense* em português despesas de capital, e quer dizer que você sabe exatamente o quanto vai gastar em um negócio. Já *Varible expense* ou despesas variáveis, e sugestivamente quer dizer que você não terá total controle sobre os seus gastos reais e que estes podem variar de acordo com o tempo.
> Aplicando estes conceitos, no sistema tradicional, no qual a empresa tem um Data Center local, ela não tera total controle sobre seus gastos, podendo gastar muito mais do que o esperado em uma manutenção por exemplo (Varible expense).
> Porém utilizando Cloud o contratante terá controle total sobre seus gastos, dado que sistemas de Cloud geralmente trabalham com custos sob demanda, portanto, serviços de manutenção, segurança, dentre outros são de responsabilidade do provedor, o contratante apenas gerencia sua infraestrutura e seus dados.

- **Econimies of scale**

> Serviços de Cloud se beneficiam muito com o crescimento de usuários, quanto mais pessoas migram para um serviço de Cloud, menor o custo dos seus serviços, dado que muitos usuários geram uma maior demanda possibilitando a comprar hardware por um preço menor, além de alavancar a produção de novos serviços pelo provedor.

- **Guessing capacity**

> Nos data centers tradicionais uma prática comum era o guessing ou a adivinhação, as empresas não tinham meios de calcular a demanda de um determinado serviço, e acaba utilizando hardwares super dimensionados para que o sistema opere com folga e caso aconteçam picos de acesso seu sistema continue estável. Essa prática gera um custo financeiro e de tempo elevado, obrigando a empresa a fazer um investimento em algo que não trará retorno.
> Quando se utiliza Cloud voce consegue uma maleabilidade e agilidade incomparavél, podendo adaptar o hardware conforme a demanda em questão de segundos, não necessitando fazer investimentos sem retorno.

- **Speed and Agility**

> Como citado no ponto anterior, velocidade e agilidade são vantagens explicitas de se usar Cloud. A facilidade de fazer upgrades de hardware, em questão de minutos é extremamente superior ao processo de um data center local, no qual você teria que comprar novos componentes do sistema, contratar um técnico responsavél por esses upgrades, além das questões logísticas.

- **Montaining data center**

> Com um sistema de cloud não existem mais as preocupações com a estrutura física do Data Center, principalmente manutenção, esse serviço é feito automaticamente pela empresa provedora, além da alta disponibilidade e a perda de dados praticamente nula.

- **Live**

> Provedores de cloud permitem que você monte sistemas, servidores ou suba aplicações em quetão de minutos, as vezes até em segundos! Isso faz com que o contratante tenha um Data Center altamente escalável, ágil, barato e eficiente.

- **agility**

> Gerar um sistema computacional em minutos independente de sua finalidade é uma vantagem imensa, isso cria a facilidade de implantar serviços de tecnologia em um curto espaço de tempo, e da a oportunidade de testar e experimentar novos ambientes sem custos extras.

- **Global deployment**

> Serviços de cloud permitem que você escale suas aplicações de forma global, você pode ampliar suas atividades por novas regiões geográficas expandindo sua infraestrutura globalmente. A maior vantagem desse proccesso é reduzir a latência e a melhora da experiêcia para usuários ao redor do mundo.

## Tipos de Cloud Computing

Cloud pode ser estruturada de várias formas, entre elas temos as principais IAAS,PAAS e SAAS, a aws cobre os 3 modelos que são apresentados a seguir.

- **IAAS - infrastructure as a service**

> IAAS é a disponibilização de uma infraestrutura como um serviço sem conhecimento dos dados que nela trafegam. Isso quer dizer que uma empresa como a AWS por exemplo, disponibiliza sua infra de forma que você consiga montar VM's, armazenamentos e outros serviços, sem que eles tenham acesso aos dados que você disponibiliza nesse serviço.
> Geralmente essa estrutura disponibiliza serviços de recursos de redes, computadores ( máquinas virtuais ou um hardware dedicado) e espaço de armazenamento, oferecendo um alto nivel de flexibilidade e controle de recursos de TI.

- **PAAS - plataform as a service**

> PAAS é a disponibilização de uma plataforma como serviço, dessa forma o contratante não necessita se preocupar com a gerencia da infraestrutura, ela continua existindo, mas o contratante usa apenas uma plataforma que favorece o desenvolvimento e hospedagem de uma aplicação. Dessa forma PAAS é voltado para pessoas que querem se preocupar apenas com a programação e hospedagem de um serviço, e não com a infraestrutura por tras dele.

* **SAAS - Software as a service**

> Neste modelo o contratante não esta interessado em gerir uma infraestrutura, nem com o desenvolvimento, apenas com o software disponibilizado pela empresa.
> Para facilitar podemos citar o Gmail como um exemplo, quando você acessa sua caixa de mensagens, não esta interessado nos Data centers do Google, tão pouco com os algoritmos que rodam por trás desse serviço, seu único intuíto é checar sua caixa de mensagens no aplicativos.
> Portanto essa estrutura oferece um produto final, completo e gerenciado pelo provedor, muitas vezes focado nos usuários finais.

## Cloud Deployments

O sistema de Cloud computing pode ser instaurado de algumas maneiras, sejam elas de forma unanime ou parcial.


- **Public Cloud**

> Este tipo de implantação envolve sempre um *Cloud Provider* (AWS, Azure, Gpc) no qual resite o sistema completo da empresa, dessa forma todos os cuidados com a estrutura física é feita pelo provedor.

**OBS:** Não é um sistema de dados publicos, os dados são sigilosos para o provedor, mas sim um sistema acessível para qualquer um que se interesse.

- **Private cloud(on premise)**

> Opção contrária a Public Cloud, nesse sistema a empresa tem um Data Center local, portanto segue o esquema de um gerenciamento local, com técnicos e estrutura física.

- **Hybrid**

> É a junção entre public e private, as empresas ainda tem operações em Data Centers locais, mais operam muitos sistemas em Cloud.

## Global Infrasctructure

- **Regions**

> Aws trabalha com regiões, basicamente são zonas geográficas nas quais podem existir uma ou mais AZ (availability zone).

- **Availability zone**

> Availability zones ou AZ's são os Data Centers da AWs espalhados pelo mundo, estão necessáriamente situados em alguma das regioes.


