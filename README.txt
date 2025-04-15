How to Run Your Background Remover API

1. Install Python (if not already installed): https://www.python.org/downloads/

2. Install dependencies:
   pip install -r requirements.txt

3. Start the server:
   uvicorn main:app --host 0.0.0.0 --port 8000

4. Test it in your browser:
   http://localhost:8000/docs

   Or from any frontend by POSTing an image to:
   http://<your-ip>:8000/remove-bg/

5. If using from phone:
   - Make sure your phone and PC are on the same Wi-Fi
   - Use your PC's local IP address in place of 'localhost'

6. To deploy online:
   - Upload to GitHub
   - Use Render.com or Railway.app to create a web service
   - Set start command: uvicorn main:app --host 0.0.0.0 --port 8000
