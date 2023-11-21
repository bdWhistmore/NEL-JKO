//Jay Banks

# NEL-JKO  
NEL AND JKO Codes for CIM Completion  
Press Ctrl+Shift+J and input the codes below  

# NEL  

API_1484_11.SetValue('cmi.completion_status', 'completed');  
API_1484_11.SetValue('cmi.score.scaled', '1.0');  
API_1484_11.SetValue("cmi.success_status", "passed");  
API_1484_11.Commit("");  

# JKO  

API_1484_11.SetValue('cmi.completion_status','completed');  

API_1484_11.SetValue('cmi.completion_status','completed');if (document.getElementsByName("courseheader").item(0).contentDocument.getElementById("c")){document.getElementsByName("courseheader").item(0).contentDocument.getElementById("c").submit()};

# Injecting Code  

Injecting JavaScript code into a running browser tab can be done in a few different ways.  

Here are some common methods:  

Browser Developer Tools (Console):  

The simplest method is using the browser's Developer Tools. You can open them by right-clicking on the page and selecting "Inspect" or using keyboard shortcuts (Ctrl+Shift+I or F12 for Windows/Linux, Cmd+Option+I for macOS).  
Go to the "Console" tab and paste your JavaScript code there. This will run the code in the context of the current page.  
Bookmarklets:  

A bookmarklet is a browser bookmark that contains JavaScript code. Create a new bookmark and paste your JavaScript code into the URL field, prefixed with javascript:. For example: javascript:alert('Hello, world!');  
To run the code, you simply click the bookmark while on the page you want to affect.  

For example, paste the following into the URL section of the created bookmark.  
```

javascript:(function(){ API_1484_11.SetValue('cmi.completion_status', 'completed'); API_1484_11.SetValue('cmi.score.scaled', '1.0'); API_1484_11.SetValue("cmi.success_status", "passed"); API_1484_11.Commit(""); })();

```


Browser Extensions:  

Custom browser extensions can run JavaScript on web pages. You can create an extension and include your script in it. However, this requires knowledge of browser extension development and may be subject to browser-specific restrictions.  
Userscripts:  

Userscripts are JavaScript snippets that can modify web pages. Tools like Tampermonkey or Greasemonkey (browser extensions) allow you to run these scripts automatically on specified pages.  
Injecting via Debugging Tools:  

Some advanced debugging tools and techniques can inject code into a page. This requires a deep understanding of browsers and web security.  

Using Web-Based IDEs:  

Some web-based integrated development environments (IDEs) can inject code into web pages for testing purposes.  

# Good Luck.  
Signed: Jay Banks  

