Internet Explorer 6 Upgrade Bar
===============================

A flexible upgrade bar for IE6-8 created with HTML and CSS

This upgrade bar looks similar to Microsoft's upgrade bar image from http://www.ie6countdown.com/, but it's much smaller, more flexible, and easy to customize.

Link: https://github.com/theodorejb/Internet-Explorer-6-Upgrade-Bar

Background info: http://designedbytheo.com/blog/2012/09/making-a-better-ie6-upgrade-bar-3/

Usage
-----

Start by including __upgrade_bar.html__ within an IE conditional comment directly after the opening body tag of the document (either via a server-side include or by simply copy/pasting the HTML). PHP example:

	<!--[if lt IE 8]>
		<?php include upgrade_bar.html ?>
	<![endif]-->

Secondly, include a link to the CSS file in the document head (also within conditional comments):

	<!--[if lt IE 8]>
		<link rel="stylesheet" type="text/css" href="BrowserUpgradeBar/upgrade_bar.css" />
	<![endif]-->

That's it! Feel free to use this code on your own site, or modify it to suit you needs, as long as it is accompanied by this readme.