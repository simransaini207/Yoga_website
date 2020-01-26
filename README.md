# Yoga_website :)
What is HTML?
HTML is the language for describing the structure of Web pages. HTML gives authors the means to:

Publish online documents with headings, text, tables, lists, photos, etc.
Retrieve online information via hypertext links, at the click of a button.
Design forms for conducting transactions with remote services, for use in searching for information, making reservations, ordering products, etc.
Include spread-sheets, video clips, sound clips, and other applications directly in their documents.
With HTML, authors describe the structure of pages using markup. The elements of the language label pieces of content such as “paragraph,” “list,” “table,” and so on.

What is XHTML?
XHTML is a variant of HTML that uses the syntax of XML, the Extensible Markup Language. XHTML has all the same elements (for paragraphs, etc.) as the HTML variant, but the syntax is slightly different. Because XHTML is an XML application, you can use other XML tools with it (such as XSLT, a language for transforming XML content).

What is CSS?
CSS is the language for describing the presentation of Web pages, including colors, layout, and fonts. It allows one to adapt the presentation to different types of devices, such as large screens, small screens, or printers. CSS is independent of HTML and can be used with any XML-based markup language. The separation of HTML from CSS makes it easier to maintain sites, share style sheets across pages, and tailor pages to different environments. This is referred to as the separation of structure (or: content) from presentation.

What is WebFonts?
WebFonts is a technology that enables people to use fonts on demand over the Web without requiring installation in the operating system. W3C has experience in downloadable fonts through HTML, CSS2, and SVG. Until recently, downloadable fonts have not been common on the Web due to the lack of an interoperable font format. The WebFonts effort plans to address that through the creation of an industry-supported, open font format for the Web (called "WOFF").

Examples
The following very simple example of a portion of an HTML document illustrates how to create a link within a paragraph. When rendered on the screen (or by a speech synthesizer), the link text will be “final report”; when somebody activates the link, the browser will retrieve the resource identified by “http://www.example.com/report”:

<p class="moreinfo">For more information see the
<a href="http://www.example.com/report">final report</a>.</p>
The class attribute on the paragraph's start tag (“<p>”) can be used, among other thing, to add style. For instance, to italicize the text of all paragraphs with a class of “moreinfo,” one could write, in CSS:

p.moreinfo { font-style: italic }
By placing that rule in a separate file, the style may be shared by any number of HTML documents.
