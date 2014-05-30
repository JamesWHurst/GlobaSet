PimBok
======

PimBok is a globalization tool for .NET F# and C#, Java, and Python projects.

The need that PimBok is designed to fullfill, is the simplification of a software project's globalization through automation. PimBok operates by scanning your project's source-code, tallying up the instances of localizable text, and creating a report.

At any given point during the course of your project development, you can run PimBok as an automated tool as part of your build process, and it produces a listing of all globalizable terms (that is, bits of text that are shown to the user) that it finds currently within the code, and a separate listing of what has already been globalized versus what is new and needs translation services for. 

Lists (that is, tables of information):

1. A master list of all translated terms, done by your firm, ever.
2. A list of all terms within a given project that need translating.
3. After having list number 1 applied to list number 2, a list of the terms that remain to be translated.

In this way, your firm preserves your investment in translation services. If you have already produced software artifacts that have all of the globalizable terms that are currently within your project in question, then PimBok reports this to you and you've nothing to do.

If only some of the terms within your project need translating, then PimBok helps you to minimize your translation cost by giving you the list of only that which has never been translated by your firm, as yet.


Definitions:

"globalizable terms", or just "terms" - words, phrases, or other bits of text that would be displayed to an end-user, which would generally need to be translated to other languages.

"lists" - a table of, which may be implemented as a database table.
