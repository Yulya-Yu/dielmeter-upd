<template>
<div>
 <div class="background">
    <div class="main">
        <section class="header">
          <h1>What's Yushkov's Di-El Meter</h1>
          <p>It is a device that measures dielectric permittivity of different materials. 
            What's dielectric permittivity and how is measuring it can be useful?
            You will find answers to these question below!</p>
            <button>View Answer</button>
        </section>
    </div>
 </div>      
        <section class="areas">
           <div class="areas-header">
               <h3><span>Areas</span> of application</h3>
           </div>
           <div class="areas-content">
               <p>There are a lot of measuring instruments known to man. All of them are using some physical properties as measuring parameters.
                  So, thermometer measures temperature, tonometer measures pressure, radiometer measures the level of radiation, barometer measures atmospheric pressure etc.
                  All of these devises are used in our everyday life.</p>
                  
               <p>However, there is one more physical property, measuring which can be useful for domestic application. This parameter is called <a href="http://www.encyclopedia.com/science/dictionaries-thesauruses-pictures-and-press-releases/dielectric-permittivity"
                  target="_blank">dielectric permittivity</a>, which is closely connected to the structure of non-metallic materials, that surround us everywhere <i>(concrete and wooden walls and ceilings, furniture, food, constructional materials etc.)</i>
                  Of course, there are devices that measure dielectric permittivity, however, they are impossible to use for everyday needs because of their huge sizes, complexity, bad locality and limited frequency range.
                  That is why we are proposing a new device, that can easily be used for domestic needs.
                  This universal technology can be applied in vast variety of fields.</p>
               <p class="bold-text">Below are only some of them</p>
           </div>
        </section>
        <section class="areas-icons">
                   <div class="area">
                       <i class="fa fa-building-o" aria-hidden="true"></i>
                       <h4>Construction</h4>
                       <p>Ability to know where empty spaces and reinforcing steel beams are located in the concrete walls, 
                       their density distribution and hidden humidity. </p>
                   </div>
                   <div class="area" >
                      <i class="fa fa-hand-paper-o" aria-hidden="true"></i>
                      <h4>Repair Works</h4>
                      <p>Ability to know if wooden constructions are damaged by mold or fungus.</p>
                   </div>
                   <div class="area">
                      <i class="fa fa-cutlery" aria-hidden="true"></i>
                      <h4>Food Industry</h4>
                      <p>Ability to control the dynamics of cheese ripening for those who manufactures cheeses, since it can help optimize time, spent on the process.</p>
                   </div>
                   <div class="area">
                      <i class="fa fa-flask" aria-hidden="true"></i>
                      <h4>Research</h4>
                      <p>Can be used in medecine to find hiddent abnormalities.</p>
                   </div>
        </section>
        <section class="adv">
           <div class="advant-container"> 
          <div class="adv-content">
                    <div class="adv-details">
                       <h4>Compactness</h4>
                       <p><i>Di-El Meter is very compact</i></p>
                       <p>There are devices that measure dielectric permittivity, however, they are impossible to use for everyday needs because of their huge sizes, complexity, 
                           bad locality and limited frequency range. What we are offering can change <i>everything!</i></p>
                   </div>
                   <div class="adv-details" >
                      <h4>Universality</h4>
                      <p><i>Di-El Meter can be used for a wide range of purposes</i></p>
                      <p>This creates almost endless posibilities for its user!</p>
                   </div>
                   <div class="adv-details">
                      <h4>Simplicity</h4>
                      <p><i>Di-El Meter is small, simple to use devise.</i></p>
                      <p>You don't have to be an engineer to figure things out!</p>
                   </div>
                   <div class="adv-details">
                      <h4>Accessibility</h4>
                      <p><i>Di-El Meter is adaptable</i></p>
                      <p>Can be used with smartphones, tablets and other modern devices!</p>
                   </div>
          </div>
          <div class="adv-head">
              <h3><span>Advantages</span></h3>
              <p>Advantages over other methods of measuring are <span>unquestionable</span></p>
          </div>
           </div>
        </section>
        <section class="creator">
            <div class="creator-head">
               <!-- <i class="far fa-user"></i> -->
               <h4>Creator</h4>
            </div>
           <p>The devise was invented by Russian scientist, <span>Valentin Yushkov </span> almost 30 years ago.
              Since that moment it was exhibited to a puplic on different conventions.
              The devise even was implemented on several factories throughout Russia.</p>
        </section>
        <section class="help">
          <div class="help-head">
              <h4>How <span>you can</span> help</h4>
          </div>
          <div class="help-content">
              <div class="help-inst">
                  <i class="far fa-stop-circle"></i>
                  <p>The works on this project are frozen at the moment. 
                  Hovewer, given a proper funding we are ready to construct modern and functional device for everyday or 
                  industrial use</p>
              </div>
              <div class="help-inst special">
                  <i class="fas fa-hands-helping"></i>
                  <p>If you want to help us please contact us through contact form below or via email. 
                    If you are looking for an investment opportunity let us make our case in favor of this revolutionary invention</p>
              </div>
              <div class="help-inst">
                  <i class="fas fa-laptop-house"></i>
                  <p class="strong-help">We also strongly belive that, if this devise become ordinary household appliance, 
                    like a cell phone, this will encourage teenagers and young adults to start their own scientific research.</p>
              </div>
          </div>
        </section>
        <footer>
           <div class="footer-contact">
               <h4>Contact us today!</h4>
               <p>kuroi.kasa1509@gmail.com</p>
               <p class="copyright"> &copy; Valentin Yushkov </p>
           </div>
        </footer>  
</div> 
</template>

<script>


export default {  
}
</script>

<style scoped>

.footer-contact {
min-height: 40vh;
background-color: #7b1fa2;
color: #fff;
display: flex;
align-items: center;
justify-content: center;
flex-direction: column;
}

.footer-contact h4 {
    font-size: 2rem;
    margin-bottom: 1%;
}

.footer-contact p {
    font-size: 1.5rem;
    margin-bottom: 2%;
}

.copyright {
    color:#ae52d4;
}

.help {
    min-height: 50vh;
    height: auto;
    width: 100%;
    max-width: 1200px;
    margin: 3% auto;
}

.help-head h4 {
font-size: 2rem;
color: #333;
width: 50%;
margin: 3% auto;
text-align: center;
}

.help-head h4 span {
    border-bottom: 4px solid #7b1fa2;
}

.help-content {
    display: flex;
}

.help-inst {
    flex: 1;
    min-height: 250px;
    height: auto;
    padding: 20px 20px;
    border-radius: 8px;
    text-align: center;
}

.help-inst + .help-inst {
    margin-left: 5%;
}

.help-inst i {
font-size: 2rem;
color:#333;
text-align: center;
margin-bottom: 3%;
}

.help-inst p {
text-align: left;
}

.special {
    -webkit-box-shadow: 4px 4px 15px 1px rgba(51,51,51,0.7); 
    box-shadow: 4px 4px 15px 1px rgba(51,51,51,0.7);
}

.special i {
color:#7b1fa2;
}

.creator {
    min-height: 30vh;
    height: auto;
}

.creator-head {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.creator-head i {
    font-size: 2rem;
    color: #7b1fa2;
}

.creator-head h4 {
    font-size: 2rem;
    border-bottom: 4px solid #7b1fa2;
    color: #333;

}

.creator p {
width: 50%;
margin: 2% auto;
color: #333;
font-size: 1.2rem;
}

.background {
     background-image: url('../assets/7.jpg');
     background-position: center;
     background-repeat: no-repeat;
     background-attachment: fixed;
     background-size: cover;
}
 .main {
     max-width: 1200px;
     height: 100vh;
     width: 100%;
     margin: 0 auto;
     display: flex;
 }

 .header {
     height: 100vh;
     width: 60%;
     display: flex;
     align-items: flex-start;
     justify-content: center;
     flex-direction: column;
     color: #333;
     padding-left: 3%;
 }

 .header h1 {
     margin-bottom: 5%;
     font-size: 2.2rem;
     font-weight: 600;
 }

 .header p {
     margin-bottom: 5%;
     font-size: 1.1rem;
 }

 .header button {
     border: none;
     text-decoration: none;
     padding: 17px 25px;
     color: #fff;
     background-color: #7b1fa2;
     font-size: 1.3rem;
     cursor: pointer;
     transition: 0.3s ease-in;
 }

.header button:hover {
    background-color: #4a0072;
}

.areas, .advant-container {
    width: 100%;
    max-width: 1200px;
    min-height: 50vh;
    height: auto;
    display: flex;
    flex-direction: row;
    margin: 2% auto;
    padding: 3% 0;
    /* align-items: center; */
    color: #333;
}

.areas-header {
    width: 40%;
    display: flex;
    /* align-items: center; */
    justify-content: center;
    font-size: 2rem;
    margin-right: 6%;
    font-weight: 400;
}

.areas-header span {
    border-bottom: 4px solid #7b1fa2; 
}

.areas-content {
    width: 54%;
}

.areas-content p{
    margin-bottom: 2%;
    font-size: 1.1rem;
}

.bold-text {
    font-weight: 600;
}

.areas-content a {
    text-decoration: none;
    color:#7b1fa2;
    font-weight: 600;
}

.areas-icons {
    display: flex;
    width: 100%;
    max-width: 1200px;
    flex-wrap: wrap;
    flex-direction: row;
    margin: 2% auto;
    justify-content: space-between;
    text-align: center;
}

.area {
    flex: 1;
    min-height: 200px;
    height: auto;
    padding: 20px 20px;
    border-radius: 8px;
    -webkit-box-shadow: 4px 4px 15px 1px rgba(51,51,51,0.7); 
    box-shadow: 4px 4px 15px 1px rgba(51,51,51,0.7);
}

.area + .area {
    margin-left: 5%;
}

.area h4, .area i {
    margin-bottom: 5%;
}

.area p {
    text-align: left;
}

.area i {
    font-size: 2rem;
    color: #7b1fa2;
}

.adv-head {
    width: 40%;
    display: flex;
    justify-content: center;
    font-size: 2rem;
    margin-left: 6%;
    font-weight: 400;
    flex-direction: column;
    text-align: right;
}

.adv-head h3 {
margin-bottom: 5%;
}

.adv-head h3 span {
    border-bottom: 4px solid #ae52d4;
}

.adv-head p{
  font-size: 1.2rem;
}

.adv {
width: 100%;
background-color: #7b1fa2;
color: #fff;
}

.advant-container {
  color: #fff;  
}

.adv-content {
width: 64%;
}

.adv-details {
    margin-bottom: 4%;
}

.adv-details h4 {
    margin-bottom: 1.5%;
    font-size: 1.2rem;
}

</style>