# Kaziqa ERP — interactive product demo

A browser-only demonstration of Kaziqa service management. The app uses seeded synthetic data, and all edits stay in the visitor's own browser localStorage. **No authentication, MySQL, SMS, M-PESA or customer data is connected.**

## Test flows
1. Switch between Laundry, Shoe care, Tailoring and Repairs.
2. Create a job with an initial deposit.
3. Advance a job through Received → In progress → Quality check → Ready.
4. Open the collection ticket and hand the item over using its reference and outstanding-balance amount.
5. Add expenses, browse customers and explore optional modules.
6. Use Reset demo to restore the original example data.

## Deployment
Deploy as a static website on Vercel, with the included `vercel.json` security headers. No environment variables or backend service are needed for this **demo**.

Do not insert real customer data. Production application must use the secured Kaziqa Drizzle/MySQL API, authenticated sessions, tenant RBAC, private Cloudinary media and verified payments before launch.
