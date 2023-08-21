- prendo n. pacchetti di figurine
- mi avvicino al tavolo
- mi siedo sulla sedia
    - sposto la sedia

# start loop    
    - apro una busta
        - prendo le carte in mano
        - le controllo
            - SE figurina  = rotta/danneggiata 
                - aggiungi a scarti

            - ALTRIMENTI figurina  = integra tieni
                - SE carta nuova aggiungi ad ALBUM principale
                - ALTRIMENTI carta = doppiona agigungi ad ALBUM scambi
                    - Se carta in album 2 = >=2 scambia con alberto
                    - ALTRIMENTI tieni
    -   riciclo busta
# end loop


# start loop    
    - apro una busta
        - prendo le carte in mano
        - le controllo
            - SE figurina  = rotta/danneggiata 
                - aggiungi a scarti

            - ALTRIMENTI figurina  = integra tieni
                - dividi per categoria [comune, noncomune, raro, epico, legy]
                    - SE carta nuova aggiungi ad ALBUM principale
                    
                    - ALTRIMENTI carta = doppiona agigungi ad ALBUM scambi
                        - Se carta in album 2 = >=2 scambia con alberto
                        - ALTRIMENTI tieni
    -   riciclo busta
# end loop

# start loop    
    - apro una busta in cerca di drago x
        - prendo le carte in mano
        - le controllo
            - SE figurina  = drago x smetti di comprare

            - ALTRIMENTI figurina  = integra tieni
                - aggiungi ad album
                    - SE doppiona aggiungi a scambi con amici
                - compra ancora
# end loop