**Opened by:** Jordan Lee
**Branch:** `hotfix/revoke-demo-perms` -> `main`
**Status:** Merged

### Description:
Revokes all production write-access permissions from the `svc_capypay_demo` service account. This account was identified as the source of the request flood that triggered INC-20250315-724.

---
### Comments:

**Blake Reynolds** `(commented 1 hour ago)`
> What's the customer impact here? We need to be proactive with our comms to the partners at Liberty Freedom.

**Jordan Lee** `(commented 59 minutes ago)`
> @Blake Reynolds The customer impact is that we have stopped our own demo app from unintentionally DDOSing our production environment. The comms should probably reflect that.
