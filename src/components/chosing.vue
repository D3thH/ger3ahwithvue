<template>
  <div>
          <div class="top-container">
      <!-- <h1>قرعة</h1>
      <h2 class="pro">برنامج قرعة العيد</h2> -->
      <img class="eeb_photo" src='../assets/3ed.jpg' alt="3eb_photo">
    </div>


    <div class="middle-container">
        <div>
            <section>
                <p>المتبقي في القرعة</p><br>
                <p> {{rmainng}} </p><br>
               <input v-model="enterd_name" class="text_input" required id="inputtext" type="text">
               <label for=""> : الاسم</label><br>

               <input @click="StartGer3ah" type="button" onclick="buton()" class="btn" value="ارسال"><br>
            </section>
        </div>
    </div>



    <div class="bottom-container">
      <a class="footer-link" href="https://www.linkedin.com/">LinkedIn</a>
      <a class="footer-link" href="https://twitter.com/">Twitter</a>
      <a class="footer-link" href="https://www.appbrewery.co/">Website</a>
      <p class="coyright">© 2021 Fahad Alhatem.</p>
    </div>

  </div>
</template>



<script>
export default {
    data(){
        return{
            names : ["فهد", "صابر", "متعب","رفيف","طمية"],
            rmainng : 5,

            enterd_name :""
            
        };
    },

    methods:
    {
      StartGer3ah(){

 
        var ran =Math.floor(Math.random()*5);

        if ( this.enterd_name == ""){
            alert("اكتب اسمك اول");

        }
        else if (this.enterd_name == this.names[ran]){
            this.StartGer3ah();
        }
        else if (this.names[ran] == "gone") {
            this.StartGer3ah();
        }
        else {
            alert(" طلع لك " + this.names[ran] );
            this.names[ran] = "gone";
            this.rmainng--;
            this.enterd_name="";
            
        }      




      }
    }

}
</script>

<style>



</style>
