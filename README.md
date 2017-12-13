# turistificacion
datos para la aproximación al impacto del turismo en Madrid

## fuentes de datos
-cad: catastro, extraccion en junio de 2017
-fl :flickr, extracción en junio de 2017 que incluye toda la informacion georeferenciada hasta el momento 
-tp: tripadvisor, extracción en septiembre de 2017
-fc: fotocasa, extracción en mayo-septiembre de 2017 
-h: hoteles, datos del portal de datos abiertos del ayuntamiento de Madrid
-local200/local300: número de locales del dataset de locales del ayto alrededor del centroide del hexágono a un radio de 200 y 300
-abnb :airbnb, extracción del 8 de abril de 2017, datos obtenidos del portal inside Airbnb http://insideairbnb.com/get-the-data.html
-m : dataset que compara datos de fotocasa y abnb, limpiado y filtrado (no es lo mismo que coger los datos de fc y abnb)

## geo
-se emplea el srid 25830
-cada punto es el centroide de un hexágono de 200 metros de diámetro sobre el que se realizan distintas operaciones de agregación

## campos
1	abnb_pk
2	abnb_tot_beds
3	abnb_tot_hosts_listings
4	abnb_tot_offer
5	abnb_tot_owners
6	abnb_tot_price
7	abnb_tot_reviews
8	abnb_tot_reviews_per_month
9	cad_med_consq
10	cad_pk
11	cad_tot_hab
12	cad_tot_hotels
13	cad_tot_houses
14	cad_tot_parcs
15	cad_tot_srf_hotels
16	cad_tot_srf_houses
17	fc_avg_price
18	fc_tot_offer
19	fc_tot_owners
20	fl_n_date
21	fl_n_locals
22	fl_n_posts
23	fl_n_tourists
24	fl_n_user
25	fl_tag_madrid
26	fl_txt_madrid
27	h_address
28	h_body
29	h_cat1cod
30	h_cat1txt
31	h_cat2cod
32	h_cat2txt
33	h_cat3cod
34	h_cat3txt
35	h_country
36	h_email
37	h_fax
38	h_id
39	h_language
40	h_latitude
41	h_locality
42	h_longitude
43	h_name
44	h_phone
45	h_subadministrativearea
46	h_title
47	h_web
48	h_zipcode
49	lat
50	local200_n_agrupaciones
51	local200_n_alojamiento
52	local200_n_alquillercoche
53	local200_n_desconocidos
54	local200_n_epigrafes
55	local200_n_fiesta
56	local200_n_locales
57	local200_n_locutoris
58	local200_n_prox_alcohol
59	local200_n_prox_educacion
60	local200_n_prox_fresco
61	local200_n_prox_noalim
62	local200_n_prox_pastelerias
63	local200_n_prox_supers
64	local200_n_prox_supersbig
65	local200_n_restaurants
66	local200_n_sex
67	local200_n_shops
68	local200_n_shops24h
69	local200_n_vacios
70	local300_n_agrupaciones
71	local300_n_alojamiento
72	local300_n_alquillercoche
73	local300_n_desconocidos
74	local300_n_epigrafes
75	local300_n_fiesta
76	local300_n_locales
77	local300_n_locutoris
78	local300_n_prox_alcohol
79	local300_n_prox_educacion
80	local300_n_prox_fresco
81	local300_n_prox_noalim
82	local300_n_prox_pastelerias
83	local300_n_prox_supers
84	local300_n_prox_supersbig
85	local300_n_restaurants
86	local300_n_sex
87	local300_n_shops
88	local300_n_shops24h
89	local300_n_vacios
90	lon
91	rn_ab_avg_price
92	rn_ab_max_price
93	rn_ab_med_price
94	rn_ab_min_price
95	rn_ab_offer
96	rn_ab_tot_price
97	rn_fc_avg_price
98	rn_fc_max_price
99	rn_fc_med_price
100	rn_fc_min_price
101	rn_fc_offer
102	rn_fc_tot_price
103	rn_med_tramo
104	rowid
105	tp_offers_tot
106	tp_pk
107	tp_pricerange_0
108	tp_pricerange_1
109	tp_pricerange_2
110	tp_pricerange_3
111	tp_pricerange_avg
112	tp_pricerange_med
113	tp_pricerange_tot
114	tp_rating_avg
115	tp_rating_max
116	tp_rating_med
117	tp_rating_min
118	tp_rating_tot
119	tp_reviews_avg
120	tp_reviews_max
121	tp_reviews_med
122	tp_reviews_min
123	tp_reviews_tot
