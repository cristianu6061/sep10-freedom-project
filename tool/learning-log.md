# Tool Learning Log

## Tool: **W3Schools Flexbox **

---

### 3/16/26:
* Text

### 3/23/26:
* I used <a href="https://www.w3schools.com/CSS/css3_flexbox.asp"> this website</a> and <a href="https://www.youtube.com/watch?v=nuXahrkx_9s"> this youtube video.</a> 
* 

Day 1 of 3 day plan:
I used <a href="https://www.w3schools.com/CSS/css3_flexbox_items.asp"> this website</a> to learn about how to add text to the boxes. I used the try it yourself and messed around with the code. I learned that in order to add the text to the boxes you need to make a container div to create the box then apply that div to text. For example:
``` CSS
<html>
<head>
<style>
.container {
  display: flex;
  background-color: DodgerBlue;
}

.container div {
  background-color: #f1f1f1;
  margin: 10px;
  padding: 20px;
  font-size: 30px;
}
</style>
</head>
<body>

<div class="container">
  <div>Item 1</div>
  <div>Item 2</div>
  <div>Item 3</div>
</div>

</body>
</html>
```

  I also messed around with code like flex-grow. I made 1 box 2x the size of the other boxes. I learned that the more you try to make the box multiply in size, the less it grows. 

Day 2:
I used the same <a href="https://www.w3schools.com/CSS/css3_flexbox_items.asp">website</a> as yesterday. I tried to learn how to change the order of boxes. I read about it then used the try it yourself. I found out first you need to create a container div, put it around your text, then use `<div style="order: 3">something</div>`. For example:
``` CSS
<html>
<head>
<style>
.container {
  display: flex;
  background-color: dodgerblue;
}

.container div {
  background-color: #f1f1f1;
  color:#000;
  width: 100px;
  margin: 10px;
  padding: 10px;
  text-align: center;
  font-size: 30px;
}
</style>
</head>
<body>

<div class="container">
  <div style="order: 3">1</div>
  <div style="order: 2">2</div>
  <div style="order: 4">3</div> 
  <div style="order: 1">4</div>
</div>

</body>
</html>
```

<div class="flex-container">
  <div style="order: 4">Text 1</div>
  <div style="order: 1">Text 2</div>
  <div style="order: 3">Text 3</div>
  <div style="order: 2">Text 4</div>
</div>
```



<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->


