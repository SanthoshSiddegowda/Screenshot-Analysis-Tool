# Screenshot Analysis Tool

An Electron-based application that captures screenshots and analyzes them using OpenAI's GPT-4 Vision API.

## Features

- Quick screenshot capture with keyboard shortcuts
- Multi-page screenshot mode
- Real-time AI analysis of screenshots
- Always-on-top overlay window
- Cross-platform support (Windows, macOS, Linux)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/SanthoshSiddegowda/Screenshot-Analysis-Tool.git
   cd screenshot-analysis-tool
   ```

2. Install dependencies:
   ```bash
   yarn install
   # or if you prefer npm
   npm install
   ```

3. Install required packages:
   ```bash
   yarn install
   ```

4. Set up environment variables:
   ```bash
   cp .env.example .env
   ```
   Then edit `.env` and add your OpenAI API key.

5. Start the application:
   ```bash
   yarn electron .
   # or
   npm run electron .
   ```

## Configuration

### Environment Variables

Create a `.env` file in the root directory with the following:
```
OPENAI_API_KEY=your_openai_api_key_here
MODEL=gpt-4o-mini
```

## Security

- Never commit the `.env` file
- Store sensitive API keys securely
- Use `.env.example` for sharing required variable names
- Regularly rotate API keys if compromised

## Troubleshooting

Common issues and solutions:

1. **Screenshots not working**
   - Ensure proper screen capture permissions
   - Check if running with necessary privileges

2. **API errors**
   - Verify API key is correct in `.env`
   - Check OpenAI API status
   - Confirm sufficient API credits

## Contributing

1. Fork the repository
2. Create your feature branch:
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add amazing feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature/amazing-feature
   ```
5. Open a Pull Request

### Code Style

- Use ESLint for JavaScript linting
- Follow existing code formatting
- Add comments for complex logic
- Write meaningful commit messages

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- OpenAI for GPT-4 Vision API
- Electron.js framework
- Screenshot-desktop package

## Support

For support, please:
1. Check existing issues on GitHub
2. Create a new issue with detailed description
3. Include system information and logs
