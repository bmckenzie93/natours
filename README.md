# natours
Project from Udemy Course

# 4-14-2020 {
  [4:11pm]
  I just watched the first section about styling the header of this project. So far I have lerned how to use the polygon attribute to style the shape of an element using CSS. Everything else I pretty much knew already. I am excited to use this technique to make my headers look 'modern' is some future projects. I also learned about a cool extension that will hilight colors in the editor with the color of the color. 

  [4:34pm]
  I completed writing the code for the first section of the header. After I complete the entire header I will switch into my own project where I implement the knowledge from this course.

  [4:53pm]
  Finished watching the next section about styling and positioning the text in the header. I usualy use flexbox to position things in the center, but here I learned more in depth about how to use position absolute and transform to center things. Good to know.

  [5:20pm]
  I styled the header text content. I used rem units instead of pixels like the video shows because I like my fonts to be responsive. I'm sure hell suggest the same later in the course anyways.

  [5:55pm]
  I just coded in the animation for the heading text to slide in from the left/right on load. It is something that I dont use often so I want to remember how to do this in the future.

  [6:28pm]
  Watched the lecture on styling the button to look as if it is raising off the page when hovered on, and gets closer to the page when it is being clicked. Super cool, this is definately one of the key things I want to have going on in my style of web designing using css.

  [6:47pm]
  Completed the hober and active states for the button on the heading. I love the functionality of using translate with box shadow to make the button look as though we are actually pressing on it in 3d.

  [7:03pm]
  Finished the lecture on the second half of the button styling. This part is to make the button animate in from the bottom after the header text animates in, and to pulse when hovered in and out of the button.

  [7:28pm]
  Completed the animation for the button to slide in from the bottom AFTER the text slides in from the sides. I used animation fill mode to make its opacity be the same as it is set to in the 0% section of the keyframe untill the animation delay is over, which makes it invisble untill the delay is over. during the delay the text animations are happening. I also made a psudo element after it that will scale up and opacity 0 on hover making it look like it is pulsing.

  With what I have just learned in creating this header I want to now begin to create my own project. 

  Project Ideas:
  1. Create an animation of a foot kicking a ball that will fly and bounce after. have the foot cock back on hover, then cock back a bit more then kick the ball on active. Make the ball fly and bounce.
}

# 4-15-2020 {
  [7:52pm]
  Last night I designed and animated a bouncing ball with a cool background making it look pretty realistic. It was really exciting.

  I just watched the section of the course where I was explained inheritance, and I see the value in making the default font size 10px instead of 16 - I think - as well as how to universally select the before and after psudo elements as well in the reset for the page. I also learned to set box sizing to inherit in the reset, and specify border box in the body. I will revise this project to follow these practices now. 
}

# 4-16-2020 {
  [12:32pm]
  Last night and this morning I listned to videos anout using BEM - 'Block Element Modifyer' - methidologies for naming html classes as well as a 7 - 1 folder system for organizing sass folders and files.

  [12:53pm]
  I refactored the html and css to follow BEM methodologies.

  [1:24pm]
  Reviewed Sass.. mixins, extends, nesting, variables ect.. nothing new

  [1:27pm]
  I am now reviewing command line. I just learned that I can autocomplete using tab if there is only one folder that starts with whatever I am typing. that is helpful
    COMMAND LINE : NEW TRICKS
      -Use tab to autocomplete folder names
      -Create multiple files with touch command, not one at a time
      -mv or cp .. will copy or move a file up one folder
      -rm = remove from computer - not to trash bin
      -rm -r will delete a whole folder and its contents
      -open filename can open an image
      - up key well show last commands fired

  [2:00pm]
  I just installed nodeJS and npm to use npm sass compiler on this project. Before this I had only used the live sass compiler extension on vs code.

  [2:24pm]
  I just ran my first npm script! I learned all about using node-sass to compile my sass! so cool! 

  [2:45pm]
  I just installed live server with npm and am now running it to watch live updates on this project.

  [2:50pm]
  I am at the point where I have my work flow environment all set up and am ready to move on with the natours project, but first I want to go back to my wild water world project and implement some of what I have learned on it. I want to make the buttons have a cool animation.

  [3:17pm]
  Nevermind I am so done with that damn project. MOVE ON BRANDON!

  [3:42pm]
  Code refactored, scss styles nested

  [3:52pm]
  I just watched how to create the '7-1 archatecture' file methidology and am now going to create all of the files to implement it.

  [4:24pm]
  I just disected my code into differant files for scalability. 

  [6:07pm]
  I just created my own grid system using floats. It was some straight up math! I see how powerfull css grid and flexbox are now that I know what the old school way of doing layouts with floats is. All hail flexbox and grid hahaha. 

  [6:33pm]
  I am about to create a heading component, keeping in mind archatecture, scalability, reusability, and good css practices.

  [7:30pm]
  I styled a heading component with a skew on hover effect that can be reused throughout the project. 

# 4-18-2020 {
  [12:30pm]
  It is saturday, I have the day to work on my dreams again. I have been working on this advanced css course for the last few days I've had, as well as been brainstorming about the next project that I want to undergo 'Off The Wall Graffiti' website remake.

  [1:27pm]
  I just created and styled the learn more button. I learned the &rarr; code to make an arrow. I also wasnt able to make my button move up at first because I forgot to make it an inline block.

  [1:46pm]
  I watched how to do the image composition in the about section, and now I am going to code it out. 

  [2:25pm]
  I completed the composition component. I used the :not psudoselector again to hover over a div and select the images inside that were not being hovered over to scale them down. cool stuff here. also used the outline property, couppled with the outline offset to make a cool border with a gap.

  [3:13pm]
  I am about to code up some feature boxes.

  [4:05pm]
  I completed the feature section with all the feature boxes. I went ober BEM again, making text with a gradient, and creating a skewed background section. I learned how to use the direct child selector and why to use it - as to not skew the children of the children as well.

  [4:38pm]
  I just watched how to make a card flip and have differant information on each side. there was 2 cards positioned absolutely ontop of eachother, one that rotates 180deg and the other 0 deg, both with a backface visibility hidden. Epic stuff there - now let me try.

  [5:41pm]
  It took a while but I got it down. I was stumped as to why there was a white square behind my card as it was flipping but it was because I had the background shadow on the card instead of the card side.

  [6:37pm]
  I took a bit of a break to make a few chess moves and I am back at it now. maybe like 10 min. 

  [7:30pm]
  The front of that card was sooo lit to make! It took a cool minute.. I guess it only took an hour so not that long but it was challenging. I had to use box decoration break: clone and background blend mode: screen for the first time. I kept forgetting to add classes to certain preceading elements in the BEM method which confused me for a while each time. like card, card-heading, card-heading-span, having all 3 of them in each elemnt.

  [9:00pm]
  I finished making all 3 cards and the button below them. I broke it by placing an htmnl element in the wrong div or something and had to fix it but I finally got it. time to clock out!
}

# 4-19-2020 {
  [11:22am]
  I'm not oficially clocked in to code right now but im going to try and sneak in a lesson while my family is occupied.
}

# 4-25-2020 {
  [11:47am]
  I am about to work on the story section on this Natours project. In this section I will learn how to create testimonials and have a bakcground video. I am not feeling totally in flow with code so far this morning, so I am going to make myself some coffee and try and zone into what I am learning and become present to it. No rush, I have 8 hours today.

  [1:00pm]
  So far I have gone over how to skew a div with content, and skew back the content so it looks right. I also went over the shape outside ability and made a clip path of a circle.

  [1:36pm]
  I finished making the stories design. I added a hover effect making the picure zoom out, blur, and darken on hover; while the name of the person animates in on top. Next up is the background video.

  [2:07pm]
  I completed the stories section by adding a background video. 

  [2:21pm]
  I just watched how to create a solid color gradient by specifying the gradient from 0 to 50% as one color, then from 50 to 100 the next color.

  [3:03pm]
  I created the 'booking' section where a form will go. I started creating the form, so far I just have the inputs with their labels on there.

  [4:06pm]
  I just styled a really cool input/label group. I learned about how to select adjacent sibilings with the + psudoselecor, as well as how to use the placeholder-shown as well. animating the placeholder to transition down into the label on focus is awesome!

  [4:31pm]
  I just watched how to custom style radio buttons. super rad! I'm going to take a second to take out the trash then come back and code that out. Return='4:38'

  [5:39pm]
  I just completed the radio buttons and the submit button, completing the book section. I learned how to style custom radio buttons and only display them when checked.

  [5:57pm]
  I'm about to start of the footer now.

  [7:15pm]
  I banged that footer out then watched the section about how to style the fixed navbar and create the animations. that was a few that I am excited to go over.

  [8:07pm]
  I completed creating the navigation styling for when it is open all the way, with the hover effects on the links too. its a cool effect that looks like the background is filling up from the side using a lateral gradient and adjusting its position and size. Next up on the project is to give it open and close functionality;
}

# 5-2-2020 {
  [12:42pm]
  I'm about to contnue on this tutorial project. I took a break from it to implement what I had learned so far on my own project, immersed in art, and am now ready to continue on this one for more information.

  [1:58pm]
  I just coded up the button icon. It is a line made of a span, and a before and after psudo element to make it into 3 stacked hamberger lines. on click the center line turns transparent and the other two lines rotate to create an X. cool beans.

  [4:00pm]
  I got off earlier to take my son on a walk to the creek, but now i'm back! time to bang out this modal.

  [5:52pm]
  I completed the modal, which is the last section of the project, and it was cool. I learned how to do some things in css that I thought I had to use javascript for. Things like creating a modal pop up that can open and close or opening and closing a menu. I can do these things with either the target psudosecector or a checkbox state. Next up on the project is to make it responsive.

}

# 5-12-2020 {
  [4:25pm]
  I've been writing media queries since 1:00 with a cool mix in that I learned how to do. i'm on the footer right now and i'm excited to write the media queries on my own project after all of this is done.
}