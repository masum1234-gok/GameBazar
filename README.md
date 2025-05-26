# GameBazaar

GameBazaar হল একটি Full Stack ই-কমার্স ওয়েব অ্যাপ্লিকেশন যেখানে ইউজাররা গেমস ব্রাউজ, অর্ডার এবং ম্যানেজ করতে পারে। প্রজেক্টটি মূলত TypeScript ও মডার্ন স্ট্যাক ব্যবহার করে নির্মিত।

## Features

- ইউজার অথেন্টিকেশন (JWT)
- গেম ব্রাউজিং ও অর্ডারিং
- অ্যাডমিন রোলস ও রাউটস
- টেইলওইন্ড ভিত্তিক সুন্দর UI
- PostgreSQL ও Drizzle ORM ব্যাকএন্ড

## Technologies Used

- **Frontend**: React, Vite, TypeScript, Tailwind CSS
- **Backend**: Node.js, Express, TypeScript
- **Database**: PostgreSQL (via Drizzle ORM)
- **Authentication**: JWT
- **Other Tools**: Zod, clsx, React Icons, Vite Plugin SSL

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/gamebazaar.git
cd gamebazaar
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure Environment Variables

`.env` ফাইল তৈরি করুন মূল ডিরেক্টরিতে এবং নিচের ভেরিয়েবলগুলো যুক্ত করুন:

```env
JWT_SECRET=your_jwt_secret_key_here
DATABASE_URL=postgresql://username:password@host:port/database
```

অথবা আপনি `.env.example` ফাইলটি কপি করে `.env` বানিয়ে নিতে পারেন:

```bash
cp .env.example .env
```

### 4. Start the development server

```bash
npm run dev
```

## Folder Structure

```
.
├── client        # React frontend
├── server        # Express backend
├── shared        # Common types/utils between frontend & backend
├── .env.example  # Example env file
├── package.json
└── tsconfig.json
```

## License

[MIT](LICENSE)