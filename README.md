# mineSweeper_CSS

{

    body{
       margin: 0;
    }
    
    
    .container_mother{
       display: grid;
       border: red 1px solid;
       height: 1080px;
       width: 100%;
       grid-template-rows: repeat(5, 216px);
       grid-template-columns: repeat(5, 20%);
    }
    
    
    .tab_right{
       display: flex;
       border: black 2px groove;
       flex-direction: column;
       justify-content: space-evenly;
       align-items: center;
       height: 100%;
       width: 100%;
       grid-row: 1 / 5;
       grid-column: 5 / 6;
       background-color: rgb(237, 255, 210);
    }
    
    .tabs_right{
       font-size: 36px;
       border: black 10px solid;
       height: 20%;
       width: 80%;
       text-align: center;
    }
    
    
    .tab_down{
       display: flex;
       border: black 2px groove;
       height: 100%;
       width: 100%;
       grid-row: 5 / 6;
       grid-column: 1 / 6;
       background-color: rgb(237, 255, 210);
    }
    
    
    .tab_left{
       align-content: center;
       justify-items: center;
       height: 100%;
       width: 100%;
       grid-row: 1 / 5;
       grid-column: 1 / 5;
       background-color: rgb(245, 255, 245);
    }
    
    
    .socialMedia_buttons{
       margin-top: 12px;
       margin-left: 12px;
       height: 100%;
       width: 324px;
       display: flex;
       gap: 24px;
    }
    
    .instagram_button_div{
       display: flex;
       border: black 1px solid;
       height: 60px;
       width: 150px;
       border-radius: 15px;
       cursor: pointer;
       box-shadow: 5px 5px 5px rgba(0, 0, 0, 0.2);
       transition: 0.2s;
    } .instagram_button_div:hover{
       background-color: rgb(0, 0, 0);
       color: rgb(255, 255, 255);
    } .instagram_button_div:active{
       background-color: rgba(0, 0, 0, 0.9);
       color: rgba(255, 255, 255, 0.8);
    }
    .instagram_button_leftDiv{
       position: relative;
       height: 100%;
       width: 40%;
    }
    .instagram_button_rightDiv{
       text-align: center;
       height: 100%;
       width: 60%;
    }
    .instagram_button_img1{
       position: absolute;
       margin-left: 10%;
       margin-top: 10%;
       height: 80%;
       width: 80%;
    }.instagram_button_img2{
       position: absolute;
       margin-left: 10%;
       margin-top: 10%;
       height: 80%;
       width: 80%;
    }
    .instagram_button_p{
       margin: 0;
       margin-top: 25%;
       font-size: 16px;
       font-family: sans-serif;
    }
    
    .youtube_button_div{
       display: flex;
       border: black 1px solid;
       height: 60px;
       width: 150px;
       border-radius: 15px;
       cursor: pointer;
       box-shadow: 5px 5px 5px rgba(0, 0, 0, 0.2);
       transition: 0.2s;
    } .youtube_button_div:hover{
       background-color: rgb(255, 0, 0);
       color: rgb(255, 255, 255);
    } .youtube_button_div:active{
       background-color: rgba(255, 0, 0, 0.8);
       color: rgba(255, 255, 255, 0.8);
    }
    .youtube_button_leftDiv{
       position: relative;
       height: 100%;
       width: 40%;
    }
    .youtube_button_rightDiv{
       text-align: center;
       height: 100%;
       width: 60%;
    }
    .youtube_button_img1{
       position: absolute;
       margin-left: 10%;
       margin-top: 10%;
       height: 80%;
       width: 80%;
    }.youtube_button_img2{
       position: absolute;
       margin-left: 10%;
       margin-top: 10%;
       height: 80%;
       width: 80%;
    }
    .youtube_button_p{
       margin: 0;
       margin-top: 25%;
       font-size: 16px;
       font-family: sans-serif;
    }
    
    
    .game_grid{
       display: grid;
       margin-left: -128px;
       margin-top: -48px;
       height: 80vh;
       width: 60vw;
       border: black 2px groove;
       grid-template-rows: repeat(20, 4vh);
       grid-template-columns: repeat(32, 1.875vw);
    }
    
    .bomb_img1{
       height: 0;
       width: 0;
    }

}
