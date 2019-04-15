# A comparison of three markup languages

MarkDown, AsciiDoc and RestructuredText all belong to the family of **lightweight markup languages** each with their own pro`s and con`s

**Usage in BCO-DMO** is intended for collaboration of documentation in GitHub. Some of the documentation will be used in-house, while some other documentation will be used as external documentation using something called ReadTheDocs or website via Github. 

ReadTheDocs needs .rst language to be able to use it and it is not being implemented at the time (https://github.com/rtfd/readthedocs.org/issues/2702), however there are other ways of making a website. Or converters on the market like AsciiDoc to .rst.

For ease of use in BCO-DMO I would only use 1 mark-up language that can be used in our Github environment.



## Markdown:

Source: https://asciidoctor.org/docs/asciidoc-vs-markdown/

The defacto lightweight markup language is Markdown. (At least, that’s what you call it at first). The main advantage of Markdown lies in its primitive syntax: its manual and cheatsheet are one and the same. But this advantage is also its greatest weakness.

As soon as authors need something slightly more complex than basic  prose (e.g., tables, cross references, footnotes, embedded YouTube  videos, etc.), they find themselves resorting to embedded HTML or  seeking out more feature-rich implementations. Markdown has become a maze of different implementations, termed  “flavors”, which make a universal definition evasive.



In general: Markdown is too low for more technical writing so will probably be ruled out for our documentation.



## AsciiDoc:

https://asciidoctor.org/docs/what-is-asciidoc/

https://mister-gold.pro/posts/en/asciidoc-vs-markdown/

AsciiDoc stands out from the lightweight markup language group group because it supports all the structural elements necessary for drafting articles, technical manuals, books, presentations and prose.
In fact, it’s capable of meeting even the most advanced publishing requirements and technical semantics.

In general AsciiDoc is more user-friendly than ReStrcutred Text

## ReStructured Text

https://www.tompurl.com/2012-11-22-writing-a-book-with-vim.html

Rendering with restructured text is more difficult

https://matthewsetter.com/initial-sphinx-doc-workflow/



Phytonic markup for documentation is restructured text. The leading Python documentation build tool, shinx uses reST to build nicely structured documentation in a form familiar to any experienced Python developer/ : https://www.quora.com/How-do-I-document-a-Python-project-with-AsciiDoc





## Styling cheatsheet MD, rST, AsciiDoc

Asciidoct vs markdown: https://asciidoctor.org/docs/asciidoc-vs-markdown/

http://hyperpolyglot.org/lightweight-markup



## Other Languages

**HTML**: Hyper Text Markup Language, standard markup language for Web pages, elements (<>) are the building blocks of HTML pages.  Source: https://www.w3schools.com/whatis/whatis_html.asp

List of web site Generator: https://github.com/myles/awesome-static-generators

Kernel documentation: https://lwn.net/Articles/692704/



parsing = interpreting language, from unstructured text to tree

document generator



### Conclusion on the markup language itself

Ascii Doc seems to be more user friendly/intuitive that Restructured Text, HOWEVER, **not only the markup language is important, but also how it can be used**. And although some bloggers still prefer the restructured text language, sphinx is a widely used and community backed document generator. It has good how to get started tutorials and a wide community and it is more settled than the young Antora.

| reStructuredText | Docutils                                                     | Sphinx                  | ReadTheDocs                               |
| ---------------- | ------------------------------------------------------------ | ----------------------- | ----------------------------------------- |
| Markup language  | processing documentation into useful formats, such as HTML, XML, and LaTeX. | Documentation generator | hosts sphinx project - publicly available |
|                  |                                                              |                         |                                           |

| AsciiDoc        | AsciiDoctor                                                  | Antora                  | Hosting projects? Jekyll? |
| --------------- | ------------------------------------------------------------ | ----------------------- | ------------------------- |
| Markup language | text processor and publishing toolchain for converting AsciiDoc content to HTML5, DocBook, PDF, and other formats | Documentation generator |                           |
|                 |                                                              | Fairly new              |                           |

#### Discussion restructured text vs ascii doc (pro asciidoc)

http://forum.writethedocs.org/t/the-asciidoc-discussion/223/26



#### Pro Documenting using sphinx

https://medium.com/@richdayandnight/a-simple-tutorial-on-how-to-document-your-python-project-using-sphinx-and-rinohtype-177c22a15b5b



https://evaparish.com/blog/2018/10/19/antora-and-docusaurus-duke-it-out

https://evaparish.com/blog/2018/10/19/why-sphinx-and-rst-are-the-best

https://evaparish.com/blog/2018/10/19/in-which-i-vent-more-about-antora



#### Pro Documenting using Antora

https://matthewsetter.com/why-antora-is-the-leading-technical-writing-platform/
