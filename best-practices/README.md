# Intro to Accessibility - Best Practices

![Hero image](./assets/hero.png)

**Learning objective:** By the end of this lesson, students understand best practices for accessibility, such as using alt text and ensuring adequate color contrast.

## Alt text

Alt text is a text description of an image that is displayed to users who cannot see the image. It is important to provide alt text for all images, including decorative images.

Tips for writing good **alt text**. 

- **Be descriptive**. The alt text should describe what the image is, not just what it looks like.
- **Be concise**. The alt text should be as short as possible, but it should still be descriptive enough to convey the meaning of the image.
- **Avoid using words like "image" or "photo."** Screen readers will already announce that the content is an image.
- **Be specific**. If the image contains text, the alt text should include the text.
- **Be consistent**. Use the same alt text for the same image wherever it appears on your website.

Here is an example of good alt text:

tktk hunter -- asset of a A black and white cat sitting on a red couch. or whatever you want, just change the alt text accordingly plz

image: cat sitting on couch
**Alt text**: A black and white cat sitting on a red couch. 

How to use alt text:

```html
<img src="https://example.com/image.jpg" alt="A black and white cat sitting on a red couch." />
```
The `alt` attribute contains the alt text for the image. This text will be displayed to users who cannot see the image.

## Color Contrast

Color contrast is the difference between the brightness of two colors. High color contrast makes text and images easier to read and comprehend.

### WCAG 2.1 color contrast requirements
The Web Content Accessibility Guidelines (WCAG) 2.1 require a minimum color contrast ratio of 4.5:1 for large text and 3:1 for small text. This means that the text should be at least 4.5 times brighter than the background for large text and at least 3 times brighter than the background for small text.

### How to test color contrast
There are a number of tools available online that you can use to test the color contrast of your website. One popular tool is the [WAVE Web Accessibility Evaluation Tool](https://wave.webaim.org/report#/https://www.boia.org/blog/what-are-the-four-major-categories-of-accessibility). You can also test two colors directly using the [WebAIM contrast checker](https://webaim.org/resources/contrastchecker/).