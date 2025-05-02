# 13-2-More-form-processing-with-jQuery

## Video

[Video](https://youtu.be/DeEAsYwhVdY) <-- Make sure to watch this video first<br>

## Directions

### Step #1 - Process the form <br>
This webpage displays a form for ordering donuts We've already set up the basic form processing handler for you AND added images for a glazed, jelly and boston cream donut.
<br><br>
In this step, you're going to change the processing logic to get the value of the selected drop down item, and add a corresponding image to the body.
<br><br>
_Hint:_<br> 
`var $donutType = $(this).find("......"); `<br>
`var donutType = .....;`<br>
`var $img = $("...");`<br>
`$img.width(100);`<br>
`$img.attr("src", ....);`<br>
`$img.appendTo("body");`
<br><br>
### Step #2 - Extra - Add a *new* donut type <br>
_Do this step only if you have extra time_<br><br>
Add another donut type to the ordering system. 
