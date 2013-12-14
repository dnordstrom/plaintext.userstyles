## Mankind's Precious · Plain Text & Friends · Solarized Dark

Firefox user styles for plain text and friends (e.g. Markdown), using a couple of colors from the dark Solarized palette.

The styles are **included** on ".txt," ".md," and related URLs, and URLs ending with ":<format>". This allows **manual activation**---the location hash can for instance be used as follows to enable the stylesheet while browsing the introduction of an article:

https://example.com/plain-text-article#intro:text (a dot works too)

Domains known to use these file extensions in URLs of their regular interface are **excluded**. For example, the URL to view this README.md file in the GitHub repository browser is simply:

https://github.com/dnordstrom/userstyles.plaintext

To include more extensions, or to exclude other domains or URLs, you can customize the `@-moz-document` regular expression.

The stylesheet uses the **font and font size** specified in your preferences---in Firefox, these can be changed at Preferences > Content > Fonts & Colors > Advanced > Monospace. (I'm personally using Fira Mono at 14px.)