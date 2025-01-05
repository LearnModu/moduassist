# ModuAssist
Host your own instance of ModuAssist's HTTP Server locally on Python! Our AI copilot designed to help you with Modu, powered by GPT-4o, is finally here.
## Example Request
```bash
curl -X POST \
    -H "Content-Type: application/json" \
    -d "{\"message\": \"what is modu\"}" \
    http://127.0.0.1:5000/api/chat
```