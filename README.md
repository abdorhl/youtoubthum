# Next.js Thumbnail Project

This repository contains a Next.js project focused on generating and displaying thumbnails. Thumbnails are small, scaled-down versions of images that provide a quick preview of the original content. This project is a simple example of how you can use Next.js to efficiently generate and serve thumbnails for your images.

## Getting Started

Follow these instructions to get the project up and running on your local machine.

### Prerequisites

- Node.js (v14 or higher)
- npm (Node Package Manager) or yarn

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/abdorhl/youtoubthum.git
   ```

2. Navigate to the project directory:

   ```bash
   cd nextjs-thumbnail-project
   ```

3. Install the dependencies:

   If you're using npm:

   ```bash
   npm install
   ```

   If you're using yarn:

   ```bash
   yarn install
   ```

### Usage

1. Place your original images in the `public/images` directory.

2. Run the development server:

   If you're using npm:

   ```bash
   npm run dev
   ```

   If you're using yarn:

   ```bash
   yarn dev
   ```

3. Open your web browser and go to `http://localhost:3000` to see the application in action.

### Configuration

You can customize the thumbnail generation settings by modifying the `utils/thumbnailGenerator.js` file. Adjust parameters such as thumbnail size, quality, and any additional processing.

## Project Structure

```plaintext
nextjs-thumbnail-project/
├── public/
│   ├── images/                  # Place your original images here
├── utils/
│   ├── thumbnailGenerator.js    # Thumbnail generation logic
├── pages/
│   ├── index.js                 # Main page displaying thumbnails
├── components/
│   ├── Thumbnail.js             # Thumbnail component
├── styles/
│   ├── GlobalStyles.js          # Global styles
├── README.md                    # Project README (you are here)
├── package.json                 # Node.js dependencies and scripts
└── .gitignore                   # Git ignore configuration
```

## Contributing

Contributions to this project are welcome! If you find any issues or have ideas for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Happy thumbnailing! If you have any questions or need further assistance, don't hesitate to reach out.
