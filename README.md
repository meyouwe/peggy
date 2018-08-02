# Peggy
An HTML page that loads JPEGs with the same base name as the document

## The problem
Unlike a lot of digital designers I donʻt use Sketch to design sites – I use Adobe InDesign. There are a few reasons for this. 

In order to get a real feel for the scale of the type, image, layout and how each page relates to each other I use InVision.

But for me, there is a stage before this that I want to quickly look at what these things look like. <!-- For me InVision is for close to first draft.--> I will output a JPEG and load it into the browser. This doesn't quite work though. Sometimes the browser will scale that image and if I have a number of pages I have will have to load each. This is annoying.

## The process
Name index.html the same as your InDesign file. For example, if your InDesign document is called website.indd, name the HTML document wesbite.html. Then I go to File/Export in InDesign and export all of your pages as JPEGs into the same folder as the HTML document. InDesign will naturally name all of your JPEGs website.jpg, website2.jpg, website3.jpg, etc...

Then all you need to do is load **website.html** in your browser. This will load the first image. Clicking anywhere on the right-hand side of the screen will go to the next image. Clicking anywhere on the left-hand side will take you to the previous image.

Check out the example folder for a working demo.