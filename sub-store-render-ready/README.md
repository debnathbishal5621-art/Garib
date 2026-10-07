# Subscription Store

Node.js + Express + SQLite customer store and admin panel.

## Run
1. Install Node.js 18+.
2. Run `npm install`.
3. Set `ADMIN_PASSWORD` and `SESSION_SECRET` environment variables (or use defaults for testing).
4. Run `npm start`.
5. Customer site: `/`
6. Admin: `/admin/login`

Default test login if no ADMIN_PASSWORD is supplied: `admin` / `admin123`. Change it before public deployment.

## Features
- Customer product catalog
- Product details and order creation
- Unique order IDs
- Admin dashboard
- Product/price/duration editing
- Product activation/featured flags
- Order status management
- Owner/staff accounts
- SQLite persistence
