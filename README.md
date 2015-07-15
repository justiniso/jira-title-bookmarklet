# JIRA title bookmarklet

## Installation

1. Bookmark this page
2. Edit the bookmark href to be the following text:

    `javascript:void(function(){window.prompt('Copy this:', document.URL + ' (' + jQuery('#summary-val').text().trim() + ')')}())`

3. Click it on a JIRA page
4. Copy the text


(Only tested in JIRA 5)
