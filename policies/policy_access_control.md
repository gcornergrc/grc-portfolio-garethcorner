# Access Control Policy (Sample)
**Company:** RailCloud Analytics Ltd. | **Version:** 1.0 | **Owner:** IT Security | **Review:** Annual

## 1. Accounts & Authentication
- SSO for all users; **MFA required** for admins and remote access.
- Service accounts: non-interactive, documented.

## 2. Authorization
- Use **RBAC**; grant by role, not by individual.
- Enforce **least privilege** and **need-to-know**; quarterly reviews.

## 3. Joiner/Mover/Leaver
- Joiner: access approved by data owner.
- Mover: adjust within 24h of role change.
- Leaver: revoke within 24h; rotate keys/tokens.

## 4. Privileged Access
- Admin actions logged; alert on failed admin logins.
- Break-glass accounts protected by MFA and monitored.

## 5. Remote Access
- VPN/Zero Trust with device health checks; idle timeout 15 min.

## 6. Review
Quarterly access recertification; keep evidence 12 months.
