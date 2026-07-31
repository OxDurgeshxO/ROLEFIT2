# RoleFit — Resume Analyzer & Job Match Platform

An educational AI-powered resume analyzer that scores your resume against curated job roles, checks ATS readiness, and builds personalized learning roadmaps.

## Features

- 📄 **Resume Upload** — PDF, DOCX, or plain text
- 🎯 **Role Matching** — Scores against 11 curated job roles
- ✅ **ATS Readiness Check** — 8-point resume structure analysis
- 🧪 **What-If Simulator** — Preview scores if you learn new skills
- 📊 **Gap Intelligence** — Coverage matrix and highest-impact skills
- 🗺️ **Learning Roadmap** — Week-by-week plan with projects
- 🎓 **Certification Recommendations** — Based on your skills and gaps
- 💬 **Interview Prep** — Role-specific practice questions
- 📈 **Progress Tracking** — Score journey over time
- 🔄 **Resume Comparison** — Track improvements between versions

## Tech Stack

- **Framework:** Next.js 16 (App Router)
- **Database:** PostgreSQL with Drizzle ORM
- **Styling:** Tailwind CSS v4
- **Animations:** Framer Motion
- **File Parsing:** pdf-parse, mammoth

## Deployment

### Quick Deploy to Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/YOUR_USERNAME/rolefit)

1. Click the button above
2. Create a PostgreSQL database on [Neon](https://neon.tech) (free)
3. Add `DATABASE_URL` environment variable
4. Deploy!

### Environment Variables

```
DATABASE_URL=postgresql://user:pass@host/dbname?sslmode=require
```

## Local Development

```bash
# Install dependencies
npm install

# Set up database
cp .env.example .env
# Edit .env with your DATABASE_URL

# Push schema to database
npx drizzle-kit push

# Start development server
npm run dev
```

## License

MIT — Built for educational purposes.
