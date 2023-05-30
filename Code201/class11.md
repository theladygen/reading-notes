# Class 11

## Reading

### [Video and Audio Content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)

1.**Explain how the ability to use video and audio on the web has evolved since the early 2000s.**

The first influx of online videos and audio were made possible by proprietary plugin-based technologies like Flash and Silverlight. Both of these had security and accessibility issues, and are now obsolete, in favor of native HTML solutions \<video> and \<audio> elements and the availability of JavaScript APIs for controlling them.

2.**Describe the use of the `src` and `controls` attributes in the \<video> element.**

In the same way as for the \<img> element, the `src` (source) attribute contains a path to the video you want to embed. It works in exactly the same way. Users must be able to control video and audio playback (it's especially critical for people who have epilepsy.) You must either use the controls attribute to include the browser's own control interface, or build your interface using the appropriate JavaScript API. At a minimum, the interface must include a way to start and stop the media, and to adjust the volume.

3.**Why is it important to have fallback content inside the \<video> element?**

This is called fallback content — this will be displayed if the browser accessing the page doesn't support the \<video> element, allowing us to provide a fallback for older browsers. This can be anything you like; in this case, we've provided a direct link to the video file, so the user can at least access it some way regardless of what browser they are using.

4.**Write a very short story where \<audio> and \<video> are characters.**

\<audio> and \<video> were best friends. When they were young they were a bit erratic. You could say they relied on specific plugin "pals" that were unreliable. However, as they grew up they discovered more accessible friends to help them do their jobs, and they are much more dependable now.

### [A Complete Guide To Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

1.**How does Grid layout differ from Flex?**

CSS Grid Layout (aka “Grid” or “CSS Grid”), is a two-dimensional grid-based layout system that, compared to any web layout system of the past, completely changes the way we design user interfaces. CSS has always been used to layout our web pages, but it’s never done a very good job of it. First, we used tables, then floats, positioning and inline-block, but all of these methods were essentially hacks and left out a lot of important functionality (vertical centering, for instance). Flexbox is also a very great layout tool, but its one-directional flow has different use cases — and they actually work together quite well! Grid is the very first CSS module created specifically to solve the layout problems we’ve all been hacking our way around for as long as we’ve been making websites.

2.**Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.**

Grid container is the element on which display: grid is applied. It’s the direct parent of all the grid items. Grid item is the children (i.e. direct descendants) of the grid container. Grid line is the dividing lines that make up the structure of the grid. They can be either vertical (“column grid lines”) or horizontal (“row grid lines”) and reside on either side of a row or column.

### [Responsive Images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

1.**Besides making a site visually appealing across different screen sizes, why should developers make images responsive?**

Responsive images help improve performance across different devices, making sites more easy to understand, view, and utilize.

2.**Define the following \<img> attributes `srcset` and `sizes`.Write an example of how they are used.**

The standard \<img> element traditionally only lets you point the browser to a single source file. The attributes `srcset` and `sizes` can be used to provide several additional source images along with hints to help the browser pick the right one.

3.**How is `srcset` more helpful for responsive images than CSS or JavaScript?**

The `srcset` attributes contain the path to the image to display with multiple images referenced, as well as a sizes attribute. So, you could offer multiple images via a \<picture> element, but then also offer multiple resolutions of each one. We use `srcset/sizes` to create a resolution switcher example, either to serve the same size image at different resolutions depending on the device resolution or to serve different image sizes depending on the viewport widths.

## Bookmark and Review

### [Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)

* This article is review from Class 05.

### [Other Embedding Technologies](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Other_embedding_technologies)

## Things I Want to Know More About

I want to re-read and explore this section further.

### ***Answers to questions were found researching and using the sources linked above each section***

[CF Reading Journal Home](../README.md)
