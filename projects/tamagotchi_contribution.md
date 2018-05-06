---
layout: project
title: Tamagotchi
permalink: projects/tamagotchi/contribution
---

<div class="ui three item menu">
  <a href="/projects/tamagotchi/overview" class="item">Overview</a>
  <a href="/projects/tamagotchi/contribution" class="active item">Contribution</a>
  <a href="/projects/tamagotchi/outcome" class="item">Outcome</a>
</div>

<h2>Contribution to the Project</h2>
<p>
For this project, my group of three members made a simplified version of this game. For instance, our game's "clock" changes with each action the player takes rather than with real-time. Additionally, the time that needs to pass for the pet to grow up is much shorter. We separated the work load into the following sections: created the classes to manage the tamagotchi, creating the display and user interface, and creating a main function that calls the functions and manipulates the data from the other two section. My main contribution for this project was designing the display and user interface. We decided that it would be best to create the dispay using ASCII rather than a GUI interface like ncurses. To have better control over the display, we split it into different sections. These sections were: titleblock, dialogue, character, and user interface. The titleblock only displays the "Tamagotchi" title and never really changes, but we separated it from the dialogue display because there are times when we show or hide the dialogue box. The dialogue display was made by using three arrays of a set length. It is initialized to all spaces so that we can display a blank dialogue box, and the cells is changed  to display messages to the player. Alternatively, that section can be replaced by a blank with just the borders of the display showing. The character display changes between different ASCII pictures that represent the age progression of the pet. There is also a display to turn off the lights in the pet's room to make the display mostly blank. The user interface display shows all the actions that user do, and can be replaced by an alternative display that shows the information (happiness, hunger, age, etc.) of the pet.
</p>

<center>
<div class="ui small rounded images">
    <img class="ui image" src="/images/tamagotchi/tamagotchi_egg.png">
    <img class="ui image" src="/images/tamagotchi/tamagotchi_baby.png">
    <img class="ui image" src="/images/tamagotchi/tamagotchi_kid.png">
    <img class="ui image" src="/images/tamagotchi/tamagotchi_teen.png">
</div
<div class="ui small rounded images">
  <img class="ui image" src="/images/tamagotchi/tamagotchi_adult.png">
  <img class="ui image" src="/images/tamagotchi/tamagotchi_parent.png">
  <img class="ui image" src="/images/tamagotchi/tamagotchi_lights.png">
  <img class="ui image" src="/images/tamagotchi/tamagotchi_grave.png">
</div>
</center>