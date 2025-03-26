# WorkZap - On-Demand Job Platform

WorkZap is a modern web platform that connects skilled professionals with clients looking for on-demand work. Built with React, TypeScript, and Tailwind CSS, it provides a seamless experience for both freelancers and clients.

## Features

- *Dual Profile System*

  - Switch between client and freelancer views
  - Personalized dashboards for both roles

- *Task Management*

  - Post detailed job listings with comprehensive information
  - Specify budgets, deadlines, and required skills
  - Track task status and progress

- *Modern UI/UX*
  - Dark theme interface
  - Responsive design for all devices
  - Intuitive navigation and form inputs

## Tech Stack

- React
- TypeScript
- Tailwind CSS
- Supabase (Authentication)
- React Router
- Lucide Icons

## Getting Started

1. *Clone the repository*

   bash
   git clone https://github.com/yourusername/workzap.git
   cd workzap
   

2. *Install dependencies*

   bash
   npm install
   

3. *Set up environment variables*
   Create a .env file in the root directory:

   env
   VITE_SUPABASE_URL=your_supabase_url
   VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
   

4. *Start the development server*
   bash
   npm run dev
   

## Project Structure


src/
├── components/     # Reusable UI components
├── context/       # React context providers
├── lib/           # Utility functions and configurations
├── pages/         # Page components
└── types/         # TypeScript type definitions


## Contributing

1. Fork the repository
2. Create your feature branch (git checkout -b feature/amazing-feature)
3. Commit your changes (git commit -m 'Add some amazing feature')
4. Push to the branch (git push origin feature/amazing-feature)
5. Open a Pull Request

## Acknowledgments

- [Tailwind CSS](https://tailwindcss.com/)
- [Lucide Icons](https://lucide.dev/)
- [Supabase](https://supabase.com/)
