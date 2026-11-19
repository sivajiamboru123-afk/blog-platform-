# WriteSpace Blog Platform

## Run on Windows
1. Extract this ZIP.
2. Open the `blog-platform-ready` folder in VS Code.
3. Choose Terminal → New Terminal.
4. Run `npm install` and wait for it to finish.
5. Run `npm start`.
6. Open http://localhost:3000 in Chrome.

## Included
- Register and log in
- Create and read blog posts
- Add comments
- Delete your own posts and comments
- Responsive frontend
- Local JSON persistence in `data/db.json`

Node.js 18+ is supported; Node.js 24 LTS is recommended. This version uses JSON storage rather than native SQLite so it avoids the `better-sqlite3` native build issue.
