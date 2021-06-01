https://wyattdockstader.github.io/Q-A-Game/

<b>What are some of the signs and causes of Callback Hell?</b>
Large pyramid shaped blocks of code With a bunch of long tail of function closures, This happens when people try to write js where execution happens visually top to bottom.

<b>What does the asynchronous mean and how are callbacks involved?</b>
Async can be described simply as happens in the future, a call back is code that runs after that "future event" happens.

<b>Summarize the 3 ways to avoid / fix Callback Hell</b>
Keep your code shallow: by nameing anonymous functions and moving those functions to the top level of the program you can clean up code and increase readability.
Modularize: basically breaking larger modules with multiple functions into simpler and less complex modules that work together and can then be called by other modules.
Handle your Errors: Do this by supplying error handlers that will alert to errors that stop your call backs from running.