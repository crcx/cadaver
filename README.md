Cadaver
--------------------------------------------------------------------------------

Prequisites:

* CGI capable web server
* Cyanide (CGI-aware Parable scripting interface)
* Markdown
* Make

Posts go in the *posts* directory. They should be numbered, starting with 1,
and ending with a *.md*. In the *posts* directory run *make*. This should
create *.html* files for each post in the *cache* directory.

Edit *mostRecent* to reflect the latest post identifier.

Edit the base URL in *0* to reflect your server configuration.

Enjoy.

