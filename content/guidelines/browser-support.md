---
layout: page
type: detail
title: Browser support
group: guidelines
path: /guidelines/browsers
status: Complete
description: Guidelines that explain which browsers the design system is optimized for
---
The Lightning Design System provides accessible markup which will serve as a foundation for your application development. In order to make sure you build accessible components, however, you will need to follow the accessibility guidance for our interactive components. This includes keyboard behavior as well as the management of ARIA roles and properties.

What is Accessibility?
----------------------

Web accessibility ensures that people with disabilities can perceive, understand, navigate, interact with, and contribute to the applications you create. This means that pages are [Perceivable, Operable, Understandable and Robust](https://www.w3.org/TR/WCAG20). This includes providing keyboard interaction alternatives for all mouse-based actions, properly identifying all form fields and buttons, providing text based alternatives for all images, videos, icons and SVGs, as well as building components that properly convey their identity, operation model, and state to assistive technologies.

The Design System enables accessible development by providing a set of semantically correct components, each with appropriate [ARIA](https://www.w3.org/TR/wai-aria) markup so they can be identified correctly to users of assistive technologies.

Standards Compliant Markup
--------------------------

The semantic markup and use of ARIA roles in our components are based on W3C standards and industry best practices. This markup is the perfect starting point for building accessible components.

Keyboard Navigation
-------------------

While we do not provide the JavaScript that is necessary to make our components interactive, in the [Accessibility Patterns](/accessibility/patterns/overview), we provide working examples of basic patterns with documentation on what interactions are required. There is also advice in the individual component’s documentation on how to create keyboard-accessible components.

Appropriate use of color
------------------------

Our components follow the two main rules of accessibility as it relates to color:

*   We never use color as the only means of providing information or requesting an action.
*   The combinations of text and their background colors do not fall below the [WCAG recommended threshold](https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-contrast.html) ratio of 4.5:1 for standard or small text and 3:1 for larger text.

Accessible Forms
----------------

Our forms offer proper use of `<fieldset>` and `<legend>` tags as well as appropriate labeling for input controls. Our radio button and checkbox controls provide a balanced solution that offers accessibility as well as design flexibility.

Images and icons
----------------

We provide a means of offering text-based alternatives for all images, icons and SVGs.

Component Identity
------------------

Our interactive components are created in accordance with the latest [ARIA Authoring Practices](http://w3c.github.io/aria-practices), with attributes that are understandable by screen reader users on key page elements. It is important to note that as a component is interacted with, the ARIA attributes may need updating to reflect the new state. Hence, we provided detailed guidance on how and when to do this.

Validating your applications
----------------------------

The Design System is only the foundation for accessible application development. We recommend that you review the accessibility of your applications before release and ensure that it meets the [WCAG Standard at the AA Level](https://www.w3.org/TR/WCAG20/#conformance).

Resources
---------

*   [Salesforce's accessibility blog posts](https://medium.com/salesforce-ux/tagged/accessibility)
*   [W3C Web Accessibility Initiative](https://www.w3.org/WAI)
*   [WAI-ARIA Authoring Practices](http://w3c.github.io/aria-practices)
*   [WebAIM](https://webaim.org/)
*   [The A11Y Project](https://a11yproject.com/)
*   [Are My Colours Accessible?](http://www.aremycoloursaccessible.com/)
*   [Salesforce Trailblazer Community: Disability Topics](https://success.salesforce.com/_ui/core/chatter/groups/GroupProfilePage?g=0F93A000000LfSVSA0)
