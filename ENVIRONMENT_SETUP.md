# Environment Setup

## Required
- Node.js LTS version agreed by the team
- Git
- GitHub access
- Cursor or VS Code
- Chrome

## Verify
node -v
npm -v
git --version

## Clone
git clone <REPOSITORY_URL>
cd pratyangi-fashions
npm install

## Run
npm run dev

Open:
http://localhost:3000

## Build check
npm run build

## Environment variables
Use .env.local for local secrets/config.
Never commit .env.local.

## Team rule
All developers must use the same Node version and package-lock.json. Do not independently change dependency versions without team agreement.
