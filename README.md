# Confluence Wiki Markup Package

This repository aims to provide a full featured Sublime Text 3 package that
provides a language for working with the wiki markup syntax from the
[Confluence][1] product by Atlassian.

Initially, this package will focus on the language and scope definitions to
support generic and targeted syntax highlighting provided by themes. When
defining the scope, the closest representation to a built-in type will be used.
This will hopefully allow most themes to be able to make sense of some of the
basic syntax rules. However, not every component in the wiki markup can easily
be represented by a generic scope, so in those instances, a unique and targeted
scope will be defined, which will require explicit theme support.

The second focus of the package will include providing basic snippets for some
of the more commonly used constructs in the language. My aim is to provide a
robust set of snippets and enhance them with actual completion support by
providing Sublime Text with a completion script.

  [1]: https://www.atlassian.com/software/confluence/
