---
title: Roses are Red
date: "2015-05-01T22:12:03.284Z"
description: "Practical tips and resources to help you maximize colour and contrast accessibility throughout your workflow."
---

Have you ever seen one of these before?


Ishahira Colour Vision Test
This is the Ishahira Colour Vision Test. It is the most common test used to evaluate varying levels of colour vision impairment or colour blindness.

Colour blindness affects around 5% of the population, with a higher prevalence in males than females. The most common pattern type of colour blindness is Deuteranopia, or Red-Green colour blindness.


Normal and Deuteranopia Color Spectrum
Although Red-Green vision-deficiencies are the most common, they are certainly not the only pattern. There are 5 other major colour vision impairments that affect people’s ability to distinguish colours. For more information on these there’s a great article here.

Colour Blindness is not the only relevant consideration in web development. Contrast Ratios also play a huge part in the accessibility of a web design.

The Web Content Accessibility Guidelines (WCAG) specify three different designations for acceptable contrast ratio in relation to text size and weight: A, AA, AAA.

The standard minimum compliance level (AA) requires that text has a minimum contrast ratio of 4.5:1. This designation is surprisingly difficult to achieve. Play around with this colour contrast picker from Lea Verou:


I encourage you to head over to Site Inspire or One Page Love with a handy colour picker and see how many of those sites would run into contrast ratio issues despite their beautiful design — you might be surprised.

As a result of all these varying impairments it can be difficult to design a website which is “colour safe”.

Thankfully, there are a few excellent resources out there to help mitigate the risk of having an inaccessible web page.

Color Blindness Simulators
There are a number of chrome extensions that will allow you to simulate colour vision impairments on any web page easily.


I Want to See Like the Color Blind Interface
I Want To See Like The Color Blind is as simple as they come and is operated by right clicking on a page and selecting “Experience Colour Blindness”. From the dropdown list that appears you can choose any of the 8 colour impairment filters.


NoCoffee
NoCoffee is a slightly more involved chrome extension that allows the user to adjust the severity of various pervasive vision issues including blocked fields of vision and color deficiency.

Colour Choosers:
Choosing Colours can be a daunting task. Many people use color picking tools to help them choose colours for web pages, logos, etc. There are a few, however, that have built-in colour accessibility functions.


Coolers.co is an excellent colour picker for a variety of reasons. Coolers.co has ‘saveable’ pallets, SCSS variable export formats, and you can upload a photo and it will generate a palette from that photo’s color scheme automatically. In addition to all that functionality, it has a built-in colour deficiency filter which can give you an idea right from the outset whether your colours will be colour blind friendly.


Colorsafe.co is a great resource for choosing WCAG-compliant colour schemes. It will generate colour palettes which are automatically filtered to only include AA (or higher) compliant choices.

Accessibility Diagnostics
Maybe you have already made your website or have been given design choices but are not sure how you stack up to the accessibility guidelines. There are a number of resources to diagnose not only colour-blindness and contrast-ratio compliance, but the entire WCAG guidelines including font size, semantic appropriateness, etc. Here’s a few popular options:


WAVE: This Web Accessibility Evaluation tool is simple and effective. Just paste your url into the landing page and it will output a screenshot of the website in-browser that includes alerts regarding semantic element appropriateness, contrast ratio, text size, etc. Each identified error gives the user a “What it means” “Why it matters” and “How to fix it”.


Achecker is a free online tool that checks an url for web accessibility complications. What sets it apart from WAVE is that it refers to specific lines of code and explains in simple terms what’s missing, and what to add.

In Summary
There is a vast array of web accessibility tools and resources available for free and in real time. The only barrier to creating accessible design is a lack of information, or a lack of motivation. As designers and developers, the responsibility to produce accessible experiences is paramount, and easier than ever.

Further Reading
If you’re looking for a more in-depth understanding, check out Geri Coady’s Color Accessibility Workflows.

If you’re more of a “Further Listening” type of person, check out Shop Talk Podcast’s Episode 272 which features Geri Coady and Shop Talk hosts Dave Rupert and Chris Coyier.