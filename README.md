# Overview of Node.js Express Login example

We will build a Node.js Express application in that:

Authentication: User can signup new account, or login with username & password.
Authorization: By User’s role (admin, moderator, user), we authorize the User to access resources

| Method |      routers      |           access           |
| :----- | :---------------: | :------------------------: |
| POST   | /api/auth/signup  |     signup new account     |
| POST   | /api/auth/signin  |      login an account      |
| POST   | /api/auth/signout |     logout the account     |
| GET    |   /api/test/all   |  retrieve public content   |
| GET    |  /api/test/user   |   access User’s content    |
| GET    |   /api/test/mod   | access Moderator’s content |
| GET    |  /api/test/admin  |   access Admin’s content   |

# Technology

- Express 4.18.2
- bcryptjs 2.4.3
- cookie-session 2.0.0
- jsonwebtoken 9.0.0
- Sequelize 6.31.1
- MySQL

💖coming soon
