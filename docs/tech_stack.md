# Tech Stack

## Technology Requirements

All projects must be built using the prescribed language (Python 3), database system (PostgreSQL), framework (Django 5), build environment (GitHub Actions CI), source control management (GitHub), cloud hosting (Heroku), and cloud storage (Amazon S3). No exceptions to these will be granted.

While there is no requirement to use Bootstrap or any other particular UI framework, teams must use Django templates for generating web pages.  Any libraries used for styling must be roughly equivalent to Bootstrap.  UI libraries cannot make JSON/XML/API calls to Django-based web services.

Note: All projects must use the PostgreSQL database engine for production on Heroku and continuous integration (on GitHub Actions). You are allowed to use SQLite for local testing so you do not have to install PostgreSQL on your own machine, but another option is to change your settings.py file point to the PostgreSQL DB on Heroku at all times.

## Git Resources
![Git Cheat Sheet](/assets/images/git-cheat-sheet.png?raw=true "Git Cheat Sheet")

* [Git tutorial](https://kbroman.org/github_tutorial/)

## Web Design Resources

* Web Content Accessibility Guidelines (WCAG) 2021 Quick Reference: [https://www.w3.org/WAI/WCAG21/quickref/](https://www.w3.org/WAI/WCAG21/quickref/)
* Four basic principles: Perceivable, Operable, Understandable, Robust
* Semantic & Accessible HTML on MDN: [https://developer.mozilla.org/en-US/docs/Learn/Accessibility/HTML](https://developer.mozilla.org/en-US/docs/Learn/Accessibility/HTML)
* Accessible Rich Internet Applications (ARIA) Reference on MDN: [https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA)
Use ARIA only in cases that aren't covered by HTML 5 semantic tags. In particular, check out the tutorials section, where they demonstrate how a screen reader parses web pages.
* ANDI Free Accessibility Testing Tool: [https://www.ssa.gov/accessibility/andi/help/install.html](https://www.ssa.gov/accessibility/andi/help/install.html)
Do NOT use this as a one-stop shop to test for accessibility. In the end, you are responsible for ensuring compliance with accessibility standards. This tool only tests compliance with Section 508, a set of standards developed for federally-funded site accessibility. It does not necessarily imply compliance with WCAG or accessibility as a general concept.
* WebAIM Contrast Checker Tool: [https://webaim.org/resources/contrastchecker/](https://webaim.org/resources/contrastchecker/)
This tool is great because it tells you whether you are passing WCAG contrast guidelines!
* Great Slideshow on Usability by UVA's own Professor Praphamontripong: [http://www.cs.virginia.edu/~up3f/cs4640/slides/4640meet03A-UsabilityPrinciples.pdf](http://www.cs.virginia.edu/~up3f/cs4640/slides/4640meet03A-UsabilityPrinciples.pdf)
* Here's a helpful infographic! For larger version, visit [https://webaim.org/resources/designers/](https://webaim.org/resources/designers/)

## Django Resources

* [Creating python virtual env](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/)
* [Tutorial on the basics of Django (YouTube Series)](https://www.youtube.com/watch?v=UmljXZIypDc)
* [Django generic editing views](https://docs.djangoproject.com/en/4.2/ref/class-based-views/generic-editing/)
* [Serving static images for your project](https://docs.djangoproject.com/en/4.2/howto/static-files/deployment/)

