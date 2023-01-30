# Calendário de entregas

- ``30/01`` Kick-off projeto final;
  - Criar um repositório **público** da equipe;
  - Adicionar a mim como membro do projeto;
  - Criação das classes/pacotes das entidades do projeto.
- ``14/02`` Definições da camada de Modelos;
  - Diagrama de Classes;
  - Diagrama de Entidade-Relacional;
  - Script SQL de criação do banco de dados do projeto.
- ``27/02`` Definições da camada de Visão;
  - Protótipo de telas com base nos requisitos;
  - Definição da identidade visual.
- ``14/03`` Definições da camada de Controle - *parte 01*;
  - Integração com Banco de dados (CRUD básico das entidades);
  - Implementação de Autenticação no sistema;
  - Início da implementação dos demais requisitos;
- ``29/03`` Definições da camada de Controle - *parte 02*;
  - Continuação da implementação dos demais requisitos.
- ``29-30/03`` e ``03-04/04`` Acompanhamento de projeto final;
- ``05/04`` Apresentação dos projetos.

## Requisitos gerais de TODOS os projetos 

- Precisa ter uma página inicial institucional estática, a página inicial;
- Demais páginas precisam ser dinâmicas e abordar os casos de uso;
- Ser responsivo, ter pontos de quebra para celular e Desktop; 
- Identidade visual com palheta de cores (até 05) e fontes;
- Possuir controle de acesso de usuários;
- Ter entre 05 e 10 componentes distintos do [Bootstrap](http://www.getbootstrap.com/). Entende-se como componentes tudo da seção Components;
- Diagrama Entidade-Relacionamento do banco de dados;
- O sistema precisa ter autenticação de usuários.

# Sistema de turismo de poucos dias

Tamanho de Equipe: **3** (+1)

## Descrição narrativa


Este projeto propõe o desenvolvimento de um sistema de recomendação de roteiros turísticos pré-estabelecido de curta estadia, com base na indicação de uma dada localização, a fim de auxiliar turistas de negócios ou eventos, com tempo reduzido, a preencherem seus horários livres com atividades que lhes satisfaçam. As vantagens de um roteiro pré-estabelecido aparece quando: (i) os locais sugeridos despertam seu interesse; (ii) as despesas podem ser financiadas; (iii) há comodidade na locomoção, alojamento, refeições podem ser feitas em um determinado local e que num retorno, o turista tendo selecionado um dos pontos do roteiro, tenha algum conhecimento sobre este.

O sistema possui duas frentes, a do Turista e a do Turismólogo. O Turismólogo é o profissional que planeja, organiza e promove viagens, eventos e atividades de lazer e negócios. Vende passagens, reserva hotéis e programa de passeios e excursões. Realiza levantamentos socioeconômicos e culturais na área de turismo. 

No módulo do Turista, o usuário informa uma localização para realizar uma consulta. Esta consulta retorna o roteiro com os atrativos turísticos, exibindo-os em um mapa interativo (API do OpenStreet Map), permitindo visualizar informações mais detalhadas ao selecionar o ponto no mapa. Estando de acordo com a sugestão gerada, o Turista terá seu roteiro individual armazenado no sistema, permitindo-o visualização póstuma. O Turista também pode deixar este roteiro de viagem público permitindo que outros possam se aproveitar da sua configuração de atrativos turísticos, e até mesmo ser avaliado e comentado.

Para o Turismólogo, o sistema permitirá que o mesmo faça a curadoria de atrativos turísticos, bem como possa realizar funcionalidades do módulo Turista. Vale notar que cada atrativo turístico possui informações como custo, categoria de atrativo (lazer, histórico, ecológico, dentre outras), tempo de duração, custo aproximado, dentre outras informações que visem a comodidade dos Turistas. Além disso, o Turismólogo é pode favoritar roteiros, como se fosse um selo de aprovação.

## Requisitos específicos resumidos

- Fazer cadastro de Turista e Turismólogo;
- Realizar curadoria de pontos turísticos (informações, descrição, custo, localização, fotos, dentre outros);
- Integrar a curadoria à API de mapas;
- Permitir comentários e avaliação nos roteiros;
- Permitir busca na curadoria de roteiros;
- Permirtir curadoria de roteiros.
