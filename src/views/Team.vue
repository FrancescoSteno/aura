<template>
  <v-content class="pa-0">

    <v-container fluid class="mt-3 mb-0">
      <v-layout wrap align-center justify-center row fill-height class="my-0">
        <v-flex xs12 md10 class="my-0">
            <p class="google-font mb-0" style="font-size:200%;color:#616161">La nostra gamma di grandi pensatori ed anche più grandi</p>
            <p class="google-font mt-0 mb-0" style="font-size:110%">Google è conosciuto in tutto il mondo. Ognuno è 'googling', controlla su 'mappe' e 
              comunica in 'gmail'. Per gli utenti semplici, sono servizi che funzionano, ma non per noi. 
              Gli sviluppatori vedono molto di più: API, problemi di scalabilità, stack tecnologici complessi. E questo è GDG.</p>

            <p class="google-font mt-3 mb-0" style="font-size:110%">Il nostro obiettivo è organizzare lo spazio per collegare i migliori esperti del 
              settore con il pubblico italiano per favorire lo sviluppo dell'IT. <br>          
              E il nostro core team è composto da: </p>

        </v-flex>
      </v-layout>
    </v-container>

    <v-container fluid >
      <v-layout wrap align-center justify-center row fill-height>
        <v-flex xs12 md10 class="">
          <coreTeam/>
        </v-flex>
      </v-layout>
    </v-container>

    <v-container fluid >
      <v-layout wrap align-center justify-center row fill-height>
        <v-flex xs12 md10 class="">
          <organizingTeam/>
        </v-flex>
      </v-layout>
    </v-container>

   


  </v-content>
  
</template>

<script>
import TeamDetails from '@/assets/data/chapterDetails.json'
import coreTeam from '@/components/team/coreTeam'
import organizingTeam from '@/components/team/organizingTeam'
  export default {
    components: {
      coreTeam,
      organizingTeam
    },
    data() {
      return {
        TeamDetails: TeamDetails,
      }
    },
  }
</script>
