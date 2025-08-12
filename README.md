# GridLink

GridLink is a dedicated digital platform for Gran Turismo Sim-Racing Leagues to serve as their online home and streamline league management. It centralizes key league operations such as user registration, race scheduling, results submission, standings, and notifications—all tailored specifically for sim-racing leagues.

## Project Purpose

Gran Turismo sim-racing leagues currently rely heavily on disparate tools like Discord, spreadsheets, and manual processes that are not specialized for their needs. GridLink’s mission is to provide an integrated, racer-focused platform that enhances engagement and simplifies administration.

## MVP Features

This initial release (MVP) includes:

- League Home / Public Landing Page: Basic league info, race calendar, and results display
- User Registration & Authentication: Secure signup, login, and role-based access with Better Auth
- Roster Management: Admins manage active racers and team assignments
- Race Calendar & Scheduling: Create and view upcoming league races and events
- Race Results Submission: Admins log race results quickly and accurately
- Standings Table & Leaderboard: Automated standings updates with filters by class/team
- Basic Notifications: Email or in-site alerts for new events, posted results, and updated standings

## Tech Stack

- **Frontend:** Vite, React (TypeScript), TailwindCSS, and shadcn/ui for a modern, performant, and responsive UI
- **Backend:** Node.js with Express powering the API and business logic
- **Database:** PostgreSQL storing structured league and user data
- **Authentication:** Better Auth managing user sessions, registration, and authorization

## Getting Started

### Prerequisites

- Node.js latest LTS
- PostgreSQL database server
- [Better Auth configuration as per project specs]

### Installation

1. Clone the repo
   `git clone https://github.com/yourusername/gridlink.git`
2. Install backend and frontend dependencies
   From project root:
   `npm install`
3. Configure environment variables (database URL, auth keys, etc.)
4. Run database migrations/seeding (if applicable)
5. Start development server
   `npm run dev`

## Contributing

Contributions are welcome! Please open issues or submit pull requests to help improve the platform.

## License

Specify your license here (e.g., MIT).

---

GridLink aims not just to keep the trains running but to make the sim-racing league experience something drivers and admins truly love. This README will evolve as the platform grows beyond MVP.

---

If you want me to add a detailed API reference, ERD diagrams, or deployment instructions, just ask!
