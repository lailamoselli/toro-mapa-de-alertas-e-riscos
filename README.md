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

Desenvolver um software voltado ao monitoramento e à prevenção de riscos geológicos e hidrológicos em Belo Horizonte e Contagem, capaz de fornecer alertas preventivos sobre condições que possam favorecer a ocorrência de desastres e avisos diante de situações de emergência. O software busca informar os usuários em tempo hábil, contribuindo para a prevenção, o afastamento ou a evacuação segura de áreas de risco e, consequentemente, para a redução de possíveis danos e perdas. Para atender a essa proposta, será desenvolvido o software Toró — Mapa de Riscos e Alertas. 

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

Para representar os diferentes perfis envolvidos com o problema, foram definidas três personas que apresentam necessidades e formas distintas de interação com o software:

- Maria Luiza representa moradores e trabalhadores que precisam acompanhar as condições da região, receber avisos preventivos, consultar possíveis riscos e compreender rapidamente situações que possam afetar sua rotina.

- Thiago José representa motoristas e demais pessoas que se deslocam frequentemente pela cidade e utilizam recursos como GPS e aplicativos de mapas, necessitando identificar alagamentos, interdições e áreas perigosas antes de acessá-las, além de obter informações que auxiliem na escolha de alternativas mais seguras de deslocamento.

- Camila Ferreira, agente da Defesa Civil, que possui maior familiaridade com sistemas internos, mapas digitais e aplicativos de comunicação e necessita acompanhar ocorrências, identificar regiões afetadas, receber informações da população e utilizar dados organizados para apoiar sua atuação. Diferentemente dos usuários que consultam o sistema principalmente para sua própria prevenção e deslocamento, esse perfil possui uma relação profissional com as informações e com o acompanhamento das situações de risco.

Essa diversidade também envolve diferentes relações entre os participantes do sistema. A população constitui o principal público beneficiado pelas informações disponibilizadas, podendo também contribuir com relatos sobre ocorrências e condições observadas. Já órgãos como Defesa Civil, prefeituras, bombeiros e demais instituições relacionadas ao gerenciamento de riscos assumem uma posição distinta, por representarem fontes e agentes envolvidos na produção, validação ou utilização de informações relacionadas à prevenção e à resposta a emergências. 

Dessa forma, o público-alvo é composto por diferentes pessoas e agentes que possuem relações distintas com as áreas de risco. Essa diversidade orienta o desenvolvimento de uma solução acessível para a população em geral, considerando também a participação da comunidade e a atuação das instituições responsáveis. Assim, o software busca atender às diferentes necessidades identificadas durante a investigação do projeto, apresentando as informações de maneira clara, compreensível e acessível. 

**3 PRODUCT DISCOVERY**

**3.1 MATRIZ CSD**

A Matriz CSD, foi utilizada no projeto para organizar, em certezas, suposições e dúvidas, Essa organização permitiu identificar quais informações já eram conhecidas, quais representavam hipóteses do grupo e quais questões ainda precisam ser investigadas, contribuindo para direcionar as pesquisas e o aprofundamento do problema ao longo do desenvolvimento do projeto.

**3.1.1 Dúvidas: O que ainda não sabemos?**

- Quando, em relação ao momento real do risco, um alerta chegaria a tempo de a pessoa conseguir evacuar em segurança?

- Para onde uma pessoa deve ir ao evacuar uma área de risco geológico ou de alagamento?

- Para onde uma pessoa deve ir ao evacuar uma área de risco geológico ou de alagamento?

- Como alguém sabe, com segurança, que o risco já passou e que é seguro voltar para casa?

- Por que as pessoas desconfiam ou não levam a sério os avisos de risco que já existem hoje?

- Como uma pessoa comum diferencia um risco real de um boato sem ter meios técnicos para verificar isso sozinha?

- Quem é responsável por confirmar que um risco relatado é real antes de a informação se espalhar?

- De onde vem, hoje, a informação que uma pessoa tem sobre o risco da região onde mora ou passa?

- Como uma pessoa sem acesso constante à internet ou celular fica sabendo de um risco iminente?

- O que uma pessoa faz quando o risco acontece durante uma queda de energia ou de sinal, momento em que ela mais precisaria de informação?

- Quais informações uma pessoa realmente precisa saber no momento do risco — o que está acontecendo, para onde ir, o que levar, quanto tempo tem?

- Por que, mesmo sabendo que mora ou passa por uma área de risco, muitas pessoas não mudam de comportamento diante de um aviso?

- Quando alguém segue todas as orientações de segurança e, mesmo assim, é atingido por um imprevisto, como esse incidente chega ao conhecimento de quem poderia evitar que se repetisse?

**3.1.2 Certezas: O que já sabemos?**

- Falta de manutenção urbana pode causar acidentes e transtornos.

- Alertas oficiais de risco geológico já existem hoje, mas vêm de canais fragmentados (Defesa Civil, prefeitura, redes sociais).

- Áreas de risco já são mapeadas oficialmente por órgãos como Defesa Civil e CPRM.

- Falta de sinal e energia é comum justamente durante eventos climáticos extremos.

- Nem toda a população tem acesso constante à internet ou smartphone.

- Pessoas que convivem há anos com o risco tendem a ignorar avisos repetidos.

- Informações com localização e imagens facilitam a resolução do problema.

- A organização dos dados permite encontrar regiões com maior necessidade de manutenção.

- Um site simples e fácil de usar aumentaria o número de usuários.

**3.1.3 Suposições: O que achamos, mas não temos certeza?**

- Um alerta com instrução clara (o quê, para onde ir, quanto tempo tem) aumentaria a chance de evacuação a tempo.

- Centralizar os relatos ajudaria a Defesa Civil/prefeitura a identificar riscos mais rapidamente.

- Um site com fotos e localização aumentaria a confiabilidade dos relatos de risco.

- O acompanhamento do status do alerta pelo site incentivaria mais pessoas a confiar e participar.

- Notificações sobre atualização do risco (ex: "risco passou") aumentariam o engajamento com o site.

- Um canal alternativo (sirene, rádio comunitário, aviso de vizinhança) ajudaria quem fica sem internet/sinal no momento do risco.

- Um site que confirma/valida relatos reduziria a disseminação de boatos.

- Se incidentes fossem reportados e resolvidos rapidamente, mais pessoas confiariam e usariam o site.

<img width="8591" height="5703" alt="Matriz CSD" src="https://github.com/user-attachments/assets/3e31bd26-c6de-4a18-adfd-f4ce0dfa3eb8" />

**3.2 MAPA DE STAKEHOLDERS**

O Mapa de Stakeholders foi utilizado para identificar e organizar as pessoas, grupos e instituições relacionados ao problema, considerando seus diferentes níveis de participação e influência. Os envolvidos foram classificados entre fundamentais, importantes e influenciadores.

**3.2.1 Fundamentais**

- Cidadãos e moradores de áreas de riscos geológicos: representam a população diretamente exposta às situações de risco e um dos principais públicos do Toró. Poderiam utilizar o software para consultar áreas vulneráveis, receber alertas preventivos e avisos de emergência, identificar locais seguros e pontos de apoio, acessar orientações e enviar relatos sobre ocorrências observadas na região.

- Motoristas e pessoas que apenas passam pela área: representam usuários que podem entrar em uma região de risco sem conhecer seu histórico ou as condições daquele momento. O Toró poderia auxiliá-los na identificação de alagamentos, inundações, interdições e outros perigos antes da aproximação da área, além de apresentar informações que contribuam para a escolha de alternativas mais seguras de deslocamento.

- Voluntários/agentes comunitários de Defesa Civil: possuem contato mais próximo com as comunidades e podem atuar na orientação da população, na identificação de situações observadas no território e no apoio às ações de prevenção. No contexto do projeto, representam uma ligação entre a população e os órgãos responsáveis pelo gerenciamento dos riscos.

**3.2.2 Importantes**

- Defesa Civil: possui relação direta com o monitoramento, a prevenção e a resposta às situações de risco. Para o Toró, representa uma das principais referências institucionais para informações oficiais, alertas, orientações e identificação de áreas vulneráveis, além de poder receber informações provenientes da população para análise.

- Bombeiros: atuam principalmente na resposta às situações de emergência, incluindo resgates e atendimento às pessoas afetadas. Sua relação com o projeto está associada às situações em que um evento deixa de representar apenas uma possibilidade de risco e passa a exigir atendimento emergencial e ações de proteção e salvamento.

- Prefeitura de Contagem e Prefeitura de Belo Horizonte: estão relacionadas à gestão dos territórios contemplados pelo projeto e às ações municipais de prevenção, infraestrutura, mobilidade e resposta aos problemas provocados por eventos geológicos e hidrológicos. Também podem representar fontes de informações oficiais utilizadas pelo software, especialmente sobre áreas de risco, interdições, serviços públicos e medidas adotadas durante ocorrências.

- Provedores de internet e operadoras de telefonia: estão relacionados aos meios utilizados para que informações e alertas digitais cheguem aos usuários. Sua presença no mapa é relevante porque o funcionamento de uma solução digital depende da disponibilidade de conexão, enquanto a falta de internet ou sinal durante situações de risco constitui uma das questões identificadas pelo próprio grupo na Matriz CSD.

- Comércio e associações de moradores locais: possuem contato direto com a realidade das regiões afetadas e com as necessidades da comunidade. Podem contribuir para a identificação de problemas recorrentes, divulgação de informações preventivas e compreensão dos impactos que as ocorrências provocam na rotina local.

**3.2.3 Influenciadores**

- Órgãos reguladores ambientais: estão relacionados às normas, diretrizes e informações referentes à gestão ambiental e à ocupação do território. No projeto, podem servir como referência para compreender aspectos ambientais relacionados às áreas estudadas e às medidas de prevenção.

- Voluntários de projetos sociais: podem contribuir para aproximar informações e ações preventivas das comunidades, principalmente de grupos que apresentem maior dificuldade de acesso aos canais digitais ou às informações oficiais.

- Especialistas em geologia, engenharia civil e meteorologia: representam conhecimentos técnicos importantes para a compreensão dos fenômenos investigados. Podem contribuir para interpretar informações relacionadas às condições meteorológicas, características do território, áreas vulneráveis, inundações, deslizamentos e outros fatores associados aos riscos abordados pelo Toró.

- Pesquisadores e professores acadêmicos orientadores do projeto: contribuem para o desenvolvimento e a avaliação da proposta, auxiliando na investigação do problema, na análise das informações levantadas e na orientação das decisões tomadas durante o desenvolvimento acadêmico do Toró.

- Mídias e canais de notícias regionais: participam da circulação de informações sobre chuvas, alagamentos, interdições e outras ocorrências. No contexto do projeto, são relevantes para compreender como as informações chegam atualmente à população e como diferentes canais podem contribuir para a divulgação de situações de risco.

- Moradores e comerciantes locais: além de estarem diretamente sujeitos aos impactos das ocorrências, possuem conhecimento cotidiano sobre as regiões onde vivem ou trabalham. Como influenciadores, podem contribuir com experiências, relatos e percepções sobre problemas recorrentes, ajudando o projeto a compreender necessidades que podem não ser identificadas apenas por meio de dados técnicos.

<img width="8450" height="5798" alt="Mapa de Stakeholders" src="https://github.com/user-attachments/assets/42f7c229-ad1c-41f3-a045-e824d6059bf8" />

**3.3 PESQUISA E ENTENDIMENTO DO PROBLEMA**

As pesquisas realizadas sobre a Avenida Tereza Cristina demonstram que as inundações constituem um problema recorrente e com impactos diretos sobre moradores, comerciantes, trabalhadores e motoristas que utilizam a região. Os casos analisados registram transbordamentos do Ribeirão Arrudas, interdições da avenida, veículos atingidos, prejuízos materiais e moradores que convivem com o receio de novas ocorrências. A recorrência desses acontecimentos demonstra que, em determinadas situações, o intervalo entre a identificação do perigo e a necessidade de reação pode ser reduzido, tornando especialmente importantes a antecipação das informações e a orientação adequada da população (ESTADO DE MINAS, 2021).

A análise foi ampliada para compreender como os riscos geológicos e hidrológicos se manifestam em outras áreas de Belo Horizonte e Contagem. Em Belo Horizonte, já haviam sido identificadas, em 2019, quase cem áreas com possibilidade de alagamento durante períodos de chuva. Ocorrências registradas ao longo de 2026, envolvendo alagamentos, transtornos urbanos e emissão de alertas de risco geológico, demonstram que esses eventos continuam afetando diferentes regiões da cidade (G1, 2019; UOL, 2026).

Em Contagem, a Defesa Civil registrava, em 2024, aproximadamente 255 pontos considerados de risco, sendo 150 relacionados a riscos hidrológicos e 105 a riscos geológicos. Além do mapeamento das áreas vulneráveis, o município realiza ações de orientação à população sobre como proceder diante de alagamentos, enchentes e deslizamentos e mantém o telefone 199 para situações de emergência ou iminência de desastre (Contagem, 2024). 

A necessidade de preparação para essas ocorrências também pode ser observada nas ações preventivas realizadas na Avenida Tereza Cristina. Em 2025, ocorreu o 10º treinamento preventivo de risco de inundação na região, envolvendo órgãos públicos e moradores voluntários. A atividade incluiu a simulação do bloqueio da via diante da possibilidade de inundação, além de procedimentos relacionados à emissão de alertas, monitoramento, sinalização, interdição e posterior liberação da avenida (Belo Horizonte, 2025).

As ações preventivas não se restringem à Avenida Tereza Cristina. Em agosto de 2026, a Defesa Civil de Belo Horizonte iniciou a preparação de suas equipes para o período chuvoso 2026/2027, contemplando monitoramento meteorológico, níveis de alerta, bloqueios preventivos, primeiros socorros, Plano de Contingência e procedimentos de resposta e atendimento às pessoas atingidas. Essas iniciativas demonstram a importância da preparação antecipada e da coordenação entre os diferentes órgãos envolvidos (Belo Horizonte, 2026).

No âmbito nacional, o Cemaden também desenvolve pesquisas relacionadas aos sistemas de alerta antecipado, integrando informações meteorológicas, características ambientais e dados populacionais para aprimorar a identificação de situações de risco. Esses estudos demonstram que o monitoramento técnico precisa estar associado à comunicação das informações aos órgãos responsáveis e à própria população, para que os dados produzidos possam efetivamente contribuir para a prevenção (CEMADEN, 2026).

O levantamento realizado demonstra, portanto, que o problema não está relacionado à ausência de informações, monitoramento ou ações preventivas. Existem mapas, sensores, previsões, alertas, treinamentos e orientações produzidos por diferentes instituições. Entretanto, essas informações encontram-se distribuídas entre diferentes sistemas e fontes, enquanto a população precisa compreender, em tempo adequado, onde existe risco, qual é a situação daquela região e como deve agir. Essa necessidade passou a orientar a proposta do Toró, que busca organizar informações existentes e apresentá-las de maneira localizada, acessível e compreensível.

**3.3.1 Depoimento e levantamento de necessidades dos usuários**

Como parte da pesquisa para compreensão do problema, realizamos uma entrevista com o objetivo de reunir experiências relacionadas a situações de risco geológico e hidrológico e identificar dificuldades e necessidades percebidas pela população. A entrevista abordou aspectos como experiências anteriores, formas de recebimento de informações sobre riscos, dificuldades para encontrar rotas seguras, informações consideradas importantes durante uma emergência e sugestões para melhorar a comunicação e a segurança da população.

Entre os relatos coletados, uma participante residente no bairro Cidade Industrial, em Contagem, descreveu uma ocorrência de chuva intensa que provocou uma rápida elevação do volume de água na região. Segundo o depoimento, a água avançou pelas ruas com grande intensidade, arrastando veículos, danificando portões e atingindo também a feira localizada no bairro Amazonas. Moradores tiveram suas residências afetadas, enquanto trabalhadores da feira perderam produtos, barracas e outros materiais.

A participante não se encontrava em casa no momento da ocorrência, pois estava viajando, e seu cachorro, Jack, permanecia na residência sob os cuidados diários de um familiar. Embora o imóvel não tenha apresentado perdas materiais significativas, o animal morreu durante o evento. Como não havia ninguém no local no momento em que a água chegou, não foi possível determinar exatamente como ocorreu o acidente. O relato evidencia que os impactos de uma situação dessa natureza não se restringem aos danos materiais, podendo envolver também perdas pessoais e afetivas.

A experiência relatada contribuiu para ampliar a compreensão das necessidades que devem ser consideradas no desenvolvimento do Toró. Além da importância de alertas antecipados e localizados, informações sobre áreas vulneráveis e orientações para deslocamento seguro, o caso demonstrou a necessidade de considerar pessoas que possuem familiares, residências ou animais em áreas de risco mesmo quando não estão fisicamente no local. Nesse contexto, funcionalidades como cadastro de locais de interesse, recebimento de alertas referentes a essas áreas e compartilhamento de notificações com familiares ou contatos cadastrados podem ampliar o alcance preventivo da aplicação.

O depoimento evidencia a importância de uma comunicação que ocorra antes que a situação se torne crítica, e reforça que o desenvolvimento da solução deve considerar não apenas o monitoramento dos riscos, mas também as experiências e necessidades das pessoas que podem ser diretamente afetadas.

**3.3.2 Levantamento de dados e tecnologias necessárias para o desenvolvimento da solução**

A partir da compreensão do problema e das necessidades identificadas durante a pesquisa, tornou-se necessário investigar quais dados e recursos tecnológicos seriam necessários para o funcionamento do software em uma implementação real. Como a proposta envolve a apresentação de áreas vulneráveis, alertas preventivos e de emergência e informações de apoio à população, o sistema dependeria da integração de diferentes fontes meteorológicas, hidrológicas e geográficas.

**3.3.2.1  Dados de monitoramento e previsão**

Um dos principais elementos seria o acompanhamento da precipitação. O Cemaden mantém uma rede de pluviômetros automáticos capaz de registrar a quantidade e a intensidade das chuvas e disponibiliza informações recentes e séries históricas por meio de seus sistemas. Esses dados poderiam auxiliar na identificação da evolução das chuvas em determinada região. Entretanto, o próprio Cemaden informa que dados disponibilizados diretamente no Mapa Interativo podem ser brutos e apresentar inconsistências, o que demonstra a necessidade de tratamento e validação antes de sua utilização pelo software (CEMADEN, 2015).

A precipitação não poderia ser analisada isoladamente. A avaliação dos riscos geo-hidrológicos envolve também fatores como previsão meteorológica, nível dos cursos d’água, características da área e, dependendo do fenômeno analisado, condições do solo e outras variáveis ambientais de acordo com as características de cada local (CEMADEN, [s.d.]b, [s.d.]c).

No próprio território estudado já existem estruturas que demonstram essa forma integrada de monitoramento. Em 2026, Contagem iniciou a implantação de 15 Plataformas de Coleta de Dados Meteorológicos distribuídas pelas oito regiões administrativas do município. Os equipamentos registram informações como chuva, temperatura, umidade, vento, radiação solar e pressão atmosférica, e parte deles também acompanha os níveis de rios e córregos (CONTAGEM, 2026b).

Na região Industrial de Contagem, próxima à confluência com o córrego Ferrugem, uma estação hidrométrica monitora o nível do Ribeirão Arrudas em intervalos de 15 minutos. Esse acompanhamento permite observar alterações do curso d’água durante períodos de chuva e demonstra a importância de relacionar a precipitação ao comportamento dos rios, principalmente em regiões historicamente atingidas por inundações (CONTAGEM, 2026c).

A Agência Nacional de Águas e Saneamento Básico (ANA), por meio do HidroWeb, disponibiliza informações relacionadas a chuva, nível e vazão de estações hidrológicas, além de possuir serviços que podem permitir a consulta automatizada dessas informações. O Instituto Nacional de Meteorologia (INMET), por sua vez, disponibiliza observações de suas estações meteorológicas automáticas. Informações de previsão meteorológica, radares e modelos de previsão também seriam importantes para que o sistema pudesse considerar não apenas as condições atuais, mas também a possibilidade de agravamento nas horas seguintes (ANA, [s.d.]; INMET, [s.d.]).

Experiências como o GeoRisk, desenvolvido no contexto do Cemaden, demonstram a utilização conjunta de modelos meteorológicos, informações ambientais, histórico de desastres e parâmetros técnicos para apoiar a previsão de riscos. Para a aplicação, essa referência reforça que qualquer classificação de atenção, alerta ou emergência deveria utilizar critérios tecnicamente fundamentados e, preferencialmente, validados pelos órgãos competentes (CEMADEN, [s.d.]a).

**3.3.2.2 Informações geográficas e localização**

Além dos dados meteorológicos e hidrológicos, o funcionamento da aplicação dependeria da identificação espacial das áreas vulneráveis. Belo Horizonte disponibiliza informações geográficas por meio do BHGEO, inclusive serviços nos padrões WMS e WFS, que permitem respectivamente visualizar mapas e acessar dados de determinadas camadas geográficas (BELO HORIZONTE, 2021).

Para a região do Ribeirão Arrudas, a Prefeitura de Belo Horizonte também disponibiliza a Carta de Inundações da Bacia do Ribeirão Arrudas, contendo informações sobre áreas potencialmente atingidas, profundidade da água, velocidade, nível de risco e tempo estimado de chegada da inundação. Esses dados demonstram que uma área vulnerável não deve ser compreendida apenas como um ponto isolado no mapa, mas como um território que pode apresentar diferentes características e níveis de exposição (BELO HORIZONTE, 2024).

Com a autorização do usuário, sua localização poderia ser relacionada a essas informações. Assim, o sistema poderia diferenciar um aviso geral, como a ocorrência de chuva em Belo Horizonte, de uma situação em que determinado usuário esteja próximo de uma área vulnerável ou possua algum local de interesse naquela região. Essa característica também se relaciona diretamente à necessidade identificada no depoimento coletado, permitindo acompanhar locais importantes mesmo quando a pessoa não estiver fisicamente presente neles.

A integração de diferentes fontes já começa a ser realizada pelos próprios municípios. Em agosto de 2026, Contagem inaugurou a Sala Observatório do Clima e da Resiliência, destinada ao acompanhamento de dados meteorológicos e hidrométricos em tempo real. A estrutura reúne estações meteorológicas, previsão do tempo, radar de precipitação, monitoramento de raios, pluviômetros e sensores de nível dos cursos d’água. Segundo o município, também está em desenvolvimento um painel para integrar essas informações em mapas, gráficos e instrumentos de apoio à tomada de decisão (CONTAGEM, 2026a).

A proposta do Toró se aproxima desse modelo de integração, porém com uma finalidade diferente. Enquanto estruturas como o Observatório auxiliam principalmente as equipes responsáveis pelo monitoramento e pela gestão das ocorrências, o Toró pretende organizar parte dessas informações para apresentá-las diretamente à população em uma linguagem mais simples, contextualizada e relacionada à localização do usuário.

**3.3.2.3 Estrutura tecnológica e processamento das informações**

Em uma implementação real, o Toró necessitaria de uma estrutura formada por front-end, back-end e banco de dados. O front-end seria responsável pelas telas visualizadas pelo usuário, como mapa, alertas, áreas de risco, orientações e locais seguros. O back-end faria a comunicação com as fontes externas, trataria os dados recebidos e aplicaria as regras necessárias ao funcionamento do sistema. O banco de dados armazenaria informações como áreas vulneráveis, estações de monitoramento, locais seguros, alertas, ocorrências e demais dados necessários à aplicação.

Também seria necessário diferenciar informações relativamente estáticas das informações dinâmicas. Mapas de áreas vulneráveis, localização de cursos d’água, locais seguros e cadastro de estações poderiam permanecer armazenados no sistema e ser atualizados quando novas versões fossem publicadas. Já precipitação, previsão meteorológica, nível dos cursos d’água, alertas oficiais e possíveis interdições exigiriam atualização frequente.

O processamento das informações poderia relacionar a localização do usuário, as características da área, a precipitação observada e acumulada, a previsão meteorológica, o comportamento dos cursos d’água e os alertas oficiais disponíveis. Para riscos geológicos, outras variáveis poderiam ser incorporadas conforme a metodologia utilizada e a disponibilidade dos dados. Pesquisas do Cemaden sobre sistemas de alerta antecipado demonstram a importância da integração entre produtos meteorológicos, informações ambientais, características regionais e locais e dados populacionais na avaliação dos riscos (CEMADEN, 2024).

Nesse processo, seria fundamental distinguir as análises apresentadas pelo software dos alertas emitidos oficialmente pelos órgãos competentes. O Toró poderia integrar e destacar avisos oficiais e utilizar outras informações para contextualizar a situação do usuário, mas não deveria substituir as instituições responsáveis pela avaliação e emissão dos alertas de desastres. A elaboração e a transmissão de alertas envolvem procedimentos técnicos, análise do risco, comunicação das informações e preparação para resposta (BRASIL, [s.d.]).

Quando uma situação relevante fosse identificada, um serviço de notificações poderia encaminhar um aviso ao usuário contendo, de maneira objetiva, o tipo de ocorrência, a região envolvida e as orientações correspondentes. Ao acessar o sistema, o usuário poderia visualizar informações complementares, áreas afetadas, contatos de emergência e, quando disponíveis, locais considerados seguros.

A indicação de deslocamentos também exigiria cuidados específicos. Uma rota convencional entre dois pontos não seria suficiente durante uma emergência, pois poderia atravessar áreas alagadas, vias interditadas ou outros locais perigosos. Por isso, a indicação de rotas seguras dependeria de dados confiáveis e atualizados sobre as condições das vias e áreas atingidas.

Por fim, a implementação exigiria verificar, para cada fonte pesquisada, sua forma de acesso, frequência de atualização, formato dos dados, condições de uso e disponibilidade para integração. A existência de uma informação em um portal público não significa necessariamente que ela esteja disponível por meio de uma API. Algumas fontes poderiam ser integradas automaticamente, enquanto outras dependeriam de autorização, parceria institucional ou mecanismos específicos de consulta.

De forma geral, o funcionamento proposto para o Toró pode ser compreendido como um fluxo em que informações provenientes de pluviômetros, estações meteorológicas e hidrológicas, previsões, mapas de risco e alertas oficiais são reunidas e processadas pelo sistema. Esses dados são relacionados à localização e aos locais de interesse cadastrados pelo usuário e transformados em informações compreensíveis sobre a situação da região. Quando necessário, a aplicação apresenta alertas e orientações adequadas.

Dessa maneira, a proposta do Toró não consiste apenas em informar se está chovendo, mas em organizar informações que atualmente se encontram distribuídas em diferentes fontes e relacioná-las ao contexto do usuário, buscando contribuir para que situações de risco sejam reconhecidas com maior antecedência e para que as orientações necessárias estejam disponíveis de forma localizada e acessível.

**3.4 PERSONAS**

Foram definidas três personas que representam diferentes perfis envolvidos com a solução e suas respectivas necessidades diante das situações de risco.

**3.4.1 Maria Luiza — Moradora e trabalhadora**

Maria Luiza tem 33 anos, trabalha como recepcionista e utiliza o smartphone diariamente, principalmente para comunicação pelo WhatsApp e acompanhamento de informações pelas redes sociais. Representa moradores e trabalhadores que convivem com os problemas da região e precisam de informações que auxiliem sua rotina e seus deslocamentos. Busca receber avisos de forma rápida, acompanhar alterações nos trajetos, identificar possíveis riscos e contribuir com relatos e imagens de situações observadas. Para ela, o sistema deve ser simples e rápido, apresentar informações confiáveis e atualizadas e permitir que a população também participe do acompanhamento das ocorrências.

**3.4.2 Thiago José — Motorista**

Thiago José tem 26 anos, é motorista e utiliza diariamente celular, aplicativos de mapas e GPS, passando grande parte do dia em deslocamento pela cidade. Representa pessoas que podem passar por regiões de risco sem conhecer previamente as condições do local. Precisa receber avisos sobre alagamentos antes de chegar às áreas afetadas, identificar ruas e avenidas que devem ser evitadas, encontrar alternativas mais seguras e saber quando determinado local foi liberado novamente. Para esse perfil, as informações devem ser claras, rápidas e localizadas, evitando alertas atrasados, confusos ou excessivos.

**3.4.3 Camila Ferreira — Agente da Defesa Civil**

Camila Ferreira tem 40 anos e trabalha como agente da Defesa Civil, utilizando computador, celular, sistemas internos, mapas digitais e aplicativos de comunicação em sua rotina profissional. Representa os profissionais envolvidos no monitoramento, prevenção e acompanhamento das situações de risco. Precisa identificar regiões vulneráveis, acompanhar ocorrências, receber informações da população e comunicar situações de perigo. Para esse perfil, o sistema deve apresentar informações precisas, organizadas, atualizadas e corretamente localizadas, facilitando o acompanhamento das ocorrências e evitando a divulgação de alertas sem confirmação ou informações incorretas.

<img width="12043" height="4068" alt="Personas" src="https://github.com/user-attachments/assets/e6d6afd7-9ad0-4efd-8a2e-7740eae3f611" />

**4 PRODUCT DESIGN**

**4.1 HISTÓRIAS DE USUÁRIOS**

**4.1.1 Maria Luiza — Moradora e trabalhadora**

- Como moradora e trabalhadora, preciso saber sobre alterações e desvios no transporte público, para planejar meu deslocamento e evitar transtornos.

- Como moradora de uma área vulnerável, preciso saber se minha região apresenta risco de alagamento, para tomar os cuidados necessários e me proteger.

- Como cidadã, preciso ter um canal para informar problemas ou situações de risco observadas na região, para contribuir para que essas ocorrências sejam conhecidas e analisadas.

- Como moradora, preciso receber informações e alertas sobre riscos próximos à minha localização, para evitar áreas perigosas e tomar decisões com antecedência.

**4.1.2 Thiago José — Motorista**

- Como motorista, preciso saber quais áreas apresentam riscos geológicos ou hidrológicos, para evitar entrar em locais perigosos durante meus deslocamentos.

- Como motorista, preciso saber se uma via está interditada, para realizar meu trajeto com maior segurança.

- Como motorista, preciso saber se existe uma rota alternativa, para continuar meu deslocamento sem passar pela área de risco.

- Como motorista, preciso receber informações atualizadas sobre as condições das vias, para planejar meu percurso e evitar regiões afetadas.

**4.1.3 Camila Ferreira — Agente da Defesa Civil**

- Como profissional da Defesa Civil, preciso visualizar informações sobre áreas de risco e ocorrências registradas, para acompanhar as situações identificadas nas diferentes regiões.

- Como profissional da Defesa Civil, preciso visualizar relatos enviados pela população, para analisar possíveis situações de risco e acompanhar as ocorrências.

- Como profissional da Defesa Civil, preciso acompanhar informações organizadas e atualizadas sobre as ocorrências, para auxiliar na tomada de decisões e nas ações de prevenção e resposta.

- Como profissional da Defesa Civil, preciso comunicar alertas e orientações sobre situações de perigo, para informar a população e contribuir para sua segurança.

**4.2 PROPOSTA DE VALOR**

**4.2.1 Maria Luiza — Moradora e trabalhadora**

A proposta de valor para Maria Luiza está direcionada ao acompanhamento das condições da região, recebimento de alertas preventivos e participação na comunicação de ocorrências. A solução permitirá consultar áreas de risco e ocorrências no mapa, receber informações localizadas, acompanhar alterações que possam interferir nos deslocamentos e enviar relatos, localização e imagens de situações observadas.

A solução deve priorizar praticidade, rapidez, informações confiáveis e atualizadas e uma interface de fácil compreensão, facilitando o acompanhamento das ocorrências e atendendo às necessidades de quem vive ou trabalha em regiões vulneráveis.

**4.2.2 Thiago José — Motorista**

A proposta de valor para Thiago José está direcionada à realização de deslocamentos mais seguros e à prevenção da entrada em áreas afetadas. A solução permitirá visualizar áreas de risco, alagamentos, inundações e vias interditadas, além de receber alertas relacionados à sua localização ou trajeto.

Quando houver informações confiáveis disponíveis, também poderá indicar vias que devem ser evitadas e possíveis alternativas de deslocamento, além de apresentar atualizações sobre as condições e a liberação das áreas afetadas, auxiliando o motorista no planejamento de seus trajetos.

**4.2.3 Camila Ferreira — Agente da Defesa Civil**

A proposta de valor para Camila Ferreira está direcionada ao acompanhamento e à organização das informações sobre riscos e ocorrências. A solução permitirá visualizar áreas vulneráveis e ocorrências no mapa, identificar sua localização e acompanhar sua evolução.

Também será possível consultar e analisar relatos enviados pela população, mantendo a diferenciação entre relatos comunitários e informações oficiais. A solução deve apresentar informações organizadas, atualizadas e corretamente localizadas, contribuindo para o monitoramento das situações de risco e para a comunicação de alertas e orientações à população.

<img width="16070" height="3049" alt="Proposta de Valor" src="https://github.com/user-attachments/assets/905beee9-64f1-428e-8d80-e18a14bc12bb" />

**4.3 PROJETO DE INTERFACE**

O projeto de interface do software foi desenvolvido a partir das funcionalidades definidas para a solução e das necessidades dos diferentes usuários identificados durante o projeto. A organização das telas considera dois perfis de utilização: o usuário comum, que acessa informações, alertas e recursos relacionados às ocorrências, e a Defesa Civil, que possui acesso às funcionalidades destinadas à análise e validação das informações registradas na aplicação.

**4.3.1 Fluxo do Usuário**

O fluxo do usuário foi elaborado para representar os caminhos possíveis entre as telas e facilitar a compreensão de como cada perfil poderá utilizar a aplicação. Como o Toró possui funcionalidades diferentes de acordo com o tipo de acesso, foram construídos fluxos para o usuário comum e para a Defesa Civil.

No fluxo do usuário comum, o acesso à aplicação pode ocorrer pela tela de login ou pela realização de um novo cadastro. Após o acesso, o usuário é direcionado para a página inicial, onde encontra o mapa e as informações relacionadas às ocorrências e alertas. A partir dessa tela, também poderá acessar seu perfil e outras funcionalidades previstas para consulta e comunicação de situações de risco.

<img width="462" height="577" alt="Wireframe-usuario" src="https://github.com/user-attachments/assets/9dd367b9-3645-4e92-b390-a74aa573d001" />

Além das funcionalidades de consulta, os wireframes destinados ao usuário comum também preveem o registro de ocorrências e o acesso a recursos de emergência, permitindo que situações identificadas pelo usuário sejam comunicadas pela aplicação e que haja acesso rápido aos meios de contato de emergência.

Para a Defesa Civil, o fluxo também parte das telas de login ou cadastro e direciona o usuário para a página inicial da aplicação. A partir dela, é possível acessar o perfil e a área específica da Defesa Civil, destinada ao acompanhamento das ocorrências registradas. Nesse ambiente, as informações recebidas podem ser consultadas e analisadas para posterior validação.

<img width="551" height="448" alt="Wireframe-defesa-civil" src="https://github.com/user-attachments/assets/04fe2b13-d9fd-4c14-99a1-e99f5ae08f76" />

Os fluxos foram organizados de forma a demonstrar visualmente as relações entre as telas e os principais caminhos que poderão ser percorridos pelos dois perfis durante a utilização do sistema.

**4.3.2 Wireframes**

Os wireframes foram desenvolvidos para representar a estrutura das telas do Toró antes da construção da interface definitiva. Nessa etapa, foram definidos a disposição dos elementos, os conteúdos principais, os campos de entrada, os botões e as possibilidades de navegação entre as diferentes funcionalidades da aplicação.

Para o usuário comum, foram projetadas telas de login, cadastro, página inicial, perfil, registro de ocorrência, redefinição de senha e acesso aos recursos de emergência. A página inicial concentra o mapa e os registros de ocorrências e alertas, permitindo que o usuário tenha acesso às principais informações logo após entrar na aplicação. A tela destinada às ocorrências possibilita o envio de informações sobre uma situação identificada, enquanto a área de emergência disponibiliza formas de contato com o serviço responsável.

<img width="462" height="577" alt="Wireframe-usuario" src="https://github.com/user-attachments/assets/9dd367b9-3645-4e92-b390-a74aa573d001" />

Para o perfil da Defesa Civil, foram desenvolvidas telas de login, cadastro, página inicial, perfil, redefinição de senha e área específica para análise das ocorrências. A interface destinada à Defesa Civil permite visualizar informações encaminhadas para a aplicação, incluindo os registros e imagens associados à ocorrência, além do espaço destinado à descrição e à validação das informações.

<img width="551" height="448" alt="Wireframe-defesa-civil" src="https://github.com/user-attachments/assets/04fe2b13-d9fd-4c14-99a1-e99f5ae08f76" />

Dessa forma, os wireframes permitem visualizar não apenas a organização individual de cada tela, mas também como elas se relacionam dentro da aplicação e como as funcionalidades previstas foram distribuídas entre os diferentes perfis de usuário.

<img width="994" height="603" alt="Wireframe" src="https://github.com/user-attachments/assets/1ea4171d-36cb-44d1-9e5e-28072e8340b5" />

As telas desenvolvidas no Figma podem ser consultadas pelo link: https://www.figma.com/design/fhQuEifVsaGw4sfhOO9Va6/TIAW--c%25C3%25B3pia-?node-id=0-1&p=f&t=zPBxkjkkr9Cqsvvh-0

**4.3.3 Protótipo Interativo**

Com base nos wireframes e nos fluxos definidos, foi desenvolvido no Figma um protótipo interativo do Toró. O protótipo permite simular a navegação entre as telas e visualizar como ocorrerá a interação do usuário com as principais funcionalidades propostas para a aplicação.

A navegação possibilita percorrer os diferentes caminhos previstos no projeto, como o acesso pelas telas de login e cadastro, a entrada na página inicial, a consulta das informações apresentadas no mapa, o acesso ao perfil e às funcionalidades correspondentes a cada tipo de usuário. Para o perfil da Defesa Civil, o protótipo também apresenta a navegação até a área destinada à análise e validação das ocorrências.

Por meio do protótipo é possível observar, de maneira mais próxima à utilização do sistema final, a relação entre as telas e o funcionamento esperado da navegação antes da etapa de implementação da aplicação.

**Protótipo interativo:** https://www.figma.com/proto/fhQuEifVsaGw4sfhOO9Va6/TIAW--c%C3%B3pia-?node-id=146-435&t=oLnGW7NOJkSyxk20-1&starting-point-node-id=146%3A435

**5 METODOLOGIA**

**5.1 FERRAMENTAS**

Durante o desenvolvimento do projeto, foram utilizadas diferentes ferramentas para apoiar as etapas de pesquisa, organização, prototipação, documentação e desenvolvimento da aplicação.

- **Miro:** utilizado na organização das atividades e na construção de artefatos do projeto, como Matriz CSD, Mapa de Stakeholders e quadro Kanban.

- **Figma:** utilizado para o desenvolvimento dos wireframes, fluxo de telas e protótipo interativo do Toró, permitindo representar e testar a navegação antes da implementação.

- **Kanban:** aplicado por meio do Miro para organizar e acompanhar as atividades da equipe, distribuídas entre tarefas a fazer, em andamento e concluídas.

- **GitHub:** utilizados para controle de versão, organização do repositório e armazenamento dos arquivos e da documentação do projeto, possibilitando o desenvolvimento colaborativo.

- **Visual Studio Code (VS Code):** definido como ambiente de desenvolvimento para a etapa de implementação da aplicação web, oferecendo suporte às tecnologias utilizadas no desenvolvimento front-end.

- **Canva:** utilizado para elaboração dos slides e organização dos elementos visuais empregados na apresentação do projeto.

- **Microsoft Teams:** utilizado para realização de reuniões e alinhamento das atividades entre as integrantes da equipe.

**5.2 ORGANIZAÇÃO DA EQUIPE E DIVISÃO DE PAPÉIS**

A equipe organizou o desenvolvimento do projeto com base no framework Scrum, dividindo o trabalho em tarefas e acompanhando o progresso das atividades durante as etapas. As demandas foram definidas e distribuídas entre as integrantes, com revisão e alinhamento em grupo conforme as entregas eram concluídas. A divisão específica de responsabilidades ficou estruturada da seguinte forma:

- **Laila:** Matriz CSD e Documentação.

- **Sophia:** Mapa de Stakeholders e Interface.

- **Bárbara:** Highlights, Personas e Interface.

- **Emily:** História do Usuário e Slides.

- **Cristiane:** Proposta de Valor e Slides.

**5.3 QUADRO DE CONTROLE DE TAREFAS - KANBAN**

Para organizar e acompanhar o desenvolvimento do projeto, a equipe utilizou um quadro Kanban no Miro, estruturado nas etapas: A Fazer, Em Andamento e Concluído. As atividades foram inseridas no quadro e movimentadas conforme o progresso do trabalho, permitindo visualizar as responsabilidades de cada integrante, as tarefas já realizadas e aquelas que ainda estavam pendentes.

<img width="9192" height="5330" alt="Quadro Kanban" src="https://github.com/user-attachments/assets/0f78e2a4-96a2-4533-9d5c-db7f418f8494" />

**5.4 PRÓXIMOS PASSOS**

**5.4.1 Curto Prazo: Validação e Testes**

No curto prazo, pretende-se realizar testes de usabilidade com usuários, utilizando o protótipo interativo para avaliar a clareza dos alertas, a facilidade de navegação e a compreensão das informações, inclusive em situações que possam exigir respostas rápidas. Os resultados obtidos serão utilizados para o refinamento da interface e da experiência do usuário (UI/UX), adequando as telas às necessidades identificadas durante as pesquisas, entrevistas e testes.

**5.4.2 Médio Prazo: Desenvolvimento Técnico**

No médio prazo, prevê-se o desenvolvimento de um Mínimo Produto Viável (MVP), reunindo as funcionalidades essenciais da proposta, como cadastro de usuários, visualização das áreas de risco e apresentação de alertas. Também será necessário avançar na integração com fontes reais de dados meteorológicos, hidrológicos e geográficos, considerando as redes e serviços identificados durante a pesquisa, além da implementação de notificações push para o envio de alertas aos usuários.

**5.4.3 Longo Prazo: Expansão e Parcerias**

No longo prazo, pretende-se buscar parcerias com a Defesa Civil e outros órgãos responsáveis pelo monitoramento e gerenciamento de riscos, contribuindo para a validação das informações utilizadas pelo sistema. Também está prevista a ampliação da participação da comunidade, permitindo o envio de relatos sobre alagamentos, deslizamentos e outras ocorrências, sujeitos à triagem antes de sua disponibilização. Após a validação e o amadurecimento da solução, poderá ser disponibilizada uma versão beta do Toró para dispositivos móveis, possibilitando sua avaliação em condições reais de uso.

**REFERÊNCIAS**

AGÊNCIA NACIONAL DE ÁGUAS E SANEAMENTO BÁSICO (ANA). HidroWeb Service. [s.d.]. Disponível em: https://www.ana.gov.br/hidrowebservice/swagger-ui/index.html.

BELO HORIZONTE (MG). Prefeitura. Acesso aos dados geográficos. Belo Horizonte, 29 abr. 2021. Atualizado em: 1 set. 2021. Disponível em: https://prefeitura.pbh.gov.br/bhgeo/acesso-aos-dados.

BELO HORIZONTE (MG). Prefeitura. Carta de Inundações da Bacia do Ribeirão Arrudas. Belo Horizonte, 3 dez. 2024. Disponível em: https://prefeitura.pbh.gov.br/obras-e-infraestrutura/informacoes/diretoria-de-gestao-de-aguas-urbanas/cartas-de-inundacoes/carta-inundacoes-bacia-ribeirao-arrudas.

BELO HORIZONTE (MG). Prefeitura. Defesa Civil de BH inicia treinamento de efetivo para o período chuvoso 2026/2027. Belo Horizonte, 17 ago. 2026. Disponível em: https://prefeitura.pbh.gov.br/noticias/defesa-civil-de-bh-inicia-treinamento-de-efetivo-para-o-periodo-chuvoso-20262027.

BELO HORIZONTE (MG). Prefeitura. Prefeitura de BH promove treinamento preventivo de risco de inundação. Belo Horizonte, 11 set. 2025. Disponível em: https://prefeitura.pbh.gov.br/noticias/preveitura-de-bh-promove-treinamento-preventivo-de-risco-de-inundacao.

BRASIL. Ministério do Desenvolvimento Regional. Manual para elaboração, transmissão e uso de alertas de risco de movimento de massa. Brasília, DF: Ministério do Desenvolvimento Regional, [s.d.]. Disponível em: https://www.gov.br/mdr/pt-br/centrais-de-conteudo/publicacoes/protecao-e-defesa-civil-sedec/ManualparaElaboraoTransmissoeusodeAlertasdeRiscodeMovimentodeMassa.pdf.

CENTRO NACIONAL DE MONITORAMENTO E ALERTAS DE DESASTRES NATURAIS (CEMADEN). GeoRisk: sistema de previsão de riscos de deslizamentos de terra. [s.d.]a. Disponível em: https://georisk.cemaden.gov.br/saiba-mais.

CENTRO NACIONAL DE MONITORAMENTO E ALERTAS DE DESASTRES NATURAIS (CEMADEN). O Cemaden. [s.d.]b. Disponível em: https://www2.cemaden.gov.br/o-cemaden/.

CENTRO NACIONAL DE MONITORAMENTO E ALERTAS DE DESASTRES NATURAIS (CEMADEN). Pluviômetros automáticos. 11 dez. 2015. Disponível em: https://www2.cemaden.gov.br/pluviometros-automatico/.

CENTRO NACIONAL DE MONITORAMENTO E ALERTAS DE DESASTRES NATURAIS (CEMADEN). Previsão de riscos geo-hidrológicos. [s.d.]c. Disponível em: https://www.gov.br/cemaden/pt-br/assuntos/riscos-geo-hidrologicos/.

CENTRO NACIONAL DE MONITORAMENTO E ALERTAS DE DESASTRES NATURAIS (CEMADEN). Workshop no Cemaden discute projeto de sistema de alertas antecipados de deslizamentos de terra multiescalar. Brasília, 28 mar. 2024. Atualizado em: 8 jul. 2026. Disponível em: https://www.gov.br/cemaden/pt-br/assuntos/noticias-cemaden/workshop-no-cemaden-discute-projeto-de-sistema-de-alertas-antecipados-de-deslizamentos-de-terra-multiescalar.

CONTAGEM (MG). Prefeitura. Contagem entrega Inspetoria Sede e Observatório do Clima. Contagem, 28 ago. 2026a. Disponível em: https://portal.contagem.mg.gov.br/portal/noticias/0/3/84593/contagem-entrega-inspetoria-sede-e-observatorio-do-clima/.

CONTAGEM (MG). Prefeitura. Contagem implanta 15 plataformas para monitoramento climático em tempo real. Contagem, 31 jan. 2026b. Disponível em: https://portal.contagem.mg.gov.br/portal/noticias/0/3/83133/contagem-implanta-15-plataformas-para-monitoramento-climatico-em-tempo-real.

CONTAGEM (MG). Prefeitura. Defesa Civil faz alerta e compartilha dicas sobre como proceder durante o período chuvoso. Contagem, 19 jan. 2024. Disponível em: https://portal.contagem.mg.gov.br/portal/noticias/0/3/79368/defesa-civil-faz-alerta-e-compartilha-dicas-sobre-como-proceder-durante-o-periodo-chuvoso.

CONTAGEM (MG). Prefeitura. Estação meteorológica reforça monitoramento de chuvas e nível do rio Arrudas no Industrial. Contagem, 21 ago. 2026c. Disponível em: https://portal.contagem.mg.gov.br/portal/noticias/0/3/84540/estacao-meteorologica-reforca-monitoramento-de-chuvas-e-nivel-do-rio-arrudas-no-industrial/.

CONTAGEM (MG). Prefeitura. TransCon. Placas indicativas de risco são instaladas em áreas de alagamento para evitar acidentes. Contagem, 6 fev. 2025. Disponível em: https://portal.contagem.mg.gov.br/portal/noticias/0/3/81050/placas-indicativas-de-risco-sao-instaladas-em-areas-de-alagamento-para-evitar-acidentes.

ESTADO DE MINAS. Entenda por que a Av. Tereza Cristina alaga com tanta frequência. Belo Horizonte, 19 jan. 2021. Disponível em: https://www.em.com.br/app/noticia/gerais/2021/01/19/interna_gerais,1230511/entenda-por-que-a-avenida-tereza-cristina-alaga-com-tanta-frequencia.shtml.

G1. BH tem quase cem áreas com risco de alagamento em caso de chuva. Belo Horizonte, 11 out. 2019. Disponível em: https://g1.globo.com/mg/minas-gerais/noticia/2019/10/11/bh-tem-quase-cem-areas-com-risco-de-alagamento-em-caso-de-chuva.ghtml.

INSTITUTO NACIONAL DE METEOROLOGIA (INMET). Estações automáticas. [s.d.]. Disponível em: https://portal.inmet.gov.br/servicos/esta%C3%A7%C3%B5es-autom%C3%A1ticas.

UOL. Forte chuva atinge Belo Horizonte e provoca estragos. São Paulo, 23 jan. 2026. Disponível em: https://noticias.uol.com.br/cotidiano/ultimas-noticias/2026/01/23/forte-chuva-belo-horizonte-mg.html.
