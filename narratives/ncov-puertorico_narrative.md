---
title: Vigilancia Genómica de SARS-CoV-2 en Puerto Rico
authors: Arnold Rodriguez-Hilario, MS
authorLinks: "https://github.com/arodzh-sudo"
date: "2022-12-13"
dataset: "https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/all-time?c=pango_lineage&d=tree,frequencies&f_country=Puerto%20Rico&l=clock&m=div&p=full&showBranchLabels=all"
abstract: "

La tecnología de **secuenciacion de proxima generación (NGS, por sus siglas en ingles)** permite detectar grupos de casos y monitorear nuevas variantes del virus. Los grupos de virus que comparten un conjunto de mutaciones en el genoma se denominan linajes. Algunas variantes que pertenecen a linajes específicos pueden tener características como la capacidad de propagarse más rápidamente, causar una enfermedad más grave o afectar el tratamiento clínico, como el tratamiento con anticuerpos monoclonales. Estas variantes pueden clasificarse como variantes de interés (VOI), variantes bajo monitoreo (VBM), variantes de preocupación (VOC) o variantes de gran preocupación.


Se implementó un flujo de trabajo básico de **vigilancia genómica utilizando la plataforma Nextstrain** para monitorear en tiempo real, la evolución del **SARS-CoV-2 en Puerto Rico**. Este programa permite la visualización de árboles filogenéticos para evaluar la divergencia de los genomas de SARS-CoV-2 de Puerto Rico en comparación con el genoma de referencia Wuhan-Hu-1. **Los linajes presentados en este narrativo son segun el clasificador Nextclade (dataset 2023-08-09)**.


![](https://raw.githubusercontent.com/nextstrain/ncov-clades-schema/master/clades.svg)
Relaciones filogenéticas de los grupos monofiléticos de SARS-CoV-2 clasificados por Nextstrain, fuente: [Nextstrain](https://nextstrain.org/)
"
---

# [Actualización - 10 de agosto de 2023](https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/six-months/?branchLabel=emerging_lineage&f_country=Puerto%20Rico&label=clade:22F%20%28XBB%29&showBranchLabels=all)

A inicios de junio de 2023, **XBB** y sus sublinajes recombinantes habían crecido a representar el **95% SARS-CoV-2** a nivel mundial. Debido a la gran transmisibilidad de esta versión del virus, se ha generado una gran diversidad de linajes descendientes de XBB (+500 sublinajes). Esto ha provocado la aparición de nuevas mutaciones en la proteína “Spike” bajo una inmensa presión selectiva (evolución convergente).


La evolución convergente se manifiesta como patrones emergentes de mutaciones que surgen de forma independiente dentro de diferentes linajes de XBB. Algunas mutaciones beneficiosas que ocurren repetidamente en varios linajes XBB son **S:486P, S:478R, S:F456L, S:E554K, S:Q613H, S:S704L, S:A701V, S:K356T y S:K403R**. Dado que XBB ha tenido suficiente tiempo para transmitirse y adquirir múltiples mutaciones en la proteina “Spike”, están surgiendo cada vez más sublinajes con emparejamientos de mutaciones beneficiosas en las siguientes formas:


**S:456L + S:478R** = FL.5.1, XBB1.16.6, XBB.1.16.9


**S:455F + 456L** = GK, DV.7.1


**S:52H + S:456L** = EG.5.1, FL.20. [El miércoles 9 de agosto de 2023, la Organización Mundial de la Salud clasificó a EG.5 como una variante de interés](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwjtwordxtKAAxWhTTABHWBIAvgQFnoECA8QAQ&url=https%3A%2F%2Fwww.who.int%2Fdocs%2Fdefault-source%2Fcoronaviruse%2F09082023eg.5_ire_final.pdf%3Fsfvrsn%3D2aa2daee_1&usg=AOvVaw2v-1ytMErhVWhZiauuSfSU&opi=89978449)


**S:478R + S:521S** = GJ.1, XBB.1.16.15


**S:478R + S:304N** = HF.1


**S:478R + S:613H** = XBB.1.42.1


**S:554K** = FL.10.1


El linaje de más rápido crecimiento a nivel mundial con una circulación significativa es actualmente **EG.5 (XBB.1.9.2 con S:F456L)**. La mayoría de EG.5 ha adquirido una mutacion adicional en S:Q52H (definiendo a EG.5.1) que también podría ser una mutación ligeramente beneficiosa.


# [XBB.1.5 (Nextstrain clade 23A, S:252V + S:486P)](https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/six-months/?branchLabel=aa&f_country=Puerto%20Rico&f_pango_lineage=XBB.1.5,XBB.1.5.10&label=clade:23A%20%28XBB.1.5%29)


XBB.1.5 (23A) tiene las mismas mutaciones que XBB (22F), con algunas mutaciones adicionales, incluida S:G252V y una eliminación en ORF8:G8 que produce un codón de terminación. El sublinaje XBB.1.5 también tiene una mutación de nucleótido adicional en la posición T23018C, lo que da como resultado que S:F486S en XBB se convierta en S:F486P. 


XBB.1.5 fue el primer sublinaje de XBB en adquirir S:F486P y propagarse ampliamente. Fue más común en Estados Unidos/Canada, donde llegó a alcanzar alrededor del 80% de frecuencia en marzo de 2023. A pesar de los multiples sublinajes de XBB y XBB.1.5 en la actualidad, la frecuencia global de XBB.1.5 aún se mantiene en 26% a finales de julio 2023.


Sublinajes de interés detectados en Puerto Rico:


**XBB.1.5.10** con **S:F456L**, ha crecido alrededor hasta un 25% de frecuencia entre junio y julio 2023.


# [XBB.1.16 (Nextstrain clade 23B, S:180V + S:252V + S:478R + S:486P)](https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/six-months/?branchLabel=aa&f_country=Puerto%20Rico&label=clade:23B%20%28XBB.1.16%29&tl=pango_lineage)


El pasado 17 de abril de 2023, la Organizacion Mundial de la Salud (OMS) y siguiendo el consejo del Grupo Asesor Técnico de la OMS sobre la Evolución Viral del SARS-CoV-2, ha designado [XBB.1.16 (23B) una Variante de Interés](https://www.who.int/docs/default-source/coronaviruse/21042023xbb.1.16ra-v2.pdf) tras un aumento sostenido en su prevalencia y una ventaja de crecimiento sostenida notificada por varios países. 


En comparación con XBB.1.5 (23A), XBB.1.16 (23B) presenta **las mutaciones adicionales en la proteína Spike: E180V y K478R**. El **aminoácido 478 es T (treonina)** en la forma típica que se encuentra en el gen (wild type) del SARS-CoV-2 y **ha mutado a K (lisina) en Ómicron** (a través de una mutación de nucleótido C->A). **En XBB.1.16, el nucleótido A ha mutado ahora a G, dando como resultado el aminoácido R (arginina)**. Por lo tanto, esta no es una mutación de 2 pasos en el sentido de que siempre requiere 2 sustituciones de nucleótidos como en el caso de S:486P.


Sublinajes de interés detectados en Puerto Rico:


**XBB.1.16.6** con **S:F456L** adicional (a través de T22930A)


**XBB.1.16.9** con **S:F456L** adicional (a través de T22930G)


**XBB.1.16.13** con **ORF1a:G519S + ORF1a:G1101D**


**XBB.1.16.16** con **S:Q613H + S:S412N**


# [CH.1.1 (Nextstrain clade 23C, S:346T + S:444T + S:452R + S:486S)](https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/six-months/?branchLabel=aa&f_country=Puerto%20Rico&label=clade:23C%20%28CH.1.1%29&tl=pango_lineage)

CH.1.1 es un **sublinaje descendiente de BA.2.75 (22D)** con mutaciones adicionales en el gen de la proteína "Spike" en las regiones 346T, 444T, 452R y 486S. Es **de los pocos linajes que continuan en circulacion y que no es descendientes de la recombinante XBB**. Actualmente se observa una mayor evolución antigénica en CH.1.1 y predomina en paises como Nueva Zelanda y Australia (10-40%), con una menor presencia en Europa y los Estados Unidos (1-10%).


Sublinajes de interés detectados en Puerto Rico:


**CH.1.1.2** con **S:T883I**


**GP.1 (CH.1.1.11.1)** con **S:Q52H**


**FK.1.4.1 (CH.1.1.17.1.4.1)** con **S:G181A**


**CH.1.1.25** con **ORF1a:S330L** + **ORF1a:P4197S**


# [XBB.1.9 (Nextstrain clade 23D FL/HN S:252V + S:486P)](https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/six-months/?branchLabel=aa&f_country=Puerto%20Rico&label=clade:23D%20%28XBB.1.9%29&tl=pango_lineage)


Los sublinajes **XBB.1.9.1 y XBB.1.9.2** son descendientes de XBB.1 que adquirieron la mutacion **S:F486P** de manera independiente a XBB.1.5. Son los sublinajes de mayor crecimiento que contienen S:F486P detras de **XBB.1.16** y XBB.1.5. Los sublinajes XBB.1.9.1 y XBB.1.9.2 comparten las mutaciones **ORF1a:G1819S + ORF1a:T4175I + ORF9b:I5T**. A nivel mundial, 23D = XBB.1.9 superó a 23A = XBB.1.5 aproximadamente en mayo de 2023 y sigue en aumento con multiples sublinajes entre ellos FL.1.5.1 y EG.5 (23F). En julio de 2023, 23D representó alrededor de 1/3 de las secuencias globales.


Sublinajes de interés detectados en Puerto Rico:


**FL.1.5.1** con **S:F456L + S:478R + S:A701V**, más común en República Dominicana donde parece haberse vuelto dominante. En aumento en EE. UU./Canadá. Cuatro secuencias detectadas en Puerto Rico a fines de junio de 2023.


**HN.1 (FL.1.5.1.1)** con **S:A67S**


**FL.20 (XBB.1.9.1.20)** con **S:F456L (22928C) + S:Q52H**. De las primeras secuencias genómicas a nivel mundial de este sublinaje fueron detectadas en Puerto Rico y fueron evaluadas para apoyar la designacion de dicho sublinaje.


# [XBB.2.3 (Nextstrain clade 23E, S:253G + S:486P + S:521S)](https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/six-months/?branchLabel=aa&f_country=Puerto%20Rico&label=clade:23E%20%28XBB.2.3%29&tl=pango_lineage)

XBB.2.3 es el único sublinaje de XBB con la mutación **S:486P** que es de la rama **XBB.2 (S:D253G)** de XBB en lugar de XBB.1 (S:G252V). XBB.2.3 (23E) tiene la mutación adicional **S:521S** en el gen de la proteina "Spike" y es el único linaje XBB con **ORF1b:P959S**, una reversión al genotipo original. 23E ha crecido constantemente desde que apareció por primera vez a principios de 2023 y ahora se encuentra en alrededor del 10% a nivel mundial. Es más común en el sur y sureste de Asia.


Sublinajes de interés detectados en Puerto Rico:


**XBB.2.3.2** con **S:G184V**


# [EG.5.1 (Nextstrain clade 23F, S:52H + S:456L + S:486P)](https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/six-months/?branchLabel=aa&f_country=Puerto%20Rico&label=clade:23F%20%28EG.5.1%29&tl=pango_lineage)

EG.5.1 (XBB.1.9.2.5.1) es un sublinaje de XBB.1.9 (23D) con mutaciones adicionales en el gen de la proteina "Spike" en  486P, F456L y Q52H. Ha estado creciendo constantemente desde que se secuenció por primera vez en marzo de 2023 y representó alrededor del 20% de las secuencias a fines de julio 2023. El sublinaje EG.5.1 es particularmente común en China, donde es el linaje dominante. Sin embargo, EG.5.1 está creciendo en todos los continentes. Es el primer clado de Nextstrain con la mutación **S:F456L** la cual es la responsable de la mayoria de los linajes en crecimiento a nivel mundial en la actualidad.


Sublinajes de interés detectados en Puerto Rico:


**EG.5.1.1** con **ORF1b:D54N (G13627A)**


**EG.5.1.3** con **ORF1a:R542C** + **C22570T**

