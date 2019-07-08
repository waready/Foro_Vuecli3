<template>
  <v-container>
      <v-layout wrap>
          <v-flex class="primary" xs12>
            <h1>12</h1>
          </v-flex>
          <v-flex class="secondary" xs6>
            <h1>6</h1>
          </v-flex>
          <v-flex class="error" xs6>
            <h1>6</h1>
          </v-flex>
      </v-layout>
      <v-layout mt-5 class="secondary" justify-center align-center="" style="height:300px;">
        <v-flex class="info" xs3>
          <h1>Centrado</h1>
        </v-flex>
         <v-flex class="success" xs3>
          <h1>Centrado</h1>
        </v-flex>
      </v-layout>
       <v-layout row wrap>
         <v-flex>
           <v-btn color="primary">
             Texto
           </v-btn>
           <v-btn>
             text
           </v-btn>
           <v-btn color="blue" dark="">
             Text
           </v-btn>
           <v-btn color="secondary" flat="">
             sin - fondo 
           </v-btn>
           <v-btn color="warning" large>
             LArgo
           </v-btn>
           <v-btn color="warning" small>
             Small
           </v-btn>
             <v-btn color="warning" large disabled="">
             LArgo
           </v-btn>
           <v-btn color="info" depressed="">
             Boton
           </v-btn>
             <v-btn color="warning" large>
              <v-icon>forum</v-icon>
           </v-btn>
           <v-btn color="primary" icon flat>
              <v-icon>forum</v-icon>
           </v-btn>
           <v-btn color="warning" fab>
              <v-icon>forum</v-icon>
           </v-btn>
           <v-btn color="warning" small fab="">
              <v-icon>forum</v-icon>
           </v-btn>
           <v-btn color="warning" >
             texto
              <v-icon>forum</v-icon>
           </v-btn>
           <v-btn color="warning" >
             texto
              <v-icon class="ml-2">forum</v-icon>
           </v-btn>
           <v-btn color="warning" >
             texto
              <v-icon right="">forum</v-icon>
           </v-btn>
           <v-btn color="warning" large>

              <v-icon left="">forum</v-icon>
              texto
           </v-btn>
           <v-btn color="red" outline="">
             <v-icon left="">forum</v-icon>
              texto
           </v-btn>
           <v-btn color="red" outline="" block="">
             <v-icon left="">forum</v-icon>
              texto
           </v-btn>

         </v-flex>
       </v-layout>
  </v-container>
</template>

<script>
  

  export default {
    
  }
</script>
