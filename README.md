function setup() {
  createCanvas(400, 400);
  background("rgb(255,206,206)");
}

function draw() {
  stroke("rgb(237,237,255)");
  fill("rgb(22,20,20)");

  // console.log(mouseIsPressed)

  if (mouseIsPressed) {
    rect(mouseX, mouseY, 20, 35);
  }
}
