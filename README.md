# Weekly_Test_-4_CSS_Properties
## Hosted Link: https://mayankkatheriya.github.io/Weekly_Test_-4_CSS_Properties/
![image](https://github.com/Mayankkatheriya/Weekly_Test_-4_CSS_Properties/assets/128832286/94283514-8413-4c2e-b22c-7a9f35356477)
![image](https://github.com/Mayankkatheriya/Weekly_Test_-4_CSS_Properties/assets/128832286/d4b36753-252e-4c73-97ce-91670075e6e6)

HTML part:\
Document Type Declaration specifying HTML5.\
Opening 'html' tag with a "lang" attribute set to "en" for English language.\
'head' section containing:\
Meta charset declaration for UTF-8 character encoding.\
Meta viewport tag for responsive design.\
Title tag specifying the title of the web page.\
Link to an external CSS stylesheet named "styles.css".\
Links for preconnecting to Google Fonts servers.\
Links to Google Fonts for the "Poppins" font family in different weights.\
Link to Google Fonts stylesheet for "Material Icons" font.\
Closing '/head' tag.\
CSS part:

*: This targets all elements in the document.

margin: 0;: Sets the margin of all elements to 0, effectively removing any default margins.\
padding: 0;: Sets the padding of all elements to 0, effectively removing any default padding.\
box-sizing: border-box;: Adjusts the box model to include padding and borders within the element's total width and height.\
font-family: 'Poppins', sans-serif;: Sets the default font family to "Poppins" (a Google Font) and fallback to a generic sans-serif font.

html: Targets the HTML element.

scroll-behavior: smooth;: Adds smooth scrolling behavior when navigating within the page using anchor links.

body: Targets the body element.

background-color: rgb(242,242,242);: Sets the background color of the body to a light gray (rgb(242,242,242)).\
![image](https://github.com/Mayankkatheriya/Weekly_Test_-4_CSS_Properties/assets/128832286/834a0ff8-c1a0-4d45-b67c-8e5d98df7aec)
\
\
\
![image](https://github.com/Mayankkatheriya/Weekly_Test_-4_CSS_Properties/assets/128832286/c997261f-66d6-49d6-945f-eeb8c4fcb8f2)
![image](https://github.com/Mayankkatheriya/Weekly_Test_-4_CSS_Properties/assets/128832286/9a10d737-2404-4db8-8b7e-a2d7d009a23d)

HTML part:\
inside body tag we need to make a header fot the nav bar\

CSS part:\

header: Targets the <header> element.

position: fixed;: Fixes the position of the header on the viewport, so it remains in the same place even when scrolling.\
top: 0;: Places the header at the top of the viewport.\
left: 0;: Aligns the left edge of the header with the left edge of the viewport.\
z-index: 5;: Specifies the stacking order of the header, ensuring it's displayed on top of other elements with lower z-index values.\
width: 100%;: Sets the width of the header to 100% of the viewport width.\
height: 75px;: Sets the height of the header to 75 pixels.\
display: flex;: Establishes a flex container for the header's content.\
justify-content: center;: Centers the content horizontally within the flex container.\
background: #333;: Sets the background color of the header to a dark gray color (#333).\
![image](https://github.com/Mayankkatheriya/Weekly_Test_-4_CSS_Properties/assets/128832286/164db852-20ed-4efa-8b0c-21a686582b19)
![image](https://github.com/Mayankkatheriya/Weekly_Test_-4_CSS_Properties/assets/128832286/682ef6d5-5724-4ccd-bd2e-30de5c2ba3c9)

HTML part:\
Opening "header" tag:\
Opening "div" tag with class "nav":\
"h2" tag with class "logo":\
"a" tag with "href" attribute pointing to a placeholder and containing the text "LOGO".\
"ul" tag with class "menu":\
"li" tag containing an "a" tag with "href" attribute pointing to a placeholder and containing the text "Home".\
"li" tag containing an "a" tag with "href" attribute pointing to a placeholder and containing the text "Services".\
"li" tag containing an "a" tag with "href" attribute pointing to a placeholder and containing the text "Portfolio".\
"li" tag containing an "a" tag with "href" attribute pointing to a placeholder and containing the text "About Us".\
"li" tag containing an "a" tag with "href" attribute pointing to a placeholder and containing the text "Contact Us".\
Closing "div" tag
Closing "header" tag\

CSS part:\
CSS for the ".nav" class:

"display: flex;"\
"padding: 0 10px;"\
"max-width: 1200px;"\
"width: 100%;"\
"align-items: center;"\
"justify-content: space-between;"

CSS for the ".nav .logo a" class:

"color: white;"\
"font-weight: 700;"\
"text-decoration: none;"

CSS for the ".nav .logo a:hover" class:

"color: rgb(255,255,255,0.8);"

CSS for the ".menu" class:

"display: flex;"\
"align-items: center;"\
"list-style: none;"

CSS for the ".menu li a" class:

"color: white;"\
"text-decoration: none;"\
"height: 100%;"\
"padding: 20px 0;"\
"margin-left: 40px;"

CSS for the ".menu li a:hover" class:

"color: rgb(255,255,255,0.8);"\
![image](https://github.com/Mayankkatheriya/Weekly_Test_-4_CSS_Properties/assets/128832286/caf1248a-3aae-44ca-9abc-d21f6c2cf446)
\
\
\
![image](https://github.com/Mayankkatheriya/Weekly_Test_-4_CSS_Properties/assets/128832286/a6438311-e261-45bd-8c16-c86f38815294)
![image](https://github.com/Mayankkatheriya/Weekly_Test_-4_CSS_Properties/assets/128832286/58ab37b6-ee78-4925-8edf-c9ea8ad2d4fc)

HTML part:\
Now come to the first section --> our homepage
make a section of class name "homepage" and give id "home"

CSS part:\
.homepage: Styles the element with the class "homepage."

width: 100%;: Sets the width to 100% of its containing block.\
height: 100vh;: Sets the height to 100 viewport heights.\
background-image: url(./Background-image.jpg);: Sets the background image.\
background-size: cover;: Scales the image to cover the container.\
background-position: center 65%;: Positions the image slightly lower than center.\
background-attachment: fixed;: Keeps the background fixed while scrolling.\
display: flex;: Treats the element as a flex container.\
justify-content: center;: Horizontally centers its content.\
align-items: center;: Vertically centers its content.\
position: relative;: Sets a relative positioning context.

.homepage::before: Creates a pseudo-element before the .homepage content.

content: "";: Sets content for the pseudo-element.\
position: absolute;: Positions the pseudo-element absolutely.\
left: 0; top: 0;: Positions the pseudo-element at the top-left corner.\
height: 100%; width: 100%;: Makes the pseudo-element cover the entire parent.\
background: rgba(0, 0, 0, 0.2);: Sets a semi-transparent black overlay.\
![image](https://github.com/Mayankkatheriya/Weekly_Test_-4_CSS_Properties/assets/128832286/a161e4c9-400d-47b8-a7dc-d83d9b12f237)
\
\
\
![image](https://github.com/Mayankkatheriya/Weekly_Test_-4_CSS_Properties/assets/128832286/ffbd8929-03dc-4b5c-82d3-a5d9eeb4907d)
![image](https://github.com/Mayankkatheriya/Weekly_Test_-4_CSS_Properties/assets/128832286/8998ffdf-c913-4c1b-a4ee-7d88fc7aee44)

Html part:\
'section class="homepage" id="home"': Defines a section with the class "homepage" and the ID "home."\
.content: Contains the section's content.\
.text: Contains the text content.\
'h1': Defines a level 1 heading for the title.\
'p': Defines a paragraph for the description.\
'a href="#services"': Defines a link with a destination anchor pointing to the "services" section.

Css part:

.homepage .content: Styles for the content container within the homepage section.

display: flex;: Uses flexbox layout.\
height: 85%; width: 70%;: Sets the height to 85% and width to 70% of the parent container.\
z-index: 3;: Sets the stacking order of the content.\
align-items: center; justify-content: center;: Centers content both vertically and horizontally.\
flex-direction: column;: Arranges items vertically.

.homepage .text: Styles for the text content within the homepage.

text-shadow: Adds a shadow to the text for a visual effect.\
color: white; font-size: 20px; text-align: center; margin-bottom: 40px;: Defines text appearance.

.homepage .text h1: Styles for the heading within the text.

font-size: 60px; margin-bottom: 10px;: Adjusts heading appearance.

.homepage a: Styles for the link within the homepage.

text-decoration: none; color: black; font-size: 18px;: Defines link appearance.\
background-color: white; padding: 10px 30px;: Sets background and padding.\
margin: 10px 0; border: 2px solid white; border-radius: 5px;: Adds margin, border, and rounded corners.\
box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);: Applies a shadow effect.\
transition: 0.4s cubic-bezier(0.55, 0.06, 0.68, 0.19);: Specifies transition properties.

.homepage a:hover: Styles when hovering over the link.

Changes the color and background to create a hover effect.\
![image](https://github.com/Mayankkatheriya/Weekly_Test_-4_CSS_Properties/assets/128832286/c7a0feee-b66e-48b3-8914-a7da76b81924)
\
\
\
![image](https://github.com/Mayankkatheriya/Weekly_Test_-4_CSS_Properties/assets/128832286/f8297f1f-9f9d-4c44-84ca-7b472976f565)
![image](https://github.com/Mayankkatheriya/Weekly_Test_-4_CSS_Properties/assets/128832286/b506f282-082f-4907-be00-816e22f5277f)

HTML part:\
'section class="services" id="services"': Defines a section with the class "services" and an ID of "services".\
'div class="text"': Contains the text content within the services section.\
'h1'Our Services'/h1': Displays the heading "Our Services".\
'p'Explore our wide range of camping gear services.'/p': Provides a paragraph describing the services offered.

CSS part:

.services: Styles the section containing the services content.

width: 100%: Sets the section's width to cover the entire available width.\
display: flex: Displays the section's content as a flex container.\
justify-content: center: Horizontally centers the content within the container.\
align-items: center: Vertically centers the content within the container.\
flex-direction: column: Arranges the content in a column layout.\
padding: 30px 0: Adds padding to the top and bottom of the section.

.services .text: Styles the content within the .services section.

display: flex: Displays the text content as a flex container.\
flex-direction: column: Arranges the text content in a column layout.\
align-items: center: Centers the text content horizontally within the container.\
margin: 50px 0: Adds margin to the top and bottom of the text content.

.services .text h1: Styles the heading within the text content.

font-size: 32px: Sets the font size of the heading to 32 pixels.\
font-weight: bold: Makes the heading text bold.\
![image](https://github.com/Mayankkatheriya/Weekly_Test_-4_CSS_Properties/assets/128832286/1f47bef8-f230-4467-a6d3-b89a9b69141b)
\
\
\
![image](https://github.com/Mayankkatheriya/Weekly_Test_-4_CSS_Properties/assets/128832286/5c4c36b4-fb9b-4504-b3ea-fd76000e8008)
![image](https://github.com/Mayankkatheriya/Weekly_Test_-4_CSS_Properties/assets/128832286/a9a0f8f5-f419-4ee8-a790-ca6be3601ae9)

HTML part:

.cards: A container for a collection of cards that represent different camping gear items.

.card: A single card element containing information about a specific camping gear item.

img: An image representing the camping gear item.\
h3: A heading element displaying the name of the camping gear item.\
p: A paragraph element providing a brief description of the camping gear item.

CSS part:

.cards: Styles the container for the cards.

width: 88%;: Sets the container width to 88% of its parent element.\
max-width: 1500px;: Limits the maximum width of the container to 1500px.\
display: grid;: Uses grid layout for arranging the cards.\
grid-template: auto / auto auto auto;: Defines the grid template with auto-sizing columns.\
gap: 40px;: Sets the gap between grid items.

.card: Styles individual cards within the container.

width: 98%;: Sets the card width to 98% of its parent container.\
background-color: white;: Sets the background color of the card to white.\
display: flex;: Displays the card content as a flex container.\
flex-direction: column;: Arranges content vertically in a column.\
align-items: center;: Centers content horizontally within the card.\
justify-content: center;: Centers content vertically within the card.\
text-align: center;: Centers text content horizontally.\
padding: 25px;: Adds padding around the card.\
border-radius: 5px;: Rounds the corners of the card.\
box-shadow: 0px 5px 10px rgba(0, 0, 0, 0.04);: Applies a subtle shadow to the card.

.card img: Styles the images within the card.

width: 120px;: Sets the image width to 120px.\
height: 120px;: Sets the image height to 120px.\
border-radius: 50%;: Rounds the image corners, creating a circular shape.\
margin: 5px 0;: Adds margin to the top and bottom of the image.

.card h3: Styles the heading within the card.

margin-top: 20px;: Adds margin to the top of the heading.

.card p: Styles the paragraph text within the card.

margin-top: 5px;: Adds margin to the top of the paragraph.\
margin-bottom: 20px;: Adds margin to the bottom of the paragraph.\
![image](https://github.com/Mayankkatheriya/Weekly_Test_-4_CSS_Properties/assets/128832286/ea4bbb1d-d3e8-4be8-a500-52df95d77aa5)
\
\
\
![image](https://github.com/Mayankkatheriya/Weekly_Test_-4_CSS_Properties/assets/128832286/91147342-9019-4d23-a86e-deb4b660d71d)
![image](https://github.com/Mayankkatheriya/Weekly_Test_-4_CSS_Properties/assets/128832286/c989cd76-9df6-43ad-b070-bbf443da2663)

HTML part:\
section class="about" id="about": Defines a section with the class "about" and an ID of "about".

div class="text": Contains the introductory text content within the about section.

h1 About Us /h1: Displays the heading "About Us".\
p Discover our story in providing camping services. /p: Provides a brief description of the content.

div class="details": Contains detailed information about the company.

Within the .details div, there are nested <div> elements for each section:

h3 Our Story /h3: Displays the heading "Our Story".\
p: Provides a paragraph describing the company's history and commitment to quality.\
h3 Our Mission /h3: Displays the heading "Our Mission".\
p: Provides a paragraph describing the company's mission and commitment to providing quality gear.\
h3 Our Vision /h3: Displays the heading "Our Vision".\
p: Provides a paragraph describing the company's vision and goal to become a camping enthusiast's destination.\
h3 Our Team /h3: Displays the heading "Our Team".\
ul class="team": Contains an unordered list of team members.\
li: List items for each team member.

CSS part:

.about: Styles the entire about section.

width: 100%;: Sets the width of the section to cover the entire available width.\
display: flex;: Displays the section's content as a flex container.\
justify-content: center;: Horizontally centers the content within the container.\
align-items: center;: Vertically centers the content within the container.\
flex-direction: column;: Arranges the content in a column layout.\
padding: 30px 0;: Adds padding to the top and bottom of the section.

.about .text: Styles the text content within the .about section.

display: flex;: Displays the text content as a flex container.\
flex-direction: column;: Arranges the text content in a column layout.\
align-items: center;: Centers the text content horizontally within the container.\
margin: 50px 0;: Adds margin to the top and bottom of the text content.

.about .text h1: Styles the heading within the text content.

font-size: 32px;: Sets the font size of the heading to 32 pixels.\
font-weight: bold;: Makes the heading text bold.

.about .details: Styles the container for the detailed information.

width: 87%;: Sets the width of the container to cover 87% of the available width.\
max-width: 1500px;: Limits the maximum width of the container to 1500px.

.details div: Styles each individual detail section within the .details container.

margin-bottom: 30px;: Adds margin to the bottom of each detail section.

.details h3: Styles the heading within the detail sections.

margin-bottom: 10px;: Adds margin to the bottom of the heading.

.team: Styles the unordered list of team members.

list-style-position: inside;: Sets the position of the list bullets to inside the list items.\
![image](https://github.com/Mayankkatheriya/Weekly_Test_-4_CSS_Properties/assets/128832286/dc496ddb-115a-429f-bd19-b7b69ca647dc)
\
\
\
![image](https://github.com/Mayankkatheriya/Weekly_Test_-4_CSS_Properties/assets/128832286/8b105d83-25ee-4a92-ae00-c2a6b691946d)
![image](https://github.com/Mayankkatheriya/Weekly_Test_-4_CSS_Properties/assets/128832286/d084fae9-e361-4988-ae88-1beb0d38f647)

HTML part:\
"section class="contact" id="contacts"": Defines a section with the class "contact" and an ID of "contacts".

"div class="text"": Contains the introductory text content within the contact section.

"h1"Contact Us"/h1": Displays the heading "Contact Us".\
"p"Reach out to us for any inquiries or feedback."/p": Provides a brief description of the content.\

"div class="info"": Placeholder for additional contact information.

CSS part:

.contact:

This class is assigned to the container or section that holds the contact information.\
width: 100%; makes sure the contact section spans the full width of its parent container.\
display: flex; sets the display property to flex, allowing for flexible layout options.\
justify-content: center; horizontally centers the content within the container.\
align-items: center; vertically centers the content within the container.\
flex-direction: column; arranges the content in a column layout, stacking elements on top of each other.\
margin-top: 30px; adds a margin at the top of the contact section.

.contact .text:

This class targets a sub-container within the contact section that holds text-related elements.\
display: flex; uses flexbox for layout.\
flex-direction: column; arranges the content in a column layout.\
align-items: center; horizontally centers the content within the sub-container.

.contact .text h1:

This targets the "h1" element within the .text container.\
font-size: 32px; sets the font size to 32 pixels.\
font-weight: bold; makes the text bold.

.info:

This class is for a sub-section within the contact area, perhaps displaying additional information.\
width: 87%; sets the width to 87% of its parent container's width.\
max-width: 1500px; restricts the maximum width to 1500 pixels.\
display: flex; uses flexbox layout.\
justify-content: space-between; evenly distributes content along the horizontal axis.\
align-items: center; vertically centers the content.\
margin: 30px 0; adds a margin above and below the sub-section.\
padding: 20px 0; adds padding above and below the sub-section.\
![image](https://github.com/Mayankkatheriya/Weekly_Test_-4_CSS_Properties/assets/128832286/4b33b0ab-18ed-4c41-804e-c2261bba1e02)
\
\
\
![image](https://github.com/Mayankkatheriya/Weekly_Test_-4_CSS_Properties/assets/128832286/a018604c-8e6a-4cb9-8135-cf137caf7106)
![image](https://github.com/Mayankkatheriya/Weekly_Test_-4_CSS_Properties/assets/128832286/b40f1229-aa3e-4646-82d9-91de0bec9b32)

HTML part:\
"div class="info"": This is the main container for the contact information and the contact form.

"div class="col-1"": This represents the left column within the ".info" container and contains contact details.

"class="contact-details"": Each of these divisions holds a specific piece of contact information along with an icon.

"span class="material-icons" id="location"": This span element displays a location icon using Google's Material Icons.

"p"123 Campsite Avenue, Wilderness, CA 98765"" This paragraph contains the address information.

"div class="col-2"": This represents the right column within the ".info" container and contains a contact form.

"form action="#contacts" method="get" autocomplete="on"": This form is set to submit data to a URL when the user interacts with it.

"input type="text" placeholder="Name*" required class /": This input field is for the user's name, with a required attribute ensuring it must be filled in.

"input type="email" placeholder="Email*" required class /": This input field is for the user's email address, also required.

"textarea placeholder="Message*" required class/textarea": This textarea is for the user's message, also required.

"button id="submit" type="submit" class=""Send Message"/button": This button, when clicked, submits the form data.

CSS part:

Styling for contact details:

.contact-details: This class is used to style a container for contact details. It uses flexbox to align its children vertically and adds a margin at the bottom.\
.material-icons: This class is used for styling icons, possibly using Google's Material Icons library. It sets the color of icons to a semi-transparent black.\
#timing-1, #timing-2, #timing-3, #location, #call, #email, #language: These are IDs applied to specific elements, presumably for contact details. They are styled to have a font size of 20px.\
.col-2: This class styles a container that appears to be used for dividing content into two columns. It sets a width and margin for spacing between columns.

Styling for a form:

form: This selector styles a form element. It arranges its children in a column layout with a gap between them.

input: This selector styles text input fields. It sets their width, height, padding, font size, border, and outline properties.

textarea: This selector styles textareas. It sets their width, height, padding, font size, border, and outline properties.

#submit: This selector styles a submit button. It sets its width, padding, font size, text color, border, cursor, and border radius. It also defines transitions for smooth hover effects.

#submit:hover: This selector styles the submit button when hovered over. It changes the background color to a darker shade.\
![image](https://github.com/Mayankkatheriya/Weekly_Test_-4_CSS_Properties/assets/128832286/5ea71e9b-0313-4eac-a137-087ef574e1cd)

## Your Web page is ready
# Thankyou
