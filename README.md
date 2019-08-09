# epubcheck-messages

A simple website listing all epubcheck messages and their severity in sortable tables.

## Details

All messages are in [a json file](epubcheck-messages.json) that can be converted to XML, YAML, etc. if needed.

Tables are sortable thanks to [Tablesaw](https://github.com/filamentgroup/tablesaw).

## Refs

- [Codes and messages](https://github.com/w3c/epubcheck/blob/master/src/main/resources/com/adobe/epubcheck/messages/MessageBundle.properties)
- [Severity #1](https://github.com/w3c/epubcheck/blob/1f6a882720f6319f4bc98241427e9612d78d52a0/src/main/java/com/adobe/epubcheck/messages/DefaultSeverities.java)
- [Severity #2](https://github.com/w3c/epubcheck/blob/c19b63928e62e2905f9696afb16b71e7fdcff793/src/main/java/com/adobe/epubcheck/messages/MessageDictionary.java#L69:L347)