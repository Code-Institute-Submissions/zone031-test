# Zone031

Zone031 is a laser tag club that I am long-standing member and current president of. For a long while we have lacked
a proper webpage and have been relying on facebook and other tools to handle our activities. Whilst this page won't 
be able to take over all of the functionalities we have on other pages (also active social media pages are important
for presence and maximising exposure) this page is intended to serve as a new front for the club which we will be able
to control the content and form of. 

## UX

The page is meant to primarily display what the club is about, what we do and how to get in contact with us. It is 
particularly important to give an immediate impression which is enticing as well as informative. We want people who
have heard of us or who are independently exploring how to play laser tag in a structured and competitive manner to
get a good impression of what it is that we do and how we do. We also want to have a page which is useful for our
international connections, providing them with information about our tournaments and showcasing our media accounts.

What this boils down to is two generalised target users in order of priority:
* The curious local: someone with little to no knowledge of who we are and what we do but with an interest to find out 
what we and the sport are about. 
* The experienced international: someone with previous lasertag experience who is looking to connect with us or stay informed
about our activities. 

### The curious local

The curious local will be met by an immediate welcome section (top left in desktpo and top on mobile) giving a short explanation
of what we are with links to our three active social media accounts (facebook, twitch and instagram). The text itself 
is written half as information and half as an advert to try to get people to try out lasertag, prompting them to scroll down
and fill out the form below. There is a carousel of images from inside of the arena and a training video give those who are 
curious a quick idea of how things are at our training sessions.

There is further information about how the game functions in the section titled The Game. Most people won't read through all
of this, but the headlines should give a good overview and the content itself should exhaust the idea of different game formats
and the rules without being far too much and also not far too simplified. Media page showcases examples from our different kinds
of videos on different platforms as well as an interactive 3d overview of the arena we play at, giving a more in depth and closer
experience of our training sessions. In the About Us section the current committee is presented with relevant contact information
to allow the curious local a way of connecting with us.

### The experienced international

The experienced international has probably already met us or knows about us from people who have. The landing page thus contains 
some information this person is not looking for, but this is also fairly clear from the get go. The Media page and particularly 
the Tournament page will showcase our channels for videos and give a good overview of the activities we have that are of most 
interest to international lasertaggers. Information on About Us page gives an overview of how we work and who is running the club
and provides contact information for those who want to send us messages.  

### Wireframe

This was the preliminary vision of the page:
https://wireframe.cc/qC9iR3

I have diverted from this structure in a few ways. 

Rather than just having a footer I added a larger and more informativa About Us page where I am also able to present the people 
currently running the club. This gives curious locals a better experience of who we are and makes us more approachable.

Initially I wanted several team pages, but we only really have two consisten teams. Thus I decided to make one page for each (atm 
content is missing for Piraya and that page is right now just a copy of the Feydakin page). With that I also got up to a number of 
six different pages on the site, making the navbar easily dividable with bootstraps 12 columns. I would have liked to have larger 
dropdown buttons as suggested by the wireframe, with team logo rather than text, but opted for a simpler and cleaner approach in the end.

Overall the structure of the page is very similar to what I first envisioned. 

## Features

### Navbar:

* Navbar: The navbar allows people to move through the pages. There is a dropdown for selecting different teams.

### Index page:

* Hyperlinks: There are clickable hyperlinks to our instagram, twitch and facebook pages. Those take people through to our most active
social media pages and allows them to connect with us there.
* Image carousel: The image carousel provided by Magic Scroll shows inside footage from the arena. The first picture taken through a small
hole indicates that there is more to see from the inside, and having slanted images visible but not fully visible, gives visitors a sense
of exploration as they scroll through. 
* Contact form: the contact form doesn't currently send information to a real place as we are using another site for that at the moment. 
Right now it shows the idea of having a contact form where curious locals can get email invites to open training sessions. Adding that last 
bit of functionality shouldn't be too complicated but is currently outside of the scope of this project as it involves far more pieces. A 
quick fix to this could be to just link through to the site we use for our training sessions.
* Embeded facebook video: Our facebook videos give the most intimate and action-filled video material from our practices. I have selected
one I find to be particularly good and could be of interest to show people who don't know what competitive laser tag is about as well as showing 
experienced internationals how it looks inside of our practice sessions. 

### Media

* Videos: I have embedded videos from our three different channels for three different types of videos. They showcase the different kinds of
content that we have and there are also hyperlinks to the different channels/pages where people who want to can find more.
* 3d model: Embedded 3d model shows all visitors a complete overview of the arena. This is a great resource as preparation for tournaments here
as well as being a unique perspective of a lasertag arena as one rarely has a good overview of how a dark room with lots of walls actually
looks and is structured. 

In the future there will be a gallery added to show a more comprehensive view of the club. Right now I do not have the complete material to
do all of this though. 

### The game

This page doesn't really contain any features but is more a document over how the game of laser tag functions at a more structured and
advanced level.

### Tournaments 

* Videos: The videos shows the full material from the competitions listed (currently one video has gone missing from MM2020). 
Together with results this gives a full overview the tournaments.

Other than that this page is meant to show the best of what we organise and entice people to participate in future tournaments
as well as function as a document over the history of our tournaments. In the future this can be expanded greatly with separate pages
for each tournament and each installment of that tournament. Additionally another page can be added with a calendar to show not just
our tournaments but tournaments worldwide which are of interest to us and any visitors of our page. 

### Teams:

* Player cards: The player cards give each player a quick introduction. The text is playful rather than informative and serves as a 
way of adding some flair to the already positive reputation of our main team Feydakin.

Right now there is content missing for the Piraya team so that page is just a copy of Feydakin until that content has been sent to me.

In the future I would like to add more to the history of the teams as well as expand the player cards and make them clickable to reveal
more information about player history and achievments. 

### About us:

Committee member cards: Presents the current committee members in an informative way and tells of what activities the different members 
are up to. 

## Technologies used: 

* HTML/CSS: The site is built using Html and Css with The Code Institute's provided template.

* Bootstrap 4.5.2: has been used to give structure to the pages as well as provide easy conversion from mobile to desktop devices. Navbar
and form functions as well as card function has also been of great help here (and I might be forgetting something). In short: bootstrap has
helped a lot. https://getbootstrap.com/

* Magic scroll: Magic scroll has been used to add a scrollable ("carousel") mini-gallery on the index page. I wanted to have a scrollable
gallery to be able to show a few images but only taking up the space of one. https://www.magictoolbox.com/magicscroll/integration/ (This 
could have been used for videos as well but I felt like that would have been overkill with content which I already find to be plentyful.)

* Video embedding: Videos have been embedded from twitch, facebook and youtube usning iframes. Also a 3d model from sketchfab. This has been
done simply by copying the provided emebedding codes from these pages.  

## Testing



## Deployment



## Credits

* All content is original and has been written by me. 
* Photos: All photos on index page have been taken by Paulina Lager Löfgren (our secretary)
* Feydakin card images have been taken from our public facebook page and have been uploaded by someone from our team. 
* Background photo for Feydakin: Jeremy Bishop via Unsplash https://unsplash.com/
* 3d model: The 3d model has been made by Smiley from our team Feydakin.


The whole site was born out of my imagination with no concrete inspiration (but obviously a lot of unconscious inspiration.)
