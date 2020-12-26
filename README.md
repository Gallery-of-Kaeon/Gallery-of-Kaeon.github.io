<h1 align="center">Kaeon United GhostHost</h1>

Kaeon United GhostHost,
or GhostHost for short,
is a utility built into the [Kaeon United](https://github.com/Gallery-of-Kaeon/Kaeon-United) platform that allows for free and anonymous front end hosting for simple projects.

<h2 align="center">Functionality</h2>

Ghosthost,
which is implemented as a Github pages site,
can take a URL to a text document as a parameter in its own URL.

The provided document may contain HTML,
JavaScript,
or Kaeon FUSION code.

If HTML is provided,
the website will render said html as a website.

If JavaScript or Kaeon FUSION is provided,
it will be executed as a script implictly.

Additionally,
if JavaScript is provided,
it shall be interpreted as United JavaScript,
and shall thus have access to the CommonJS require function,
through which it may import modules stored online via their URLs.

Additionally,
if desired,
it is also possible to specify raw code in the URL instead of a link.

Accessing the site with no URL arguments shall render the home page for [Kaeon United](https://github.com/Gallery-of-Kaeon/Kaeon-United).

It should be noted that GhostHost relies on a public CORS proxy,
the [CORS Anywhere](https://cors-anywhere.herokuapp.com/) proxy,
which occasionally goes down.

<h2 align="center">Instructions</h2>

The URL for an HTML project must follow this format:

    https://gallery-of-kaeon.github.io?html=resource_link

The URL for a JavaScript project must follow this format:

    https://gallery-of-kaeon.github.io?unitedJS=resource_link

The URL for a Kaeon FUSION project must follow this format:

    https://gallery-of-kaeon.github.io?unitedOP=resource_link

The URL for an HTML project using raw code instead of a URL must follow this format:

    https://gallery-of-kaeon.github.io?htmlRaw=resource_code

The URL for a JavaScript project project using raw code instead of a URL must follow this format:

    https://gallery-of-kaeon.github.io?unitedJSRaw=resource_code

The URL for a Kaeon FUSION project using raw code instead of a URL project must follow this format:

    https://gallery-of-kaeon.github.io?unitedOPRaw=resource_code

<h2 align="center">Example</h2>

To demonstrate,
we've uploaded an example site to this repository, located at the following URL:

[https://gallery-of-kaeon.github.io/?html=https://raw.githubusercontent.com/Gallery-of-Kaeon/Gallery-of-Kaeon.github.io/master/GhostHost/Example/example.html](https://gallery-of-kaeon.github.io/?html=https://raw.githubusercontent.com/Gallery-of-Kaeon/Gallery-of-Kaeon.github.io/master/GhostHost/Example/example.html)

<h2 align="center">Why use GhostHost over Github pages, or other similar services?</h2>

Other platforms used for free hosting usually require the creation of some sort of account,
require an intermediate knowledge of IT related topics,
making them inaccessible to beginners,
and are contingent upon the resources and good will of whoever is hosting them.
Additionally,
most impose strict limitations on their use.

GhostHost provides the potential for anonymous use,
and the technique is simple enough to replicate that,
if GhostHost or other hosting services ever go down or change their policies,
someone else could easily replicate it elsewhere for little to no cost.