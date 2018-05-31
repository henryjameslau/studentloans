# ONS-slider-UI

Adapted from ONS dvc 404. Set the limits of the slider, starting value in the `index.html`.  

`<input id="ex8" data-slider-id='ex1Slider' type="text" data-slider-min="340" data-slider-max="1710" data-slider-step="1" data-slider-value="1000"/>`

The ticks marks are listed below.

`<div class="zero"><p class="tick-one">£340</p></div>
       <div class="one-hundred"><p class="tick-two">£1710</p></div>`

The £ sign on the slider is set in the CSS

`.tooltip-inner::before {
   content: "£";
   }`
   
Get the value of the slider form `guess_value`
