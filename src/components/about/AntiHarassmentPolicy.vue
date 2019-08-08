<template>
    <v-container class="pa-0 my-0">
        <v-layout wrap align-start justify-start row fill-height class="my-0" >
     
            <v-flex xs12 md8 lg8 class="pa-2 my-0">
                <p class="google-font" style="font-size:180%;color:#0277bd">Politica Anti Molestie</p>

                <p class="google-font" style="font-size:110%">
                    <b style="font-size:120%;color: #2E2E2E;">Perché abbiamo una politica anti-molestie ufficiale per gli eventi del  {{chapterDetails.ChapterName}}?</b>

                    <ul class="mt-2" style="font-size:110%">
                        <li class="google-font">Stabilisce le aspettative di comportamento durante l'evento. Semplicemente avere una politica anti-molestie può prevenire le molestie.</li>
                        <li class="google-font">Incoraggia le persone  che hanno avuto brutte esperienze in altri eventi a partecipare.</li>
                        <li class="google-font">Fornisce al personale dell'evento e ai volontari direttive su come gestire rapidamente le molestie, con una quantità minima di interruzione per l'evento.</li>
                    </ul>
                </p>

                <p class="google-font" style="font-size:110%">
                    <b style="font-size:120%;color: #2E2E2E;">{{chapterDetails.ChapterName}} si prefige di fornire un'esperienza di eventi senza molestie per tutti, indipendentemente da: </b>

                    <ul class="mt-2" style="font-size:110%">
                        <li class="google-font">Sesso</li>
                        <li class="google-font">Orientamento Sessuale</li>
                        <li class="google-font">Invalidità o Handicap</li>
                        <li class="google-font">Identità Sessuali</li>
                        <li class="google-font">Anni</li>
                        <li class="google-font">Razza</li>
                        <li class="google-font">Religione</li>
                        <li class="google-font">Nazionalità</li>
                    </ul>

                    <span class="google-font" style="font-size:110%">Quanto sopra non è un elenco esaustivo: non tolleriamo molestie nei confronti dei partecipanti in qualsiasi forma.</span>
                </p>

                <p class="google-font" style="font-size:120%">Il linguaggio e le immagini sessuali non sono appropriati per nessuna sede di eventi, compresi i discorsi. I partecipanti all'evento che violano queste regole possono essere espulsi dall'evento e l'evento può essere bandito da eventi futuri a discrezione degli organizzatori e gestori dell'evento.</p>

                <p class="google-font" style="font-size:110%">Le molestie includono (ma non si limitano a):
                    <ul class="mt-2" style="font-size:110%">
                        <li class="google-font">Offensive verbal comments related to gender, sexual orientation, disability, gender identity, age, race, religion</li>
                        <li class="google-font">The use or display of sexual images in public spaces</li>
                        <li class="google-font">Deliberate intimidation</li>
                        <li class="google-font">Stalking</li>
                        <li class="google-font">Harassing photography or recording</li>
                        <li class="google-font">Sustained disruption of talks or other events</li>
                        <li class="google-font">Inappropriate physical contact</li>
                        <li class="google-font">Unwelcome sexual attention</li>
                    </ul>
                </p>

                <p class="google-font" style="font-size:120%">Participants asked to stop any harassing behavior are expected to comply immediately. 
                    <br><br>
                    Exhibiting partners and guests are also subject to the anti-harassment policy. In particular, exhibitors and speakers should not use sexualized images, activities, or other material, or otherwise create a sexualized environment in their slide decks, exhibit material, exhibit staffing, promotional items or demo material. 
                    <br><br>
                    If you are being harassed, notice that someone else is being harassed, or have any other concerns, please contact an organizer or event volunteer immediately. Organizers and event volunteers may be identified by t-shirts or special badges/lanyards. Organizers will investigate the issue and take appropriate action. This may include helping participants contact venue security or local law enforcement, provide escorts, or otherwise assist these experiencing harassment to fell safe for the duration of the event. 
                    <br><br>
                    Though we hope that we never have to invoke this policy, we believe that having this document helps everyone think a little more about how their actions and words affect the whole community, as well as individuals in the community.
                </p>


            </v-flex> 
           
            <v-flex xs12 md4 lg4 class="pa-2 hidden-sm-and-down">
                
            </v-flex>
        </v-layout>

    </v-container>
</template>

<script>
import ChapterDetails from '@/assets/data/chapterDetails.json'
export default {
    data() {
        return {
            chapterDetails: ChapterDetails,
        }
    },
}
</script>
