=== Columns ===
Contributors: kovshenin
Donate Link: http://kovshenin.com/beer/
Tags: columns, shortcode
Requires at least: 3.5
Tested up to: 3.6
Stable tag: 0.7
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This WordPress plugin boosts your website with... you guessed it, columns!

== Description ==

Create a column group with the `[column-group]` shortcode, then add columns to the group with the `[column]` shortcode, like this:

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

Styles are in columns.css. If you'd like your own margins and stuff, dequeue the columns.css style during `wp_enqueue_scripts` with a priority of 11 or more.

== Installation ==

1. Download archive and unzip in wp-content/plugins or install via Plugins - Add New.
1. Start using the `[column-group]` and `[column]` shortcodes.

== Screenshots ==

1. Columns demo
2. This is how things look in the editor

== Changelog ==

= 0.7 =
* First version