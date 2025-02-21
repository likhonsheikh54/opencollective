# Open Collective Dashboard

A modern, feature-rich dashboard for managing open source projects and contributions through Open Collective. Built with Next.js 14, TypeScript, and Tailwind CSS.

## Features

- 📊 Real-time project analytics and statistics
- 👥 Contributor management and tracking
- 💰 Financial overview and donation tracking
- 🌓 Dark mode support
- 📱 Fully responsive design
- 🔒 Authentication and authorization
- 🎨 Modern UI with shadcn/ui components

## Tech Stack

- **Framework:** Next.js 14 with App Router
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **UI Components:** shadcn/ui
- **Authentication:** NextAuth.js
- **State Management:** React Context
- **Database:** Prisma with PostgreSQL
- **Deployment:** Vercel

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/likhonsheikh54/opencollective.git
   cd opencollective
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Copy the example environment file:
   ```bash
   cp .env.example .env.local
   ```

4. Update the environment variables in `.env.local`

5. Start the development server:
   ```bash
   npm run dev
   ```

## Project Structure

```plaintext
├── app/                 # Next.js app directory
│   ├── api/            # API routes
│   ├── (auth)/        # Authentication routes
│   ├── projects/      # Project-related pages
│   └── settings/      # Settings pages
├── components/         # React components
├── lib/               # Utility functions
├── prisma/            # Database schema and migrations
└── public/            # Static assets
```

## Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

If you find this project helpful, please consider:

- Starring the repository
- Contributing to the codebase
- Supporting us on Open Collective

## Acknowledgments

- [Open Collective](https://opencollective.com) for their amazing platform
- [Vercel](https://vercel.com) for hosting
- [shadcn/ui](https://ui.shadcn.com) for the beautiful components

This advanced version includes:

1. A modern dashboard with real-time analytics
2. Project management features
3. Dark mode support
4. Responsive design
5. Activity tracking
6. Professional UI components
7. Comprehensive documentation

To complete the setup:

1. Initialize the repository with the provided code
2. Set up GitHub Actions for CI/CD
3. Configure the deployment on Vercel
4. Set up the database with Prisma
5. Add authentication with NextAuth.js
6. Configure the Open Collective API integration

The dashboard provides a professional interface for managing open source projects and tracking contributions, making it easier for maintainers and contributors to collaborate effectively.
