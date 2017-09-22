**Rules for name**

1. Use Intention-Revealing Names

  The name of a variable, function, or class, should answer all the big questions. It
should tell you why it exists, what it does, and how it is used. If a name requires a comment, 
then the name does not reveal its intent.
the good examples:
  ```
  public List<Cell> getFlaggedCells() {
    List<Cell> flaggedCells = new ArrayList<Cell>();
    for (Cell cell : gameBoard)
      if (cell.isFlagged())
        flaggedCells.add(cell);
    return flaggedCells;
  }
  ```
2. Avoid Disinformation

  Spelling similar concepts similarly is information. Using inconsistent spellings is dis-
information.

3. Make Meaningful Distinctions

  Number-series naming (a1, a2, .. aN) is the opposite of intentional naming. Such
names are not disinformative—they are noninformative; they provide no clue to the
author’s intention.

4. Use Pronounceable Names
  
5. Use Searchable Names

  Single-letter names and numeric constants have a particular problem in that they are not
easy to locate across a body of text.
  single-letter names can ONLY be used as local vari-ables inside short methods. The length 
of a name should correspond to the size of its scope

6. Avoid Encodings  
7. Avoid Mental Mapping

8. Class Names

  Classes and objects should have noun or noun phrase names like Customer , WikiPage ,
Account , and AddressParser . Avoid words like Manager , Processor , Data , or Info in the name
of a class. A class name should not be a verb.

9. Method Names

  Methods should have verb or verb phrase names like postPayment , deletePage , or save .
Accessors, mutators, and predicates should be named for their value and prefixed with get ,
set , and is according to the javabean standard

10. Don’t Be Cute

  Say what you mean. Mean what you say.
  
11. Pick One Word per Concept

12. Don’t Pun(双关)

  add, insert, append 
  TODO: for java's container, e.g, list, set, what do add, insert, append mean?
  
13. Use Solution Domain Names
