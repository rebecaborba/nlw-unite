# JavaScript

//variaveis
const mensagem = "Oi, tudo bem?"
//tipos de dados
  //number
  //string
//funcao
alert (mensagem)

const participante = {
  nome: "Mayk Brito",
  email: "mayk@gmail.com",
  dataIncricao: new date (2024, 2, 22, 19, 20),
  dataCheckIn: new date (2024, 2, 25, 22, 00)
}

let participantes = [
  {
    nome: "Mayk Brito",
    email: "mayk@gmail.com",
    dataIncricao: new date (2024, 2, 22, 19, 20),
    dataCheckIn: new date (2024, 2, 25, 22, 00)
  }, 
]

fo(let participante of participantes) {
  //faça alguma coisa aqui
  //enquanto tiver participantes nesta lista 
}