Create

![](media/b3f4cf25cc2fd176c8e3df3360bbcab8.png)

**Create a PDF Embedded Viewer in your Application**

**Background**

When writing business applications you may need to view PDF files in your
application. But this requires that the user has to make use of an external PDF
viewer such as Adobe or use the OS’s default web-browser.

With PDF.js there is a chance to provide reliable and consistent PDF viewing
capabilities in your application. This blog provides the way forward on how to
integrate the PDF.js files into your own application.

PDF.js has mostly been developed by Mozilla which provides a JavaScript library
that makes it possible to render PDF files in a browser without using a browser
plugin. This library does the rendering but isn’t responsible for providing any
other functionality to the user like navigation, zoom levels or printing.

Additionally, there’s a complete viewer (implemented using html, CSS and
JavaScript) that does the things mentioned above with all the features
controlled within the browser.

As PDF.js uses many technologies provided by modern browsers only and does not
work with old browsers like Internet Explorer 8.

PDF.js is licensed under the “Apache License, Version 2.0” that makes it
possible to use it in your own application.

There two ways in which one might want to view a PDF-continuous page method or
PDF- Page by page method.

So how do you take advantage of the browser in offline state to open PDF files
directly within your application? Read on in my Blog to find out how to integrate both
methods is described.

[delphi-pdf-embedded-viewer-with-pdfjs](https://bayeseanblog.com/blog/delphi-pdf-embedded-viewer-with-pdfjs/21)

![](media/5f32c26e17cf7f32351f70833925b39d.gif)

**Tools**

-   IDE - Delphi 10.2.3 IDE using the INDY third Party components.

-   PDF.js JavaScript library.

-   Created in FMX - the code is portable to VCL.



Happy Coding
