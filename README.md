# Drafty

One of the challenges for inexperienced users may be how to go about generating and maintaining Pacts. Not everyone is comfortable working with potentially massive JSON files!

Drafty is a single HTML file in an attempt to make it easier. It opens up a form based on the Pact schema, designed to make it easier for non-technical users to construct Pacts. By simply interacting with the form, a valid Pact JSON can be progressively created without the need to dig into the JSON itself.

To use it, simply open `drafty.html` in a web browser. You can either copy/paste an existing Pact into it and start changing it using the form, or construct a totally new Pact via the form, then save the generated JSON as a Pact when you're done.

No idea what instructions will be required to use this - I'm just throwing it out to see if it's of any use...

----

Full credit for the JSON schema editor should go to https://json-editor.github.io/json-editor/ 

I simply lifted their code and adapted it slightly for use as a Pact editor
