# pyramid-learning-journal

## Coverage:

Step1:

pyramid_learning_journal/test_pyramid_learning_journal.py ............

----------- coverage: platform linux, python 3.6.1-final-0 -----------
Name                                        Stmts   Miss  Cover
---------------------------------------------------------------
pyramid_learning_journal/views/default.py      21      0   100%


========================== 12 passed in 2.73 seconds ===========================
___________________________________ summary ____________________________________
  py27: commands succeeded
  py36: commands succeeded
  congratulations :)

## Author: Chris Hudson and Erik Enderlein

## Site:
 -https://quiet-springs-92243.herokuapp.com/

## Routes and Views:

### Routes:
-routes the home page to /
-routes the detail page for entries to /journal(entry id)
-routes the new entry page(create) to /journal/new-entry
-routes the edit page to /journal/(entry id)/edit-entry

### Views:
-list view for the home page(s) to main.html
-detail view for each entry page to entry.html
-create view for making a new entry to new-entry.html
-edit view for editing an entry to edit_entry.html

