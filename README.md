#This project was created by Justin Barry at github.com/sinocelt
#It is released under the GPLv3 license
#You are free to copy it, modify it, and/or share it
#Please give credit to Justin Barry

This is a project that randomly chooses quotes which then allows you to Tweet them.

Make sure that you put the files: 
generate_quotes.html, quotes.js, and random_quotes.json

into the same folder, and host them on a server like Apache. Then access the files via the server. Without viewing the project in a server, CORS will prevent the program from working.

About the quotes:
All quotes in the random_quotes.json file were aquired via Wikimedia, either from Wikipedia.org or Wikiquote.org.
The quote pages were downloaded, and then the quotes were extracted using sed. Then, the JSON file was created and parsed using sed.
