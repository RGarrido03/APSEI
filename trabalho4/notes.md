# PropertEase
- Ideia
- Problema & solução

## Comercialização
Incluir vantagens e desvantagens.
  - Projeto de investigação, grátis
  - Startup
  - Freemium: preço da AI para recomendar preço de alojamento é paga
  - Anúncios
  - SAS: vender partes da solução. Infraestrutura de agregação de dados: wrappers que mandam para uma queue que manda para BDs. 

## Marcas registadas
Não tem nada patenteável, mas para a integração são usadas identidades visuais e acessos proprietários às APIs.

## Tecnologias
- Encontrar alternativas open-source, ou algo do género. Por exemplo, se se usasse MySQL, tinha de se trocar para Postgres.
- Ver as licenças dos open-source
- Sugestão: fazer tabela

## Cibersegurança
- Importa é que saber que se tem de fazer isso
- Os dados que são sensíveis estão separados em diferentes BDs
- Análise de código

## Ataques
- Revisão de código estático, que vai diretamente avisar sobre CVE/CWE. Ou seja, evitar os códigos que se sabem
- Zero days não são importantes, óbvio

## Dados
- Não somos donos dos dados. Somos um meio, um mensageiro.
- Iliba-nos de alguns aspetos, mas imaginem que temos acesso à API do Airbnb, se alguém acedesse ao nosso sistema poderia partir tudo
  - Detetar mudanças de preço
  - Rate limit

## AI
- Ética

## Hyperscalers
- Startup: usar serviços geridos por eles.
  - AWS: RDB, S3, auto-scaling

## Externalidades
- Extremamente dependentes de serviços externos. Ou seja, a lei pode mudar e proibir self-hosting de alojamentos; as ações do Airbnb podem cair a pique e perdemos uma boa parte da nossa solução.
