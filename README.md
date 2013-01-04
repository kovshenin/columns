Columns
=======

This WordPress plugin boosts your website with... you guessed it, columns! Create a column group with the [column-group] shortcode, then add columns to the group with the [column] shortcode, like this:

[column-group]
    [column]This is my first column[/column]
    [column]This is my second column[/column]
[/column-group]

You can also span columns, like this:

[column-group]
    [column span="2"]This is my first column spanned across two columns.[/column]
    [column]This is my second column[/column]
    [column]This is my third column[/column]
[/column-group]

The firt column will be twice as large as the second or third.

Styles are in columns.css. If you'd like your own margins and stuff, dequeue the columns.css style during wp_enqueue_scripts with a priority of 11 or more.
