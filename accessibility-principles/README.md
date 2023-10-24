# ![Intro to Accessibility - Accessibility Principles](./assets/hero.png)

**Learning objective:** By the end of this lesson, students will be familiar with the four accessibility principles: perceivable, operable, understandable, and robust.

There are [four main accessibility principles](https://www.boia.org/blog/what-are-the-four-major-categories-of-accessibility): perceivable, operable, understandable, and robust.

## Perceivable

Information and user interface components must be presented so all users can perceive them. For example, text must be large enough to be read, and images must have alt text for users who are blind.

### Text alternatives

We can make our apps perceivable with text alternatives like:

- **Image alt text:** A short image description, that screen readers can parse. For example, instead of using the alt text "image of a cat," you could use the alt text "a black cat sitting on a red couch."
- **Video captions:** Text that displays the audio content of a video. Captions are essential for users who are deaf or hard of hearing.
- **Audio transcripts:** Written versions of the audio content of an audio recording. Transcripts benefit users who are deaf or hard of hearing, and users who prefer to read text rather than listen to audio.
- **Chart descriptions:** Text descriptions of the data in a chart or graph. Chart descriptions help users to understand the data, even if they cannot see the chart or graph.
- **Icon labels:** Text that describes the purpose of an icon. Icon labels are helpful for users who are blind, have low vision, or are unfamiliar with the icon.

### Design for adaptability

Our content should be presented differently without losing any important information or structure. This is important for people with disabilities, as well as people who are using different devices.

We can make our app adaptable by:

- Using responsive design. This will ensure that our website looks good and functions well on all devices, regardless of screen size.
- Breaking up our text into smaller paragraphs and use headings and subheadings to organize our content. This will make our content easier to read and scan.
- Using images and videos to illustrate our points. However, we should provide alternative text for images and video captions so that people with disabilities can still access our content.
- Allowing users to increase the font size of our text. This is helpful for people with low vision and other disabilities that make it difficult to read small text.

tktk hunter -- asset of breaking up text into smaller paragraphs or a side-by-side of a paragraph with or without an image to illustrate.

## Operable

 User interface components and controls must be operable by all users. For example, all functions must be accessible to users who cannot use a mouse.

### Keyboard accessible

We can ensure that all of the features and functions of our website can be used with a keyboard only.

Not everyone can use a mouse or other pointing device, and even people who use a mouse may prefer a keyboard for navigation and interaction. By making our website keyboard accessible, we can ensure that everyone can use and enjoy our website, regardless of their abilities.

### Prevent seizures / physical reactions

We should avoid designing content that could trigger seizures or other physical reactions in our users.

Some people, especially those with epilepsy or other photosensitive conditions, can be triggered by flashing lights, flickering images, or patterns. By being mindful of how we design our content, we can ensure everyone can safely use and enjoy our website.

Here are some tips for avoiding triggering seizures or other physical reactions in our users:

- Avoid using flashing lights, flickering images, or certain patterns in our content.
- If we must use flashing lights or flickering images, ensure they do not flash more than three times per second and are not too bright.
- Provide a way for users to turn off flashing lights and flickering images if necessary.


### Input modalities

We can make it easier for users to interact with our website using different methods, such as a mouse, touchscreen, or voice commands.

Not everyone can use a keyboard; even people who use a keyboard may prefer other input methods, such as a touchscreen on a mobile device.

To support different input modalities, we can:

- Use clear and consistent labels for all interactive elements. This will help users understand what each element does and how to interact with it, regardless of how they interact with the website.
- Make sure that all interactive elements are large enough and have enough space between them so that they are easy to tap or click. This is especially important for users with touchscreens or who struggle with fine motor control.
- Consider adding support for voice commands. This will allow users to interact with the website using their voices, which can be helpful for people with disabilities or people using their hands for other tasks.

## Understandable

Information and the operation of user interface components must be understandable. For example, instructions must be clear and concise.

### Readable

We can ensure that the text content on our website is easy to read and understand for everyone.

People have different reading abilities, and poorly formatted or written text is difficult for anyone to understand.

We can make our apps more readable by:

- Using clear and concise language. Avoid using jargon or technical terms that our audience may not understand.
- Using a readable font size and line height. Avoid using fonts that are too small or too much line spacing.
- Using high-contrast colors for our text and background.
- Avoid using all caps or italics for large blocks of text.

### Predictable

Our websites should be designed to appear and behave in a way that users can expect. 

By doing so, we enable users to learn how to use and navigate our site quickly and easily. This is also less frustrating and confusing for them.

Doing the following can help us make our sites predictable:

-  Using a consistent layout and design throughout our website. This will help users learn where to find things and understand how our website works.
-  Using clear and consistent labels for all interactive elements. This will help users to understand what each element does and how to interact with it.
-  Ensuring that all interactive elements behave predictably. For example, when a user clicks a button, they should expect something to happen, such as the page changing or a new window opening.
-  Avoid using unexpected or confusing elements on our website. For example, we should avoid hidden menus or pop-up ads that may startle or annoy users.

### Input assistance

We can design our sites to help users avoid and correct mistakes when they enter information.

Having to re-enter information because of a small typo is super frustrating. We can design our sites to be more forgiving of mistakes, creating a more user-friendly experience.

We can help users avoid and correct mistakes on our website by:

- Validating input as it is being entered. This will allow users to correct mistakes immediately without submitting the form and start over.
- Providing feedback to users when they make a mistake. This feedback should be clear and concise and explain what the user did wrong and how to fix it.
- Allowing users to go back and correct their mistakes easily. For example, we should provide a "Back" button on all forms.

## Robust

Content must be robust enough to be interpreted reliably by users, including the assistive technologies they may use. For example, content should be coded to allow screen readers to access it.

### Compatible

We can design our website to be compatible with as many different browsers and assistive technologies as possible, both now and in the future.

There are a lot of different browsers and accessibility technologies out there, as well as user preference settings within a browser to consider. We can ensure everyone can access and use our content by making our website compatible with a wide range of user agents.

We can achieve browser compatibility by:

- Using valid HTML and CSS code. This will help to ensure that our website is rendered correctly in all browsers.
- Avoiding proprietary browser features. If we must use proprietary features, we should provide alternatives for users with browsers that do not support those features.
- Testing our website with a variety of different browsers and assistive technologies. This will help us to identify and fix any compatibility issues.

And we can achieve assistive technology compatibility by:

- Providing text alternatives for all images and other non-text content. This will allow users who are using screen readers or other assistive technologies to access and understand our content.
- Using semantic HTML elements to mark up our content. This will help assistive technologies understand the structure and meaning of our content.
- Avoid using CAPTCHAs and other forms of authentication that are not accessible to users with disabilities.
