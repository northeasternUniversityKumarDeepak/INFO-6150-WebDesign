# Deepak Kumar's Portfolio

This is a portfolio website for Deepak Kumar, featuring various sections. Below are the features implemented in the HTML and Sass files, and descriptions of attributes used:

## HTML Pages

### `index.html`
- Header Section: Contains a navigation menu with links to different sections of the portfolio.
- About Me and Education: Information about Deepak's background and education.
- Experience: Details about Deepak's work experience with an unordered list.
- Skills: A list of skills categorized by languages, software/tools, Azure cloud services, and other skills.
- Certifications: Displays images of Deepak's certifications in a gallery.
- Audio and Video: Includes an audio and video section.
- Send Your Queries: A link to the "form.html" page.
- Contact Me: Provides contact information, including phone and email.
- Footer: Contains the copyright information and a "Scroll to top" link.

### `form.html`
- Header Section: Includes Deepak's name and job title.
- Contact Form: Allows users to submit queries with fields for name, email, and a message.
- Footer: Contains the copyright information and a "Scroll to top" link.

## CSS (Sass) Styles

### `styles.scss`
- Defines global styles for the body, headers, links, and more.
- Implements a header with navigation, ensuring links change color on hover.
- Sets the background image for the "resp_sec" section.
- Styles the "experience" section with a maximum height and overflow.
- Defines styles for images.

### `images.scss`
- Sets a fixed width and height for images.

### `flexbox.scss`
- Defines a placeholder selector `%flex_info` for reusable flexbox styling.
- Applies flex styles to the "skills" section.

### `cert_flex.scss`
- Sets styles for the "certifications" section and the image gallery.

### `utilities_extra.scss`
- Defines custom properties (CSS variables) for the primary and secondary colors.
- Extends placeholder selectors for contact info and buttons.
- Uses mixins for button styling and converting pixels to em units.
- Styles the "contact" and "footer" sections.

### `button.scss`
- Defines a placeholder selector `%list` for button styling.
- Implements button styles with hover effects.
- Defines styles for list items and image links.

### `utilities.scss`
- Styles the header container and its content.
- Implements a grid system for arranging elements.
- Styles the "about," "education," "education_header," "education_div1," and "education_div2" sections.
- Sets hover effects for images and video sections.
- Styles the "Send_your_queries" section.

## Custom Variables (config.scss)
- Sets custom variables for body color, header color, secondary color, font stack, and box shadow.
- Defines functions and mixins for setting text color and background.

## Implemented Features

### CSS Grid Layouts

1. **HTML Page: index.html**
   - **Header Section**: Grid layout for the header section is implemented using a CSS Grid.
   - **About and Education**: The section with About Me and Education content uses a CSS Grid layout.
   - **Education**: The section with Education content uses a CSS Grid layout.

### Flexbox Layouts

1. **HTML Page: index.html**
   - **Header Section**: The header section contains a navigation menu with Flexbox layout.
   - **Skills Section**: The Skills section uses Flexbox for organizing skills information.
   - **Certification Section**: The Certification section uses Flexbox for organizing certificates.

### SASS Features

#### Variables
1. **SASS File: config.scss**
   - Variables are defined for body and header colors, font stack, secondary color, and box shadow.

#### Custom Properties (CSS Variables)
1. **SASS File: utilities_extra.scss**
   - CSS custom properties (variables) are defined using `:root` for primary background color and text color.

#### Nesting
1. **SASS Files: styles.scss, utilities.scss, utilities_extra.scss**
   - Nesting is used extensively to define styles for different elements within their parent elements.

#### Interpolation
1. **SASS File: utilities_extra.scss**
   - Interpolation is used when defining text color within strings, e.g., `color: #{$primary-color};`.

#### Placeholder Selectors
1. **SASS File: utilities_extra.scss**
   - Placeholder selector `%contact-info` is defined and extended in other parts of the code.

#### Mixins
1. **SASS File: utilities_extra.scss**
   - A mixin named `button` is defined and used to style buttons with background and text colors.

#### Functions
1. **SASS File: utilities_extra.scss**
   - A SASS function `calculate-em` is used to convert pixel values to em units.
#### More SASS Features

##### Extending Selectors
1. **SASS Files: utilities.scss, cert_flex.scss, styles.scss**
   - The `@extend` directive is used to extend styles from one selector to another, improving code reusability.

##### Variables in Placeholder Selectors
1. **SASS File: utilities_extra.scss**
   - Variables are used within placeholder selectors for defining text color.

##### Pseudo-class and Pseudo-element Styling
1. **SASS Files: styles.scss, cert_flex.scss**
   - Pseudo-classes and pseudo-elements like `:hover` are used to style elements upon interaction.

##### Box Shadow and Hover Effects
1. **SASS Files: utilities.scss, styles.scss, cert_flex.scss**
   - Box shadow and hover effects are applied to elements to enhance visual appeal.

##### Grid and Flexbox Styling
1. **SASS Files: styles.scss, utilities.scss, cert_flex.scss**
   - Grid and Flexbox styling is consistently applied to create responsive layouts.


Note: The portfolio includes responsive design elements and hover effects for interactive user experiences.
