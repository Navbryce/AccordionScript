# AccordionScript
A small script to create an accordion effect. It's useful for FAQ sections and other question and answer formats.

# Dependencies
- Jquery
- Font awesome (the snippet can be easily manipulated to remove this dependency)

# Installationa nd Use
Put the JavaScript snippet somewhere on your website or in its own independent JavaScript file and link it to the page.

Follow the format with as many Divs/Sections as needed:
```
  <div class="faq">
    <div class="question">
      <h4>How do I apply for board? <span class="fa fa-chevron-down"></span></h4>
    </div>
    <div class="answer">
      <p>Answer</p>
    </div>
  </div>
```
Note: Do not change the classes parent/child hierarchy
