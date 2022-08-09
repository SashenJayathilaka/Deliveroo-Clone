# Deliveroo Clone with REACT NATIVE!

#### PREREQUISITES:
- Install Node JS in your computer <a href='https://nodejs.org/en/'>HERE</a>

<a href="#facebook"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" alt="Facebook" width="30" height="30" /></a>
<a href="#instagram"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg" alt="Instagram" width="30" height="30" /></a>
<a href="#google"><img src="https://raw.githubusercontent.com/atulmy/oauth/master/web/public/images/social/google.svg" alt="Google" width="30" height="30" /></a>
<a href="#google"><img src="https://user-images.githubusercontent.com/99184393/180461713-76c02155-35f5-497e-b3a3-364fec13da39.png" alt="Google" width="30" height="30" /></a>
<a href="#google"><img src="https://user-images.githubusercontent.com/99184393/180462270-ea4a249c-627c-4479-9431-5c3fd25454c4.png" alt="Google" width="30" height="30" /></a>
<a href="#github"><img src="https://user-images.githubusercontent.com/99184393/182531543-22e5cec1-bf41-444c-80b0-c2b7205b99ca.png" alt="GitHub" width="30" height="30" /></a>
<a href="#github"><img src="https://user-images.githubusercontent.com/99184393/182531694-325c7651-c586-4b79-9304-9b7d39fd2a95.png" alt="GitHub" width="30" height="30" /></a>
<a href="#github"><img src="https://user-images.githubusercontent.com/99184393/182531879-62dd069e-d5aa-456c-874e-fb5303a5fa3c.png" alt="GitHub" width="30" height="30" /></a>
<a href="#github"><img src="https://github.githubassets.com/images/modules/logos_page/Octocat.png" alt="GitHub" width="30" height="30" /></a>
<a href="#github"><img src="https://raw.githubusercontent.com/atulmy/oauth/master/web/public/images/tech/github.svg" alt="GitHub" width="30" height="30" /></a>
<a href="#github"><img src="https://assets.stickpng.com/images/580b57fcd9996e24bc43c520.png" alt="GitHub" width="30" height="30" /></a>

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts
 Installing Expo CLI

```
npm install --global expo-cli
```
Initializing the project
```
npx create-expo-app deliveroo-clone 
cd deliveroo-clone
```

 Starting the development server
```
expo start
```
## Setup Tailwind CSS
```
npm install tailwindcss-react-native
npm install --save-dev tailwindcss
```
Tailwindcss requires a ``tailwind.config.js`` file with the content section configured to include the paths to all of your components and any other source files that contain Tailwind class names.
```
// tailwind.config.js
module.exports = {
  content: [
    "./screens/**/*.{js,ts,jsx,tsx}",
    "./pages/**/*.{js,ts,jsx,tsx}",
    "./components/**/*.{js,ts,jsx,tsx}",
  ],
  // ...
};
```
Add ``TailwindProvider`` at the top level of your application. The ``TailwindProvider`` creates the context for reactive styles and the atomic style objects.
```
import { TailwindProvider } from "tailwindcss-react-native";

function MyAppsProviders({ children }) {
  return <TailwindProvider>{children}</TailwindProvider>;
}
```
### Configure your babel.config.js
```
// babel.config.js
module.exports = {
  plugins: ["tailwindcss-react-native/babel"],
};
```
## Using Firebase
Firebase SDK Setup
```
expo install firebase
or
expo install firebase@9.6.11
```
#### Dependencies
```
expo install react-native-screens
```
```
expo install react-native-safe-area-context
```
### Creating a Build
- Optimize the assets for speed - ``npx expo-optimize`` (formerly expo optimize)
- Bundle the project for production - ``npx expo export:web`` (``expo build:web`` in the legacy Expo CLI).
- Creates a production ready static bundle in the ``web-build/`` directory. Don't edit this folder directly.
- If you make any changes to your project, you'll need to re-build for production.
- For more help use ``npx expo export:web --help``
- <a href="https://docs.expo.dev/eas" target="_blank">More Info</a>

#### Expo Publish
publish your project
```
expo publish
```
