# Projects Portfolio

## Technical Profile
As a versatile software engineer I've built a diverse portfolio of personal projects focusing on developer tools, language implementation, and high-performance systems.
My work demonstrates particular strength in creating efficient, user-friendly tools that solve real-world development challenges.

## Technical Skills Demonstrated

### Languages & Frameworks
- **Rust**: Systems programming with advanced patterns:
  - Async programming with tokio and futures
  - Thread management with mpsc channels and oneshot
  - Error handling with anyhow and Result propagation
  - Command-line interfaces with clap
  - Clean architecture with module separation
  - Language Server Protocol implementation
  - Parser development with tree-sitter integration
- **Python**: Developer tooling and language processing:
  - Integration with system APIs and libraries
  - Performance optimization for data processing
  - Concurrent processing with asyncio and threading
  - API design and implementation
  - Full-text search and indexing implementation
- **JavaScript/C++**: Language tooling and parser development:
  - C++ scanner implementation for complex lexical analysis
  - External scanner API integration for advanced parsing features
  - Tree-sitter grammar development in JavaScript
  - DSL implementation for language parsing
- **C#/Unity**: Performance-oriented developer tooling:
  - Advanced scene automation with intelligent analysis and processing
  - DOTS/ECS architecture with automated GameObject-to-Entity conversion pipelines
  - Performance optimization with Job system and Burst compilation
  - Meticulous IL instruction/code path analysis for optimal SIMD utilization
  - Unity editor tool development with intuitive UI/UX design
  - Diagnostic engine frameworks with automated issue detection and resolution
  - Scene streaming optimization with subscene management

### Performance Engineering
- Parallel processing and multi-threading optimization
- Memory management and allocation strategies
- Data structure optimization for minimal overhead
- Cache-aware algorithms and data layout
- CPU/GPU bottleneck identification and resolution
- Profiling and performance metrics analysis

### Developer Tools Engineering
- Command-line interface design with user experience focus
- Language server implementation and parsing techniques
- Incremental parser development for code analysis
- Cross-platform tool development and distribution
- Configuration management for flexible deployment
- Automated testing and verification systems

### Software Architecture
- Modular design with clear separation of concerns
- Performance-oriented system design
- Data-oriented design principles
- Scalable architecture patterns for large codebases
- Component-based design with well-defined interfaces
- Asynchronous processing patterns
- Plugin-based systems for extensibility
- Cross-platform compatibility considerations

### AI/ML Integration
- Vector embeddings for semantic search and retrieval
- Computer vision and object detection models
- Speech recognition and processing

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

---
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

---
### [Tree-Sitter-Cyber](https://github.com/instance-id/tree-sitter-cyber) (Rust/C++/JavaScript)
**Custom Parser for the Cyber Language**

- Developed a complete Tree-sitter grammar for the Cyber scripting language
- Created syntax highlighting queries for advanced code visualization
- Implemented complex parsing rules to handle the language's unique syntax
- Built support for editor integration across multiple platforms
- Implemented a custom C++ scanner for handling complex language features

**Technical Highlights:**
- Created precise grammar definitions in JavaScript using Tree-sitter's DSL
- Implemented custom precedence rules for complex expression parsing
- Generated optimized Rust parser code from Tree-sitter grammar
- Developed custom highlighting queries for semantic tokens
- Built cross-platform compatibility with WASM compilation support
- **Custom C++ Scanner Implementation:**
  - Created a sophisticated lexer using Tree-sitter's external scanner API
  - Implemented proper indentation-based scoping with indent/dedent token generation
  - Developed robust string literal handling for single, double, and triple quotes
  - Built support for multiline strings with appropriate delimiter tracking
  - Implemented a delimiter stack system for proper nesting and context tracking
  - Added debug facilities for development and troubleshooting
  - Utilized modern C++ features for memory safety and performance

---
### [ProStream](https://github.com/instance-id/ProStream) (Unity/C# WIP Asset)
**Advanced Unity Developer Tool for Scene Conversion and Streaming**

- Created a comprehensive developer tool that automates the conversion of traditional GameObject scenes to DOTS entity subscenes
- Developed a rule-based engine that intelligently analyzes scene structures and automatically creates optimized streaming layers
- Designed an intuitive editor interface that simplifies the complex process of setting up scene streaming with minimal manual configuration
- Built an automated system that handles GameObject-to-Entity conversion, subscene creation, and streaming setup through a guided workflow
- Implemented extensive documentation with step-by-step guides to help developers integrate advanced streaming capabilities into their projects

**Technical Highlights:**
- **Scene Automation & Processing:**
  - Created an intelligent scene analysis system that identifies optimal streaming boundaries based on object density and relationships
  - Built automatic layer generation that organizes GameObjects into logical streaming groups based on customizable rule sets
  - Implemented a GameObject-to-Entity conversion pipeline with automatic hierarchy preservation and reference maintenance
  - Developed a subscene creation system that handles all the complexity of breaking apart monolithic scenes into efficient streaming units

- **Performance Optimization Tools:**
  - Designed automated frustum culling integration using Unity's job system with Burst compilation for scenes processed by the tool
  - Created a configurable terrain LOD generation system that developers can customize based on their performance requirements
  - Implemented performance metrics tracking with Unity's ProfilerRecorder API to help developers optimize their converted scenes
  - Built bounds checking and occlusion systems that are automatically configured during the conversion process

- **Developer Experience:**
  - Crafted an intuitive Unity editor integration with wizard-style guidance for the conversion workflow
  - Built visual feedback systems showing streaming boundaries and performance impact analysis
  - Implemented serialized configuration settings allowing developers to save and reuse conversion parameters across projects
  - Created automated validation systems to ensure converted scenes will perform well in production

- **Diagnostics & Troubleshooting:**
  - Implemented a comprehensive diagnostic engine framework that helps developers identify and fix issues in their Unity projects
  - Created specialized diagnostic tools including mesh validation, shader compatibility checking, and DOTS compatibility validation
  - Built a unified UI with shortcut support (Alt+Shift+H) providing centralized access to all diagnostic tools
  - Designed the system with an extensible architecture allowing developers to create custom diagnostic tools
  - Developed intelligent issue detection with automated fix suggestions and one-click repair options
  - Incorporated asynchronous search capabilities using Unity's SearchService for performant project-wide scanning
  - Implemented robust error reporting with detailed contextual information for resolving conversion issues

---
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


---
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

---
### [Voice Assistant](https://github.com/instance-id/voice_assistant) (C/Python/TS/JS)
**Voice Command Processing System**
- Developed a distributed voice assistant system with components running on both edge devices (ESP32 Korvo 1) and server infrastructure
- Implemented wake-word detection, voice command recognition, and natural language processing through a sophisticated pipeline
- Created a hybrid processing system with on-device recognition for common commands and server-side processing for complex queries
- Built integration with Home Assistant for comprehensive smart home control
- Designed with both privacy and performance in mind through edge processing preferences

**Technical Highlights:**
- **Embedded Development:**
  - ESP-IDF (Espressif IoT Development Framework) with C/C++ firmware implementation
  - ESP Audio Front End (AFE) for audio processing
  - ESP Speech Commands recognition engine for on-device processing
  - Custom event handling for physical button controls and LED feedback

- **Server-side Technologies:**
  - Python with gRPC for efficient bidirectional streaming
  - Faster-Whisper for state-of-the-art speech recognition
  - Docker containerization for simplified deployment
  - EMQX MQTT broker for reliable message distribution
  - Websocket communication with Home Assistant for command execution

- **Advanced Architecture:**
  - Dual-path command processing for minimal latency with fallback capabilities
  - Streaming audio processing that starts upon wake word detection
  - Cancelable transcription when on-device matches are found
  - Command list generation and synchronization between server and edge device

---
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

---
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

---
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

---https://github.com/instance-id/instance-id/blob/main/personal_project_portfolio.md
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



