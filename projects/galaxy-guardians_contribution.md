---
layout: project
title: Galaxy Guardians
permalink: projects/galaxy-guardians/contribution
---

<div class="ui three item menu">
  <a href="/projects/galaxy-guardians/overview" class="item">Overview</a>
  <a href="/projects/galaxy-guardians/contribution" class="active item">Contribution</a>
  <a href="/projects/galaxy-guardians/outcome" class="item">Outcome</a>
</div>

<h2>Contribution to the Project</h2>

<img class="ui centered rounded image" src="/images/galaxy-guardians/contribution.png">

<h4>Scripts and Control</h4>
<p>
For this project, my main focus was coding the classes and functions that controlled the players and enemies. The first task that I completed was creating all of the controls for the player to move and shoot. For the various enemies, all of the different enemy classes were created using inheritance. I took this approach because all the different enemies shared specific fields. By creating a parent class with these parameters, I would just create each unique enemy as a child class to the parent. As child classes, I was able to give each child class properties that would make it behave differently from one another, such as different movement patterns. To make the enemies shoot, I created functions in the parent class that would create an object that represented an enemy's attack and gave that object movement. Both my partner and I had agreed that this approach was the best solution to give enemies attacks. If we had created separate classesoutside of the parent class, it would be difficult utilize the attack functions in relation to the several enemies on-screen. After working out all the kinks for the player and enemy to attack each other correctly, I moved on to create the scripted enemy pattern. Just like was mentioned in the <a href="/projects/galaxy-guardians/overview" class="item">overview</a>, each stage of a Bullet Hell game has its enemies spawn exactly the same everytime the stage is repeated. As a result, I could not just randomly generate enemies; I had to pick and choose which enemies go where, shoot when, and shoot how. I accompished this by creating a class specifically for the order of the enemies' spawn. After this repetitive process, we were able to consider the game completed. 
</p>

<h4>Assisting my Team</h4>
<p>
My partner for this project was responsible for a lot of the code and creation pertaining to the appearance and ambiance of our game. However, creatign unique shapes or textures by hand in Unity can be difficult to impossible. To move this part of the project forward, we both spent some time to search for ways to create visuals easily and quickly so that we could complete the game by the deadline. After my partner had created the base objects for our game, we both sat down to browse the available textures on the Unity Assest store. Creating the multiple file for unique textures were outside of our skillset, so the best way to get textures and colors for our game were to use the free assests that other Unity developers had provided for the community. Lastly, the scrolling background and other visuals needed to be implemented in code. Although my partner did most of the coding for this aspect of the game, I offered suggestions and assistance to keep the workflow going as we began to reach the deadline of the project.
</p>

<p>
The GitHub repo can be found <a href="https://github.com/look-n-cook/Look-n-Cook">here</a>.
</p>
