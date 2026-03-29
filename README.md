🚀 CodeViz – Learn, Compile & Explore Code in One Place
> A standalone .exe version of CodeViz will be available soon, allowing users to install and run the application without any manual setup.
A desktop-based developer tool designed to simplify coding, learning, and experimentation, all in one unified environment.

📌 Problem Statement

Learning programming today is fragmented, overwhelming, and inefficient, especially for beginners.

Many students are interested in tech but don’t come from a technical background
They rely heavily on online resources like tutorials and courses
This often leads to getting stuck in “tutorial hell” — consuming content without actually building or understanding deeply

At the same time:
- Learners constantly switch between:
 - YouTube / documentation for concepts
 - IDEs for coding
 - Browsers for syntax/reference
- There is no unified environment that combines:
 - Learning + Writing + Testing code
- Setting up compilers and environments is confusing for beginners
- Most tools are built for developers, not learners

👉 Result:
Cognitive overload
Lack of practical understanding
Slow progress and loss of motivation



💡 Solution – CodeViz
CodeViz solves this by providing a self-contained desktop application where users can:

- ✍️ Write code

- ⚙️ Compile & execute programs

- 📚 Learn concepts through built-in structured content

- 🔍 Access syntax-highlighted code snippets

- 🧠 Build understanding without leaving the environment

- 🔕 Stay focused with an offline, ad-free, and distraction-free experience

Think of it as a developer learning hub + mini IDE combined

🛠️ Approach & Architecture

CodeViz is built using a modular and scalable architecture:

🔹 1. GUI Layer
- Built using CustomTkinter
- Clean, minimal, distraction-free interface
- Navigation between modules:
   - Code Editor
   - Concepts
   - Snippets

🔹 2. Core Logic Layer
- Handles:
   - Compilation & execution of code
   - File handling
   - Dynamic content loading

🔹 3. Content Engine
- Uses JSON-based structured storage
- Stores:
   - Programming concepts
   - Code examples
- Easily extendable without changing code

🔹 4. Syntax Highlighting
- Implemented using Pygments
- Improves readability and learning experience

🔹 5. Compiler Integration
- Supports execution via system-installed compilers (e.g., Python, C++)
- Designed with flexible path handling (user-independent setup)

🧰 Tech Stack
- Category	                   - Technology Used

- Language	                   - Python

- GUI Framework	              - CustomTkinter

- Syntax Highlighting	        - Pygments

- Data Storage	               - JSON

- Compiler Integration	       - System-based (Python, C++)

💻 System Requirements
To run CodeViz smoothly on your PC/Laptop:


Minimum Requirements:
   - OS: Windows 10 / 11 (Recommended)
   - RAM: 4 GB
   - Storage: 200 MB free space
   - Python: 3.8+

Recommended:
   - RAM: 8 GB+
   - SSD storage
   - Python 3.10+

Required Dependencies:
   - Python installed and added to PATH
   - C++ compiler (e.g., MinGW / GCC) installed



🎯 Key Features
   - Integrated Code Editor
   - Compile & Run Code Instantly
   - Built-in Concept Learning System
   - Syntax Highlighting
   - Structured Code Snippets
   - Modular Architecture for Scalability



⚠️ Current Limitation
> CodeViz is built in Python and currently supports **C++ code execution only**.  
> Multi-language support is actively planned and will be introduced in future updates.



🔮 Future Improvements
   - Reintroduce Code Visualizer (Advanced Version)
   - Add multi-language support
   - AI-powered code explanation
   - Smart search across concepts/snippets
   - Cloud sync for user data
   - Beginner learning paths (structured roadmap inside app)



📊 Conclusion

CodeViz is not just another coding tool,
it’s a learning-focused development environment built to:
   - Reduce friction in learning programming
   - Improve productivity
   - Provide a single source of truth for coding + concepts
  Built with the vision to make coding simpler, smarter, and more accessible

🤝 Contribution
Contributions, suggestions, and improvements are welcome!
