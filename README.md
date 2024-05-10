// Código omitido

posicaoHorizontal++
// Código omitido

posicaoHorizontal+= 2
// Código omitido

posicaoHorizontal+= random(0, 3)
// Código omitido

posicaoVertical+= random(-3, 3)
// Código omitido

function setup() {

    createCanvas(400, 400);
    background(color(100, 0, 0));
    cor = "color(random(0, 255), random(0, 255), random(0,255))";
    posicaoHorizontal = 0;
    posicaoHorizontal = 200;
    }
    
let cor;
let posicaoHorizontal;
let posicaoVertical; 

let posicaoHorizontal2;
let posicaoVertical2;

// Código omitido
// Código omitido

function setup() {

    createCanvas(400, 400);
    background(color(100, 0, 0));
    cor = "color(random(0, 255), random(0, 255), random(0,255))";
    posicaoHorizontal = 0;
    posicaoVertical = random(height);
    posicaoHorizontal2 = 0;
    posicaoVertical2 = random(height);
    }
    
// Código omitido

function draw() {
    fill(cor);
    circle(posicaoHorizontal, posicaoVertical, 50);
    circle(posicaoHorizontal, posicaoVertical, 50);
    
    posicaoHorizontal+= random(0, 3);
    posicaoVertical+= random(-3, 3);
    posicaoHorizontal2+= random(0, 3);
    posicaoVertical2+= random(-3, 3);
let cor;
let circuloX;
let circuloY;

// Código omitido
// Código omitido

function setup() {

    createCanvas(400, 400);
    background(color(100, 0, 0));
    cor = "color(random(0, 255), random(0, 255), random(0,255))";
    circuloX = [0, 0];
    circuloY = [random(height), random (height)];
    }
    
// Código omitido

function draw() {
    fill(cor);
    circle(circuloX[0]), circuloY[0], 50);
    circle(circuloX[1]), circuloY[1], 50);
// Código omitido

circuloX[0] += random(0, 3);
circuloY[0] += random(-3, 3);

circuloX[1] += random(0, 3);
circuloY[1] += random(-3, 3);
let cor;
let circuloX;
let circuloY;

function setup() {

    createCanvas(400, 400);
    background(color(100, 0, 0));
    cor = "color(random(0, 255), random(0, 255), random(0,255))";
    circuloX = [0, 0, 0];
    circuloY = [random(height), random (height), random (height)]
    
function draw() {

    fill(cor);
    circle(circuloX[0]), circuloY[0], 50);
    circle(circuloX[1]), circuloY[1], 50);
    circle(circuloX[2]), circuloY[1], 50);
    
    circuloX[0] += random(0, 3);
    circuloY[0] += random(-3, 3);
    
    circuloX[1] += random(0, 3);
    circuloY[1] += random(-3, 3);
    
    circuloX[2] += random(0, 3);
    circuloY[2] += random(-3, 3);
    
    if(mouseIsPressed) {
        cor = color(random(0, 255), random(0, 255), random(0,255), random(0, 100))";
    }
}
// Código omitido

function draw() {

    fill(cor);
    
    // console.log(circuloX length);
    for(let dedo in circuloX) {
        console.log(dedo);
}
// Código omitido

function draw() {

    fill(cor);
    
    // console.log(circuloX length);
    for(let contador in circuloX) {
        console.log(contador);
}
// Código omitido

function draw() {

    fill(cor);
    
    // console.log(circuloX length);
    for(let contador in circuloX) {
        console.log(contador);
        circle(circuloX[contador], circuloY[contador], 50);
}
// Código omitido

function draw() {

    fill(cor);
    
    // console.log(circuloX length);
    for(let contador in circuloX) {
        console.log(contador);
        circle(circuloX[contador], circuloY[contador], 50);
        circuloX[contador] += random(0, 3);
        circuloY[contador] += random(-3, 3);
}
// Código omitido

    if(circuloX[contador]>= width) {
        circuloX[contador] = 0;
    }
let cor;
let circuloX;
let circuloY;

function setup() {
  createCanvas(400, 400);
  background(color(100, 0, 0));
  cor = "color(random(0, 255), random(0, 255), random(0,255))";
  circuloX = [0, 0, 0];
  circuloY = [random(height), random(height), random(height)];
}
function draw() {
  fill(cor);

  // console.log(circuloX length);
  for (let contador in circuloX) {
    console.log(contador);
    circle(circuloX[contador], circuloY[contador], 50);
    circuloX[contador] += random(0, 3);
    circuloY[contador] += random(-3, 3);

    if (circuloX[contador] >= width) {
      circuloX[contador] = 0;
      circuloY[contador] = random(height);
    }
  }

  if (mouseIsPressed) {
    cor = color(random(0, 255), random(0, 255), random(0, 255), random(0, 100));
  }
}
