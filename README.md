# Tp3
ON commence a accepter l'invitation de collaboration dans notre boite mail. 



dans courseGIT, on fait la commande git clone git@github.com:Patate276/tp3.git
ce qui permet de cloner le fichier tp3 dans le repertoire locale. 

pour synchronisez les fichiers distant, on utolise alors les commandes : 

-git add src/Cryptomonaie.java
-git add README.md
-git commit -m " ajout distant du fichier  Cryptomonaie et src "
-git push

on a donc nos 2 fichiers déposés dans le fichiers distants
on effectue ensuite : git pull

on a donc bien tout synchronisé. 


Etant Porthos, on travaillera sur Portefeuille.java

Une fois les erreurs corriger, on creer une branche PorthosCoin,  avec git checkout -b test

on creer un nouveau fichier avec New-Item test.txt ( Powershell )
on ajoute alors ce fichier dans git avec git add test.txt

étant donné que l'on change de branche, le fichier test.txt n'est plus visible, car il n'appartient pas a cette branche. 




Effectuer un git add README.md puis un git commit -m "nouveau commit sur la branche principale"

git log --graph --oneline --all --decorate --topo-order


avec git checkout main, on est alors dans la branche principale. 

on effectue alors git merge test, qui nous permet de fusionner la branche main et la branche test. 


ainsi, on peut désoramis retrouver le test.txt si l'on effectue ls. 


On creer enssuite la branche PorthosCoin. 
git checkout -b PorthosCoin

on fusionne ensuite cette branche au main : git merge main




![image_a_integrer](https://github.com/user-attachments/assets/fe91d416-3142-4789-b6e9-c1564ff6fc29)



