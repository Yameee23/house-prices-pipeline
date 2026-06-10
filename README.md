# House Prices - Pipeline de nettoyage
## Dataset

Pour ce projet j'ai manipuler un DataSet sur des maisons recuperer sur kaggle 
voici le lien :https://www.kaggle.com/datasets/juhibhojani/house-price

## Ce que j'ai fait

Dans ce projet j'ai voulu rednre ce data utilisable pour du machine learning , pour cela j'ai commencer  par 
nettoyer le Dataset en supprimant les colonnes inutiles (avec trop de Nan etc ) 
en utilisant la fonction Drop() . Puis je suis passer a l'encodage ou j'ai transformé les colonnes texte en nombres pour
que le modèle ML puisse les utiliser et pour finir j'ai normalisé les colonnes numériques pour les ramener entre 0 et 1,
ce qui permet au modèle ML de comparer les colonnes équitablement sans qu'une colonne domine les autres à cause de ses 
grandes valeurs.

## Technos utilisées

Pour ce projet j'ai utilisé Python avec les librairies Pandas et scikit-learn, et DataSpell comme environnement de développement.