# Squad Syncer

Squad Syncer is a robust MERN stack web application designed to streamline team collaboration for diverse tasks. The platform, with its intuitive interface featuring both dark and light modes, ensures a seamless experience for users. 

## Features

- **User Authentication**: Easily create an account and log in to access the platform.
- **Dashboard**: Display pending and accepted team requests.
- **My Team Section**: Empower users to effortlessly create or join teams.
- **Team Creation**: Specify crucial details like title, description, required skills, and the desired number of team members.
- **Real-time Chat**: Facilitated by WebSockets through Socket.IO, fostering efficient communication within teams.
- **Security**: Implement JWT authentication for secure user access.

## Technologies Used

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Styling**: Tailwind CSS

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/anni-loper/SquadSyncer.git
```

2. Navigate to the project directory:

```bash
cd squad-syncer
```

3. Install dependencies for the backend:

```bash
npm install
```

4. Navigate to the `client` directory and install dependencies for the frontend:

```bash
cd client
npm install
```

5. Go back to the project root directory:

```bash
npm run dev
```

8. Open [http://localhost:3000](http://localhost:3000) to view the application in your browser.

## Contributing

Contributions are welcome! Please refer to the [Contribution Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).
