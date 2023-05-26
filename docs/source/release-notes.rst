Release Notes
=============

v1.10

Field & RegEx Reference
^^^^^^^^^^^^^^^^^^^^^^^

Updated Content and Examples

New Interface Features
^^^^^^^^^^^^^^^^^^^^^^
**Primary Field** - Determines The Main BRS Field Input (Only One Can Be Selected)

Term Field
  [bi,ti]
  [bi]
  [ti]
  [mi]
  [mn,mp]
  [pi]
  [fm]

  **Advanced Field Search** - Toggles Display of Additional Search Fields to Use as Primary Field:
    Disclaimer [ds]
    Design Code [dc]
    G/S Field [gs]
    Status Field
      [sn]
      [rn]
      [rg]
    Filer Field
      [on]
      [ow]
      [at]

**Additional Field** - Determines Additional BRS Fields that Contain Operator to Indicate How this Field will be Used in Connection with Primary Field (Can Select 0 or all)

Class Field
  [cc]
  [ic]
  [tc]
  [us]
Live/Dead
  live[ld]
  dead[ld]
  
  **Advanced Field Search** - Toggles Display of Additional Search Field to Add Conditional Search
  
    G/S Field
    
**Automatic Detection of BRS that is Inside and Outside of RegEx** - The application has been programmed to recognize any BRS entry in either the Primary Field input or selected Additional Field Input that should be searched inside RegEx in the new system and recognizes syntax that should be search outside of RegEx (i.e., quotes or fields without RegEx).

**Parsing of Multiple Search Statements** - The application has been programmed to recognize multiple search statements for a single field's input/

**Automatic Operator Identification** - The application has been programmed to recognize operators and handle them accordingly with proper X4 Upper case syntax

**Automatic Outer Parens** - The application upon recognizing multiple search statements in the field's input will automatically create outer parens for the user, that will appear on the edges of the input box, in the BRS Display, and in the X4 Query

**Active Field Highlighting** - The active fields are now clearly designated with a light blue shade when selected and reflected by the same blue color in the BRS display window

**Class Field Validation Warning** - Class Field will Turn Red if the Class Number/Letter is Unacceptable

v1.00
-----

Field & RegEx Reference
^^^^^^^^^^^^^^^^^^^^^^^

Added Expanded RegEx and Field References with Filters and 

BugFix
^^^^^^
Fixed Character Replacement for BRS ?

v0.94
-----

Class Field
^^^^^^^^^^^

**Class Input** - When class input is not going to result in an acceptable query limited by class, the Class Field will contain a red shade to indicate the input is not acceptable.
This will not prevent the BRS Autopopulate or Regex Pattern Output from reflecting the unacceptable syntax, and currently only checks against Coordinated Class, International Class, and US Class matches.  This version is context specific based on the selected class, but does require additional input before it will recognize the change in the selected Class Field.

v0.93
-----

BRS Syntax Expansion
^^^^^^^^^^^^^^^^^^^^

**Expanded Pattern Matching** - Improved Rules to handle: 
  
  Single exclude wildcards: '{!a}', '{!c}', '{!d}', '{!e}', '{!m}', '{!o}', '{!v}'
  
  Combination wildcards: '{!a+!d}', '{a+d}', '{!c+!d}', '{c+d}', etc.

Reference Buttons
^^^^^^^^^^^^^^^^^

**About/Help Button** - Added button that creates expandable reference that: 
  
  links to this documentation via "Help Guide"
  
  links to Regex101.com
  
  provides a short list of Fields that will appear in Regex Pattern Output as "Field Reference"

**RegexRef Button** - Added button that creates expandable reference that displays regular expression syntax that will be displayed in the Regex Pattern Output so that the user can reference and learn the syntax that is displayed.  The reference also provides explanations and how the similar syntax would be executed in BRS where possible.
