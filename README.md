# Deblurring di immagini mosse

Il progetto riguarda il deblurirng di immagini. Il tipo di "blur" in questione è ottenuto mediante sovrapposizione di immagini leggermente traslate a partire dall'originale, lungo un tragitto randomico.

Questo tipo di blur ntende simulare il risultato del tremolio della mano per riprese con tempo di esposizione prolungato.

Per il progetto vengono utilizzate immagini mnist. Il generatore di immagini blurred viene fornito nel notebook allegato, e non deve essere modificato.

Utilizzate Mean Squared Error (mse) per valutare l'errore tra l'immagine deblurred e la ground truth.

Misurate l' mse su 10000 immagini blurred ottenute dal validation set. Ripetete la computazione precedente per 10 volte, e fornite come risutato la media dei 10 round, unitamente alla deviazione standard.

Dovete consegnare un singolo notebook, dove deve essere conservata la traccia del training. Il progetto deve essee svolto in tensorflow/keras.

Il lavoro deve essere scolto in keras/tensorflow. Consegnate un singolo notebook dove dovete conservare traccia del training.

Discutete e motivate l'architettura finale, cosi come la scelta dei principali iperparametri.
