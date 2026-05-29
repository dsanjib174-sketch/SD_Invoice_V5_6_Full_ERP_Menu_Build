# SD Invoice V5.6 Full ERP Menu Build

This continues V5.5 architecture and restores the full ERP menu with all required tabs and working routes.

Included:
Dashboard, Company/Profile, Subscription, Plans, Updates, Clients, Client Data, Branches, Users, Masters, Rate Contract, Quotation, Proforma, Invoice, Delivery Challan, Receipts, Document Register, Ledger, Credit Note, GST/GSP, Tally/SAP, Communication, Audit, Change Password.

Important:
This is a routed full ERP UI architecture. Data save, approval workflow, exports and full accounting logic should be connected module by module next.

Render:
Build Command: pip install -r requirements.txt
Start Command: gunicorn run:app

Superadmin URL: /admin
Client URL: /
