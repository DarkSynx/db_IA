# db_IA
base de donné pour intelligence artificiel en Français

V 0.1a

dico.db

encyclo.db

synonyme.db

verbes.db

les base de donnés sont au format SQLite3 
les tables porte le nom du fichier soit 
dico pour dico.db 
encyclo pour encyclo.db
synonyme pour synonyme.db
et
verbes pour verbes.db

toutes les base sont composé de 3 colones

la colone "0" : le hash sha256 du mot , verbe ou de la formule

la colone "1" : le mot , le verbe , la formule , le terme en question 

la colone "2" : contient de l'information surle mot , le verbe , la formule , le terme en question  cette information peu renvoye dans le cas de la base de verbe au dictionnaire a l'encyclopédie ou au synonyme . 


une base de donné Primaire de cartographie des liens logique ou static entre les mots sera réaliser prochainement 
permettant ainsi de centraliser l'exploitation de ces 4 bases ous base de donné .




