# Entry 6
##### 5/8/25

### What have I done so far?

In the 3 weeks that have passed by from the last blog, there have been major changes in the course. We went from just learning the tool to making a full website for the Freedom Project. Once again, I was heavily using [Foundation](https://get.foundation/) again, and I tried to make everything that wasn't regular HTML out of Foundation. I think I did good at that because a lot of the responsiveness and main features are built from Foundation elements from their Docs page. I am pretty sure there is zero Bootstrap except with some backend stuff which I still need to find and fix because it doesn't work very well with the rest of the page. The main feature of the Part A site was the [card](https://get.foundation/sites/docs/card.html) element. It displays a picture with a quick description beneath it and it was really useful for displaying some of the older technology that Aviation has. The main part of my second page displays my idea. For this I used the [Media Object](https://get.foundation/sites/docs/media-object.html) element, also from Foundation. It is kinda like a card, but smaller and sideways. It is more focused on the description instead of the picture, unlike the cards. I wanted to have some kind of diagram or model but I didn't have enough time to make it, so it is just a description of the idea that I had.

### Challenges that I Faced

This was actually one of the hardest projects that I have been assigned this year. For the majority of the semester we have been learning about a framework called [Bootstrap](get.bootstrap.com} but I decided to completely ignore that and try and mainly use Foundation. I think I succeded at that as I mentioned before, however, I learned responsiveness on Bootstrap and most of the Foundation elements aren't really compatible. I had to quickly learn and go through Foundations grid, which was actually pretty simple and easy to work out. It is called the `XY Grid` and it uses an activation class called `grid-x` to let the computer know whats happening. After that it is the screen size, followed by the columns. For example, if I wanted something to be 4 columns on a small screen and above, I would write : `small-12`. Of course there is more advanced stuff that I kinda used but I didnt fully understand how it worked and I only needed it for a few things.

I was also very limited on time for some of the project. I was away and didnt have much oppurtunity to work on the project so I had to finish it all in a rush once I was home again. I found it fun to do so I was able to work on it for a while outside of school and I would try and sneak in some more immprovements whenever I could. I got the MVP done in time and I think it was pretty good even though it was a little rushed. Since it was rushed I was a little stressed out and I can't think as well so I got a creative block and had no idea what to do at that point. 

For this project, I made a wireframe to help guide me in the design. I had to make two different wireframes for a desktop and a phone. On the phone, I wanted an accordion to display the context of project, vs it being a normal box on the desktop version. I approached this problem quite late since I didn't know how to do it and it wasn't really necesary to make. Since I had some extra time I decided to work on it. I had some problems with the accordion because the JS scripts needed to be in a very specific order to work, but other than that I was able to make it work quite well. I used a visibility class which hides the div until the screen reaches that breakpoint. Here is the code for that: 
``` bash 
<div class= "container grid-x context align-center show-for-small-only">
  <div class= "small-12 medium-8 large-6">
          <ul class="accordion context" data-accordion data-allow-all-closed="true">
```
I haven't used Foundation accordions before this so it was all new to me. The first line (In order) contains the container, the resposniveness tag I mentioned earlier, the CSS class, a Foundation alignment class, and the hiding mechanism. The second line is just the breakpoints, simalair to Bootstraps version. The third line is the div that holds the actual text. In the Foundation code it has an `is-active` tag that auto opens the tab, but I removed that. The last part is what allows the accordion to be closed since it normally needs two tabs, with only one open at a time.

All 3 challenges were very difficult to figure out, and they each took me hours to overcome and it was a little stressful at times, however I had fun working on it. It is really satisfying to finally be done with a decent product and how I managed to achieve everything I wanted to have on the site. 

### EDP
This is right at the end of the Freedom Project, so the best fit stages of the process would be 6 and 7. 6 is to evaluate the product, and I did that with the MVP. Afterwards, we contiuned to build on it to add the extra stuff such as the accordion and the colors. Once that stage was over we looked at classmates websites, and got suggestions from them, which is where step 7 comes in. I tried to incorporate some of the feedback, however I couldn't figure out how to do most of them in the short amount of time I had. I did finish the website in a much better place than from when we had the mini presentations though. 
New grid
No Bootstrap
Revert to show wbesite before responsiveness
No time
Creative Blcok
Feedback and Improvememnts
Switching elements when chaning screen sizes

[Previous](entry05.md) | [Next](entry07.md)

[Home](../README.md)
