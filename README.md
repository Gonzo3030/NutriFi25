# NutriFi25 🥑🏋️‍♀️

<div align="center">
  <img src="https://via.placeholder.com/800x200/4CAF50/FFFFFF/?text=NutriFi25" alt="NutriFi25 Banner" width="100%" />
</div>

## 🚩 Overview

NutriFi25 is an AI fitness and nutrition agent built on the ElizaOS framework. It uses Claude AI to provide personalized fitness guidance, nutritional advice, and wellness recommendations. With the ability to interact via Telegram and post relevant content on Twitter/X, NutriFi25 acts as your personal health companion.

## ✨ Features

- 🥗 Personalized nutrition advice tailored to your goals and preferences
- 🏋️‍♀️ Custom fitness recommendations and workout plans
- 📊 Progress tracking and motivational support
- 🔄 Autonomous content posting on Twitter/X about fitness, nutrition, and wellness
- 💬 Interactive conversations via Telegram
- 📱 Mobile-friendly interface for on-the-go health guidance
- 🧠 Powered by Claude AI for intelligent, contextual recommendations

## 🎯 Use Cases

- 🏃‍♂️ Get personalized workout routines based on your fitness level
- 🍽️ Receive meal planning and nutrition advice tailored to your dietary needs
- 💪 Track progress toward fitness goals with intelligent feedback
- 📖 Learn about the latest research in health and wellness
- 🤔 Ask questions about exercise techniques, nutrition facts, and health topics
- 📅 Set reminders for workouts, meals, and healthy habits

## 🚀 Quick Start

### Prerequisites

- [Python 2.7+](https://www.python.org/downloads/)
- [Node.js 23+](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
- [pnpm](https://pnpm.io/installation)

> **Note for Windows Users:** [WSL 2](https://learn.microsoft.com/en-us/windows/wsl/install-manual) is required.

### Installation

```bash
# Clone the repository
git clone https://github.com/Gonzo3030/NutriFi25.git

# Navigate to the project directory
cd NutriFi25

# Copy the environment file and configure your API keys
cp .env.example .env

# Install dependencies
pnpm i && pnpm build && pnpm start
```

### Configuration

1. Edit the `.env` file with your API credentials:
   - Anthropic API key (for Claude AI)
   - Twitter/X API credentials
   - Telegram Bot Token

2. Configure your agent by editing `agent/src/defaultCharacter.ts`

3. Start the agent:
```bash
pnpm start
```

4. To interact with the agent in a web interface:
```bash
pnpm start:client
```

## 🛠️ System Architecture

NutriFi25 is built on the ElizaOS framework, an AI agent operating system that provides the infrastructure for:
- Natural language processing via Claude AI
- Multi-platform communication (Telegram, Twitter/X)
- Memory and context management
- Action execution and scheduling

The agent is designed to be extensible, allowing for additional functionality through custom plugins and integrations.

## 📊 Roadmap

- [ ] Implement autonomous Twitter content posting
- [ ] Add support for image analysis of food and exercises
- [ ] Integrate with fitness trackers and nutrition apps
- [ ] Develop a mobile app for better user experience
- [ ] Add community features for group fitness challenges
- [ ] Expand language support for international users

## 🤝 Contributing

Contributions are welcome! Feel free to submit pull requests or open issues to help improve NutriFi25.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built on the amazing [ElizaOS](https://github.com/elizaOS/eliza) framework
- Powered by Anthropic's Claude AI
- Inspired by the need for more personalized, accessible fitness and nutrition guidance

---

<div align="center">
  <p>NutriFi25 - Your AI-powered fitness and nutrition companion</p>
</div>