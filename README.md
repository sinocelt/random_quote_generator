This is a project that randomly chooses quotes which then allows you to Tweet them.

Make sure that you put the files: 
generate_quotes.html, quotes.js, and random_quotes.json

into the same folder, and host them on a server like Apache. Then simply open generate_quotes.html with a browser. Without viewing the project from a server like Apache, CORS will prevent the program from working. If you own a domain, you could also host these files on your domain.

About the quotes:
All quotes in the random_quotes.json file were aquired via Wikimedia, either from Wikipedia.org or Wikiquote.org.
The quote pages were downloaded, and then the quotes were extracted using sed. Then, the JSON file was created and parsed using sed.
