# UTube — Web Client (React)

This folder contains the React web client component of the UTube project — a browser-based frontend for browsing, watching, uploading, and managing videos.

## Live Demo

A demo of the web client is hosted on GitHub Pages:
**https://avrhambi.github.io/Utube**


## Wiki - Full Documentation

**For complete details, explanations, screenshots, and usage instructions, please visit the [Wiki tab](https://github.com/Avrhambi/Utube/wiki).**

---


## Getting Started

1. **Clone the Repository**
   ```bash
    # if you didn't alreardy clone it once for the entire project
    git https://github.com/Avrhambi/Utube.git
    cd Web_client

2. **Run the Application**
Use the following command to run the app in development mode:
   ```bash
     npm start

This will open http://localhost:3000 to view it in your browser. The page will automatically reload when you make edits, and any lint errors will show in the console.

 3. **Testing the Application**
To run the tests interactively, use:
    ```bash 
      npm test

You can refer to the Create React App documentation for more details about running tests.

 4. **Building for Production**
To build the web app for production:
    ```bash 
     npm run build

This will bundle and optimize the app into the build folder. After making design changes or adding features, you need to run this command. The files and folders from the build folder, except the media folder, should be copied to replace the current files in the public folder of the server-side code.
The media folder in the server’s public directory should remain unchanged.
