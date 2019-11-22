<template>
  <div> 
    <div id="app" >
      
      <header>
        <div class="logo">
          <img src="./assets/logo.png" alt="ER-Películas">
        </div>
          <div class="menu">
            <ul>
              <li>
                <a href="#">Home</a>
              </li>
              <li>
                <a href="#">Sobre</a>
              </li>
              <li>
                <a href="#">Portfólio</a>
              </li>
            </ul>
        </div>
      </header>
      
      <div class="banner">
        <div class="container">
          <div class="row">
            <div class="col-12 col-md-7">
              <h1>
                Peliculas empresariais especiais. Venha conhecer
              </h1>

              <a href="" class="button-default">Ver mais sobre</a>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="bg-dark">
      <div class="container">
          <div class="row">
            <div class="col-12 col-md-7">
              <h2>Sobre a <strong>ER</strong> </h2>
                <p>
                  A ER PELÍCULAS conta com profissionais altamente qualificados que estão no ramo a <strong>15</strong> anos, possuímos o certificado NR35 (trabalho em altura) exigido pelas pequenas e grandes empresas.
                </p>
                
                <p>A nossa empresa é especializada em películas arquitetônicas prediais, industrias, comerciais, residências, de segurança e decorativa.</p>
            </div>

            <div class="col-12 col-md-5">
              <a href="#"> <img src="./assets/img-sobre.png" alt=""></a>
            </div>
          </div>
      </div>
    </div>

    <div class="bg-white">
        <div class="container">
          <div class="row">
            <div class="col-12 col-md-6">
              <img src="./assets/img-protecao.jpg" alt="">
            </div>

            <div class="col-12 col-md-6">
    
              <h3>Proteção e Qualidade</h3>
              <span>99%</span>
                <ul>
                  <li>Bloqueio de até 99% dos raios UV; </li>
                </ul>

                <ul>
                  <li>Torna o vidro mais 
                  resistente, pois evita 
                  o estilhaço causado 
                  por impacto; </li>
                </ul>
              
              <span>70%</span>
                <ul>
                  <li>Ambiente decorativo, pois possui diversas cores e modelos;</li>
                </ul>
                
                <ul>
                  <li>70% economia de energia e refrigeração do ambiente;</li>
                </ul>
            </div>
          </div>
        </div>
    </div>
          
    <div class="bg-black">
      <div class="container">
        <div class="row">
          <div class="col-12 col-md-4">
            <h4>Películas Arquitetônicas: </h4>
            <img src="./assets/img-arquitetonicas.jpg" alt="">
            <p>Auxiliam no conforto e consumo de energia, protegendo o ambiente da luminosidade excessiva, calor interno e danos as mobílias causados pelos raios UV.</p>

            <p>As películas arquitetônicas ajudam proteger a sua saúde, bloqueando até 99% dos raios UV no ambiente e evitando câncer de pele e problemas oculares.</p>

            <p>Trabalhamos com variados modelos e cores de películas para o seu ambiente. <br> Benefícios:</p>
            
            <a href="button-white">Ver mais projetos como este</a>
          
          </div>

          <div class="col-12 col-md-4">
            <h4>Películas Decorativas:</h4>
            <img src="./assets/peliculas-decorativas.jpg" alt="">
            <p>Uma ótima opção para quem deseja decorar seu ambiente e torna-lo mais privativo, conta com diferentes texturas e detalhes.</p>

            <p>As películas decorativas podem ser utilizadas em vários ambientes como box de banheiro, janelas, portas e vidros internos e externos.</p>

            <p>Também utilizada em escritórios e comércios. Há várias sugestões para sua aplicação, como em divisória, fechamentos de área, em guaritas, e fachadas de lojas.</p>
            <a href="button-white">Ver mais projetos como este</a>

          </div>

          <div class="col-12 col-md-4">
            <h4>Películas de Segurança:</h4>
            <img src="./assets/img-seguranca.jpg" alt="">
            <p>Desenvolvida para segurança de ambientes tem a função de bloquear a entrada forçada não autorizada evitando o vandalismo.</p>

            <p>Já em caso de algum incidente no local aplicado, aumenta a resistência do vidro e na quebra impede que seus estilhaços atinjam pessoas que estão no ambiente, sendo um ótimo fator de segurança e custo benefício.</p>

            <p>Muito usado em portas, janelas, vitrines, sacadas, parapeitos e tetos de vidro.</p>
            <a href="button-white">Ver mais projetos como este</a>
          </div>

        </div>
      </div>
    </div>

    <div class="bg-gray">
      <div class="container">
        <div class="row">
          <div class="col-12 col-md-6">
            <img src="./assets/img-fale-conosco.png" alt="">
          </div>

          <div class="col-12 col-md-6">
            <h2>Fale <br> <strong>Conosco</strong> </h2> 
            <p>E solicite um orçamento agora mesmo. <br> Qualquer dúvida ou sugestão, estaremos <br> prontos para lhe atender da melhor forma.  </p>
            <p>Telefone: <br> <strong>(47) 3546.0909</strong> </p>
            <p>E-mail: <br> <strong>(47) 3546.0909</strong> </p>
          </div>
        </div>
      </div>
    </div>

    <footer>
      <div class="container">
        <div class="row">
          <div class="col-12 text-center">
            <img src="./assets/logo.png" alt="">
            <p>A nossa empresa é especializada em películas <br>arquitetônicas prediais, industrias, comerciais, <br>residências, de segurança e decorativa. </p>
            <p>Copyright © 2018 - ER Películas - Todos os direitos reservados </p>
          </div>
        </div>
      </div>
    </footer> 
    
  </div>
</template>



<script>

import "bootstrap/dist/css/bootstrap.css"

export default {
  name: 'app',
  
}
</script>

<style>


.logo {
  background: #171717;
  width: 313px;
  height: 80px;
  border-style: solid;
  border-width: 3px;
}
.menu {
  background: #171717;
  width: 531px;
  height: 80px;
  font-family: Raleway Medium;
  margin: left;
}

.menu li a {
  font: Raleway Medium;
  font-size: 16px;
  line-height: 19px;
  color: #FFFFFF;
  list-style: inline;
  padding: left;
}

.bg-dark{
  padding: 50px 0;
  background:#171717;
  
}
  .bg-dark p {
    color: #FFFFFF
  }
  .bg-dark h2 {
    color: #FFFFFF;	
    font-size: 60px;	
    font-weight: 300;	
    line-height: 70px;
    margin-bottom: 35px;
  }
  .bg-dark strong {
    font-weight: 650;
  }
.bg-white{
  padding: 50px 0;
}

.bg-black{
  padding: 50px 0;
  background:#171717;
  
}
  .bg-black p {
    color: #F7F7F7
  }

.bg-gray{
  padding: 50px 0;
  background:#FFFFFF
}

footer{
  padding: 50px 0;
  background:#232323
}




</style>
