# igor-github
github/igor
function draw() {
  background("white");
  fill("black");
  textSize(64);
  textAlign(CENTER,CENTER);
  
  let maximo = width;
  let minimo = 1;
  //mouseX, 0, width ==> 0, palavra.length
  let palavra = "Caminhante";
  let quantidade = map(mouseX, 0, width, 1, palavra.length);
  //console.log(quantidade);
  let parcial = palavra.substring(0,quantidade);
  text(parcial,200,200);
  
  // if(mouseX <50) {
  // let palavra = "C";
  //text(palavra,200,200);
  //}else if (mouseX <100){
  //let palavra = "Ca";
  // text(palavra,200,200);
  //}else{
  //let palavra = "Caminhante";
  // text (palavra,200,200);
  //}
}function draw() {
  background("white");
  fill("black");
  textSize(64);
  textAlign(CENTER,CENTER);
  
  let maximo = width;
  let minimo = 1;
  //mouseX, 0, width ==> 0, palavra.length
  let palavra = "Caminhante";
  let quantidade = map(mouseX, 0, width, 1, palavra.length);
  //console.log(quantidade);
  let parcial = palavra.substring(0,quantidade);
  text(parcial,200,200);
}function draw() {
  inicializaCores();
  
  background("white");
  fill("black");
  textSize(64);
  textAlign(CENTER,CENTER);
  
  let maximo = width;
  let minimo = 1;
  //mouseX, 0, width ==> 0, palavra.length
  let palavra = "Caminhante";
  let quantidade = map(mouseX, 0, width, 1, palavra.length);
  //console.log(quantidade);
  let parcial = palavra.substring(0,quantidade);
  text(parcial,200,200);
}
