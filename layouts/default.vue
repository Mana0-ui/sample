<template> <!-- ページ全体の共通レイアウト-->
  <div>
    <nuxt />
    <footer>
    
      <div class="footer-logo">
        <div class="footer-image">
         <img src="~assets/images/foot_logo.png" alt="レモン社">
        </div>
      </div>
      <div class="row footer">
        <div class="col-6  d-md-none">
          <div class="container">
           <p>銀座教会店</p>
          </div>
        </div>
        <div class="col-6  d-md-none" >
          <div class="container">
          <p>新宿店</p>
          </div>
        </div>
        <div class="col-6  d-md-none" >
          <div class="container">
          <p>秋葉原店</p>
          </div>
        </div>
        <div class="col-6  d-md-none">
          <div class="container">
          <p>横浜店</p>
          </div>
        </div>
        <div class="col-6  d-md-none ">
          <div class="container">
          <p>名古屋栄店</p>
          </div>
        </div>
        <div class="col-6  d-md-none ">
          <div class="container">
          <p></p>
          </div>
        </div>
        <div class="col-6  d-md-none" >
          <div class="container">
          <p>店舗コンセプト</p>
          </div>
        </div>
        <div class="col-6  d-md-none" >
          <div class="container">
          <p>こだわり</p>
          </div>
        </div>
        <div class="col-6  d-md-none ">
          <div class="container">
          <p>会社概要</p>
          </div>
        </div>
        <div class="col-6  d-md-none ">
          <div class="container">
          <p>沿革</p>
          </div>
        </div>
        <div class="col-6  d-md-none">
          <div class="container">
          <p>作例</p>
          </div>
        </div>
        <div class="col-6  d-md-none" >
          <div class="container">
          <p>商品ラインナップ</p>
          </div>
        </div>
        <div class="col-6  d-md-none ">
          <div class="container">
          <p>商品を買う</p>
          </div>
        </div>
        <div class="col-6  d-md-none ">
          <div class="container">
          <p>商品を売る</p>
          </div>
        </div>
        <div class="col-6  d-md-none ">
          <div class="container">
          <p>中古情報</p>
          </div>
        </div>
        <div class="col-6  d-md-none" >
          <div class="container">
          <p>商品レビュー</p>
          </div>
        </div>
        <div class="col-6  d-md-none ">
          <div class="container">
          <p>ナニワグループオンライン</p>
          </div>
        </div>
        <div class="col-6  d-md-none ">
          <div class="container">
          <p>ナニワグループブログ</p>
          </div>
        </div>
      

      <!-- md以上のフッター -->

      <div class="d-none d-md-block col-md-3">
          <div>
          <p>銀座教会店</p>
          </div>
        </div>
        <div class="d-none d-md-block col-md-3" >
          <div>
          <p>店舗コンセプト</p>
          </div>
        </div>
        <div class="d-none d-md-block col-md-3" >
          <div>
          <p>作例</p>
          </div>
        </div>
        <div class="d-none d-md-block col-md-3">
          <div>
          <p>中古情報</p>
          </div>
        </div>
        <div class="d-none d-md-block col-md-3 ">
          <div>
          <p>新宿店</p>
          </div>
        </div>
        <div class="d-none d-md-block col-md-3 ">
          <div>
          <p>こだわり</p>
          </div>
        </div>
        <div class="d-none d-md-block col-md-3" >
          <div>
          <p>商品ラインナップ</p>
          </div>
        </div>
        <div class="d-none d-md-block col-md-3" >
          <div>
          <p>商品レビュー</p>
          </div>
        </div>
        <div class="d-none d-md-block col-md-3 ">
          <div>
          <p>秋葉原店</p>
          </div>
        </div>
        <div class="d-none d-md-block col-md-3 ">
          <div>
          <p>会社概要</p>
          </div>
        </div>
        <div class="d-none d-md-block col-md-3">
          <div>
          <p>商品を買う</p>
          </div>
        </div>
        <div class="d-none d-md-block col-md-3" >
          <div>
          <p>ナニワグループオンライン</p>
          </div>
        </div>
        <div class="d-none d-md-block col-md-3 ">
          <div>
          <p>横浜店</p>
          </div>
        </div>
        <div class="d-none d-md-block col-md-3 ">
          <div>
          <p>沿革</p>
          </div>
        </div>
        <div class="d-none d-md-block col-md-3 ">
          <div>
          <p>商品を売る</p>
          </div>
        </div>
        <div class="d-none d-md-block col-md-3" >
          <div>
          <p>ナニワグループブログ</p>
          </div>
        </div>
        <div class="d-none d-md-block col-md-3 ">
          <div>
          <p>名古屋栄店</p>
          </div>
        </div>
        <div class="d-none d-md-block col-md-3 ">
          <div>
          <p></p>
          </div>
        
        </div>

      
      
      <div class="footer-last">
        <p>＜古物商許可番号＞ 東京都公安委員会許可 第301068400194号 Copyright © 2020 lemonsha All Rights Reserved.</p>
      </div>
    </div>
    </footer>

    <!--  共通のフッター -->
    
  </div>
</template>
<script>
export default{

}
</script>
<style>
footer{
  width: 100%;
  background-color: #DDD;
  text-align: center;
  
}
.footer-logo{
 width: 100%;
 padding: 25px 0;
}
.footer-image{
  width: 100px;
  height: 29.09px;
  margin: 0 auto;

}
.footer-image img{
width: 100%;
height: 100%;
}
.footer-last{
  width: 100%;
  background-color: #666666;
  color: white;
  font-size: 12px;
}

</style>
