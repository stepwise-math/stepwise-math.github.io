---
title: "How was this site built?"
date: 2020-04-11
description: "You have a to-do list that scrolls on for days. You are managing multiple projects, getting lots of email and messages on different messaging systems, managing finances and personal health habits and so much more."
tags: [hugo, setup, installation]
---


## The First Step: Hugo on Windows
I use Windows 10. True Story.

And I noticed that the official installation assumes a couple of things.

* Only technical users install and use Hugo
* All such technical users will have chocolatey or [scoop](https://scoop.sh/) (not to be confused with [sqoop](https://sqoop.apache.org/))
already installed.

To be very honest, `April 10 2020` was the first time I learnt about the existence of the scoop. Why this barrier to entry?
Instead here is another website that gives me exactly what I need: [Link to External Website](https://bwaycer.github.io/hugo_tutorial.hugo/tutorials/installing-on-windows/)


## Next: Find a theme

This site uses the Hugo theme found [here](https://themes.gohugo.io/theme/hugo-ink/) and whose code can be found [here](https://github.com/knadh/hugo-ink). 
If you like looking at pretty themes, [this link](https://themes.gohugo.io/),
has a full list of themes categorized under helpful tags.

Deciding which theme to use was not my last problem in piblishing this ite. 
But I plan to write a future update in another post, about that. So watch out for that!
### Sub-Note: 

Inserting Images. Adding my Images to the same folder as my post#.md was what FINALLY worked for me.
The below image uses:

	 '![alt_text](/posts/my_pic.jpg)'
	
###### (sub sub note: Do not forget the "!" at the start)

![alt_text](/posts/clutch_pearls.jpg)


### Yet another way to do it, is as follows:

1. Create your free Account on [Cloudinary](https://cloudinary.com/). It's free for [basic usage](https://cloudinary.com/pricing).

2. Upload your desired image to Cloudinary

3. Hover over your uploaded image and find the 'Copy URL' button

4. Paste URL into your Hugo Markdown(.MD) file. It should look something like this:


	`![alt_text](https://res.cloudinary.com/dtpkxwtpw/image/upload/clutch_pearls.jpg)`

And that also helped me generate the image below!
![alt_text](https://res.cloudinary.com/dtpkxwtpw/image/upload/v1586643083/clutch_pearls_ff406d.jpg)

## Third: Push Everything to Github 
I cannot do better than the info on their official website. So here goes the link to creating a freely hosted website on
[Github](https://help.github.com/en/github/working-with-github-pages)

## Fourth: Launch site using Github Pages
And engage.

![Engage!](https://res.cloudinary.com/dtpkxwtpw/image/upload/v1586644418/picard_pointing_ltcv5k.jpg)
Congratulations! The final moment your site is `live` is somewhat anti-climactic. But hey, at least you did it.



###### 
