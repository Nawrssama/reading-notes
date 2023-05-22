# Key differences between scraping static and dynamic websites:

> Static websites have fixed HTML content that remains the same each time it is loaded, making scraping relatively straightforward.

> Dynamic websites, on the other hand, generate content dynamically using JavaScript or AJAX, requiring additional techniques like rendering JavaScript or interacting with APIs to extract data.

# Techniques to avoid getting blocked while scraping websites:

> Implement polite scraping: Set appropriate request headers, use delays between requests, and mimic human-like behavior to avoid overwhelming the target website.

> Rotate IP addresses and user agents: Use proxy servers or VPNs to switch IP addresses and vary user agents to make requests appear as if they are coming from different sources.

> Respect robots.txt: Check the website's robots.txt file to understand which parts of the site are allowed or disallowed for scraping and honor those rules.

# Playwright and its benefits in web scraping:

> Playwright is a tool that allows browser automation and is designed for tasks like web scraping.

> It supports multiple browsers (Chrome, Firefox, Safari) and provides an easy-to-use API to interact with web pages, fill forms, click buttons, and perform other actions.

> Playwright handles JavaScript rendering, making it particularly useful for scraping dynamic websites where content is loaded dynamically.

# Purpose of using XPath in web scraping:

> XPath is a query language used to navigate XML and HTML documents.

> In web scraping, XPath helps locate specific elements or extract data from structured documents.

> XPath expressions can be used to select elements based on their attributes, position, or hierarchical relationships within the HTML structure.

# Example of an XPath expression to select a specific HTML element:

> Suppose we want to select the title of an article with a class attribute of "title" from an HTML page. The XPath expression would be:

    //h2[@class="title"]

> This expression starts with a double forward slash (//) to select any h2 element in the document, then narrows down the selection by specifying the class attribute with the value "title".