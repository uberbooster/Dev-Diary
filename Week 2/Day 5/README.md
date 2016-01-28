Reflect:
What else would you like to be able to do when creating your web applications?
I would like to be able to build a database that will store available rental locations (sites) while differentiating between the "types" of locations (making each location type a specific class such as RV, primitive tent, tent with electric, etc.), and report available sites to the user, then allow the user to "reserve" a specific type of site.

How do you think you are going to keep the different languages JavaScript, CSS, and HTML straight?
Not sure yet, other than to learn the syntax of each and recognize the differences.

Review:
How would you select a paragraph and make the text color "light-salmon"?
Using inline styling, you would use <p style="color: lightsalmon">This is light salmon</p>
Using internal styling you would place
p.ls {
  color: lightsalmon;
}
in the <head> <style> section then use <p class="ls">This is light salmon</p> in the <body> section.

What is the difference between inline and internal styles?
Inline styles are used at a specific tag in the <body> area and while it take priority, only works to style that specific tag.
Internal styles can be used to change the default styling of a specific tag (e.g. <p>, <div>, <article>, etc.) in the <head> section so every tag used in the <body> section will that matches your "styled" tag will use the style as defined in the <head> section.  So if you specified that all <p> tags are to be blue, when you use a <p> tag in your <body>, it will be blue without having to specify it inline.

What will the following CSS styling do?
h1 {
  font-family: "Comic Sans MS";
  background-color: chartreuse;
}
It will change the styling of any <h1> tag in the <body> section to the font Comic Sans MS and change the background color of the line to chartreuse.  The font color will be the default, which is probably black.
