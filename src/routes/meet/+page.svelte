<script> //add photos
  import Person from "$lib/Person.svelte";
  import Spacer from "$lib/Spacer.svelte";
</script>
 
<h1>Mentors</h1>
<div class="team-grid">
  <Person src="/people/mscho.jpg" name="Matthew Schoifet" alt="Schozus" /> 
  <Person src="/people/AkashS.jpeg" name="Akash" alt="Akash Shah" /> <!--add-->
  <Person src="/people/SharonK.jpeg" name="Sharon" alt="Sharon" /> <!--add-->
  <!--<Person src="/people/BenMentor.jpeg" name="Ben" alt="Ben" />-->
  <Person src="/people/MikeD.jpeg" name="Mike" alt="Mike" /> 
</div>
<br>

<h1>Drive Team</h1>
<div class="team-grid">
  <Person src="/people/VioletK.webp" name="Violet" alt="Violet"/>
  <Person src="/people/ClementineL.webp" name="Clementine" alt="Clementine"/> <!--add-->
  <Person src="/people/BennetM.webp" name="Bennett" alt="Bennett"/> 
</div>
<br>

<h1>Programming</h1>
<div class="team-grid">
  <Person src="/people/OliverK.webp" name="Oliver" alt="Oliver" /> 
  <Person src="/people/SophieG.webp" name="Sophie" alt="Sophie" />
  <Person src="/people/AsaS.webp" name="Asa" alt="Asa" />
  <Person src="/people/MaxamG.webp" name="Maxam" alt="Maxam" />

  <Person src="/people/NedD.webp" name="Ned" alt="Ned" />
  <Person src="/people/AngelaC.webp" name="Angela" alt="Angela"/>
  <Person src="/people/EthanK.webp" name="Ethan" alt="Ethan"/>
  <Person src="/people/Arda.webp" name="Arda" alt="Arda" />
</div>
<br>

<h1>CAD/Mechanical</h1>
<div class="team-grid">

  <Person src="/people/PeterH.webp" name="Peter" alt="Peter"/>
  <Person src="/people/Oona.webp" name="Oona" alt="Oona" /> 
  <Person src="/people/Leila.webp" name="Leila" alt="Leila" /> 
  <Person src="/people/CharlieN.webp" name="Charlie" alt="Charlie"/>

  <Person src="/people/Elliot.webp" name="Elliot" alt="Elliott"/> 
  <Person src="/people/Lucy.webp" name="Lucy" alt="Lucy" /> 
  <Person src="/people/StevenN.webp" name="Steven" alt="Steven"/> 
  <Person src="/people/AnandP.webp" name="Anand" alt="Anand"/>

  <Person src="/people/KyleA.webp" name="Kyle" alt="Kyle"/> 
  <Person src="/people/EzraS.webp" name="Ezra" alt="Ezra"/> 
  <Person src="/people/Benjamin.webp" name="Ben" alt="Ben"/> 
  <Person src="/people/OzzyL.webp" name="Ozzy" alt="Ozzy"/>

  <Person src="/people/EvaE.webp" name="Eva" alt="Eva"/>
  <Person src="/people/MaxV.webp" name="Max" alt="Max"/>
  <Person src="/people/NoraH.webp" name="Nora" alt="Nora"/>
  <Person src="/people/BeckettG.webp" name="Beckett" alt="Beckett" /> 

  
  <Person src="/people/WilliamM.webp" name="William" alt="William"/>
  <Person src="/people/DanielZ.webp" name="Daniel" alt="Daniel"/>
  <Person src="/people/SachinT.webp" name="Sachin" alt="Sachin"/>
  <Person src="/people/RyanW.webp" name="Ryan" alt="Ryan"/>
</div>


<Spacer />

<style>
  .team-grid {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    width: 80%;
    margin: auto;
    gap: 4vw;
    justify-items: center;
    align-items: center;
  }
</style>