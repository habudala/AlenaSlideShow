### Created a slideshow at my aunt's request, so that she can keep track of her recovey

##### My aunt had a plastic surgery, and she asked me to create a slideshow for her, so that she could keep track of her recovery. (For obvious reasons I decided not to post the original slideshow with her pictures up here, but with random ones I found on my mac. but for you doubters, I did leave one image of her right after the surgery) Being a web developer, I decided to create a web page for her with an imageslider in it (instead of using s shitty PP slide or sg...) I've written the entire thing in vanilla JavaScript just to practice a little. I was curious how long it would take me... took about an hour, the majority of which was spent styling the page (couldn't settle on the shades of green I used for my gradients).

Some features I used:

###### -Bootstrap Responsive design so that the page would scale nicely (not that it needs it...)
	  
###### -Some CSS3 styling elements to make it more pleasing to the eye (arguably)

###### -SetInterval and clearInterval methods (just to practice a bit)

###### -For loop to get through my nodeColection object (pretty proud of it as it's my 
###### first time using DOM traversal tools instead of just generic getElementById/ClassName)

###### -"this" keyword practice (worked like a charm... Duh!)

###### - also, optimized the targeting of elements using the event object's target/srcElement property (instead ###### of the this keyword and ) so it would work in older versions of IE5 ++

###### I also implement a conditional statement to check if the browser supports the addEventListener method. In case it doesn't, I tell the code to run attachEvent() method (mostly for IE 5-8)