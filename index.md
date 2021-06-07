# Copy issue link bookmarklet

Drag this link to your bookmark bar to save the bookmarklet:

<a href='javascript:"use strict";var e,t,c,n=document.createElement("textarea"),o=document.querySelector("h1.gh-header-title"),a=window.location.href;o&&o.children[0]&&o.children[0].textContent&&(e=o.children[0].textContent.trim(),t=a.split("/"),c="".concat(t[3],"/").concat(t[4],"#").concat(t[6]),n.value="".concat(e," [").concat(c,"](").concat(a,")"),document.body.appendChild(n),n.select(),document.execCommand("copy"),n.remove());'>Copy issue link</a>

See [github.com/benbalter/copy-issue-link-bookmarklet](https://github.com/benbalter/copy-issue-link-bookmarklet) for more information.
