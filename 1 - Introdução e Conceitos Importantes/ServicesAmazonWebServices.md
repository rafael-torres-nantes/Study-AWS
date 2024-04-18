# Serviços da AWS

Os [Serviços da AWS](https://aws.amazon.com/pt/products/?nc2=h_ql_prod_fs_f) combinados acabam gerando diversas funcionalidades.

<p align="center">
    <img src="/1 - Introdução e Conceitos Importantes/assets/servicesAWS.png" width="480" height="320">
</p>

## Global Infrastructure
[Regiões e Zonhas Disponíveis](https://aws.amazon.com/pt/about-aws/global-infrastructure/regions_az/?p=ngi&loc=2)

A infraestrutura global da AWS é composta por: 
- 22 regiões
- 70 Zonas de Disponibilidade (AZ) 
- 216 Edge Locations ao redor do mundo. 

### Regiões (Regions)

As regiões representam localidades físicas onde a AWS está disponível, com várias regiões nos Estados Unidos, por exemplo. 

###  Zonas de Disponibilidade
As Zonas de Disponibilidade, que são a quantidade de datacenters em cada região, garantem alta disponibilidade, desempenho, tolerância a falhas e recuperação de desastres, com no mínimo duas AZs por região. É importante notar que as Zonas de Disponibilidade são cruciais tanto do ponto de vista tecnológico quanto do ponto de vista legal, já que alguns governos têm restrições sobre onde certos tipos de dados podem ser hospedados. Além disso, a AWS nunca move ou copia dados entre regiões sem a solicitação explícita do dono do recurso.

###  Edge Locations (Pontos de Presença)

As Edge Locations são utilizadas para entrega de conteúdo por meio do serviço de CDN da AWS, chamado CloudFront, acelerando a entrega de conteúdo estático, como páginas HTML, imagens e vídeos. Elas podem existir em localidades que ainda não possuem uma região da AWS ou Zonas de Disponibilidade, e a AWS trabalha com diversos parceiros ao redor do mundo para viabilizar isso. Essas Edge Locations desempenham um papel crucial na melhoria da velocidade de entrega de conteúdo, como demonstrado pelo contraste entre a lentidão e rapidez na entrega de diferentes tipos de conteúdo.

## Atualizações da AWS

## Comunicação Frequente das Atualizações

