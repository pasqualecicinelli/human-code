!-- 
****************
    HUMAN CODE  
****************
 -->


## TRACCIA
# Scegliere cosa guardare su Netflix
Che barba, che noia, che noia, che barba!
Perché ci si mette sempre un’ora a scegliere cosa guardare la sera? Certo è difficile mettere d’accordo i gusti di tutti, poi dipende anche in base al tempo (o al sonno) che abbiamo. Delle volte si pensa di vedere quel bel film che ci hanno consigliato, mentre altre volte si viene risucchiati da quella serie tv che ci tiene incollati allo schermo. Che senso di vuoto quando poi finisce! 



- seduti sul divano
- accendi la tv
- accendi Netflix
- cosa guardiamo ?
- vogliamo veder il film che ci hanno consigliato ?

# SE #

vero 

- vado nella 
    - lista film consigliati 
        - premo play

# ALTRIMENTI #

- dipende dal tempo :

# SE #
abbiamo almeno 1 ora guardiamo un film scegliendo tra :

 - lista film non guardati

 # se #
 - lista vuota non entrare

 # altrimenti

 - cerca tra lista film per genere


# altrimenti

 guardo una serie scegliendo tra :

  - lista serie consigliate

  # se 
  - lista serie consigliate è vuota

  vai a:
    - lista serie non guardate
<!-- 
  # altrimenti 

  - lista serie non guardate
 -->
- lista generi film (azione ecc...)
    -lista film
        -lista consigliati

- lista generi serie (azione ecc...)
    -lista film
        -lista consigliati

tempo x: >1 ora
tempo y: <1ora

copia lista generi film in lista generi film non guardati
copia lista generi serie in lista generi serie non guardate

se >1 ora prendi lista generi film non guardati
    - seleziona genere "azione"
        - seleziona lista consigliati
            - seleziona film a caso
                - guarda
        - altrimenti se lista consigliati è vuota scegli seleziona lista generi film
            - seleziona genere azione
                - seleziona film a caso
                    -guarda
        
        - se film selezionato è guardato copia in lista generi film gia visti
        - se lista generi film non guardati è vuota seleziona lista serie
