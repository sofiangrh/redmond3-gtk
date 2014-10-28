This is a Windows 3.1 lookalike theme for GTK+. Currently, it is very immature.
There are numerous tradeoffs in the look, because my insights on GTK+ theming are
fairly limited; so, looks are bent in favor of GTK instead of authentic Windows 3.1.
For an example, see combo boxes.

Another thing is that Windows 3.1 applications, even those by Microsoft itself,
present a beautiful primer on how to be inconsistent in UI design. Take a look
at, say, Microsoft Internet Explorer, Microsoft Office and standard Win3.1 apps,
save for 3rd party vendors such as Borland.

In spirit of this, I think some inconsistencies can be excused as long as the spirit
and nostalgic values are not damaged.

SOURCES:

	Numerous Windows 3.1 and 3.11 screen shots scattered over the net.
	Tabs are made as depicted on http://msdn.microsoft.com/en-us/library/aa733699%28v=vs.60%29.aspx

TODO:

*	Do something about tabs, leftmost and rightmost tabs will be ugly. I don't know how to bend
	the pixmap engine so that it lets me draw gaps for the leftmost and the rightmost tabs
	differently.

*	The rightmost corner of menus is eaten away. I still don't know the cause.
	This applies to menubars and menus.

*	The code was done in the manner of "hack until it works". General refactoring is needed.

*	Maybe there IS a way to make comboboxes look as on Win3.1 proper. Hint me; I know that
	even Redmond engine doesn't do it.

Theme by [necrothemes](https://github.com/necrothemes/)
