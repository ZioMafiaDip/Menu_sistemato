Menu_sistemato
==============
l'immagine per lo stage è 1024X960
|->il bordo nero del reticolato in cui si muovono i tank è (46*18)X(40*20)=828X800
|    |->i bordi:
|      -top:80
|      -left:64
|      -right:892(1024-132)
|      -down:880(960-80)
|->il reticolato forma un matrice di 20 righe e 18 colonne
    |->l'idea è quella di usare le celle  della matrice come coordinate per inserire i pezzi della mappa
       righe->64+46*j
       colonne->80+40*j
       così da avere il top e left ricavato e poter inserire le immagini.
       volendo si può creare una serie di matrici testuali ed un'algoritmo che le interpreta.
       caso particolare è il mattone che si dimezza quando dal lato in cui viene colpito, e che richiede un trattamento 
       diverso, come ad esempio una classe a parte
