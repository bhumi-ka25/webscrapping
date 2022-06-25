1.SCRAPY
Scrapy is a fast, open-source web crawling framework written in Python, used to extract the data from the web page with the help of selectors based on XPath.

Description
For extracting data from web pages, Scrapy uses a technique called selectors based on XPath and CSS expressions. Following are some examples of XPath expressions:

-/html/head/title − This will select the <title> element, inside the <head> element of an HTML document.

-/html/head/title/text() − This will select the text within the same <title> element.

-//td − This will select all the elements from <td>.

-//div[@class = "slice"] − This will select all elements from div which contain an attribute class = "slice"
 
METHODS
1)extract()
It returns a unicode string along with the selected data.
	
2)re()
It returns a list of unicode strings, extracted when the regular expression was given as argument.
	
3)xpath()
It returns a list of selectors, which represents the nodes selected by the xpath expression given as an argument.
4)css()
	
It returns a list of selectors, which represents the nodes selected by the CSS expression given as an argument.
	
