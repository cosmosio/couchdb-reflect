## What is couchdb-tools?

CouchDB Emily tools synchronizes an array/object with a couchDB document, view or bulk of documents. It can further manipulate CouchDB User and Security documents. The exact same code will work in both the browser and in node.js, the only difference being the transport layer.

####It can manipulate CouchDB documents:

* Get a CouchDB document and save it in a JavaScript object
* Update the JavaScript object when the document is updated in the database
* Upload a modified document to the database
* Create a document
* Remove a document

####It can manipulate CouchDB views:

* Get a CouchDB view and save it in a JavaScript array
* Update the JavaScript array when a document is added or removed from the databae
* Update the JavaScript array when a document is updated in the database

####It can manupulate CouchDB bulk documents:

* Get a CouchDB bulk of documents and save it in a JavaScript array
* Update the JavaScript array when a document is added or removed from the databae
* Update the JavaScript array when a document is updated in the database
* Update the database when one of the documents is updated
* Add or remove documents in the database when they are add or removed from the JavaScript array

In other words, CouchDB tools will reflect the status of your CouchDB in objects/arrays, and you can observe their changes to update the views.
