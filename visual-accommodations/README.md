# ![Intro to Accessibility - Visual Accommodations](./assets/hero.png)



**Learning objective:** By the end of this lesson, students will be familiar with the practices we can implement to provide accommodations to people with visual disabilities.

## What are visual disabilities?

Visual disabilities can include blindness, low vision, and color blindness. People with visual disabilities may have difficulty seeing or distinguishing between colors.

## Accommodating visual disabilities

We can use these techniques to accommodate visual disabilities:

- Provide alt text for images so that people who use screen readers can understand what the images communicate.
- Use high-contrast colors between text and background to make text easier to read.
- Avoid the use of color alone to convey information.

## Alt text

Alt text is a short image description that screen readers can parse. Providing alt text for all images, including decorative images such as logos or icons, is vital.

Writing good alt text is difficult for many reasons, but primarily because alt text tries to capture what is important about an image in writing. However, the important elements in an image can change depending on the context in which the image is used. Sometimes, you won't know the context in which an image will be used; that's okay.

Although all of these won't apply in all conditions, here are some tips for writing good alt text:

- **Be concise.** The alt text should be as short as possible but still descriptive enough to convey the image's meaning.
- **Avoid using words like image or photo.** Screen readers will already announce that the content is an image.
- **Be specific.** If the image contains text, the alt text should include it if it is relevant to the context in which the image is presented.
- **Be consistent.** Use the same alt text for the same image wherever it appears on your website unless the context in which the image is used calls for deviation.
- **Convey emotion.** Is there an emotional meaning behind an image? Is something dramatic or exciting happening in an image? Your alt text should try to capture that emotion if it's relevant.

For more info, [this video from Google](https://www.youtube.com/watch?v=flf2vS0IoRs) does a great job explaining how to write good alt text.

### How to add alt text to an image

You can add alt text to an image by adding the `alt` attribute inside of an `<img>` element, as shown below:

```HTML
<img src="./image-source" alt="Add alt text here!">
```

### 🧠 You Do

![A stylized illustration of a black cat and a white cat on a bold red couch against a minimalist dark background.](./assets/alt-text.png)

Given the above image, without any context, we might write alt text like this:

A stylized illustration of a black cat and a white cat on a bold red couch against a minimalist dark background.

For this activity, you will rewrite the alt text for the above image so that it is more applicable for use in these contexts:

1. The image appears below the headline: ***Cats return to owner after being missing for eight years***.
2. The image is used on an auction site selling furniture.

You will have two different sets of alt text after this activity.

## Color contrast

![Two elements shown, one has low contrast between the off-white background and the white foreground text. Another has high contrast between the blue background and white foreground text.](./assets/contrast.png)

Color contrast is the difference between the brightness of two colors. High color contrast makes text and images easier to read and comprehend. 

The [W3C](https://en.wikipedia.org/wiki/World_Wide_Web_Consortium) publishes the [Web Content Accessibility Guidelines (WCAG)](https://en.wikipedia.org/wiki/Web_Content_Accessibility_Guidelines), which companies and governments often reference to help implement them implement accessibility standards on the web. One of the areas they set standards for is color contrast.

### WCAG color contrast requirements

WCAG 2.0 level AA (the easiest to meet requirement) specifies a minimum color contrast ratio of 4.5:1 for normal text and 3:1 for large text (24px or larger). There are many online tools to check the contrast between two colors. Governments around the world use these guidelines to evaluate sufficient color accessibility. [This contrast checker](https://webaim.org/resources/contrastchecker/) built by WebAIM is one the most popular ways to compare the contrast directly between two colors. Both [Chrome](https://developer.chrome.com/docs/devtools/accessibility/contrast/) and [Firefox](https://firefox-source-docs.mozilla.org/devtools-user/accessibility_inspector/) have built-in dev tools to evaluate a website and flag any inaccessible text found on it as well.

There is a recurring theme when implementing accessible content: simpler is almost always better. Black text on a white background or white text on a black background will always meet these contrast requirements. That said, you're not restricted from doing something unique. Just ensure it meets the guidelines.

### 🧠 You Do

Add this HTML inside the `<body>`:

```html
<button id="btn">Click me!</button>
```

And this CSS to your CSS file:

```css
#btn {
  background-color: #EFEFEF;
  color: #FFFFFF;
  font-size: 20px;
  padding: 8px 16px;
}
```

Alter the CSS for the button to meet the WCAG 2.0 level AA color contrast requirements.  

If you don't have an eye for color, that's fine! Here are a few cool resources you can explore to help out:

- [Adobe Color](https://color.adobe.com/create/color-wheel)
- [Coolors](https://coolors.co/generate)
- [ColorSpace](https://mycolor.space/)

Don't forget you can also opt for a simpler color palette.

## Conveying meaning without color

While color can help signal preferred actions or potential danger to users, we can't rely on it as the only indicator. 

Take links, for example. Links have different colors associated with them, but they're also typically underlined. This underlining helps people with blue/black and purple/black color blindness still distinguish between regular text and links.

Beyond this, underlined links are a widespread and clear pattern used across the internet. By adhering to this design, your users will immediately recognize how to navigate your site, even if they've never visited it.
