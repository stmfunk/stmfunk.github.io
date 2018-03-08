---
layout: post
title:  "Projectors, how do they work?"
date: 18-03-08 20:34:15 +0000
categories: questions
---

Digital projectors are ubiquitous in our lives. We use them to entertain, learn and display but how do they work? So there are four main types of projector in use today: Digital Light Processing(DLP), Liquid Crystal on Silicon (LCoS), Liquid Crystal Display (LCD), or LED and Laser. There is also a class of projector based off CRT technology. We will start with this.

The technique behind CRT (Cathode Ray Tube) projectors is effectively the same as used in a traditional boob tube TV, except with the projector the image is projected forwards onto some form of canvas or flat surface and in a TV the image is projected from behind onto a phosphorus screen. Another key difference, one that is most obvious when you see an image of a CRT projector, is the three tubes. Traditional TVs have a single tube with three electron guns one for each colour. A CRT projector has three tubes each with a single electron gun. This means three images are being projected simultaneously a red, blue and green one. As a result the image needs to be calibrated precisely to line up all three channels, otherwise the picture can be blurry or distorted. Each tube is fitted with a large lens to magnify and focus the image. While CRT projectors have many drawbacks: expensive to purchase and power, very hot when running, difficult to calibrate, heavy and difficult to transport; they are still used today for their excellent picture quality. 

![CRT Projector]({{ "assets/crt_projector.jpeg" | absolute_url }})

A more modern technology is the DLP projector. This technology is seriously bad-ass. The idea is to physically manipulate light with moving mirrors in a form light a binary computer. It's incredibly precise and exactly timed. So basically you have a large lamp (like any projector) which shines onto an array of mirrors. Each mirror is responsible for one pixel of the image. Now these mirrors are really tiny, like fraction of a hair tiny. Each one is hinged at the center, and controlled with a matrix. The mirror can tilt either toward the lens (on) or away (off) allowing binary control over the pixel. 
By flickering quickly the image can be made grey. Now to add colour to an image the projector contains a spinning colour wheel that splits the light into red, green and blue. The DLP chip synchronises with this disk flickering the pixel different colours at different amounts. Now tell me that isn't mental? 

![DLP Projector]({{ "assets/ProjectorDLP.jpg" | absolute_url }})

A similar but somewhat less awesome technology is LCoS or Liquid Crystal over Silicone. LCoS uses a spinning colour wheel like DLP and relies on mirrors, however unlike DLP the mirrors do not move on an LCoS array. They rely on Liquid Crystals, a technology also used in LCDs. 
The image is created by shining a white light onto a set of three dichroic mirrors, which only reflect light at a certain wavelength. This splits the light into red, green and blue channels, which are shone onto the LCoS arrays themselves. 
The LCoS array consists of a matrix of nematic or ferromagnetic liquid crystals. These crystals have interesting properties when a current is applied to them, for example the more common nematic crystals will become untwisted when a current is applied allowing light to pass through them. 
The crystal is placed above a reflective layer and when and light is shone onto the pixel it will reflect if there is a current being passed through it. The light of each colour is reflected off a different LCoS chip, and the three beams are recombined using an arrangement of prisms into a full image which is then shone through a lens and projected. 

![LCoS Projector]({{ "assets/lcos-projector.jpg" | absolute_url }})

Next up is LCD technology. You have probably head of this one, LCD TVs are pretty ubiquitous nowadays, you are probably reading this article on one right now in fact. 
The technology here is very similar to LCoS. The first few stages are identical with the white being split with mirrors etc, but instead of the light being reflected off the LCoS chip, it is passed through an LCD screen. This screen contains the same liquid crystals used in LCoS but the array is less complicated when light is simply passing through.
After this is passed on through a similar prism configuration and voila, an image. LCDs are much cheaper that DLP projectors, and easier to make than LCoS which is why most projectors you see everyday are of this type. 

![LCD Projector]({{ "assets/lcd-projector.jpg" | absolute_url }}) 
Now I mentioned LED and Laser projectors earlier. These are alternative light sources rather than image processing technologies. In all the above projectors there is a light source, typically a big ole lamp. These lamps have drawbacks, they get very hot and they need to be replaced fairly often. 
The alternatives are LED and Laser light sources. LEDs firstly, have very low power consumption and low heat output. They also produce a more coherent light source than a lamp which means less light is wasted. In addition they can produce light of any colour so there is no need for a splitter to divide up the white light. 
Lasers are even more efficient. They produce a very tight coherent beam of light of any colour producing a much sharper image. They consume very little energy and can produce a brighter image. To top it all off they last much longer than lamps too. 

I think I have covered everything I set out to, there was more to it than I thought there would be, but we got there in the end. 

References:

<http://www.explainthatstuff.com/projectiontv.html>

<https://electronics.howstuffworks.com/lcd-projectors2.htm>

<https://www.electronichouse.com/smart-tv/buying-guide-types-of-video-projectors/>

<https://yourbusiness.azcentral.com/crt-projector-work-25245.html>

<https://electronics.howstuffworks.com/dlp2.htm>

<https://electronics.howstuffworks.com/lcos4.htm>

<https://www.lifewire.com/how-laser-based-video-projectors-work-4132351>

{% comment %}
 vim: set wrap spell:
{% endcomment %}
