<template>
  <div class="[ header ]">

      <div class="[ header_background ]">
          <div class="[ header_background-square ]">
              <video autoplay muted loop>
                  <source src="http://clips.vorwaerts-gmbh.de/VfE_html5.mp4" type="video/mp4">
              </video>
          </div>
          <div class="header_background-text">
              <h2 id="firstText"><span id="firstText_bold">MARKUS</span> ELDEVIK</h2>
              <h3 id="secondText">FILM EDITOR</h3>
              <h4 id="thirdText">	&amp; MOTION GRAPHIC DESIGNER</h4>
         </div>
      </div>


  </div>
</template>

<script>

</script>

<style lang="scss" scoped>
@import '@/styles/main.scss';

.header{
  width: 100%;
  height: 100%;
    &_background{
      background-image: linear-gradient(to right, $primary-black 50%, $primary-orange 50%);
      background-size: cover;
      height: 600px;

        &-square{
          height: 200px;
          width: 200px;
          background-color: $primary-gray;
          transform: rotate(45deg);
          margin-left: auto;
          margin-right: auto;
          overflow: hidden;
          box-shadow: 5px 10px 18px $primary-black;
          position: relative;
          top: 30%;
          outline: 4px solid $primary-gray;
          outline-offset: 5px;
          display: -webkit-box;
          display: -ms-flexbox;
          display: -webkit-flex;
          display: flex;
          justify-content: center;
          align-items: center;
        }

        &-text{
          color: $primary-white;
          font-family: $header-font;
          font-weight: 100;
          line-height: 0.5em;
          margin-left: 5%;
          margin-top: 60%;

      }
    }
  }

    #firstText{
      font-size: 18px;
      font-weight: 100;
    }
    #firstText_bold{
      font-weight: bolder;
    }
    #secondText{
      font-size: 13.5px;
      letter-spacing: 0.5em;
      font-weight: 100;
    }
    #thirdText{
      font-size: 8.5px;
      letter-spacing: 0.1em;
      color: $primary-orange;
    }

    video {
    min-height: 150%;
    position: absolute;
    transform: rotate(-45deg);
    margin-left: -100px;
    margin-top: 100px;
  }

@media screen and (min-width: 700px){
  .header{
      &_background{
          height: 800px;
          &-square{
            height: 300px;
            width: 300px;
          }
          &-text{
            margin-top: 40%;
        }
      }
    }

    #firstText{
      font-size: 38px;
    }
    #secondText{
      font-size: 28px;
    }
    #thirdText{
      font-size: 18px;
    }
}

@media screen and (min-width: 900px){

.header{
    &_background{
      height: 800px;
        &-square{
          height:400px;
          width: 400px;
          top: 20%;

        }
        &-text{
          margin-top: 10%;
      }
    }
  }

  #firstText{
    font-size: 40px;
  }
  #secondText{
    font-size: 30px;
  }
  #thirdText{
    font-size: 19px;
  }
}


@media screen and (min-width: 1500px){
  .header{
      &_background{
          height: 1000px;
          &-square{
            height: 500px;
            width: 500px;
          }
          &-text{
        }
      }
    }

    #firstText{
      font-size: 60px;
    }
    #secondText{
      font-size: 45px;
    }
    #thirdText{
      font-size: 28.5px;
    }
}



</style>
