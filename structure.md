# Project Structure

```
/ (root)
  package.json
  README.md
  (many documentation md files)
  backend/
    package.json
    server.js
    controllers/
    middleware/
    migrations/
    models/
    routes/
    config/
  frontend/
    package.json
    next.config.js
    jsconfig.json
    app/         # Next.js 13 app directory
    components/
    context/
    hooks/
    lib/
    public/
    styles and configs
```

- Backend uses Express.js and Sequelize for database interactions.
- Frontend uses Next.js with Tailwind CSS.
- Tests are implemented via scripts in backend and possibly front-end.
