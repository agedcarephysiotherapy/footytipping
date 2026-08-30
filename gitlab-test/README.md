# GitLab Pages test architecture

This folder is a standalone test website intended to be copied into a GitLab repository to test GitLab Free + GitLab Pages + a custom domain.

It is deliberately isolated from the existing Footy Tipping application. Nothing in the existing root application is replaced or modified.

Architecture:
- GitLab: source repository and CI/CD
- GitLab Pages: static website hosting
- Supabase: future database/auth/storage backend
- Resend: future transactional email

Before using it as a real website, replace the example domain, phone and email and connect the contact form to a backend/email service.
