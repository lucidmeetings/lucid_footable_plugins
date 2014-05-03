FooTable plugins
======================

These plugins (okay, there's just one so far) may be over-specific to
the way Lucid Meetings uses FooTables. Proceed at your own risk. 

lucidBookmarkable
-----------------

lucidBookmarkable makes it possible to save a link to a page
where you've filtered, sorted, paged, and expanded rows in a FooTable -- and
see the same state when you load the link. State of the table is
stored, and read from, the URI fragment (the bit after the '#'). 

file: lucid_footable_bookmarkable.js

Usage: When you initialize a footable, include the option: 

    lucidBookmarkable: {
        enabled: true
    }

Example: https://features.icann.org/board-advice#advice-to-board_f=confusing&advice-to-board_d=false&advice-to-board_e=19