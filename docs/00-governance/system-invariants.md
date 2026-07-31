# System Invariants

**Document ID:** INV-001  
**Revision:** 0.1  
**Status:** Draft

## INV-001 — Core Isolation

Normal users shall never require direct access to the Core
Service.

## INV-002 — Database Isolation

Client applications shall never access the system database directly.

## INV-003 — API Boundary

External applications shall interact with the Core Service
through documented APIs.

## INV-004 — Auditability

All security-sensitive and business-critical state changes
shall produce an auditable record.

...
