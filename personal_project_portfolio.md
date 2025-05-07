# Personal Projects Portfolio

## Technical Profile
As a versatile software engineer with expertise at the intersection of Rust and Python, I've built a diverse portfolio of personal projects focusing on developer tools, language implementation, and high-performance systems.  
My work demonstrates particular strength in creating efficient, user-friendly tools that solve real-world development challenges.

## Featured Projects

### [Vectorizer](https://github.com/instance-id/vectorizer) (Rust)
**Text Embedding Generator and Vector Database Integration**

- Built a high-performance text embedding tool in Rust that processes project files for AI retrieval
- Implemented integration with Qdrant vector database for storage and retrieval of embeddings
- Created a configuration system supporting both global and per-project settings
- Developed Neovim integration for automatic embedding of saved files
- Used the All-MiniLm-L(6/12)-V2 models for generating high-quality text embeddings

**Technical Highlights:**
- Implemented async processing with Tokio and thread management for optimal performance
- Designed a robust CLI with clap that follows modern design patterns similar to Ruff and uv
- Used mpsc channels and oneshot patterns for efficient inter-thread communication
- Implemented sophisticated error handling with anyhow and custom error propagation
- Created command-line progress indicators with automatic refresh for better UX

### [Cyber Language Server](https://github.com/instance-id/cyber-language-server) (Rust)
**LSP Implementation for the Cyber Language**

- Developed a full Language Server Protocol implementation in Rust
- Created advanced language features including completions, diagnostics, and hover information
- Implemented document parsing and syntax validation
- Built with an extensible architecture for future language features

**Technical Highlights:**
- Used tower-lsp for async LSP communication with high performance
- Leveraged tree-sitter for incremental parsing and efficient syntax analysis
- Implemented concurrent document processing with Tokio and DashMap
- Designed thorough error handling with anyhow and custom error types
- Built with tracing for comprehensive logging and diagnostics

### [Tree-Sitter-Cyber](https://github.com/instance-id/tree-sitter-cyber) (Rust/JavaScript)
**Custom Parser for the Cyber Language**

- Developed a complete Tree-sitter grammar for the Cyber scripting language
- Created syntax highlighting queries for advanced code visualization
- Implemented complex parsing rules to handle the language's unique syntax
- Built support for editor integration across multiple platforms

**Technical Highlights:**
- Created precise grammar definitions in JavaScript using Tree-sitter's DSL
- Implemented custom precedence rules for complex expression parsing
- Generated optimized Rust parser code from Tree-sitter grammar
- Developed custom highlighting queries for semantic tokens
- Built cross-platform compatibility with WASM compilation support

### [NCM-RS](https://github.com/instance-id/ncm-rs) (Rust)
**Neovim Configuration Manager**

- Built a Rust-based tool for managing multiple Neovim configurations
- Implemented symlink-based configuration switching with automatic backups
- Created a command-line interface for easy management of configurations
- Developed cross-platform compatibility for Linux and Windows

**Technical Highlights:**
- Designed a modular architecture with clear separation of concerns
- Implemented advanced configuration management with lazy_static and RwLock
- Created cross-platform abstractions for file paths using custom environment variable detection
- Leveraged clap for parser-based CLI design similar to modern Rust CLI tools
- Implemented comprehensive error handling with anyhow and Result propagation
- Followed best practices for command-line documentation and help text

### [NotifyDB](https://github.com/instance-id/notifydb) (Rust)
**Linux Notification Database and Manager**

- Created a Rust-based D-Bus notification store that captures and archives system notifications
- Developed a Flutter GUI frontend for viewing, filtering, and searching stored notifications
- Implemented real-time notification capturing with automatic database storage
- Built to solve a practical problem with incomplete notification information in Pop_OS

**Technical Highlights:**
- Native Rust implementation with D-Bus system integration
- SQLite database for efficient storage and retrieval
- Multi-threaded architecture handling both UI and background notification monitoring
- Cross-platform Flutter UI with responsive design

### [Voice Assistant](https://github.com/instance-id/voice_assistant)
**Voice Command Processing System**
- Developed a system for receiving and processing voice commands
- Integrated with speech recognition technologies for accurate transcription
- Created action handlers to respond to specific voice triggers
- Built a modular system extensible for various home automation needs

**Technical Highlights:**
- Low-latency audio processing pipeline
- Whisper integration for high-quality speech recognition
- Extensible plugin architecture for custom commands
- Cross-platform compatibility for various operating systems

### [Searcher](https://github.com/instance-id/Searcher) (Python)
**Houdini Asset Search Tool**

- Developed a specialized search tool for Houdini, enabling efficient content discovery
- Implemented full-text search capabilities for finding assets across large libraries
- Built with compatibility across multiple Houdini versions (18.0-20.0)
- Created advanced indexing system for fast query responses

**Technical Highlights:**
- SQLite FTS5 (Full-Text Search) integration for powerful search capabilities
- Cross-platform implementation for Windows, Linux, and macOS
- Custom Python Panel UI integration for seamless Houdini embedding
- Optimized for performance with large asset libraries

### [Verifier](https://github.com/instance-id/verifier) (Python)
**Asset Verification System**

- Developed a comprehensive verification system that integrates with Discord to validate legitimate asset purchases
- Created multi-asset verification with role-based permission management
- Implemented database storage for verified purchases to prevent invoice sharing
- Built Discord bot commands for self-service verification and administration

**Technical Highlights:**
- OAuth2 integration for secure authentication
- Multi-database support (SQLite, MySQL, MS SQL)
- Discord API integration with permission management
- Extensible design for adding new verification features

### [Camera Overlay System](https://github.com/instance-id/tracking_overlay) (Python)
**Advanced Visual Interface for Camera Feeds**

- Created a customizable video feed overlay system with high-tech visual interface
- Implemented dynamic grid overlay with motion detection highlighting
- Developed head tracking with animated reticle display
- Built person identification display panels for recognized individuals
- Added support for external motion detection data sources including ONVIF and ML models

**Technical Highlights:**
- GPU acceleration support for AMD, NVIDIA, and Jetson hardware
- Configurable through both command line and YAML configuration files
- Docker support for various hardware platforms
- Real-time video processing with optimized performance

### Computer Vision Projects
**Object Detection and Vision Processing Tools**

- Developed multiple computer vision applications focusing on real-time object detection
- Created systems for visual verification using computer vision techniques
- Built tools for analyzing and processing visual data with machine learning models
- Implemented cross-platform solutions that work on various hardware configurations

**Technical Highlights:**
- Integration with popular ML frameworks for vision processing
- Hardware acceleration for optimal performance
- Cross-platform compatibility and deployment options
- Practical applications solving real-world detection challenges

### ProStream (Unity/C# WIP Asset)
**Advanced Scene Streaming System for Unity**

- Developed a sophisticated scene management solution that dynamically loads and unloads Unity scenes based on proximity
- Created an intuitive editor interface for configuring streaming distances and layer persistence
- Implemented a rule-based engine for matching and configuring scene components
- Designed a modular architecture with separate engines for operations, modifications, and rules
- Built comprehensive documentation with detailed workflows and setup guides

**Technical Highlights:**
- Custom Unity editor integration with intuitive UI
- Distance-based loading optimization system
- Persistent layer management for critical scene components
- Integration with Unity's prefab system for optimal scene organization

## Technical Skills Demonstrated

### Languages & Frameworks
- **Rust**: Systems programming with advanced patterns:
  - Async programming with tokio and futures
  - Thread management with mpsc channels and oneshot
  - Error handling with anyhow and Result propagation
  - Command-line interfaces with clap
  - Thread-safe global state with RwLock and lazy_static
  - Clean architecture with module separation
  - Language Server Protocol implementation using tower-lsp
  - Parser development with tree-sitter integration
- **Python**: Developer tooling and language processing:
  - Full-text search and indexing implementation
  - Integration with system APIs and libraries
  - Performance optimization for data processing
  - API design and implementation
- **JavaScript**: Language tooling and parser development:
  - Tree-sitter grammar development
  - DSL implementation for language parsing
- **C#/Unity**: Game development and interactive applications

### Developer Tools Engineering
- Command-line interface design with user experience focus
- Language implementation and parsing techniques
- Incremental parser development for code analysis
- Cross-platform tool development and distribution
- Configuration management for flexible deployment

### Software Architecture
- Modular design with clear separation of concerns
- Asynchronous processing patterns
- Plugin-based systems for extensibility
- Cross-platform compatibility considerations

### AI/ML Integration
- Vector embeddings for semantic search and retrieval
- Computer vision and object detection models
- Speech recognition and processing
- Integration of ML models into production applications
