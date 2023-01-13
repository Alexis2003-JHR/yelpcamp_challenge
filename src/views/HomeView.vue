<template>
  <div class="home">
    <div class="initial_page">
      <div class="fractions">
        <div class="f1">
          <div class="central-content">
            <img class="logo" src="../assets/Home/Logo.svg" alt="">
            <h2>Explore the best camps on Earth.</h2>
            <p>YelpCamp is a curated list of the best camping sport on Earth. Unfiltered and unbiased reviews.</p>
            <ul>
              <li>Add your own camp suggestions.</li>
              <li>Leave reviews and experiences.</li>
              <li>See locations for all camps.</li>
            </ul>
            <div class="view-button">
              <h3>View Campgrounds</h3>
            </div>
            <p>Parnered with: </p>
            <div class="parner-images">
              <img src="../assets/Home/Airbnb.svg" alt="">
              <img src="../assets/Home/Booking.svg" alt="">
              <img src="../assets/Home/Plum_Guide.svg" alt="">
            </div>
          </div>

        </div>
        <div class="f2">
          <img class="f2-img" src="../assets/Home/Hero_Image.png" alt="">
        </div>
      </div>
    </div>
  </div>
</template>

<script>

export default {
}
</script>

<style scoped>
/*Order and essentials*/
.initial_page{
  background-color: rgba(255, 247, 229, 0.315);
  height: 100vh;
  width: 100%;
}
.fractions{
  display: flex;
  justify-content: space-between;
}
.f1{
  display: flex;
  align-items: center;
  justify-content: center;
  width: 50%;
}
.central-content{
  width: 70%;
}
.logo{
  width: 150px;
  position: absolute;
  top: 5%;
}
.f2{
  width: 48%;
  height: 100vh;
}
.f2 img{
  width: 100%;
  height: 100vh;
}
.f2-img{
  object-fit: cover;
}
/*Style*/
h2{
  font-size: 65px;
  font-weight: 600;
}
p, li{
  font-size: 20px;
  color: rgb(78, 78, 78);
}
li{
  padding: 10px 45px;
  margin: 0;
	list-style: none;
	background-image: url("../assets/Home/Checkmark.svg");
	background-repeat: no-repeat;
	background-position: left center;
	background-size: 30px;
}
.view-button{
  display: flex;
  background-color: #000;
  justify-content: center;
  width: 225px;
  height: 60px;
  border-radius: 8px;
}
.view-button :hover{
  cursor: pointer;
  box-shadow: 2px 3px 0 0 #000;
  transition: .5s;
}
.view-button h3{
  font-weight: 500;
  color: #fff;
}

/*RESPONSIVE*/

</style>