First read the report and examine the image.

And then since we know there is text information inside the image we can use strings or exfiltool.

Using strings, we found an encoded text at the bottom : Zhh\djrljhZdb\`jnphf

And then we use Cyberchef and use the Magic module to check what encryption it is.

We managed to find that it is encrypted with rotate-right and it outputted the coordinates : -44.259654-21.057843

But those coordinates are incorrect if you type it into google maps as is, the correct coordinates are 44.259654,21.057843

After typing in the correct coordinates we find the exact location and also the country and town : https://maps.app.goo.gl/gdXhSh8Pe2inh1nL6

serbia-rakinac-44.259654-21.057843
