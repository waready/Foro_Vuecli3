<template>
  <v-container grid-list-md>
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
       <v-layout row wrap="">
         <v-flex xs12 md6>
            <v-card>
              <v-img  src="https://cdn.vuetifyjs.com/images/cards/docks.jpg">
              </v-img>
              <v-card-title>
                <h2>lorem ipsun nada mas por ahora no hay problema</h2>
              </v-card-title>
              <v-card-text>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Totam enim quis, rerum ipsa porro aliquam similique in veritatis odio ducimus illum aspernatur facilis blanditiis est eos animi. Quasi, perspiciatis et!</p>
              </v-card-text>
              <v-card-actions>
                <v-btn color="info" flat>
                  Accion
                </v-btn>
              </v-card-actions>
            </v-card> 
         </v-flex>
         <v-flex xs12 md6>
            <v-card>
              <v-img  src="https://cdn.vuetifyjs.com/images/cards/docks.jpg">
                <v-container fill-height="">
                  <v-layout row wrap>
                    <v-flex>
                      <span class="headline white--text">asdasdsads</span>
                    </v-flex>
                  </v-layout>
                </v-container>
              </v-img>
              <v-card-title>
                <h2>lorem ipsun nada mas por ahora no hay problema</h2>
              </v-card-title>
              <v-card-text>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Totam enim quis, rerum ipsa porro aliquam similique in veritatis odio ducimus illum aspernatur facilis blanditiis est eos animi. Quasi, perspiciatis et!</p>
              </v-card-text>
              <v-card-actions>
                <v-btn color="info" flat  @click="dialog=true">
                  Accion
                </v-btn>
              </v-card-actions>
            </v-card> 
         </v-flex>
       </v-layout>
       <v-dialog
         v-model="dialog"
          width="500px"
          persistent=""
       >
         <v-card>
           <v-card-title>
             este es el titulo
           </v-card-title>
           <v-card-text>
             Lorem ipsum, dolor sit amet consectetur adipisicing elit. Sed sint dignissimos obcaecati, illum similique eligendi earum unde? Explicabo nostrum blanditiis quae ex reprehenderit recusandae commodi accusamus dolor, quia exercitationem optio.

           </v-card-text>
           <v-divider/>
             <v-card-actions>
                <v-btn class="error" @click="dialog=false"> 
                  Cerrar
                </v-btn> 
             </v-card-actions>
           
         </v-card>
       </v-dialog>
  </v-container>
</template>

<script>
  

  export default {
    data(){
      return{
        dialog:false
      }
    }
  }
</script>
