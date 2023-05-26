# HTML

## CONTEXT
 - ABOUT HTML 
 - MARKUP
 - ELEMENTS & ATTRIBUTES IN HTML 
 - CHANGES BY HMTL IN SOFTWARE FIELD
 - WHY HTML IS SO IMPORTANT 
 - HOW HTML BECOME SO POPULAR 
 - CREATING A WEBPAGE BY HTML
 - PROS & CONS
 - OVER VIEW OF HTML

## CREATION OF HTML
HTML (Hypertext Markup Language) was created by a group of scientists and researchers at CERN (European Organization for Nuclear Research) in the late 1980s. The primary individuals credited with the creation of HTML are Tim Berners-Lee and his colleague Robert Cailliau.

![16747250](https://github.com/simplyshunnu/HTML/assets/127955482/f1cdde78-9951-48b9-aab2-2de0ead45505)


## Tim Berners-Lee &  Robert Cailliau

Tim Berners-Lee, a British computer scientist, is often considered the inventor of the World Wide Web. In 1989, while working at CERN, he proposed a system for information management that utilized hypertext, which laid the foundation for what would become HTML. Berners-Lee developed the first web browser called "WorldWideWeb" and the first web server. He also authored the first version of HTML along with the HTTP (Hypertext Transfer Protocol) and URL (Uniform Resource Locator) standards.

Robert Cailliau, a Belgian computer scientist and engineer, collaborated closely with Tim Berners-Lee on the development of HTML and the World Wide Web. Cailliau played a crucial role in refining and documenting the HTML language, as well as advocating for its adoption.

The early versions of HTML were relatively simple and focused primarily on structuring and linking documents. Over time, HTML evolved with the introduction of new versions and standards. The development and standardization of HTML have involved contributions from various individuals and organizations, including the World Wide Web Consortium (W3C), which is responsible for maintaining and updating HTML specifications.

It's important to note that while Tim Berners-Lee and Robert Cailliau played pivotal roles in the creation of HTML, the development of the web and HTML itself is the result of collaborative efforts from a broader community of researchers, programmers, and organizations.



##  MARKUP
 
 
HTML markup consists of several key components, including those called tags and their attributes, character-based data types, character references and entity references. HTML tags most commonly come in pairs like < h1 > , < /h1 >, although some represent empty elements and so are unpaired. The first tag in such a pair is the start tag, and the second is the end tag (they are also called opening tags and closing tags).

Another important component is the HTML document type declaration, which triggers standards mode rendering.

The following is an example of the classic "Hello, World!" program:

     <!DOCTYPE html>
    <html>
     <head>
         <title>This is a title</title>
    </head>
    <body>
    <div>
        <p>Hello world!</p>
    </div>
    </body>
    </html>
The text between <html> and </html> describes the web page, and the text between <body> and </body> is the visible page content. The markup text <title>This is a title</title> defines the browser page title shown on browser tabs and window titles and the tag <div> defines a division of the page used for easy styling. Between <head> and </head>, a <meta> element can be used to define webpage metadata.

The Document Type Declaration <!DOCTYPE html> is for HTML5. If a declaration is not included, various browsers will revert to "quirks mode" for rendering.
 
 
 
 ## ELEMENTS
 
HTML (Hypertext Markup Language) consists of various elements that define the structure and content of a web page. Here are some commonly used HTML elements:

  - ###  `<h1>` to `<h6>`: Heading elements  
           # Heading 1
 
 
           ## Heading 2
 
 
           ### Heading 3
 
 
           #### Heading 4
 
 
           ##### Heading 5
 
 
           ###### Heading 6
 
 - ### `<p>`: Paragraph element
   
          This is a paragraph.

 - ### `<a>`: Anchor element
 
           [Link Text](https://www.example.com)
 
 - ### `<img>`: Image element
               `![
                 Alt Text 
                 ](
                 image-url
                  )`

 - ### `<ul>` and `<li>`: Unordered list element
 
 
           -
            Item 1
          -
            Item 2
          -
            Item 3

 - ### `<ol>` and `<li>`: Ordered list element 
 
             1. 
              Item 1
             2. 
              Item 2
             3.
              Item 3

- ### `<div>`: Generic container element:
              
  
             (<
              div
              >
             Content goes here.
            </
               div
               >)

- ### `<span>`: Inline container element
 
            This is a 
            <
             span 
             style
              =
             "color: red;"
              >
             red
             </
             span 
             >
             text.

- ### `<table>`, `<tr>`, `<td>`, and `<th>`: Table elements       
 
                | Header 1 | Header 2 |
                |----------|----------|
                | Cell 1   | Cell 2   |
                | Cell 3   | Cell 4   |

 - ### `<form>` and `<input>`: Form elements
 
               <
               form 
                >
               
                
                < 
                input 
                type 
                = 
                "text"
                       
               name
               =
              "username"
                       
               placeholder
                =
                "Username"
                >
  
                
                <
                input 
                 
                type
                =
               "password"
                       
                name
                =
                "password"
                       
                placeholder
                =
               "Password"
                >

                
                
                <
                input
                       
                type
                =
               "submit"
                       
                value
                =
                "Submit"
                >

 
               </
                form
                >

 
 ## ATTRIBUTE
 
  `CLASS` ATTRIBUTE
 
             <
             div 
                  
              class
              =
              "container"
               >

                 Content goes here.
              </
              div
              >
 
 `ID` ATTRIBUTE
 
              <
              h1
                  
              id
              =
                  "my-heading"
                  >
               Heading
             </
               h1
               >
          
 `STYLE` ATTRIBUTE
 
                    <
                    p
                    style
                    =
                    "color: red"
                    >
                    This is a red paragraph.
                   </
                   p
                   >
 
 
       
 `src` attribute (for images)
 
 
                    ![
                     Alt Text
                     ]( 
                     image-url
                     )

 `href` attribute (for links)
 
                    [
                    Link Text
                    ](
                    https://www.example.com
                    )
     
` alt `attribute (for images)
 
                ![
                 Alt Text
                ](
                 image-url "Alternative text"
                 )

       
 
 Other attributes
 
 
                      <
                      input type
                        =
                        "text"
                        name
                        =
                        "username"
                        placeholder
                        =
                        "Username"
                        >

           

 
 ##  CHANGES BY HMTL IN SOFTWARE FIELD
 
 
 
 HTML (Hypertext Markup Language) plays a crucial role in the software field, particularly in web development. It serves as the foundational language for creating the structure and content of web pages. Here are some ways HTML has influenced and brought changes to the software field:

 - Web Development: HTML is the backbone of web development. It enables the creation of interactive and dynamic websites by providing a structure to organize content, define headings, paragraphs, lists, forms, tables, and more.

- Responsive Web Design: HTML, in combination with CSS (Cascading Style Sheets) and JavaScript, allows for responsive web design. Developers use HTML's semantic elements and CSS media queries to design websites that adapt and respond to different screen sizes and devices.

- Semantic Markup: HTML provides semantic elements like (< header >, < footer >, < nav >, < section >, and more,) which contribute to the organization and structuring of web content. This semantic markup enhances accessibility, search engine optimization (SEO), and understanding of the document's structure.

- Accessibility: HTML supports accessibility features, such as ARIA (Accessible Rich Internet Applications), which enable developers to create web content that is accessible to individuals with disabilities. HTML elements like < alt > attributes for images, < label > elements for form fields, and proper use of headings aid in creating accessible websites.

- Integration with Other Technologies: HTML integrates seamlessly with other technologies like CSS for styling and JavaScript for dynamic behavior. This trio of HTML, CSS, and JavaScript forms the foundation for interactive web applications, allowing for client-side scripting, animations, and user interactions.

- Web Standards and Compatibility: HTML is governed by standards set by the World Wide Web Consortium (W3C) and other organizations. These standards ensure consistency and compatibility across different browsers and platforms, making it easier for developers to create web applications that work well across various environments.

- Frameworks and Libraries: HTML forms the basis for many web development frameworks and libraries, such as React, Angular, and Vue.js. These frameworks provide abstractions and additional functionality to streamline the development process, making it easier to build complex web applications.

- Cross-Platform Development: HTML is a key component in hybrid mobile app development frameworks like Cordova and Ionic. These frameworks allow developers to leverage their HTML, CSS, and JavaScript skills to create mobile applications that can be deployed on multiple platforms.

Overall, HTML has revolutionized the software field by enabling the creation of visually appealing, interactive, and accessible web applications. It continues to evolve with new standards, features, and technologies, driving innovation in software development.
                           
  ## WHY HTML IS SO IMPORTANT
 
 HTML is of utmost importance because it serves as the fundamental language for creating web pages. It provides the structure and semantics necessary for organizing and presenting content on the internet. HTML enables the creation of accessible, search engine-friendly, and responsive websites. It acts as a common language understood by web browsers, ensuring cross-platform compatibility. HTML integrates seamlessly with CSS and JavaScript, enabling interactive and dynamic web experiences. With the increasing reliance on the internet for information and services, HTML remains crucial for web development, powering the digital world we navigate daily.
 
 
 ## HOW HTML BECOME SO POPULAR
 
 
 HTML became popular due to several factors. Firstly, it was developed as an open standard, allowing anyone to use and contribute to its development. Additionally, the rise of the internet and the World Wide Web made HTML the standard markup language for creating web pages. The simplicity of its syntax and ease of learning played a significant role in its popularity. Moreover, the continuous advancements in web technologies, such as the introduction of CSS and JavaScript, further solidified HTML's importance in creating dynamic and interactive websites. Lastly, the wide adoption and support by web browsers ensured its widespread usage and popularity.
 
 
 ## CREATING A WEBPAGE BY HTML
 
                 
 
                                         <!DOCTYPE html>
                                        <html>
                                          <head>
                                        <title> Dec </title>
                                            <style>
                                          body {
                                          font-family: Arial, sans-serif;
                                         }
                                               h1 {
                                              color: #333;
                                                   }
                                          p {
                                       font-size: 16px;
                                         }
                                      </style>
                                    </head>
                                     <body>
                                     <h1>Hii Sampling HTML to Create a WebPage </h1>
                                   <p>This is a sample page to Create a WebPage by using HTML
                                  <img src=>
                                   <ul>
                                   <li>Just Created to Test the HTML </li>
                                  <li>This Page is Created By Me  "Abdul"</li>
    
                                   </ul>
                                   </body>
                                    </html>


 IF YOU EXECUTE THIS CODE THE OUTPUT :![Screenshot 2023-05-26 134415](https://github.com/simplyshunnu/HTML/assets/127955482/c44d0ed9-9289-413b-a72a-902ffeb886e9)

 
 
 ## PROS & CONS OF HTML
 
 
 ### Pros of HTML:

-  Universal Compatibility: HTML is supported by all modern web browsers and is compatible with various platforms and devices, ensuring widespread accessibility.

-  Easy to Learn and Use: HTML has a simple syntax and is easy to understand, making it accessible for beginners. It doesn't require complex programming knowledge to create basic web pages.

-  Structured Content: HTML provides semantic elements that help organize and structure web content, making it easier for search engines to understand and index the information.

-  Integration with Other Technologies: HTML seamlessly integrates with CSS and JavaScript, allowing for enhanced styling, interactivity, and dynamic behavior on web pages.

-  Web Standard and Community Support: HTML is an open standard governed by the World Wide Web Consortium (W3C) and has a large and active community, providing resources, documentation, and support for developers.

### Cons of HTML:

-  Limited Interactivity: HTML is primarily a markup language for structuring content. While it supports basic interactivity through JavaScript, it has limitations compared to more advanced programming languages.

-  Limited Styling Capabilities: While HTML provides some basic styling options, its capabilities are limited compared to CSS. Complex styling and design features often require additional CSS rules.

-  Accessibility Challenges: While HTML supports accessibility features, ensuring a fully accessible web page requires additional considerations, such as proper labeling, ARIA attributes, and adherence to accessibility guidelines.

-  Browser Compatibility Issues: Although HTML is a standard, different web browsers may interpret and render HTML code differently, leading to potential inconsistencies in appearance and behavior across browsers.

-  Static Nature: HTML primarily defines the structure and content of web pages. It lacks the ability to dynamically generate content or perform complex server-side operations, which may require additional technologies.

Understanding the pros and cons of HTML can help developers make informed decisions and leverage its strengths while mitigating its limitations.
     
 
 
 
 ##  OVER VIEW OF HTML
 
 
 HTML (Hypertext Markup Language) is a standard markup language used for creating web pages and structuring their content. It provides a set of elements and tags that define the layout, text, images, links, and other components of a web page. HTML allows for the organization and hierarchy of content through headings, paragraphs, lists, tables, and more. It also enables the inclusion of media elements such as images and videos. HTML is the backbone of the World Wide Web and works in conjunction with CSS (Cascading Style Sheets) and JavaScript to create visually appealing, interactive, and accessible web pages.
