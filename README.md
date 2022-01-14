# Project1
var box;
function setup() {
  createCanvas(1600,1600);
box=createSprite(400, 400, 60, 60)
console.log(box)
}

function draw() 
{
  background("red");
  if(keyIsDown(RIGHT_ARROW)){
   background("cyan")
  }
drawSprites()

}




