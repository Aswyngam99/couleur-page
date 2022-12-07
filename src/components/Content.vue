<template>
     <div>
        <Navigation/>
      <v-card tile class="back" height="200">
      </v-card>
   <!-- infos -->
          <v-card tile flat class="mx-6 my-6">
            <v-card class="mx-2 my-2 px-2 py-2 confirm-card">
                <v-card-text>
                <h2 class="titre">1. Objet</h2>
                <p>Cette méthode sert à déterminer les valeurs chromatiques d'échantillons transparents liquides au moyen de l'appareil Lico 200. Les valeurs chromatiques typiques pouvant être mesurées de cette manière sont les suivantes : 
                    <v-list-item one-line>
                        <v-list-item-content>
                        <v-list-title>- Valeurs selon L*, a*, b* (CIE)</v-list-title>
                        <v-list-title>- Lovibond<sup>R</sup> </v-list-title>
                        <v-list-title>- Klett</v-list-title>
                        <v-list-title>- Gardner</v-list-title>
                        <v-list-title>- Hazen</v-list-title>
                        </v-list-item-content>
                    </v-list-item>
                	L'appareil Lico 200 est utilisé aussi bien pour les lessives et les produits pour lave-vaisselle liquides que pour les nettoyants ménagers et les matières premières liquides.
                </p>
                </v-card-text>
            </v-card>
            <v-card class="mx-2 my-2 px-2 py-2 confirm-card">
                <v-card-text>
                <h2 class="titre">2. Domaine d'application</h2>
                <p>Cette procédure s’applique au laboratoire Henkel Reghaia.</p>
                </v-card-text>
            </v-card>
            <v-card class="mx-2 my-2 px-2 py-2 confirm-card">
                <v-card-text>
                <h2 class="titre">3. Document de Référence</h2>
                 <v-list-item two-line>
                    <v-list-item-content>
                        <v-list-item-title><strong>- ISO 9000 :</strong></v-list-item-title>
                        <v-list-item-subtitle>Systèmes de management de la qualité — Principes essentiels et vocabulaire.</v-list-item-subtitle>
                        <v-list-item-title><strong>- ISO 9001 :</strong></v-list-item-title>
                        <v-list-item-subtitle>Systèmes de management de la qualité — Exigences.</v-list-item-subtitle>
                        <v-list-item-title><strong>- ISO 9002 :</strong></v-list-item-title>
                        <v-list-item-subtitle>Systèmes de management de la qualité — Lignes directrices pour l’application de l’ISO 9001:2015.</v-list-item-subtitle>
                    </v-list-item-content>
                </v-list-item>
                </v-card-text>
            </v-card>
            <v-card class="mx-2 my-2 px-2 py-2 confirm-card">
                <v-card-text>
                <h2 class="titre">4. Définitions et Abréviations</h2>
                <p>Non indiquées.</p>
                </v-card-text>
            </v-card>
            <v-card class="mx-2 my-2 px-2 py-2 confirm-card">
                <v-card-text>
                <h2 class="titre">5. Responsabilités et Autorités</h2>
                <p>Le technicien contrôle qualité est responsable sur l’analyse. <br> Le responsable laboratoire est responsable sur la validation des méthodes.</p>
                </v-card-text>
            </v-card>
            <v-card class="mx-2 my-2 px-2 py-2 confirm-card">
                <v-card-text>
            <h2 class="titre">6. Processus</h2>
             <v-list-item two-line>
                <v-list-item-content>
                    <v-list-item-title><strong>1 - Résumé de la méthode</strong></v-list-item-title>
                    <v-list-item-subtitle>La lumière émise par une lampe halogène est dispersée au moyen d'un réseau de diffraction. L'absorption de cette lumière monochromatique par l'échantillon est mesurée dans la gamme comprise entre 380 nm et 720 <br> nm en pas de 10 nm. L'angle d'observation est de 2°.</v-list-item-subtitle>
                    <v-list-item-title><strong>2 - Réactifs</strong></v-list-item-title>
                    <v-list-item-subtitle>Eau désionisée ou autre solvant approprié pour l'échantillon (si nécessaire).</v-list-item-subtitle>
                    <v-list-item-title><strong>3 - Appareillage</strong></v-list-item-title>
                    <v-list-item-subtitle>* Appareil de mesure chromatique Lico 200, Dr. Lange, Duesseldorf.</v-list-item-subtitle>
                    <v-list-item-subtitle>* Imprimante LD 200, Dr. Lange, Duesseldorf.</v-list-item-subtitle>
                    <v-list-item-subtitle>* Cuvettes rectangulaires, 10 mm, 50 mm (p. ex. Dr. Lange, Duesseldorf).</v-list-item-subtitle>
                    <v-list-item-subtitle>* Cuvettes rondes, 11 mm, (p. ex. Dr. Lange, Duesseldorf).</v-list-item-subtitle>
                    <v-list-item-title><strong>4 - Procédé</strong></v-list-item-title>
                      <v-list-item two-line>
                        <v-list-item-content>
                             <v-list-item-title><strong>Préparation de l'appareil</strong></v-list-item-title>
                              <v-list-item-subtitle>Au moins 15 minutes avant de procéder au calibrage, enclencher l'un après l'autre l'imprimante et l'appareil de mesure Lico. <br> Après l'enclenchement du Lico 200, un auto-test est réalisé automatiquement. <br> Après le test apparaît sur l’écran :</v-list-item-subtitle>
                              <v-img src="../../public/1.jpg"contain height="100" width="150"></v-img>

                              <v-list-item-title><strong>Configuration</strong></v-list-item-title>
                              <v-list-item-subtitle>La configuration doit être effectuée avant le calibrage. Pour ce faire, il faut fixer le format des données de sortie sur le display et l'imprimante.</v-list-item-subtitle>
                              <v-img src="../../public/2.jpg"contain height="100" width="150"></v-img>
                              <v-list-item-subtitle>Appuyer sur la touche ”CONF”</v-list-item-subtitle>
                              <v-img src="../../public/3.jpg"contain height="100" width="150"></v-img>
                              <v-list-item-subtitle>Appuyer sur la touche ”C”</v-list-item-subtitle>
                              <v-img src="../../public/4.jpg"contain height="100" width="150"></v-img>
                              <v-list-item-subtitle>Appuyer sur la touche ”OUI” <br> Le display indique par exemple: </v-list-item-subtitle>
                              <v-img src="../../public/5.jpg"contain height="100" width="150"></v-img>
                              <v-list-item-subtitle>Appuyer sur ”OUI” si vous voulez sélectionner le système de couleur indiqué.<br>Sinon, appuyer à plusieurs reprises sur ”NON” jusqu'à ce que le système de couleur désiré (p. ex. Gardner) soit proposé.</v-list-item-subtitle>
                              <v-img src="../../public/6.jpg"contain height="100" width="150"></v-img>
                              <v-list-item-subtitle>Appuyer sur ”OUI”</v-list-item-subtitle>
                              <v-img src="../../public/7.jpg"contain height="100" width="150"></v-img>
                              <v-list-item-subtitle>Appuyer sur ”OUI”</v-list-item-subtitle>
                              <v-img src="../../public/8.jpg"contain height="100" width="150"></v-img>
                              <v-list-item-subtitle>Appuyer sur ”OUI”</v-list-item-subtitle>
                              <v-img src="../../public/9.jpg"contain height="100" width="150"></v-img>
                              <v-list-item-subtitle>Appuyer sur ”&#8593;”</v-list-item-subtitle>
                              <v-img src="../../public/10.jpg"contain height="100" width="150"></v-img>
                              <v-list-item-subtitle>Appuyer sur ”OUI”</v-list-item-subtitle>
                              <v-img src="../../public/11.jpg"contain height="100" width="150"></v-img>
                              <v-list-item-subtitle>Appuyer sur ”&#8593;” pour terminer la sélection</v-list-item-subtitle>
                              <v-img src="../../public/12.jpg"contain height="100" width="150"></v-img>

                              <v-list-item-title><strong>Calibrage</strong></v-list-item-title>
                              <v-list-item-subtitle>- L'appareil doit être calibré avant chaque mesure. Le calibrage est toujours réalisé avec de l'eau désionisée. <br>- Les liquides de couleur foncée sont mesurés dans des cuvettes de 10 mm cuvettes, les liquides moins colorés dans des cuvettes de 50 mm pour obtenir une plus grande précision grâce à la plus grande longueur du <br> chemin optique. <br>- Remplir une cuvette du type convenant à l'échantillon d'eau désionisée aux ¾ de sa hauteur. <br>- Essuyer avec un papier doux en cellulose l'eau restant à l'extérieur de la cuvette et placer la cuvette dans l'appareil. <br>- Fermer le couvercle pour éviter toute interférence de lumière.  </v-list-item-subtitle>
                              <v-list-item-subtitle>Appuyer sur ”Cal”</v-list-item-subtitle>
                              <v-img src="../../public/13.jpg"contain height="100" width="150"></v-img>
                              <v-list-item-subtitle>Exemple : La mesure doit être réalisée avec une cuvette de 11 mm :</v-list-item-subtitle>
                              <v-list-item-subtitle>Appuyer sur ”11 mm”</v-list-item-subtitle>
                              <v-img src="../../public/14.jpg"contain height="100" width="150"></v-img>
                              <v-list-item-subtitle>Appuyer sur ”Mes”</v-list-item-subtitle>
                              <v-list-item-subtitle>Le calibrage se déroule automatiquement. Ensuite apparaît :</v-list-item-subtitle>
                              <v-img src="../../public/15.jpg"contain height="100" width="150"></v-img>
                              <v-list-item-subtitle>Les valeurs de calibrage sont imprimées.</v-list-item-subtitle>
                              <v-list-item-subtitle>Après la sortie sur imprimante, le premier affichage apparaît :</v-list-item-subtitle>
                              <v-img src="../../public/16.jpg"contain height="100" width="150"></v-img>

                              <v-list-item-title><strong>Mesure</strong></v-list-item-title>
                              <v-list-item-subtitle>Remplir une cuvette de l'échantillon à analyser en veillant à ce qu'il n'y ait pas de bulles.</v-list-item-subtitle>
                              <v-list-item-subtitle>Placer la cuvette dans l'appareil.</v-list-item-subtitle>
                              <v-list-item-subtitle>Appuyer sur ”C”</v-list-item-subtitle>
                              <v-img src="../../public/17.jpg"contain height="100" width="150"></v-img>
                              <v-list-item-subtitle>Appuyer sur ”Mes” pour démarrer la mesure.</v-list-item-subtitle>
                              <v-list-item-subtitle>Après la mesure automatique, l'affichage suivant apparaît :</v-list-item-subtitle>
                              <v-img src="../../public/18.jpg"contain height="100" width="150"></v-img>
                              <v-list-item-subtitle>Les valeurs présélectionnées (voir 6.2, ”Configuration”) sont imprimées automatiquement.</v-list-item-subtitle>
                        </v-list-item-content>
                    </v-list-item>
                    <v-list-item-title><strong>5 - Expression des résultats</strong></v-list-item-title>
                    <v-list-item-subtitle>Les résultats sont exprimés comme indiqués sur le display, avec référence à cette méthode et en indiquant le système chromatique sélectionné. <br> Si une solution de l'échantillon original a été utilisée pour la mesure, ajouter de plus le solvant et la concentration de la solution.</v-list-item-subtitle>
                    <v-list-item-title><strong>6 - Précision</strong></v-list-item-title>
                    <v-list-item-subtitle>Conformément à la spécification de l'appareil Lico 200, la reproductibilité des valeurs de transmission (sortie avec ”PRNT”, ”PLOT”) devrait être de l'ordre de ±0.2 % (en se référant à l'eau distillée).</v-list-item-subtitle>
                    <v-list-item-title><strong>7 - Sécurité</strong></v-list-item-title>
                    <v-list-item-subtitle>Aucune précaution spéciale n'est requise.</v-list-item-subtitle>
                    <v-list-item-title><strong>8 - Remarques</strong></v-list-item-title>
                    <v-list-item-subtitle>Pour de plus amples informations, veuillez consulter le mode d'emploi LICO 200, Dr. Lange.</v-list-item-subtitle>
                </v-list-item-content>

                </v-list-item>
                </v-card-text>
            </v-card>
           </v-card>
             <!-- Footer -->
            <v-footer flat bottom padless>
                <v-col><strong>PR SHEQ VR A.5-01– Procédure de Veille Réglementaire</strong> <br> <div class="primary--text"> Propriété exclusive de HENKEL Algérie Unité de Production Réghaia. <br> Toute reproduction intégrale ou partielle ainsi que son utilisation par, ou la communication à, des tiers, sans accord préalable écrit de l’auteur est illicite.</div> Le R-SMI est responsable de la gestion et l’application de cette procédure.</v-col>
            </v-footer>
    </div>
</template>

<script>
  export default {
    name: 'HelloWorld',

    data: () => ({

    }),
  }
</script>
<style scoped>
.confirm-card {
  overflow: hidden;
}
.titre{
    color: #ff0011;
}
.back{
    background: url('../../public/labo3.jpg');
}
</style>