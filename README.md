# LLM & Transformers Learning Page

An interactive educational web page to learn about Large Language Models, Generative AI, and Transformer architectures.

## Features

### Interactive Learning Sections

1. **Introduction to LLMs** - Understand what large language models are and their key characteristics
2. **Transformer Architecture** - Explore the revolutionary architecture with an interactive flow diagram
3. **Attention Mechanism** - Interactive demo showing how attention works in transformers
4. **Pre-training (Phase 1)** - Deep dive into foundation learning:
   - Next-token prediction objective
   - Training data sources and scale
   - Interactive pre-training simulation
   - Cost breakdown calculator
   - What models learn during pre-training
5. **Post-training (Phase 2)** - Comprehensive guide to alignment:
   - Supervised Fine-Tuning (SFT)
   - Reward modeling with interactive examples
   - RLHF (Reinforcement Learning from Human Feedback)
   - Constitutional AI and DPO
   - Fine-tuning techniques (LoRA, prompt tuning, etc.)
   - Pre-training vs Post-training comparison
6. **Key Concepts** - Essential concepts like tokens, embeddings, context windows, and sampling
7. **Popular Models** - Overview of major LLM families (GPT, Claude, LLaMA, BERT, etc.)
8. **Knowledge Quiz** - Test your understanding with interactive quizzes
9. **Resources** - Curated list of papers, courses, and tools to continue learning

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

- How Large Language Models work at a fundamental level
- The Transformer architecture and why it's revolutionary
- The attention mechanism and its importance
- How LLMs are trained (pre-training, fine-tuning, RLHF)
- Key concepts: tokens, embeddings, context windows, temperature
- Overview of popular LLM families and their characteristics
- Resources to continue your learning journey

## Topics Covered

### Fundamentals
- Large Language Models basics
- Transformer architecture
- Attention mechanism (self-attention, multi-head attention, cross-attention)
- Embeddings and vector representations

### Pre-training (Phase 1)
- Next-token prediction and autoregressive modeling
- Unsupervised learning from massive datasets
- Training data sources (web crawls, books, code, papers)
- Scale: billions to trillions of tokens
- Computational requirements and costs
- What models learn: grammar, knowledge, reasoning, common sense
- Pre-training loss functions

### Post-training (Phase 2)
- Supervised Fine-Tuning (SFT)
- Reward modeling and human preference learning
- Reinforcement Learning from Human Feedback (RLHF)
- Constitutional AI (CAI)
- Direct Preference Optimization (DPO)
- Fine-tuning techniques: Full, LoRA, Prompt Tuning, Instruction Tuning
- Safety and alignment challenges
- Value alignment and bias mitigation

### Practical Concepts
- Tokenization and token limits
- Context windows
- Parameters and model scale
- Temperature and sampling strategies
- Generation strategies

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

## Educational Value

This page is designed to provide:
1. **Visual Learning**: Diagrams and interactive elements make complex concepts easier to understand
2. **Progressive Disclosure**: Start with basics and build up to advanced concepts
3. **Active Learning**: Quizzes and interactive demos reinforce understanding
4. **Comprehensive Coverage**: From basic concepts to advanced topics
5. **Further Resources**: Curated list of papers, courses, and tools

## Next Steps After Completing This Tutorial

1. Read the foundational papers mentioned in the Resources section
2. Experiment with pre-trained models on Hugging Face
3. Take online courses (Stanford CS224N, Hugging Face NLP Course)
4. Build projects using LLM APIs (OpenAI, Anthropic, etc.)
5. Follow AI research communities and stay updated

## Contributing

Feel free to enhance this learning page with:
- More interactive demos
- Additional visualizations
- More quiz questions
- Updated information about new models
- Additional resources and references

## License

This educational resource is free to use and modify for learning purposes.

---

**Happy Learning!** 🚀

Start your journey into the fascinating world of Large Language Models and Generative AI!
