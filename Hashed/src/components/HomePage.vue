<template>
    <div class="container-fluid m-0 p-0"> 

        <div id="home-page" class="full-hight bg-danger p-4">
            <div class="container pt-3">
                <div class="row pb-5">
                    <div class="col-lg-6 pt-4 my-auto">
                        <img id="iphone-img" src="../assets/iphones.png">
                    </div>
                    <div class="col-lg-6">
                        <div class="text-center mb-3">
                            <h1 class="display-3">[{ title }]</h1>
                            <h3>Clothes finally connected</h3>
                        </div>
                    </div>
                </div>
            </div>
                 
        </div>

        <div id="about" class="bg-warning p-4">
        </div>

        <div id="contact" class="bg-info p-4">
        </div>

        <div id="footer" class="bg-dark p-4">
        </div>                

    </div> 

</template>

<script>
export default {
  data () {
    
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

#home-page {
    background-color: rgb(182, 178, 127);
    background: url('../assets/marjanblan-QIJ9Fp7r6A8-unsplash.jpg') no-repeat center center;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
} 

#iphone-img {
    max-height: 80vh;
}

</style>
