# goqr
## Get OAuth QR-Code from specific useraccount

This tool is for Linux-based systems, only.

**Dependencies:**
- qrencode

**Tip:**
You don't need to deploy this script into multi-host environments.
If qrencode is present on all relevant hosts, just run goqr like this:

```bash
ssh user@host 'bash -s' < /path/to/goqr
```