# QA Checklist (Hamza)

## If testing on Mehdi's machine
1) Open: https://localhost  (accept the certificate)
2) You should see the n8n UI.
3) Visit: https://localhost/webhook/hello
   - Expected JSON:
     {"ok": true, "msg": "hello from n8n"}

## If testing remotely via a temporary tunnel
(Mehdi will send a link like https://<something>.trycloudflare.com)
1) Open the link (HTTPS).
2) Visit: <tunnel>/webhook/hello
   - Expected JSON:
     {"ok": true, "msg": "hello from n8n"}

## Send back two screenshots
- n8n UI page
- The hello JSON result
