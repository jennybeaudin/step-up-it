---
layout: default
title: Introduction to HTML
permalink: /classes/05-intro-to-html/
menu_hide: 1
---

## Introduction to HTML

[Beginning HTML Slideshow](http://www.slideshare.net/hglennrock/gdi-intro-htmlcssclass1mm)

## HTML for Structure: Section, Article, Header, Footer, Nav

Thus far we have discussed html tags which are used for content like paragraphs, headings, links and images.
HTML also provides some tags to help structure your document:

- **&lt;section&gt;**
- **&lt;article&gt;**
- **&lt;header&gt;**
- **&lt;footer&gt;**
- **&lt;nav&gt;**
- **&lt;main&gt;**

### **&lt;section&gt;**

A logical grouping of content, for example the 'Skills' section of a resume.

{% highlight html %}
<section>
    <h2>Skills</h2>
    <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>Adobe Creative Suite</li>
    </ul>
</section>
{% endhighlight %}

### **&lt;article&gt;**

A self-contained piece of content, for example a single job listing:

{% highlight html %}
<article>
    <h2>Vermont Works for Women</h2>
    <p>Step Up Program Coordinator, 2007-Present</p>
</article>
{% endhighlight %}

or a single blog post:

{% highlight html %}
<article>
    <h2>Breaking into Corrections: Cathy’s story</h2>
    <p>Cathy Chamberland was our very first applicant for the Step Up to Law Enforcement program this year...</p>
</section>
{% endhighlight %}

### **&lt;header&gt;**

A header for an html document or a section/article. For example the masthead area of a website containing the logo and tagline:

{% highlight html %}
<header>
    <img src="logo.png" alt="Step Up to IT" />
    <p>A nine-week program for women interested in the field of IT</p>
</header>
{% endhighlight %}

or the employer, job title and dates the position was held for a single job listing.

{% highlight html %}
<article>
    <header>
      <h2>Vermont Works for Women</h2>
      <p>Step Up Program Coordinator, 2007-Present</p>
    </header>
    <p>Coordinated training programs for women seeking new careers in traditionally male-dominated fields including law enforcement, construction and manufacturing.</p>
</article>
{% endhighlight %}

### **&lt;footer&gt;**

A footer for an html document or a section/article. For example the footer area of a website containing the copyright information.

{% highlight html %}
<footer>
    <p>&copy; 2014 All rights reserved.</p>
</footer>
{% endhighlight %}

### **&lt;nav&gt;**

A set of navigation links, for example the primary navigation of a website.

{% highlight html %}
<nav>
    <ul>
        <li><a href="/">Home</a></li>
        <li><a href="/about.html">About</a></li>
        <li><a href="/contact.html">Contact</a></li>
    </ul>
</nav>
{% endhighlight %}

### **&lt;main&gt;**

The main content area of a web page. This should only include the content which is unique to the page (in other words
the masthead, navigation and footer should not be inside the main tag). There should only ever be a single
main tag on any web page.

{% highlight html %}
<nav>
    <ul>
        <li><a href="/">Home</a></li>
        <li><a href="/about.html">About</a></li>
        <li><a href="/contact.html">Contact</a></li>
    </ul>
</nav>
<main>
    <h1>About Us</h1>
    <p>Vermont Works for Women helps women and girls recognize their potential and explore, pursue, and excel in work that leads to economic independence.</p>
</main>
<footer>
    <p>&copy; 2014 All rights reserved.</p>
</footer>
{% endhighlight %}

## Brackets Live Preview

The Brackets editor comes with a Live Preview functionality which allows you to see changes you make to your
HTML and CSS documents immediately in a browser like Chrome. 

[How to Use Brackets Live Preview](https://github.com/adobe/brackets/wiki/How-to-Use-Brackets#live-preview)

## Chrome Developer Tools

[Introduction to Navigating HTML/CSS with Chrome DevTools](https://developer.chrome.com/devtools/docs/dom-and-styles)

- Opening Chrome DevTools
- Navigating the DOM with the Elements Panel 
- Viewing Styles for an Element
- Editing Styles
- Editing HTML
