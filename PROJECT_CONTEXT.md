# Project Context

## Project Type
Full auction/bidding platform similar to bid.cars.

## Stack
- Vite
- React
- TypeScript
- Firebase
- Cloudflare Pages
- GitHub sync

## Deployment
Frontend deployed on Cloudflare Pages.

## Backend Architecture
System is being migrated away from VITE_API_URL dependency.
Goal is Firebase-native architecture.

## Firebase Usage
- Firebase Auth
- Firestore
- Firebase Storage
- Optional Firebase Functions

## Main Features
- Visitor registration
- Admin approval system
- User dashboard
- Escrow wallet
- Invoice system
- Real-time bidding
- CSV import system
- Notifications
- Admin messaging
- Vehicle listings

## Admin Requirements
Admin login should use:
Email:
CSAPEX@bid.cars

Password:
031295$$$$01KILOX

Admin should:
- approve users
- send invoices
- manage bids
- upload CSV vehicle data
- send notifications
- manage wallet balances

## CSV Requirements
CSV uploads should:
- save permanently
- write into Firestore
- populate listings automatically

## Notification Requirements
Notifications must:
- appear instantly
- play sound
- support repeated alerts
- work for invoices/messages/admin approvals

## Current Major Task
Remove all VITE_API_URL dependency safely without breaking:
- admin panel
- bidding
- invoices
- CSV uploads
- Firestore persistence

## Important Notes
- Project is large and production-oriented
- Cloudflare Pages is the deployment platform
- Firebase is the primary backend
- No VPS available
