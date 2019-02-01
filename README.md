Writing RFCs is a pain in the ass.
To start writing my own RFC I had to download an 
existing one parsable by the id2xml tool that you can install
by running ```pip install id2xml```. You can then use this tool
to parse a text based rfc and generate the xml output needed by
the xml2rfc tool (```pip install id2xml```) to generate the html or txt version of the document.
In this folder you can find the text version of the OAuth Framework.
You can play with it doing:


Running ```id2xml rfc6749.txt``` produces *rfc6749.xml*

Running ```xml2rfc rfc6749.xml --html``` produces *rfc6749.html*

If you need to write your own RFC just copy the rfc6749.txt and adapt to
your needs.
