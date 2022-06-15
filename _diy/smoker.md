---
title: Smoker 2.0
layout: single
classes: wide
date: 2022-06-14
author_profile: true
header:
  teaser: /assets/imgs/smoker/smoker-header3.jpg

excerpt: Smoker with IOT fan

gallery1:
  - image_path: /assets/imgs/smoker/smoker-header1.jpg
    url: /assets/imgs/smoker/smoker-header1.jpg
  - image_path: /assets/imgs/smoker/smoker-header2.jpg
    url: /assets/imgs/smoker/smoker-header2.jpg
  - image_path: /assets/imgs/smoker/smoker-header3.jpg
    url: /assets/imgs/smoker/smoker-header3.jpg

gallery2:
  - image_path: /assets/imgs/smoker/smoker1.jpg
    url: /assets/imgs/smoker/smoker1.jpg
  - image_path: /assets/imgs/smoker/smoker2.jpg
    url: /assets/imgs/smoker/smoker2.jpg
  - image_path: /assets/imgs/smoker/smoker3.jpg  
    url: /assets/imgs/smoker/smoker3.jpg  

gallery3:
  - image_path: /assets/imgs/smoker/smoker4.jpg
    url: /assets/imgs/smoker/smoker4.jpg
  - image_path: /assets/imgs/smoker/smoker5.jpg
    url: /assets/imgs/smoker/smoker5.jpg

gallery4:
  - image_path: /assets/imgs/smoker/smoker6.jpg
    url: /assets/imgs/smoker/smoker6.jpg
  - image_path: /assets/imgs/smoker/smoker7.jpg
    url: /assets/imgs/smoker/smoker7.jpg

fan_gallery1:
  - image_path: /assets/imgs/smoker/fan1.jpg
    url: /assets/imgs/smoker/fan1.jpg
  - image_path: /assets/imgs/smoker/fan3.png
    url: /assets/imgs/smoker/fan3.png
  - image_path: /assets/imgs/smoker/fan2.jpg
    url: /assets/imgs/smoker/fan2.jpg

---

My second welding project - a smoker from an old barrel with IOT fan:
{% include gallery id="gallery1" caption="First runs of the fan experiment and cooking of a smoked salmon" %}

A few months after I finished the [grill project](/diy/grill/) I decided to move on to the next natural welding project - a smoker. I had no prior experience with smoked food other than eating at a restaurant a few times and it is not like I loved it too much, but I was after the challenge.

Smokers started popping out everywhere in the last few years, probably because people were bored at home during the Covid-19. I consulted a few friends that had recently bought smokers and understood that the main challenge is keeping the food at a constant temperature for a long time. The most popular method to do it nowadays is using a pellets chamber with electrical ignition system. But where the fun in that??

Another method is using a charcoal smoker with a fan that controls the amount of air supply. That sounded like something I can leverage to learn some IOT stuff I wanted for a long time, so I decided to go for it!

## Smoker
This project was naturally divided to two tasks - the welding part and the IOT fan part.
My wife's father is a farmer and we found some in one of his fields an old heavy \~100L iron barrel.
This turned the welding part into mostly grinding challenge:
{% include gallery id="gallery2" caption="Original iron barrel and the beginning of the grinding process" %}
After two days of grinding both the external and internal paint, I cut the upper part as a lid and a door for the charcoal. This way I can use it both as a grill and a smoker. Added a few hinges, legs and wheels and thought I can use standard oven grates I was able to find:
{% include gallery id="gallery3" caption="After two days of grinding and cutting"%}

Lastly, I painted it using a heat resistant black spray, added two cabinet gas springs to support the heavy lid and decided to replace the oven grates with self made heavy duty grates from 8mm rod:
{% include gallery id="gallery4" caption="Custom made grates from 8mm iron rod"%}

## IOT Fan
As mentioned above a major part of this project was working on the IOT fan. The idea is to control the amount of air in the chamber in order to control the flames and maintain the temperature.
The main features are temperature probes for the food and the chamber, simple display, control fan both manually and automatically, and a web app console.

Here are a few photos of the development prototype and first experiment:
{% include gallery id="fan_gallery1" caption="The fan prototype and web console screenshot" %}

I have detailed the process of learning and building this sub-project in a [Github repo](https://github.com/uzadude/smoken).

