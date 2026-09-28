# toro-mapa-de-alertas-e-riscos
Trabalho acadêmico sobre a falta de conhecimento acerca dos riscos geológicos, apresentado à Pontifícia Universidade Católica de Minas Gerais, para avaliação na disciplina de Trabalho Interdisciplinar: Aplicações Web Front-End, dos cursos de Sistemas de Informação e Análise e Desenvolvimento de Sistemas.
- **Projeto:** Toró — Mapa de Riscos e Alertas

- **Repositório GitHub:** [toro-mapa-de-alertas-e-riscos](https://github.com/lailamoselli/toro-mapa-de-alertas-e-riscos/tree/main)

- **Membros da equipe:**
  - Bárbara Luiza Oliveira de Souza
  - Cristiane Gonçalves Vieira
  - Emilly Victoria Soares Vieira
  - Laila Roberta Moselli dos Reis
  - Sophia de Fatima Simoes Almeida
    
**1 INTRODUÇÃO**

Os riscos geológicos e hidrológicos fazem parte da realidade de diferentes áreas urbanas e envolvem aspectos relacionados à prevenção, ao monitoramento e à comunicação de situações que podem afetar a população. Nesse contexto, compreender como as informações sobre esses riscos são identificadas, organizadas e disponibilizadas torna-se relevante para o desenvolvimento de soluções que aproximem esses dados das necessidades das pessoas.

A partir dessa perspectiva, este trabalho apresenta o desenvolvimento do software Toró — Mapa de Riscos e Alertas. A proposta tem como base a investigação dos riscos geológicos e hidrológicos em Belo Horizonte, Contagem e demais áreas da Região Metropolitana, considerando diferentes públicos e suas formas de acesso e compreensão das informações relacionadas a essas ocorrências. O software busca reunir e apresentar essas informações de maneira clara, localizada e acessível, oferecendo alertas preventivos e de emergência, identificação de áreas de risco, orientações de segurança, indicação de locais seguros e apoio ao deslocamento e à evacuação em situações de perigo.

Dessa forma, o projeto busca utilizar a tecnologia como meio de aproximar informações relacionadas aos riscos da população, reunindo em uma única solução recursos que contribuam para o acesso à informação, a prevenção e a segurança diante de possíveis situações de perigo.

**2 CONTEXTO DO PROJETO**

**2.1 PROBLEMA**

Desastres associados a eventos climáticos extremos representam desafios recorrentes entre os fenômenos naturais de maior potencial de impactos sociais, econômicos e ambientais, causando perdas humanas e materiais. Entre essas ocorrências, destacam-se os deslizamentos, os alagamentos e as inundações, cuja frequência e intensidade têm aumentado nas últimas décadas. A precipitação é um dos principais fatores associados à ocorrência desses eventos, tornando o monitoramento pluviométrico e a utilização de dados provenientes de sistemas de monitoramento importantes para a identificação, prevenção e gestão de riscos em áreas urbanas. 

Belo Horizonte, Contagem e outros municípios da Região Metropolitana possuem áreas sujeitas a riscos geológicos e hidrológicos, principalmente durante períodos de chuvas intensas. Em Contagem, por exemplo, a Defesa Civil registrava, em 2024, cerca de 255 pontos considerados de risco, sendo 150 relacionados a riscos hidrológicos e 105 a riscos geológicos. A existência de áreas já identificadas e monitoradas demonstra que parte significativa do problema é conhecida pelos órgãos responsáveis, mas não elimina a exposição da população às ocorrências.

Entre essas áreas, a Avenida Tereza Cristina e seu entorno constituem um caso relevante pela recorrência histórica das inundações associadas ao Ribeirão Arrudas. A região será utilizada como principal recorte investigativo deste trabalho, permitindo analisar de forma mais aprofundada um problema que também se manifesta em outras áreas de Belo Horizonte, Contagem e Região Metropolitana.

As inundações na Avenida Tereza Cristina não estão relacionadas apenas à quantidade de chuva que cai diretamente sobre a via. A avenida está inserida na bacia hidrográfica do Ribeirão Arrudas, que recebe águas provenientes de diferentes áreas de Belo Horizonte e Contagem. Os córregos Ferrugem e Riacho das Pedras, localizados em Contagem, por exemplo, são afluentes desse sistema. A relação entre esses cursos d'água e as enchentes na Tereza Cristina levou à implantação de obras de contenção de cheias destinadas a reduzir o volume de água que segue em direção ao Ribeirão Arrudas.

Somam-se a essa dinâmica fatores característicos da urbanização, como a impermeabilização do solo, a ocupação de áreas próximas aos cursos d'água, as alterações realizadas na rede de drenagem e as características do relevo. Durante chuvas intensas, a menor capacidade de infiltração favorece o escoamento superficial e a concentração da água nos sistemas de drenagem e cursos d'água, contribuindo para o aumento rápido da vazão e para a possibilidade de inundação das áreas próximas.

A recorrência desse problema na Avenida Tereza Cristina é registrada constantemente, entretanto, este problema não se limita à existência física das áreas vulneráveis. Existe também o desafio de fazer com que informações sobre uma situação de perigo cheguem às pessoas expostas de maneira clara, localizada e em tempo adequado. Mesmo em regiões já mapeadas e monitoradas, diferentes perfis permanecem sujeitos ao risco: moradores e comerciantes que convivem diariamente com a região, trabalhadores que dependem das vias para seus deslocamentos e motoristas ocasionais que podem desconhecer completamente o histórico de determinado local.

Dessa forma,o problema investigado envolve tanto a recorrência dos riscos geológicos e hidrológicos quanto a necessidade de que informações confiáveis sobre essas ocorrências sejam comunicadas de forma localizada, compreensível e em tempo útil, permitindo que diferentes públicos reconheçam uma situação de perigo antes que sua exposição ao risco se agrave.

**2.2 OBJETIVOS**

Desenvolver um software voltado ao monitoramento e à prevenção de riscos geológicos e hidrológicos em Belo Horizonte e Contagem, capaz de fornecer alertas preventivos sobre condições que possam favorecer a ocorrência de desastres e avisos diante de situações de emergência. O software busca informar os usuários em tempo hábil, contribuindo para a prevenção, o afastamento ou a evacuação segura de áreas de risco e, consequentemente, para a redução de possíveis danos e perdas. Para atender a essa proposta, será desenvolvido o software *Toró — Mapa de Riscos e Alertas*. 

**2.2.1 Objetivos específicos**

Investigar a Avenida Tereza Cristina e seu entorno como principal área de estudo, buscando compreender as áreas vulneráveis, os fatores associados aos riscos geológicos e hidrológicos, as condições meteorológicas que podem favorecer essas ocorrências, os mecanismos de monitoramento existentes e as necessidades de informação das pessoas que vivem, trabalham ou circulam pela região, a fim de identificar quais informações devem ser apresentadas aos usuários de forma clara, rápida e localizada.

- Desenvolver uma forma de visualização das áreas de risco por meio de mapa, permitindo a consulta de regiões vulneráveis, áreas afetadas, ocorrências, locais seguros e pontos de apoio, considerando inicialmente a Avenida Tereza Cristina e seu entorno e possibilitando a atualização das informações conforme novos dados estejam disponíveis.
- Estruturar alertas preventivos e localizados, utilizando a geolocalização e informações de monitoramento para informar os usuários com antecedência quando forem identificadas condições que possam favorecer situações de perigo, evitando que os avisos se limitem a informações amplas sobre chuva ou risco no município.
- Disponibilizar avisos em situações de emergência, apresentando informações e orientações que auxiliem os usuários no afastamento ou na evacuação segura de áreas de risco, além de prever recursos de emergência para facilitar o contato com serviços de apoio e a comunicação com familiares ou contatos previamente cadastrados.
- Investigar formas de apoiar deslocamentos mais seguros em situações de risco, auxiliando os usuários na identificação de áreas afetadas, locais que devem ser evitados e possíveis rotas alternativas, quando houver informações confiáveis disponíveis.
- Disponibilizar recomendações e orientações sobre como agir antes, durante e após situações de perigo, além de informações sobre redes, serviços de apoio, locais seguros e pontos de referência disponíveis.
- Possibilitar o cadastro de usuários, permitindo a personalização de recursos relacionados à localização, recebimento de alertas e definição de contatos para situações de emergência.
- Possibilitar a participação da comunidade por meio de um canal de relatos e denúncias, permitindo o envio de localização, informações e feedbacks sobre ocorrências ou possíveis áreas de risco ainda não contempladas pelo sistema, submetendo essas informações à triagem e análise antes de sua incorporação definitiva ao mapa ou aos alertas.
- Planejar a integração do software com instituições, serviços e iniciativas que já atuam no monitoramento, gerenciamento e resposta a situações de risco, incluindo Defesa Civil, serviços de emergência e órgãos de Segurança Pública, priorizando o uso de informações confiáveis para a composição e atualização dos mapas, alertas e orientações disponibilizados pelo sistema.
  
**2.3 JUSTIFICATIVA**

A prevenção de desastres associados a riscos geológicos e hidrológicos depende não apenas da identificação das áreas vulneráveis e do monitoramento das condições que podem favorecer essas ocorrências, mas também da capacidade de transformar essas informações em meios que auxiliem a população a reconhecer situações de perigo e agir de forma adequada. Nesse sentido, o acesso a informações confiáveis, compreensíveis e relacionadas ao território constitui um aspecto importante para a prevenção e para a redução da exposição das pessoas ao risco.

Em Belo Horizonte e Contagem, diferentes iniciativas já são utilizadas para o monitoramento, a prevenção e a comunicação desses riscos. Existem áreas oficialmente mapeadas, sistemas de monitoramento, canais de alerta e medidas de sinalização destinadas a informar a população. Em Contagem, por exemplo, além dos 255 pontos de risco registrados pela Defesa Civil em 2024, ações de prevenção incluíram a instalação, em 2025, de 53 placas de alerta e 25 faixas em 16 pontos críticos de alagamento. Essas iniciativas demonstram que o reconhecimento das áreas vulneráveis e a comunicação do risco já fazem parte das estratégias adotadas pelos órgãos responsáveis.

A existência desses recursos, entretanto, também evidencia a diversidade de informações envolvidas na prevenção e na resposta a essas ocorrências. Dados meteorológicos, áreas de risco, alertas, orientações, pontos de apoio e informações sobre ocorrências podem estar associados a diferentes fontes e formas de comunicação. Diante disso, torna-se relevante investigar como essas informações podem ser reunidas e apresentadas de maneira visual, localizada e acessível, de modo que diferentes públicos consigam compreender não apenas a existência de uma situação de perigo, mas também sua localização e as possibilidades de ação diante dela.

A Avenida Tereza Cristina e seu entorno oferecem um contexto adequado para aprofundar essa investigação devido ao histórico de inundações da região e à sua relação com a bacia hidrográfica do Ribeirão Arrudas. Por se tratar de uma área utilizada diariamente por moradores, comerciantes, trabalhadores e motoristas, o impacto de uma ocorrência não se restringe às pessoas que conhecem previamente o histórico da região. A escolha desse recorte permite, portanto, observar tanto as características das áreas vulneráveis quanto às necessidades de informação de diferentes pessoas que podem estar expostas a uma mesma situação de risco.

A partir desse contexto, a proposta concentra-se na utilização da tecnologia como meio de aproximar as informações sobre o risco da realidade encontrada no território. A representação das áreas por meio de mapa, associada a alertas preventivos e avisos de emergência, busca permitir que o usuário identifique regiões vulneráveis ou afetadas e tenha acesso a informações que possam auxiliar na prevenção, no afastamento ou na evacuação de áreas de risco. A apresentação de locais seguros, pontos de apoio, orientações e possíveis alternativas de deslocamento complementa essa proposta ao considerar que, diante de uma ocorrência, reconhecer o perigo é importante, mas também pode ser necessário compreender quais ações podem ser tomadas para reduzir a exposição a ele.

A integração com instituições, serviços e iniciativas que já atuam no monitoramento e gerenciamento de riscos permite que a proposta seja desenvolvida de maneira complementar às estruturas existentes. O objetivo não é substituir os mecanismos oficiais de monitoramento, alerta ou atuação em situações de emergência, mas investigar como informações provenientes dessas estruturas podem ser organizadas e apresentadas em um mesmo ambiente de maneira acessível e relacionada às necessidades dos usuários.

Dessa forma, o desenvolvimento do Toró se justifica pela possibilidade de aprofundar a investigação sobre a relação entre monitoramento, localização, comunicação do risco e apoio à tomada de decisão, utilizando a Avenida Tereza Cristina como principal recorte de estudo. Os objetivos definidos para o projeto buscam transformar os aspectos identificados durante essa investigação em recursos capazes de reunir informações confiáveis e apresentá-las de maneira localizada, compreensível e útil para diferentes públicos expostos.

**2.4 PÚBLICO-ALVO**

O público-alvo é composto principalmente por pessoas que moram, trabalham ou circulam por áreas expostas a alagamentos, inundações, deslizamentos e possíveis interdições durante os períodos de chuva, o projeto contempla tanto pessoas que possuem contato frequente com áreas vulneráveis quanto aquelas que podem circular ocasionalmente por esses locais e desconhecer seu histórico de ocorrências.

Esse público apresenta diferentes níveis de conhecimento sobre os riscos existentes no território. Moradores e comerciantes, por exemplo, podem possuir maior familiaridade com o histórico de determinada região por vivenciarem ocorrências anteriores, enquanto trabalhadores e motoristas que utilizam essas áreas apenas para deslocamento podem não reconhecer antecipadamente os locais mais vulneráveis. Essa diferença torna necessário que as informações apresentadas pelo software não dependam de conhecimento prévio sobre riscos, permitindo que diferentes usuários compreendam a localização, a natureza da situação e as orientações relacionadas a ela.

Também são considerados os diferentes níveis de familiaridade e acesso à tecnologia. Parte dos usuários utiliza diariamente smartphones, aplicativos de mapas e GPS, WhatsApp, redes sociais e outros recursos digitais, enquanto outros podem possuir menor familiaridade com essas ferramentas ou acesso mais limitado. Por se tratar de informações relacionadas à prevenção e à segurança, o projeto considera importante que a interação com o software seja simples e que alertas, mapas e orientações sejam apresentados de maneira direta, visual e de fácil compreensão, evitando que o usuário precise dominar conceitos técnicos para interpretar uma situação de risco.
