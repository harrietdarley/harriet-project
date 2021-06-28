# Personal Portfolio & CV 
This is my personal website and CV which I created in order for potential employers, collaborators and other coders to visit. The website lists my front end development skills and previous employment, work experience and education. There are also links to my social media pages such as GitHub, Facebook and Instagram where they can find more information.  

Users can complete my contact form to enquire about future collaborations or to hire me, or simply just to get in touch. 


## UX
My website provides a detailed and informative list of my personal skills and experience. I styled my website in a way that the information could be displayed clearly and creatively for the users. I chose fonts that are engaging and clear and a consistent yet bright colour scheme to attract visitors. I thought the abstract background to begin would catch the users attention as it is unusual and reflects a style I personally like. 

### User Stories 
- As a potential recruiter, collaborater or other coder:
    - I want to know the coder's experience and their current skills. 
    - I want to be able to easily get in contact with the coder to find out more information, to hire them or collaborate with them. 
    - I want to visit the coder's social media pages. 
    - I want to be able to find out what the coder specialises in and what their personal style is. 
    - I want to know whether they are currently available for recruiting or collaborating. 


### Wireframes
I created my wireframes using Abode XD, I displayed two different aspects; one from a laptop and one from a phone, to ensure my webpage would be responsive from a variety of technology.

[**Abode XD**](https://xd.adobe.com/view/bb4d84c6-7588-400a-9241-3869ecc76a26-ee1e/)

## Features 

### Existing Features 

#### All Pages 
- **Navigation Links**: My navigation bar is constantly at the top of the page as the user scrolls, this allows them to access any page at all times by clicking the navigation links. In the center of the navigation links, I have placed my logo. 
- **Animated Titles** (excluding home page): The titles at the top of each page contain moving letters in order to accentuate the word.

#### About Me Page
- **Skills Icons**: The icons show the user visually each of my skills. 

#### Experience Pages 
- **Experience Boxes**: To present my employment, work experience and education, I have used boxes which include the date, a title and a description. 

#### Contact Page 
- **Form with Submit Button**: Allows the user to contact me by completing the form and submitting their required details. They can get in touch to collaborate, recruit me or to find out about my code. When they click the "Send" button, the form will be submitted through Form Spree and a Thank You message is displayed. Their details and message will be emailed to me so I can reply to their email address.
    - **Form Boxes**: Form boxes are required so user must fill out all details. 
- **Social Links**: When the user clicks on each of the social media icons, my GitHub, Linkedin and Twitter pages will be displayed in another tab. 
- **Footer**: The footer shows that I am the owner of the website. 

### Features Left to Implement 
- **Dynamic Boxes**: I will make the experience and skills boxes dynamic so I can easily insert content onto the page making the website easier to edit. 
- **Contact Form**: Instead of submitting my form to Formspree's API, I will create my contact form with my own code so it functions how I want it to. 
- **New Projects**: Once I create more websites, I will add a page to my website displaying my other projects. 
- **Return to Top Link** I will add a link in the footer to allow users to return to the top of the page. 

## Technologies Used 
- [**Abode XD**](https://www.adobe.com/uk/products/xd.html)
    - I used Abode XD to make designs of my website so I had a template for building tha actual site.
- [**HTML5**](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
    - My project uses HTML5 to create the basic elements and content of my website.
- [**CSS3**](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS3)
    - My project uses CSS3 to add custom styles to the website's elements and content.
- [**Bootstrap v5.0.1**](https://getbootstrap.com)
    - I used Bootstrap v5.0 to add a responsive grid system, and to use the prebuilt components, JavaScript plugins and Bootstrap styles, and I edited them for a desired effect. 
- [**JavaScript**](https://www.javascript.com/)
    - I used JavaScript to add functionality to some of the components.
- [**Tobias Ahlin**](https://tobiasahlin.com/moving-letters/)
    - The project uses Tobias Ahlian's JavaScript template to move letters. 
- [**DaFont**](https://www.dafontfree.io)
    - I used DaFont to style my text. 
- [**Cufon Fonts**](https://www.cufonfonts.com)
    - I used Cufon Fonts to style my text. 
- [**Font Awesome**](https://fontawesome.com/)
    - The project uses Font Awesome for my social media links. 
- [**Icons8**](https://icons8.com)
    - I used Icons8 to obtain my skills icons. 
- [**Favicon**](https://favicon.io)
    - I used Favicon.io to generate my favicon. 
- [**Formspree**](https://formspree.io)
    - I used FormSpree to submit my code to an API and to ensure the Submit button processed their information. 
- [**Visual Studio Code**](https://code.visualstudio.com)
    - I used Visual Studio Code to write the code for my project. 
- [**Git**](https://git-scm.com/)
    - I've used Git as a version control system to regularly add and commit changes made to my project.
- [**GitHub**](https://github.com/)
    - I've used GitHub as a remote repository to push and store changes to my project. Also using GitHub pages to deploy my website in a live environment.

## Testing 

### Responsive Testing 
By using Google Chrome's web development tools, I could ensure that every change to my website worked on many different screen sizes. I double checked this by testing the website on different technology such as a mobile phone, tablet and laptop. 

### HTML5 and CSS3 Validation 
I used the [W3C HTML Validator tool](https://validator.w3.org/#validate_by_input) and the [W3C CSS Validator tool](https://jigsaw.w3.org/css-validator/#validate_by_input) to validate both my HTML and CSS Code. 

### Bugs and Problems 
- **Animated Titles**: The JavaScript only worked on one title so I struggles with editing the JavaScript so it moved the letters on all the titles across the website. 
- **Experience Boxes**: I first tried using Bootstrap grid system to position my boxes however this was not working as I could not get the right spacing between the columns, I asked my mentor and he told me to look at using Flexbox which eventually positioned them perfectly. 
- **Computer Image**: The opacity property was not working on my image however I found out the linear-gradient property made background images opaque as it adds a layer over the image. 
_ **GitHub**: I didn't push my code upto GitHub enough times however luckily this didn't affect my project. 

## Deployment

I used GitHub Pages as a hosting platform for my project. I did the following steps to deploy my website to GitHub Pages: 

1. Opened a new terminal window in my Visual Studio Code workspace. 
2. Used the 'git init' command to initialise the Git. 
3. Used the 'git add .' command to add all files to Git. 
4. Used the 'git commit -m "Initial Commit"' command to commit all the files to Git.
5. Created a new repository called 'harriet-project' in GitHub. 
6. Used the 'git remote add origin https://harrietdarley.github.io/harriet-project.git' command to add the remote origin to my local Git repository. 
7. Used the 'git push -u origin master' command and entered my GitHub username and password to push the files to GitHub. 
8. In GitHub, I selected the 'master branch' option in 'Settings' on my repository page under the 'GitHub Pages' selection. 

### Repository Link 

https://harrietdarley.github.io/harriet-project/

### Running Code Locally 

Users can run my code locally by downloading a local copy of my code to their desktop by going to my GitHub repository. 

## Credits 

### Media 
- The photos in the website are obtained by Unsplash.
- The icons are obtained by either Font Awesome, Icons8 or Favicon.

### Acknologements 
- I received guidance from my mentor, Sunny Hebbar. He helped me with the few problems I had with my website. 
