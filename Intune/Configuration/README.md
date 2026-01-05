# Win - OIB - Compliance - U - Defender for Endpoint - v3.1

## Purpose
This template creates a Windows 10/11 compliance policy focused on Microsoft Defender for Endpoint.

## Notes
- This version **does NOT include scheduledActionsForRule**
- Scheduled actions were removed to ensure compatibility with tenants
  where Graph does not support this property.

## Scope
- Windows 10 and later
- Device-based assignment only

## Important
Do NOT add `scheduledActionsForRule` back unless the tenant explicitly
supports Compliance Scheduled Actions via Graph.

## Source
Adapted from OIB baseline for CIPP usage.
