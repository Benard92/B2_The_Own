# FECO — Finance Education College Online

FECO provides customers with online services and interactive learning tutorials for investment and financial education. It offers course content, practice tools, user dashboards, and optional paid services to help learners build investing skills.

## Key features
- Course catalog with lessons, quizzes, and progress tracking
- Interactive tutorials and simulations for investment strategies
- User accounts, profiles, and progress dashboards
- Payment/subscription support for premium content
- Admin UI for managing courses and users
- API endpoints for content and user data (REST or GraphQL)
- Analytics and reporting for student progress

## Getting started (local)
1. Clone the repo
   ```bash
   git clone https://github.com/Benard92/B2_The_Own.git
   ```
2. Change into the project directory
   ```bash
   cd B2_The_Own
   ```
3. Install dependencies
   - For Node: `npm install`
   - For Python: `python -m venv .venv && source .venv/bin/activate && pip install -r requirements.txt`
4. Configure environment variables
   - Copy `.env.example` to `.env` and set DB and API keys
5. Run the app
   - `npm start` or `python manage.py runserver`
6. Run tests
   - `npm test` or `pytest`

## Suggested project structure
- /backend — API, models, auth
- /frontend — web app, components, pages
- /docs — design, API docs, curriculum outlines
- /scripts — deployment and maintenance scripts

## Roadmap (MVP)
- User registration, login, and profile
- Course creation and lesson viewer
- Quizzes and progress tracking
- Basic dashboard for learners
- Admin course management
- Payment integration (Stripe/PayPal)

## Contributing
- Fork the repo and create a branch per feature: `feature/short-description`
- Follow the code style and add tests for new features
- Open a pull request with a clear description and link to related issues
- See CONTRIBUTING.md for more details

## License
MIT (change if needed)

## Contact
- Maintainer: Benard92
- Project issue: https://github.com/Benard92/B2_The_Own/issues/2