# Hi, guest. You are on the page of the DLTMessageAnalyzer plugin.

----
## What is the DLTMessageAnalyzer?

The DLTMessageAnalyzer is a plugin for dlt-viewer SW. Works in combination with the **[following source code](https://github.com/GENIVI/dlt-viewer)**

It is developed in order to increase the analytical capabilities of the dlt-viewer.

Feature-set:

- Search speed ten times faster, than in original dlt-viewer, in case of enabled "in-RAM" cache.
- Possibility to save regex patterns with human-readable names
- Possibility to easily use combinations of the saved regex patterns, which allows to form "angles of analysis" without the need to remember the regex expressions.
This increadibly increases the speed of the analysis!
- This plugin uses all other available and turned on decoding plugins, so it analyzes the decoded messages
- "Grouped view" functionality, which allows to easily form groups of repetitive messages and check request-response number, trace spam cases, etc.
- "Search view" functionality. Analogue of the dlt-viewer's search with extended capabilities
- "Files view", which shows names of analyzed files
- Advanced highlighting of regex groups (refer to [regex name scripting](./md/regex_name_scripting.md) section)
- Continuous search. The analysis continues to happen while new messages being received from HU 
- Check of entered regular expressions with providing human-readable errors in case of wrong input
- In-RAM cache, which makes search dramatically faster
- Work with multiple regex files. Possibility to copy-paste from one file to the other
- "Filters view", which allows to quickly get access to defined "key groups" and change their content (refer to [regex name scripting](./md/regex_name_scripting.md) section)
- Lock of the search between 2 message id-s
- Debug "console view"
and many other features

**=> The main goal of this plugin is to fully replace the existing search functionality of the dlt-viewer, making it faster, more readable, intuitive, and efficient for any user.**

----

## Screenshots:

![Screenshot of DLTMessageAnalyzer plugin - Search view](./md/DLTMessageAnalyzer_screenshot_SearchView.png)
----
![Screenshot of DLTMessageAnalyzer plugin - Grouped view](./md/DLTMessageAnalyzer_screenshot_GroupedView.png)
----
![Screenshot of DLTMessageAnalyzer plugin - Filters view](./md/DLTMessageAnalyzer_screenshot_FilterView.png)