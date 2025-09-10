# AI-Powered Workplace Search (Theme 2 – MCP Hackathon)

Solo participant: chandan T

This repository will contain my MCP server for Theme 2 of the Descope MCP Hackathon.
📝 AI-Powered Workplace Search

This project was built by **Chandan** for a hackathon. It is a simple tool that lets people search through company documents (PDF, Word, CSV, etc.) instantly using a web interface.

✨ What it does

- Upload or place internal documents into a `data/` folder.
- The app automatically reads and indexes the text.
- A FastAPI server exposes a `/search` endpoint.
- You can type a query and instantly see matching text/snippets.

🚀 How to install & run

1. Make sure Python 3.11+ is installed.
2. Clone or unzip the project.
3. Put some sample documents into the `data/` folder (for example `EmployeeHandbook.pdf`).
4. Open PowerShell in the project folder and run:

powershell
.\run_project.ps1


5.Open your browser at http://127.0.0.1:8000/docs
 to see the Swagger UI and test the API.

📝 Example URLs to test

GET http://127.0.0.1:8000/search?q=policy

GET http://127.0.0.1:8000/docs (Swagger UI)

You can use the Swagger UI “Try it out” button to run searches live.


🎯 Why I built it

Finding information quickly inside lots of workplace documents is hard.
This project shows a simple way to index and search them using open-source tools.

🙋‍♂️ Author

Built by Chandan (solo participant).
