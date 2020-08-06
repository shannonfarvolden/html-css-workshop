# Introduction to Web Development Workshop

---

### By the end of the workshop you will:

- Create your very own single profile page in HTML and CSS

Here's what you'll create today!
[IMAGE AND DEMO OF WHAT SINGLE PROFILE PAGE WILL LOOK LIKE]

---

### And by doing so, you will:

- Understand what HTML and CSS means and their roles in web development
- Inspect website elements using Google Chrome Developer Tools

---

### Your Instructors & Mentors today

Our lead instructors:  
Kim Diep – Software Engineer @ M&G Plc  
Shannon Farvolden - Software Engineer @ Pace Revenue Management

Assistant Instructors:  
Katie Sanderson – Software Engineer @ Goldman Sachs  
Larisa Aionesei – Data Engineer @ Avanade
Zahra Waheed - Bioinformatician @ EMBL-EBI

---

### Setup

- Code Editor (Visual Studio Code)
- Google Chrome browser

---

### What is HTML?

- Hyper Text Markup Language (HTML) is the backbone used to create web pages
- Web Browsers like Google Chrome render HTML
- When the browser receives a file with `.html` extension, it knows that there are a set of rules that need to be applied to that file in order to display on the web page. Today we will be understanding some of those rules

---

### Download sample project - Exercise

Head over to https://github.com/shannonfarvolden/html-css-workshop

Find the Code button and click download zip. We will be writing some code in here later!
![alt text](slides/images/project-download.png 'Project download')

Open the folder in Visual Studio Code
Open starter.html in Google Chrome Browser to check everything works

If you did this correctly, you should be able to see: "Welcome to the workshop! You're all set up!"

---

### What is an HTML Element?

- HTML elements are the building blocks of HTML pages
- HTML elements are represented by <> tags
- An HTML element is defined by a start tag, some content, and an end tag:  
  `<tagname>Content goes here...</tagname>`

---

### Exploring the Google Chrome Developer Tools - DEMO


---

### Exploring the Google Chrome Developer Tools - Exercise

- Go to a website URL of your choice
- Use the Google Chrome Developer Tools to inspect the HTML elements
- Can you spot where the head and body are? You might also see a header and footer on some sites.

---

### HTML Boilerplate - DEMO

- Basic Structure: html, head, body

---
### HTML Boilerplate - Exercise

Observe the Boilerplate
Add a `footer` opening and closing tag inside the `<body>`

[IMAGE OF EXAMPLE]

---

### HTML Text

Let's walk through some common html tags

## Headings can be created by **h<a number 1-6>**

This will display the largest size heading
`<h1>My First Heading</h1>`

Paragraphs which are displayed as smaller text can be created using p tag
`<p>My first paragraph.</p>`

---

### Creating Your Profile Page Greeting - DEMO

[IMAGE OF PROFILE PAGE WITH PROFILE PAGE GREETING HIGHLIGHTED]

---

### Creating Your Profile Page Greeting Heading - Exercise

[Exercise walkthroughs guide pdf in repo]

#### Try it yourself! Open up starter.html and on line 10 amend the message in `<h1></h1>` to any greeting message you like.

---

### Creating Your Greeting Paragraph - DEMO

---
### Creating Your Greeting Paragraph - Exercise

[Exercise walkthroughs guide pdf in repo]

---

### Adding <div> containers to structure your profile page  - DEMO
[IMAGE OF PROFILE PAGE WITH HIGHLIGHTED BOXES AROUND THE DIV CONTAINERS]

---
### Adding <div> containers to structure your profile page - Exercise

[Exercise walkthroughs guide pdf in repo]
- Card container, Heading container, Intro container

---

### Adding a Profile Picture to Your Page - DEMO

Images are displayed using the img tag. src is used to specify source of the image. alt is the alternative text displayed if the image is not found.
`<img src="profile.jpg" alt="Profile picture">`
Because the img tag contains attributes only and no content, it does not have a closing tag

---
### Adding a Profile Picture to Your Page - Exercise

[Exercise walkthroughs guide pdf in repo]

---

### Adding links to social media - DEMO

Links are created using the `a` tag with the location pass in the `href` attribute (href stands for "Hypertext Reference")

Some tags, such as this tag, will allow you to pass through an attribute to specify additional information about the element.

`<a href="">Twitter</a>`

---

### Adding links to social media - Exercise

[Exercise walkthroughs guide pdf in repo]

---

### Creating Your Experience section - DEMO
- Unordered lists

You can create a list using the `ul` tagname with `li` for list items

```

<h3>Experience</h3>
<ul>
  <li>Software Engineer - Pace</li>
  <li>Software Developer - Broadridge</li>
  <li>Software Developer - UBC</li>
</ul>

```

To change your list into an ordered list update `ul` to `ol`

```
<h3>Experience</h3>
<ol>
  <li>Software Engineer - Pace</li>
  <li>Software Developer - Broadridge</li>
  <li>Software Developer - UBC</li>
</ol>
```

---

### Creating Your Experience section - Exercise

[Exercise walkthroughs guide pdf in repo]

---

### Creating Your Education and Projects section - DEMO
Now that we have an Experience section, we can apply the same approach to Education and Projects

---
### Creating Your Education and Projects section - Exercise

[Exercise walkthroughs guide pdf in repo]

---
### CSS: What is it and what does it do?

---

### Creating your First CSS file and linking to stylesheet - DEMO


---
### Creating your First CSS file and linking to stylesheet - Exercise

[Exercise walkthroughs guide pdf in repo]
















### Kim - Notes on structure transfer over to Slides - TO DO


### CSS:
- Setting a background color on the body
- Changing the colour of a heading tag
- Introduction to using CSS to target IDs - add IDs in and CSS for IDs

### Advanced:
- Using Google Fonts (optional) to change the font, include style inside <head>
- Intro to Font Awesome: applying font awesome icons onto social media links and styling with CSS
