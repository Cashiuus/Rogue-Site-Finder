Rogue-Site-Finder
=================

Python project to explore the web for fake or rogue sites

This is a working project to build an app capable of exploring the web in order to find rogue sites that similarly resemble a client's company name or existing parent site. Ideas around this concept are still being brainstormed.


Usage Summary:
You will provide the app with one or more "in-scope" URLs that are known good. You will also provide it a string, such as the client's name for finding sites that may be using it in their title.


Potential Vectors:
- Sites that leverage a client's logo image, linking to it from a remote site
- Analyzing Google results for sites that have the target string in its name, but do not belong to the client
- Input target URLs into search to retrieve a list of "top misspelled" variants and determine if any of those are hosted.
