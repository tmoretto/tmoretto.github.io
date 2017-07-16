---
layout: post
title:  "Olho Vivo API"
date:   2017-07-15 12:00:00 -0300
categories: java open-source
---

Outro dia indo para o trabalho acabei perdendo 3 ônibus em sequência! Sempre chegando alguns segundos atrasado no ponto e vendo seu busão indo embora **:(** 

Durante a espera do próximo ônibus lembrei que a SPTrans possui uma API para consulta em tempo real de várias informações da frota de ônibus em São Paulo [Olho Vivo API][olho-vivo-api]. 

Assim que cheguei em casa resolvi dar uma olhada na API e criei um wrapper bem simples em **Java** com **Spring Boot** para consumir os serviços disponibilizados. 

Para utilizar a API do Olho Vivo você precisa primeiramente fazer um http POST passando seu token de acesso. Apanhei um pouquinho com isso no começo pois os cookies retornados precisam ser enviados em todas as requests seguintes para que os acessos funcionem. 

O projeto completo esta lá no meu [GitHub][link-github].

Até a próxima!

[olho-vivo-api]: http://bit.ly/2v4GxTv
[link-github]: http://bit.ly/2tsBKsV

