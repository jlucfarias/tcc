# 3 DESENVOLVIMENTO

Tendo os conceitos citados acima já explorados e destrinchados, deve-se agora compreender o andamento e construção da solução pretendida por este trabalho.

Primeiramente, é preciso compreender a metodologia utilizada no decorrer deste trabalho e de como este trabalho foi organizado por ela. Após isso, serão apresentadas as problemáticas relativas ao uso da internet pela comunidade surda e às ferramentas de auxílio a esse uso. Em seguida será visto uma descrição mais detalhada da solução proposta e, por fim, a construção dos protótipos da ferramenta, objeto deste trabalho, como solução para os problemas apresentados.

## 3.1 METODOLOGIA

O objeto deste trabalho foi construído seguindo as fases típicas de um processo de desenvolvimento de software, a saber (BEZERRA, 2007): a) Levantamento de Requisitos; b) Anáĺise de Requisitos; c) Projeto; d) Implementação; e) Testes e f) Implantação. Para o presente trabalho, foi seguido até a fase de Anáĺise de Requisitos.

A fase de levantamento de requisitos é aquela em que há uma busca pela compreensão do problema, aplicada ao desenvolvimento de software, e tem por finalidade unir as visões dos usuários do software a ser desenvolvido e os desenvolvedores do software (BEZERRA, 2007). Requisitos são características e restrições do produto de software que visam satisfazer as necessidades do usuário e são estabelecidos pelo(s) cliente(s) e usuários do produto (MACHADO, 2018). O detalhamento e descrição dessa fase estão contidos na seção 3.2 deste trabalho onde foi feito um levantamento preliminar das problemáticas relativas ao uso da internet e das ferramentas de tradução automática para Libras por parte da comunidade surda, através dos intérpretes de Libras do Instituto Federal de Educação, Ciência e Tecnologia do Rio Grande do Norte (IFRN).

A fase de análise de requisitos é definida por BEZERRA (2007), como aquela em que é realizado um estudo detalhado dos requisitos levantados e, a partir deste estudo, construir modelos para representar o sistema a ser construído. O detalhamento dessa fase para este trabalho se encontra na seção 3.3 onde foi descrito a proposta de solução para os problemas apontados na seção 3.2 e continuado na seção 3.4, na qual foi inicializado a modelagem das modificações a serem feitas para solucionar os problemas apontados na seção 3.2.

## 3.2 LEVANTAMENTO PRELIMINAR

A fase de levantamento de requisitos, do software construído neste trabalho, consistiu na elicitação das problemáticas no uso da internet pela comunidade surda do IFRN CNAT. Essa elicitação se deu por meio de duas entrevistas (Apêndice A), sendo uma delas uma conversa informal sem qualquer tipo de modelo científico e uma entrevista semi-estruturada, ambas com intérpretes de Libras do IFRN.

A entrevista semi-estruturada foi escolhida por causa da liberdade que há nas respostas por não serem fruto de uma padronização criada pelo entrevistador, é focalizada em um objetivo que dele se confecciona um roteiro com perguntas principais e, a depender das circunstâncias da entrevista, serem feitas perguntas complementares (MANZINI, 1990/1991, p. 154).

Os respondentes dessas entrevistas foram alguns dos intérpretes do IFRN por serem um grupo com contato facilitado e serem o auxílio comunicacional da população surda do IFRN. Mesmo assim, houve alguma dificuldade para marcar as datas de ocorrência das entrevistas por conta da burocracia — foi solicitado um contato prévio com a coordenação dos intérpretes para designar aqueles que fariam as entrevistas —, apresentada em um primeiro momento e pelo tempo de disponibilidade dos intérpretes que é curto devido à necessidade de disponibilidade para a comunidade surda do IFRN.

A primeira entrevista serviu de base para compreensão e primeira visão das opiniões dos intérpretes acerca das problemáticas do uso da Libras na web, mas não será utilizada neste trabalho como fonte de dados por não seguir qualquer modelo ou rigor científico no processo.

O objetivo das perguntas feitas na entrevista é elucidar as problemáticas encontradas pelos surdos repassadas no contato com os intérpretes e compreender de que maneira é possível alterar uma interface web para se adequar às necessidades apresentadas pelos surdos.

A primeira pergunta buscou entender o processo de busca dos surdos para encontrar o conteúdo desejado na internet, independentemente do idioma utilizado no conteúdo. A segunda pergunta procurou catalogar o dispositivo mais utilizado pelos surdos para focalizar qualquer ação nesse dispositivo. A terceira pergunta buscou determinar a opinião geral sobre a acessibilidade da internet para as pessoas surdas e é ela que definiu se as demais perguntas seriam feitas, porque todas as perguntas, a partir da questão de número 4 (quatro) — excluindo a sétima pergunta —, dependiam da certeza de se existia alguma dificuldade para os surdos na utilização da internet no sentido da acessibilidade; caso a resposta fosse positiva para essa pergunta, a entrevista seria encerrada.

A quarta pergunta procurou encontrar uma lista das dificuldades encontradas pelos surdos no processo de utilização da internet. A quinta pergunta procurou perceber as soluções utilizadas pelos surdos para resolver os problemas apresentados na pergunta anterior. A sexta pergunta buscou descobrir se os surdos fazem uso de alguma ferramenta externa, seja o auxílio de um intérprete ou uma solução tecnológica, para melhorar a experiência deles com a internet. A sétima pergunta procurou descobrir como os surdos conseguem utilizar a internet sem auxílio de alguma ferramenta ou auxílio externo, mas essa pergunta só podia ser feita quando a resposta para a pergunta anterior fosse de que eles não utilizam ferramentas ou auxílio.

A oitava pergunta buscou listar todas as ferramentas que os surdos utilizam para melhorar a compreensão dos conteúdos na internet. A nona pergunta serviu como avaliação de todas as ferramentas apresentadas na pergunta anterior utilizando como escala valores numéricos de 1 (um) a 5 (cinco), sendo 1 equivalente a “muito ruim” e 5 equivalente a “muito bom”. A décima pergunta foi feita caso houvesse alguma ferramenta que não obteve nota 5 (cinco) e busca criar uma lista dos problemas das ferramentas citadas anteriormente.

### 3.2.1 Resultados do Levantamento Preliminar

No total foram entrevistados cinco intérpretes do IFRN CNAT que terão seus nomes omitidos porque a pessoalização das respostas não é relevante para o presente trabalho. Todos os respondentes responderam às três primeiras perguntas e a partir daí, houveram diferenças entre os entendimentos acerca das questões.

As respostas da primeira pergunta foram feitas no entendimento da possibilidade do acesso, o que evidencia uma falta de compreensão do sentido da pergunta como apresentado na seção anterior e esse mal entendimento se deu pela falta de noção de como conduzir uma entrevista por parte do pesquisador deste trabalho. Mesmo assim, todas as respostas foram dadas no sentido de que há a possibilidade de uso da internet pelos surdos, independente de como e onde acessam.

Na segunda pergunta, as respostas foram unânimes em elencar que os dispositivos móveis são os dispositivos mais utilizados para o acesso a internet por parte dos surdos.

Nas respostas da terceira pergunta houve uma ruptura entre as respostas com alguns respondendo que a internet é um ambiente acessível para os surdos e outros dizendo que a internet não é um ambiente acessível, como pode ser visto no gráfico de respostas da terceira24 pergunta (Figura 2), em que três responderam que a internet é acessível e dois responderam que a internet não é acessível.

Figura 2 – Gráfico de Respostas da Terceira Pergunta
Fonte: Elaboração própria em 2022.

Um dos motivos que pode ter resultado nessa diferenciação nas respostas pode ser encontrada já nas respostas da primeira pergunta, pois todos responderam que há a possibilidade de uso da internet por parte dos surdos, fazendo disso a definição da palavra acessibilidade para eles, mas aqueles que responderam que a internet não é um ambiente acessível parecem ter confrontado essa definição com a existência de ferramentas de auxílio para a compreensão dos conteúdos da internet para os surdos, o que pode ser visto com a citação indireta da existência dessas ferramentas nas respostas negativas. Caso as respostas fossem positivas para essa pergunta, a entrevista seria encerrada para não causar desentendimento, considerando que a pergunta seguinte intenta elencar o que motivou a resposta negativa à terceira pergunta.

As respostas da quarta pergunta foram unânimes em citar que o problema da acessibilidade é um dos maiores para os respondentes.Um respondente em especial, cujo nome fictício será A. O., complementou dizendo que as páginas web, normalmente, não são adaptadas linguisticamente, ou seja, não possuem qualquer consideração em relação a Libras.

As respostas para a quinta pergunta foram semelhantes ao dizer que a forma comum de solução são pessoas conhecidas que conseguem se comunicar com eles e que entendem do conteúdo que eles possuem dúvidas.

As respostas para a sexta pergunta foram congruentes em dizer que há ferramentas para auxiliar os surdos na utilização da internet e o mais citado delas foi a aplicação HandTalk e houve também um complemento a essa resposta, por parte do respondente A. O., dizendo que essas ferramentas são rejeitadas pelos surdos pela utilização de representações humanas em 3D, chamados de avatares.

Só houve uma resposta para a sétima pergunta, feita pelo respondente A. O., e nela é possível ver que os surdos, mesmo com dificuldades, buscam acessar os conteúdos de qualquer maneira.

As respostas à oitava pergunta foram bem divididas com um respondente retomando as ferramentas elencadas na sexta pergunta, com a adição do dicionário, e outro respondente vai na contramão dizendo que não há uso comum de ferramentas para compreensão do conteúdo, pois eles aprendem vocabulário com outras pessoas, mas que também podem utilizar um dicionário trilíngue ou um glossário.

A décima pergunta só teve um respondente, A. O., pois foi o único a dar uma nota diferente de cinco (entendido como “muito bom”) para alguma das ferramentas por ele citada. A. O. disse que ambas as ferramentas citadas por ele, HandTalk e ProDeaf, possuem um vocabulário restrito e a falta de consideração em relação ao contexto em que a palavra foi empregada.

## 3.3 A PROPOSTA DE SOLUÇÃO

Considerando as respostas dadas na entrevista preliminar (Apêndice A) e a fundamentação teórica executada no decorrer deste trabalho, foi percebido que a existência de ferramentas de auxílio aos surdos para uso da internet se dá pela baixa ou falta de acessibilidade nos sites da web em decorrência da não utilização da Libras nos conteúdos, seja na construção do conteúdo ou na adequação do conteúdo para a Libras. Ferramentas, como o HandTalk, traduzem os conteúdos já existentes sem necessitar de qualquer alteração no conteúdo, dessa forma caberia apenas à ferramenta servir de intermédio comunicacional entre o conteúdo e a pessoa surda, dessa maneira é diminuído o trabalho tomado pelos criadores de sites para traduzir e permitir a compreensão dos conteúdo pelos surdos. Porém, como visto nas respostas da entrevista preliminar (Apêndice A), essa facilitação acaba ocasionando26 problemas de contextualização pelas limitações das ferramentas e adiciona uma dependência com a ferramenta por considerar que a tradução feita será fiel. E esses problemas ocasionam desentendimentos por parte dos surdos em relação ao conteúdo exposto.

Para que esses problemas não ocorram, é preciso utilizar-se do papel dos intérpretes na condição de auxiliares do entendimento do português para os surdos e, ao mesmo tempo, na facilidade das ferramentas para quem possui conteúdo já publicado e não deseja fazer qualquer alteração nele.

O objetivo deste trabalho consiste na idealização de uma ferramenta que utilizará de vídeos pré-gravados, elaborados pelo autor do conteúdo, para traduzir o conteúdo já existente.

Os vídeos serão utilizados por dois motivos principais: a) garantir maior representação para os surdos, pois, como mostrado por Moraes et al (2018), os surdos rejeitam as ferramentas que utilizam representações humanas em 3D e b) impedir quaisquer problemas de tradução, pois o trabalho de tradução prévia com profissionais especializados intenta contextualizar e garantir o uso de sinais adequados para significação mais aproximada com o sentido do texto a ser traduzido. Para ter acesso a esses vídeos, a ferramenta buscará na estrutura do documento do site por caminhos válidos para vídeos externos nos elementos do conteúdo selecionado pelo usuário e, caso o caminho seja válido, ou seja, o vídeo seja possível de ser reproduzido, então a ferramenta reproduzirá o vídeo num local definido na interface, baseado na interface utilizada pelas ferramentas existentes de mesmo propósito. A ferramenta utilizará dos mesmos recursos visuais já utilizados pelas ferramentas de tradução para que se mantenha uma padronização desses recursos e sejam mais facilmente percebidos pelos surdos como um conteúdo acessível.

## 3.4 MODELAGEM DO PROTÓTIPO

Para compreender melhor como será e quais são alguns dos recursos dessa ferramenta, foi escolhido o 1paradigma da prototipação porque com ele seria possível alcançar esse objetivo e utilizaria dos conhecimentos já apreendidos pelo autor deste trabalho. Para isso, foi feita uma modelagem do resultado de uma situação de uso da ferramenta em que foi dividido em duas etapas: a primeira com a criação de um protótipo de baixa fidelidade para compreensão rápida da proposta, elencando os elementos obrigatórios para a ferramenta, e a segunda etapa com a criação de um protótipo de alta fidelidade para exemplificar o uso da ferramenta em um site real para demonstrar de maneira mais fiel como será o uso da ferramenta; nessa etapa foi escolhido o site do Sistema Unificado de Administração Pública (SUAP) do IFRN para exemplificação prática da ferramenta por causa da facilidade de acesso tanto para os entrevistados e os surdos assistidos por eles, quanto para o autor deste trabalho.

Em ambos os grupos foi determinado que apenas os conteúdos do menu lateral e do conteúdo principal da página de dados do aluno seriam representados, por se tratarem de páginas mais comuns para o autor deste trabalho.

Os protótipos alteram o layout atual para comportar o elemento de reprodução de vídeos e mostrar como será o uso de vídeos com gravação prévia no local utilizado pelas ferramentas de tradução para a Libras, a saber: o canto inferior direito da tela dos celulares; esses vídeos servirão para explicação dos elementos e textos presentes na página utilizando a Libras.

Todos os protótipos elaborados foram feitos usando a ferramenta Figma, por se tratar de uma ferramenta conhecida pelo autor deste trabalho, estão disponíveis para visualização pública no seguinte site: https://github.com/jlucfarias/tcc/tree/master/prototypes; e foram contruídos baseados no uso em dispositivos móveis por serem os dispositivos mais utilizados pelos surdos como visto na entrevista (Apêndice A).

### 3.4.1 Protótipo de Baixa Fidelidade

O primeiro protótipo do menu lateral (Figura 3) mostra o conteúdo do menu lateral, marcado com o número 1 em vermelho, com os itens dispostos na vertical e um item selecionado, marcado com o número 2 em vermelho e uma borda ao redor do elemento selecionado, que acionará a tradução do conteúdo na janela de tradução, marcada com o número 3 em vermelho. Esta janela é a região onde serão reproduzidos os vídeos pré-gravados e ficará posicionada acima de todo o conteúdo da página.

Figura 3 – Protótipo de Baixa Fidelidade do Menu Lateral
Fonte: Elaboração própria em 2022.

O primeiro protótipo da página de dados do aluno (Figura 4) mostra o conteúdo da página, marcado com o número 1 em vermelho, que ao ter o texto selecionado, marcado com o número 2 em vermelho e uma borda ao redor do elemento selecionado, acionará a tradução do conteúdo na janela de tradução, marcada com o número 3 em vermelho.

Figura 4 – Protótipo de Baixa Fidelidade da Página de Dados do Aluno
Fonte: Elaboração própria em 2022.

### 3.4.2 Protótipo de Alta Fidelidade

O segundo protótipo do menu lateral (Figura 5) mostra o menu lateral do site do SUAP quando o usuário já entrou com suas credenciais e requisitou a aparição do menu, que inicialmente está escondido. Esse protótipo mostra a diferença desse elemento sem a utilização da ferramenta aqui proposta (à esquerda) e com a utilização da ferramenta (à direita). Nele é possível ver o conteúdo selecionado, Boletins em azul dentro do Submenu Ensino, e a janela de tradução em um momento da reprodução do vídeo da tradução do conteúdo do item selecionado.

Figura 5 – Protótipo de Alta Fidelidade do Menu Lateral
Fonte: Elaboração própria em 2022.

O segundo protótipo da página de dados do aluno (Figura 6) mostra o conteúdo da página de dados do aluno do SUAP. Esse protótipo também mostra a diferença dessa página sem a utilização da ferramenta aqui proposta (à esquerda) e com a utilização da ferramenta (à direita). Nele é possível ver que o botão com o texto Editar foi selecionado e isso aciona a tradução, que pode ser vista na janela de tradução posicionada no canto inferior direito.

Figura 6 – Protótipo de Alta Fidelidade da Página de Dados do Aluno
Fonte: Elaboração própria em 2022.

Por fim, é necessário retomar as problemáticas percebidas a partir das experiências empíricas do autor deste trabalho e da entrevista (Apêndice A) realizada que, juntos, resultaram na percepção de que há a necessidade de ação(ões) para melhoria ou alteração da situação atual das ferramentas existentes de tradução para a Libras. Essa(s) ação(ões) se deu(ram) na elaboração descritiva de uma ferramenta que utilizasse a identificação dos surdos com pessoas reais em detrimento de avatares e o auxílio dos intérpretes na compreensão dos conteúdos da web para os surdos (como visto na seção 3.2.1 deste trabalho) para atingir uma melhoria na compreensão dos conteúdos em português pelos surdos e esse objetivo pode ser atingido no uso de vídeos pré-gravados pois, diferente das ferramentas atuais, é a forma que possibilita não só essa identificação e melhoria na compreensão, mas impede de atingir os erros de comunicação descritos neste trabalho. Sem os erros de comunicação apresentados e com as melhorias realizadas pelo uso dessa solução, é possível perceber que a existência, idealização e construção de uma ferramenta que utiliza algo diferente das ferramentas atuais de tradução para a Libras e, ao mesmo tempo, utilize de pessoas reais é possível.
