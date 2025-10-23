# doXmind Documentation

This is the official documentation site for doXmind, an AI-powered document intelligence platform. The documentation is built with [Mintlify](https://mintlify.com).

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

You need to have Node.js and npm installed on your machine.

- [Node.js](https://nodejs.org/) (18.x or higher)
- [npm](https://www.npmjs.com/get-npm)

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/your_username_/doXmind-Docs.git
   ```
2. Install Mintlify CLI globally
   ```sh
   npm i -g mintlify
   ```

### Running the Application

To run the documentation site in development mode, use the following command:

```sh
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view it in the browser. The page will reload if you make edits.

### Building the Application

To build the documentation for production, use the following command:

```sh
npm run build
```

This will build the documentation site for production to the `.mintlify/dist` folder. It correctly optimizes the build for the best performance.

## Project Structure

- `mint.json`: The main configuration file for Mintlify (navigation, branding, colors).
- `package.json`: Contains the project's metadata and dependencies.
- `introduction.mdx`: The homepage/welcome page.
- `quickstart.mdx`: Quick start guide.
- `development.mdx`: Development guide.
- `api-reference/`: Contains the API documentation.
  - `introduction.mdx`: API documentation landing page.
  - `endpoint/`: Contains API endpoint examples.
- `logo/`: Contains logo assets (dark and light versions).
- `.github/workflows/`: Contains GitHub Actions configuration for automated deployment.

## Editing Documentation

### Editing Existing Pages

Simply edit the `.mdx` files in the root directory or subdirectories. Each MDX file supports:
- Standard Markdown syntax
- React components (Cards, Steps, Tabs, etc.)
- Frontmatter for metadata (title, description)

### Adding New Pages

1. Create a new `.mdx` file in the appropriate directory
2. Add frontmatter at the top:
   ```yaml
   ---
   title: Your Page Title
   description: 'Your page description'
   ---
   ```
3. Update `mint.json` to add the page to navigation

### Customizing Theme

Edit `mint.json` to customize:
- Brand colors and logo
- Navigation structure
- Footer links and social media
- Top navigation bar

## Deployment

This project uses GitHub Actions for automated deployment. When you push to the `main` or `master` branch, the documentation is automatically deployed to Mintlify hosting.

You can also manually deploy using:

```sh
npm run deploy
```

## Available Scripts

- `npm run dev` - Start local development server
- `npm run build` - Build static files for production
- `npm run deploy` - Deploy to Mintlify hosting
- `npm run preview` - Preview the production build locally

## Learn More

- [Mintlify Documentation](https://mintlify.com/docs)
- [MDX Documentation](https://mdxjs.com/)

## Support

For questions and support, please contact [support@doxmind.com](mailto:support@doxmind.com)