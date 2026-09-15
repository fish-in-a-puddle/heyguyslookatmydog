# heyguyslookatmydog
A website that shows you random pictures of my dog. That's pretty much it.

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/78520988-0be8-483c-9bf6-ba3590a76877" />

#### [Visit the site here](https://fish-in-a-puddle.github.io/heyguyslookatmydog/)

## Features

- Displays one of 55 pictures of my dog with captions
- New image button so you don't have to reload the page over and over again
- Custom pixel art paw print cursor
- Share button to quickly copy the link to your clipboard
- Links to the project here on Github and on Stardance

## How it works

The image that is shown when the page loads is picked using Javascript random number generation. Using a switch() function, the image's SRC property and the caption's text-content property are selected depending on the number. I was originally going to set the image as an empty div and change the image by setting the class. Each class would contain the background image and the height and width of the div. However, this didn't work for some reason, so I figured out how to set an img element's SRC property in Javascript and worked from there.
