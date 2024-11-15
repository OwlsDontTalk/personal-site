# personal-site# Personal Website

Welcome to my personal website.
This is an [MIT licensed](https://github.com/mldangelo/personal-site/blob/main/LICENSE) React-based application.
It offers a simple interface, easy modifications, static export capabilities, and free automatic deployments
via [GitHub Pages](https://pages.github.com/).

## 🚀 Features

- Built with modern JavaScript, using tools and frameworks
  like [create-react-app](https://github.com/facebook/create-react-app), [React-Router](https://reactrouter.com/), and
  SCSS.
- Automated workflows via [GitHub Actions](https://github.com/features/actions).
- And more!

## 🔧 Dependencies

Ensure you have [node](https://nodejs.org/) >= v16. Optionally,
use [nvm](https://github.com/nvm-sh/nvm#installing-and-updating) to manage node versions.

## 🚀 Setup and Running

1. Clone the repository:
   ```bash
   git clone git://github.com/owlsdonttalk/personal-site.git
   cd personal-site
   ```
2. (Optional) Ensure you're on Node v16 or higher:
   ```bash
   nvm install
   node --version
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the application:
   ```bash
   npm start
   ```

By default, the application should be available at [http://localhost:3000/](http://localhost:3000/).

## 🚢 Deploying

### Deploying to GitHub Pages

1. Update the environment variables and Git remote URL
   in [`.github/workflows/github-pages.yml`](.github/workflows/github-pages.yml).
2. Adjust the `homepage` value in `package.json` based on your hosting preferences.
3. Planning on using a custom domain? Update `public/CNAME`. Otherwise, remove it.
   After making a commit to `main`, simply push your changes, and the deployment will be handled automatically.

## 🙌 Acknowledgements

- Idea & Inspiration [Personal Website](https://github.com/mldangelo/personal-site)
  by [@mldangelo](https://github.com/mldangelo) .
- Initial template from [Future Imperfect](https://html5up.net/future-imperfect) by [@ajlkn](https://github.com/ajlkn)
  for [HTML5 UP](html5up.net).