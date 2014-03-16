confluence-jsdoc-template
=========================

Template for JSDoc 3.2+ in Confluence wiki markup.

Usage
-----

Clone the repository into /usr/local/bin/jsdoc/templates, or wherever you keep your JSDoc 3
templates. Run JSDoc 3 with the -t option, followed by the full path to confluence-jsdoc-template.
Import the wiki markup into your Confluence or compatible wiki program. In Confluence, you may
have to use the convertWikiToStorageFormat API to convert the markup into HTML for internal
storage by Confluence.

Todo
----

1. Support all tags. Need willing testers in order to make this happen.
2. Make the pages prettier and make use of the table of contents macro. Design help is needed.
3. Improve link detection so that things like list return values are found and linked.
4. apply patch
5. Fix properties on a parameter
6. Implement class properties
7. fix @fires
8. Fix empty promise/array pattern Promise where no <> exists.
9. Symbols duplicated when documented twice. Is this expected?

Contribute
-------

I would love contributions. Please issue a pull request!
