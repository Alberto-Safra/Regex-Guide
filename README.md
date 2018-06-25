# Regex-Guide
Guide for regex

* \d is a digit 0-9
* \. is for period
* . is wildcard char 
* [] brackets will match any one char in bracket as an option
* ^[_something_] will match to anything but that something
* you can also do case sense ranges e.g. [A-Z], [a-z], [0-9], [A-Za-z0-9]
* _something_ \{ _ANumber_\} will let you match that something ANumber many times. 
* additionally, \{_lowNum_,_highNum_} will let you match an expression a number in that range many times
* _something_* lets you match _something_ with arbitraty repitation while _something_+ makes sure at least one occurance is satisfied
* _something_? means something is optionally matched
* \s is for any white space including carriage return
* ^before a _something_ (not in a group) meeans starts with $ after something means ends with
* () captures whats inside it
* (_something_|_somethingelse_) means something or somethingelse
* back refrencing is refering to your first captured group as \1 your seconf \2 ect