=== StackTack ===
Contributors: george_edison
Tags: editor, widget, question
Requires at least: 3.3
Tested up to: 3.4.2
Stable tag: 1.2.1

StackTack is a JavaScript widget that displays questions from Stack Exchange sites.

== Description ==

If you've written a question or answer on any Stack Exchange site and you would like to share it with your readers, you are no longer limited to pasting a static link. Instead, StackTack will embed a live widget with the contents of the question and some of the top rated answers.

== Installation ==

1. Upload the directory `stacktack` to the `/wp-content/plugins/` directory.
1. Activate the plugin through the 'Plugins' menu in WordPress.
1. To insert a StackTack widget, click the Stack Exchange icon in the toolbar.

== Frequently Asked Questions ==

= Are all Stack Exchange sites supported? =

Yes, all Stack Exchange sites are supported.

= Can I have multiple instances of StackTack on the same page? =

Yes, the widget can be embedded multiple times on the same page.

== Screenshots ==

1. StackTack icon in the editing toolbar.
2. An instance of StackTack in a post.

== Changelog ==

= 1.2.1 =
* Fixed bug that prevented requests to the API from using HTTPS
* Added a paragraph to the global settings page

= 1.2 =
* Moved the JS and CSS for the dialog to separate files
* Added individual widget options
* Added ability to display only a single answer

= 1.1 =
* Added options page
* Updated to latest version of StackTack