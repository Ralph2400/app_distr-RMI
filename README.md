1- tout d'abord, on compile tout les fichiers



2- a l'aide de la commande rmiregistry on demare le service Naming RMIregistry pour permettre la connection au local host

(base) Ralphs-MBP:RMI ralph$ rmiregistry
      
      
      
3- A present on peut faire marcher le server pour permettre des connection au serveur et l'acces a l'objet calculator 

(base) Ralphs-MBP:RMI ralph$ java CalculatorServer



4- A present on peut lancer l'application client qui va se connecter au serveur et afficher les resultat ci dessous grace a l'echange entre client et server et l'acces des methodes de la classe CalculatorImpl

(base) Ralphs-MBP:RMI ralph$ java CalculatorClient
1
9
18
3
(base) Ralphs-MBP:RMI ralph$ 
