---
title: Vigilancia Genómica de SARS-CoV-2 en Puerto Rico
authors: Arnold Rodriguez-Hilario, MS
authorLinks: "https://github.com/arodzh-sudo"
date: "2022-12-13"
dataset: "https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/all-time?c=pango_lineage&d=tree,frequencies&f_country=Puerto%20Rico&l=clock&m=div&p=full&showBranchLabels=all"
abstract: "

Se implementó un flujo de trabajo básico de **vigilancia genómica utilizando la plataforma Nextstrain** para monitorear en tiempo real, la evolución del **SARS-CoV-2 en Puerto Rico**. Este programa permite la visualización de árboles filogenéticos para evaluar la divergencia de los genomas de SARS-CoV-2 de Puerto Rico en comparación con el genoma de referencia Wuhan-Hu-1. Los linajes presentados en este narrativo son segun el clasificador Nextclade (dataset 06-16-2023) y las siguientes versiones de pangolin y sus componentes: pangolin: 4.3, pangolin-data: 1.21, constellations: v0.1.10, scorpio: 0.3.17 y usher 0.6.2


La tecnología de **secuenciacion de proxima generación (NGS, por sus siglas en ingles)** permite detectar grupos de casos y monitorear nuevas variantes del virus. Los grupos de virus que comparten un conjunto de mutaciones en el genoma se denominan linajes. Algunas variantes que pertenecen a linajes específicos pueden tener características como la capacidad de propagarse más rápidamente, causar una enfermedad más grave o afectar el tratamiento clínico, como el tratamiento con anticuerpos monoclonales. Estas variantes pueden clasificarse como variantes de interés (VOI), variantes bajo monitoreo (VBM), variantes de preocupación (VOC) o variantes de gran preocupación.

![](https://raw.githubusercontent.com/nextstrain/ncov-clades-schema/master/clades.svg)
Relaciones filogenéticas de los grupos monofiléticos de SARS-CoV-2 clasificados por Nextstrain, fuente: [Nextstrain](https://nextstrain.org/)
"
---

# [Actualización - 31 de julio de 2023](https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/six-months/?c=emerging_lineage&f_country=Puerto%20Rico&label=clade:22F%20%28XBB%29&showBranchLabels=all)

A inicios de junio de 2023, **XBB** y sus sublinajes recombinantes habían crecido a representar el **95% SARS-CoV-2** a nivel mundial. Debido a la gran transmisibilidad de esta versión del virus, se ha generado una gran diversidad de linajes descendientes de XBB (+500 sublinajes). Esto ha provocado la aparición de nuevas mutaciones en la proteína “Spike” bajo una inmensa presión selectiva (evolución convergente).


La evolución convergente se manifiesta como patrones emergentes de mutaciones que surgen de forma independiente dentro de diferentes linajes de XBB. Algunas mutaciones beneficiosas que ocurren repetidamente en varios linajes XBB son **S:478R, S:F456L, S:E554K, S:Q613H, S:S704L, S:A701V, S:K356T y S:K403R**. Dado que XBB ha tenido suficiente tiempo para transmitirse y adquirir múltiples mutaciones en la proteina “Spike”, están surgiendo cada vez más sublinajes con emparejamientos de mutaciones beneficiosas en las siguientes formas:


**S:456L + S:478R** = FL.5.1, XBB1.16.6, XBB.1.16.9


 **S:455F + 456L** = GK, DV.7.1


 **S:52H + S:456L** = EG.5.1, FL.20. [El pasado miércoles 19 de julio de 2023, la Organización Mundial de la Salud incluyo a EG.5 como una variante bajo monitoreo](https://www.who.int/en/activities/tracking-SARS-CoV-2-variants/)


 **S:478R + S:521S** = GJ.1, XBB.1.16.15


**S:478R + S:304N** = HF.1


 **S:478R + S:613H** = XBB.1.42.1


**S:554K** = FL.10.1


El linaje de más rápido crecimiento a nivel mundial con una circulación significativa es actualmente **EG.5 (XBB.1.9.2 con S:F456L)**. La mayoría de EG.5 ha adquirido una mutacion adicional en S:Q52H (definiendo a EG.5.1) que también podría ser una mutación ligeramente beneficiosa.


# [XBB.1.5 (Nextstrain clade 23A, S:252V + S:486P)](https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/six-months/?branchLabel=aa&f_country=Puerto%20Rico&f_pango_lineage=XBB.1.5,XBB.1.5.10&label=clade:23A%20%28XBB.1.5%29)


XBB.1.5 (23A) tiene las mismas mutaciones que XBB (22F), con algunas mutaciones adicionales, incluida S:G252V y una eliminación en ORF8:G8 que produce un codón de terminación. El sublinaje XBB.1.5 también tiene una mutación de nucleótido adicional en la posición T23018C, lo que da como resultado que S:F486S en XBB se convierta en S:F486P. 


XBB.1.5 fue el primer sublinaje de XBB en adquirir S:F486P y propagarse ampliamente. Fue más común en Estados Unidos/Canada, donde llegó a alcanzar alrededor del 80% de frecuencia en marzo de 2023. A pesar de los multiples sublinajes de XBB y XBB.1.5 en la actualidad, la frecuencia global de XBB.1.5 aún se mantiene en 26% a finales de julio 2023.


Sublinajes de interés detectados en Puerto Rico:


XBB.1.5.10 con S:F456L, ha crecido alrededor hasta un 25% de frecuencia entre junio y julio 2023


# [XBB.1.16 (Nextstrain clade 23B, S:180V + S:252V + S:478R + S:486P)](https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/six-months/?branchLabel=aa&f_country=Puerto%20Rico&label=clade:23B%20%28XBB.1.16%29)


El pasado 17 de abril de 2023, la Organizacion Mundial de la Salud (OMS) y siguiendo el consejo del Grupo Asesor Técnico de la OMS sobre la Evolución Viral del SARS-CoV-2, ha designado [XBB.1.16 (23B) una Variante de Interés](https://www.who.int/docs/default-source/coronaviruse/21042023xbb.1.16ra-v2.pdf) tras un aumento sostenido en su prevalencia y una ventaja de crecimiento sostenida notificada por varios países. 


En comparación con XBB.1.5 (23A), XBB.1.16 (23B) presenta **las mutaciones adicionales en la proteína Spike: E180V y K478R**. El **aminoácido 478 es T (treonina)** en la forma típica que se encuentra en el gen (wild type) del SARS-CoV-2 y **ha mutado a K (lisina) en Ómicron** (a través de una mutación de nucleótido C->A). **En XBB.1.16, el nucleótido A ha mutado ahora a G, dando como resultado el aminoácido R (arginina)**. Por lo tanto, esta no es una mutación de 2 pasos en el sentido de que siempre requiere 2 sustituciones de nucleótidos como en el caso de S:486P.


Sublinajes de interés detectados en Puerto Rico:


**XBB.1.16.6** con **S:F456L** adicional (a través de T22930A)


**XBB.1.16.9** con **S:F456L** adicional (a través de T22930G)


**XBB.1.16.13** con **ORF1a:G519S + ORF1a:G1101D**


**XBB.1.16.16** con **S:Q613H + S:S412N**


# [XBB.1.9 (EG/FL/HN S:252V + S:486P)](https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/six-months/?branchLabel=emerging_lineage&f_country=Puerto%20Rico&label=emerging_lineage:XBB.1.9)

Los sublinajes **XBB.1.9.1 y XBB.1.9.2** son descendientes de XBB.1 que adquirieron la mutacion **S:F486P** de manera independiente a XBB.1.5. Son los sublinajes de mayor crecimiento que contienen S:F486P detras de **XBB.1.16** y XBB.1.5. Los sublinajes XBB.1.9.1 y XBB.1.9.2 comparten las mutaciones **ORF1a:G1819S + ORF1a:T4175I + ORF9b:I5T**. A pesar de que ambos sublinajes fueron identificados como variantes bajo monitoreo por la Organizacion Mundial de la Salud, aun no reciben una asignacion de clado por parte de Nextstrain. No obstante, con el aumento de varios sublinajes preocupantes de XBB.1.9, como **EG.5.1/EG.5.1.1 y FL.1.5.1**, es probable que XBB.1.9 sea designado como [23C en las proximas semanas por el equipo de Nextstrain](https://github.com/nextstrain/ncov/issues/1073) debido a la rápida tasa de crecimiento; ahora con una proporción global de 20% a finales de julio de 2023.


Sublinajes de interés detectados en Puerto Rico:


**FL.1.5.1** con **S:F456L + S:478R + S:A701V**, más común en República Dominicana donde parece haberse vuelto dominante. En aumento en EE. UU./Canadá. Cuatro secuencias detectadas en Puerto Rico a fines de junio de 2023.


**HN.1 (FL.1.5.1.1)** con **S:A67S**


**FL.20 (XBB.1.9.1.20)** con **S:F456L (22928C) + S:Q52H**. De las primeras secuencias genómicas a nivel mundial de este sublinaje fueron detectadas en Puerto Rico y fueron evaluadas para apoyar la designacion de dicho sublinaje.


**EG.5.1** con **S:F456L + S:Q52H**


**EG.5.1.1** con **ORF1b:D54N (G13627A**)


# [Deriva antigénica recurrente de H69/V70 e Y144](https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/all-time?c=gt-S_69,70,144&d=tree,frequencies&f_country=Puerto%20Rico&p=full&tl=pango_lineage)


La evolución del SARS-CoV-2 se ha caracterizado por la aparición de conjuntos de mutaciones, en el contexto de "variantes de preocupación", que afectan las características del virus, incluidas la **transmisibilidad y la antigenicidad** probablemente **en respuesta al perfil inmunitario cambiante de la población humana**.


Se espera que una pequeña minoría de mutaciones afecte el fenotipo del virus de una manera que confiera una ventaja de aptitud, al menos en algunos contextos. Tales **mutaciones pueden alterar varios aspectos de la biología del virus, como la patogenicidad, la infectividad, la transmisibilidad y/o la antigenicidad**. Aunque se debe tener cuidado de no confundir las mutaciones que simplemente están presentes en los linajes en crecimiento con mutaciones que cambian la biología del virus.


La mayor parte de la pandemia ha sido impulsada por **3 mutaciones recurrentes** del dominio amino terminal (NTD): **H69/V70 & Y144**.


La deleción **Δ69–70** ha surgido varias veces en los númerosos sublinajes de SARS-CoV-2 y se entiende que **altera la conformación de un bucle expuesto del NTD** y se ha reportado que este cambio está asociado con una **mayor capacidad de infectividad del virus**.


La recurrencia de **ΔY144** es preocupante con respecto a la **respuesta de anticuerpos policlonales** como el bucle N3 (aminoácido en las posiciones 140-156, que son el **objetivo principal de una variedad de anticuerpos neutralizantes**), que ΔY144 cambia, se predice que se encuentra **entre las regiones más inmunogénicas de la proteína "Spike"**.


Esto destaca la necesidad del desarrollo de ensayos moleculares (qPCR) para la detección acelerada de sublinajes y estimaciones de proporción cuando el número de casos positivos es bajo o se sospecha que se ha introducido una nueva variante en la isla.

