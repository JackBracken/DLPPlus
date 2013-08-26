Get table with id of "threadslist".
Get its tbody.
For every tr in that, if first td has id = "td_threadstatusicon_" + int
check if that int is blocked. If so, display: none; that tr.


Storage of ids in chrome.local.storage;

FILES!

background.js 	<-- interfaces between filter.js and chome api for storage etc
filter.js 		<-- content_script injected to add filter controls
options.js 		<-- provisionally to remove threads from filter, may make a nice interface
options.html 	<-- displays all filtered threads
