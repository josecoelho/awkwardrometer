> **Note from "author"**: This is a human writting now, this is the example of a simple project built using Claude. Including this text! :D The top line was the result of me asking for it to say it has written way too much for a one file project readme. 

Back to the AI generated `README.md`:

> **Note**: This README is a perfect example of how to turn "I made a simple audio gauge that measures awkward silence" into "I BUILT A REVOLUTIONARY SILENCE MONITORING SYSTEM!" The power of technical writing at its finest - where every basic feature sounds like it could solve world hunger. Please read with a grain of salt and enjoy our enthusiasm! 😄

# Awkwardrometer

A web-based tool that visualizes the growing awkwardness of silence using a single gauge. Perfect for those moments when you're not sure if you should say something or just let the silence consume your soul.

## Overview

This project was built entirely through prompts with Claude (Anthropic's AI assistant). It uses browser's audio API to detect sound levels and displays how painfully awkward the silence is becoming using a professional gauge visualization.

## Live Demo

Check out the Awkwardrometer in action: https://josecoelho.github.io/awkwardrometer

## Deployment

This project is hosted using GitHub Pages. To deploy your own version:

1. Fork this repository from https://github.com/josecoelho/awkwardrometer
2. Ensure the main HTML file is named `index.html`
3. Go to your repository's Settings
4. Navigate to Pages section
5. Select "Deploy from a branch" under Source
6. Choose "main" branch and "/ (root)"
7. Click Save and wait for deployment
8. Access your site at `https://[your-username].github.io/awkwardrometer`
## Features

- Single sensitivity level calibrated for optimal awkwardness detection
- Real-time audio monitoring
- Visual color-coded feedback ranging from "this is fine" green to "someone please say something" red
- Progressive status messages that match your internal monologue during silence
- No installation required - runs directly in browser
- Responsive design that works on desktop and mobile devices

## How It Works

The application:
1. Requests microphone access from the browser (promise not to record your awkward moments)
2. Continuously monitors audio levels
3. Updates the gauge in real-time based on sound detection
4. Shows increasingly anxious messages based on silence duration
5. Uses color gradients to indicate awkwardness severity:
   - Green (0-2s): Normal conversation
   - Light Green (2-4s): Slightly uncomfortable
   - Yellow (4-6s): Definitely awkward
   - Orange (6-8s): Very awkward
   - Red (8-10s): Maximum awkwardness achieved

## Technical Details

- Built using:
  - React
  - Gauge.js for visualization
  - Web Audio API for sound detection
  - Pure HTML/CSS/JavaScript
- No build process required
- No external dependencies to install

## Usage

1. Download the HTML file
2. Open it in a modern web browser
3. Allow microphone access when prompted
4. Watch the gauge measure the growing awkwardness in real-time

## Configuration

The application includes a single gauge with:
- Sensitivity level of 35 (calibrated for optimal awkwardness detection)
- 11 increasingly uncomfortable status messages
- Color-coded zones for visual feedback

## Messages Scale

0. "Listening..."
1. "Ok... I'm listening"
2. "Getting silence..."
3. "Quite quiet..."
4. "Very quiet now..."
5. "Is anyone there?"
6. "Hello...?"
7. "This is awkward..."
8. "Should I say something?"
9. "Really awkward now..."
10. "Maximum awkwardness!"

## Development

This project was developed through an iterative conversation with Claude. The development process included:
1. Initial concept of measuring awkward silence
2. Integration of professional gauge visualization
3. Fine-tuning of sensitivity and messages
4. Making it look pretty (because if we're going to measure awkwardness, we might as well do it in style)

## Credits

- Developed through prompts with Claude (Anthropic)
- Uses Gauge.js for visualization
- Web Audio API for audio processing
- Inspired by every awkward silence ever

## License

MIT License - Feel free to use, modify, and distribute as needed. May your awkward silences be well measured.

## Contributing

Feel free to fork, modify, and submit pull requests. Some areas for potential improvement:
- Additional awkward messages
- Different sensitivity presets for various social situations
- Integration with a "conversation starter" API
- Emergency joke generator for peak awkwardness
- Support group finder for chronic awkward silence creators

## Note About Prompts

This entire project was built through conversation with Claude. The prompts focused on:
1. Initial concept of measuring social discomfort
2. Technical implementation details
3. Making the gauge look professional
4. Crafting increasingly uncomfortable status messages
5. Finding the perfect sensitivity level
6. Documentation with a sense of humor

The iterative nature of the conversation allowed for continuous refinement and improvement of the implementation, resulting in this masterpiece of awkwardness measurement.
# Silence Monitor

A web-based tool that visualizes silence duration using multiple audio gauges. Perfect for monitoring awkward silence in conversations, interviews, or any scenario where audio engagement needs to be tracked.

## Overview

This project was built entirely through prompts with Claude (Anthropic's AI assistant). It uses browser's audio API to detect sound levels and displays the duration of silence using professional gauge visualizations.

## Features

- Multiple sensitivity levels to accommodate different environments
- Real-time audio monitoring
- Visual color-coded feedback (green to red)
- Progressive status messages indicating silence duration
- No installation required - runs directly in browser
- Responsive design that works on desktop and mobile devices

## How It Works

The application:
1. Requests microphone access from the browser
2. Continuously monitors audio levels
3. Updates gauges in real-time based on sound detection
4. Shows different messages based on silence duration
5. Uses color gradients to indicate silence severity:
   - Green (0-2s): Normal conversation
   - Light Green (2-4s): Brief pause
   - Yellow (4-6s): Notable silence
   - Orange (6-8s): Extended silence
   - Red (8-10s): Maximum awkwardness

## Technical Details

- Built using:
  - React
  - Gauge.js for visualizations
  - Web Audio API for sound detection
  - Pure HTML/CSS/JavaScript
- No build process required
- No external dependencies to install

## Usage

1. Download the HTML file
2. Open it in a modern web browser
3. Allow microphone access when prompted
4. Watch the gauges respond to silence in real-time

## Configuration

The application includes three gauges with different sensitivity levels:
- High Sensitivity (2): Detects even slight drops in audio
- Medium Sensitivity (5): Balanced detection
- Low Sensitivity (10): Only responds to complete silence

## Customization

You can easily customize:
- Sensitivity levels
- Status messages
- Color schemes
- Number of gauges
- Gauge sizes
- Update frequencies

## Development

This project was developed through an iterative conversation with Claude. The development process included:
1. Initial concept and basic implementation
2. Addition of multiple sensitivity levels
3. Integration of professional gauge visualization
4. Refinement of user interface and messages
5. Performance optimization

## Credits

- Developed through prompts with Claude (Anthropic)
- Uses Gauge.js for visualization
- Web Audio API for audio processing

## License

MIT License - Feel free to use, modify, and distribute as needed.

## Contributing

Feel free to fork, modify, and submit pull requests. Some areas for potential improvement:
- Additional visualization options
- More configuration parameters
- Audio recording capabilities
- Data export features
- Network sync for remote monitoring

## Note About Prompts

This entire project was built through conversation with Claude. The prompts focused on:
1. Initial concept development
2. Technical implementation details
3. User interface design
4. Visual feedback mechanisms
5. Status message crafting
6. Performance optimization
7. Documentation

The iterative nature of the conversation allowed for continuous refinement and improvement of the implementation.
