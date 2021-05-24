
<b>What problems does the Observer Pattern seek to solve?</b>
It seeks to remedy the push pull in code that happens trying to keep everything in sync when the page responds to input that effects many components.

<b>What are the three mechanisms of the observer pattern?</b>
Subscribe: adds new observable events, Unsubscribe: removes observable events and Broadcast: that executes all evnts with bound data

<b>Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.</b>
This is a reach but it looks like the event emmiter is the gate keeper to the dom, all updates pass through the event listeners with a series of property checks.