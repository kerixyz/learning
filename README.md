# Interactive Learning Guides

A collection of professional, interactive documentation-style websites for learning about AI technologies, available in multiple formats.

## 📚 Available Guides

### 1. **LLM & Transformers Guide** (`index.html`)
Learn about Large Language Models, Generative AI, and Transformer architectures with interactive demos and comprehensive documentation.

### 2. **MCP & Agentkits Primer** (`mcp.html`)
A comprehensive guide to the Model Context Protocol and building AI agents, covering architecture, tools, and real-world implementations.

### 3. **Presentation Mode** (`slides.html`)
Both guides available in a beautiful slide presentation format, perfect for learning or presenting. Switch between LLM and MCP topics on the fly.

Built with clean, modern interfaces featuring sidebar navigation, smooth transitions, and an optimal learning experience.

## Features

### Common Features (All Versions)

- **Version Switcher** - Easily switch between LLM, MCP, and Slides versions
- **Smooth Transitions** - Beautiful fade animations between sections
- **Progress Tracking** - Visual indicator showing completion percentage
- **Keyboard Navigation** - Use arrow keys to navigate between pages
- **Mobile Responsive** - Optimized for all device sizes
- **Professional Design** - Clean, modern aesthetic inspired by GitBook/VuePress
- **No Dependencies** - Everything works offline!

### Documentation Mode (`index.html`, `mcp.html`)

- **Left Sidebar Navigation** - Organized chapters with instant navigation
- **Breadcrumb Navigation** - Always know where you are
- **Previous/Next Buttons** - Easy chapter-by-chapter progression
- **Interactive Elements** - Live demos, calculators, and visualizations

### Presentation Mode (`slides.html`)

- **Full-Screen Slides** - Distraction-free presentation format
- **Topic Switcher** - Choose between LLM and MCP content
- **Slide Counter** - Always know your progress
- **Keyboard Shortcuts** - Arrow keys, Home, End navigation
- **Click Navigation** - Navigate with on-screen buttons

### LLM & Transformers Guide Topics

1. **Introduction to LLMs** - Understand what large language models are and their key characteristics
2. **Transformer Architecture** - Explore the revolutionary architecture with an interactive flow diagram
3. **Attention Mechanism** - Interactive demo showing how attention works in transformers
4. **Pre-training (Phase 1)** - Deep dive into foundation learning with interactive simulations
5. **Post-training (Phase 2)** - Comprehensive guide to RLHF, SFT, and alignment
6. **Key Concepts** - Essential concepts like tokens, embeddings, context windows, and sampling
7. **Popular Models** - Overview of major LLM families (GPT, Claude, LLaMA, BERT, etc.)
8. **Knowledge Quiz** - Test your understanding with interactive quizzes
9. **Resources** - Curated list of papers, courses, and tools to continue learning

### MCP & Agentkits Primer Topics

1. **Introduction to MCP** - Understanding the Model Context Protocol and its importance
2. **What is MCP?** - Core concepts: Resources, Tools, and Prompts
3. **Architecture** - System architecture and communication flow
4. **Protocol Basics** - JSON-RPC foundation and message types
5. **Core Components** - Building MCP servers and clients
6. **Agentkits & Frameworks** - Popular frameworks like Claude SDK, LangChain, AutoGen
7. **Building with MCP** - Step-by-step guide to creating your first server
8. **Popular Tools** - Official and community MCP servers
9. **Example Implementations** - Real-world use cases and workflows
10. **Resources** - Documentation, SDKs, and learning path

### Interactive Elements

- **Progress Tracker**: Automatically tracks which sections you've explored
- **Scale Calculator**: Visualizes the massive scale of LLMs
- **Transformer Layer Explorer**: Click each layer to learn how data flows through transformers
- **Attention Visualizer**: Click words to see attention patterns
- **Tokenization Demo**: Enter your own text to see how it gets tokenized
- **Pre-training Simulator**: Watch a model learn to predict tokens through training iterations
- **Cost Breakdown Calculator**: See the real computational costs of training GPT-3
- **Reward Modeling Demo**: Interactive example showing how human feedback guides training
- **Training Comparison Table**: Side-by-side comparison of pre-training vs post-training
- **Interactive Quiz**: Test your knowledge with immediate feedback

## How to Use

### Option 1: Deploy to Vercel (Recommended)

The easiest way to share this learning page is to deploy it on Vercel for free:

#### Using Vercel CLI:

```bash
# Install Vercel CLI (first time only)
npm install -g vercel

# Deploy from the project directory
vercel

# Follow the prompts - just press Enter to accept defaults
# Vercel will provide you with a live URL
```

#### Using Vercel Dashboard:

1. Visit [vercel.com](https://vercel.com) and sign up/login
2. Click "Add New Project"
3. Import your Git repository
4. Vercel will auto-detect the static site and deploy it
5. Get your live URL instantly!

**No configuration needed!** The `vercel.json` file is already set up.

### Option 2: Open Locally

Simply open `index.html` in any modern web browser:

```bash
# On Linux/Mac
open index.html

# On Windows
start index.html

# Or just double-click the file in your file explorer
```

### Option 3: Serve with a Local Server

For the best local experience, serve the page with a local web server:

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js (if you have http-server installed)
npx http-server

# PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## What You'll Learn

### From the LLM Guide:
- How Large Language Models work at a fundamental level
- The Transformer architecture and why it's revolutionary
- The attention mechanism and its importance
- How LLMs are trained (pre-training, fine-tuning, RLHF)
- Key concepts: tokens, embeddings, context windows, temperature
- Overview of popular LLM families and their characteristics

### From the MCP Guide:
- What the Model Context Protocol is and why it matters
- How to build AI agents that can use tools and access data
- MCP architecture and core components (Resources, Tools, Prompts)
- Popular agentkits and frameworks (Claude SDK, LangChain, AutoGen)
- Building your own MCP servers
- Real-world agent implementations and workflows

## Topics Covered

### LLM & Transformers

**Fundamentals**
- Large Language Models basics
- Transformer architecture
- Attention mechanism (self-attention, multi-head attention, cross-attention)
- Embeddings and vector representations

**Pre-training (Phase 1)**
- Next-token prediction and autoregressive modeling
- Unsupervised learning from massive datasets
- Training data sources (web crawls, books, code, papers)
- Scale: billions to trillions of tokens
- Computational requirements and costs
- What models learn: grammar, knowledge, reasoning, common sense

**Post-training (Phase 2)**
- Supervised Fine-Tuning (SFT)
- Reward modeling and human preference learning
- Reinforcement Learning from Human Feedback (RLHF)
- Constitutional AI (CAI)
- Direct Preference Optimization (DPO)
- Fine-tuning techniques: Full, LoRA, Prompt Tuning, Instruction Tuning
- Safety and alignment challenges

**Practical Concepts**
- Tokenization and token limits
- Context windows
- Parameters and model scale
- Temperature and sampling strategies
- Generation strategies

### MCP & Agentkits

**Protocol Fundamentals**
- JSON-RPC 2.0 foundation
- Message types (requests, responses, notifications)
- Connection lifecycle
- Security and authentication

**Core Components**
- Resources (data and content access)
- Tools (function calling and actions)
- Prompts (reusable templates)
- MCP servers and clients

**Building Agents**
- Creating MCP servers (TypeScript/Python)
- Implementing tools and resources
- Testing with MCP Inspector
- Integrating with Claude Desktop

**Agent Frameworks**
- Claude Agent SDK
- LangChain integration
- AutoGen multi-agent systems
- CrewAI role-based agents

**Real-World Applications**
- Code review assistants
- Research and documentation tools
- DevOps automation
- Customer support bots
- Content management systems

## Technologies Used

- **HTML5**: Structure and content
- **CSS3**: Modern styling with gradients, animations, and responsive design
- **JavaScript**: Interactive features and demos
- **No external dependencies**: Everything works offline!

## Browser Compatibility

Works best on modern browsers:
- Chrome/Edge (v90+)
- Firefox (v88+)
- Safari (v14+)

## Which Version Should I Use?

### 📚 Documentation Mode (`index.html` or `mcp.html`)
**Best for:**
- Deep learning and reference
- Following along with interactive demos
- Tracking your progress through topics
- Having content available while coding

**Features:**
- Sidebar navigation for quick jumping between topics
- Interactive demos and visualizations
- Progress tracking
- Breadcrumb navigation

### 🎯 Presentation Mode (`slides.html`)
**Best for:**
- Presentations and teaching
- Quick overviews and refreshers
- Study sessions
- Sharing concepts with teams

**Features:**
- Full-screen slides
- Switch between LLM and MCP topics
- Clean, distraction-free interface
- Easy keyboard navigation

## Educational Value

These guides are designed to provide:
1. **Visual Learning**: Diagrams and interactive elements make complex concepts easier to understand
2. **Progressive Disclosure**: Start with basics and build up to advanced concepts
3. **Active Learning**: Interactive demos reinforce understanding
4. **Multiple Formats**: Choose the format that works best for your learning style
5. **Comprehensive Coverage**: From basic concepts to advanced topics
6. **Further Resources**: Curated lists of papers, courses, and tools

## Next Steps After Completing These Guides

### After the LLM Guide:
1. Read the foundational papers mentioned in the Resources section
2. Experiment with pre-trained models on Hugging Face
3. Take online courses (Stanford CS224N, Hugging Face NLP Course)
4. Build projects using LLM APIs (OpenAI, Anthropic, etc.)
5. **Continue to the MCP Guide** to learn how to build agents!

### After the MCP Guide:
1. Install Claude Desktop and configure MCP servers
2. Build your first custom MCP server
3. Experiment with different agent frameworks
4. Create an agent for your own workflow
5. Contribute to the MCP community and open source servers

## Contributing

Feel free to enhance these learning guides with:
- More interactive demos and visualizations
- Additional topics and sections
- New MCP server examples
- Updated information about new models and tools
- More quiz questions
- Translations to other languages
- Additional resources and references

## License

This educational resource is free to use and modify for learning purposes.

---

**Happy Learning!** 🚀

Start your journey into the fascinating world of AI:
- 📚 **LLM & Transformers** - Understand how modern AI models work
- 🔌 **MCP & Agentkits** - Build agents that actually do things
- 🎯 **Presentation Mode** - Share knowledge with your team

All three formats are designed to work together and complement each other!
