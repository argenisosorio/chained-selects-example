# Chained selects example

Chained is simple plugin for chained selects. It works with both jQuery and Zepto. You can choose from two different versions. Use jquery.chained.js if you do not want to make external queries for setting content of child selects. This version uses data attirbutes to decide the content.

For more complex scenarios maintaining data attributes will get cumbersome. Also if you want to make queries against database use jquery.chained.remote.js instead. This version makes an external AJAX query and uses the returned JSON to build child selects.

## Simple usage

Child selects are chained to parent select. All selects must have an id attribute. Child select options must have class names which match option values of parent select. When user selects something in parent select the options in child select are updated. Options which have matching classname with parents currently selected option will stay visible. Others are hidden.

<a href="https://appelsiini.net/projects/chained/">Read complete documentation https://appelsiini.net/projects/chained/</a>