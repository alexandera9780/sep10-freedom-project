# Entry 6
##### 5/5/25

Since the last blog entry, we've began to code our websites, using our wireframes that we created, as well as using our content from our Part A software advancements and hardware advancements. My wireframes were made for the computer design, as well as phone designs. [This is the design I made for the phone](https://wireframe.cc/Usu0g1). [And this was my design for computer](https://wireframe.cc/F8klVE). However the wireframe and the actual website came out slightly different. The original idea was to have a navigation bar on the side on the screen that would open and close slowly. This never ended up happening due to the fact that the navigation bar would always open top to bottom and it would completely disappear when clicked. Since it couldn't be helped, I instead opted for making my accordions at the bottom open from left to right first before opening top to bottom. One thing I had to do so it could fit properly on screen when opening left to right was using `position: absolute;`  `left: 200px;`  `transform: translate(-50%);`  `width: 100px;`. These 4 lines of code in my CSS fixed the accordion to the right size and place on the screen. From there, I used my newly learned jQuery and used the `.animate` function to open the accordion to normal size upon clicking the buttons. This came with the problem that all the buttons in the code were linked together, so no matter what button I pressed, it would randomly open up the accordion. I fixed this by adding ids to all my buttons and instead of linking to div classes I just linked to the id.

## EDP
At this point in the building of my freedom project, I'd say I'm in the final stages of the Engineer Design Process. I've done all my testings on my tools, I've ran through all my code and debugged. All thats left to do is to put in finishing touches and make sure that the website looks clean and presentable for presentations, as well as elevator pitches.

## Skills
### Adaptability
I feel like even though it wasn't a skill I necessarily tried to work on too much, it was a skill that came up a lot, especially during this part of the website creation. After the initial wireframes of the project, when I realized they weren't working out, I needed a plan b on deciding what to do next. Thankfully, with a couple ideas from a few friends, we helped to determine what the next steps should be, showing adaptation to a bad situation ,turning it into a better situation.

### Attention to details
This is an important skill that I also didn't really try to work on too much, but it came up a lot as well, more so during the coding parts. While coding, precision is everything, and one wrong code could ruin the entire website for you in an instant. I worked well on precision, especially when it came to the div classes and the CSS, since I has to use my own eyes to scout the distance between the accordion and the walls of the screen, so that it looked normal when opening.

[Previous](entry05.md) | [Next](entry07.md)

[Home](../README.md)
