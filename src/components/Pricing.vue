<template>
  <div class="pricing_area">
    <section class="pricing py-5">
      <div class="container">
        <div class="row justify-content-center">
          
                <div class="col-lg-10">

                    <div class="section_title text-center mb-70">
                    

                    <span
                class="wow fadeInUp"
                data-wow-duration="1s"
                data-wow-delay=".3s"
                >03 PRICING</span>

                        
                        
                        <h3 class="wow fadeInUp" data-wow-duration="1.2s" data-wow-delay=".2s">Plans for less than a monthly garage space</h3>
                        <span class="wow fadeInUp" data-wow-duration="1s" data-wow-delay=".1s" >
                          Every plan includes concierge delivery and pick-up, cleaning and refueling, full insurance coverage, and vehicle maintenance. Your only additional cost is tolls and gas while you're driving.


                        </span>
                    
                    </div>
                </div>
            </div>
        <div class="row">
          <!-- Free Tier -->
          <div class="col-lg-4" v-for="(obj,key) in PrincingJson" :key="key">
            <div class="card mb-5 mb-lg-0">
              <div class="card-body">
                <h1 class="card-title text-muted  text-center">{{obj.type}}</h1>
                <h6 class="card-title1 text-muted  text-center">
                  {{obj.day}}
                </h6>

                <h6 class="card-price text-center">
                  {{obj.price}}<span class="period">/ month</span>
                </h6>
                <hr />

                <h5 class="card-descption text-muted  text-center">
                  {{obj.description}}
                </h5>

                <a href="#" class="btn btn-block  text-uppercase"
                  > start with {{obj.type}}</a
                >
                <a href="#">
                  <h6 class="card-title1 text-muted  text-center">
                    View blan details
                  </h6>
                </a>
              </div>
            </div>
          </div>
          
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  data:()=> ({
    PrincingJson: [
      {
          type:'FLexPass',
          day:'Get 2 day/month',
          price:'159',
          description:'Not sure how you drive ? Get a magic button anytime you need a car.'
      },
      {
          type:'Getaway',
          day:'Get 4 day/month',
          price:'219',
          description:'Not sure how you drive ? Get a magic button anytime you need a car.'
      },
      {
          type:'Freedom',
          day:'Get 8 day/month',
          price:'398',
          description:'Not sure how you drive ? Get a magic button anytime you need a car.'
      }
    ]
  })
}
</script>

<style lang="css">
.card-body a{
  background-color: #4c4c4c;
  
}
  
</style>