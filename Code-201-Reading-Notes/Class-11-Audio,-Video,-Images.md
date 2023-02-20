# Audio Video Images

## Video and Audio Content

In the early 2000s the main way of getting video and audio on websites were third party programs like flash and silverlight. These programs came with problems however like security and accessibility issues. They have now been phased out by newer techniques like the < video > and < audio > tag that lets you put the video straight into the websites html.

In the "video" element the src attribute is used to link the the video itself the the site, the same way it's used in < img > tags. The "control" atribute is used to add a control interface to the video.

It important to have fallback content inside the video tag because it allows you to write backup text if the browser doesn't support the video. This can include a link to the video source or a discription of the video.

Example Story: Once there was a man named Video and a woman named Audia. They loved eachother very much and wanted to live together. But unfortunately for them, a rich landlord named ***Flash*** bought all the houses in the area and charged high prices for rent. Audia and Video really wanted to be together but with Flash decreasing the acsessibility of houses, they had to put restrictions on their relationship. One day, the mayor of the town, HTML, say this injustice and decided to put a stop to it. Mayor HTML bought all the houses in the town and removed rent. Now Video and Audia can live freely in the HTML.

## Grid

Grid is a new CSS method. It has multidirectional flow unlike flex. It's used to move content around the page. The grid container is the parent element an the grid items are it's children. The grid lines are the rows and coloums that make up the structure of the grid.

## Responsive Images

Devolopers should make images responsive because almost every one uses mobile phones so if you code an image on a website, it's likley gonna be viewed on phone screen. The image needs to be responsive to look good acros devices.

The img attribute srcset can be used to link to multiple images, depending on the device, and the sizes attribute selects which browser requirements would be best for which image.

Using srcset is more useful than doing it in CSS or Javascrip because when the browser starts to load a page, it starts to preload images before the the CSS and JS links. Having the controls be in th HTML page makes it faster and more responsive.
