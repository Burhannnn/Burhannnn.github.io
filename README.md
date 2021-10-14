# Burhannnn.github.io
Home
Getting Started
Schema
Themes
Projects
Team
Blog
JSON ResumeGetting Started Schema Themes Projects Team Blog
Getting Started
Command Line Tool
We've built a CLI (Command Line Interface) which is supported by OSX, Linux and Windows. To create your own resume, install resume-cli from npm:

npm install -g resume-cli

Exporting
The command line tool uses an ecosystem of modules that we've open sourced to convert your resume to different formats:

resume export resume.pdf

resume export resume.html

Import from LinkedIn
One of our community members wrote a great Chrome extension to import your LinkedIn Profile.

Download here

Hosting
JSON Resume offers a hosting service that renders your resume.json to any theme you would like.

e.g. http://registry.jsonresume.org/thomasdavis

All you have to do is create a Gist on Github named resume.json.

e.g. https://gist.github.com/thomasdavis/c9dcfa1b37dec07fb2ee7f36d7278105

Our hosting service will automatically detect this when you access https://registry.jsonresume.org/{your_github_username}

To set a theme, just add to your resume.json;
{ "meta": { "theme": "elegant" } }



JSON RESUME IS OPEN SOURCE

VIEW ON GITHUB
