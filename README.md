<h1 align="center">GhostHost</h1>

GhostHost is an experimental site that allow for free hosting of sorts for simple projects.

The website can take a URL to a text document as a parameter in its own URL.
If the text in said resource constitutes valid HTML,
the website will render said html as a new site.

The URL must follow this format:

    https://gallery-of-kaeon.github.io?path=resource_link

To demonstrate,
we've uploaded an example site to this repository:

    https://gallery-of-kaeon.github.io/?path=https://raw.githubusercontent.com/Gallery-of-Kaeon/Gallery-of-Kaeon.github.io/master/GhostHost/Example/example.html

GhostHost itself is hosted by Github Pages and uses the CORS Anywhere API as a CORS proxy.

Though it is working, lots of testing and polishing remains to be done.

<h2 align="center">Why use GhostHost over Github pages, or other similar services?</h2>

Any other platform used for free hosting usually requires the creation of some sort of account,
and is contingent upon the good will of whoever is hosting said platform.
Additionally,
most impose strict limitations on their use.

GhostHost provides the potential for anonymous use,
and the technique is simple enough to replicate that,
if GhostHost ever goes down or changes its policies,
someone else could easily replicate it elsewhere for little to no cost.