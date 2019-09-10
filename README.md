<h1 align="center">GhostHost</h1>

GhostHost is an experimental site that allow for free hosting of sorts for simple projects.

The website can take a URL to a text document as a parameter in its own URL.
If the text in said resource constitutes valid HTML,
the website will render said html as a new site.

The URL must follow this format:

    https://gallery-of-kaeon.github.io?path=resource_link

To demonstrate,
we've uploaded an example site to this repository:

    https://gallery-of-kaeon.github.io/?path=https://raw.githubusercontent.com/Gallery-of-Kaeon/Gallery-of-Kaeon.github.io/master/example.html

GhostHost itself is hosted by Github Pages and uses the CORS Anywhere API as a CORS proxy.

Though it is working, lots of testing and polishing remains to be done.