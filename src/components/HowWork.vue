<template>
  <div class="service_area">
    <div class="container">
      <div class="row">
        <div class="col-xl-3 col-md-3">
          <div
            class="single_service text-center wow fadeInLeft" 
            data-wow-duration="1.2s"
            data-wow-delay=".4s"
          >
            
            <span
                class="wow fadeInUp"
                data-wow-duration="1s"
                data-wow-delay=".3s"
                >02 HOW IT WORK</span>
            <h3>Simple and handy rental process</h3>
          </div>
        </div>
        <div class="col-xl-4 col-md-4">
          <div
            class="single_serv text-center wow fadeInUp" 
            data-wow-duration="1s"
            data-wow-delay=".3s"
          >
            
            <p>
              Lorem ipsum dolor sit amet
            </p>
            <hr />
            <div class="col-md-12">
              <div class="row">
                <div class="col-md-2">
                  <button
                    type="button"
                    class="btn btn-primary btn-circle btn-lg"
                  >
                      <img src="../assets/img/cross.svg" alt="" style="width:10px;">
                  </button>
                </div>
                <div class="col-md-10">
                  <p>Click here</p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-xl-4 col-md-5">
          <div
            class="single_serv text-center wow fadeInRight" 
            data-wow-duration="1.2s"
            data-wow-delay=".4s"
          >
            
            <p>
              Lorem ipsum dolor sit amet
            </p>
            <hr />

            <div class="col-md-12">
              <div class="row">
                <div class="col-md-2">
                  <button
                    type="button"
                    class="btn btn-primary btn-circle btn-lg"
                  >
                      <img src="../assets/img/cross.svg" alt="" id="img">
                  </button>
                </div>
                <div class="col-md-10">
                   <p>Click here</p>
                   
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="row">
                <div class="col-xl-3 col-md-4">
                    <div class="single_service text-center wow fadeInLeft" data-wow-duration="1.2s" data-wow-delay=".4s">
                        <div class="icon">
                            <img src="../assets/img/text.png" alt="">
                        </div>
                        <h3>You text</h3>
                        <p>Tell us where and when you want your car delivered, no app required.</p>
                    </div>
                </div>
                <div class="col-xl-3 col-md-4">
                    <div class="single_service text-center wow fadeInUp" data-wow-duration="1s" data-wow-delay=".3s">
                        <div class="icon">
                            <img src="../assets/img/delever.png" alt="">
                        </div>
                        <h3>We deliver</h3>
                        <p>We bring your car right to your door, clean and gassed up for your drive.</p>
                    </div>
                </div>
                <div class="col-xl-3 col-md-4">
                    <div class="single_service text-center wow fadeInRight" data-wow-duration="1.2s" data-wow-delay=".4s">
                        <div class="icon">
                            <img src="../assets/img/drive.png" alt="">
                        </div>
                        <h3>You drive</h3>
                        <p>Never worry about mileage or insurance. We have every detail covered.</p>
                    </div>
                </div>
                <div class="col-xl-3 col-md-4">
                    <div class="single_service text-center wow fadeInRight" data-wow-duration="1.2s" data-wow-delay=".4s">
                        <div class="icon">
                            <img src="../assets/img/pick.png" alt="">
                        </div>
                        <h3>We pick up</h3>
                        <p>You decide when you're done with your car. When you're ready, we'll pick it up and refuel and clean it.</p>
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
   .service_area .single_serv {
  padding: 48px 35px 45px 35px;
  -webkit-transition: 0.3s;
  -moz-transition: 0.3s;
  -o-transition: 0.3s;
  transition: 0.3s;
  margin-bottom: 30px;
  -webkit-border-radius: 5px;
  -moz-border-radius: 5px;
  border-radius: 5px;
}

#img{
  width: 10px;
}
</style>
