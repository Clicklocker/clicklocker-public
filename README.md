# 🔗 ClickLocker – Public Integration Resources

This repository contains public files and metadata required to integrate external systems with the ClickLocker platform.

---

## 📁 Contents

- `cert/ca.crt` – Root CA certificate for verifying TLS communication
- `schemas/webhooks/` – JSON Schema definitions for incoming/outgoing webhook payloads
- `openapi.yaml` – Public API specification (OpenAPI 3.x)
- `examples/` – Sample payloads and request formats
- `other/` – Reserved for GPG keys, static metadata, etc.

---

## 🛡️ Security

All TLS connections use CA-signed certificates. For certificate pinning or trusted validation, use the included `cert/ca.crt`. No private keys are ever stored here.

---

## 🌐 Intended Use

This repository is public and intended for use by:
- External integrators
- Developers building tools against ClickLocker APIs
- Systems requiring ClickLocker-issued public certificates

---

## 📘 API Documentation

Public API specs are maintained in `openapi.yaml`. More usage examples and developer docs will be added over time.

---

## 🧩 Contact

For integration support or questions, please contact the ClickLocker engineering team at:  
📧 `admin@clicklocker.pl`

---

> All files in this repository are safe to publish and intended for public access.
