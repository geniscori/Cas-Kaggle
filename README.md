# Cas-Kaggle
El dataset que tractarem tracta sobre accidents de cotxe als 49 estats d'Estats Units d'Amèrica del febrer del 2016 fins al desembre del 2021.

## Objectius
El principal objectiu és de reconèixer quins són els factors que afecten principalment la severitat d'un accident. A més, farem una anàlisi de les dades per tal de respondre diferents preguntes sobre a què es deu un accident, quins dies succeeixen més accidents, a quins llocs passen més sinistres, a prop de quins objectes freqüents dels carrers n'ocurreixen més...
També, intentarem fer diferents models per tal de predir la severitat dels accidents. D'aquests models, triarem el que compleixi unes mètriques que posteriorment descriurem.

##  Metodologia
Primer farem *data cleaning* per tal de detectar i corregir les dades que estiguin corruptes o que faltin. Seguidament farem una primera anàlisi de les dades i donarem resposta a algunes de les preguntes que hem formulat anteriorment. Després, seleccionarem la nostra variable objectiu i utilitzarem mètodes de resampleig per balencejar les nostres dades. Finalment, entrenarem diferents models i farem les prediccions corresponents.

## Descripció del dataset

Es tracta d'un dataset sobre accidents de trànsit a tot el país, que cobreix els 49 estats dels EUA. Les dades d'accidents es recullen des del febrer del 2016 fins al desembre del 2021, mitjançant diverses API que proporcionen dades d'incidents (o esdeveniments) de trànsit en streaming. Aquestes API transmeten dades de trànsit capturades per una varietat d'entitats, com ara els departaments de transport dels Estats Units i l'estat, les agències d'aplicació de la llei, les càmeres de trànsit i els sensors de trànsit dins de les xarxes de carreteres. Actualment, hi ha uns 2 milions de registres d'accidents. El dataset ha estat extret de la següent adreça del web *Kaggle*: https://www.kaggle.com/sobhanmoosavi/us-accidents
