<div align="center">
  <img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Project Logo">
  <h1 align="center">Dynamic_og: Automated Open Graph Images Generator</h1>
</div>

<p align="center">
  Streamline your workflow with automated generation and updating of Open Graph images for your web documents.
  <br />
  <a href="https://github.com/empress-eco/dynamic_og"><strong>Explore the Docs »</strong></a>
  <br />
  <br />
  <a href="https://github.com/empress-eco/dynamic_og/issues">Report Bug</a>
  ·
  <a href="https://github.com/empress-eco/dynamic_og/issues/new">Request Feature</a>
</p>

## About The Project

Dynamic_og is an innovative tool designed for developers seeking to automate the creation and updating of Open Graph (OG) images for their web documents. It effortlessly generates OG images based on document changes and attaches the generated image to a particular field in the document, simplifying your workflow and saving you precious time.

### Key Features

- Define DocType-wise templates for generating images
- Preview your template live in the OG Image Template
- Automatically regenerate images on document changes
- Full Inter Font Family support in the image HTML template
- Automatically delete older image files
- Update existing OG images on documents in bulk from OG Template form/API

### Built With

This project is built with Node.js and requires Node >= 16 and Empress Version >= 14.

## Getting Started

### Prerequisites

Ensure you have Empress bench installed on your system.

### Installation

You can install this app on your Empress site by following these steps:

1. Clone the repo
   ```sh
   git clone https://github.com/empress-eco/dynamic_og.git
   ```
2. Install the application on your Empress site:
   ```sh
   bench --site my_site.localhost install-app Empress_dynamic_og
   ```

## Usage

Dynamic_og revolves around the **OG Image Template**. To generate OG images for a given DocType, simply create a new **OG Image Template** document.

## Contributing

We welcome community contributions! Here's how you can contribute:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is under the MIT License. Your contributions are also licensed under the MIT License.

## Acknowledgements

Special thanks to the Empress Community for providing the essential tools that power this project. Their innovation and dedication have been instrumental in building the foundations and functionalities we rely on. We are profoundly grateful for their pioneering work and ongoing support.