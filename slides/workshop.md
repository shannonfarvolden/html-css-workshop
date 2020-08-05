# Introduction to Web Development Workshop

---

### By the end of the workshop you will:

- Create your very own single profile page in HTML, CSS and JavaScript

Here's what you'll create today!
[IMAGE HERE]

- **Deploy your single profile page to Github Pages**

---

### And by doing so, you will:

- Understand what HTML, CSS and JavaScript means and their roles in web development
- Inspect website elements using Google Chrome Developer Tools

---

### Your Instructors & Mentors today

Our lead instructors:  
Kim Diep – Software Engineer @ M&G Plc  
Shannon Farvolden - Software Engineer @ Pace Revenue Management

Assistant Instructors:  
Katie Sanderson – Software Engineer @ Goldman Sachs  
Larisa Aionesei – Data Engineer @ BI Professional  
Zahra Waheed - Bioinformatician @ EMBL-EBI

---

### Setup

- Code editor (Visual Studio Code)
- Google Chrome browser

---

### What is HTML?

- Hyper Text Markup Language (HTML) is the backbone used to create web pages
- Web Browsers like Google Chrome render HTML
- When the browser receives a file with `.html` extension, it knows that there are a set of rules that need to be applied to that file in order to display on the web page. Today we will be understanding some of those rules

---

### Download sample project

Head over to https://github.com/shannonfarvolden/html-css-workshop

Find the Code button and click download zip. We will be writing some code in here later!
![alt text](slides/images/project-download.png 'Project download')

---

### What is an HTML Element?

- HTML elements are the building blocks of HTML pages
- HTML elements are represented by <> tags
- An HTML element is defined by a start tag, some content, and an end tag:  
  `<tagname>Content goes here...</tagname>`

---

### HTML Boilerplate

- Basic Structure: html, head, body

---

### Exercise 2

- Go to a website URL of your choice
- Use the Google Chrome Developer Tools to inspect the HTML elements
- Can you spot where the head and body are? You might also see a header and footer on some sites.

---

### HTML Text

Let's walk through some common html tags

## Headings can be created by **h<a number 1-6>**

This will display the largest size heading
`<h1>My First Heading</h1>`

Paragraphs which are displayed as smaller text can be created using p tag
`<p>My first paragraph.</p>`

## Try it yourself! Open up starter.html and after line 9 add `<h1></h1>` or your tag of choice with any text in between

---

## HTML Lists

You can create a list using the `ul` tagname with `li` for list items

```
<h2> A few of my favourite things </h2>
<ul>
  <li>Coffee</li>
  <li>Picnics</li>
  <li>Coding</li>
  <li>Girls in tech events</li>
</ul>
```

To change your list into an ordered list update `ul` to `ol`

```
<h2> A few of my favourite things </h2>
<ol>
	<li>Girls in tech events</li>
  <li>Coffee</li>
  <li>Picnics</li>
  <li>Coding</li>
</ol>
```

---

### Links

Links are created using the `a` tag with the location pass in the `href` attribute (href stands for "Hypertext Reference")

Some tags, such as this tag, will allow you to pass through an attribute to specify additional information about the element.

`<a href="https://www.nhm.ac.uk/">Link to natural history museum</a>`

---

### Images

Images are displayed using the img tag. src is used to specify source of the image. alt is the alternative text displayed if the image is not found.
`<img src="profile.jpg" alt="Profile picture">`
Because the img tag contains attributes only and no content, it does not have a closing tag

---

### Breakout!

Notes: At this point of the workshop, attendees work under instructor guidance to create their profile page in HTML/CSS/JavaScript

---

### Let's put together your profile page

### Instructor Demo

Let's create a new directory (folder) in Visual Studio Code

---


### Kim - Notes on structure transfer over to Slides

### HTML:
- Adding the boilerplate, including the footer
- Adding headings (H1) - profile page greeting
- Adding greeting paragraph (p) - bio
- Adding Containers - structuring our one pager website: Card container, Heading container, Intro container
- Adding an Image (Profile Picture)
- Adding anchor links to social media
- Unordered lists: Creating your experience section
- Unordered lists: Creating your education and projects section

### CSS:
- Creating your First CSS file and linking to stylesheet
- Setting a background color on the body
- Changing the colour of a heading tag
- Introduction to using CSS to target IDs - add IDs in and CSS for IDs

### Advanced:
- Using Google Fonts (optional) to change the font, include style inside <head>
- Intro to Font Awesome: applying font awesome icons onto social media links and styling with CSS
