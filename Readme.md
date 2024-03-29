# SkillPairUp Server (Backend)

## Description

This repository contains the backend codebase for SkillPairUp, responsible for handling server-side logic and API endpoints. The backend is built using ExpressJS and TypeScript, providing a robust and type-safe environment for development. Additionally, it utilizes Postgres as the database management system and Prisma as the ORM for database operations.

## Languages and Frameworks

- ExpressJS
- TypeScript

## Tools Used

- Postgres
- Prisma

## Prequisites

- Install NodeJS v16.16
- Install Postgresql server
- Install Prisma globally

## Installation

To run the backend server locally, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/shwetasharma10/server.git && cd server
   ```

2. Install dependencies using yarn:

   ```bash
   yarn install
   ```

3. Generate Prisma client and deploy migrations:

   ```bash
   prisma generate
   prisma migrate deploy
   ```

4. Build the TypeScript code:

   ```bash
   yarn run build
   ```

5. Start the server:
   ```bash
   yarn start
   ```

## Usage

Once the server is running, it will be accessible at the specified port. You can now navigate to the client app and see the server in action.

## Support

If you encounter any issues or have questions about the SkillPairUp backend, please open an issue in the repository, and we'll be happy to assist you.
