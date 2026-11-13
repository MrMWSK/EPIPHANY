MRMWSK READER STUDIO
====================
A browser-based HTML reader branded by MrMWSK.

Files
-----
- index.html: the complete standalone app.

Publish using the existing repository
--------------------------------------
1. Open https://github.com/MrMWSK/EPIPHANY
2. Upload index.html and README.txt from this package to the repository root (the top level).
3. Open Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Select branch main and folder /(root), then Save.
6. After GitHub Pages finishes publishing, the site should be available at:
   https://mrmwsk.github.io/EPIPHANY/

App notes
---------
The app processes the selected HTML file in the visitor's browser; it does not upload user files to a server. It accepts .html/.htm files up to 15 MB, offers reading themes and text sizing, can print/save as PDF, and can download a cleaned HTML copy. Language filters recognise common class names and lang attributes (for example .urdu-text, .roman-urdu, .english-text, lang="ur", and lang="en"). Unlabelled sections remain visible under All content. The app does not automatically translate text.

Before public launch, test it with several representative HTML files and browsers.
