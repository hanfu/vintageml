********
About Sphinx
********

RST Grammers
=======

fonts
	*italic*

	**bold**

	``little red``

	:class:`little black bold`

	:guilabel:`little blue box`

	.. centered:: centered

	::

		if code chunk:
			more

	:math:`X_{0:5} = equation(X_0)`


	.. admonition:: admonition box

	   blue box

	.. Note:: blue

	.. seealso:: blue

	.. Attention:: orange

	.. Caution:: orange 

	.. Warning:: orange

	.. DANGER:: red

	.. Error:: red

	.. Hint:: green

	.. Important:: green

	.. Tip:: green







links
	`link <https://hanfu.us>`_

	.. _anchor: [external.url.if.any]

	use anchor_

	footnote [#this]_

	.. [#this] this is a footnote

	.. math::
		:label: this_eq

		X_{0:5} = (X_0)

	eq ref :eq:`this_eq`

	.. code-block:: python
		:caption: this_code
		:name: this_code

		if code-block:
			more

	code ref :ref:`this_code`


.. sidebar:: a box

	some text

textbox
	more text

image
	.. image:: path/to.jpg
		:target: somelink_
		:alt: alt-image
		:align: center
		:width: 400px

variable
	today is |today|

	.. |today|

list


Reference
	<https://sphinx-rtd-theme.readthedocs.io/en/stable/demo/demo.html>
	
	<https://github.com/ralsina/rst-cheatsheet/blob/master/rst-cheatsheet.rst>
	<>
	<>
