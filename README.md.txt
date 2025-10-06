# Sports Dugout Contest Backend

Backend API for The Sports Dugout $1,000 referral contest.

## Features
- Stripe payment processing
- Webhook handling for payment events
- CORS enabled for frontend integration
- Environment variable configuration

## Environment Variables
- `STRIPE_SECRET_KEY`: Your Stripe secret key
- `STRIPE_WEBHOOK_SECRET`: Your Stripe webhook secret
- `PORT`: Server port (default: 3000)

## Endpoints
- `GET /`: Health check
- `GET /api/test`: Configuration test
- `POST /api/create-payment-intent`: Create payment
- `POST /api/webhook`: Stripe webhook handler