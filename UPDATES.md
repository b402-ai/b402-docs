# B402 Documentation Updates

## Summary

Updated the b402-docs repository with comprehensive getting started guides matching PayAI and x402 documentation structure.

## Files Created/Updated

### 1. get-started/quickstart.mdx (NEW)
- 3-step drop-in setup guide
- Quick examples for seller and buyer
- Network configuration tables
- Supported tokens cards
- Links to detailed guides

### 2. get-started/seller.mdx (UPDATED)
- Complete Express server setup
- Full working code example
- API endpoint specifications
- Next steps with cards

### 3. get-started/buyer.mdx (UPDATED)
- Browser wallet integration
- Complete payment function
- React component example
- Supported wallets
- Error handling examples

### 4. docs.json (UPDATED)
- Added quickstart to Getting Started group
- Now shows: Quickstart → Buyer Guide → Seller Guide

## Structure

```
Getting Started/
├── Quickstart (NEW)     - 2-minute setup
├── Buyer Guide          - Send payments
└── Seller Guide         - Accept payments
```

## Key Features

✅ **Quickstart Guide** - Drop-in setup in 3 steps
✅ **Seller Guide** - Complete Express server with code
✅ **Buyer Guide** - Browser wallet integration with React example
✅ **Copy-Paste Ready** - All code examples work out of the box
✅ **PayAI-Style Structure** - Matches x402/PayAI documentation flow

## Next Steps

Deploy to Mintlify:
```bash
cd /path/to/b402-docs
mintlify dev  # Test locally
mintlify deploy  # Deploy to production
```

The documentation is now ready for deployment!
