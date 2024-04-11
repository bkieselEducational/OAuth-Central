# OAuth-Central

## OAuth History, Development, and RFCs
Beginning with the OAuth (Open Authorization) discussion group in April of 2007, a small group of developers went on to write the 'OAuth Core 1.0 final draft' which would be released on December 4th of that same year. An ammendment to the Core protocol would be made (April 2009), resulting in OAuth 1.0a, which addresses a security vulnerability known as a "Session Fixation Attack". Ultimately, the OAuth 1.0 protocol was officialy published as an informational Request For Comments in [RFC 5849](https://datatracker.ietf.org/doc/html/rfc5849). Also note that the original design intentions of OAuth 1.0 were for the primary purpose of allowing API access to resources managed by a 3rd party. In other words, authorization. The use of OAuth as an authentication method (and little else), came about later as an alternate use case. While the OAuth 1.0a RFC 5849 was officially obsoleted by OAuth 2.0 [RFC 6749](https://datatracker.ietf.org/doc/html/rfc6749), it continues to be a valid protocol and you may still encounter it in the wild. For example, Evernote still manages access to it's Thrift API through OAuth 1.0a. If OAuth 1.0a should ever become of interest to you, please refer to this supplementary [README](https://github.com/bkieselEducational/OAuth-1.0a-from-Scratch).

Even with the advent of OAuth 2.0, it's primary concern continues to be authorization, NOT authentication. However, with that being said, OAuth 2.0 does employ a sister-protocol called OpenID Connect, which adds an intentional authentication layer to an OAuth 2.0 flow!

As this is meant to be a central hub for all of my OAuth related resources, aside from the links above, we will want to break up our OAuth related concerns into the following categories:
1. [Application Authorization](https://github.com/bkieselEducational/OAuth-Client-Application-Authorization)
2. [OAuth SDKs](https://github.com/bkieselEducational/OAuth-SDKs)
3. [OAuth Concepts and Implementation](https://github.com/bkieselEducational/OAuth-Concepts-and-Implementation) 
4. [Related Terminology](https://github.com/bkieselEducational/OAuth-Related-Terminology)
5. [OAuth Gotchas](https://github.com/bkieselEducational/OAuth-Gotchas)
