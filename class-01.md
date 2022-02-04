## Table of Readings
  
<br>
 
|Book| Chapter | Topic |
|:---:|:---:| :---: |
|Duckett: HTML and CSS| [Introduction](##-html-and-css-introduction) |About this Book|
|Duckett: HTML and CSS| [Chapter 1](##-html-and-css-chapter-1) | Structure|
|Duckett: HTML and CSS| [Chapter 8](##-html-and-css-chapter-8) |Extra Markup|
|Duckett: HTML and CSS| [Chapter 17](##-html-and-css-chapter-17) |HTML5 Layout|
|Duckett: HTML and CSS| [Chapter 18](##-html-and-css-chapter-18) |Process & Design|
|Duckett: JavaScript and jQuery| [Introduction](##-javascript-and-jquery-introduction) |About this book|
|Duckett: JavaScript and jQuery| [Chapter 1](##-javascript-and-jquery-chapter-1) | The ABC's of Programming|
  
<br> 
 
## HTML and CSS Introduction
 
 <br>
 
##### Sub sections:
1. About this book
2. How the web works
3. Learning from other pages


1. About this book :
  Introduction: There are intro pages for each chapter, introducing the key topics of each chapter <br>
  Reference: which introduce the key pieces of HTML/CSS code. HTML in blue and CSS in pink <br>
  Background: white pages that explain the context <br>
  Diagram: dark pages showing infographics. Simple visual reference  <br>
  Example: show a working example of the key topics <br>
  Summary: summarize what the chapter went over <br>
  
  
 Is it hard to learn? No! Code can look complicated at a glance but if you take the time to break it down piece by piece it's rather simple and follows logical rules.  <br>
 
 Structure of this book: Three sections   <br>
      Section 1.HTML: first chapter will look at HTML and how its used to create web pages. <br>
        you can start by simply writing what you want to appear on your page <br>
        then you add tages or elements to the words so that the browser knows what you want each set of words to be, a heading or a paragraph as an example.  <br>
        the rest of this section will introduce us to the tags at our disposal with HTML <br>
           * texts <br>
           * links <br>
           * images <br>
           * tables <br>
           * forms <br>
           * video audio <br>
           * flash <br>
           * miscellaneous elemets <br>
        these may not be the most exciting but theyre important building blocks <br>
      
      Section 2. CSS: This section starts with how CS uses rules to style your HTML webpages <br>
        Look at a variety of CSS properties. Generally these properties fall into one of two categories: <br>
             Presentation: How to control things such as color of text, fonts, size of text, background colors, and background images <br>
             Layout: These control where the different elements are positioned on the screen. Making the site more attractive <br>
        
      Section 3: Practical: The book ends with some helpful info that helps in building better websites.  <br>
        Some new tags for HTML5 which help describe the structure of the pages. (HTML5 being the newest version of HTML) <br>
        Before learning this it's important to have a grasp on CSS.  <br>
        These chapters will talk about the design process that I can follow in creating a new site <br>
        Then there are topics that will help us put it on the web, Search Enginge optimisation (SEO) and analytics software to track who comes to the site <br>
      
How people access the web: <br>
      Browsers: such as chrome, firefox, safari etc. <br>
      Web servers: When you use your brower the request of going to a site is sent to a webserver which hosts the site. <br>
                   web servers are computers that are constantly connected to the internet and optimized to send web pages. <br>
                   Some big comparies run their own webservers but its more common to use the service of a webhosting company <br>
      Devices: Desktops, laptops, tablets, mobline phones.  <br>
      Screen Readers: Programs that read out the contents of a computer screen to the user. <br>
                      It's important to keep in mind screen readers when you're desiging your code  <br>
                      Throughout this book we'll see references to them and how to ensure our site are accessible to people who use this software <br>
                      
How Websites are created: : All websites used HTML and CSS but content management systems, blogging software, and e-commerce platforms often add a few more technologies. <br>
       What you see: web browser interprets the HTML/CSS code you create.  <br>
                     Most sites include extra content such as images, audio, video, or animations. <br>
                     Some sites also send JavaScript or Flash, these are advanced topics touched on later (different book) <br>
       How it is created: Small websites just use HTML/CSS <br>
                          Larger websites make use of technologies that are used to produce HTML and CSS that is sent to the browser <br>
                          More complex sites may use a database to store data, and programming languages such as PHP, ASP.net Java or Ruby on a web server.  <br>
       HTML5 & CSS3: These are the most recent versions oF HTML and CSS, they build on previous versions of the languages.  <br>
       
       
How the web works: Communication between your computer and a Domain Name System (DNS) server  <br>
                   1. Connect to the web vis Internet service provider (ISP) <br>
                   2. Computer contacts a network (DNS) <br>
                   3. Unique number of DNS server returns to your computer and allows the browers to contact the web server.  <br>
                   4. Web server sends back the page you requested <br>
 
 
 
## HTML and CSS Chapter 1
 
 Chapter One:Structure  <br>

##### Key Topics:
            1. Understanding Structure <br>
            2. Learning about markup <br>
            3. Tags and Elements  <br>
   
Many web pages are just electronic versions of documents that have been around for ages. <br>
    Newspapers, Insurance forms, shop catalogues etc.  <br>
    And they generally follow the same structure of their non-electronic counterparts <br>
    
Structure is used to draw the eye to the important information  <br>
      a heading is larger to separate sections of a document, and give the reader a quick easy reference for which part of the document theyre viewing <br>
      heading types and sizes can also quickly display a hierarchy of information.  <br>
      Biggest heading could be a title to an article, while a smaller heading could be a subsection to said article <br>

HTML describes the structure of pages <br>
      You can use HTML to create these headings, and the information below each heading <br>
      
          Example Code: <br>
              <htmL>
                <body>
                  <h1> Heading! </h1>
                  <p> some text about the topic, maybe an introduction </p>
                  <h2> Sub-heading! </h2>
                  <p> some more imformation about the topic at hand </p>
                  <h2> Another Sub-heading! </h2>
                  <p> More info about this second subheading </p>
                 </body>
                </html>
       
       In the angled brackets above you see HTML elements. they're made up of two tags, an opening and a closing tag.  <br>
       Each element tells the browers something about the info that is between the two tags. <br>
       
       <html></html> are the tages that indicate that anything between these two elements are HTML code <br>
       <body></body> tag indicates that anything within these elements are shown in the main browser window <br>
       <h1-6></h1-6> indicate headers. 1 being the largest text, 6 being smallest <br>
       <p></p> indicate paragraphs <br>
       
       <p></p> analysis: <br>
       < = left angle bracket : Opening of a tag <br>
       p = character : indicate the tags purpose <br>
       >  = right angle bracket : closing of a tag <br>
       / = forward slash : needed to indicate the tag is the end of a set.  <br>
       
 Attributes can tell use more about elements  <br>
      attributes provide additional info about the contents of the element.  <br>
      They appear within the opening tag and are made up of a two parts <br>
        1. Name <br>
        2. Value  <br>
          The two parts are separated by an equal sign <br>
         
            Example Code: <br>
                <p lang ="en-us"> Paragraph in the english language</p> <br>
                
                lang = attribute name <br>
                en-us = attribute value  <br>
                
             Alternate example: <br>
                <p lang="fr">Paragraphe en Francais</p> <br>
                
                lang = name <br>
                fr = value <br>
                
                **HTML5 allows yuo to use upercase attribute names and omit the quotemarks but it is best practice to use lowercase and quote marks. <br>
                
                
Body Head and Title <br>
      Body: <body></body> everything in this element is in the main browser window <br>
      Head: <head></head> this contains info about the page, you'll usually find <title> in the <head> element <br>
      Title: <title></title> this is shown at the top of the brower, the tab title,  <br>
              allowning you to quickly discern which tab you want to go to when you have multiple open <br>
    
    HTML stands for HyperTextMarkup Language.  <br>
       Hypertext: refers to the fact that HTML allows you to create links to other pages.  <br>
       Markup language: allows you to annotate text. Providing additional meaning to the content of the document <br>
                         tags we add count as markup <br>
                        
    
    Creating a webpage on a PC <br>
      All you need to create a webpage is a text editor such as Notepad <br>
      There is also a free version Nodepad++ (notepad-plus-plus.org)  <br>
      
            code:  <br>
              <html>
                <head>
                  <title> My first Web Page </title>
                 </head>
                 <body>
                  <h1> Welcome to my first webpage! </h1>
                  <p>This is an HTML page I created in Notepad </p>
                 </body>
                </html>
                
         Save the file as an .html extension  <br>
        Start the web browser and go to file menu and open, select the file and open it.  <br>
         There's your first webpage! <br>
         
Coding in a content management system <br>
  If you're working with a content management system, such as a blogging platform or an e-commerce application.  <br>
    you'll typically log into a special admin section to control a portion of the website.  <br>
    This means you wont see the whole inner code of the webpage but just a sub section of the website.  <br>
    
 Looking at how other sites are built <br>
  You can look at how any webpage is made via code by looking at by using "view source" or by pressing f12 on windows  <br>
  
##### Chapter 1 Summary: 
 - HTML pages are text documents <br>
 - HTML uses text tags to give info a meaning <br>
 - Tags are referred to as elements <br>
 - Tags come in pairs, opening and closing <br>
 - Opening tags can carry attributes, telling us more about the content within the tags <br>
 - Attributes require a name and a value  <br>
 - To learn HTML you need to know what tags are available for you to use, what they do, and where they can go <br>
        

## HTML and CSS Chapter 8
  Chapter 8: Extra Markup (p176-199) <br>

##### Key Topics: 
  - Specifying different versions  <br>
  - Identifying and Grouping Elements  <br>
  - Comments, meta information and iframes  <br>
  
  Helpful topics covered in this chapter: <br>
    - Different versions of HTML and how to indicate which version youre using <br>
    - how to add comments to code <br>
    - global attribute: which can be used on any element (class and id attributes) <br>
    - elements that are used to group together parts of the page  <br>
    - how to embed a page within a page using iframes <br>
    - add info about a page using <meta> <br>
    - add characters such as angled brackets and copyright symbols <br>
    
  
  Versions of HTML:  <br>
    HTML 4(1997) Most the same as HTML5 but used presentational elements that arent recommended anymore, such as <center> and <font> <br>
    XHTML 1.0 (2000) HTML was reformated to follow rules of XML.  <br>
                     Made it so every elemeted needed a closing tage besides imgs <br>
                     Attribute names had to be lowercase <br>
                     attributes required a value and values were put in quotes <br>
                     deprecated elements should no longer be used <br>
                     every element that was opened inside another element should be closed inside the same element <br>
                  Two flavors of XHTML: <br>
                          strict: author had to follow rules to the letter <br>
                          transitional: could still use <center> <font> etc.  <br>
                       A third was called: Frameset. allowing authors to partition windows into several frames, each holding different HTML code <br>
                                           These are very rarely used, being phased out.  <br>
     HTML5 (in progress during this books publication process): authors dont need to close all tags, new elements, new attributes  <br>
     
    
  DOCTYPES <br>
      The doctype allows the webpage to know which type of HTML you are using <br>
      
      HTML5 : <!DOCTYPE html> <br>
      HTML4 : <!DOCTYPE html PUBLIC -- links found on pg 181> <br>
      Transitional HTML1.0/Strict HTML1.0 Same as HTML4 but different links, on pg 181 <br>
      XML Declaration : <?xml version="1.0" ?> <br>
      
   Comments in HTML <br>
        to write comments (not included in the code but rather a note to whoever is reading the code) use <!-- Comment here! --> <br>
        
   ID attribute:  <br>
         Every element can carry an ID attribute. start with an underscore(_) or a letter, no other character and make sure never to use repeat ID's for elements. <br>
         this allows you to call each ID and treat them differently. (with HTML or with CSS or JS later)  <br>
         ID is known as a global attribute, because it can be used on any element <br>
    
   Class Attribute:  <br>
         Every element can carry a class attribute  <br>
         This allows you to indetify more than one element with the same class. <br>
         Example: some elements you might want to class as important  <br>
         
   Block Elements:  <br>
        Some elements will always appear to start ona new line in the browser window.  <br>
          Examples of elements are  < h1> < p> < ul> or < li>  <br>
  
 <br> 
 
   Inline elements: 
         Some elements will always appear to coninue on the sameline, as their neighboring elements. These are Inline <br>
          Examples of inline elements are <a> <b> <em> or <img> <br>
   
   Grouping Text and Elements in a Block <br>
        <div> element allows you to group of a set of elements together <br>
          Example: us <div> to contain all the elements in a headers of your site  <br>
                    such as the logo and navigation links <br>
          You can use an id or class attribute on a div element to create a CSS style rule for the whole block <br>
          div also allows you to organize your code  <br>
          
    Grouping Text and elements Inline <br>
        <span> element acts like an inline equiv to <div>  <br>
            It's used to either:  <br>
                1. Contain a section of text where there is no other suitable element to diffrentiate it from its surrounding text <br>
                2. Contain a number of inline elements <br>
         Most common reason people use <span> is to control the appearance of the content of these elements using CSS <br>
            You will ususally see that a class or id is used with <span> elements, so as to: <br>
                - Expain the purpose of the span element <br>
                - so CSS styles can be used to style just that element within the element.  <br>
                 
      Iframes: <br>
        <iframe> is like a little window that has been cut into your page <br>
              Example of iframe: google maps <br>
                                  the content within an iframe can be any HTML code <br>
               Created by using an <iframe> element <br>
                  You'll need to know a few attrbutes to use iframes <br>
                        src : specifies URL of page shown in the frame <br>
                        height : specifies pixels alloted for height of frame <br>
                        width : specifies pixel alloted for width of frame <br>
                        scrolling: (not supported in HTML5) but was usedto indicate whether iframe had scroll bars, if page was larger than alloted space <br>
                                    yes = show, no = dont show, and auto = show only if needed <br>
                        frameborder: (not supported in HTML5) whether the grame should have a border or not <br>
                        seamless: new in HTML5, applied to iframe where scrollbars arent desired. Doesnt need a value, but you'll often see values anyway.  <br>
                                  Older browers don't support seamless attribute.  <br>
                
       Information about your pages: <br>
          <meta> element lives inside the <head> portion of your code and contains info about the webpage <br>
            It's not visible to the users but can help by telling the search enginges about your page <br>
              Info such as: author of page, whether or not it is time sensitive (if it is time sensitive it can be se tto expire)  <br>
             <meta> is an empty element so it doesn't need a closing tag <br>
                     and uses attribute to carry the info <br>
                        Most common attributes: name and content which are usually used together <br>
                        
              Value of the name attribute can be anything you want it to be. <br>
              Some defined values for this attribute that are commonly used: <br>
                Description: Contains description of page <br>
                             Example code: <br>
                                <meta name = "Description"
                                    content = "An Essay on Installation" /> <br>
                Keywords: list of comma, separated words the user might search t <br>o find the page (in practice this no longer has any noticable effect) <br>
                          Example: <br>
                            <meta name = "keywords"
                                contents ="installation. art. opinion" />
                Robots: whether search enginges should add this page to their search or not.  <br>
                          noindex: should not be added <br>
                          nofollow: should add to results but not the pages that it links to <br>
                            example: <br>
                              <meta name = "robots"
                                  content = "nofollow" /> <br>
                       
            The <meta> element uses http-equiv and content attributes in pairs.  <br>
              Three instances of http-equiv attributes: <br>
                  1. author : defines the author of web page <br>
                              Example: <br>
                                   <meta http-equiv="author"
                                     content="Eden" /> <br>
                  2. pragma : prevents browser from caching page <br>
                               (where caching is storing it locally to save time downloading it on subsequent visits) <br>
                               Example: <br>
                                    <meta http-equiv="pragma"
                                      content="no-cache" /> <br>
                  3. expires : because browsers often cache the contents of a page, the expires option indicates when that cache expires.  <br>
                                date must follow example: <br>
                                    <meta http-equiv="expires"
                                      content="Fri. 04 Apr 2022 23:59:59 PST" />  <br>
                                      
 Escape Characters <br>
    There are characters that are used and reserved by HTML code (Such as < and > )  <br>
      Therefore if you want the characters to appear within your page you need to use the escape characters <br>
      You can use the escape codes: &1t; or &#60; if you want to use < in your page.  <br>
      You can find these escape codes on page 194 of Duckett HTML/CSS book  <br>
      some common ones  <br>
      < = &lt; <br>
      > = &gt; <br>
      & = &amp; <br>
      " =&quot; <br>
      copyright = &copy; <br>
      trademark = &trade; <br>
      registered trademark = &reg; <br>
      multiplication = &times; <br>
      Division = &divide; <br>
      left single quote/double quote = &lsquo; / &ldquo; <br>
      right single quote/double quote = &rsquo; / &rdquo;  <br>
      

##### Summary Chapter 8 Eztra Markup: <br>
  
  - DOCUTYPES tell browser which version of HTML you are using <br>
  - You can add comments <!-- --> <br>
  - id and class attributes allow you to identify particular elements <br>
  - <div> and <span> elements allow you to group block-level and inline elements together <br>
  - <iframes> cut windows into your webpage <br>
  - <meta> tag allows you to supply all kinds of info  <br>
  - escape characters are used to include special characters <br>
         

         
## HTML and CSS Chapter 17 <br>
        Chapter 17: HTML5 Layout <br>

##### Key Topics <br>
    - HTML5 Layout Elements <br>
    - How old browers understand new elements <br>
    - Styling HTML5 Layout elements with CSS <br>
     <br>
   
   
Before HTML5 You would use <div> to id parts of a page such as the header, the navigation bar, and different articles within a page <br>
      before: <\ div id = "header">  <br>
        After: <\ header> <br>
      before: <\ div id = "'nav"> <br>
        after: <\ nav> <br>
      before: <\ div id = "content"> <br>
                <\ div class = "article"> <br>
                <\ div class = "article"> <br>
        after: <\ div id = "content"> <br>
                 <\ article> <br>
                 <\ article> <br>
      before: <\ div id = "footer"> <br>
        after: <\ footer> <br>
        
        
 Headers and Footers <header> <footer> <br>
    The main header or footer appear at the top and bottom of the page respectably  <br>
    There can also be a header or footer for each individual article within a page as well.  <br>
    <section> can also have a header or footer.  <br>

Navigation <\ nav> <br>
    the nav elementis used to contain the major navigational blocks on the site <br>
    this is usually a unordered list with each list item containing a link within the site <br>
        either to other pages of the site or down to a portion of the same page that is indicated with an id <br>
        
 Articles <\ article> <br>
    Article elements act as contianers for any secction of a page that could stand alone.  <br>
        such as a blog entry, a comment, or a forum post  <br>
     A page can contain multiple articles, each having their own opening and closing article tags <br>
        Article tags can even be nested within each other.  <br>
        
 Asides <\ aside> <br>
    An aside element has two purposes depending on whether it is inside or outside an <\ article> element <br>
        1. inside an <\ article> it should contain info related to the artile but not essential to the overall meaning <br>
            (So a pullquote or glossary might be an aside) <br>
        2. outside of an article, an <\ aside> can act as a container for content that is related to the entire page. <br>
            (Might be links to other sections of the site, a list of recent posts, a search box, etc) <br>
            
 Sections <\ section> <br>
     The <\ section> element groups related content together. <br>
     Typically each section will have its own heading <br>
        Example: homepage might have several sections <br>
                    - latest news <br>
                    - top products  <br>
                    - newsletter sign ups etc. <br>
         Alternatively: long articles can be split up into separate sections <br>
      Section should not wrap the entire page, that's still best left for <div> <br>
     
Heading Groups: <\ hgroup> <br>
    Purpose for <\ hgroup> element is to group together a set of one or more <h1-6> elements so that they are treated as one single heading.  <br>
          Example: hgroup elements could be used to conain both a title inside <\ h2> and a subtitle within <\ h3> <br>
                <\ hgroup>
                  <\ h2>Vegetarian</h2>
                  <\ h3>Five week course</h3>
                <\ /hgroup>
     
     This element has mixed reception. Some say it has little use.  <br>
     
Figures <\ figure> <\ figcaption> <br>
    figure used to contain content in reference from mainflow of article <br>
    examples: <br>
        - images <br>
        - videos <br>
        - graphs <br>
        - diagrams  <br>
        - code samples <br>
        - text that supports main body <br>
        
       <\ figure> should contain <\ figcaption> to provide a text description for contents  <br>
            can be added within an article element  <br>
            
Sectioning Elements <\ div> <br>
    <\ div> will always remain important for grouping related elements  <br>
  
Linking around block-level elements <br>
    html5 allows authors to place a link <a> element around a block level element, turning the whole block into a link <br>
    
Helping older browsers understand <br>
    old browsers dont know the new HTML5 elelements and will treat them as inline elements  <br>
    
    CSS: <br>
    header, section, footer, aside, nav, article, figure, figcaption {
      display: block;} <br>
      
    HTML: <br>
    <!--[if lt IE 9]
        <script src="http://htm5shiv.googlecode.com/svn/trunk/html5.js"></script>
     <![endif]-->
      <br>
     
Nice code examples on pg 445-448** <br>

##### Summary Chapter 17  <br>
      - new HTML5 elements indicate the purpose of different parts of a web page and help describe its structure <br>
      - new elements provide clearer code <br>
      - older browers don't understand HTML5 need a workaround <br>
 
     
     
## HTML and CSS Chapter 18 <br>
     Chapter 18 Process and Design <br>

##### Key topics: <br>
    - How to approach building a site <br>
    - Understanding your audience and their needs <br>
    - How to present information visitors want to see <br>
    
    
    Lookin at: <br>
        - What's your audience? <br>
        - How to organize info <br>
        - Design theory <br>
        - Design tips <br>

Who? <br>

  Target Audience: <br>
      -Age? <br>
      -Gender? <br>
      -Country? <br>
      -Urban/Rural? <br>
      -Avg. Income? <br>
      -Education level? <br>
      -Family status? <br>
      -Occupation? <br>
      -Web use frequency? <br>
      -Device to access site? <br>
    
    Company: <br>
      -Size of company? <br>
      -Position of individual? <br>
      -Site for self or others? <br>
      -Budget? <br>
      
 Why are they visiting your site? <br>
    -entertainment or other goal? <br>
    -personal or professional goal? <br>
    -essential or luxury? <br>
    
 What are they trying to achieve? <br>
     -List of tasks you want your site to achieve <br>
     
 What info does your site need? <br>
 
How often will people visit your site? <br>

Site maps: <br>
Home: <br>
  About: <br>
      History <br>
      Foundation <br>
      Future Plans <br>
  Articles: <br>
      news <br>
      book reviews <br>
      press <br>
      interviews <br>
  Visit: <br>
      Location <br>
      Opening times <br>
      tickets <br>
  Shops: <br>
      Books <br>
      Gifts <br>
  Contact: <br>

Wireframes: <br>
  a simple sketch of the key information that needs to go on each page of the site.  <br>
    Shows a hierarchy of the information and how much space it might requires <br>
    
 Getting your message across using design: <br>
  The primary aim of any kind of visual design is to communicate.  <br>
  organization and prioritizing info on a page helps the users to understand its importants and how to read the site <br>
  
  Content:  <br>
      Logo <br>
      Navigation <br>
      Links to related content <br>
      Login or membership options <br>
      Ability for users to comment <br>
      Copyright info <br>
      Links to polocies <br>
      
    Prioritizing: <br>
      make important features distinct, use sizes and colors and location to your advantage <br>
      
    Organization: <br>
        Use grouping of like functions for ease of access for users.  <br>
        
   Be consistent in your style and colorings.  <br>
   
   Concise: navigation should be quick and easy to read  <br>
   Clear: Site should be predictable <br>
   Selective: Dont put everything together, put navigation at one place, contact info at another, login options in another <br>
   Context: provide context to let userrs know where they are in a site <br>
   Interactive: links should be interactive, big enough to click on, change when the user hovers over them. different than other text on the page <br>
   
   
##### Summary Chapter 18 Process and Design: <br>
      - Its important to understand who your target audience is, why they would come to your site, what info they wantto find and when they are likely to return <br>
      - site maps allow you to plan the structure of a site <br>
      - wireframes allow you to organize the information that will need to go on each page <br>
      - design is about communication. visual hierarchy help visitors understand what you are trying to tell them <br>
      - you can differentiate between pieces of info using size, color, and style <br>
      - you can use grouping and similarity to help simplify the info you present.  <br>
 

     
## JavaScript and jQuery Introduction <br>
Introduction: JavaScript and Jquery: interactivr front-end web development  <br>


Javascript makes web pages more interactive <br>

1. Access content  <br>
    You can us JS to select any element, attribute or text from an HTML page  <br>
        - Select text from h1 on a page <br>
        - select any element with a class attribute with a value of note <br>
        - find out what was entered into text input whose id attribute has a value of email <br>
2. Modify content  <br>
    You can use JS to add elements, attributes and text to the page, or remove them.  <br>
        - add a paragraph of text after the first h1 element <br>
        - change the value of class attribute to trigger new css rules for those elements  <br>
        - change the size or position of an <img> element <br>
3. program rules <br>
    You can specify a set of steps for the browers to follow (like a recipe) which allows it to access or change the content of the page <br>
        - gallery script could checkwhich img a user cliced on and display a larger version of that img <br>
        - a mortgage calculator could collect values from a form, perfrm a calculation and display repayments <br>
        - an animation could check the domensions of the browers window and move an image to the bottom of the viewable are (also known as the viewport) <br>
4. React to events <br>
    you can specify that a script should run when a specific event has occurred. <br>
        - a button is pressed <br>
        - a link is clicked <br>
        - a cursor hovers over an element <br>
        - information is added to a form <br>
        - an interval of time has passed <br>
        - a web page has finished loading <br>
        
       
Structure of the book: <br>

Core Concepts by Chapter: <br>
    1. Key concepts in programming, show how computers creat odels using data, how JS changes content of HTML page <br>
    2-4. basics of JS language <br>
    5. explain document object model (DOM), access and change a documents contents while its loaded into the browser <br>
    6. discuss how events an be used to trigger code <br>
    7. show how jquery can make the process of writing scripts faster and easier <br>
    8. introduce  Ajax, set of techniques that allow you to change part o the webpage without relaoding it <br>
    9. application programming interfaces (API)  <br>
    
 Practical Applications by Chapter: <br>
    10. deal with error handling and debugging, explain how JS is processed <br>
    11. techniques for creating content panels (sliders, modal windows, tabbed panels, accordians) <br>
    12. techniques for filtering and sorting data. (filter gallery imgs and reordering the rows of a table by clicking on column headings) <br>
    13. deal with form enhancements and how to validate form enteries <br>
    
    
    
##### CSS Refresher: <br>
  .fruit {color: pink;} <br>
  .fruit = selector <br>
  color = property name <br>
  pink = property value  <br>
  {} = declaration block <br>
     
     
## JavaScript and jQuery Chapter 1 <br>
 
##### Chapter 1: The ABCs of programming <br>

A. What is a script and how do I create one.  <br>
B. How do computers fit in with the world around them? <br>
C. How do I write a script for a web page?  <br>

A. Script is a set of instructions <br>
    like a recipe, a handbook, or manuals.  <br>
    Scripts are made up of a instructions a computer can follow step-by-step <br>
    A browser may use different parts of the script depending on how the user interacts with the webpage <br>
    Scripts can run different sections of the code in response to the situation around them  <br>
    
    To write script first: state your goals. list the tasks that need to be completed in order to achieve it.  <br>
       1. Define the goal <br>
       2. design the script <br>
       3. code each step  <br>
       
     Flow chart: Tasks of a hotel cleaner <br>
     Check each room <br>
        Does the room need tidying? <br>
              yes: tidy room  <br>
                    Step1 remove bedding <br>
                    2 wipe all surfaces <br>
                    3 vacuum floor <br>
                    4 fit new bedding <br>
                    5 remove used towels and soaps <br>
                    6 clean toilet bath sink and surfaces <br>
                    7 place new towels and soap <br>
                    8 wipe bathroom floor <br>
                    9 repeat check <br>
              no: move to next step <br>
         Does the mini bar need restocking? <br>
               yes: restock then run check again <br>
               no: move to next step <br>
         Move to next room <br>
      
Need to learn:  <br>
    Vocabulary: text that computer understands <br>
    Syntax: how to put that text into instructions the computer can follow <br>
Computers solver problems programmatically, by following a series of istructions on after the other.  <br>
  Type of instructions they need are often different from the type we as humans would need, Needs step by step instructions  <br>
  
  To design the script you should draw out a flowchart <br>

##### Summary of 1A: <br>
- script is a series of instructions that the cmputer can follow in order to achieve a goal <br>
- each time the script runs, it might only use a subset of all instructions <br>
- computers approach the task in a different way than humans, so your instruction must let the computer solve the task programmatically <br>
- to approach writing a script break down your goal into a series of tasks then work out each step needed to complete the task (a flowchart can help) <br>


#### Chapter 1B: How do computers fit in with the world around them? <br>

Computers create models of the world using data.  <br>
    Objects: things: each object can have its own <br>
        - properties <br>
        - events <br>
        - methods <br>
     Properties : characteristics : each property has <br>
        - name <br>
        - value <br>
       
    Events: What is an event? <br>
        The computers way of sticking up its hand and saying "hey this just happened" <br>
    What does an event do? <br>
         The programmers choose which eventsthey respond to.  <br>
         When specific events happen, that even can trigger apsecific sections of the code <br>
         
     Methods: represent things people need to do with objects.  <br>
          They can retrieve or update the values of an objects properties  <br>
        What is a method? <br>
            Methods typically represent how people or other things interact with an object in the real world.  <br>
        What does a method do?  <br>
             The code for a method can contain lots of instrctions that together represent one task.  <br>
             
   Example: <br>
   Objecttype: document <br>
   Properties:  <br>
      URL: www.example.com/ <br>
      Last modified: today! <br>
      title: learning code <br>
    Event: Happens when <br>
       load : page and assests have loaded <br>
       click : user clisk something <br>
       keypress : user pressed key <br>
     Method: what it do <br>
        write() : adds new content to the docment  <br>
        getElementByld() accesses an element when you state its id attribute <br>
        
        
  How a browers sees a web page <br>
     1. receieve a page as HTML code <br>
     2. create a model of the page and store it in memory <br>
     3. use a rendering engine to show the page on screen <br>
     
###### Summary of chapter 1B How do computers fit in with the world around them?  <br>
    - computers create models of the world using data <br>
    - the models use objects to represent physical things.  <br>
            objects can have: properties that tell us about the object;  <br>
            methods that perform tasks using the properties of that object;  <br>
            events which are triggered when a user interacts with the computer  <br>
     - programmers can write code to say "when this event occurs, run that code" <br>
     - web browsers use HTML markup to create a model of the web page. Each element creates its own node  <br>
     - to make webpages interactive, you write code that uses the browser's model of the web page <br>
     
  
#### Chapter 1C How do I write a script for a webpage? <br>
  
  HTML : content layers <br>
  CSS : presentation layer  <br>
  JS : behavior layers  <br>
  
  Link your JS to your HTML files  <br>
  
###### Summary 1C  <br>
  - keep your JS codein its own JS file.  <br>
  - HTML <script> element is used in HTML pages to tell the brower to load the JS file  <br>
  - view the source code of the page in the browers. JS will not change the HTML, script works with the model of the web page that the browser has created. <br>
