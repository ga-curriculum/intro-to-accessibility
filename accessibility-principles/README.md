# Intro to Accessibility - Accessibility Principles

![Hero image](./assets/hero.png)

**Learning objective:** By the end of this lesson, students will be familiar with the four accessibility principles: perceivable, operable, understandable, and robust.

There are [four main accessibility principles](https://www.boia.org/blog/what-are-the-four-major-categories-of-accessibility): **perceivable, operable, understandable, robust.**

## Perceivable

Information and user interface components must be presented in a way that can be perceived by all users. For example, text must be large enough to be read and images must have alt text for users who are blind.

### Text alternatives
We can make our apps *perceivable* with text alternatives like:
- **Image alt text**: A short description of an image, which can be read by screen readers. For example, instead of using the alt text "image of a cat," you could use the alt text "a black cat sitting on a red couch."
- **Video captions**: Text that displays the audio content of a video. Captions are essential for users who are deaf or hard of hearing.
- **Audio transcripts**: A written version of the audio content of an audio recording. Transcripts are beneficial for users who are deaf or hard of hearing, as well as users who prefer to read text rather than listen to audio.
- **Chart descriptions**: A textual description of the data in a chart or graph. Chart descriptions help users to understand the data, even if they cannot see the chart or graph.
- **Icon labels**: Text that describes the purpose of an icon. Icon labels are helpful for users who are blind or have low vision, as well as users who are not familiar with the icon.

tktk hunter -- some relevant asset for icon labels or something that we haven't done in the concepts section already

### Design for adaptability
Our content should be able to be presented in different ways without losing any important information or structure. This is important for people with disabilities, as well as people who are using different devices.

We can make our app adaptable by:
- **Using responsive design.** This will ensure that our website looks good and functions well on all devices, regardless of screen size.
- **Breaking up our text into smaller paragraphs and use headings and subheadings to organize our content.** This will make our content easier to read and scan.
- **Using images and videos to illustrate our points.** However, we should be sure to provide alternative text for images and captions for videos so that people with disabilities can still access our content.
- **Allowing users to increase the font size of our text.** This is helpful for people with low vision and other disabilities that make it difficult to read small text.

tktk hunter -- asset of breaking up text into smaller paragraphs, or a side by side of a paragraph with or without an image to illustrate.


## Operable

 User interface components and controls must be operable by all users. For example, all functions must be accessible to users who cannot use a mouse.

### Keyboard accessible
We can ensure that all of the features and functions of our website can be used with a keyboard only.

Not everyone can use a mouse or other pointing device, and even people who can use a mouse may prefer to use a keyboard for navigation and interaction. By making our website keyboard accessible, we can ensure that everyone can use and enjoy our website, regardless of their abilities.

### Prevent seizures / physical reactions
We should avoid designing content in a way that could trigger seizures or other physical reactions in our users.

Some people, especially those with epilepsy or other photosensitive conditions, can be triggered by flashing lights, flickering images, or certain patterns. By being mindful of how we design our content, we can help to ensure that everyone can use and enjoy our website safely.

Here are some tips for avoiding triggering seizures or other physical reactions in our users:

- Avoid using flashing lights, flickering images, or certain patterns in our content.
- If we must use flashing lights or flickering images, make sure that they do not flash more than three times per second and that they are not too bright.
- Provide a way for users to disable flashing lights and flickering images if they need to.


### Input modalities
 We can make it easier for users to interact with our website using different methods, such as a mouse, touchscreen, or voice commands.

Not everyone can use a keyboard, and even people who can use a keyboard may prefer to use other input methods, such as a touchscreen on a mobile device.

To support different input modalities, we can:
- Use clear and consistent labels for all interactive elements. This will help users to understand what each element does and how to interact with it, regardless of how they are interacting with the website.
- Make sure that all interactive elements are large enough and have enough space between them so that they are easy to tap or click. This is especially important for users who are using touchscreens or who have difficulty with fine motor control.
- Consider adding support for voice commands. This will allow users to interact with the website using their voices, which can be helpful for people with disabilities or people who are using their hands for other tasks.


## Understandable

Information and the operation of user interface components must be understandable. For example, instructions must be clear and concise.

### Readable 
We can ensure that the text content on our website is easy to read and understand for everyone.

People have different reading abilities, and poorly formated or written text is difficult for *anyone* to understand.

We can make our apps more readable by:
- Using clear and concise language. Avoid using jargon or technical terms that our audience may not understand.
- Using a readable font size and line height. Avoid using too small of a font size or too much line spacing.
- Using high-contrast colors for our text and background.
- Avoid using all caps or italics for large blocks of text.

### Predictable
Our websites should be designed so they appear and behave in a way that users can expect. 

By doing so, we enable users to learn how to use and navigate our site quickly and easily. This is also less frustrating and confusing for them.

Doing the following can help us make our sites predictable:
-  Using a consistent layout and design throughout our website. This will help users to learn where to find things and to understand how our website works.
-  Using clear and consistent labels for all interactive elements. This will help users to understand what each element does and how to interact with it.
-  Ensuring that all interactive elements behave in a predictable way. For example, when a user clicks on a button, they should expect something to happen, such as the page changing or a new window opening.
-  Avoid using unexpected or confusing elements on our website. For example, we should avoid using hidden menus or pop-up ads that may startle or annoy users.

### Input assistance
We can design our sites to help users avoid and correct mistakes when they enter information.

Let's face it, everyone makes mistakes, and having to re-enter information because of a small typo is super frustrating. We can design our sites to be more forgiving of mistakes, however, which will create a more user-friendly experience.

We can help users avoid and correct mistakes on our website by:
- Validating input as it is being entered. This will allow users to correct mistakes immediately, without having to submit the form and then start over.
- Providing feedback to users when they make a mistake. This feedback should be clear and concise, and it should explain what the user did wrong and how to fix it.
- Allowing users to easily go back and correct their mistakes. For example, we should provide a "Back" button on all forms.

## Robust

Content must be robust enough to be interpreted reliably by a wide variety of user agents, including assistive technologies. For example, content should be coded in a way that allows screen readers to access it.

### Compatible
We can design our website to be compatible with as many different browsers and assistive technologies as possible, both now and in the future.

There are a lot of different browsers and accessibility technologies out there, as well as user preference settings within a browser to consider. By making our website compatible with a wide range of user agents, we can ensure that everyone can access and use our content.

We can achieve browser compatibility by:
- Using valid HTML and CSS code. This will help to ensure that our website is rendered correctly in all browsers.
- Avoiding proprietary browser features. If we must use proprietary features, we should provide alternatives for users who are using browsers that do not support those features.
- Testing our website with a variety of different browsers and assistive technologies. This will help us to identify and fix any compatibility issues.

And we can achieve assistive technology compatibility by:
- Providing text alternatives for all images and other non-text content. This will allow users who are using screen readers or other assistive technologies to access and understand our content.
- Using semantic HTML elements to mark up our content. This will help assistive technologies to understand the structure and meaning of our content.
- Avoid using CAPTCHAs and other forms of authentication that are not accessible to users with disabilities.