# Testing

> [!NOTE]  
> Return back to the [README.md](README.md) file.

## Code Validation

### HTML
I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

| Validator | File | Screenshot | Notes |
| --- | --- | --- | --- |
| [W3C Validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Flauren21717.github.io%2FMilestone_project_1%2F) | index.html | ![W3C Results - index.html](https://github.com/Lauren21717/Milestone_project_1/blob/main/assets/media/W3C%20Results%20-%20index.png?raw=true) | No errors found |
| [W3C Validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Flauren21717.github.io%2FMilestone_project_1%2Fabout.html) | about.html | ![W3C Results - about.html](https://github.com/Lauren21717/Milestone_project_1/blob/main/assets/media/W3C%20Validator%20-%20about.png?raw=true) | No errors found |
| [W3C Validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Flauren21717.github.io%2FMilestone_project_1%2Fclass.html) | class.html | ![W3C Results - class.html](https://github.com/Lauren21717/Milestone_project_1/blob/main/assets/media/W3C%20Validator%20-%20class.png?raw=true) | No errors found |
| [W3C Validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Flauren21717.github.io%2FMilestone_project_1%2Fjoin.html) | join.html | ![W3C Results - join.html](https://github.com/Lauren21717/Milestone_project_1/blob/main/assets/media/W3C%20Validator%20-%20join.png?raw=true) | No errors found |

### CSS
I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.

| Directory | File | Screenshot | Notes |
| --- | --- | --- | --- |
| assets | style.css | ![W3C Result - CSS](https://github.com/Lauren21717/Milestone_project_1/blob/main/assets/media/W3C%20Validator%20-%20CSS.png?raw=true) | No error on style.css file |

## Lighthouse Audit

I've tested my deployed project using the Lighthouse Audit tool to check for any major issues.

### Home

1. **Outcome of the Audit**
   ![Home Lighthouse Before](https://github.com/Lauren21717/Milestone_project_1/blob/main/assets/media/home-lighthouse-before.png?raw=true)

2. **Solution Applied**
   - **Serve images in next-gen formats**: I changed all images on the homepage from `jpeg` to `webp`.
   - **Background and foreground colors do not have a sufficient contrast ratio.**

   | Before | After |
   | --- | --- |
   | ![Button Before](https://github.com/Lauren21717/Milestone_project_1/blob/main/assets/media/btn-lg-before.png?raw=true) | ![Button After](https://github.com/Lauren21717/Milestone_project_1/blob/main/assets/media/btn-lg-after.png?raw=true) |
   | ![Feature Before](https://github.com/Lauren21717/Milestone_project_1/blob/main/assets/media/feature-lh-before.png?raw=true) | ![Feature After](https://github.com/Lauren21717/Milestone_project_1/blob/main/assets/media/feature-lh-after.png?raw=true) |
   | ![Location Before](https://github.com/Lauren21717/Milestone_project_1/blob/main/assets/media/Location-lh-before.png?raw=true) | ![Location After](https://github.com/Lauren21717/Milestone_project_1/blob/main/assets/media/Location-lh-after.png?raw=true) |

3. **The Final Outcome**
   ![Home Lighthouse After](https://github.com/Lauren21717/Infinite_Fitness/blob/main/assets/media/home-lighthouse-after.png?raw=true)


### About Page
   ![About Lighthouse](https://github.com/Lauren21717/Infinite_Fitness/blob/main/assets/media/about-lighthouse-after.png?raw=true)


### Class Page
   ![Class Lighthouse Before](https://github.com/Lauren21717/Milestone_project_1/blob/main/assets/media/class-lighthouse-before.png?raw=true)


### Join Now Page
   ![Join Now Lighthouse](https://github.com/Lauren21717/Milestone_project_1/blob/main/assets/media/join-now-lighthouse.png?raw=true)


## Responsiveness
   
- Screenshots of responsive design breakpoints for various devices.
- Viewport - Desktop: 1600x992px / Laptop: 1280x802px / Tablet: 768x1024px / Mobile: 320x480px.

    ![Responsive Screenshots - Home](https://github.com/Lauren21717/Milestone_project_1/blob/main/assets/images/Responsive%20Screenshots%20-%20Home.png?raw=true)
    ![Responsive Screenshots - About](https://github.com/Lauren21717/Milestone_project_1/blob/main/assets/media/Responsive%20Screenshots%20-%20About.png?raw=true)
    ![Responsive Screenshots - Class](https://github.com/Lauren21717/Milestone_project_1/blob/main/assets/media/Responsive%20Screenshots%20-%20Class.png?raw=true)
    ![Responsive Screenshots - Join Now](https://github.com/Lauren21717/Milestone_project_1/blob/main/assets/media/Responsive%20Screenshots%20-%20Join%20Now.png?raw=true)

## Manual Testing

### 1. Navigation Testing
- **Objective:** Ensure all navigation links and menus function correctly and navigate to the intended page.

### 2. Form Testing
- **Objective:** Test the forms to ensure they submit data correctly and display appropriate validation messages for any errors.

### 3. Content Testing
- **Objective:** Review all text content, images, and multimedia elements to ensure accuracy, relevance, and proper formatting.

### 4. Functionality Testing
- **Objective:** Test all interactive elements such as buttons, dropdowns, sliders, and accordions to ensure they perform their intended functions without errors.

### 5. Cross-Browser Testing
- **Objective:** Verify the compatibility of the website across different web browsers (e.g., Chrome, Firefox, Safari) to ensure consistent behavior and appearance.

**Issue Discovered:**
- The position of the callout section appeared differently across different browsers.
- **Before Fix:**
    - **Chrome Version 122.0.6261.111**
      ![Chrome testing before](https://github.com/Lauren21717/Milestone_project_1/blob/main/assets/media/chrome-testing-before.png?raw=true)
    - **Firefox Version 123.0.1**
      ![Firefox testing before](https://github.com/Lauren21717/Milestone_project_1/blob/main/assets/media/firefox-testing-before.png?raw=true)
    - **Safari Version 17.3.1**
      ![Safari testing before](https://github.com/Lauren21717/Milestone_project_1/blob/main/assets/media/safari-testing-before.png?raw=true)
      
- **Solution Applied:**
    1. Utilized browser developer tools to inspect the CSS properties affecting the callout section's position.
    2. Adjusted CSS styles to ensure consistent positioning across all browsers.
    
- **After Fix:**
    - **Chrome Version 122.0.6261.111**
      ![Chrome testing after](https://github.com/Lauren21717/Milestone_project_1/blob/main/assets/media/chrome-testing-after.png?raw=true)
    - **Firefox Version 123.0.1**
      ![Firefox testing after](https://github.com/Lauren21717/Milestone_project_1/blob/main/assets/media/firefox-testing-after.png?raw=true)
    - **Safari Version 17.3.1**
      ![Safari testing after](https://github.com/Lauren21717/Milestone_project_1/blob/main/assets/media/safari-testing-after.png?raw=true)
    
- **Compatibility Testing:** 
    - The site was tested on various devices and operating systems to ensure compatibility.
    - **Issue Found:** On smartphones, the callout section covered the entire page.
    
    **Solution Applied:** 
    - Removed the `font-size` rule from the `.display-4` class.
    - Eliminated the set height from `.home-background` in relevant media queries.
    
    **Before Fix:**
    - ![Home Callout Before](https://github.com/Lauren21717/Infinite_Fitness/blob/main/assets/media/home-callout-before.png?raw=true)
    
    **After Fix:**
    - ![Home Callout After](https://github.com/Lauren21717/Infinite_Fitness/blob/main/assets/media/home-callout-after.png?raw=true)
    
- **Test Results:**  
    - On smartphones, tablets, laptops, and desktops, the page rendered as expected.

---

### Bugs Discovered and Fixed
- **HTML Validation Issues:** Checked using the [HTML Validator](https://validator.w3.org/).
    - **Warnings and Fixes:**
      - Replaced `<section>` tags with `<div>` where no heading was present.
      - Removed stray `</div>` and `</section>` tags.
      - Corrected missing DOCTYPE in some files.

- **CSS Validation:** No errors found using the CSS Validator.

---

### UI Improvements

1. **Border-Radius Adjustments**:
    - Adjusted the `border-radius` of images on the About, Class, and Join Now pages to maintain consistency.
  
   **About Page:**
   - **Before:**
     ![About Img Before](https://github.com/Lauren21717/Milestone_project_1/blob/main/assets/media/about-img-before.png?raw=true)
   - **After:**
     ![About Img After](https://github.com/Lauren21717/Milestone_project_1/blob/main/assets/media/about-img-after.png?raw=true)

   **Class Page:**
   - **Before:**
     ![Class Img Before](https://github.com/Lauren21717/Milestone_project_1/blob/main/assets/media/class-img-before.png?raw=true)
   - **After:**
     ![Class Img After](https://github.com/Lauren21717/Milestone_project_1/blob/main/assets/media/class-img-after.png?raw=true)

   **Join Now Page:**
   - **Before:**
     ![Join Img Before](https://github.com/Lauren21717/Milestone_project_1/blob/main/assets/media/join-img-before.png?raw=true)
   - **After:**
     ![Join Img After](https://github.com/Lauren21717/Milestone_project_1/blob/main/assets/media/join-img-after.png?raw=true)

2. **Callout Section Padding Adjustment (Home Page):**
    - **Before:**
      ![Home Callout Padding Before](https://github.com/Lauren21717/Infinite_Fitness/blob/main/assets/media/home-callout-bg-before.png?raw=true)
    - **After:**
      ![Home Callout Padding After](https://github.com/Lauren21717/Infinite_Fitness/blob/main/assets/media/home-callout-bg-after.png?raw=true)
