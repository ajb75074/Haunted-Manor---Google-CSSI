# Haunted-Manor---Google-CSSI
# Scavenger Hunt Horror Game 🎃🔍  

## Overview  
This game was developed during the **Google Computer Science Summer Institute (CSSI) 2022 Cohort** as a team project.  It’s a **scavenger hunt-style horror game** where players interact with objects and uncover clues. The game features dynamic audio, randomized elements, and eerie visual effects to enhance immersion.  

## 🎮 Features  
- **Interactive Gameplay** 🕵️‍♂️  
  - Players interact with objects to progress.  
  - Alerts and choices determine different paths.  
- **Dynamic Audio** 🎶  
  - Background and setting music adapt to player choices.  
  - Clicking objects triggers different sound effects.  
- **Randomized Clues** 🔄  
  - A shuffled array randomizes object order, ensuring varied experiences.  
- **Immersive Visuals** 🖼️  
  - Filtered and transformed images create a unique atmosphere.  
  - Objects appear/disappear using the `is-hidden` class.  
- **Custom Styling** 🎨  
  - CSS and [Bulma](https://bulma.io/) used for a clean, responsive UI.  

## 🛠️ Tech Stack  
- **JavaScript** (Game logic, object interactions, randomized elements)  
- **CSS/Bulma** (Styling, UI design, animations)  
- **HTML** (Base pages, displaying clues and dialogue)  

## 🖥️ Code Snippet  
Example of how images are filtered and transformed in CSS:  

```css
#clock {
  width: 200px;  
  height: auto;  
  position: fixed;
  top: 50%;
  left: 2%;
  filter: contrast(1.2) brightness(0.8) sepia(30%) opacity(80%);
  transform: scaleX(-1);
}
