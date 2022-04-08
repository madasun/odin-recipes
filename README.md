
# Studio Ghibli Recipes

## Introduction - First TOP Project

I'm currently progressing through the "Foundations" of The Odin Project to learn and get more hands-on practice for web development. This recipe website began as a basic project for HTML and CSS. I decided to revisit it after the lessons about flexbox to apply/practice what I had learned. Doing so also gave me an opportunity to brainstorm layout ideas through sketching and then try to bring it to life.

# Overview

## (Beginning)

This is the first layout I created using only HTML and CSS. Despite it being very simple I wanted it to be pleasant to look at. 

![game title](/src/images/ghibliRecipesOri.png)

After completing more lessons I returned to the recipe website to add flexbox. There were immediately some changes I knew I could make to improve it. For one, my eyes kept straying to how large I made the header image instead of the real content of the website -- the recipes. I also noticed that every popular recipe website I visited showcased the food itself through photos and not just simple links. With these things in mind I tried putting together a plan.

## (Planning)

Before changing anything I sketched a few basic ideas to get a sense for what I wanted. I planned to keep it simple looking overall with muted colors. The first version of the website had an (overly huge) image of the fire demon, Calcifer, as a "polaroid." This was because I wanted it to feel like a photo being shared/looked at and not some image randomly on the page.

I still liked the idea of using polaroids in the reworked layout and decided to turn the recipes into the polaroids. They would be like snapshots from the movies the recipes originated from. It could bring focus (and nostalgia) to the recipes themselves, especially if I simplified the header/hero image.

![Sketches](/src/images/sketches.png)


## (Finished)

When I first started adding flexbox I too often found myself copy-pasting pieces until it seemed like it would work. It wasn't conducive to learning how it all fit together though. I revisited the TOP practices, did a lot of Google searches (CSS-tricks guide to flexbox in particular was very helpful!), and spent extra time figuring out how to fit flexbox together through understanding rather than "lucky guessing." It wasn't until after I pushed it to github that I realized it didn't look as good on mobile as I originally thought. 

This gave me another opportunity to play with the flexboxes to fix it, and even make the footer look less crowded than before, despite all the extra links and an email input box. The changelog shows the before/after of the footer.

Overall, I'm satisfied with how this project turned out and the process of making it!

![Fin](/src/images/ghibliRecipes600.png)

# Conclusion

The html and css lessons were a great refresher, and I know more about flexbox now than I ever have. However, a big thing I'm taking away from this is putting the time into learning why something does what it does. Copy-pasting snippets might work, but knowing the way it all fits together made the whole process easier and more enjoyable for me in the end. I'm definitely going to hang on to this thought when I get more into Javascript..

For this website in the future, I would if I could:
- add a hamburger menu for mobile
- go over the css to consolidate it where possible
- make needed adjustments so the site is usable for anyone (as I learn more about accessibility)
- (For example, is there closed-captioning when needed? The YouTube video I embedded on the Fish Cookies recipe page doesn't have CC available. I think it needs a written transcript instead)

# *Changelog
As of 04/07/22:
- screenshots of [Previous layout](/src/images/ghibliRecipes.png) and [Current layout](/src/images/ghibliRecipes2.png)
- image header was being cut off on mobile and it now scales depending on size of viewport
- remove unnecessary alt tags from purely decorative images for screen readers
- add section tags around the header, content and footer to better define them 
- the embedded youtube video on "Fish Cookies" does not auto-play and the resolution scales with size of viewport
- despite there not being many links in the footer, they became crowded and hard to read on mobile, so I:
1. rework the flexboxes and now they wrap correctly so it's readable on mobile 
2. add extra information and link navigation
3. organize the content of footer and give them visual hierarchy

![Footer](/src/images/footers_ba.png)


# Credit & Resources
- [The Odin Project](https://www.theodinproject.com)

- [Studio Ghibli](https://ghiblicollection.com/) of course

- [Heart icon by Freepik - Flaticon](https://www.flaticon.com/free-icons/heart)

- [Search icon by Smashicons - Flaticon](https://www.flaticon.com/free-icons/search)

- [Adobe Color](https://color.adobe.com/create/color-wheel)

- [CSS-Tricks Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

Recipes from:
 - [Alison's Wonderland Recipes](http://wonderlandrecipes.com), [Sylvia Wakana](https://sylviawakana.com), [IssaGrill](https://www.youtube.com/channel/UC5vRdlKbfMnfuGKuHpruPfA), [Binging With Babish](https://www.bingingwithbabish.com)

___
Any feedback is welcome! Thank you for visiting!
