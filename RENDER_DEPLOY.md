# Render Python MCP Server Setup

## How to Deploy

1. **Push all files to a GitHub repository**
   - Include: `mcp_server.py`, `resume.txt`, `requirements.txt`, `Procfile`, and optionally `readme.md`.

2. **Create a new Web Service on Render**
   - Go to https://dashboard.render.com/
   - Click "New +" > "Web Service"
   - Connect your GitHub repo
   - For build and start commands, Render will use `requirements.txt` and `Procfile` automatically
   - Choose a free or paid plan

3. **After deploy, Render will give you a public URL**
   - Use this URL in the Puch WhatsApp chat:
     ```
     /mcp connect <RENDER_URL>/mcp <YOUR_APPLICATION_KEY>
     ```

## Project Files
- `mcp_server.py`: Your MCP server code
- `resume.txt`: Your markdown resume
- `requirements.txt`: Python dependencies
- `Procfile`: Tells Render how to start your server

---

**You are ready to deploy!**
