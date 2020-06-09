# OpenAKC
At it's simplest, OpenAKC is a dynamic SSH key manager / privilaged access management tool for Linux (and possibly other unix like platforms).  It is however far from a traditional key manager, allowing all static trust which would normally be configured in an "authorized_keys" file to be centrally managed.  Additionally, session recording is provided along with many restrictions applied above what SSH normally provides.

OpenAKC can also allow users to log on to "role accounts" using personal keys while applying similar rules, with session recording and enhanced logging to satisfy security best practice.  You no-longer have to require users to log in to servers with personal accounts and escalate privilages just to ensure complete logging.  OpenAKC relieves you from managing user permissions, home folders, and authentication across large numbers of machines while ensuring detailed records showing which users accessed which servers, and what they did!

WARNING: This is pre-release software and although it is functional, plenty of work remains to ensure it is robust and secure.

There is precious little documentation as yet, but please find a demo [here].  Any contributions of in regard to documentation (or anything else) would be greatly appreciated.

Please note that most of this tool is created using shell code, I hope this makes it approachable for sysadmins (as the likely users), to contribute.

[here]: https://www.youtube.com/watch?v=r2hv-WivqHY
