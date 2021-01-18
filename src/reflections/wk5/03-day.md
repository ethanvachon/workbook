# Day Three Reflection
__1/13/21__

## In simple terms what is a sub-document?
A sub-document is essentially just a document that is nestled in another document. An example of this is if a schema is nested in another schema.

## When might you use a sub-document?
These sub-documents are mostly useful in the models for mvcs in node. They are very useful if data in your model needs to contain an array of objects that need their own id.

## How do you add to a collection of sub-documents? What about editing them?
To add to a collection and to edit them, you'll need to first use findOne to get the document. At this point, you can get the targeted array and add to, or edit it.


## Daily Project github.com/ethanvachon/planet-data