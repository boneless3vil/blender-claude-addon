# Blender Claude Addon

Advanced Blender AI assistant add-on that integrates Anthropic's Claude directly into Blender.

## Features

- Ask Claude AI questions directly within Blender
- Capture screenshots and get visual feedback on your Blender scene
- Get contextual help for your Blender projects
- Multiple Claude model options (Opus, Sonnet, Haiku)
- AI Control for manipulating Blender objects with natural language commands
- Demo mode for testing without an API key
- Conversation history with clear formatting
- History management with automatic archiving

## Installation

1. Download the latest release from the [Releases](https://github.com/your-username/blender-claude-addon/releases) page.
2. In Blender, go to Edit > Preferences > Add-ons > Install...
3. Select the downloaded ZIP file.
4. Enable the addon by checking the box next to "3D View: Claude AI Assistant".
5. Configure your Anthropic API key in the addon preferences.

## Configuration

1. After installation, go to the addon preferences.
2. Enter your Anthropic API key.
3. Choose which Claude model to use (Opus, Sonnet, or Haiku).
4. Configure screenshot and history locations if desired.

## Usage

### General Questions
1. Open the Claude panel in the sidebar of the 3D View (N key).
2. Type your question in the input field.
3. Click "Ask Claude" or press Enter.

### Screenshots
1. Click "Screenshot & Ask" to capture your current view and ask a question about it.
2. Claude will respond with insights about your scene.

### AI Control
1. Click "AI Control Blender" to create or modify objects with natural language.
2. Type commands like "create a cube measuring 2x3x4 inches with a metallic material" or "move the cube to 1,2,3".

## Requirements

- Blender 4.0 or newer
- Anthropic API key (sign up at [anthropic.com](https://anthropic.com/))

## Version History

### v1.1.0 
- Added AI Control feature to create and manipulate Blender objects with natural language
- Improved screenshot capture with multiple backup methods for Blender 4.4 compatibility
- Enhanced fallback image generation that always produces valid images
- Fixed API key validation to accept all valid Anthropic key formats
- Multiple context handling improvements for more reliable operation

### v1.0.2
- Improved screenshot capture with multiple backup methods for Blender 4.4 compatibility
- Enhanced fallback image generation that always produces valid images
- Fixed API key validation to accept all valid Anthropic key formats
- Multiple context handling improvements for more reliable operation
- Better error messages and logging for troubleshooting

### v1.0.1
- Cross-platform path handling using os.path instead of hardcoded paths
- Fixed Enter key handling to prevent double-pressing issues
- Enhanced text wrapping for better readability when panel is resized
- Simplified code block highlighting for better reliability

### v1.0.0
- Initial release

## License

This project is licensed under the MIT License - see the LICENSE file for details.
