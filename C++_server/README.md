# UTube — C++ Server

This folder contains the C++ server component of the UTube project. It handles intelligent video recommendations using a multi-threaded TCP architecture that runs alongside the Node.js backend.


## Wiki - Full Documentation

**For complete details, explanations, screenshots, and usage instructions, please visit the [Wiki tab](https://github.com/Avrhambi/Utube/wiki).**


## FULL PROJECT DETAILS
For full details on the entire UTube project, including the Android app, React web app, and Node.js server, please skip this README.md and refer to the wiki pages located inside the `cpp_server` branch's wiki folder or on the wiki page of the entire repository.

## GETTING STARTED
To set up and run the server locally, follow these steps:

1. **Clone the Repository**
   Open your terminal and run the following command:
   ```bash
   git clone https://github.com/Avrhambi/Utube.git c++_server
   cd C++_server

### Step 1: Install the required JSON library
Before compiling, run this command in the terminal to install the required JSON library:

```bash
sudo apt-get install nlohmann-json3-dev
```

### Step 2: Compile and run the server
To compile and run the C++ server, use this command in the terminal:

```bash
make && make run
```

To stop the server, use `Ctrl+C`.

### Additional options:
- `make` - Compile only
- `make run` - Run the compiled server
- `make clean` - Remove compiled files

## IMPORTANT: PORT AVAILABILITY CHECK
Before running the services, ensure that port `55551` is available on your system. Follow these steps to check:

### Windows:
1. Open Command Prompt (cmd).
2. Run the following command:

```bash
netstat -ano | findstr :55551
```

If there's no output, the port is available.

### Linux/macOS:
1. Open Terminal.
2. Run the following command:

```bash
lsof -i :55551
```

If there's no output, the port is available.

If the port is in use, you may need to choose a different port or close the application using it.

### Note: 
If you change the port, remember to update it in both:
1. The **C++ server** in `main.cpp` at the line on top:

```cpp
const int SERVER_PORT = 55551;
```

2. The **NodeJS server** in `services/cppServerService.js` at the line on top:

```js
const CPP_SERVER_PORT = 55551;
```
