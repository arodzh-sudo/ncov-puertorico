---
title: Vigilancia Genómica de SARS-CoV-2 en Puerto Rico
authors: Arnold Rodriguez-Hilario, MS
authorLinks: "https://github.com/arodzh-sudo"
date: "2022-12-13"
dataset: "https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/all-time?branchLabel=emerging_lineage&c=pango_lineage&d=tree,frequencies&f_country=Puerto%20Rico&l=clock&m=div&p=full&showBranchLabels=all"
abstract: "

Se implementó un flujo de trabajo básico de **vigilancia genómica utilizando la plataforma Nextstrain** para monitorear en tiempo real, la evolución del **SARS-CoV-2 en Puerto Rico**. Este programa permite la visualización de árboles filogenéticos para evaluar la divergencia de los genomas de SARS-CoV-2 de Puerto Rico en comparación con el genoma de referencia Wuhan-Hu-1.


La tecnología de **secuenciacion de proxima generación (NGS, por sus siglas en ingles)** permite detectar grupos de casos y monitorear nuevas variantes del virus. Los grupos de virus que comparten un conjunto de mutaciones en el genoma se denominan linajes. Algunas variantes que pertenecen a linajes específicos pueden tener características como la capacidad de propagarse más rápidamente, causar una enfermedad más grave o afectar el tratamiento clínico, como el tratamiento con anticuerpos monoclonales. Estas variantes pueden clasificarse como variantes de interés (VOI), variantes en seguimiento (VBM), variantes de preocupación (VOC) o variantes de gran preocupación.

![](https://raw.githubusercontent.com/nextstrain/ncov-clades-schema/master/clades.svg)  
Relaciones filogenéticas de los grupos monofiléticos de SARS-CoV-2 clasificados por Nextstrain, fuente: [Nextstrain](https://nextstrain.org/)
"
---


# [Actualización - 22 de febrero de 2023, XBB.1.9.1 y XBB.1.9.2 - 2023](https://nextstrain.org/fetch/genome.ucsc.edu/trash/ct/singleSubtreeAuspice_genome_19c13_6258c0.json?f_userOrOld=uploaded%20sample&label=id:node_7610599&tl=pango_lineage_usher)

Los sublinajes **(XBB.1.9.1 y XBB.1.9.2)** son los descendiente más recientes del linaje **XBB**, que han adquirido varias sustituciones de preocupación, entre ellas S:486P, sustitución clave en el sublinaje XBB.1.5 y se encuentran en crecimiento en distintas partes de Europa y Asia. Estos sublinajes presentan [mayor transmisibilidad relativa que XBB.1.5 según estimaciones en la plataforma cov-SPECTRUM](https://cov-spectrum.org/explore/World/AllSamples/Past6M/variants?nextcladePangoLineage=XBB.1.9*&). En los Estados Unidos, se ha detectado XBB.1.9.1 y ha mantenido crecimiento en la costa sureste, centro y oeste, aunque sigue representando <1 % en todo el país.


**XBB.1.9** -> ORF1a:G1819S, ORF1a:T4175I


**XBB.1.9.1** -> **S:F486P** (luego de C11956T), Indonesia/Singapore/Malaysia/UK


**XBB.1.9.2** -> **S:F486P** (luego de 27507C, 16878T), Indonesia/Singapore


**EG.1 (XBB.1.9.2.1)** -> **S:Q613H** on N:L219F


Al momento, en Puerto Rico no se han detectado sublinajes que pertenezcan a la familia de XBB.1.9

# [CH.1.1 - Puerto Rico 2023](https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/six-months?branchLabel=emerging_lineage&c=gt-S_346,444,452,486&d=tree,entropy&f_country=Puerto%20Rico&label=clade:22D%20%28Omicron%29&p=full)


**CH.1.1 (BA.2.75.3.4.1.1.1.1)** parece haber surgido en Agosto de 2022, posiblemente en Australia. [A febrero de 2023, la mayoría de las secuencias de este linaje se han detectado en el Reino Unido, pero también se han detectado muchas partes del mundo](https://cov-spectrum.org/explore/World/AllSamples/Past6M/variants?nextcladePangoLineage=CH.1.1*&). En los Estados Unidos, [se estima que CH.1.1 representa alrededor del 0.9-1.9% de las infecciones por SARS-CoV-2](https://covid.cdc.gov/covid-data-tracker/#variant-proportions).


CH.1.1 es descendiente de **BA.2.75 (22D)** que adquirió un conjunto mutacional importante en la región del dominio de unión al receptor (RBD), que es el objetivo principal de los anticuerpos neutralizantes contra el SARS-CoV-2.


Este sublinaje presenta **4 de las mutaciones más importante** según el estimador de escape de anticuerpos para mutaciones en el RBD de SARS-CoV-2, desarrollado por [Jesse Bloom en el Departamento de Ciencias del Genoma de la Universidad de Washington](https://jbloomlab.github.io/SARS2_RBD_Ab_escape_maps/escape-calc/):


**F486S, R346T, K444T, L452R**


En Puerto Rico, se han detectado 5 muestras clasificadas como CH.1.1 con fechas de colección entre Noviembre y Enero 2023.


# [XBB.1.5 (23A)](https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/six-months/?branchLabel=emerging_lineage&c=gt-S_486&d=tree,entropy&f_country=Puerto%20Rico&label=clade:22F%20%28Omicron%29&p=full&tl=pango_lineage)


XBB.1.5 (23A) sigue siendo el linaje circulante aparentemente más apto. Ya es dominante en la costa este de los EE. UU. y se prevé que lo sea en el resto de los Estados Unidos a mediados de febrero 2023. 


En Puerto Rico, se han detectado múltiples muestras clasificadas XBB.1.5 con fechas de colección entre Diciembre 2022 y Enero 2023, posiblemente representando cerca del [70% de los casos de infeccion por SARS-CoV-2](https://observablehq.com/@andy-bloch/walgreens-covid-19-tracker).


XBB.1.5 es descendiente de XBB (22F), una variante recombinante, lo que significa que su genoma consiste en una combinación de dos variantes "parientes" diferentes. **XBB es una recombinante del linaje BJ.1 (BA.2.10.1.1) (21L) y BM.1.1.1 (BA.2.75.3.1.1.1) (22D)**, con un punto de ruptura en la región S1 del gen de la proteína “Spike”. XBB contiene el conjunto mutacional que se encuentra en todos los descendientes de BA.2, esto incluye mutaciones en el gen de la proteína “Spike” de BJ.1 en **S:V83A, S:Y144-, S:H146Q, S:Q183E, S:V213E, S:G339H, S :R346T, S:L386I, S:V455P y S:G446S**, y mutaciones de BM.1.1.1 en **S:N460K, S:F486S y S:F490S**.


**XBB.1.5**, surge con una nueva mutación clave: **F486P**. La sustitución S:F486P se distingue de las anteriores debido a que requiere dos sustituciones de nucleótidos: **T23018C y T23019C**. Se prevé que esta mutación (S:486P) [aumente la afinidad significativamente al restaurar la unión al receptor humano ACE2 mientras se mantiene un perfil de evasión inmunitaria](https://www.biorxiv.org/content/10.1101/2023.01.03.522427v2).


# [BA.2 vs BA.5 - Puerto Rico 2023](https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/six-months?branchLabel=emerging_lineage&c=emerging_lineage&d=tree,frequencies&f_country=Puerto%20Rico&label=clade:21L%20%28Omicron%29&p=full&showBranchLabels=all)

A menudo se discuten **dos rasgos principales** relacionados con la **proteína "Spike"** con respecto al **escape inmunológico (anticuerpos) y la unión al receptor humano ACE2**, el primero se refiere a cambios genéticos relacionados con la **susceptibilidad del reconocimiento de anticuerpos** y el segundo, una medida de qué tan bien el virus puede **adherirse y entrar en las células del huésped**.


Las **mutaciones en la región genómica** que codifica para la proteína "Spike" pueden proporcionar una **ventaja de ciertos sublinajes sobre otras variantes** que carecen de esas mutaciones. **Algunas variantes exitosas han sido buenas en uno de estos dos rasgos**. Recientemente, se está observando que los linajes en circulación están adquiriendo mutaciones que le han brindado **ventajas en estos dos rasgos (escape inmunológico y afinidad al ACE2)**.


De los más de 800 sublinajes y recombinantes de Ómicron, los que están en mayor circulación (a nivel mundial y local) son miembros de dos orígenes genéticos: **BA2 y BA.5**.


BA.5:


**BA.5.2.1, BF/BE, BQ.1.1**


BA.2:


**BA.2.75, BM/BN, XBB.1.5, CH.1.1**


Puerto Rico **no estuvo muy expuesto a la familia de sublinajes BA.2.75 (BM/BN)** como se vio en el sur y noroeste de los Estados Unidos, más bien se vio afectado por los sublinajes **BA.5 (BE/BF)**. Esto pone en **riesgo a la isla de un aumento de casos** de COVID-19 causado por sublinajes más aptos de la familia **BA.2.75 (XBB.1.5, CH.1.1, XBN, XBP)**


Actualmente, XBB.1.5 es el linaje predominante en Puerto Rico con una frecuencia estimada de 60-70%.


# [Deriva antigénica recurrente de H69/V70 e Y144](https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/all-time?branchLabel=emerging_lineage&c=gt-S_69,70,144&d=tree,frequencies&f_country=Puerto%20Rico&p=full&tl=pango_lineage)

La evolución del SARS-CoV-2 se ha caracterizado por la aparición de conjuntos de mutaciones, en el contexto de "variantes de interés", que afectan las características del virus, incluidas la **transmisibilidad y la antigenicidad**, probablemente **en respuesta al perfil inmunitario cambiante de la población humana**.


Se espera que una pequeña minoría de mutaciones afecte el fenotipo del virus de una manera que confiera una ventaja de aptitud, al menos en algunos contextos. Tales **mutaciones pueden alterar varios aspectos de la biología del virus, como la patogenicidad, la infectividad, la transmisibilidad y/o la antigenicidad**. Aunque se debe tener cuidado de no confundir las mutaciones que simplemente están presentes en los linajes en crecimiento con mutaciones que cambian la biología del virus.


La mayor parte de la pandemia ha sido impulsada por **3 mutaciones recurrentes** del dominio amino terminal (NTD): **H69/V70 e Y144**.


La deleción **Δ69–70** ha surgido varias veces en los númerosos sublinajes de SARS-CoV-2 y se entiende que **altera la conformación de un bucle expuesto del NTD** y se ha reportado que este cambio está asociado con una **mayor capacidad de infectividad del virus**.


La recurrencia de **ΔY144** es preocupante con respecto a la **respuesta de anticuerpos policlonales** como el bucle N3 (aminoácido en las posiciones 140-156, que son el **objetivo principal de una variedad de anticuerpos neutralizantes**), que ΔY144 cambia, se predice que se encuentra **entre las regiones más inmunogénicas de la proteína "Spike"**.


Esto destaca la necesidad del desarrollo de ensayos moleculares (qPCR) para la detección acelerada de sublinajes y estimaciones de proporción cuando el número de casos positivos es bajo o se sospecha que se ha introducido una nueva variante en la isla.

# [SARS-CoV-2 - Puerto Rico 2020](https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/all-time?branchLabel=emerging_lineage&c=pango_lineage&d=tree,frequencies&dmax=2020-07-23&f_country=Puerto%20Rico&p=full&tl=pango_lineage)

**COVID-19**, la enfermedad causada por el nuevo coronavirus *SARS-CoV-2*, se identificó por primera vez en Puerto Rico el 13 de marzo de 2020. Las primeras muestras secuenciadas correspondieron a viajeros europeos que llegaron en un crucero y residentes locales que tuvieron contacto cercano con familiares con historial de viajes recientes. La asignación de linajes PANGO identificó el linaje **A.1** en las muestras de viajeros, mientras que los linajes **B.1 y B.1.1** se identificaron en las muestras de residentes. Los linajes **B.1.x** predominaron en los Estados Unidos y las Américas en ese momento, en contraste con **A.1** que predominó en Europa. 


La fase inicial de la epidemia se caracterizó por la detección de una amplia diversidad de linajes **B.1.x** que circulaban en baja frecuencia por períodos cortos de tiempo, lo que sugiere que la epidemia local inició por múltiples eventos de introducción [(Santiago et al. (2022), Genomic surveillance of SARS-COV-2 in Puerto Rico enabled early detection and tracking of variants. Communications medicine).](https://doi.org/10.1038/s43856-022-00168-7)


# [B.1.588 - 2020](https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/all-time?branchLabel=aa&c=pango_lineage&d=tree,frequencies&dmax=2021-02-17&dmin=2020-06-11&f_country=Puerto%20Rico&f_pango_lineage=B.1.588&p=full&tl=pango_lineage)

En agosto de 2020, se detectó el linaje B.1.588 en varios municipios de Puerto Rico. **B.1.588** se convirtió rápidamente en el linaje predominante en Puerto Rico, alcanzando casi el **70% en proporción y provocando la primera ola epidémica en noviembre de 2020**. La circulación del linaje B.1.588 disminuyó durante el invierno de 2020 e inicios del año 2021, una temporada marcada por viajes frecuentes debido a las festividades.


B.1.588 se separó de su linaje parental B.1 tras la aparición de tres (3) mutaciones no conservativas: **T20I en la proteína "Spike" y dos mutaciones en la proteína de la nucleocápside (N); M234I y D401Y**.


# [B.1.1.7 (Variante Alfa/20I/V1) - Puerto Rico 2021](https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/all-time?branchLabel=aa&f_country=Puerto%20Rico&label=clade:20I%20%28Alpha,%20V1%29&p=full&tl=pango_lineage)

Adaptado de [CoVariants](https://covariants.org/variants/20I.Alpha.V1)


Anunciada el 14 de diciembre de 2020 por la Organizacion Mundial de la Salud (OMS), B.1.1.7 parece haber surgido y/o haberse expandido inicialmente en el sureste del Reino Unido.


La **variante Alfa (B.1.1.7)** fue de los primeros linajes asociados con **múltiples mutaciones en la proteína "Spike"**. Más notablemente **N501Y** y una eliminación en las posicion **69/70**. La deleción 69/70 en esta variante hace que las pruebas TaqPath dé un resultado negativo en el ensayo de la proteína S, lo que puede proporcionar un indicador útil de la prevalencia de esta variante (un fenómeno denominado *S-gene target failure* o SGTF).


Además, esta variante exhibió una deleción adicional en **Y144-** y una sustitución en **P681H** (adyacente al sitio de escisión de furina).


B.1.1.7 se detectó por primera vez en Puerto Rico en enero de 2021, circulando junto con el linaje predominante local B.1.588 y otros linajes B.1.x. Filogenéticamente, Alfa mostró múltiples grupos monofiléticos que divergían a lo largo de un período de circulación de 4 a 5 meses. Los grupos monofiléticos más grandes de Alfa se distinguieron por sustituciones en las regiones del genoma no estructural, incluidas las regiones ORF1ab, ORF3, ORF7a y ORF8, lo que posiblemente afectó la síntesis de ARN y la replicación del virus.


# [B.1.617.2 y sublinajes AY (Variante Delta/21A/21I/21J) - Puerto Rico 2021](https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/all-time?branchLabel=emerging_lineage&c=pango_lineage&f_country=Puerto%20Rico&label=clade:21A%20%28Delta%29&p=full&tl=pango_lineage)

Adaptado de [CoVariants](https://covariants.org/variants/21A.Delta)


La **variante Delta (B.1.617.2)** se detectó por primera vez en India a finales de 2020 y se expandió rápidamente, dominando en casi todos los países al terminar el año 2021. **Delta** mostró múltiples sustituciones y deleciones en la proteína "Spike", las más importantes en las posiciones **L452R y P681**, los cuales afectan la unión de anticuerpos. **B.1.617.2** tenía mutaciones adicionales en la proteina "Spike" en las posiciones **T19R, R158G, T478K y D950N**. Además, tiene una deleción en las posiciones **E156- y F157-**.


La **variante Delta** se había generalizado durante el segundo trimestre de 2021 y B.1.617.2 era el linaje predominante en muchos países del mundo. A medida que la secuenciación se volvió más accesible y aumentaron los esfuerzos de vigilancia genómica, la Red PANGO comenzó a **dividir el linaje B.1.617.2 en grupos relacionados más pequeños (AY.*)** que podían rastrearse por separado. Los linajes AY.x más nuevos permitieron a los investigadores hacer un seguimiento a una escala más fina en términos de su ubicación geográfica predominante y sus mutaciones asociadas.


Delta se detectó por primera vez en Puerto Rico en junio de 2021, durante un período en el que la transmisión del SARS-CoV-2 estaba disminuyendo y la campaña de vacunación avanzaba rápidamente. Sin embargo, la transmisión de Delta desplazó a la mayoría de los linajes circulantes y dio lugar a la tercera ola epidémica. Para finales del verano 2021 el 100% de los casos de COVID-19 muestreados y secuenciados fueron causados por Delta. 


# [B.1.1.529 (Omicron) - Puerto Rico 2021](https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/all-time?branchLabel=emerging_lineage&c=pango_lineage&f_country=Puerto%20Rico&label=clade:21M%20%28Omicron%29&p=full&tl=pango_lineage)

Adaptado de [CoVariants](https://covariants.org/variants/21K.Omicron)

La variante designada por la Organización Mundial de la Salud (OMS) más reciente es **Omicron (B.1.1.529/21M)**, parece haber surgido en noviembre de 2021, posiblemente en Sudáfrica.


Esta variante es principalmente de preocupación debido a la **gran cantidad de mutaciones (>50) en comparación con la cepa ancestral de Wuhan, más de 30 de ellas dentro de la region de la proteína "Spike"**. Muchas de estas sustituciones se encuentran en el **dominio de unión al receptor (RBD)** y el dominio **N-terminal** y, por lo tanto, pueden desempeñar funciones clave en la unión del receptor humano ACE2 y el reconocimiento de anticuerpos.


21M (Omicron), que corresponde al linaje Pango B.1.1.529, se dividió en clados más pequeños que incluyen **21K (BA.1)**, su clado hermano **21L (BA.2)** y otras sublinajes diversos de Omicron, como **22A (BA.4), 22B (BA.5), 22C (BA.2.12.1), 22D (BA.2.75), 22E (BQ.1) y 22F (XBB)**.


Con la aparición de **Omicron (BA.1) a finales de 2021**, vimos una variante hipertransmisible diferente a las anteriores con un aumento estimado de 3 veces en su número de reproducción efectiva en comparación con la variante Delta. Para finales de enero 2022, 100% de casos de COVID-19 muestreados y secuenciados fueron causados por la variante Omicron.


# [BA.1 & BA.1.1 (21K) - Puerto Rico 2021-2022 ](https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/all-time?branchLabel=aa&c=pango_lineage&d=tree,frequencies&f_country=Puerto%20Rico&label=clade:21K%20%28Omicron%29&p=full)

En contraste con los Estados Unidos, Puerto Rico no observó dos olas consecutivas de los linajes BA.1 y BA.1.1. El linaje **BA.1.1 (BA.1 + mutación S:346K)** dominó rápidamente en Puerto Rico desde su detección, causando el cuarto y más alto pico epidémico en Puerto Rico que se observó a mediados de diciembre de 2021 hasta Febrero 2022. **Más del 70% de los casos de COVID-19 secuenciados en diciembre 2021, enero y febrero 2022, fueron identificados como BA.1.1**. 


En Puerto Rico, el sublinaje presentó una acumulación de mutaciones adicionales, especialmente en la región del gen S de la proteína “Spike”, como por ejemplo **S:N417K y S:K440N**, las cuales indujeron fenotipos con mayor aptitud y transmisibilidad que linajes anteriores.


# [BA.2 (21L) - Puerto Rico 2021-2022 ](https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/all-time?c=pango_lineage&d=tree,frequencies&dmax=2022-08-01&dmin=2021-11-09&f_country=Puerto%20Rico&f_pango_lineage=BA.2,BA.2.1,BA.2.10,BA.2.12,BA.2.12.1,BA.2.13,BA.2.13.1,BA.2.20,BA.2.21,BA.2.3,BA.2.37,BA.2.38,BA.2.65,BA.2.73,BA.2.76,BA.2.9&label=clade:21L%20%28Omicron%29&p=full)

Adaptado de [CoVariants](https://covariants.org/variants/21L.Omicron)

**BA.2 (21L) y BA.1 (21K)** comparten **38 mutaciones** de nucleótidos y aminoácidos, pero **BA.2 tiene 27 adicionales**.


Mirando solo la región genómica de la proteína "Spike", ambos comparten 21 mutaciones de aminoácidos, BA.1 tiene 12 mutaciones de aminoácidos únicas y BA.2 tiene 6 adicionales (más una deleción/mutación). En particular, **BA.2 carece de la eliminación en S:H69- y S:V70-** lo que provoca la "caída del gen S" o SGTF que se ha utilizado para rastrear BA.1 en las pruebas de PCR TaqPath.


Las 6 mutaciones Spike adicionales en BA.2 son: **S:T19I, S:V213G, S:S371F, S:T376A, S:D405N y S:R408S**. Además de esto, hay una deleción de 9 nucleótidos de la posición 21633-21641 que conduce a las deleciones y mutaciones S:L24-, S:P25-, S:P26- y S:A27S.


El linaje **BA.2 superó al linaje BA.1.1 en marzo 2022** para convertirse en linaje predominante en Puerto Rico durante mediados del 2022. BA.2 y varios sublinajes (**BA.2.9, BA.2.73, BA.2.12.1**) causaron el pico epidémico en Puerto Rico que se observó durante el verano 2022, comparable al pico epidemico de BA.1.1 en diciembre 2021 y enero 2022. 


# [BA.2.73 - Puerto Rico 2022 ](https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/all-time?branchLabel=aa&c=pango_lineage&d=tree,frequencies&dmax=2022-08-01&f_country=Puerto%20Rico&f_pango_lineage=BA.2.73&p=full&tl=pango_lineage)

Mediante análisis filogenéticos, identificamos un grupo que secuencias genómicas que presentaban un perfil genético distinto al linaje BA.2 original. Adicional a las mutaciones presentes en el linaje BA.2, este grupo de secuencias genómicas presentan la mutación **G257S en el gen S que codifica para la proteína "Spike"** y la mutación **P2287S en el ORF1a** que codifica para proteínas no estructurales. 


Estimaciones realizadas en la plataforma **cov-SPECTRUM** sugieren que esta **combinación de mutaciones confiere una ventaja de crecimiento relativo de ~30% sobre el linaje BA.2** original (Fuente: [covSPECTRUM])(https://cov-spectrum.org/explore/World/AllSamples/Past6M/variants?aaMutations=ORF1a%3AP2287S%2CS%3AG257S&pangoLineage=BA.2*&)


La primera secuencia fue detectada el 7 de marzo de 2022 en Puerto Rico (EPI_ISL_11176165). Desde entonces, se ha detectado en los Estados Unidos (31 jurisdicciones), y en más de 10 países internacionalmente.


El 13 de mayo de 2022, [presentamos una solicitud de consideración al Comité de Designación de Linajes (LDC, por sus siglas en inglés) del grupo PANGO, para la evaluación de este posible nuevo sublinaje.](https://github.com/cov-lineages/pango-designation/issues/632) El 13 de junio de 2022, el LDC acepto la solicitud y designaron el nuevo sublinaje como **BA.2.73**, [identificado como un sublinaje de la variante Ómicron BA.2 en Puerto Rico y USA.](https://github.com/cov-lineages/pango-designation/commit/9951f5664d2874df6a757b7ce851f1d0b4a8438e)


# [BA.4 (22A)](https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/six-months?branchLabel=aa&c=pango_lineage&d=tree,frequencies&f_country=Puerto%20Rico&gmax=29639&gmin=240&label=clade:22A%20%28Omicron%29&m=div&p=full&tl=pango_lineage)

Adaptado de [CoVariants](https://covariants.org/variants/22A.Omicron)

Al igual que con todas las variantes de Ómicron, BA.4 es clasificada como Variante de Preocupación (VOC, por sus siglas en inglés). El sublinaje BA.4 comparte varias mutaciones de la proteína "Spike" con el sublinaje BA.1.1 e incluso contiene más mutaciones en esta región que BA.2. A diferencia de las demás subvariantes de Ómicron, BA.4 no exhibe la mutación **S:Q493R**, pero si presenta las mutaciones **S:L452R y S:F486V**, junto con las deleciones **S:H69- y S:V70-**, que provocan el **"*S-gene target failure*"**.


Los sublinajes BA.4.1 y BA.4.6 se establecieron como los sublinajes dominantes durante los meses de septiembre y octubre 2022 de esta subvariante, con las sustituciones **S:V3G y S:R346T** respectivamente en el gen de la proteína "Spike".


# [BA.5 (22B)](https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/six-months?branchLabel=emerging_lineage&c=pango_lineage&d=tree,frequencies&f_country=Puerto%20Rico&gmax=29639&gmin=240&label=clade:22B%20%28Omicron%29&p=full&showBranchLabels=all&tl=pango_lineage)

Adaptado de [CoVariants](https://covariants.org/variants/22B.Omicron)

BA.5 y sus sublinajes es la variante dominante a nivel global, donde es responsable de alrededor del 80% de las infecciones. 


El linaje  de más rápido crecimiento dentro de esta familia es el BQ.1 (22E), en particular, con mutaciones adicionales S:R346T y S:Y144, una combinación que ha surgido varias veces de forma independiente.


En el caso de BA.5 en Puerto Rico, BA.5.1 y BA.5.2.1 se han establecido como los sublinajes dominantes de esta subvariante, antes de ser desplazados mas recientemente por BQ.1.1. La sustitución **L37F** en el **marco abierto de lectura 10 (ORF10)** aparenta haber conferido un tipo de ventaja a BA.5.1 sobre BA.5. Las mutaciones que distinguen a BA.5.2.1 de BA.5 y BA.5.1, se encuentran en el gen de la **Nucleocápside (N): la deleción 30/32 y la sustitución S33F**. 


Todas estas mutaciones y deleciones están directamente asociadas a la [supresión de genes de interferón tipo I (IFN-I) y genes estimulados por IFN](https://www.nature.com/articles/s41423-021-00807-4)


Varios otros sublinajes descendientes de BA.5.2.1 **(BF.5, BF.7 y BF.11)** mostraron una gran ventaja de crecimiento en comparacion con otros sublinajes de la familia BA.5. En especifico, el linaje BF.11 presentaba la sustitución **S:R346T**, mutación clave en el **dominio de unión al receptor (RBD)** que conduce a un escape inmunológico sin afectar la capacidad del virus para unirse a las células humanas en el receptor ACE2.

# [BQ.1 (22E) en Puerto Rico](https://nextstrain.org/community/arodzh-sudo/ncov-puertorico/Puerto-Rico/six-months/?branchLabel=aa&c=pango_lineage&d=tree,frequencies&f_country=Puerto%20Rico&m=div&p=full&tl=pango_lineage&label=clade:22E%20%28Omicron%29)

Adaptado de [CoVariants](https://covariants.org/variants/22E.Omicron)

BQ.1/22E surgió a mediados de 2022, posiblemente en África central u occidental. Se identificó por primera vez como variante 'de interés' en agosto y se ha expandido globalmente desde entonces. En Puerto Rico, el linaje BQ.1 se detectó a finales del mes de Septiembre 2022. Desde entonces, es el grupo monofilético de mayor proporción en la Isla.


Al igual que con todos los sublinajes de Ómicron, BQ.1 (22E) es de motivo de preocupación debido al aumento notable en la transmisión y la evasión inmunitaria de esta familia de linajes. Tienen una gran cantidad de mutaciones en el gen “Spike”, muchas de ellas en el **dominio de unión al receptor (RBD) y el dominio N-terminal**, que pueden desempeñar funciones clave en la unión del receptor humano ACE2 y el reconocimiento de anticuerpos.


BQ.1/22E comparte todas las mutaciones (incluso en la “Spike”) encontradas en BA.5 (22B) pero también tiene mutaciones adicionales.  
Dentro del “Spike”, BQ.1 tiene otras mutaciones en **S:K444T y S:N460K**. Fuera del “Spike”, tiene más mutaciones en: **ORF1a:Q556K, ORF1a:L3829F, ORF1b:Y264H, ORF1b:M1156I, ORF9b:P10F y N:E136D**.


Varios linajes dentro de BQ.1, en particular el sublinaje **BQ.1.1**, ha adquirido una mutación adicional [**S:R346T** que ayuda al virus a evadir los anticuerpos neutralizantes](https://www.thelancet.com/journals/laninf/article/PIIS1473-3099(22)00642-9/fulltext).


