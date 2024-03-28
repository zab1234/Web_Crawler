# webCrawler

Our program works as a web crawler for the Facebook sight. After initializing command-line arguments, it sets up the crawler with server details and the user information. The Crawler class sends HTTP requests and manages the cookies as well as the sessions. As it runs, it extracts hyperlinks and flags through the HTML parser. With this, it extracts different hyperlinks from content on each page.

One of the biggest challenges we faced is the scalability and efficiency. With larger scaled data, it may work slower since it reads all the data by each character. Network problems and certain formatting was another issue that we faced while developing the script. Certain semantics like sending login information, extracting the CSRF, and parsing the HTML took some time to develop. 

In order to test the code, we divided it into each individual function and tested it section by section to ensure functionality. We also used the performance testing on Gradescope to improve the speed of the crawler’s efficiency, that way it would not time out. Logging different values while the crawler was running also helped us see if the script was working as intended and helped with the debugging process. 
