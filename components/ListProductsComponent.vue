<template>
  <div>
    <div class="container">
      <ul>
        <li class="product">
        <div class="product__img">
          <img src="../img/product.png" alt="">
        </div>
        <div class="product__text">
          <div class="product__title">Наименование товара</div>
          <div class="product__desk">Довольно-таки интересное описание товара в несколько строк. Довольно-таки интересное описание товара в несколько строк</div>
          <div class="product__price">10 000 руб.</div>
        </div>
        </li>
        <li class="product">
        <div class="product__img">
          <img src="../img/product.png" alt="">
        </div>
        <div class="product__text">
          <div class="product__title">Наименование товара</div>
          <div class="product__desk">Довольно-таки интересное описание товара в несколько строк. Довольно-таки интересное описание товара в несколько строк</div>
          <div class="product__price">10 000 руб.</div>
        </div>
        </li>
                <li class="product">
        <div class="product__img">
          <img src="../img/product.png" alt="">
        </div>
        <div class="product__text">
          <div class="product__title">Наименование товара</div>
          <div class="product__desk">Довольно-таки интересное описание товара в несколько строк. Довольно-таки интересное описание товара в несколько строк</div>
          <div class="product__price">10 000 руб.</div>
        </div>
        </li>
        <li class="product">
        <div class="product__img">
          <img src="../img/product.png" alt="">
        </div>
        <div class="product__text">
          <div class="product__title">Наименование товара</div>
          <div class="product__desk">Довольно-таки интересное описание товара в несколько строк. Довольно-таки интересное описание товара в несколько строк</div>
          <div class="product__price">10 000 руб.</div>
        </div>
        </li>
                <li class="product">
        <div class="product__img">
          <img src="../img/product.png" alt="">
        </div>
        <div class="product__text">
          <div class="product__title">Наименование товара</div>
          <div class="product__desk">Довольно-таки интересное описание товара в несколько строк. Довольно-таки интересное описание товара в несколько строк</div>
          <div class="product__price">10 000 руб.</div>
        </div>
        </li>
        <li class="product">
        <div class="product__img">
          <img src="../img/product.png" alt="">
        </div>
        <div class="product__text">
          <div class="product__title">Наименование товара</div>
          <div class="product__desk">Довольно-таки интересное описание товара в несколько строк. Довольно-таки интересное описание товара в несколько строк</div>
          <div class="product__price">10 000 руб.</div>
        </div>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>

export default {
  data() {
    return {
      
    }
  }
}
</script>

<style scoped>
.container{
margin-top: 83px;
}

.product{
  display: inline-block;
  margin-left: 16px;
  margin-bottom: 16px;
  width: 332px;
  height: 423px;
  box-shadow: 0 0 10px rgba(0,0,0,0.2);
  background: rgb(255, 255, 255);
  border-radius: 4px;
}

.product__text{
  margin-left: 16px;
  margin-right: 16px;
}

.product__title{
  font-family: 'Source Sans Pro', sans-serif;
  font-weight: 600;
  font-size: 20px;
  margin-top: 16px;
  line-height: 25,14px;
}

.product__desk{
  font-family: 'Source Sans Pro', sans-serif;
  font-weight: 400;
  font-size: 16px;
  margin-top: 16px;
  line-height: 20,11px;
}

.product__price{
  font-family: 'Source Sans Pro', sans-serif;
  font-weight: 600;
  font-size: 24px;
  margin-top: 16px;
  line-height: 30,17px;
  margin-bottom: 24px;
}
</style>