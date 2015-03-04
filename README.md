# meteor-big-js-problem
A reproduction of the problem with minimizing big JavaScript files (RangeError: Maximum call stack size exceeded).

Start the application with `meteor run`. Everything works as it should.

Start the application with `meteor run --production`. The error `RangeError: Maximum call stack size exceeded
` occurs.

The problem could have something todo with minimizing the big JavaScript file in the client directory.
