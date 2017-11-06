# Css
#responsive vs mobile first design

##responsive
###
The term responsive web design was coined by Ethan Marcotte in a 2010,Responsive design is the way to adapt a website's layout for different screen resolutions using fluid grids that ebb and flow with a device's screen size.No one wants to pan across the page, so this is a fantastic way to create a single website that works across multiple devices and is how some sites look so similar on your phone, tablet and desktop.your site needs to adapt to survive. Your site should be able to adapt to whatever circumstance your user is using it for,Different elements of the page should be able to change when viewing them on a smaller screen. The text should shrink and photo sizes should reduce, or not even exist, on a mobile platform. Media queries are usually what's used to get your site responsive. There are dozens of free frameworks, like Bootstrap and Foundation,ex:
http://minister-engineer-54261.bitballoon.com/
http://broker-rabbit-10874.bitballoon.com/

##mobile first design
###
Mobile First, means you're designing an online experience for mobile before designing it for the desktop or for any other device. This is both a strategy and sometimes even a new way of writing code. A few years ago, a desktop site with some adjustments was what you would see on your phone. Now a site is often created specifically with your mobile device in mind. Planning for your site layout is different for mobile than it is for a desktop, because you're forcing yourself to identify what's important about your content to your user. By starting with content, you're able to figure out what is relevant to your users, whether they're using their phone or desktop. . Designing mobile first makes you really think about specific design decisions, like fonts, right at the get-go. If you want the different versions of your site to resemble each other, you'll have to pick a font for your headers that looks great on the smallest device. It would make no sense to use a really beautiful script font if you can't read it on a small screen.




#Css with BEM

# How to write CSS with BEM

#### The Block, Element, Modifier methodology (commonly referred to as BEM) is a popular naming convention for classes in HTML and CSS. Developed by the team at Yandex, its goal is to help developers better understand the relationship between the HTML and CSS in a given project.


# Here's an example of what a CSS developer writing in the BEM style might write:

#### In this CSS methodology a block is a top-level abstraction of a new component, for example a button: .btn { }. This block should be thought of as a parent. Child items, or elements, can be placed inside and these are denoted by two underscores following the name of the block like .btn__price { }. Finally, modifiers can manipulate the block so that we can theme or style that particular component without inflicting changes on a completely unrelated module. This is done by appending two hyphens to the name of the block just like btn--orange.

# Why should we consider BEM?

    1. If we want to make a new style of a component, we can easily see which modifiers and children already exist.
    We might even realize we don't need to write any CSS in the first place because there is a pre-existing
    modifier that does what we need.

    2. If we are reading the markup instead of CSS, we should be able to quickly get an idea of which element depends
    on another (in the previous example we can see that .btn__price depends on .btn, even if we don't know what that
    does just yet.)

    3. Designers and developers can consistently name components for easier communication between team members.
    In other words, BEM gives everyone on a project a declarative syntax that they can share so that they're on the same page.
