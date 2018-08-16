# Exercise to select and modify elements using jQuery

Use the provided HTML file and complete the following:
  
### Use jQuery to give the elements their desired features

```
    <div class='red'>I should be red!</div>
    <div class='red'>I should be red too!</div>
    <div id="myElement">I should be blue! When you click on me, I want you to invoke a function 
    that uses alert() to display the message "myElement was clicked!"
        <div>I want my background to be green and my text white!</div>
        <div>I want my background to be orange and my text black!</div>
    </div>
    <div class='red'>Red please!</div>
```
### Wire up the buttons as requested in the code

```
    <!-- The 4 buttons below should have their text display 'strong' and have a 2px blue border 
    when hovered over with the mouse -->
    <!-- The 4 buttons below should perform the actions specified by their text -->
    <div class="hazBtns">
        <button id="btnFade">Fade Images</button>
        <button id="btnUnfade">UnFade Images</button>
        <button id="btnSlideDn">Slide Images Down</button>
        <button id="btnSlideUp">Slide Images Up</button>
    </div>
```
#### Tips:
* Create CSS selectors in the HTML as needed for style requests
* Use the jQuery function toggleClass() to add/remove styles
* Use the jQuery on() event handler function for button clicks and other events
* Use the jQuery effects fanctions fadeToggle() and slideToggle() to apply effects to images 
* Check the jQuery documentation and/or your text book for additional details

### Bonus:
* Try some of the other effects such as animate()
