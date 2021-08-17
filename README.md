![malicious-pdf.png](https://triop.se/wp-content/uploads/2021/08/malicious-pdf-e1629197726260.png)

# Malicious PDF

Generate four different malicious pdf files with phone-home functionality. Can be used with [Burp Collaborator](https://portswigger.net/burp/documentation/collaborator).

Used for penetration testing and/or red-teaming etc

## Usage

`./malpdf.py burp-collaborator-url`

Output will be written as: test1.pdf, test2.pdf, test3.pdf and test4.pdf in the current directory.

Do not use the http:// etc prefix on the url argument.