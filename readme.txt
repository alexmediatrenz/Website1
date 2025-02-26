# Cosmic Personality Blog

An interactive blog platform with personality quizzes, zodiac games, and a fun dating match generator.

## 🌟 Features

- **Personality Quiz Hub**: Dive deep into your personality with science-based and fun assessments
- **Zodiac Dart Game**: Test your cosmic compatibility with an interactive wheel-of-fortune style game
- **Random Dating Match Generator**: Generate potential matches based on birth data and Twitter presence
- **Content Integration**: Blog articles on relationships, self-discovery, and astrology

## 🚀 Getting Started

### Prerequisites

- Node.js 16.x or higher
- npm or yarn
- PostgreSQL database

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/cosmic-personality-blog.git
cd cosmic-personality-blog
```

2. Install dependencies
```bash
npm install
# or
yarn install
```

3. Set up environment variables
```bash
cp .env.example .env
# Edit .env with your database credentials and API keys
```

4. Set up the database
```bash
npm run prisma:generate
npm run prisma:migrate
npm run seed
```

5. Start the development server
```bash
npm run dev
# or
yarn dev
```

6. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application

## 🛠️ Tech Stack

- **Frontend**: Next.js, React, TailwindCSS, Framer Motion
- **Backend**: Next.js API Routes
- **Database**: PostgreSQL with Prisma ORM
- **Authentication**: NextAuth.js
- **Styling**: TailwindCSS with custom components
- **State Management**: React Context and hooks
- **Deployment**: Vercel (recommended)

## 📁 Project Structure

The project follows a feature-based structure:

- `app/`: Next.js app router pages and API routes
- `components/`: Reusable UI components
- `lib/`: Core utilities and business logic
- `hooks/`: Custom React hooks
- `context/`: React context providers
- `types/`: TypeScript type definitions
- `data/`: Static data for quizzes, zodiac info, etc.
- `prisma/`: Database schema and migrations

## 🧪 Running Tests

```bash
npm run test
# or
yarn test
```

## 📚 Documentation

For more detailed documentation on how to use and contribute to this project, see [DOCS.md](./DOCS.md).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgements

- All the amazing libraries and frameworks that made this project possible
- The open-source community for inspiration and support
