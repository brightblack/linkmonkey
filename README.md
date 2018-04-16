# linkmonkey

This is a project that combines a number of features to in a safe environment check the content of URI's from the web.

It does this via a number of processes that include:
- Checking content is the same from different source host types and source locations
- combined sandbox and conventional incident-response approaches to verifying if the content is malicious
- rendering via safe mechanisms the content so users can see what the content shows without exposing themselves to malcious content
- support for attempted automatic responses to some types of recognised content like phishing, in order to automate the population of honeytoken credentials, used elsewhere to identify malicious activity.
