Frontend Mentor - Results summary component solution
This is a solution to the Results summary component challenge on Frontend Mentor. Frontend Mentor challenges help you improve your coding skills by building realistic projects.

Table of contents
Overview
The challenge
Links
Built with
What I learned
Useful resources
Author
Acknowledgments
Overview
The challenge
Users should be able to:

View the optimal layout for the interface depending on their device's screen size
See hover and focus states for all interactive elements on the page
Bonus: Use the local JSON data to dynamically populate the content
Links
Solution URL: https://github.com/AnnaRouss/Results-Summary-Component/edit/main/
Live Site URL: Add live site URL here
Built with
Semantic HTML5 markup
CSS custom properties
Flexbox
CSS Grid
What I learned
This was much much harder then it looked took me almost two weeks to make it and I still feel like it could have used more tweaking as its much bigger then I meant it to be but I do like that it looks okay.

<h1>Some HTML code I'm proud of</h1>
<button class="custom-button">Continue</button>
.proud-of-this-css {
  background: linear-gradient(to top,hsla(241, 72%, 46%, 0), hsla(256, 72%, 46%, 1));
  .custom-button:hover {
    background: linear-gradient(to top,hsla(241, 72%, 46%, 0), hsla(256, 72%, 46%, 1));
    color: hsl(224, 30%, 27%);
    font-family: Hanken Grotesk;
    font-weight: 700;
    font-size: 12px;
}
}
const proudOfThisFunc = () => {
 [
  {
    "category": "Reaction",
    "score": 80,
    "icon": "./assets/images/icon-reaction.svg"
  },
  {
    "category": "Memory",
    "score": 92,
    "icon": "./assets/images/icon-memory.svg"
  },
  {
    "category": "Verbal",
    "score": 61,
    "icon": "./assets/images/icon-verbal.svg"
  },
  {
    "category": "Visual",
    "score": 72,
    "icon": "./assets/images/icon-visual.svg"
  }
]
}
If you want more help with writing markdown, we'd recommend checking out The Markdown Guide to learn more.

note and the content within this section and replace with your own plans for continued development.**

chatgpt - This helped me when I was really stuck
Author
Website - AnnaRouss
Frontend Mentor - @AnnaRouss
Acknowledgments
This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.
