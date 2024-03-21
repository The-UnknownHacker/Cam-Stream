## Cam-Stream

Cam-Stream is a simple Flask app that enables you to stream your webcam.
This app was originaly made to stream video from my 3d printer to my ip

### Installation

1. **Clone the Repository**: 
   ```
   git clone https://github.com/The-UnknownHacker/Cam-Stream/
   ```
   Alternatively, you can download the ZIP file.

2. **Navigate to the Directory**: 
   ```
   cd Cam-Stream
   ```

3. **Run the Application**: 
   Open the `main.py` file and execute it.

### Usage

4. **Install Cloudflare Tunnel**: 
   Download and install Cloudflare Tunnel.

5. **Run the Tunnel**: 
   Execute the following command to run the Cloudflare Tunnel:
   ```
   cloudflared tunnel --url http://localhost:5000
   ```

### Accessing Your Stream

Once the Cloudflare Tunnel is running, you can access your webcam stream via the Cloudflare tunnel URL.

### Notes

- Ensure your webcam is properly connected and configured.
- Make sure to grant necessary permissions for accessing the webcam.
- For security reasons, avoid sharing your stream URL publicly unless necessary.

Feel free to customize the app or contribute to its development! If you encounter any issues or have suggestions, please open an issue or submit a pull request.

Enjoy streaming your webcam with Cam-Stream!
