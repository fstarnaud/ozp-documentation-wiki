
OZONE Platform, developed as a government project, must accommodate all 508 disability requirements as required by federal law. In order to accommodate, some general purpose guidelines will be defined, and must be tested for release as part of the program lifecycle.

### Section 508 Refresh

The US Access Board is in the process of updating the Section 508 requirements and, according to estimates, should be finalizing the new requirements at the end of 2015. Once the changes come into effect, the US Access Board will require compliance with the World Wide Web Consortium (W3C) Web Content Accessibility Guidelines (WCAG) 2.0 rather than trying to maintain their own unique set of standards. WCAG 2.0 Level AA will be the minimum to comply with Section 508 once the new standards come into effect.

### ARIA

W3C has also created a development language supplement called Web Accessibility Initiative (WAI) Accessible Rich Internet Applications (ARIA) Suite. It helps to identify and describe elements and how they relate to each other. This is a framework for adding attributes to complex applications that would otherwise be inaccessible because the native development language doesn't have certain capabilities. This enables technologies that have been inaccessible in the past to communicate more effectively with screen readers and other assistive technology devices. However, you don't need to double up. For example, if you are using an <`h1`> tag, there is **no** need to use ARIA to define the object's role as "heading". ARIA is only a supplement to help if a development language can't support identifying or describing elements in the application.

### OZONE-specific Guidelines for 508 Compliance
1. OZONE makes use of rendering technology designed to allow users to mashup web applications together in a common view. As a result, we can only supply 508 compliance to the iframe boundary, and not beyond.
2. The webtop renderer should consist of ARIA/metatags designed to allow screen readers to read which applications are open.
3. Keyboard navigation should exist for every function within the system, regardless of what it is. Being able to navigate between windows or applications, configuration, and stateful actions should have a defining keystroke matching with common standards (see GSA guidelines for software).
4. All images being presented to the browser, via direct HTML ```<img>``` tags or CSS, must present descriptive text.
5. All buttons and form elements must be presented with common descriptive text and labels.

### Reference Material
####Current Section 508
1. U.S. Government page on [federal 508 disability compliance requirements](https://www.section508.gov/)
2. Section 508 [reference manual](https://www.section508.gov/archive-section508-reference)
3. U.S. General Service Administration (GSA) [Guidance for Software Applications and Operating Systems](http://www.gsa.gov/graphics/staffoffices/508softwareandos.doc)

####WCAG 2.0 (Section 508 Refresh)
4. [Web Content Accessibility Guidelines (WCAG) Overview](http://www.w3.org/WAI/intro/wcag "Web Content Accessibility Guidelines Overview")
5. [WCAG 2.0 Checklist](http://www.w3.org/TR/2006/WD-WCAG20-20060427/appendixB.html "WCAG 2.0 Checklist")
6. [How to Meet WCAG 2.0](http://www.w3.org/WAI/WCAG20/quickref/ "How to Meet WCAG 2.0")

####ARIA
7. [What is WAI-ARIA, what does it do for me, and what not?](http://www.marcozehe.de/2014/03/27/what-is-wai-aria-what-does-it-do-for-me-and-what-not/ "What is WAI-ARIA, what does it do for me, and what not?")
8. [Mozilla Developer Network – ARIA resource area](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA "Mozilla Developer Network – ARIA resource area")
9. [Accessible Rich Internet Applications (WAI-ARIA) 1.0 Standards](http://www.w3.org/WAI/PF/aria/ "	Accessible Rich Internet Applications 1.0")

###Labeling Form Controls and Interactive Elements
Accessible labels are necessary to make several other types of elements understandable, such as inputs, widgets, and ARIA landmark regions. Accessible labels that create a delightful experience are:

1. Concise -- 1 to 3 simple words. Only occasionally as many as 5 words.
2. Meaningful -- accurately convey the purpose of the element.

There are many ways to label an interactive element such as a button or an input field.

####Self-labeled

Some elements, like links and buttons with display text, label themselves. In this case, screen reader users and all other users can perceive the label.

1`<div>`
2  <button>Submit</button>
3`</div>`