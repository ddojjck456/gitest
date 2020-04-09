# gitest
for my test 2


# ~text 123~
        <!DOCTYPE html>
        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <meta http-equiv="X-UA-Compatible" content="ie=edge">
            <title>滿版作業-1</title>
            <link href="https://fonts.googleapis.com/css?family=Noto+Sans+TC&display=swap" rel="stylesheet">
            <style>
                *{
                    margin: 0px;
                    padding: 0px;
                    list-style: none;
                    font-family: 'Noto Sans TC', sans-serif;
                }
                .banner{
                    width: 100%;
                    height: 100vh;
                    background-color: #ccc;
                    background:
                        linear-gradient(115deg, #7bf 50%, transparent 50%) center center / 100% 100% ,
                        url(https://picsum.photos/1200/600) right center / auto 100% ;

                }
                .containter{
                    height: 100%;
                    width: 100%;
                    max-width: 1440px;
                    margin: auto;
                }
                .banner-txt{
                    height: 100%;
                    display: flex;
                    flex-direction: column; /* (讓文字由左至右從上到下) */
                    justify-content: center; /* (置中) */
                    align-items: flex-start; /* (讓原本是滿版的底線變成跟文字一樣的長度) */
                }
                .banner-txt h1{
                    font-size: 80px;
                    border-bottom: 1px solid #333;
                    font-weight: 900;
                    padding-bottom: .3em;
                    margin-bottom: .3em;
                }
                .banner-txt h1 small{
                    display: block;
                    font-size: 53px;
                    font-weight: 700;
                }
                .banner-txt h2{
                    font-size: 50px;
                    font-weight: 700;
                }
                .banner-txt p{
                    font-size: 20px;
                    font-weight: 300;
                }
            </style>
        </head>
        <body>

            <div class="banner">
                <div class="containter">
                    <div class="banner-txt">
                        <h1>金魚都能懂的
                            <small>
                                這個網頁畫面怎麼切
                            </small>
                        </h1>
                        <h2>圖文滿版區塊</h2>
                        <p>這畫面實在太常見，在各種樣板網頁可說是設計常客
                        <br>
                        金魚切不出來十時在說不過去阿</p>
                    </div>
                </div>
            </div>
        </body>
        </html>
