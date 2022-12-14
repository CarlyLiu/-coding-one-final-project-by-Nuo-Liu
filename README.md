# coding-one-final-project-by-Nuo-Liu

**More is Less**

Less is more is a famous motto by the well-known architect Mies van der Rohe. This is a design philosophy that promotes simplicity and opposes over-decoration. Less is often more for people to appreciate. And when something is simple, it often contains, or is shown to have more content. But when we look at something that is complicated, what we see is often thinner than we imagine.Because the first glance is limited in the parts we can focus on, we focus on what we perceive as the centre.

I was inspired by an image from an unknown source on the internet, which expresses the moving landscape of the bright moon on the water in a simplistic arrangement of lines. If it had been a picture, I would not have felt the main idea it conveyed. Because photographs tends to be too realistic, there can be too much off-centre content and too many distracting elements.At the same time line summarisation of an image also allows for a degree of data masking and privacy of some image details.

![inspire](https://user-images.githubusercontent.com/112803802/205695292-7102a14a-26e3-4b32-9a99-446490cc6e4e.jpeg)

So this inspired the idea that I could use convolution, through edge detection, to extract the centre of expression and present it succinctly. By lining up straight lines, to represent the content. But this is much more difficult than one might think, plentiful in ideal yet skinny in reality. The implementation is more complicated than one might think, firstly the edge detection needs to be done and the image needs to be adjusted for contrast so that a better edge detection result can be obtained.When implementing this, I found that the edges of some of the photos were clearly related to the colour contrast, so using the colour contrast for the channel filtering would be more effective. However, in practice, due to the complexity of the colour of the photo I had limited experience and time, I was unable to create a perfect processing, and some grainy noise was produced in some areas where the colour changed, but the flaw was not overshadowed and the overall result was still relatively up to expectations.

At the same time, the sound is inseparable from the image and when we see the image, it is too boring without the sound, and the music allows us to immerse ourselves in the image.In order to give the viewer a better experience, I have added mouse-based interaction, which allows people to adjust the images they want to see according to their needs. I also added a sound adjustment process at the end to blend the rhythm of the music with the images and to give a new perspective.

VIDEO LINKED:https://youtu.be/0Any7ma1MUw
