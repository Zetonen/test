<template>
  <div id="app">
    <Nav_main/>
    <div class="hero">
      <div class="container">
        <a class="large_text">Denid Novik</a>
        <a class="small_text">UX | UI designer
          24 years old, Minsk</a>
        <div class="language">
          <a class="language_Ru">RU |</a>
          <a class="language_En"> ENG</a>
        </div>
      </div>
    </div>
    <div class="hero-body">
      <img src="data:image/jpeg;base64,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" crossorigin="anonymous">
    </div>
    <div class="hero-box">
      <a class="heading">About me</a>
      <div class="container-box">
        <p>Hi, I'm Denis – UX/UI designer from Minsk. I'm interested in design and everything connected with it.</p>
        <p>I'm studying at courses "Web and mobile design interfaces" in IT-Academy</p>
        <p>Ready to implement excellent projects with wonderful people.</p>
      </div>
    </div>
    <div class="footer">
      <a class="heading">Skills</a>
      <a class="small_text">I work in such programs as</a>
      <div class="footer-body">

      </div>
      <a class="heading">Contacts</a>
      <a class="small_text">Want to know more or just chat?
        You are welcome!</a>
      <button class="btn-black">Send message</button>
      <a class="small_text_small">Like me on
        LinkedIn, Instagram, Behance, Dribble</a>
    </div>
  </div>
</template>

<script>

  import Nav_main from '@/components/Nav_main.vue'

  export default {
    name: 'App',
    components: {
      Nav_main,
    }
  }
</script>

<style>

  .large_text{
    font-family: Gilroy-Bold;
    color: #070707;
    width: 120px;
    font-weight: bold;
    font-size: 47px;
  }
  .small_text {
    font-family: Gilroy-Medium;
    color: #070707;
    font-size: 18px;
  }
  .language{
    transform: rotate(270deg);
    font-size: 16px;
  }

  .language_En{
    font-family: Gilroy-Bold;

  }
  .container{
    display: flex;
    justify-content: space-around;
    align-items: flex-end;
    padding-top: 80px;
  }
  .hero-body{
    margin-left: 44%;
    min-height: 400px;
    padding-top: 8%;

  }
  .heading{
    font-family: Gilroy-Medium;
    color: #070707;
    font-size: 34px;
  }
  .container-box{
  }
  .hero-box{
    flex-direction: column;
    margin: 0 34%;
  }
  .footer{
    display: flex;
    flex-direction: column;
    margin: 197px 34% 0;

  }
  .small_text_small{
    font-size: 12px;
    padding-top: 20px;
    padding-bottom: 20px;
  }
  .btn-black{
    color: #FFFFFF;
    background: #070707;
    width: 180px;
    height: 40px;
    border-radius: 60px;
  }
</style>


