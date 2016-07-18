# jarvis
IRC bot for the scp-wiki related channels. Powered by pyscp and sopel.

## Changelog

### 1.0.0

New features

* Changelog!
* Added a check for orphaned mainlist titles to !errors.
* Added !version / !jarvis command. 
* Added !rejoin command.
* Added !tvtropes command.

Bug fixes

* Fixed channels with capital letters causing incorrect message logging for some users.
* Fixed number-only-names being treated as dates when adding quotes.
* Names that start with numbers are no longer invalid when retrieving quotes.
* !errors can now only be used in the SSSC.
* Ban expiration time is now checked at the time of banning instead of the last !updatebans call.
