# Video Novel Engine (VNE)

![VNE Logo](https://raw.githubusercontent.com/ArtoriasphereOrg/VNE---Video-novel-engine/refs/heads/main/Untitled%20design.png)

[![Netlify Status](https://api.netlify.com/api/v1/badges/c887f232-1e10-4eab-b9c6-ece5ed058464/deploy-status)](https://app.netlify.com/projects/videonovelengine/deploys)

## About the Project

The **Video Novel Engine (VNE)** is an innovative web-based tool that empowers creators to build interactive video novels. With VNE, you can craft engaging, multimedia storytelling experiences by combining videos with interactive choices, subtitles, and audio effects. Whether you're a game developer, storyteller, or multimedia enthusiast, VNE makes it easy to create dynamic narratives that captivate your audience.

### Key Features
- **Load Videos**: Import videos from CORS-supported URLs to serve as the foundation of your story.
- **Select Key Frames**: Mark specific moments in the video to add interactivity, such as decision points.
- **Add Interactive Elements**: Include choice buttons (up to 3 per frame), subtitles, and audio (e.g., background music or sound effects).
- **Customize Buttons**: Style choice buttons with custom colors, sizes, and positions.
- **Preview & Test**: Preview your video novel in real-time to ensure choices and elements work as intended.
- **Export Projects**: Save your project as a `.vne` file, packaged as a ZIP for easy sharing or later use.
- **Remove Frames**: Easily delete frames or choices to refine your project.

### How It Works
1. Load a video by entering a valid URL.
2. Navigate to key moments and mark them as frames.
3. Add choices, subtitles, or audio to each frame.
4. Preview the interactive video novel to test functionality.
5. Export your project as a `.vne` file or share it with others.

Check out the [Tutorial & Preview](https://artoriasphereorg.github.io/VNE---Video-novel-engine/Tutorial/index.html) page to see VNE in action and learn how to use it!

## Getting Started

To explore VNE, visit the live demo hosted on Netlify or clone this repository to run it locally.

- **Live Demo**: [Video Novel Engine](https://videonovelengine.netlify.app/) (replace with your actual Netlify URL if different)
- **Tutorial**: Learn how to create your first video novel [here](https://artoriasphereorg.github.io/VNE---Video-novel-engine/Tutorial/index.html).
- **Clone the Repository**:
  ```bash
  git clone https://github.com/ArtoriasphereOrg/VNE---Video-novel-engine.git
  ```
- **Run Locally**:
  1. Install a local server (e.g., `http-server` via npm or Python’s `http.server`).
  2. Serve the project directory and open `index.html` in your browser.

## Technologies Used
- **HTML5 & JavaScript**: For the core functionality and interactivity.
- **Tailwind CSS**: For responsive and modern styling.
- **JSZip**: For handling `.vne` file exports.
- **XML Parsing**: For processing `.vne` files to create previews.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m "Add your feature"`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a Pull Request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
Created by [ArtoriasphereOrg](https://github.com/ArtoriasphereOrg). For questions or feedback, open an issue or reach out via GitHub.
