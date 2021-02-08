# Horiseon Code Refractory

# Statement of Work (SOW)
The project objective is to refactor the code, which includes a review existing code with ficus on improvement. The following objective apply:
    - Review of compliance with accessiblity standards
    - SEO
    - Code structure for ease of reading and understanding
    - Structural Markup review (e.g. description of headings and paragraphs)
    - Semantic Markup, which is a way of writing and structuring HTML code so that it reinforces 
        the semantics, or meaning, of the content rather than its appearance. Writing semantic markup means understanding the hierarchy of content and how both users and machines will read it. (e.g. emphasis of sentences, quotatinos, meaning of acronyms, etc.)
    - Image lement compliance with accessibility attributes
The work does not include an content or syntax review if the displayed page.

# Review of Page in Browser
First we reviewed the page in three browsers (Chrome, Firefox, Edge), to understand the current behavior. Result:
    - Accessibility requirements are partially met, since it provides the user with an acceptable way to navigate and interact with the site. However, alt and title text is missing throughout the page (Top Header, Menu, Images, Headers)

# Code updates
General
index.html: kept notations in the code for reference and understanding
syle.css: removed unnecessary code

index.html
- Replaced <div> elements with <main>, <nav>, <aside>, <section>, <footer> elements 
- Added alt and title text to images 
- line 34: changed class to id
- line 36, 44, 52: unified class for all references; updated css
- line 68, 76, 85: did not add title, since icons do not further explanations
- line 80: deleted </img> closing tag
CSS:
- replaced redundant classes
- removed class="header"
- repaced hero class with id
- removed unnessary class cascades
- changed ".header nav ul il" to "ul li"  
- ul list-style-type has no impact on current page, but might be browser dependent

# Questions

index.html
    line 35 
        <main class="content"> Question: A move of image element from css to html enables alt and title. it also would required a change of css background-image to html img. This would cause a change in picture size, which could be adjusted. I am not understanding what the different feature of the background-image vs html img is.
        Example: <img id="hero" src="./assets/images/digital-marketing-meeting.jpg" alt="Digital Marketing Meeting" title="A meeting about digital marketing"> -->





