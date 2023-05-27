# Words
__(Adding Preferences DataStore to the words app to save the user selection)__  
The Words app is a simple dictionary app, with a list of letters, words for each letter, and the ability to look up definitions of each word in the browser.

### Why to use Preferences DataStore?
Initially, if we perform the following on the words app:
- Launch the app.
- Switch to grid layout.
- Exit and relaunch the app.

When the app is relaunched, letters are displayed in a linear layout and not in a Grid (i.e. the user selection is not retained.)  
To fix this issue, Preferences DataStore is used.
