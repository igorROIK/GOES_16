# GOES_16
Python scripts for processing images from the GOES 16 satellite.

O satélite GOES-16, conhecido anteriormente como GOES-R, é o primeiro da série GOES-R da Geostationary Operational Environmental Satellites, operado pela NASA e a NOAA. Encontra-se 
posicionado a Leste, em 75.2°W, visando uma visão centrada nas Américas. O GOES-16 fornece imagens de alta resolução espacial e temporal da Terra, por meio de 16 bandas espectrais 
em comprimento de ondas visíveis e infravermelhos, usando o seu Advanced Baseline Imager (ABI). Além disso, permite por meio do Geostationary Lightning Mapper (GLM), a mapear a ocor-
rência de raios. 

Com objetivo de possibilitar o acesso as imagens do GOES-16, estarei disponibilizando vários scripts, os quais permitirão o processamento de várias informações.

AS IMAGENS PARA SEREM USADAS NOS SCRIPTS PODEM SER BAIXADAS NO SITE:
- https://home.chpc.utah.edu/~u0553130/Brian_Blaylock/cgi-bin/goes16_download.cgi
NA PÁGINA ABERTA EM -Domain- selecione Full Disk, neste caso obtêm imagens da América do Sul. Em -Product- será selecionado a váriavel a ser analisada. Já nos campos -Date- e
-Hour (UTC)-, seleciona a data e o horário da imagem a ser analisada, lembrando que o horário se encontra em UTC. Após selecionar os devidos campos, clicar em -Submit-, e aguardar
o carregamento dos arquivos para download.

DESCRIÇÃO RÁPIDA DOS CANAIS DO GOES-16
Canal 1 – Visível (0,47 mícrons)
Canal 2 – Visível (0,64 mícrons)
Canal 3 - Infravermelho próximo (0,86 mícrons)
Canal 4 - Infravermelho próximo (1,37 mícrons)
Canal 5 – Infravermelho próximo (1,60 mícrons)
Canal 6 - Infravermelho próximo (2,20 mícrons)
Canal 7 – Infravermelho ondas curtas Colorido (3,90 mícrons)
Canal 8 – Vapor de água ondas médias colorido (6,20 mícrons)
Canal 9 - Vapor de água ondas médias colorido (6,90 mícrons)
Canal 10 - Vapor de água ondas médias colorido (7,30 mícrons)
Canal 11 - Infravermelho Termal ondas longas (8,40 mícrons)
Canal 12 - Infravermelho Termal ondas longas (9,60 mícrons)
Canal 13 - Infravermelho Termal ondas longas (10,35 mícrons)
Canal 14 - Infravermelho Termal ondas longas (11,2 mícrons)
Canal 15 - Infravermelho Termal ondas longas (12,3 mícrons)
Canal 16 - Infravermelho Termal ondas longas (13,3 mícrons)

Visível: 
Esse tipo de imagem capta o albedo (reflexão luz solar) das nuvens, por isso disponível apenas durante o dia. Tons claros representam área de alto albedo e 
tons mais escuros representam áreas de baixo albedo. A refletividade está relacionada com a profundidade da nuvem, distribuição e tamanho das gotas, 
composição (gotas de água ou gelo) e conteúdo de água líquida.
Infravermelho:
Esse tipo de imagem capta a temperatura no topo das nuvens. As imagens de satélite infravermelhas são relacionadas à temperatura do brilho. 
Vapor de água: 
Esse tipo de imagem capta vapor de água nas nuvens. As cores mais escuras indicariam um ar mais seco quando mais brilhante e mais branco, maior a umidade no 
ar.
