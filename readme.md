
# BAP — Bizface Agent Protocol

> An open protocol for defining and discovering enterprise AI agents via `ai-manifest.txt`.  
> Enables agent-to-agent communication across the AI-native web.

---

## 🌐 What is BAP?

**BAP (Bizface Agent Protocol)** is a lightweight open standard that allows any enterprise to publish a structured manifest of its AI agents — making them discoverable and interactable by other AI agents or systems.

Think of it as the `robots.txt` of the AI-native internet:  
Instead of search bots, your endpoints talk to intelligent agents.

---

## 🔍 Why BAP?

- ✅ Declare your AI endpoints clearly (`Sales`, `HR`, `Support`, etc.)
- 🔗 Let other AIs initiate meaningful conversations with the right roles
- 🤖 Build infrastructure for autonomous B2B communication
- 🌍 Open, human-readable, machine-friendly — like a modern Yellow Pages

---

## 📄 ai-manifest.txt Example

```yaml
company_name: Acme Inc.
location: Los Angeles, CA
language: en
agents:
  - role: SalesDepartment
    description: Handles product pricing and availability inquiries
    endpoint: https://acme.com/ai/sales
    availability: 24/7
    protocol: openai-chat
  - role: HRDepartment
    description: Handles job applications and candidate screening
    endpoint: https://acme.com/ai/hr
    availability: 24/7
    protocol: openai-chat
```

---

## 🧱 File Structure

Your company should host this file at:

```
https://yourdomain.com/ai-manifest.txt
```

Make sure the file is:
- UTF-8 encoded
- YAML 1.2 compliant
- Publicly accessible

---

## 📦 Tools Coming Soon

We’re working on:
- [ ] AI Agent Directory (search engine for `ai-manifest.txt`)
- [ ] BAP Validator & Schema Tools
- [ ] GitHub Action for manifest publishing
- [ ] Developer SDKs (Node, Python)

---

## 🤝 Get Involved

We're looking for contributors, early adopters, and visionary collaborators to shape the AI-native future.

📬 Email us at: [lhlhome@gmail.com](mailto:lhlhome@gmail.com)

---

## 🪪 License

MIT License © 2025 [Bizface.ai](https://bizface.ai)
