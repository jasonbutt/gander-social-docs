# AT Protocol

*Unofficial community intelligence. Last reviewed: 2026-11-01.*

The AT Protocol is the shared network underneath Gander, Bluesky and other apps. A handle is the readable address people use to find you. A DID is the underlying identifier. Your personal data server, or PDS, stores your account repository. Apps use indexing services to turn those records into feeds and profiles.

That common base makes many core social records portable and interoperable. It does not mean every app feature travels with you. Gander's FAQ singles out Boards and Groups as experiences that may not appear or work the same way elsewhere. Treat an app's special tools as app features until their interoperability is demonstrated.

The protocol supports account migration in principle. A particular move can still depend on app support and practical tooling. Check current official instructions before moving an account or changing a handle.

For the technically curious: an `at://` URI identifies a record. A CID identifies one version of its content, so it can change when the record is edited. This guide's canonical documents use stable `at://` URIs.

**Sources:** [AT Protocol overview](https://atproto.com/), [AT Protocol documentation](https://atproto.com/guides/overview), [Gander FAQ](https://gandersocial.ca/faq/).

**Check in app before adding:** current account migration and custom-domain handle support in Gander.
