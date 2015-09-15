 TIY-Assingments
  
 **ASSIGNMENT 07  
 ** READING JavaScript: Events**
  * [ ] How does an `Event` "bubble"? Can I make it stop?
  There actually a couple of things happening here depending. There is something called "Capturing" and it is when the outer
  most element is fired and responds to whatever has been triggered regardless of its position.
  The Bubble response happens like this: when an even listener responds to a triggered event it responds from the inner most
  element to the outer most element in its response.  There is no real upside to either method in particular although certain
  versions of IE 9 and under, Capturing was the main method used 
  an onclick happens when the user clicks an item and can respond as the page is opening.
  an onload is when the element can only be accessed or triggered by the user clicking AFTER
  the page has completely loaded.
  
  * [ ] What does the `target` property of an `Event` refer to?
  the target event property returns the element that triggered the event.It is referring to the actual event that is triggered
  during the action performed. refers to the internal firing process of an event and its trigger


  * [ ] Besides `click`, what _other_ event types can I trigger with my mouse?
  , mouse events would be like onkeypressonclick, onmousemove, onmouseup, 
  form event examples would be onblur onchange onfocusin etc.
  
  * [ ] What types of events can be triggered on a `<form>` element?
  submission of filled field
  <form> events examples are onblur onchange onreset onselect onsubmit
  
  
  * [ ] `click` me, baby, one more time!
  a mouse action which can trigger any number of events . some actions must be "double clicked" or "right clicked"
  etc. depending on the OS and the model and capabilities of the mouse
  and many of the mouse events can invove a click or double click
 
  
  * [ ] `scroll` down the avenue 
  the scroll is a feature that allows the user to navigate through options or a list  or whatever it may be,
  by scrolling the page using the mouse dial, or wheel
 
 
   * [ ] `change` is a-comin' changes 
 could be referring to the Hash
 or in frame objects it is onhashchange-when and event occurs after changes to the anchor part of a URL(?)
 // I need to have this explained
 onchange	The event occurs when the content of a form element, the selection, or the checked state have 
 changed (for <input>, <keygen>, <select>, and <textarea>)
	 ref:http://www.w3schools.com/jsref/dom_obj_event.asp
 
   * [ ] `submit` to mah authah-ri-tah!
  this a way of triggering an event by its very action of entering the info into the provided blank field.
 onsubmit is example this event occurs when a form is submitted like in the responsive column
 
    * [ ] this is a complete `load`...
   onloaddata onloadeddate onloadstart
frame object load example would be like onload in which the event occurs when an object has loaded 
 
  * [ ] well, just `unload` about it.
onbeforeunload this is when the event occurs before the document is about to be loaded
**READING JavaScript: Events**

*How does an Event "bubble"? Can I make it stop?* this was brought into existence to deal 
with the ability of multiple actions to trigger the same event so two or more event handlers
it is the opposite of capturing
bubbling:he event is first captured and handled by the innermost element and then propagated to outer elements.
capturing, the event is first captured by the outermost element and propagated to the inner elements.


*
ref:http://stackoverflow.com/questions/4616694/what-is-event-bubbling-and-capturing











More Questions
Homework Assignments
**What interactive elements exist?** 
the feature basically opens like an accordion, thus its name, and reveals (n) number of 
features as a subset to the default display

**How do you interacts with them?** 
clicks, could be a mouse rollover or

**What visual effects are produced by interacting?** 
the accordion expands
**How does it do it?**

**What existing HTML elements are changed?**

**What new HTML elements are created?**

**What CSS styles are used to produce the effect?**

**_View Mode Switch_**it allows basic switching of views like rollover menu items creating a small pop up box. 
this is considered to be at entity level

**What does it do?**
it creates new options on the user end in the form of alternate viewpoints of popuated elements
**What interactive elements exist?**
 there is toggle action of a graphically renderred button of some sort that when
 clicked by the user, offers an alternate orginizational view of the 
 items populating the page
 ;it creates new options on the user end

**How do you interact with them?**
rollovers and clicks, submits 

**What visual effects are produced by interacting?**
 the pop up box of some sort
 a change in view for the view switch. example: button in corner
 that when toggled presents the user with an alternate view of the elements populating 
 the page

**How does it do it?**

**What existing HTML elements are changed?**

**What new HTML elements are created?**

**What CSS styles are used to produce the effect?**

**Responsive Multi-Column Form**
this is basically a two or more columned blueprint for the document object 
model and an example would be a submittal form for instance

**What does it do?**

**What interactive elements exist? **
rollovers, clicks, tabs work

**How do you interact with them?**
 clicks rollover prompts

**What visual effects are produced by interacting?**
 The fields are populated with the info that the user inputs.

**How does it do it?**

**What existing HTML elements are changed?**

**What new HTML elements are created?**

**What CSS styles are used to produce the effect?**

 CSS columns which can be applied really to any element. 
 I need to confirm but I think you can use nests two multi-responsive columns inside one another
