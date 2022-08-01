### Video and Audio Content

1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.
    - It evolved from using flash then to silverlight to now modern html5 with the use of audio and video tags that would allow users to inbed audio and video files. With the increase in bandwith allows us to use audio and videos in our webpages. 
2. Describe the use of the src and controls attributes in the <video> element.
    -   <video src="rabbit320.webm" controls>
        <p>Your browser doesn't support HTML5 video. Here is a <a href="rabbit320.webm">link to the video</a> instead.</p>
        </video>
            In the same way as for the <img> element, the src (source) attribute contains a path to the video you want to embed. It works in exactly the same way.
3. Why is it important to have fallback content inside the <video> element?
    -   Helps visitors see or understand content of  the webpage in case of the video or audio not properly functioning.
4. Write a very short story where <audio> and <video> are characters.
    -   Audio and Video where two such wonderful things that they wanted everyone to know who they were. 

### A Complete Guide To Grid

1. How does Grid layout differ from Flex?
    - Grid aligns content like a chart and flex is more loosely used. 
2. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.
    - Grid container is the container of all the grid items, 
    - Grid item Determines a grid item’s location within the grid by referring to specific grid lines. grid-column-start/grid-row-start is the line where the item begins, and grid-column-end/grid-row-end is the line where the item ends.

### Responsive Images

1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?
    - So the images they use on their pages can correctly be viewed based on users preferences. Such as tablets phones and etc. 
2. Define the following <img> attributes srcset and sizes. Write an example of how they are used.
    - <img srcset="elva-fairy-480w.jpg 480w,
             elva-fairy-800w.jpg 800w"
        sizes="(max-width: 600px) 480px,
            800px"
        src="elva-fairy-800w.jpg"
        alt="Elva dressed as a fairy">
        - srcset defines the set of images we will allow the browser to choose between, and what size each image is.
        - sizes defines a set of media conditions (e.g. screen widths) and indicates what image size would be best to choose, when certain media conditions are true
3. How is srcset more helpful for responsive images than CSS or JavaScript?
    - better helps the user see the image by letting the browser choose the appropriate size image. 

### Bookmark and Review
Images in HTML https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML
This article is review from Class 05.
Other Embedding Technologies https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Other_embedding_technologies