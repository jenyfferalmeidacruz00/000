* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    color: white;
}

body {
    background: linear-gradient(#1354A5 0%, #041832 33.33%, #041832 66.67%, #01080E 100%);
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
}


body::before {
    background-image: url("img/code.png");
    background-repeat: no-repeat;
    background-position: right;
    content: "";
    display: block;
    position: absolute;
    width: 100%;
    height: 100%;
    opacity: 0.4;
}

.container {
    width: 1200px;
    height: 600px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    border-radius: 24px;
    border: 1px solid #1875E8;
    box-shadow: 4px 4px 20px 0px rgba(1, 8, 14, 0.15);
    background-image: url("img/Ruido.png");
    background-size: 100% 100%;
    position: relative;
}

.container__conteudo {
    display: flex;
    align-items: center;
    position: absolute;
    bottom: 0;
}

.container__informacoes {
    flex: 1;
    padding: 20px;
}

.container__botao {
    border-radius: 16px;
    background: #1875E8;
    padding: 16px 24px;
    width: 100%;
    font-size: 24px;
    font-weight: 700;
    border: none;
    margin-top: 16px;
}

.container__texto {
    margin: 16px 0 16px 0;
}

.container__texto-azul {
    color: #1875E8;
}

h1 {
    font-family: 'Chakra Petch', sans-serif;
    font-size: 72px;
}

h2,
p,
button {
    font-family: 'Inter', sans-serif;
}

h2 {
    font-size: 32px;
    font-weight: 400;
}
