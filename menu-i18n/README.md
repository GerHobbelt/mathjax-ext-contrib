# Extension: menu-i18n

Provides facilities for internationalization of the MathJax contextual menu,
with string substitution data specified in a JSON file.

This extension is VERY EXPERIMENTAL -- use with EXTREME caution.

# Configuration:

    MathJax.Hub.Config({
        MathMenu: {
            menuDataFile: "menudata.json"
        },
        extensions: ["http://cs.jsu.edu/mathjax-ext/github/menu-i18n/menu-i18n.js"]
    });

# Usage:

File `menudata.json`:

    {
        "Original Menu Item Label Text" : "Replacement Text", ...
    }

See [sample](http://leathrum.github.com/mathjax-ext-contrib/menu-i18n/sample.html)

# History:

*6 Apr 2012* -- initial upload to GitHub  
further history maintained there
