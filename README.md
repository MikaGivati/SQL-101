Ledger & Groove — Learn SQL

An interactive, self-contained SQL course that runs entirely in your browser. No installs, no server, no account — just open the HTML file.

Built around a small vinyl record shop database (artists, albums, customers, purchases), the course walks through eight lessons covering the SQL basics, with editable worked examples and self-checking practice tasks.

Try it

Open sql_course.html directly in any modern browser — locally (double-click the file) or hosted (e.g. via GitHub Pages).

Looking for something harder? See sql_course_advanced.html and its own README.

What's covered
SELECT basics — choosing columns, wildcards, aliases
WHERE — filtering rows with comparisons, AND/OR, LIKE, BETWEEN
Sorting & limiting — ORDER BY, LIMIT, DISTINCT
Aggregate functions — COUNT, SUM, AVG, MIN, MAX
Grouping data — GROUP BY, HAVING
Joins — INNER JOIN, LEFT JOIN
Subqueries
Modifying data — INSERT, UPDATE, DELETE

Each lesson has:

A short explanation and worked examples you can edit and re-run
Practice tasks with a Run button (see your query's real output) and a Check answer button (grades your query against the expected result)
Hints and an optional Show solution for when you're stuck
How it works

The course runs real SQL against a real database, in-browser:

sql.js (SQLite compiled to WebAssembly) provides the database engine, loaded from a CDN.
The sample database (artists, albums, customers, purchases) is created and seeded fresh each time the page loads.
All progress, checkmarks, and database state live in memory for the current session — reloading the page resets everything back to the starting point.
Lesson 8's practice tasks (INSERT/UPDATE/DELETE) share one running copy of the database so changes carry over between its tasks, since edits naturally build on each other.
Tech

Single HTML file — no build step, no dependencies to install. Everything (styles, logic, lesson content) lives in sql_course.html.
