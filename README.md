# z5.4
<html>
    <head>
        <style>
            body {
                font-family: Arial, sans-serif;
                margin: 0;
                padding: 0;
            }
            
            .container {
                width: 870px;
                margin: 0 auto;
            }
            
            .main-info {
                float: left;
                width: 400px;
            }
            
            .advertisement {
                float: right;
                width: 350px;
                margin-top: 90px;
                padding: 30px;
                border: 2px dotted navy;
            }
            
            .reviews {
                width: 870px;
                float: left;
                margin-left: 30px;
                clear: both;
                margin-top: 20px;
            }
            
            .review {
                border-left: 10px double navy;
                width: 350px;
                padding-left: 10px;
                margin-bottom: 20px;
                position: relative;
            }
            
            .reviewer-name {
                color: firebrick;
                display: inline-block;
                margin-bottom: 5px;
                padding-left: 40px;
                position: relative;
            }

            .reviewer-name span {
                border-bottom: 1px dotted firebrick;
                padding-bottom: 2px;
            }

            .reviewer-name::before {
                content: "";
                display: inline-block;
                width: 30px;
                height: 30px;
                background-image: url('https://i.pinimg.com/736x/50/96/24/509624878021153b6916ac6d75f5dde3.jpg');
                background-size: contain;
                position: absolute;
                left: 0;
                top: 50%;
                transform: translateY(-50%);
            }
            
            .main-info h1 {
                color: purple
            }
            
            .main-info h2 {
                color: indigo;
                font-size: 20px;
            }
            
            .main-info p {
                font-size: 20px;
            }
            
            .advertisement h2 {
                color: indigo;
            }
            
            .review::after {
                content: "";
                display: block;
                width: 30px;
                height: 35px;
                background-image: url('https://i.pinimg.com/originals/d8/54/71/d854718a02ae8764a631f377001ce7ec.png');
                background-size: contain;
                background-repeat: no-repeat;
                margin-top: 10px;
                margin-right: 20px;
            }

            .review::after:hover {
                border-bottom: 3px dotted goldenrod;
                cursor: pointer;
            }
        </style>
    </head>
    <body>
        <div class="container">
            <section class="main-info">
                <h1>Зоопарк редких животных</h1>
                <h2>Более 150 видов</h2>
                <p>Вы увидите крупных диких представителей живой природы, а также редких птиц, змей и многое другое!</p>
                <img src="https://pic.rutubelist.ru/video/2025-01-26/6c/5e/6c5ef38c2d9612a1b89d454b5577d795.jpg" width="400">
            </section>
            
            <div class="advertisement">
                <h2>Внимание! Специальное предложение от партнёра!</h2>
                <p><a href="">Щенки хаски</a> от заводчика со всеми документами</p>
                <img src="https://avatars.mds.yandex.net/i?id=6dbb64ea7294dcc3744729606e8f6940bd230879-12802892-images-thumbs&n=13" width="150">
                <img src="https://avatars.mds.yandex.net/i?id=9e444362538ec9f48d4d157bcb6071a7_l-4835468-images-thumbs&n=13" width="150">
            </div>
            
            <div class="reviews">
                <div class="review">
                    <div class="reviewer-name"><span>Олег</span></div>
                    <p>Были в серпентарии. Ребёнок в восторге!</p>
                </div>
                
                <div class="review">
                    <div class="reviewer-name"><span>Наталья</span></div>
                    <p>Спасибо за экскурсию! Очень интересно!</p>
                </div>
                
                <div class="review">
                    <div class="reviewer-name"><span>Анна</span></div>
                    <p>Так и не попали к птицам. жаль… Однако, остальное очень здорово!</p>
                </div>
            </div>
        </div>
    </body>
</html>
