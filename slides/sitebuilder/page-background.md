## Background

Let's start by choosing a background image for our site.

Choose a nice large image.

	html {
		background-color: black;
		background-image: url('http://tiny.cc/grassy-field');
		background-size: cover;
		background-attachment: fixed;
	}

Note:
We already have an 'html' tag on the page, so we can style it from the CSS using the keyword 'html'.

We use this one for adding a background as it is the outermost element - it contains everything else on the page so we know the bg will go behind everything else.