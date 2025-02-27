# For the 50

## Table of Contents

- [For the 50](#for-the-50)
  - [What is Testing](#what-is-testing)
  - [Validators and Lighthouse](#validators-and-lighthouse)
  - [Home Page](#home-page)
  - [About Page](#about-page)
  - [Stories Page](#stories-page)
  - [Knowledge Page](#knowledge-page)
  - [Statistics Page](#statistics-page)
  - [Contact Page](#contact-page)
  - [Report Page](#report-page)
  - [Meet the Team Page](#meet-the-team-page)
  - [Manual Testing](#manual-testing)
    - [Python](#python)
    - [JavaScript](#javascript)
    - [Navbar and footer](#navbar-and-footer)
    - [Contact Page](#contact-page-1)
    - [About Page](#about-page-1)
    - [Knowledge Page](#knowledge-page-1)
    - [Report Page](#report-page-1)
    - [Meet the Team Page](#meet-the-team-page-1)

## What is Testing

Behavior-driven development (BDD), manual testing, and webpage testing were employed to ensure the website functions correctly and adheres to quality standards. Each page was thoroughly evaluated using various tools to verify its performance, accessibility, and compliance with web standards.

## Validators and Lighthouse

### Home Page

- **HTML Validation**: The HTML structure of the Home Page was validated using the W3C HTML Validator. The result was successful with no errors or warnings, confirming compliance with web standards and ensuring robust cross-browser compatibility.

  ![Home Page HTML Validator Result](documentation/html-validator-home-page.png)

- **Google Chrome Lighthouse Assessment**: The Home Page was assessed using Google Chrome Lighthouse to evaluate its performance, accessibility, best practices, and SEO.  
  - **Performance**: 74 - "The page demonstrates good performance with room for further optimization."  
  - **Accessibility**: 95 - "Excellent accessibility ensures the page is user-friendly for a diverse audience."  
  - **Best Practices**: 78 - "Adherence to best practices is commendable, with minor areas for improvement."  
  - **SEO**: 91 - "Strong SEO implementation enhances search engine visibility."

  ![Home Page Lighthouse Result](docs/testing//light-house-home-page.png)

---

### About Page

- **HTML Validation**: The About Page's HTML was rigorously validated using the W3C HTML Validator. The validation was successful, indicating the page is well-structured and adheres to web standards.

  ![About Page HTML Validator Result](documentation/html-validator-about-page.png)

- **Google Chrome Lighthouse Assessment**: The About Page achieved the following scores during the Lighthouse evaluation:  
  - **Performance**: 99 - "Exceptional performance indicates a highly optimized page."  
  - **Accessibility**: 93 - "The page is highly accessible, ensuring inclusivity for all users."  
  - **Best Practices**: 74 - "Good adherence to best practices with scope for refinement."  
  - **SEO**: 91 - "Strong SEO strategies contribute to excellent search visibility."

  ![About Page Lighthouse Result](docs/testing//light-house-about-page.png)

---

### Stories Page

- **HTML Validation**: The Stories Page was successfully validated using the W3C HTML Validator, confirming error-free HTML and compliance with web standards.

  ![Stories Page HTML Validator Result](documentation/html-validator-stories-page.png)

- **Google Chrome Lighthouse Assessment**: The Stories Page results are as follows:  
  - **Performance**: 85 - "The page shows solid performance, providing a smooth user experience."  
  - **Accessibility**: 95 - "Outstanding accessibility ensures the content is easily navigable for all users."  
  - **Best Practices**: 78 - "The page adheres to recommended practices, enhancing its reliability."  
  - **SEO**: 91 - "Effective SEO implementation boosts discoverability."

  ![Stories Page Lighthouse Result](docs/testing//light-house-stories-page.png)

---

### Knowledge Page

- **HTML Validation**: The Knowledge Page's HTML passed the W3C validation successfully, ensuring a clean and error-free structure.

  ![Knowledge Page HTML Validator Result](documentation/html-validator-knowledge-page.png)

- **Google Chrome Lighthouse Assessment**: Key scores for the Knowledge Page:  
  - **Performance**: 97 - "Excellent performance ensures quick loading and smooth interactions."  
  - **Accessibility**: 96 - "Superior accessibility provides an inclusive experience for all users."  
  - **Best Practices**: 74 - "A solid foundation of best practices with opportunities for further refinement."  
  - **SEO**: 91 - "Strong SEO techniques improve the page's visibility."

  ![Knowledge Page Lighthouse Result](docs/testing//light-house-knowledge-page.png)

---

### Statistics Page

- **HTML Validation**: The Statistics Page was validated without errors using the W3C HTML Validator, confirming compliance with web standards.

  ![Statistics Page HTML Validator Result](documentation/html-validator-statistics-page.png)

- **Google Chrome Lighthouse Assessment**: The Statistics Page scored:  
  - **Performance**: 95 - "Impressive performance ensures a fast and efficient experience."  
  - **Accessibility**: 95 - "High accessibility standards make the page user-friendly for everyone."  
  - **Best Practices**: 78 - "The page adheres to best practices, ensuring reliability and security."  
  - **SEO**: 91 - "Effective SEO enhances search engine ranking."

  ![Statistics Page Lighthouse Result](docs/testing//light-house-statistics-page.png)

---

### Contact Page

- **HTML Validation**: The Contact Page's HTML passed the W3C validation test successfully, ensuring no structural issues.

  ![Contact Page HTML Validator Result](documentation/html-validator-contact-page.png)

- **Google Chrome Lighthouse Assessment**: The Contact Page received the following scores:  
  - **Performance**: 99 - "Exceptional performance reflects a well-optimized page."  
  - **Accessibility**: 95 - "Outstanding accessibility ensures ease of use for all visitors."  
  - **Best Practices**: 78 - "The page adheres to best practices with minor areas for improvement."  
  - **SEO**: 82 - "Good SEO strategies enhance discoverability."

  ![Contact Page Lighthouse Result](docs/testing/light-house-contact-page.png)

---

### Report Page

- **HTML Validation**: The Report Page passed the W3C validation successfully, ensuring an error-free HTML structure.

  ![Report Page HTML Validator Result](documentation/html-validator-report-page.png)

- **Google Chrome Lighthouse Assessment**: Report Page scores include:  
  - **Performance**: 89 - "The page offers reliable performance with room for optimization."  
  - **Accessibility**: 95 - "The page meets high accessibility standards for inclusivity."  
  - **Best Practices**: 74 - "Adherence to best practices contributes to reliability."  
  - **SEO**: 91 - "Strong SEO implementation supports better visibility."

  ![Report Page Lighthouse Result](docs/testing/light-house-report-page.png)

---

### Meet the Team Page

- **HTML Validation**: The Meet the Team Page's HTML was validated successfully, confirming it adheres to web standards.

  ![Meet the Team Page HTML Validator Result](documentation/html-validator-meet-team-page.png)

- **Google Chrome Lighthouse Assessment**: The scores for this page are:  
  - **Performance**: 99 - "Outstanding performance ensures a seamless user experience."  
  - **Accessibility**: 82 - "Good accessibility ensures usability for a wide audience."  
  - **Best Practices**: 74 - "The page follows best practices with minor areas for enhancement."  
  - **SEO**: 82 - "Effective SEO practices enhance search visibility."

  ![Meet the Team Page Lighthouse Result](docs/testing/light-house-meet-team-page.png)

## Manual Testing

### Python

All Python was validated using (CI Python Linter)[https://pep8ci.herokuapp.com/]

| FILE     | VALIDATOR SCREENSHOT                                                                                    | RESULT            |
| -------- | ------------------------------------------------------------------------------------------------------- | ----------------- |
| ***Backend*** |
| views.py    | <details><summary>Views</summary><img src="docs/testing/backend-views.png"></details> | <mark>PASS</mark> |
| urls.py     | <details><summary>Urls</summary><img src="docs/testing/backend-urls.png"></details> | <mark>PASS</mark> |
| urls.py     | <details><summary>Wsgi</summary><img src="docs/testing/backend-wsgi.png"></details> | <mark>PASS</mark> |
| settings.py | <details><summary>Settings</summary><img src="docs/testing/backend-settings.png"></details> | <mark>few errors but these were't be split for better functionality</mark> |
| ***ForThe50*** |
| views.py   | <details><summary>Views</summary><img src="docs/testing/forthe50-views.png"></details> | <mark>PASS</mark> |
| urls.py    | <details><summary>Urls</summary><img src="docs/testing/forthe50-urls.png"></details> | <mark>PASS</mark> |
| apps.py     | <details><summary>Apps</summary><img src="docs/testing/forthe50-apps.png"></details> | <mark>PASS</mark> |
| serializers.py     | <details><summary>Serializers</summary><img src="docs/testing/forthe50-serializers.png"></details> | <mark>PASS</mark> |
|  |  |  |

### JavaScript

All JavaScript was validated using (JS Hint)[https://jshint.com/]

|   PAGE                                     |  VALIDATOR SCREENSHOT                                     |   RESULT    |
|--------------------------------------------|-----------------------------------------------------------|-------------|
| script.js              |<details><summary>script.js</summary><img src="docs/testing/script-js.png"></details>| <mark>PASS</mark> |
| statistics.js          |<details><summary>statistics.js</summary><img src="docs/testing/statistics-js.png"></details>| <mark>PASS</mark> |
|  |  |  |

### **Navbar and footer**

| Element                | Action      | Expected Result                                         | Pass/Fail         |
| ---------------------- | ----------- | ------------------------------------------------------- | ----------------- |
| Logo                   | Click       | Redirect to Home page                                   | <mark>PASS</mark> |
| Footer link to Meet the team        | Click       | Redirect to Meet the Team page | <mark>PASS</mark> |
| Navigation menu | Click | Redirect to expected page | <mark>PASS<mark> |
| Report a Crime button | Click | Redirect to Report a Crime page | <mark>PASS<mark> |
|  |  |  |

### **Contact Page**
| Element                | Action      | Expected Result                                         | Pass/Fail         |
| ---------------------- | ----------- | ------------------------------------------------------- | ----------------- |
| Contact Resources button | Click | Redirect to Contact page | <mark>PASS<mark> |
| Hotline buttons | Click | Connect to phone interface | <mark>FAIL<mark> |
| Text button | Click | Open text message editor | <mark>FAIL<mark> |
| Submit Tip Online button | Click | Redirect to Report page | <mark>PASS<mark> |
| Find Local Resources button | Click | Redirect to resources in new window | <mark>FAIL<mark> |
| Request Victim Assistance button | Click | Redirect to assistance and support information in new window | <mark>FAIL<mark> |
| Email links | Click | Opens a blank email with the required email address in place | <mark>PASS<mark> |
|  |  |  |

### **About Page**
| Element                | Action      | Expected Result                                         | Pass/Fail         |
| ---------------------- | ----------- | ------------------------------------------------------- | ----------------- |
| Report a Crime button | Click | Redirect to report page | <mark>PASS<mark> |
|  |  |  |

### **Knowledge Page**
| Element                | Action      | Expected Result                                         | Pass/Fail         |
| ---------------------- | ----------- | ------------------------------------------------------- | ----------------- |
| Resource links | Click | Redirect to requested site in new window | <mark>PASS<mark> |
| Report Crime button | Click | Redirect to report page | <mark>PASS<mark> |
|  |  |  |

### **Report Page**
| Element                | Action      | Expected Result                                         | Pass/Fail         |
| ---------------------- | ----------- | ------------------------------------------------------- | ----------------- |
| Submit Report button | Click | Submits entered details from the form and give user feedback | <mark>PASS<mark> |
|  |  |  |

### **Meet the Team Page**
| Element                | Action      | Expected Result                                         | Pass/Fail         |
| ---------------------- | ----------- | ------------------------------------------------------- | ----------------- |
| Social links | Click | Redirect to requested site in new window | <mark>PASS<mark> |
|  |  |  |