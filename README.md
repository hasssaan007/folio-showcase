# Folio

> **Showcase page.** This repository is a public showcase of a **private repository**:
> it contains a description of the work only, with **no source code**.

**The client portal your clients actually love.** One branded link where a company's clients see project status, files, approvals and messages, and pay invoices. Built from blocks, with automations.

## Positioning

Notion is excellent for internal work and poor at the outward-facing job. Folio does the outward-facing half: branded client portals reachable by one magic link with no signup, carrying approvals, e-signature, payments and block-level automations.

Launch niche: agencies and freelancers, where the pain is sharpest, with an architecture general enough for any company.

## What I built

- **Portal builder** - drag-and-drop blocks with live preview
- **Core blocks** - status, files, approvals, messages, payments, checklists, tasks
- **Magic-link client access** - unauthenticated clients reach a portal through a share token validated in edge functions, so row-level security stays locked to authenticated team members
- **Automations** - block-based triggers and actions, with run history
- **Billing** - Stripe both for client payments inside portals and for the product's own subscriptions
- **Workspaces** - branding, plans and team membership

## Stack

Next.js 14 (App Router), TypeScript, Tailwind CSS, Supabase (Postgres, RLS, auth, storage, edge functions, realtime), Stripe, Vercel

---

*Source code is private. This page documents the work; code can be shared on request.*
