### Tags
Every HTML5 file needs to have 4 tags as the outset.
- **DOCTYPE** - indicate the version and type of document. ![[Pasted image 20230114233430.png]] This describes an html5 document. 
- **html** - indicates the start and end of the html CODE in the document. 
- **head** - contains information that describes the webpage but does not  show on it.
- **body** - contains information that describes how the webpage will look (contains infromation that shows on a webpage).

### Head tags
- link - allows us to link to external files such as stylesheets(css), or scripts(javascript). Files that accentuate the page.
- meta - Tags that describe the data. Such as the character set (utf-8 or utf-16). ![[Pasted image 20230114232405.png]] These are examples of what the meta tag can contribute to:
	- charset - utf-8 supports character 1-4 bytes long. All basic characters. utf-16 should be used for chinese or cyrillic characters.
	- keywords - helps search results for the search engine.
	- description - a text the search engine will display as a description for the website. 
	- viewport - tells the browser how to render the webside across devices. 
	- google - hinders google translate from translating you website.
- title - the text that will display on the flap of the webpage.  

### Body tags
- script - hold scripts from programming languages
- noscript - Shows the information inside of it if browser does not support the language in the script tag. 

### Void Elements
Void elements are tags that do not have closing tags. This is because they are self-contained or do not contain any data.

### Entities
Entities are little pieces of html-code that the compiler interprets as symbols. They are star with the *&* symbol followed by the name of the entity and they end with a semicolon.  ![[Pasted image 20230114234841.png]]