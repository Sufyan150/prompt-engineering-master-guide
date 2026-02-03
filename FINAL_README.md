# Prompt Engineering Master Guide

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Stars](https://img.shields.io/github/stars/dair-ai/Prompt-Engineering-Guide?style=social)](https://github.com/dair-ai/Prompt-Engineering-Guide)
[![Website](https://img.shields.io/website?url=https%3A%2F%2Fwww.promptingguide.ai&label=Live%20Site)](https://www.promptingguide.ai/)

A comprehensive educational resource for prompt engineering with large language models (LLMs). This repository contains extensive guides, techniques, research papers, and practical applications for effectively interacting with and optimizing language models.

## 🚀 Overview

Prompt engineering is a critical discipline focused on developing and optimizing prompts to efficiently use language models (LMs) for a wide variety of applications and research topics. This guide helps you:

- Understand the capabilities and limitations of large language models (LLMs)
- Master various prompting techniques for different use cases
- Learn about advanced applications and research findings
- Explore tools and resources for prompt optimization

## 📚 Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Core Topics](#core-topics)
- [Techniques Covered](#techniques-covered)
- [Model-Specific Guides](#model-specific-guides)
- [Applications](#applications)
- [Research & Papers](#research--papers)
- [Tools & Resources](#tools--resources)
- [Contributing](#contributing)
- [License](#license)

## Features

- 📖 **Comprehensive Documentation**: Detailed guides covering everything from basic to advanced prompt engineering techniques
- 🌐 **Multi-language Support**: Available in 13+ languages including English, Chinese, Japanese, Spanish, French, German, and more
- 🎯 **Practical Examples**: Real-world examples and use cases with code implementations
- 📊 **Research Integration**: Latest academic papers and research findings in prompt engineering
- ⚡ **Interactive Web Interface**: Built with Next.js and Nextra for an excellent user experience
- 🧠 **Model Coverage**: Specific guidance for ChatGPT, GPT-4, LLaMA, Mistral, Gemini, and other leading models

## Getting Started

### Prerequisites
- Node.js >= 18.0.0
- pnpm package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/dair-ai/Prompt-Engineering-Guide.git
cd Prompt-Engineering-Guide
```

2. Install dependencies:
```bash
pnpm install
# Or if you don't have pnpm:
npm install -g pnpm
```

3. Install required packages:
```bash
pnpm install next react react-dom nextra nextra-theme-docs
```

4. Run the development server:
```bash
pnpm dev
```

5. Visit `http://localhost:3000` to view the guide

### Quick Start

For immediate access without installation, visit the live version at [https://www.promptingguide.ai/](https://www.promptingguide.ai/)

## Core Topics

### 1. Introduction to Prompt Engineering
- Understanding LLM capabilities and limitations
- Basic prompting concepts and terminology
- LLM settings and configuration
- Elements of effective prompts
- General design principles

### 2. Advanced Prompting Techniques
- Zero-shot and few-shot prompting
- Chain-of-thought reasoning
- Tree of Thoughts (ToT)
- Retrieval-Augmented Generation (RAG)
- Self-consistency methods
- Prompt chaining and automation

### 3. Safety and Reliability
- Adversarial prompting awareness
- Bias identification and mitigation
- Factuality and truthfulness considerations
- Risk assessment frameworks

## Techniques Covered

| Technique | Description | Use Case |
|-----------|-------------|----------|
| Zero-Shot Prompting | Direct inference without examples | Simple classification tasks |
| Few-Shot Prompting | Providing examples in the prompt | Complex reasoning tasks |
| Chain-of-Thought | Step-by-step reasoning | Mathematical problems |
| Tree of Thoughts | Structured exploration of solutions | Planning and creative tasks |
| ReAct Prompting | Reasoning + Acting framework | Tool usage and interaction |
| Prompt Chaining | Sequential prompt execution | Multi-step workflows |
| Self-Consistency | Sampling + decoding strategy | Improving reliability |

## Model-Specific Guides

The guide includes detailed documentation for various LLMs:

- **OpenAI Models**: ChatGPT, GPT-4
- **Meta Models**: LLaMA, Code Llama, Mixtral
- **Google Models**: Gemini, Flan
- **Microsoft Models**: Phi-2
- **Other Models**: Mistral 7B, OLMo

Each model guide includes:
- Architecture and capabilities
- Optimal prompting strategies
- Limitations and considerations
- Best practices

## Applications

The repository covers numerous practical applications:

- **Function Calling**: Integrating LLMs with external tools
- **Data Generation**: Creating synthetic datasets for training
- **Code Generation**: Programming assistance and automation
- **Question Answering**: Building QA systems
- **Text Summarization**: Content condensation techniques
- **Creative Writing**: Story generation and content creation
- **Mathematical Reasoning**: Problem-solving approaches

## Research & Papers

Extensive collection of academic papers organized by:

- **Overviews**: Foundational and survey papers
- **Approaches**: Methodological innovations
- **Applications**: Domain-specific implementations
- **Collections**: Curated paper lists

Topics include:
- Instruction tuning
- In-context learning
- Parameter-efficient fine-tuning
- Alignment and safety research
- Emergent abilities in LLMs

## Tools & Resources

### Development Tools
- Prompt optimization utilities
- Testing frameworks
- Evaluation metrics
- Debugging techniques

### Educational Resources
- Interactive notebooks
- Video lectures
- Slide decks
- Hands-on exercises

### Community Resources
- Links to relevant courses
- Discussion forums
- Contributed examples
- Best practice collections

## Contributing

We welcome contributions from the community! Here's how you can help:

### Ways to Contribute
- **Documentation**: Improve existing guides or add new ones
- **Examples**: Share practical use cases and implementations
- **Translations**: Help translate content into new languages
- **Research**: Contribute papers and findings
- **Tools**: Add new utilities and resources

### Contribution Guidelines
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add amazing feature'`)
5. Push to the branch (`git push origin feature/amazing-feature`)
6. Open a Pull Request

Please ensure your code follows the project's style guidelines and includes appropriate tests where applicable.

## Community

Join our community to stay updated and connect with other practitioners:

- [Discord Server](https://discord.gg/YbMT8k6GfX) - Real-time discussions
- [Twitter](https://twitter.com/dair_ai) - Latest updates and announcements
- [YouTube Channel](https://www.youtube.com/channel/UCyna_OxOWL7IEuOwb7WhmxQ) - Educational content
- [Newsletter](https://nlpnews.substack.com/) - Weekly AI and NLP insights

## Courses & Education

Enhance your learning with our structured courses:

- **Introduction to Prompt Engineering**: Fundamental concepts and techniques
- **Advanced Prompt Engineering**: Cutting-edge methods and applications
- **AI Agents**: Building intelligent autonomous systems
- **RAG Systems**: Retrieval-Augmented Generation implementations

Visit [DAIR.AI Academy](https://academy.dair.ai/) for more information.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for details.

## Acknowledgments

- Special thanks to all contributors who have helped build this comprehensive resource
- Sponsored by [SerpAPI](https://serpapi.com/) for supporting our development efforts
- Inspired by the growing community of prompt engineering practitioners

## Citation

If you use this guide in your research or work, please cite us:

```bibtex
@article{Saravia_Prompt_Engineering_Guide_2022,
author = {Saravia, Elvis},
journal = {https://github.com/dair-ai/Prompt-Engineering-Guide},
month = {12},
title = {{Prompt Engineering Guide}},
year = {2022}
}
```

---

⭐ **Star this repository if it helped you with your prompt engineering journey!**

Made with ❤️ by the DAIR.AI community