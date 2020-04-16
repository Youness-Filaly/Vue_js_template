<template>
  <div class="about_area">
    <div class="container">
      <div class="row justify-content-end">
        <div class="col-lg-5 offset-lg-1">
          <div class="about_info">
            <img src="../assets/img/about.png" style="width: 80%" />
            <div id="msgErreur">
              <p>
                We’re a smart alternative to owning a car for people who don’t
                drive every day. In short, we’ve eliminated all the hassles of
                owning a car.
              </p>
            </div>
          </div>
        </div>

        <div class="col-lg-5 offset-lg-1">
          <div class="about_info">
            <div class="section_title white_text">
              <span
                class="wow fadeInUp"
                data-wow-duration="1s"
                data-wow-delay=".3s"
                >01 ABOUT US</span
              >
              <h3>Let's make cities better</h3>
              <p
                class="mid_text wow fadeInUp"
                data-wow-duration="1s"
                data-wow-delay=".5s"
              >
                We believe in using business to drive positive change in the
                world and never settling for what worked in the past.
              </p>
              <p
                class="last_text wow fadeInUp"
                data-wow-duration="1s"
                data-wow-delay=".6s"
              >
                That’s why we believe parking, health and safety, and quality of
                life can be radically improved in our cities — Upshift members
                are reducing CO2 emissions and using fewer city parking spaces,
                making our air healthier to breathe and allowing city planners
                to transform unused parking spots into public parks.
              </p>
              <div class="col-md-12">
                <div class="row">
                  <div class="col-md-1">
                    <button
                      type="button"
                      class="btn btn-primary btn-circle btn-lg"
                    >
                      <img src="../assets/img/cross.svg" alt="" id="img">
                    </button>
                  </div>
                  <div class="col-md-11">
                    <p>Inderstand our values?</p>
                    <p>Learn more about our company</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>

<style lang="css">
.btn-circle.btn-lg {
  width: 50px;
  height: 50px;
  padding: 10px 16px;
  font-size: 18px;
  line-height: 1.33;
  border-radius: 25px;
  background-color: #4c4c4c;
}

.about_info {
  
  color: #4c4c4c;
}
.about_info p {
  margin-left: 50px;
}
.about_info .section_title span {
  color: #4c4c4c;
}

#msgErreur {
  background: #4c4c4c;
  width: 400px;
  height: 200px;
  position: absolute;
  transform: translate(60px, -100px);
}

#msgErreur p {
  color: #fff;
  margin: 50px 50px 50px 50px;
}
#img{
  width: 10px;
}
</style>
