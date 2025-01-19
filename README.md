# MART220Collaboration
 This is how we share, Creative Coding 2 (MART220) course


I asked ChatGPT, "what is your favorite dish?"

ChatGPT said:


"As an AI, I don't eat food or have personal preferences, but I can describe a fun and visually appealing dish to create in p5.js! Let's go with a bowl of ramen—a vibrant and colorful dish with lots of elements that can be represented using simple shapes."

here is the code it gave me for Ramen

Ramen Dish Representation in p5.js

Here’s how I’d "draw" a bowl of ramen:

function setup() {
  createCanvas(400, 400);
  background(220);

  // Bowl base
  fill(200, 200, 255); // Light blue
  arc(200, 300, 300, 150, PI, TWO_PI, OPEN);

  // Noodles
  stroke(255, 204, 153); // Light beige
  strokeWeight(3);
  for (let i = 110; i <= 290; i += 10) {
    line(i, 240, i + 10, 250);
  }

  // Egg
  fill(255, 255, 200); // Pale yellow
  noStroke();
  ellipse(250, 220, 50, 35);

  fill(255, 153, 102); // Orange yolk
  ellipse(250, 220, 20, 20);

  // Seaweed
  fill(50, 100, 50); // Dark green
  rect(140, 200, 20, 50);

  // Green onion
  fill(102, 255, 102); // Light green
  ellipse(180, 230, 10, 10);
  ellipse(190, 240, 10, 10);
  ellipse(200, 230, 10, 10);

  // Chopsticks
  stroke(153, 102, 51); // Light brown
  strokeWeight(5);
  line(100, 150, 180, 250);
  line(120, 140, 200, 240);
}

What This Represents

    Bowl: A light blue arc at the bottom of the canvas.
    Noodles: Curvy yellow lines drawn with strokes.
    Egg: A pale oval with an orange yolk.
    Seaweed: A dark green rectangle.
    Green Onion: Light green circles scattered near the noodles.
    Chopsticks: Two diagonal brown lines above the bowl.


    In comparision to my Pizza Sketch vs Chat GPT, mine is pretty basic. Chat used some coding I don't remember like the use of i+=10 and the let = stuff I will have to refresh my memory.  Also do not remember what this is arc(200, 300, 300, 150, PI, TWO_PI, OPEN);
but I will ask GPT to explain ! 


Michael Howell