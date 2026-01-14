# Cybersecurity Controls

Controls implemented:
- TLS 1.2+ enforced for all network communication
- Role-based access control (RBAC)
- Audit logging for security-sensitive actions
- Secrets are stored in environment variables
- Regular dependency updates and vulnerability scanning

Incident handling:
- Security incidents are reviewed within 24 hours
- Critical incidents trigger notification to system owners



## QA Smoke Test Marker

This repository is used for Annex IV QA validation.
Unique marker: SECURITY_SMOKE_REPO_98765

Additional control:
- Redis is used as an in-memory store with AUTH enabled and protected by IP allowlist.
