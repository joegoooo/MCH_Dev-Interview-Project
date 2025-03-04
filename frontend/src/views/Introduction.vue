<template>
  <div class="introduction">
    <header class="intro-header">
      
      <div class="intro-container">

        <img src="../assets/selfie.jpg" alt="Hello" class="selfie"></img>

        <div class="intro-text">
          <h2>自我介紹</h2>
          <p>
            我是黃奕淇，交大資工大一生。興趣是打打羽球、追追動漫（最近推青之驅魔師）。
            高中時除了自學C++外，還有自學Python跟Pygame。
            高二時有稍微接觸過網頁前端相關知識(HTML等)。
            希望能加入開發部的行列，學習更深的開發知識，一起完成專案！
          </p>

        </div>
      
      </div>    
    
    </header>
    <section class="about-section">
      <h3>個人資訊補充</h3>
      <ul>
        <li>好棒棒1</li>
        <li>好棒棒2</li>
        <li>好棒棒3</li>
      </ul>
      
    </section>
  </div>
</template>


<style scoped>
/* import font */
@font-face {
  font-family: 'cwTeXFangSong';
  font-style: normal;
  font-weight: 500;
  src: url(//fonts.gstatic.com/ea/cwtexfangsong/v3/cwTeXFangSong-zhonly.eot);
  src: url(//fonts.gstatic.com/ea/cwtexfangsong/v3/cwTeXFangSong-zhonly.eot?#iefix) format('embedded-opentype'),
       url(//fonts.gstatic.com/ea/cwtexfangsong/v3/cwTeXFangSong-zhonly.woff2) format('woff2'),
       url(//fonts.gstatic.com/ea/cwtexfangsong/v3/cwTeXFangSong-zhonly.woff) format('woff'),
       url(//fonts.gstatic.com/ea/cwtexfangsong/v3/cwTeXFangSong-zhonly.ttf) format('truetype');
}



.introduction {
  font-family: 'cwTeXFangSong';
  padding: 40px 20px;
  max-width: 1200px;
  margin: 0 auto;
}

.intro-header {
  background-color: #fafafa;
  padding: 40px;
  border-radius: 30px;
}

.intro-container {
  display: flex;
  align-items: center;
  gap: 40px;
}

.selfie {
  display: flex;
  width: 200px;
  height: 200px;
  border-radius: 50%;
}

.intro-text h2 {
  font-size: 2.5rem;
  margin-bottom: 20px;
}

.intro-text p {
  font-size: 1.7rem;
  margin-bottom: 20px;
}

.contact-button {
  padding: 10px 20px;
  background-color: #656d73;
  border: none;
  border-radius: 5px;
  color: #fff;
  cursor: pointer;
}

.contact-button:hover {
  background-color: #36383a;
}

.about-section {
  margin-top: 40px;
  padding: 0 40px;
}

.about-section h3 {
  font-size: 2rem;
  margin-top: 20px;
  margin-bottom: 10px;
}

.about-section p {
  font-size: 1.5rem;
  line-height: 1.6;
}

@media screen and (max-width: 576px) {
  .intro-container {
    display: block;
    align-items: center;
    gap: 40px;
  }

  .selfie {
    display: block;
    width: 200px;
    height: 200px;
    border-radius: 50%;
  }
}

</style>
