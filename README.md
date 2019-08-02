# HTTPServerApplication
This is the repository for the First Assignment. 



PROBLEM STATEMENT: 

http://bit.do/httpserver

Write a Java application to create a minimal HTTP web server that serves GET requests with requested html resources if available, else responds with error message.


(Putting the pieces together)
Directions to get started: 
Create a simple TCP Socket  based server side app (using port 80). 
		(Print whatever you receive on inputstream)
In your browser goto “http://localhost” (put this in address bar and press enter)
		(Observe the console for the print statements you made in step 1)
Handle the requests based on the observations in step 2.
Improve your app to support multiple concurrent requests using threads. (if not already  done in step 1).


Expectations:
When an html document requested through browser, it should  serve the request with appropriate response.
Else should respond with an error message.



Supporting Information:

HTTP response format:

PROTOCOL_WITH_VERSION RESPONSE_CODE STATUS         Example:=>    HTTP/1.1 200 OK
Brief Description about the server.                                                    Example:=>    Server: My Java HTTP Server : 1.0
Date: RESPONSE_DATE_AND_TIME		  
Content-type: CONTENT_TYPE				     Example:=>    Content-type: text/html
Content-length: SIZE_OF_RESPONSE_FILE		     Example:=>    Content-length: 256
NEW_LINE
ACTUAL_FILE_CONTENT_BYTES

References:
https://www.tutorialspoint.com/http/http_requests
https://www.tutorialspoint.com/http/http_responses
https://www.w3.org/Protocols/rfc2616/rfc2616.html
https://www.w3.org/Protocols/rfc2616/rfc2616-sec3.html#sec3

