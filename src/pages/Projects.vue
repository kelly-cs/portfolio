<template>
          <div class="content">
            <vue-headful
              title="Projects - Likai Codes"
              description="Projects of Likai.Codes!"/>
            <div class="left">
              <h2>Likai Kuroi</h2>
              <h3>Code Projects!</h3>
            </div>

            <div class="middle">

            </div>
            
            <div class="right">
              <p>some project over here</p>
              <p>maybe a script that monitors git commits or w/e</p>
            </div>
             
          </div>
</template>

<script>
export default {
  name: 'Home'
}
</script>

<style>

/* Default */
.content {
  display: flex;
  position: relative;
  flex-direction: row;
  justify-content:space-between;
  margin-top: 2%;
  margin-left: 3%;
  margin-right: 3%; 
  margin-bottom: 2%;
  border: 1px solid red;
  max-height: 60%;
  min-height: 60%;
}

/* For 1920x1080 */
@media screen and (max-width: 1921px){
  .content {
  display: flex;
  position: relative;
  flex-direction: row;
  justify-content:space-between;
  margin-top: 2%;
  margin-left: 3%;
  margin-right: 3%; 
  margin-bottom: 2%;
  border: 1px solid red;
  min-height: 400px;
  max-height: 400px;
  }
}

/* For 1440p */
@media screen and (min-width: 1921px) and (max-width: 2560px){
  .content {
  display: flex;
  position: relative;
  flex-direction: row;
  justify-content:space-between;
  margin-top: 2%;
  margin-left: 3%;
  margin-right: 3%; 
  margin-bottom: 2%;
  border: 1px solid red;
  min-height: 750px;
  max-height: 750px;
  }
}


.left {  
  display: inline-flex;
  flex-direction: column;
  background-color: gray;
  text-align: left;
  overflow: auto;
  width: 55%;
  margin-right: 2%;
  border: 1px solid yellow;
}

.middle {
display: flex;
flex-direction: column;
background-color: white;
width: 1%;
margin-left: 1%;
margin-right: 1%;

}

.right {
  display: inline-flex;
  flex-direction: column;
  background-color: gray;
  text-align: right;
  width: 55%;
  margin-left: 2%;
  overflow: auto;
  border: 1px solid yellow;
}

</style>