# IntelliGrade

IntelliGrade is an AI Dependency & Academic Performance Forecasting Dashboard designed to help educators and administrators monitor student AI usage and predict academic performance risks. The application provides insights into AI dependency patterns, student risk levels, and performance predictions through interactive data visualizations.

## Features

- User authentication with login and signup powered by Supabase
- Dashboard with multiple tabs for:
  - Overview of key metrics and trends
  - Student risk analysis with detailed profiles
  - AI usage pattern visualization
  - Academic performance predictions and risk categorization
- Interactive charts and graphs using Recharts
- Risk-based recommendations for student interventions
- Responsive design with Tailwind CSS and Lucide React icons

## Tech Stack

- Next.js (React framework)
- TypeScript
- Supabase (authentication and backend)
- Tailwind CSS (styling)
- Recharts (data visualization)
- Lucide React (icons)

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd intelligrade-frontend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Set up environment variables:

   Create a `.env.local` file in the project root with the following variables:

   ```
   NEXT_PUBLIC_SUPABASE_URL=your-supabase-url
   NEXT_PUBLIC_SUPABASE_ANON_KEY=your-supabase-anon-key
   ```

4. Run the development server:

   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser to view the app.

## Environment Variables

- `NEXT_PUBLIC_SUPABASE_URL`: Your Supabase project URL
- `NEXT_PUBLIC_SUPABASE_ANON_KEY`: Your Supabase anonymous public API key

## Usage

- Access the app at the root URL.
- If not logged in, use the Login or Sign Up links to authenticate.
- Once logged in, you will be directed to the IntelliGrade dashboard.
- Navigate through the tabs to explore:
  - Overview metrics and trends
  - Detailed student risk analysis and profiles
  - AI usage patterns and correlations
  - Academic performance predictions and insights

## Implementation Details

- The app uses Supabase for user authentication and backend services.
- The dashboard (`intelligrade_dashboard.tsx`) features multiple tabs with charts built using Recharts.
- Student data is currently generated as mock data for demonstration purposes.
- Risk levels are calculated based on AI dependency scores and used to provide recommendations.
- Tailwind CSS is used for styling, ensuring a responsive and modern UI.
- Lucide React provides consistent iconography throughout the app.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
