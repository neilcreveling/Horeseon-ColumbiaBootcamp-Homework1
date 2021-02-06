# Horeseon-ColumbiaBootcamp-Homework1
Accessibility is crucial for any company's web page. Companies are legally required to ensure users with disabilities access to their websites. Meanwhile, accessibile web pages contain information that is more easily identifiable by search engines. In this task, I provided marketing agency Horiseon Social Solutions Services, Inc. with a refactored codebase that follows accessibility standards so that its website is optimized for search engines. During this process, I made additional alterations to improve semantics, eliminate redudancies, add comments, and clean-up the code to make future development for this website more efficient. Below are some more detailed descriptions of my improvements:

## Accessibility
To increase accessibility, my first goal was to keep search engine optimization in mind. Changing certain <div> elements into a descriptive and concise <title> element and giving dates a <time> element, for example, helps search engines and browsers identify what is displayed on the page by providing machine-readable information. Providing descriptive <alt> attributes to all images serves the same function, while also addressing accessibility issues regarding users with disabilities. 

## Semantics
The HTML found in this codebase was almost entirely composed of <div> elements, which are not specific and do not convey the underlying meaning of the web page. Therefore, I altered all of the <div> elements to reflect their individual purpose within the page. For example, I changed the main content of the page into an <article> element, the separate areas of text within the <article> as <section> elements, and the background image into a <figure> element. I also changed the names of certain classes, such as .hero into .background-image, so developers can better understand the purpose and meaning of the class upon reading the name.

## Redundancies
In many instances, this websites codebase possessed multiple id and class elements that were redundant and could be deleted. By either deleting id elements completely or taking multiple class elements and reducing them down to a single class element with a new concise name, the CSS became much more simple and easy to manipulate by any developer in the future if need be.

## Comments
For every change I made, I included a comment in both the HTML and CSS files so both I and future developers viewing the web page's code can clearly view my changes, my rationale, and the history of the refactoring process. If any issues are discovered, any questions arise, or future changes need to be made to alter certain aspects of the web page, I or other developers will easily be able to pinpoint where in the code to look. This includes an ample number of commits with descriptive comments found in the GitHub repository.

## Clean-up
I also provided some additional clean-up, such as making sure the HTML and the CSS were structurally in sync with one another, so the code could be easily followed and interpreted by myself or future developers.

## License
MIT License

Copyright (c) 2021 Neil Creveling

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
