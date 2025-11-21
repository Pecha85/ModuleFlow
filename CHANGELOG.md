# Changelog

All notable changes to this project will be documented in this file.

---
## [0.0.4] - Bug fixing. Preset manager

### Fixed
- Fixed configuration reload after canceling task editing
- Fixed incorrect formatting of links in the MD service
- Fixes in the Link system
- Fixes in Info 
- Fixes in WebSocketManager code
- Fixes in FileManager code
- Starting preset was removed due to the transition to the Preset Manager
### Added
- Preset Manager
- 3 example presets
- Buttons to confirm task editing in the task bar
- New log events
- Info updates

---
## [0.0.3] - Bug fixing. Discord community is UP!

### Fixed
- Fixed configuration reload after canceling task editing
- Naming mistakes in code
- Bug in preview task transition
- "+" Button position in Chain
- UI fixes

### Added
- Buttons to confirm task editing in the task bar
- Task progress and state color in the task bar
- Prompt chain connected to Log system
- Documentation updates
- UX improvements
- Discord server

---
## [0.0.2] - Bug fixing. Drag&Drop system

### Fixed
- Text display adjustments in UI
- UI module delamination when task preview is enabled and the chain is hidden
- The ability to delete tasks during generation
- Rename "prompt group" → "module presets". Remove "exaples" folder and restart for update
- Task Resource name fixes
- "Wrong JSON" error during config opening

### Added
- Drag&Drop JSON system. Automatically opened modules, chain presses, generative configs and tasks when D&D files to the interface
- Warnings when starting a task without configs and links
- Updates in the "info" section
- Added check for the existence of the task folder before pressing the button
- JSON protection system for config loading
- Warnings with JSON type when open config
- Documentation updates

---
## [0.0.1] - Initial Release

### Added
- Initial version of the application for modular prompt building and generation task management via ComfyUI API.
- **Prompt Chain** — modular prompt chaining system for assembling complex prompts from text and numeric blocks
- **Settings** — visual panel for configuring generation parameters, with support for loading JSON workflows
- **Task Manager** — task queue system with support for creation, execution, and status tracking
- **Output** — information panel showing assembled prompt and iteration index with real-time updates
- **Preview** — result viewer displaying generated images as a responsive grid of cards
- **Log** — application log viewer with automatic saving of runtime messages
- Basic WebSocket integration with the **ComfyUI API**
