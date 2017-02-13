# Layered Web Design
A LAYERED WEB DESIGN (LWD) TEMPLATE

LWD is a new methodology for creating one-page websites, specifically targeting small businesses and startups that need only static websites with limited content. In the code, the site is essentially a one-page website, but visually it looks like a multi-page website with many of the common features of a website (navigation patterns, menu links, separate "pages", etc.). You can think of it as a hybrid app/website.

Built on HTML5, CSS3, and Javascript (jQuery in my case) these small apps provide the look and feel of an app or website in the small package of a one-page website. There are many benefits to this method of website design, including:

- A faster, lighter website for the user to download
- Less taxing on servers and user data plans
- Grounds the user in a familiar design patter (and reduces scrolling)
- The perception of increased load speeds
- Provides an app-like experience without having to create an app
- Leaner code for developers
- Only basic Javascript is needed to create transitions


### Demo
[https://brianhaferkamp.github.io/layered-web-design-template/](https://brianhaferkamp.github.io/layered-web-design-template/)

### Video Tour (YouTube)
[![Video tour screenshot, click to watch](https://github.com/brianhaferkamp/layered-web-design-template/blob/gh-pages/img/videoScreenshot.jpg)](https://youtu.be/PWGvR_wAiBA)

### Screenshots of the sections

#### Home/Splash

![Screenshot of home/splash page](https://github.com/brianhaferkamp/layered-web-design-template/blob/gh-pages/img/2017-02-13_074545.jpg "Photo of the home/splash page that sits under all of the layers")

#### About

![Screenshot of about page](https://github.com/brianhaferkamp/layered-web-design-template/blob/gh-pages/img/2017-02-13_074726.jpg "Photo of the about section")

#### Services

![Screenshot of services page](https://github.com/brianhaferkamp/layered-web-design-template/blob/gh-pages/img/2017-02-13_074818.jpg "Photo of the services section")

#### Contact

![Screenshot of contact page](https://github.com/brianhaferkamp/layered-web-design-template/blob/gh-pages/img/2017-02-13_074859.jpg "Photo of the contact section")

#### Shop

![Screenshot of shop page](https://github.com/brianhaferkamp/layered-web-design-template/blob/gh-pages/img/2017-02-13_074933.jpg "Photo of the shop section")

## Why did you create this hybrid site?

This design methodology tries to solve a couple of different issues. The first is the page bloat of even small, multipage websites that is putting strain on mobile user data plans and data connections. The second is the disorienting, scrolling nature of the solution to the multi-page website: the one-pager.

By combining both the small size of the one-page website and the familiar patterns of a multi-page design we can decrease overhead on servers and mobile users while not disorienting users with long, scrolling websites.

This pattern also has the secondary benefits of: a smaller code base, ability to add animations and transitions to "page" loads, a low barrier to entry for beginning designers, and an app-like site without the need for a large (and for most small sites, unnecessary) javascript framework.

## What sorts of techniques did you use?

It's not all that complicated. The main concept is to take a relatively positioned one-page website and break up the sections into layers. This is achieved by applying position: absolute (of fixed) to those sections. This creates a stacking effect where you can bring layers to the front or layer them in any way that you choose. Using viewport height and width units allows you to have full-bleed images or layers with scrolling or no scrolling. I used jQuery to handle section transitions (page loads) but you could use CSS or vanilla javascript. That's it, really. The rest is building out sections just like you would any page on a website. You could even feed dynamic data to the page through a JSON file or AJAX request to a database.

## Have questions or comments?

If you want to talk about this or learn more, I'm happy to chat with you. Connect with me on Twitter:

[@brianhaferkamp](https://twitter.com/BrianHaferkamp)
