# Access Control Policy (Sample)

**Company:** RailCloud Analytics Ltd. | **Version:** 1.0 | **Owner:** IT Security | **Review:** Annual

## 1. Accounts & Authentication
- All users authenticate via SSO; **MFA required** for admins and remote access.
- Service accounts must be non-interactive and documented.

## 2. Authorization
- **RBAC**; grant access by role, not by individual.
- **Least privilege** and **need-to-know** enforced; review quarterly.

## 3. Lifecycle (Joiner/Mover/Leaver)
- **Joiner:** access approved by data owner.
- **Mover:** adjust access within 24h of role change.
- **Leaver:** revoke access within 24h; rotate keys/tokens.

## 4. Privileged Access
- Admin actions logged centrally; alert on failed admin logins.
- Break-glass accounts protected by MFA and monitored.

## 5. Remote Access
- VPN/Zero Trust with device health check; idle timeout 15 min.

## 6. Review
Quarterly access recertification by data owners; keep evidence 12 months.
