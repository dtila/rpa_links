# UiPath links helper
This repository helps you extract navigation links from different types of documents. From now, there is a single link supported: webpage links (HTML).

__Remarks__ 
If the HTML is not well formated or invalid, it does not throws any exception, but it returns an empty list

## Build
The included bat file requires the Visual Studio 2019 Community to be installed. If you have anything else, you need to modify it and adapt to your Visual Studio installation.

## ExtractLinksFromMail activity
Extracts the HTML links from a *MailMessage*. It receives a mail and outputs an array of list of HTML links which has been found in the body of the message.

__Input parameters__
- MailMessage: a Mail message object

__Output parameters__
- Links: a list of links that has been found in the input message


## ExtractLinksFromMessage activity
Extracts the HTML links from a raw string. It receives the actual HTML content as a string, and outputs the HTML links which has been found there.

__Input parameters__
- Message: a message as a text or formatted as HTML message

__Output parameters__
- Links: a list of links that has been found in the input message


# Disclaimer
Open any issue if you find any bug or the documnetation is not clear. Push requests and issues are always welcome!
