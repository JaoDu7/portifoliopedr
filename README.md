# portifoliopedro

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, sans-serif;
}

body {
  background-color: #f5f5f5;
  color: #333;
  line-height: 1.6;
}

header {
  background-color: #2c3e50;
  color: white;
  text-align: center;
  padding: 40px 20px;
}

header h1 {
  font-size: 2.5em;
}

.sobre, .galeria, .contato {
  padding: 40px 20px;
  max-width: 1000px;
  margin: auto;
}

.galeria .fotos {
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
  margin-top: 20px;
}

.imagem {
  width: 45%;
  margin-bottom: 20px;
}

.imagem img {
  width: 100%;
  border-radius: 10px;
  box-shadow: 0px 4px 10px rgba(0,0,0,0.2);
}

h2 {
  margin-bottom: 20px;
  color: #2c3e50;
}

.contato a {
  color: #2980b9;
  text-decoration: none;
}

footer {
  text-align: center;
  padding: 20px;
  background-color: #2c3e50;
  color: white;
  margin-top: 40px;
}