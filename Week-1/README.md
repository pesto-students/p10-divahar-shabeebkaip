In today's digital age, browsing the internet has become a daily activity for most people. However, many users are unaware of how a browser fetches a web page from a URL and renders it for their use. In this assignment, we will delve into the details of how a browser works, the high-level components involved in the process, and the order of execution of scripts.


The main functionality of a browser

The main functionality of a browser is to fetch web pages from servers and render them for users. To achieve this, a browser uses various components such as the networking component, rendering engine, and parsers.

High-level components of a browser

The high-level components of a browser include the following:

1. User Interface: This component is what the user interacts with. It includes features such as the address bar, bookmarks, and navigation buttons.
2. Networking Component: This component is responsible for making HTTP calls to fetch web pages from servers.
3. Rendering Engine: This component is responsible for rendering HTML, CSS, and JavaScript to display web pages.
4. JavaScript Engine: This component is responsible for executing JavaScript code on web pages.
5. Data Storage Component: This component is responsible for saving data locally such as cookies and local storage.

Rendering engine and its use

The rendering engine is responsible for rendering HTML, CSS, and JavaScript to display web pages. It works by parsing the HTML document and creating a DOM (Document Object Model) tree. It then applies CSS rules to the DOM tree and creates a render tree. Finally, it uses the render tree to display the web page.

Parsers (HTML, CSS, etc)

Parsers are responsible for parsing HTML, CSS, and JavaScript code to create a DOM tree, CSSOM (CSS Object Model), and AST (Abstract Syntax Tree). The DOM tree represents the structure of the HTML document, the CSSOM represents the style rules of the web page, and the AST represents the structure of the JavaScript code.

Script Processors

The script processors are responsible for executing JavaScript code on web pages. They work by parsing the JavaScript code and creating an AST (Abstract Syntax Tree). They then use the AST to execute the JavaScript code.

Tree construction

Tree construction is the process of creating a DOM tree and CSSOM from HTML and CSS code, respectively. The rendering engine uses the DOM tree and CSSOM to create a render tree which is used to display the web page.

Order of script processing

The order of script processing is important because JavaScript code can modify the DOM tree and CSSOM which can affect the rendering of the web page. In general, JavaScript code is executed in the order it appears in the HTML document. However, JavaScript code can be deferred or async to improve the loading performance of web pages.

Layout and Painting

Layout is the process of calculating the position and size of each element in the render tree. Painting is the process of drawing each element on the screen. The rendering engine uses the render tree to perform layout and painting.

Conclusion

In summary, a browser fetches a web page from a server by using the networking component to make HTTP calls. It then uses the rendering engine, parsers, script processors, and data storage component to render the web page for the user. The rendering engine creates a DOM tree and CSSOM from HTML and CSS code, respectively, and then uses them to create a render tree which is used to display the web page. Finally, the layout and painting process is performed to draw each element on the screen. Understanding how a browser works is crucial for web developers and designers to optimize the user experience of their web pages.
