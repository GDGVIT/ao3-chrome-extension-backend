<p align="center">
<a href="https://dscvit.com">
	<img width="400" src="https://user-images.githubusercontent.com/56252312/159312411-58410727-3933-4224-b43e-4e9b627838a3.png#gh-light-mode-only" alt="GDSC VIT"/>
</a>
	<h2 align="center"> AO3 Assist </h2>
	<h4 align="center"> A sophisticated recommendation system for Archive of Our Own (AO3) that leverages AI/ML to provide personalized fanfiction suggestions through a Chrome extension. Features secure authentication, profile management, and ML-powered recommendations. <h4>
</p>

---
[![Join Us](https://img.shields.io/badge/Join%20Us-Developer%20Student%20Clubs-red)](https://dsc.community.dev/vellore-institute-of-technology/)
[![Discord Chat](https://img.shields.io/discord/760928671698649098.svg)](https://discord.gg/498KVdSKWR)

[![DOCS](https://img.shields.io/badge/Documentation-see%20docs-green?style=flat-square&logo=appveyor)](INSERT_LINK_FOR_DOCS_HERE) 
  [![UI ](https://img.shields.io/badge/User%20Interface-Link%20to%20UI-orange?style=flat-square&logo=appveyor)](INSERT_UI_LINK_HERE)


## Features

- [X]  Secure JWT-based authentication system with token validation
- [X]  User profile management with customizable usernames
- [X]  ML-powered fanfiction recommendations based on user preferences
- [X]  Cross-origin resource sharing (CORS) support for Chrome extension 
- [X]  RESTful API architecture with Express.js 
- [X]  Password hashing for enhanced security 
<br>

## Dependencies
- Node.js v14.0.0 or higher
- PostgreSQL database
- Core Dependencies:

    - express: ^4.19.2
    - jsonwebtoken: ^9.0.2
    - bcrypt: ^5.1.1
    - cors: ^2.8.5
    - body-parser: ^1.20.2
    - cookie-parser: ^1.4.6
    - dotenv: ^16.4.5
    - pg: ^8.12.0


## API Endpoints

### Authentication Routes (`/auth`)
```
POST /auth/login - User login
POST /auth/register - New user registration
GET /auth/token/:token - Token validation
GET /auth/validate - Verify user token
PATCH /auth/update_username - Update user's username
GET /auth/userdetail - Get user details
```

### AI/ML Routes
```
GET /recom - Get personalized recommendations (requires authentication)
```

## Running

Clone the repository and install dependencies:
```bash
git clone https://github.com/GDGVIT/ao3-chrome-extension-backend.git
cd ao3-chrome-extension-backend
npm install
```

Set up your environment variables in `.env`:
```bash
PORT=3000
DATABASE_URL=your_postgres_connection_string
JWT_SECRET=your_jwt_secret
# Add other required environment variables
```

Start the development server:
```bash
npm run test
```

# Contributors

<table>
<tr align="center">
	<td>
	Varshith Kumar
	<p align="center">
		<img src="https://temp-dep.vercel.app/_next/image?url=%2Fteam%2Ftechnical%2Fvarshith.jpg&w=1920&q=75" width="150" height="150" alt="Varshith Kumar">
	</p>
		<p align="center">
			<a href="https://github.com/var-code-5">
				<img src="http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width="36" height="36" alt="GitHub"/>
			</a>
			<a href="https://www.linkedin.com/in/varshith-kumar-reddy-meda-02a7b02b3/">
				<img src="http://www.iconninja.com/files/863/607/751/network-linkedin-social-connection-circular-circle-media-icon.svg" width="36" height="36" alt="LinkedIn"/>
			</a>
		</p>
		<p align="center">
			Backend 
		</p>
	</td>
	<td>
	Dipit Madan
	<p align="center">
		<img src="https://temp-dep.vercel.app/_next/image?url=%2Fteam%2Ftechnical%2Fdipit.jpeg&w=1920&q=75" width="150" height="150" alt="Dipit Madan">
	</p>
		<p align="center">
			<a href="https://github.com/Dipit12">
				<img src="http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width="36" height="36" alt="GitHub"/>
			</a>
			<a href="https://www.linkedin.com/in/dipit-madan">
				<img src="http://www.iconninja.com/files/863/607/751/network-linkedin-social-connection-circular-circle-media-icon.svg" width="36" height="36" alt="LinkedIn"/>
			</a>
		</p>
		<p align="center"
		<p align="center">
			Machine Learning
		</p>
	</td>
</tr>
</table>


<p align="center">
	Made with ❤ by <a href="https://dscvit.com">GDSC-VIT</a>
</p>


