[Home] [home]
## HTML Questions:
- **What does a doctype do?**
  - Informs the browser which version of HTML/XHTML to expect so that it knows how to render the page.
- **What's the difference between full standards mode, almost standards mode and quirks mode?**
  - Generally, the differences lie in how information gets rendered for the sake of maintaining backwards compatibility prior to W3C and IETF standards.  Implementation of quirks mode may vary browser to browser.
- **What's the difference between HTML and XHTML?**
  - XHTML, Extensible Hypertext Markup Language, has the same depth of expression as HTML, but also conforms to XML syntax.
  - HTML is based on SGML.  SGML parsers generally will keep parsing despite syntax errors, XML parsers will not.
  - XHTML for syntax checking and strict structure, HTML if not.
- **Are there any problems with serving pages as application/xhtml+xml?**
  - You would need to use content negotiation to get around ISP caching pages and serving them to users with browsers that will not correctly render application/html+xml
- **How do you serve a page with content in multiple languages?**
  - You would need translated pages located on the server for each supported language and a way for systematically switching
- **What kind of things must you be wary of when design or developing for multilingual sites?**
  - Recognizing the browser’s language request from header
  - Systematic management of pages for different languages
  - Generic page when language can’t be served
- **What are data- attributes good for?**
  - Provides extra storage for information without needing to use hacks such as classList, extra properties, etc. Good for dynamically changing data as well as specific CSS styling.
- **Consider HTML5 as an open web platform. What are the building blocks of HTML5?**
- **Describe the difference between a cookie, sessionStorage and localStorage.**
- **Describe the difference between <script>, <script async> and <script defer>.**
- **Why is it generally a good idea to position CSS <link>s between <head></head> and JS <script>s just before</body>? Do you know any exceptions?**
- **What is progressive rendering?**
- **Have you used different HTML templating languages before?**

[home]: ./README.md
