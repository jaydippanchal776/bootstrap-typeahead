# bootstrap-typeahead
Bootstrap Typeahead is used for autosuggestion list based on type text in input. 

I have customized this js and added more function, so that you can easily used this for multi purpose.

# Example 1 - Li color based on condition

To change color of list element based on search content. I have added colour attribute for this. 

    $('#typeahead').typeahead({

        colour: "colourCondition"

    });

Here coloutCondition is javascript function

      function colourCondition(item, i) {

           if (item.type == 3) {

                i.addClass("color-brown");
    
           }
   
      }

Source from : http://www.codewithgeek.com/category/bootstrap/typeahead/
