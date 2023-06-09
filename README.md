# JavaScript Tutorial
JavaScript is world's most popular programing language.    
JavaScript is the programing language of the Web.    
JavaScript is easy to learn.    
This tutorial will teach you JavaScript from basic to advanced

# Why Study JavaScript?
JavaScript is one of the 3 languages all web developer must learn:

1. __HTML__ to define the content of web pages   
2. __CSS__ to specify the layout of web pages   
3. __JavaScript__ to program the behavior of web pages   


# JavaScript Introduction  
This page contains some example of what JavaScript can do.

## JavaScript Can Change HTML Content
One of many JavaScript HTML methods is `getElementById()`.  

The example below "finds" an HTML element (with id="demo"), and changes the element content (innerHTML) to "Hello JavaScript"

### Example
```javascript
document.getElementById("demo").innerHTML = "Hello JavaScript"
```

```HTML
    <p id="demo">JavaScript can change HTML content.</p>
    <button type="button" onclick='document.getElementById("demo").innerHTML = "Hello JavaScript!"'>Click Me!</button>
```

One click on the button(Click Me!) it will change id demo text from "JavaScript can change HTML content." to "llo JavaScript!". 



