<template>
  <form class="container">
    <div class="title">
    Добавление товара
    </div>
    <div class="main">
      <div class="main__block">
        <div class="main__title">
          Наименование товара
          <div class="red-point"></div>
        </div>
        <input class="main__input" type="text" placeholder="Введите наименование товара">
      </div>
      <div class="main__block">
        <div class="main__title">
          Описание товара
        </div>
        <input class="main__input" type="text" placeholder="Введите описание товара">
      </div>
      <div class="main__block">
        <div class="main__title">
          Ссылка на изображение товара
          <div class="red-point"></div>
        </div>
        <input class="main__desk" type="text" placeholder="Введите ссылку">
      </div>
      <div class="main__block">
        <div class="main__title">
          Цена товара
          <div class="red-point"></div>
        </div>
        <input class="main__input" type="text" placeholder="Введите цену">
      </div>
      <button class="btn">
        Добавить товар
      </button>
    </div>
  </form>
</template>

<style scoped>
.container{
  margin-left: 32px;
}

.title {
  font-family: 'Source Sans Pro', sans-serif;
  font-weight: 600;
  font-size: 28px;
  line-height: 35,2px;
  margin-bottom: 16px;
  margin-top: 32px;
}

.main{
box-shadow: 0 0 10px rgba(0,0,0,0.2);
border-radius: 4px;
width: 332px;
display: block;
padding: 24px;
}


.main__title{
  display: flex;
  font-family: 'Source Sans Pro', sans-serif;
  font-weight: 400;
  font-size: 10px;
  line-height: 12,57px;
  margin-bottom: 4px;
}

input {
  display: block;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
  border: none;
  outline:none;
  border-radius: 4px;
  width: 268px;
  margin-bottom: 16px;

}

input:focus {
  box-shadow: 0 0 10px rgba(0,0,0,0.5);
}

input[type="text" i]{
  padding: 0px 0px;
  padding-top: 10px;
  padding-right: 0px;
  padding-bottom: 11px;
  padding-left: 16px;
}

.main__desk{
  width: 268px;
  height: 108px;
}

.btn{
  font-family: 'Source Sans Pro', sans-serif;
  font-weight: 600;
  font-size: 12px;
  background: #EEEEEE;
  color:#B4B4B4;
  border:none;
  border-radius: 10px;
  padding: 10px 95px 11px 96px;
}

.btn:hover{
  background: #494848;
  color:#eeeded;
}

.red-point{
  content: '';
  background-color:#FF0000;
  border-radius:50%;
  width: 4px;
  height: 4px;
  pointer-events: none;
  margin-left: 0px;
}

</style>