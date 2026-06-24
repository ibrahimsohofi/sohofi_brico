# Price History Feature

## Tasks
- [x] Analyze current database schema and backend code
- [ ] Add price_history table to database initialization
- [ ] Modify product update endpoint to log price changes
- [ ] Add API endpoint to fetch price history for a product
- [ ] Update TypeScript types to include price history
- [ ] Add UI component to display price history in product view
- [ ] Test the feature

## Notes
- Track both `selling_price` and `purchase_price` changes
- Store: product_id, old_price, new_price, price_type (selling/purchase), changed_at, changed_by
