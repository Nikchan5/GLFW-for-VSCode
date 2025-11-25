GLFW for VSCode — OpenGL Quick-Start Template

A clean and ready-to-use template for starting OpenGL development with GLFW in Visual Studio Code.
The project includes a fully pre-configured tasks.json, basic rendering examples, and core OpenGL structures such as VAO, VBO, and EBO — all set up so you can start coding immediately.

🚀 Features
🔳 Basic GLFW Window

Initialization of GLFW

Window creation

Rendering loop

Basic input handling

🎨 Shader Pipeline

Example Vertex and Fragment shaders

Shader compilation & linking

📦 VBO / VAO / EBO

VBO: Uploading vertex data to GPU

VAO: Storing vertex attribute configurations

EBO: Indexed rendering for shared vertices

📐 GLM Integration

Easy vector & matrix math

Model / View / Projection examples

🖼️ stb_image.h

Demonstration of loading textures or using other single-header utilities

🔧 Setup and Usage
1️⃣ Prerequisites

You'll need:

Visual Studio Code

C++ compiler (GCC/G++, Clang, or MSVC)

GLFW, OpenGL, and optionally GLM
(or already included in your setup)

2️⃣ Clone the Repository
git clone <your-repo-url>
cd <your-repo-folder>

3️⃣ VSCode Configuration

This template already includes:

.vscode/tasks.json — build command setup
(compiling and linking OpenGL, GLFW, GLM, stb, etc.)

⚠️ Important:
Make sure include paths and library paths in tasks.json match your system.

4️⃣ Build & Run

Open the folder in VSCode

Press Ctrl + Shift + B
(starts build using tasks.json)

After building, run the executable:

.\cutable.exe


This will open your GLFW window.

🤝 Contributing

Have ideas, improvements, or fixes?
Feel free to open an Issue or create a Pull Request!
