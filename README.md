# Ghostline Webhook Test Utility

This is a dummy webhook endpoint used for automation and integration testing. You may POST any JSON payload to the following endpoint:
curl -X POST https://hooks.zapier.com/hooks/catch/22459586/2xpj9rh/
-H "Content-Type: application/json"
-d '{"username":"devbot","leak":"🧨 Ghostline Test Drop"}'




Update README with webhook test instructions
---

**Payload Guidelines:**
- Use valid JSON objects
- No authentication required
- Accepts all HTTP verbs (POST, PUT, DELETE)

**Use Cases:**
- Zapier webhook tests
- Serverless API callback simulations
- Webhook validation tools

---

_This repo is for sandbox testing only._

