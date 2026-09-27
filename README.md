# Kako Kabob Truck Manager — Version 2

Tablet-first operations app for Kako Kabob's food truck.

## Current modules
- Dashboard with READY / ACTION REQUIRED / DO NOT OPERATE logic
- Pre-departure inspections
- Temperature logs
- Equipment status
- Maintenance tracking
- Event logs
- Incident/breakdown reports
- Permit/document register
- Team roles
- Truck profile and local backup
- Offline PWA shell
- Supabase/Postgres schema prepared for cloud activation

## Current state
The app works locally/offline. The next phase connects Supabase for authentication, shared cloud data, photos/documents, and cross-device syncing.

## Security
Never place a Supabase service-role key in browser code.
