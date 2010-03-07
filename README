Stringformat
============

Provides a full implementation of Python style string formatting for JavaScript as outlined in the
Python documentation: http://docs.python.org/library/stdtypes.html#string-formatting-operations

The function comes attached to String, and you may use it like that:

    String.format( "I have %d apples, and %d pears.", [ 13, 10 ] );

It supports a simple argument:

    String.format( "I have %d apples.", 9 );

If you want to move the function to string prototype where, arguably, it may be more useful:

    String.prototype.format = function () {
      return String.format( this, arguments );
    };

    "I have %d apples, and %d pears..".format( 9, 12 );

Additionally, the function support a noConflict method which allows you to unassign it from 
String and into whatever name you want.

    $.format = String.format.noConflict();

    
