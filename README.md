<h1 align="center">I-Can-Buy-Myself-Flowers</h1>
<br />
<div align="center">
<a href="https://github.com/KsuNyota/KsuNyota">
</a>
<h2 align="left">Описание</h2>
<p align="left">
Это приложение направлено на поиск нужного растения. Если Вы не знаете, какое растение подходит именно Вам, может Вы новичок или у Вас есть домашние питомцы? В этом приложении Вы смотжете выбрать для себя лучший вариант комнатного растения. Ну а если Вы в этом совсем не разбираетесь, то Вы можете пройти тест и узнать, какое растение подходит именно Вам!
  <h2 align="left">Как скачать проект</h2>
  <ul align="left"><li>Клонировать проект в Visual Studio или скачать архивом</li>
<li>Найти файл Flowers.sln</li>
<li>Нажать по нему 2 раза</li>
<li>Нажать кнопку "Flowers"</li></ul>
  <h2 align="left">Как пользоваться приложением</h2>
  <ol align="left"><li>Зарегистрироваться или войти</li>
<li>Пользоваться нужными функциями</li></ol>
<h2 align="left">Каталог</h2>
<ul align="left"><li>Тест: Какое растение Вам подходит</li>
<li>Крупные растения</li>
<li>Для начинающих</li>
<li>Безопасны для животных</li>
<li>Устойчивы к слабому освещению</li></ul>
<h2 align="left">Корзина</h2>
<p align="left">
Все понравившиеся растения можно добавлять в корзину, а затем оплатить.
<h2 align="left">Профиль</h2>
<p align="left">
В Вашем профиле Вы можете поменять фамилию, имя, логин и пароль.
<h2 align="left">О проекте</h2>
<h3 align="left">Добавление в корзину</h3>
<p align="left">
<ul align="left"><li>Данные в корзину добавляются при помощи вспомогательных файлов.</li>
  <pre>
    <div class="container">
      <div class="code">
        <h4>Добавление в корзину</h4>
        <div class="wrap">
          int sh = 0;
            int sm = 0;
            string pokupki = @"pokp.txt";
            string cpc = "";
            cpc = File.ReadAllText(pokupki);
            spic.Text = cpc;
            string tht = @"theni.txt";
            string jnj = File.ReadAllText(tht);
            cost.Text = jnj;
            string[] pnp = jnj.Split();
            foreach (string p in pnp)
            {
                if (p != "")
                {
                    sm = sm + Convert.ToInt32(p);
                    summa.Text = Convert.ToString(sm);
                }
            }
        </div>
      </div>
    </div>
  </pre>
<li>Из корзины можно перейти на другие страницы приложения.</li></ul>
<h3 align="left">Тест</h3>
<p align="left">
<ul align="left"><li>Нужное растение выберится в зависимости от результата теста.</li>
<li>Будет показана картинка и название растения.</li></ul>
    <p align="left"><b>Приятный кактус</b></p>
<picture>
  <img alt="Приятный кактус" src="https://github.com/KsuNyota/KsuNyota/blob/master/Flowers/Resources/безопасно%20для%20животных/Приятный%20кактус.jpg">
</picture>

<h2 align="left">Где нас найти</h2>
<p align="left">Ссылка на репозиторий: https://github.com/Lord-Veliar/I-Can-Buy-Myself-Flowers
</div>
  
<!--
**KsuNyota/KsuNyota** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
