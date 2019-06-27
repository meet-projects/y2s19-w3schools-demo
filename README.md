# y2s19-w3schools-demo

In this demo, you’ll be guiding students through the process of making a fixed navbar by finding example code online.  

## Part 1 - State the Goal
First go to https://meet.mit.edu/ and show them what a fixed navbar looks like so they can visualize what the goal is.
<br />
Now show them our current site: home.html. It’s nice, and you can use the links to navigate the page. But a fixed navbar would make it even easier!

## Part 2 - Look Online
So we google: html fixed navbar, and look!  A w3schools resource: https://www.w3schools.com/howto/howto_css_fixed_menu.asp
<br />
Show them the example in w3schools and then click on “Try it Yourself”. Show them how you can change the content in the code in the left and then run to see the immediate changes. Wow.

##Part 3 - Integrate
Now, point out that most of this example is css, and then creating a navbar just requires making a div with the navbar class that has the links and then a div with the main class and all the content.  So we can put all of this css into a stylesheet and link it to home.html, and create the divs navbar and main.
<br />
But it’s not exactly perfect. For 1, the <h1> element makes the navbar too tall and we can’t see the page. 
<br />
Ask the students what they think we can do to fix this.
<br />
Inside styles.css, we can add:<br />
.navbar h1 {<br />
  float: right;<br />
  display: block;<br />
  color: #f2f2f2;<br />
  padding: 14px 16px;<br />
  font-size: 17px;<br />
  margin: 0;<br />
}<br />
<br />
But then we notice that when we click on the links, the <h2> elements are hidden behind the navbar.
<br />
To fix this we can give a bigger space before the <h2>. How? <br />
h2 {<br />
  padding-top: 60px;<br />
}<br />
<br />
And now we’re done!

