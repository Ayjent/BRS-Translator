Release Notes v0.94
===================

Class Field
-----------

**Class Input** - When class input is not going to result in an acceptable query limited by class, the Class Field will contain a red shade to indicate the input is not acceptable.
This will not prevent the BRS Autopopulate or Regex Pattern Output from reflecting the unacceptable syntax, and currently only checks against Coordinated Class and International Class matches.  Future versions will be context specific based on the selected class.

Release Notes v0.93
===================

BRS Syntax Expansion
--------------------

**Expanded Pattern Matching** - Improved Rules to handle: 
  
  Single exclude wildcards: '{!a}', '{!c}', '{!d}', '{!e}', '{!m}', '{!o}', '{!v}'
  
  Combination wildcards: '{!a+!d}', '{a+d}', '{!c+!d}', '{c+d}', etc.

Reference Buttons
-----------------

**About/Help Button** - Added button that creates expandable reference that: 
  
  links to this documentation via "Help Guide"
  
  links to Regex101.com
  
  provides a short list of Fields that will appear in Regex Pattern Output as "Field Reference"

**RegexRef Button** - Added button that creates expandable reference that displays regular expression syntax that will be displayed in the Regex Pattern Output so that the user can reference and learn the syntax that is displayed.  The reference also provides explanations and how the similar syntax would be executed in BRS where possible.
