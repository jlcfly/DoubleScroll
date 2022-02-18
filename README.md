# DoubleScroll
Plain ol' Javascript that a horizontal scroll bar to top of horizontally-scrollable element

Add DoubleScroll.js via a script tag. Then, in your HTML, wrap the element you want to horizontally scroll with a div tag:

	<div id="doublescroll">
    .
    .
    .
	</div>

Then in your javascript:

	DoubleScroll(document.getElementById('doublescroll'));

You do not have id your outer div 'doublescroll'. Name it whatever you want. Just reference it appropriately in the javascript call.

It's not required to style the _#doublescroll_ element, but it might be advisable to do so in certain circumstances. For example, adding a border:

	#doublescroll {
		border: 1px solid #999;
	}

That's it.
