# VAPI AI Voice Assistant

## Overview

This project is a voice assistant powered by VAPI AI, featuring a React frontend and a Python backend. It enables users to interact with an AI through voice commands and receive spoken responses.

## Purpose and Problem Solved

The primary purpose of this project is to demonstrate the integration of VAPI AI for creating sophisticated voice-based applications. It provides a hands-free interface for interacting with AI, potentially solving problems related to accessibility or enabling new forms of user interaction.

## Key Features

* **Real-time Voice Interaction:** Engage in natural conversations with the AI.
* **VAPI AI Integration:** Leverages VAPI's capabilities for voice recognition and synthesis.
* **React Frontend:** Modern and responsive user interface.
* **Python Backend:** Handles server-side logic and VAPI communication.

## Requirements

### Prerequisites

* [Node.js](https://nodejs.org/) (LTS version recommended)
* [npm](https://www.npmjs.com/) (comes with Node.js)
* [Python](https://www.python.org/) (version 3.x recommended)
* [pip](https://pip.pypa.io/en/stable/) (comes with Python)
* VAPI AI API Key (obtain from [VAPI AI](https://vapi.ai/))

### Dependencies

* **Frontend:** See `frontend/package.json` (React, Vite, @vapi-ai/web, etc.)
* **Backend:** See `backend/requirements.txt`

## File Structure

```
.
├── .vscode/
│   └── settings.json
├── backend/
│   ├── .env             # Backend environment variables (VAPI Key, etc.)
│   ├── main.py          # Main backend application script
│   └── requirements.txt # Python dependencies
├── frontend/
│   ├── .env             # Frontend environment variables
│   ├── .gitignore
│   ├── README.md        # Frontend specific README
│   ├── eslint.config.js # ESLint configuration
│   ├── index.html       # Main HTML entry point
│   ├── package-lock.json
│   ├── package.json     # Node.js dependencies and scripts
│   ├── public/
│   │   └── vite.svg
│   ├── src/
│   │   ├── App.jsx        # Main React application component
│   │   ├── ai.js          # VAPI AI integration logic
│   │   ├── call/          # Components related to the call UI
│   │   ├── index.css      # Global styles
│   │   └── main.jsx       # React application entry point
│   └── vite.config.js   # Vite configuration
└── README.md            # This file (Project Root README)
```

## Getting Started

1. **Clone the repository:**

   ```bash
   git clone <your-repository-url>
   cd VAPI-AI-Voice-Assistant-main
   ```
2. **Setup Backend:**

   ```bash
   cd backend
   # Create a virtual environment (recommended)
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`

   # Install dependencies
   pip install -r requirements.txt

   # Create a .env file and add your VAPI_API_KEY
   echo "VAPI_API_KEY=your_vapi_api_key_here" > .env

   # Run the backend server
   python main.py
   ```
3. **Setup Frontend:**
   *Open a new terminal.*

   ```bash
   cd ../frontend

   # Install dependencies
   npm install

   # Create a .env file if needed for frontend variables
   # echo "VITE_API_URL=http://localhost:8000" > .env # Example

   # Start the development server
   npm run dev
   ```
4. **Access the application:** Open your browser and navigate to the URL provided by the Vite development server (usually `http://localhost:5173`).

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/your-feature-name`).
6. Open a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details (if applicable, otherwise state the license).

## Contact

Syed Abdullah Shah

- 🌐 Connect with me on LinkedIn [**LinkedIn**](http://www.linkedin.com/in/syed-abdullah-shah-4018a5176)
- 📩 Email: [sa.abdullahshah.2001@gmail.com](mailto:sa.abdullahshah.2001@gmail.com)
