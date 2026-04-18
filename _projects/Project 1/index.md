---
layout: post
title: Ball Machine Screw Conveyor
description:  I modeled a miniature screw conveyor in SolidWorks for a 10 mm ball machine. I made custom parts that were 3D printed on an Ender 3 Pro and sliced on Cura. I assembled the parts and made design modifications along the way for it to be functional in the end.
skills: 
  - CAD Modeling
  - SolidWorks
  - DFM/DFA
  - Rapid Prototyping 
  - FDM 3D Printing
  - Testing
  - Problem Solving

main-image: /IMG_20260417_181133052_30percent.jpg
---

---
# Header 1 
Used for the title (already generated automatically at the top)
## Header 2  
Use this for the header of each section
### Header 3 
Use this to have subsection if needed


## Embedding images 
### Internal images
{% include image-gallery.html images="Project 1/images/IMG_20260417_181133052_30percent.jpg" height="400" %}
{% include image-gallery.html images="Project 1/images/IMG-20260417-181133052-30percent.jpg" height="400" %}

### Embed images
{% include image-gallery.html images="project2.jpg" height="400" %} 
place the images in project folder/images then update the file path.   


## Embedding youtube video
The second video has the autoplay on. copy and paste the 11-digit id found in the url link. <br>
*Example* : https://www.youtube.com/watch?v={**MhVw-MHGv4s**}&ab_channel=engineerguy
{% include youtube-video.html id="6mobO4Vh4Ao" autoplay= "false"%}

you can also set up custom size by specifying the width (the aspect ratio has been set to 16/9). The default size is 560 pixels x 315 pixels.  

The width of the video below. Regardless of initial width, all the videos is responsive and will fit within the smaller screen.
{% include youtube-video.html id="tGCdLEQzde0" autoplay = "false" width= "900px" %}  

<br>

## Adding a hozontal line
---

## Starting a new line
leave two spaces "  " at the end or enter <br>

## Adding bold text
this is how you input **bold text**

## Adding italic text
Italicized text is the *cat's meow*.

## Adding ordered list
1. First item
2. Second item
3. Third item
4. Fourth item

## Adding unordered list
- First item
- Second item
- Third item
- Fourth item

## Adding code block
```ruby
def hello_world
  puts "Hello, World!"
end
```

```python
def start()
  print("time to start!")
```

```javascript
let x = 1;
if (x === 1) {
  let x = 2;
  console.log(x);
}
console.log(x);

```

## Adding external links
[Wikipedia](https://en.wikipedia.org)


## Adding block quote
> A blockquote would look great if you need to highlight something


## Adding table 

| Header 1 | Header 2 |
|----------|----------|
| Row 1, Col 1 | Row 1, Col 2 |
| Row 2, Col 1 | Row 2, Col 2 |

make sure to leave aline betwen the table and the header


