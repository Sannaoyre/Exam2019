<template>
  <div class="[ wrapper ]">

      <div class="[ headline ]">
        <h1 class="[ headline_one ]">I'm Markus Eldevik</h1>
        <h2 class="[ headline_two ]">ABOUT ME</h2>
      </div>

      <b-container fluid class="[ about ]">
          <b-row>
                <b-col sm="12" md="2" lg="4">
              IMG
                </b-col>

                <b-col sm="12" md="6" lg="4">
                  <h3 class="[ about_headline ]">Hey!</h3>
                  <p class="[ about_text ]">Norway based 24-year-old film editor that is progressively leaning more towards motion graphic design. I do jobs on advertisement projects, music videos and logo animations.<br><br> Norway based 24-year-old film editor that is progressively leaning more towards motion graphic design.
                  </p>
                </b-col>

                <b-col  sm="12" md="4" lg="4">
                  <div class="[ skillbar ]">

                    <div class="[ skillbar-outer ]">
                        <div class="[ skillbar-inner ]">
                          <div><p class="[ skillbar_inner-text ]">Adobe Audition</p></div>
                        </div>
                    </div>

                    <div class="[ skillbar-outer ]">
                        <div class="[ skillbar-innerTwo ]">
                          <div><p class="[ skillbar_inner-text ]">Adobe Premiere Pro</p></div>
                        </div>
                    </div>

                    <div class="[ skillbar-outer ]">
                        <div class="[ skillbar-innerThree ]">
                          <div><p class="[ skillbar_inner-text ]">Adobe After Effects</p></div>
                        </div>
                    </div>

                    <div class="[ skillbar-outer ]">
                        <div class="[ skillbar-innerFour ]">
                          <div><p class="[ skillbar_inner-text ]">Adobe Illustrator</p></div>
                        </div>
                    </div>

                    <div class="[ skillbar-outer ]">
                        <div class="[ skillbar-innerFive ]">
                          <div><p class="[ skillbar_inner-text ]">Adobe Photoshop</p></div>
                        </div>
                    </div>

                  </div>

                </b-col>
          </b-row>
    </b-container>
  </div>
</template>

<script>
</script>


<style lang="scss" scoped>
@import '@/styles/main.scss';


.wrapper{
  margin-left: 5%;
  margin-right: 5%;
}

.headline{
  text-align: center;
  margin-top: 2%;
  &_one{
    color: $primary-white;
    font-size: $subheading-1-mobile;
    font-family: $title-font;
  }
  &_two{
    font-weight: 100;
    color: $primary-white;
    font-family: $title-font;
    font-size: $subheading-3-mobile;
  }
}

.about{
  margin-top: 5%;
  &_text{
    color: $primary-white;
    font-size: $subheading-4-mobile;
  }
  &_headline{
    color: $primary-white;
    font-size: $subheading-3-mobile;
  }
}

.skillbar{

  &-outer{
    background-color: $primary-white;
    border-radius: 3em;
    width: 100%;
  }
  &-inner{
    width: 90%;
    border-radius: 3em;
    background-color: $primary-orange;
    &Two{
        width: 80%;
        border-radius: 3em;
        background-color: $primary-orange;
    }
    &Three{
      width: 70%;
      border-radius: 3em;
      background-color: $primary-orange;
    }
    &Four{
      width: 60%;
      border-radius: 3em;
      background-color: $primary-orange;
    }
    &Five{
      width: 50%;
      border-radius: 3em;
      background-color: $primary-orange;
    }
    &-text{
      color: $primary-black;
      margin: 10px;
      font-size: 16px;
    }
  }
}

.skillbar_inner-text{
  color: $primary-black;
  margin: 20px;
  padding: 2px;
  font-size: 13px;
}



@media screen and (min-width: 700px){
  .headline{
    margin-top: 2%;
    &_one{
      font-size: $subheading-1;
    }
    &_two{
      color: $primary-white;
      font-family: $title-font;
      font-size: $subheading-3;
    }
  }

  .about{
    &_text{
      font-size: $subheading-4-mobile;
    }
    &_headline{
      font-size: $subheading-3;
    }
  }

  .skillbar{
    &_inner-text{
      margin: 12px;
      font-size: 8px;
    }
  }
}




@media screen and (min-width: 900px){
  .about{
    &_text{
      font-size: $subheading-4;
    }
    &_headline{
      font-size: $subheading-3;
    }
  }

  .skillbar{
    &_inner-text{
      margin: 18px;
      font-size: 16px;
    }
  }
}

</style>
