Usage
=====

.. _entering:

Entering BRS Syntax 
-------------------

To use BRS Translator you do not need to enter any fields, such as [bi,ti] or operators, such as "and", "adj", and "or", into the BRS Input.  
However, the field settings you have selected as active will dictate what is an appropriate entry in the BRS Input and whether the output of the Regex Pattern Output is a valid query in the new Search application.

The primary field setting dictates the field that will be searched in the "BRS Input" section and will be reflected with the first Field Tag in the BRS Autopopulate Display next to the "BRS Input" in a light blue color.  You may further filter your results by selecting the additional field settings with class fields, live/dead status, and the goods/services field.  The selected additional fields will show up in the BRS Autopopulate Display.  Note that the Class Fields and G/S Field require input before showing up in the BRS Autopopulate Display.

Changing Search Query Regex Syntax
----------------------------------

You may change the Regex Pattern Output's reguluar expression syntax from a direct analogue of the BRS syntax to a broader syntax that will provide unlimited instances of a particular character or set of characters.  To do so click on the Regex Syntax Toggle and it will change the syntax. The toggle will tell you what version of syntax you are using, either "Accurate" or "Broader".

"Accurate" is the direct analogue of the BRS Syntax in regular expressions.

"Broader" is more expansive regular expression syntax that identifies when the BRS Syntax the user has entered includes: 

   0 to some number of instances designation, such as "{v0:2}", and then finds 0 or more instances.
   
   1 to some number of instances designation, such as "{v:2}", and then finds 1 or moreinstances.

Exporting Search Query to New Search Application
------------------------------------------------

To export the BRS Translator's Regex Pattern Output to the new Search application, click on the Copy Result.  The Regex Pattern Output is now in your clipboard, and click in the Input box and use the Ctrl+V command or right click command to paste the search query.  Then execute the query in the new Search application.

