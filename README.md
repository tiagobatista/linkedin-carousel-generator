# linkedin-carousel-generator

For LinkedIn, the carousel can in in any of the following formats: Powerpoint (PPT or PPTX), Word Document (DOC or DOCX) or Portable Document Format (PDF). We’re going to focus on PDF.

So this challenge is to build a software tool that allows a user to create a carousel that they can use on a LinkedIn post. Though you don’t have to use it for that - you could use it to generate handouts for your next tech talk - it’s essentially going to build a PDF document.

Step Zero

In this step you decide which programming language and IDE you’re going to use and you get yourself setup with a nice new project.

Step 1

In this step your goal is to allow the user to preview a slide with some text on it. So that means the user should be presented with a GUI that shows a slide preview and a text box. When the test is updated the slide preview is updated.

LinkedIn supports multiple sizes, with a common size being the 1080 x 1080 pixel square. The max supported is 4320 x 4320 pixels. For this challenge we will stick to a 1080 x 1080 square which will make it feasible to offer a full sized preview on most screens.

So your GUI looks something like this:

![img1](https://substackcdn.com/image/fetch/w_1456,c_limit,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fccfae61a-f132-47dd-b821-2b07485ab807_372x433.png)

Step 2

In this step your goal is to be able to add a profile image, which will be shown in the top left hand corner and their name that can be shown beneath it.

To do that you’ll need to add the ability to upload an image as well as to specify their name/handle. Once you’ve don that you should have a GUI something like this (feel free to make it a better UX):

![img2](https://substackcdn.com/image/fetch/w_1456,c_limit,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Ffa700d71-75cd-4fc7-823b-6b33b19f01a9_359x536.png)

Step 3

In this step your goal is to set the background and foreground colour as well as the font face and size. These will affect all the slides.

![img3](https://substackcdn.com/image/fetch/w_1456,c_limit,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fc6deaa49-75c1-42c6-b4e1-a615bbb95fbe_374x666.png)

Step 4

In this step your goal is to be able to add a slide and navigate through the slides, with the preview and edit options for the text on each slide.

![img4](https://substackcdn.com/image/fetch/w_1456,c_limit,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F451d3cb3-ee55-4623-a00a-dd38a5896cb0_496x674.png)

Step 5

In this step your goal is to add an image as the background of an individual slide, a high level of transparency is a good idea (or go one step further and make it configurable).

![img5](https://substackcdn.com/image/fetch/w_1456,c_limit,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F0cce1367-2154-4c4c-bd21-98066c7c90fc_472x732.png)

Step 6

In this step your goal is to export the carousel as a PDF. The PDF should have one page per slide, reflecting the font, color, content and background image added for each slide.

Going Further

You can take this further and add support for PowerPoint and other formats. You could also integrate with the LinkedIn API to post it.
