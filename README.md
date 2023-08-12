# VisionAI - Enhancing Web Accessibility for the Visually Impaired

VisionAI is a Python-based program that leverages artificial intelligence and voice technologies to enhance web accessibility for individuals with visual impairments. The program transforms web content into audio output and enables voice interaction with web pages, providing a more inclusive and interactive web browsing experience.

![VisionAI Demo](demo_screenshot.png)

## Features

- **Text-to-Audio Conversion:** Converts web content into audio output using synthetic voices.
- **Voice Interaction:** Allows users to interact with web pages using voice commands.
- **Image Analysis:** Utilizes GPT-4 for analyzing images and providing audio descriptions.
- **Natural Language Processing:** Processes voice inputs using GPT-4 for accurate interaction.
- **Voice Input Recognition:** Employs OpenAI Whisper for speech recognition and transcription.
- **Web Task Handling:** Performs various web tasks, including searching, browsing, reading, and form filling.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/visionai.git
   cd visionai
   ```

2. Install dependencies:

   ```bash
   pip install -e .
   ```

3. Set up your API keys:
   - Obtain API keys for GPT-4 and OpenAI Whisper.
   - Configure the keys in `config.ini` file.

## Usage

1. Launch the VisionAI program:

   ```bash
   visionai
   ```

2. Follow the voice prompts to navigate web pages, issue commands, and interact with content.

## Configuration

- Edit `config.ini` to set API keys and other configuration parameters.

## Contributing

Contributions are welcome! If you have improvements or new features to propose, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-new-feature`.
3. Commit your changes: `git commit -m 'Add new feature'`.
4. Push the branch: `git push origin feature-new-feature`.
5. Open a pull request.
