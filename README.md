
#lien google pour telecharger les données allociné utilisées pour l'entrainement:
https://drive.google.com/drive/folders/1fiul6DrqkYG2tWdsF9wEvS86MfwokVJq


#l'objectif ici  de mon travail est de mettre en place un modele pour  prédire le sentiment d'un avis allocine(positif ou négatif )

pour se faire je disposes d'avis allociné que j'ai scrapé(note,avis) : 104001 lignes

#les notes allociné varient entre :([0.5, 1. , 1.5, 3. , 4. , 3.5, 2.5, 2. , 5. , 4.5])


J'ai considéré dans cette premiere partie qu'une note >=3.5 est un avis positif et une note<=2.5 est un avis negatif


Ensuite j'ai utilisé le countVectorizer et le Tfid comme algorithme de vectorisation des avis et la regression linéaire comme algorithme de classification
en valadidant a chaque fois les résultats sur différents echantillons.


resultats:

    90.08 de precision de prédiction avec le Tfid et le trigramme

    89.60. de precision de prédiction pour le countVectorizer et le bigramme




je reviens bientot vous presenter les resultats en utilisant le doc2vec et word2vec comme algorithme de vectorisation des données textuelles
