CLINTON TECH TOOLS

Structure
  index.html      the homepage
  tools.js        the list of tools (edit this)
  pages/          one .html file per tool

Add a tool
  1. Put your-tool.html inside the pages/ folder.
  2. Open tools.js and add a line inside the list (keep the comma):

       { "name": "Your Tool", "file": "your-tool.html" },

     Optional extras:
       "desc": "One-line description",
       "category": "Text",
       "icon": "code"     (code, text, calc, image, link, clock, color, lock, file, cube)

  The card, the counter and the search all update by themselves.
  Works when opened straight from a phone/computer folder and on any host.

  In each tool page, add a link back:  <a href="../index.html">Back</a>
