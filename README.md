<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name = "description" content = "Это моя первая страница...">
    <meta name = "author" content="Mikhail">
    <meta name="keywords" content="сайт-визитка, разработка сайтов, !этот тег устарел!!!">
    <meta name="robots" content="all">
    <link rel="stylesheet" href="css/reset.css">
    <link rel="stylesheet" href="css/style.css">
    <meta property="og:title" content="Это моя первая страница">
    <title>Андрей Браун - веб-разработчик</title>
</head>
<body>
    <header>
        <nav>
            <div class="logo">Андрей Браун</div>
            <div class="menu">
                <ul>
                    <li>Обо мне</li>
                    <li>Услуги</li>
                    <li>Кейсы</li>
                    <li>Прайс</li>
                    <li>Отзывы</li>
                    <li>Контакты</li>
                </ul>
            </div>
        </nav>
    </header>

    <div class="main">
        <div class="title_container">
            <h1>Привет <br>Я Андрей Браун</h1>
            <h4>фул стек веб-разработчик</h4>
            <input type="submit" value="Обо мне">
            <input type="submit" value="Мои работы">
        </div>
    </div>
    <div class="about_me">
        <div class="snd_head">
            <div class="zagolovok">
                <h2>ОБО МНЕ</h2>
            </div>
            <div class="up_picture">
                <img  class= "fst_pct" src="img/cherta.png" alt="Тут должна была быть картинка...">
            </div>
        </div>
        <div class="snd_image">
            <img  class = "lil"src="img/small_andrey_braun.png" alt="Тут должна быть картинка...">
        </div>
        <div class="snd_main_text">
            <p class="snd_main_tenxt_one">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Placeat amet tenetur enim maiores ipsa, modi quia dolorem suscipit quam vitae explicabo praesentium rem omnis iure?</p>
            <p class="nd_main_tenxt_two">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ab, magnam, vero. Fugiat tempora, fuga tempore nihil hic et placeat vel nam, consectetur iure asperiores illum.</p>
        </div>
        <div class="upload">
            <a href="https://google.com" target="_blank" class="fst_bottom" >Скачать резюме</a>
        </div>
    </div>
    <div class="what_i_can">
        <div class="third_header">
            <div class="third_zagolovok">
               <h2 class= "whaaat">ЧТО Я УМЕЮ</h2>
            </div> 
            <div class="third_img">
                <img class="cherta_two" src="img/cherta.png" alt="Ой, картинка не загрузилась..">
            </div>
        </div>
        <div class="main_part">
            <div class="first_punkt">
                <img src="img/laptop.png" alt="Ноут не загрузился.." class="laptop">
                <h3 class= "podzag_1">Веб-дизайн</h3>
                <span class= "span_1">Lorem ipsum dolor sit amet,<br> consectetur adipisicing elit.<br> Placeat, voluptatum.</span>
            </div>
            <div class="second_punkt">
                <img src="img/znak.png" alt="Тут должен был быть знак..">
                <h3 class= "podzag_2">Разработка</h3>
                <span>Lorem ipsum dolor sit amet,<br> consectetur adipisicing elit.<br> Sed, culpa!</span>
            </div>
            <div class="third_punkt">
                <img src="img/racket.png" alt="Тут должна была быть ракета..">
                <h3 class= "podzag_3">CEO-Оптимизация</h3>
                <span>Lorem ipsum dolor sit amet,<br> consectetur adipisicing elit.<br> Deserunt, dolor.</span>
            </div>
            <div class="forth_punkt">
                <img src="img/loud.png" alt="Тут должен был быть громкоговоритель..">
                <h3 class= "podzag_4">Маркетинг</h3>
                <span>Lorem ipsum dolor sit amet,<br> consectetur adipisicing elit.<br> Hic, accusantium.</span>
            </div>
            <div class="clear">
                
            </div>
        </div>
    </div>
    <div class="keys">
        <div class="keysi_header">
            <h2 class = "keysi">Кейсы</h2>
            <img src="img/cherta.png" alt="">
            <p class="keys_txt">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Soluta iusto iure iste qui nam magnam, nisi accusamus?</p>
        </div>
        <div class="opencloud">
            <img src="img/opencloud.jpg" alt="Тут должна быть картинка.." class="opencloud_img">   
        </div>
        <div class="block_one">
            <div class="first_part">
                <h3 class="client">CLIENT:</h3>
                <span>Какая-то компания</span>
            </div>
            <div class="second_part">
                <h3 class="website">WEBSITE:</h3>
                <span>http://www.somedornain.com</span>
            </div>
            <div class="third_part">
                <input type="submit" value="VISIT LIVE SITE" class="visit_live">
            </div>
        </div>
        <div class="block_two">
            <h3 class="pro_name">НАЗВАНИЕ ПРОЕКТА</h3>
            <span>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste earum repellat consequatur minus animi,<br> et harum provident odio nemo veniam, neque illo dolore! Nesciunt quo porro fugit in, quasi voluptate<br> distinctio officiis dolor, ipsam iure eum quia totam ducimus illum. Fuga aperiam reiciendis, iste perferendis?</span>
        </div>
        <div class="clear_two"></div>
    </div>
    <div class="cost">
        <div class="raschet">
            <h2>Расчет стоимости</h2>
        </div>
        <div class="real_input">
            <div class="site_type">
                <div class="text_part_one">
                    <h3>ТИП САЙТА</h3>
                </div>
                <div class="pict_part_one">
                   <select name="list1" id="list" class="select_one">
                       <option value="choose1">Выберите пункт</option>
                       <option value="opt1">Опция1</option>
                       <option value="opt2">Опция2</option>
                       <option value="opt3">Опция3</option>
                   </select>    
                </div>
            </div>
            <div class="site_design">
                <div class="text_part_two">
                    <h3>ДИЗАЙН</h3>
                </div>
                <div class="pict_part_two">
                    <select name="list2" id="list" class="select_two">
                        <option value="choose2">Выберите пункт</option>
                        <option value="opt4">Опция1</option>
                        <option value="opt5">Опция2</option>
                        <option value="opt6">Опция3</option>
                    </select>
                </div>
            </div>
            <div class="site_adapt">
                <div class="text_part_three">
                    <h3>АДАПТИВНОСТЬ</h3>
                </div>
                <div class="pict_part_three">
                    <select name="list3" id="list" class="select_three">
                        <option value="choose3">Выберите пункт</option>
                        <option value="opt7">Опция1</option>
                        <option value="opt8">Опция2</option>
                        <option value="opt9">Опция3</option>
                    </select>
                </div>
            </div>
        </div>
        <div class="real_srok">
            <span class="sroki">Сроки</span> <span style="font-size: 20px"><b>0</b></span>
        </div>
        <div class="real_cost">
            <span class="stoimost">Стоимость</span> <span style="font-size: 20px"><b>0</b></span>
        </div>
    </div>
    <div class="statistics">
            <div class="main_stat">
                <h2>Немного статистики</h2>
                <img src="img/cherta.png" alt="" class="cherta_3">
            </div>
    <div class="main_stat_part">
            <div class="first_stat">
                <img src="img/smile.png" alt="Тут должен был быть смайлик.." class="fst_stat_img">
                <h3 class="first_stat_h">120</h3>
                <span class="fst_stat_span">СЧАСТЛИВЫХ КЛИЕНТОВ</span>
            </div>
            <div class="second_stat">
                <img src="img/skobki.png" alt="Тут должны были быть скобки.." class="second_stat_img">
                <h3 class="second_stat_h">4,600</h3>
                <span class="second_stat_span">ЧАСОВ РАБОТЫ</span>
            </div>
            <div class="third_stat">
                <img src="img/galochka_new.png" alt="Тут должна была быть галочка.." class="third_stat_img">
                <h3 class="third_stat_h">340</h3>
                <span class="third_stat_span">ПРОЕКТОВ ЗАВЕРШЕНО</span>
            </div>
            <div class="forth_stat">
                <img src="img/cubok.png" alt="Тут должен был быть кубок" class="forth_stat_img">
                <h3 class="forth_stat_h">23</h3>
                <span class="forth_stat_span">НАГРАД ПОЛУЧЕНО</span>
            </div>
            <div class="clear_three">   
            </div>
        </div>
    </div>
    <div class="otzivi">
        <div class="main_otzivi">
            <h2 class="main_otzivi_h">ОТЗЫВЫ</h2>
            <img src="img/cherta.png" alt="" class="cherta_4">
        </div>
        <div class="example_otzivi">
            <div class="example_img">
                <img src="img/man_photo.png" alt="Тут должно было быть фото.." class="muzhik">
            </div>
            <div class="example_text_part">
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Obcaecati eaque sunt ex deserunt reprehenderit, quos ea<br> vero natus nostrum, amet nisi molestias voluptate ipsa veritatis quis nulla quibusdam quas porro cumque?</p>
                <p class="gen_director"><b>Михаил,</b> Ген директор ПАО "Газпром". </p>
            </div>
        </div>
        <div class="three_circles">
            <img src="img/main_orange.png" alt="Тут должен был быть кружок.." class="fst_orange">
            <img src="img/orange_copy.png" alt="Тут должен был быть кружок" class="second_orange">
            <img src="img/orange_copy.png" alt="Тут должен был быть кружок" class="third_orange">
        </div>
    </div>
    <div class="my_contacts">
        <div class="main_contacts">
            <h2>МОИ КОНТАКТЫ</h2>
            <img src="img/cherta.png" alt="" class="cherta_four">
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eum nemo amet, ut modi, quia fugit.</p>
        </div>
        <div class="three_punkts">
            <div class="perviy">
                <img src="img/geo.png" alt="Тут была картинка.." class="geo">
                <p>Санкт-Петербург<br>Невский проспект 11</p>
            </div>
            <div class="vtoroy">
                <img src="img/convert.png" alt="Тут была картинка.." class="convert">
                <p>info@companyname.com</p>
            </div>
            <div class="tretiy">
                <img src="img/telephone.png" alt="Тут была картинка.." class="telephone">
                <p>+7 999 999-99-99</p>
            </div>
            <div class="pustoy"></div>
        </div>
        <h2 class="leave_me_message">ОСТАВЬТЕ МНЕ СООБЩЕНИЕ</h2>
        <div class="leave_message">
           <div class="first_line">
                <div class="ur_name">
                    <input type="text" placeholder="Имя" class="input_name">
                </div>
                <div class="soap">
                    <input type="text" placeholder="Email" class="input_email">
                </div>
                <div class="clear_four"></div>
            </div>
            <div class="message">
<!--                <img src="img/your_message.png" alt="">-->
                <textarea name="name1" id="" cols="30" rows="10" placeholder="Сообщение" class="input_message"></textarea>
            </div>
            <div class="button">
                <input type="reset" value="Отправить" class="send_message">
            </div>
        </div>
        <div class="down_images">
            <div class="facebook">
                <img src="img/facebook.png" alt="Тут должна была быть запрещенная в России сеть..">
            </div>
            <div class="twitter">
                <img src="img/twitter.png" alt="Тут должна была быть запрещенная в России сеть..">
            </div>
            <div class="ball">
                <img src="img/ball.png" alt="Тут должен был быть мяч..">
            </div>
            <div class="cat">
                <img src="img/cat.png" alt="Тут должна была быть киса..">
            </div>
            <div class="instagram">
                <img src="img/instagram.png" alt="Тут должна была быть запрещенная в России сеть..">
            </div>
            <div class="in">
                <img src="img/inn.png" alt="Тут должна была быть картинка..">
            </div>
            <div class="clear_five"></div>
        </div>
    </div>
    <div class="map">
        <div class="fo_fun"></div>
        <input type="reset" value="I'M HERE" class="im_here">
    </div>
    <div class="footer">
        <p>Copyright@2021Михаил Рожков. Design by Web</p>
    </div>
</body>
</html>
