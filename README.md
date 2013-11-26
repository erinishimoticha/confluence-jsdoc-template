confluence-jsdoc-template
=========================

Template for JSDoc 3.2+ in Confluence wiki markup.

Usage
-----
Install jsdoc locally by running npm install -s jsdoc
Clone the repository into the template folder in your project (same level as node_modules).
Run the documentation with "-t template/confluence-jsdoc-template" flag to use this template.

Your project should look something like this:

```
|- node_modules
|- template
  \- confluence-jsdoc-template
|- package.json
```

Import the wiki markup into your Confluence or compatible wiki program. In Confluence, you may have to use the
convertWikiToStorageFormat API to convert the markup into HTML for internal storage by Confluence.

Todo
----

1. Support all tags. Need willing testers in order to make this happen.
2. Make the pages prettier and make use of the table of contents macro. Design help is needed.
3. Improve link detection so that things like list return values are found and linked.

Contribute
-------

I would love contributions. Please issue a pull request!
