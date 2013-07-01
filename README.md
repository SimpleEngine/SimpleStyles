SimpleStyles
============

Simple Responsive Object-Oriented CSS Framework

Thanks to and based on
-------

The principles of Nicole Sullivan's OOCSS
  https://github.com/stubbornella/oocss/

The HTML5 Boilerplate from H5BP
  https://github.com/h5bp/html5-boilerplate/

Twitter Bootstrap
  http://twitter.github.com/bootstrap/

What's different with SimpleStyles?
-------

SimpleStyles separates the structure (grid) and the styles. Unlike other grid css frameworks 
that limit the possibilities of design, SimpleStyles removes padding, margins and other visual 
styles from the grids, making it easy to drop grids inside other grids, use negative margins, 
break borders and create visual masterpieces.

SimpleStyles takes the brilliant concepts behind OOCSS and combines them 
with a responsive grid css framework like Twitter Bootstrap (only much more simplified)

Unlike Twitter Bootstap, which is really a theme out of the box, SimpleStyles assumes 
you will want to extend these styles and make your own look and feel.

Basic jQuery JavaScript extensions will be added to this framework (much like Twitter Bootstap)

What makes SimpleStyles better?
-------

If you want a css theme out of the box, Twitter Bootstap is better.
Or if you want a nice granular OOCSS framework, OOCSS.org is the way to go.

If you like the 12 grid system (that Twitter Bootstap uses) but want to be able to easily extend elements and 
drop a flexible 12 grid layout inside of another one, but not worry about messing up your grid's styles 
(like the OOCSS framework allows), then this is the framework for you.

Features
-------

1. Extremely extendable (that's what it's designed for)
2. 12 Grid system (with a true Object Oriented fluid system)
3. Light - not bloated with styles you will never use
4. Responsive
5. Simple naming convention

Naming Conventions
-------

Class and ID names use the hyphen (ie. .class, .class-name, .class-long-name)

SimpleStyles uses an object naming convention. Which is very similiar to a structural naming convention. Basically, 
you name an element for what its purpose is, not for its properties. For example, if we were to think of 
an element as an animal such as a bear, we wouldn't call it .four-paws-with-1-body (as this describes its properties). 
We would call it .bear (what it is) and include the properties inside the class.

This also makes it really to extend the class. We could make different types of bears such as .bear.polar which
could add the polar bears properties to the class. Or .bear.grizzly and so on

Let's look at a quick real world example. Let's say we wanted a 4 column system. We would create a .grid class 
(this is named after its purpose and what it is) We could then give that grid the properties it needs. Next we
could great a class .row (for each row) and so on.

Let's look at other use practices

Bad Examples (using location or properties within the class name):

1. .top-section { properties... }
2. .top-right-section { properties... }
3. .border-main { properties... }
4. .border-blue { properties... }

Good Examples (using usecase or generic class naming practices):

1. .header { properties... }
2. .header.secondary { properties... }
3. hr { properties... }
4. hr.secondary { properties... }
5. .sidebar { properties... }

It's also based on the principle that styling is done using classes not IDs. Whereas IDs are reserved for JavaScript.
This makes it very easy to know which elements JavaScript is referencing. CSS ID's were never meant to be 
re-used in a page. So sticking to classes is better for a Object-Oriented approach.

