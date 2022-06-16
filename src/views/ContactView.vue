<template>
  <div class="container contact-container">

    <h2 class="nav mb-4 d-flex justify-content-center">Contact</h2>

    <div class="containerpic">
  <img src="../assets/hanna8.jpg" class="img-contact" style="">
  <div class="centered">
    <div class="text-center ">
        <ul class="list-unstyled contact">
          <li><i class="fas fa-map-marker-alt fa-2x"></i>
              <p>Stockholm, SWEDEN</p>
          </li>
          <li><i class="fas fa-phone mt-1 fa-2x"></i>
              <p>070-285 19 20</p>
          </li>
          <li><i class="fas fa-envelope mt-1 fa-2x"></i>
              <p>Collab@hannafriberg.com</p>
          </li>
        </ul>
        </div>
    </div>
    </div>

    
</div>
</template>


<style>
.containerpic {
  position: relative;
  text-align: center;
  color: rgb(0, 0, 0);
  font-weight: bold;
}

.centered {
  position: absolute;
  top: 75%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.nav {
  font-weight: bold;
}

.img-contact {
  opacity: 0.6;
  height: 40rem;
}

.contact{
  font-size: 15px;
}

.contact-container {
  padding-bottom: 10rem;
}

</style>