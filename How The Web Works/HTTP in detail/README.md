# HTTP in detail:

## Task1: What is HTTP(S)

- HTTP stand for : **HyperText Transfer Protocol**

- The "S" in HTTPS stand for : **Secure**

- To have the flag you just need to click on the padlock, the flag is : **THM{INVALID_HTTP_CERT}**

## Task2: Request and Responses

- As we can see in the source code, the HTTP protocol which is used here is the 1.1 so the answer is: **HTTP/1.1**

- The response header who tells the browser how much data to expect is : **Content-Length**

## Task3: HTTP Methods:

- The **POST** Method allow us to create a new user account

- The **PUT** Method would be used to update your email address

- To remove a picture, use the **DELETE** Method

- To view a news article, use the **GET** Method

## Task4: HTTP Status Codes

- If you create a new user or a new thing, you will receive a **201** response code

- If the page doesn't exist, you will receive a Page Not Found error so response code: **404**

- If the service is Unavailable, you will receive a response code: **503**

- If you aren't login, you don't have the access to edit your profile so response code: **401**

## Task5: Headers:

- The header who tells the web server which browser a user use, is: **User-Agent**

- The header who tells the browser the type of content is : **Content-Type**

- The **Host** header tells to the web server which website is being requested

## Task6: Cookies

- To save cookie on a computer, uses the header : **Set-Cookie**

## Task7: Making Requests

- Add the room after the / in the URL, then click on go, the flag is: **THM{YOU'RE_IN_THE_ROOM}**

- Do the same thing, but change the URL with "blog", and click on the gear icon on the left side type: "id" and on the right: 1 then click on go, 
the flag is : **THM{YOU_FOUND_THE_BLOG}**

- Change the URL by : /user/1, and put "DELETE" option, then click on go, the flag is : **THM{USER_IS_DELETED}**

- Change the URL, and click on gear option to put the username=admin, here is the flag: **THM{USER_HAS_UPDATED}**

- Do the same thing on the /login page, here is the flag: **THM{HTTP_REQUEST_MASTER}**
