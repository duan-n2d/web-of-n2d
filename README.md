# My Learning Journey

![Project Banner](https://via.placeholder.com/1200x300)

A beautiful, modern website to document and share my learning journey in Coding, Data Analysis, Data Engineering, and English.

## 🚀 Features

- **Modern Tech Stack**: FastAPI backend + Svelte frontend
- **Responsive Design**: Beautiful UI that works on all devices
- **Learning Tracks**: Separate sections for each learning path
- **Progress Tracking**: Track progress in different learning areas
- **Resource Library**: Organize learning resources by category
- **Note Taking**: Create and organize notes for each topic
- **Code Snippets**: Save and share useful code snippets
- **Project Showcase**: Highlight completed projects and skills gained

## 💻 Technology Stack

### Backend
- [FastAPI](https://fastapi.tiangolo.com/) - Modern, fast web framework for building APIs
- [SQLAlchemy](https://www.sqlalchemy.org/) - SQL toolkit and ORM
- [Pydantic](https://pydantic-docs.helpmanual.io/) - Data validation and settings management
- [Alembic](https://alembic.sqlalchemy.org/en/latest/) - Database migrations

### Frontend
- [Svelte](https://svelte.dev/) - Cybernetically enhanced web apps
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [DaisyUI](https://daisyui.com/) - Component library for Tailwind CSS
- [Chart.js](https://www.chartjs.org/) - Simple yet flexible JavaScript charting
- [Marked](https://marked.js.org/) - Markdown parser and compiler

## 🛠️ Getting Started

### Prerequisites
- [Docker](https://www.docker.com/) and Docker Compose
- [Node.js](https://nodejs.org/) (v14 or higher)
- [Python](https://www.python.org/) (v3.8 or higher)

### Installation

1. Clone the repository
```bash
git clone https://github.com/duan-n2d/web-of-n2d.git
cd my-learning-journey
```

2. Start the development environment
```bash
docker-compose up -d
```

3. Access the application
- Frontend: http://localhost:5000
- Backend API: http://localhost:8000
- API Documentation: http://localhost:8000/docs

### Manual Setup (without Docker)

#### Backend
```bash
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
uvicorn app.main:app --reload
```

#### Frontend
```bash
cd frontend
npm install
npm run dev
```

## 📁 Project Structure

The repository follows a clean architecture with clear separation of concerns. See the [Project Structure](PROJECT_STRUCTURE.md) for more details.

## 🧪 Testing

### Backend
```bash
cd backend
pytest
```

### Frontend
```bash
cd frontend
npm run test
```

## 🔄 Continuous Integration

This project uses GitHub Actions for CI/CD. Every push to the main branch triggers:
- Linting checks
- Unit tests
- Build tests
- Deployment (if on main branch)

## 🌐 Deployment

The site can be deployed to various platforms:
- [Vercel](https://vercel.com/) for frontend
- [Heroku](https://www.heroku.com/) or [DigitalOcean](https://www.digitalocean.com/) for backend
- [Netlify](https://www.netlify.com/) as a full-stack alternative

Detailed deployment instructions are available in [DEPLOYMENT.md](DEPLOYMENT.md).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📊 My Learning Progress

### Current Focus Areas
- 🧠 **Coding**: Advanced JavaScript, Python Design Patterns
- 📊 **Data Analysis**: Statistical Methods, Data Visualization
- 🔧 **Data Engineering**: ETL Pipelines, Data Warehousing
- 🗣️ **English**: Technical Writing, Public Speaking

### Recent Achievements
- Completed FastAPI + SQLAlchemy tutorial
- Built first end-to-end data pipeline
- Wrote technical blog post on data visualization

## 📬 Contact

- GitHub: [@duan-n2d](https://github.com/duan-n2d)
- LinkedIn: [Duan Nguyen](https://linkedin.com/in/duannguyen2606)

---

Happy working! 📚