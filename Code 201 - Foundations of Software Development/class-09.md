# Class 9
### HTML Forms Your first Web Form. How To Structure A Web Form.
1. Why are forms so important in web development?
  - Web forms are one of the main points of interaction between a user and a web site or application.
2. When designing a form, what are some key things to keep in mind when it comes to user experience?
  - it's important to remember that the bigger your form, the more you risk frustrating people and losing users. Keep it simple and stay focused: ask only for the data you absolutely need.
3. List 5 form elements and explain their importance.
  1. form = the actual form 
  2. fieldset = element is a convenient way to create groups of widgets that share the same purpose, for styling and semantic purposes.
  3. legend = element as if it is a part of the label of each control inside the corresponding <fieldset> element. 
  4. label = The <label> element is the formal way to define a label for an HTML form widget. This is the most important element if you want to build accessible forms — when implemented properly, screenreaders will speak a form element's label along with any related instructions, as well as it being useful for sighted users. Take this example, which we saw in the previous article:
  5. input = associated with labels but 

### Learn JS
### Introduction To Events.
1. How would you describe events to a non-technical friend?
  - Events are actions or occurrences that happen in the system you are programming, which the system tells you about so your code can react to them.
2. When using the addEventListener() method, what 2 arguments will you need to provide?
  - the name of the event and a function to handle the event. 
3. Describe the event object. Why is the target within the event object useful?
  - Sometimes, inside an event handler function, you'll see a parameter specified with a name such as event, evt, or e. This is called the event object, and it is automatically passed to event handlers to provide extra features and information. 

  Example: 
  const btn = document.querySelector('button');
function random(number) {
  return Math.floor(Math.random() * (number+1));
}
function bgChange(e) {
  const rndCol = `rgb(${random(255)}, ${random(255)}, ${random(255)})`;
  e.target.style.backgroundColor = rndCol;
  console.log(e);
}
btn.addEventListener('click', bgChange);

4. What is the difference between event bubbling and event capturing?
  - Event bubbling and capture are terms that describe phases in how the browser handles events targeted at nested elements.

#### Bookmark and Review
HTML5 Input Types
https://developer.mozilla.org/en-US/docs/Web/Events