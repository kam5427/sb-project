<template>
  <div class="">
    <div class="container-fluid first">
      <div class="row justify-content-md-center">
        <div class="col-10 " >
          <div class="row">
            <div class="col-6 f">
              <h1 class="h_first">
                Онлайн-сервис
              </h1>
              <h1 class="h_first">
                для развития <span style="color:#F85257" >DIGITAL</span> и <span style="color:#F85257" >SOFT</span> навыков
              </h1>
              <button type="button" class="btn btn-white btn-lg"> <h4 style="margin: 0px;">Узнать подробности</h4></button>
            </div>
            <div class="col-6 rocket">
              <img src="~~/assets/svg/rocket.svg" alt="">
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
              <div class="col-5">
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
              <div class="col-6 offset-1" style="margin-top:-100px;">
                <img src="~~/assets/svg/svg-planets.svg" style="height: 80%;" alt="">
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="container-fluid four mb-5">
        <div class="row justify-content-md-center">
          <div class="col-8">
            <div class="lcard">
              <div class="row m-5">
                <div class="col-6 text-white">
                  <p class="ml-5 mt-5">
                    EVA - инструмент, задающий направление обучения студенту. Контролирует темп обучения и подстраивается под вас. Высокая эффективность обеспечивается моделью ученик - учитель.
                  </p>
                  <button type="button" class="btn btn-white-2 btn-lg ml-5 mb-5">
                  <h4 style="margin: 0px;">
                    Познакомься с EVA
                  </h4>
                  </button>
                </div>
                <div class="col-5">
                  <img src="~~/assets/svg/svg-polygon.svg" alt="eva" class="eva">
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
    background-position: 0 -210px;
    background-repeat:no-repeat;
  }
  .f{
    margin-top: 200px;
  }
  .rocket{
    margin-top:-40px;
  }
  .h_first{
    color:white;
  }
  .btn-white{
    margin-top:57px;
    background-color: white;
    height: 80px;
    width: 350px;
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
    height:670px ;
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
    height: 80px;
    width: 350px;
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


