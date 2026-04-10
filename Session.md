The period of time during which an entity may perform actions on resources to which they are entitled.

During the life of a session, a specific entity may be referred to as a [[Subject]] - i.e. the subject in question to be authenticated and authorized.

[[Access Management]] platforms include components which act as a [[Session Manager]]
to keep track of active sessions.

A session has three distinct phases:
- **Establishment**: Authentication occurs - the subject presents credentials, and they are validated.  If successful, authorization is evaluated based on the subject's entitlements (and any other context, if applicable).  If authorization is successful, access is granted and the session is established.
- **In-Session**: The subject performs actions on resources they are entitled to, and these may be monitored and/or logged.  Optionally, [[Continuous authorization]] may occur, i.e. authorization is evaluated at every action or other set interval.
- **Destruction**: a session may end either when a pre-configured duration is reached, it's ended by the user (e.g. by logging out), or by intervention the session manager (e.g. if continuous authorization fails).  Following destruction of a session, a new session must be established to regain access.