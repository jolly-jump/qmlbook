# Contributing

:+1::tada: First, thanks for taking the time to contribute! :tada::+1:

The following is a set of guidelines to contribute to the QmlBook, which is hosted at (https://github.com/qmlbook/qmlbook/) on GitHub.

## Licensing

You provide us the contributions under [Attribution-NonCommercial-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-nc-sa/4.0/) license for text and [BSD](http://opensource.org/licenses/BSD-3-Clause) license for code. We keep us the rights to print a book based on the provided content. We can not ensure that everyone will then be correctly named, but we will do the best. This is just that you understand what you are about todo:-). 

Still interested? Cool. Welcome!

## Issues

Each chapter on the qmlbook (http://qmlbook.org) has several 'issue' reporting links. Please use these when you find a spelling error or another issue in the text. This will help us to identify the section later. The issue link will let you create or view the issues of this particular chapter.

The issues can be foud at (https://github.com/qmlbook/qmlbook/issues)

## Patch Contribution

We use the standard github pull requests for merging your fork of the book back to this one. You can find more information at (https://help.github.com/articles/using-pull-requests/).

## Chapter Contribution

You might feel adventures and are willing to contribute a full chapter. Your name will then be placed on the chapter for your reference. For this crate a new chaprer folder (e.g. ch99) and write your content using [Sphinx](http://sphinx-doc.org) markup. We will then place the chapter into the chapter queue and when it's ready we will sort it into the table of contents.

## Translations

So you speak something else then english. Great! Feel free to translate the book into your language. ~For this clone the repository and then later create a pull request that we can sort this in. Before you start you should contact us on gitter to make sure there is no overlap.~

Browse to https://www.transifex.com/qmlbook/qt5-cadaques/dashboard/
and click on "Try for free" or "Help Translate". You will have to
create an account and log in. Browse again to above link and click
"Join Team", select your language. If your language is not in the
list, go back and scroll down where you can "Request language". After
it was added, join the team with the language(s) you want to
contribute to. As soon as your join request is accepted, you can start to translate.

Translating is done by clicking on a resource, which corresponds to
each chapter of the book. So you can start translating "ch01--index"
which contains strings with the english source that you need to
translate, correct from previous translations or review.

When the translation is done on transifex.com someone needs to pull
the online changes into the git repository, e.g. for italian:

```
# tx pull -l it
```

Now the changed "po"-files should be updated locally, which need to be
commited and merged via a pull request on git. This can also be done
by someone with the knowledge of git, not necessarily the translator.

Last but not least, when the changes are merged, the language updates
should automatically appear in the book.

~Note: The infrastructure is not yet there, but soon we should be ready for translations.~

// JRyannel, JThelin


