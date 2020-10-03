<template>
  <div class="">
    <div class="container-fluid first">
      <div class="row justify-content-md-center">
        <div class="col-lg-10 col-12" >
          <div class="row" style="margin-top:70px;">
            <div class="col-lg-6 col-md-4 col-12 f">
              <h1 class="h_first">
                Онлайн-сервис
              </h1>
              <h1 class="h_first">
                для развития <span style="color:#F85257" >DIGITAL</span> и <span style="color:#F85257" >SOFT</span> навыков
              </h1>
              <button type="button" class="btn btn-white btn-lg"> <h4 style="margin: 0px;">Узнать подробности</h4></button>
            </div>
            <div class="col-lg-6 col-md-8 col-12  ">
              <img src="~~/assets/svg/rocket.svg" class="rocket" alt="" width="100%" height="auto">
            </div>
          </div>
        </div>
        </div>
      </div>

      <div class=" container-fluid second">
        <div class="row justify-content-md-center">
          <div class="col-12">
            <h1 class="text-center mb-5">
              Почему нужно учиться у нас?
            </h1>
          </div>
          <div class="col-12">
            <div class="row mt-5 justify-content-md-center">
              <div class="col-3 text-center about">
                <img class="mb-5" src="~~/assets/svg/astr.svg" alt="">
                <h5>Погружение </h5>
                <p>Найдем для тебя заказы и задачи из реального бизнеса</p>
              </div>
              <div class="col-3 text-center about">
                <img class="mb-5" src="~~/assets/svg/book.svg" alt="">
                <h5>Аналитика и метрика </h5>
                <p>Индивидуальные аналитики и метрики</p>
              </div>
              <div class="col-3 text-center about">
                <img class="mb-5" src="~~/assets/svg/start.svg" alt="">
                <h5>Визуализация обучения </h5>
                <p>Покажем тракеторию твоего развития</p>
              </div>
              <div class="col-3 text-center about">
                <img class="mb-5" src="~~/assets/svg/alien.svg" alt="">
                <h5>Трудоустройство</h5>
                <p>Предоставим тебе опыт работы и подготовим к собеседованию</p>
              </div>
            </div>
          </div>
        </div>
      </div>

    <div class="container-fluid third">
      <div class="row">
        <div class="col-12" style="margin-top: 200px;">
          <div class="container">
            <div class="row">
              <div class="col-lg-4 col-12">
                <h1 class="h-first mb-5">
                  Как это работает?
                </h1>
                <h5 class="text-white"> Многоуровневая игра
                  с которой процесс обучения
                  становится легче и проще.
                  Всего 10% теории,
                  остальное практика — реальные
                  задачи из реального бизнеса.</h5>
                <h5 class="text-white">Работа в командах, личный наставник, сообщество единомышленников и полное погружение в мир профессии ждут студентов на платформе.</h5>
              </div>
              <div class="col-lg-7 col-12 offset-md-1 mt-4 mt-md-0" style="margin-top:-100px;">
                <img src="~~/assets/svg/svg-planets.svg" height="auto" width="100%">
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="container-fluid four mb-5">
        <div class="row justify-content-md-center">
          <div class="col-md-8 col-12">
            <div class="lcard">
              <div class="row m-md-5 m-0">
                <div class="col-md-6 col-12 text-white">
                  <p class="ml-md-5 mt-md-5 mt-3 ml-3">
                    EVA - инструмент, задающий направление обучения студенту. Контролирует темп обучения и подстраивается под вас. Высокая эффективность обеспечивается моделью ученик - учитель.
                  </p>
                  <button type="button" class="btn btn-white-2 btn-lg ml-md-5 ml-3 mb-5">
                  <h4 style="margin: 0px;">
                    Познакомься с EVA
                  </h4>
                  </button>
                </div>
                <div class="col-lg-5 col-12">
                  <img src="~~/assets/svg/svg-polygon.svg" class="d-none d-sm-block eva" alt="eva" >
                </div>
              </div>
            </div>
          </div>
        </div>
    </div>


  </div>

</template>

<style>
  .first {
    background-image: url('~assets/svg/background.svg');
    background-position: 0 -93px;
    background-repeat:no-repeat;
    margin-top: -160px;
    height: 900px;
  }
  .f{
    margin-top: 200px;
  }
  .rocket{
margin-top: 185px;

  }
  .h_first{
    color:white;
  }
  .btn-white{
    margin-top:57px;
    background-color: white;
    height: 60px;
    width: auto;
    color:#701678;
    border-radius: 26px;
    box-shadow: 0 0 10px 2px #F85257;
  }
  .second{
    margin-top:58px;
  }
  .about{
    width: 338px;
  }
  .third{
    background-image: url('~assets/svg/bg2.svg');
    height:750px ;
    margin-top: 100px;
  }
  .h-first{
    color:white;
  }
  .lcard{
    margin-top: 100px;
    background-image: url('~assets/svg/Rectangle-5.svg');
    border-radius: 15px;
    background-repeat:no-repeat;
    height: 300px;
  }
  .btn-white-2{
    margin-top:17px;
    background-color: white;
    height: 60px;
    width: auto;
    color:#701678;
    border-radius: 26px;
    box-shadow: 0 0 10px 2px #F85257;
  }
  .eva{
    margin-top:-210px;
    margin-left: -50px;
    height: 130%;
  }
</style>


