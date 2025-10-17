# Change Log

All notable changes to ADR Chambers products are documented in this file.

---

## [v1.4.0] - 2026-03-31

### BlueJ ADR
- Removed legacy 2FA implementation
- Fixed filtering and export functionality
- Reverted unstable API changes and stabilized endpoints

### Thaimis Web
- Enforced HTTPS across all endpoints (HTTP to HTTPS redirect)
- Updated ingress and TLS configuration
- Deployed latest content updates

### Platform Infrastructure
- Updated AKS application configurations
- Added monitoring alerts for Application Gateway, VMs, VMSS, Storage Accounts, Cosmos DB, and MySQL
- Configured Azure Activity Log archival to storage account

---

## [v1.3.0] - 2026-02-25

### BlueJ ADR
- Fixed case filtering and export across multiple modules
- Resolved incorrect search result rendering
- Improved API response handling

### Thaimis Web
- Removed www.thaimis.com and thaimis.com from legacy ingress hosts
- Migrated TLS settings to new Helm chart configuration

### ADR Services
- Updated operational documentation
- Added backup 2FA code references

### Platform Infrastructure
- Updated Helm chart values for thaimis-web deployment
- Applied Kustomize overlay patches for production environment

---

## [v1.2.0] - 2026-01-22

### BlueJ ADR
- Enhanced case management search and filtering
- Performance improvements to API endpoints
- Bug fixes for payment processing edge cases

### Thaimis Web
- Content updates and UI improvements
- Security patch deployment

### Platform Infrastructure
- Updated AKS application manifests
- Helm chart version bumps for bluej-adr-api and payments microservice
- Added ExternalSecrets configuration for new service credentials

---

## [v1.1.0] - 2025-12-31

### BlueJ ADR
- Year-end release with accumulated bug fixes
- Improved dispute resolution workflow
- Enhanced reporting and export capabilities

### Thaimis Web
- End-of-year content updates
- Performance optimizations

### Arbitration App
- Initial arbitration case management features
- Integration with BlueJ ADR platform

---

## [v1.0.0] - 2025-10-17

### Initial Release

- BlueJ ADR dispute resolution platform
- Thaimis Web application
- ADR Services backend infrastructure
- Azure AKS landing zone deployment
- Helm chart configurations for all services
- Observability stack with Azure Monitor and Defender for Cloud
- GitOps deployment pipeline via ArgoCD

