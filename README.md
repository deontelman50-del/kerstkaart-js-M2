[kerstkaart.js](https://github.com/user-attachments/files/24186667/kerstkaart.js)# kerstkaart-js-M2

[Uploconst canvas = document.getElementById("canvas");
const g = canvas.getContext("2d");


//de boom
g.beginPath();
g.strokeStyle = "green";

g.moveTo(400, 220);
g.lineTo(150, 350);
g.lineTo(650, 350);
g.lineTo(400, 220);
g.fillStyle = "green";
g.fill();

g.moveTo(250, 350);
g.lineTo(100, 450);
g.lineTo(700, 450);
g.lineTo(550, 350);
g.lineTo(250, 350);
g.fillStyle = "green";
g.fill();

g.moveTo(200, 450);
g.lineTo(50, 550);
g.lineTo(750, 550);
g.lineTo(600, 450)
g.lineTo(200, 450);
g.fillStyle = "green";
g.fill();

g.moveTo(150, 550);
g.lineTo(0, 700);
g.lineTo(800, 700);
g.lineTo(650, 550);
g.lineTo(150, 550);
g.fillStyle = "green";
g.fill();

g.stroke();


//de ster van de kerst boom       
//drie hoek 1

g.beginPath();
g.strokeStyle = "yellow";
g.moveTo(400, 0);
g.lineTo(450, 90);
g.moveTo(400, 0);
g.lineTo(350, 90);
g.lineTo(450, 90);
//drie hoek 2
g.moveTo(540, 130);
g.lineTo(450, 90);
g.moveTo(540, 130);
g.lineTo(450, 170);
g.lineTo(450, 90);
//drie hoek 3
g.moveTo(400, 260);
g.lineTo(450, 170);
g.moveTo(400, 260);
g.lineTo(350, 170);
g.lineTo(450, 170);
//drie hoek 4
g.moveTo(260, 130);
g.lineTo(350, 170);
g.moveTo(260, 130);
g.lineTo(350, 90);
g.lineTo(350, 170);
//vierkant
g.moveTo(450, 90);
g.lineTo(450, 170);
g.lineTo(350, 170);
g.lineTo(350, 90);

g.fillStyle = "yellow";
g.fill();
g.stroke();


//de stam
g.beginPath();
g.strokeStyle = "brown";

g.moveTo(300, 700);
g.lineTo(300, 900);
g.lineTo(500, 900);
g.lineTo(500, 700);

g.fillStyle = "brown";
g.fill();


g.stroke();


//kerstballen
g.beginPath();
function Ball(xPos, yPos, size, color) {
       g.strokeStyle = color;
       g.fillStyle = color;
       g.beginPath();
       g.arc(xPos, yPos, size, 0, 20 * Math.PI);
       g.closePath();
       g.fill();
       g.stroke();
}

Ball(250, 340, 40, "red");
Ball(550, 400, 40, "blue");
Ball(340, 420, 40, "yellow");
Ball(450, 350, 40, "gold");
Ball(590, 510, 40, "silver");
Ball(465, 530, 40, "darkGreen");
Ball(350, 600, 40, "darkBlue");
Ball(220, 650, 40, "orange");

//huisjes
function huis(x, y){

g.beginPath();
g.moveTo(x+225, y+925);
g.lineTo(x+325, y+925);
g.lineTo(x+325, y+770);
g.lineTo(x+315, y+770);
g.lineTo(x+315, y+760);
g.lineTo(x+305, y+760);
g.lineTo(x+305, y+750);
let radius = 30;
g.arc(x+305-radius, y+750, radius, 0, Math.PI, true);
g.moveTo(x+225, y+925);
g.lineTo(x+225, y+770);
g.lineTo(x+235, y+770);
g.lineTo(x+235, y+760);
g.lineTo(x+245, y+760);
g.lineTo(x+245, y+750);
g.fillStyle = "red";
g.fill();
g.stroke();

}

huis(0,0);
huis(200,50);
huis(-200,40);
huis(400,30);
ading kerstkaart.js…]()
