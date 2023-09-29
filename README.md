@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@500&display=swap');

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

body{
    width: 100%;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background: linear-gradient(45deg, #0a0a0a, #101111);
}

.calculator{
    border: 1px solid #bad62d;
    padding: 20px;
    border-radius: 16px;
    background: transparent;
    box-shadow: 0px 3px 15px rgba(119, 119, 113, 0.5);

}

input{
    width: 320px;
    border: none;
    padding: 24px;
    margin: 10px;
    background: transparent;
    box-shadow: 0px 3px 15px rgbs(84, 84, 84, 0.1);
    font-size: 40px;
    text-align: right;
    cursor: pointer;
    color: #ffffff;
}

input::placeholder{
    color: #ffffff;
}

button{
    border: none;
    width: 60px;
    height: 60px;
    margin: 10px;
    border-radius: 50%;
    background: #d69347;
    color: #161414;
    font-size: 20px;
    box-shadow: -8px -8px 15px rgba(255, 255, 255, 0.1);
    cursor: pointer;
}

.equalBtn{
    background-color: #d7860c;
}

.operator{
    color: #161112;
}
