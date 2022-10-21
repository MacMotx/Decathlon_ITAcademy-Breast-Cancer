# Hackathon_ITAcademy Selection phase Test

> The selection phase consisted in a dataset of breast-tumor morfological qualities as independent variables and the diagnostic as the dependent variable. Classification algorithms we're used, i.e. Random Forest Classifier and Logistic regression, in conjunction with some dimensionality reduction techniques like Principal Component Analysis and Recursive Feature Elimination.





Layout

🌌 Background

El càncer de mama és el més comú entre les dones del món. Representa el 25% de tots els casos de càncer i va afectar més de 2,1 milions de persones només el 2015. Comença quan les cèl·lules de la mama comencen a créixer de manera descontrolada. Aquestes cèl·lules solen formar tumors que es poden veure mitjançant raigs X o sentir-se com embalums a la zona del pit.

✅ Objectius

Comprendre el conjunt de dades i netejar-lo (si cal). Construir models de classificació per predir si el tipus de càncer és maligne o benigne, variable "diagnosi" 0 benigne i 1 maligne. També ajustar els hiperparàmetres i comparar les mètriques davaluació de diversos algorismes de classificació.

📈 Dataset

Per poder entrenar el model clickeu al següent link: Download train

I per poder avaluar-vos tindreu el següent conjunt de dades per al testeig: Download test Submission

Per realizar l'entrega es demana un fitxer csv amb el nom "predictions.csv" on estará la columna de diagnosis amb un 0 o 1, en funció de si es benigne o maligne. Notar que cada fila del predictions correspon a la predicció de la fila del test amb les dades. Evaluation

L'avaluació es tindrà en compte el següent:

- 400/600:(OBJECTIUS) Això s'obtindrà a partir de la puntuació (macro) f1 del model predictiu. Comparant les prediccions que ha fet el vostre model sobre test_x versus la veritat terrestre.

- 200/600:(OBJECTIUS) Si ets capaç d'automatitzar l'extracció de dades dels PDF i incorporar-les a la formació del model. S'atorgaran 100 punts.

Stack proposat:

Python


