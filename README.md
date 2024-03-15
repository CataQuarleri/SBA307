# SBA307
### This project is a responsive website for a pet sitting service created only with HTML and CSS. It was styled as desktop first and uses media queries for mobile access.
<br>
If the user accesses the website from a desktop, they'll see a neat header with a fully functional navbar showing all the navlinks available and a dropdown menu in the navbar that is signaled with an arrow down icon. When hovering on the Sign Up nav link the dropdown menu shows up and gives the option to Login and register as a client or Login as an admin. 
The homepage hides a cute animation that activates on hover. 
<br>
If the user accesses from a mobile device, the navbar gets hidden under a burger menu. The icon on the navbar gets activated on click (through a hidden checkbox) and shows a side menu and an overlay on top of the main container. The side menu can be hidden by clicking again anywhere inside the menu except for the links. On mobile device there are also some difference from the desktop mode, for example all the cards from the client stories and welcome page are set vertically. 
<br>
The Login/Register page for clients features 2 forms but it only shows one at a time. Login form is the one showing by default but if the user needs to create an account, by clicking the link at the bottom of the card the login form hides and a register form takes it place. This was accomplished by using the :target pseudo-class.

### For this Skills Based Assesment, I completed the following requirements: 

## HTML Requirements
- Have at least three pages.
  - There are 4 pages including "Home", "Clients", "Services" and "Client Login/Register"
- Keep the grid system consistent between pages as much as possible.
  - I've used the same navBar for every page and duplicated some of the content containers to mantain a consistent grid
- Use at least ten different HTML tags. -
  - Just in the homepage I used: "html", "head", "meta", "link", "title", "script", "body", "header", "nav", "a", "img", "div", "main", "h1", "p", "strong" and "button" 
- Include at least one table.
  - The service page includes a table with a header, 3 columns and 4 rows. The base of the table is made with bootstrap but I modified some of the styling to keep a consistent color.
- Include at least two forms.
  - Under the Sign In dropdown, the Client Login/Register shows one form, but if you click on the "Create account" link, there's a surprise! 
- Include at least one dropdown menu.
  - The sign in nav link is actually a dropdown menu with the options to login as a client or as an admin

### Include at least one of each of the following forms of content: 
- Text. - checked
- Images. - checked
- GIFs. - checked
  
## CSS Requirements
- Make use of inline, internal, and external styling.
  - Each page has the external styling link, the pages that have img tags have inline styling for those elements and in the Service page I used internal styling to overwrite the bootstrap styling I linked. 
- Use five different CSS selectors.
  - I used element selectors for general styling (*, body, li, a), most of the selectors I used were .class but also I used #id to select one element inside the nav, and I also used the pseudo-class :hover to make some animations.
- Use colors that complement each other.
  - the color palette used was "https://coolors.co/palette/d17d10-ef9826-f5c07a-8ebc38-afd36b-d4e8b0" that remind me of a park, earthy tones.
- Use Flexbox and/or the Bootstrap Grid.
  - I used Flexbox as my main positioning tool but I also used Bootstrap to generate the table in Services page.
- Use at least two CSS animations.
  - There's one surprise animation in the homepage and the whole navbar has animations on hover