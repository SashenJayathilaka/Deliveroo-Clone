# Deliveroo Clone with REACT NATIVE!

#### PREREQUISITES:
- Install Node JS in your computer <a href='https://nodejs.org/en/'>HERE</a>

<a href="#facebook"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" alt="Facebook" width="30" height="30" /></a>
<a href="#instagram"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg" alt="Instagram" width="30" height="30" /></a>
<a href="#"><img src="https://user-images.githubusercontent.com/99184393/183095729-0ae04014-a62c-4013-93ff-6861fbff308e.png" alt="" width="30" height="30" /></a>
<a href="#"><img src="https://user-images.githubusercontent.com/99184393/179383376-874f547c-4e6f-4826-850e-706b009e7e2b.png" alt="" width="30" height="30" /></a>
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

### Creating a Build
- Optimize the assets for speed - ``npx expo-optimize`` (formerly expo optimize)
- Bundle the project for production - ``npx expo export:web`` (``expo build:web`` in the legacy Expo CLI).
- Creates a production ready static bundle in the ``web-build/`` directory. Don't edit this folder directly.
- If you make any changes to your project, you'll need to re-build for production.
- For more help use ``npx expo export:web --help``
- <a href="https://docs.expo.dev/eas" target="_blank">More Info</a>

#### 🔴 Open the camera app on your device and scan the code below
<a href="#instagram"><img src="https://drive.google.com/uc?export=download&id=1MYoXnakTDmbp23AwWyChIPmPONP-FpJV" alt="qr" width="200" height="200" /></a>
<a href="#instagram"><img src="https://user-images.githubusercontent.com/99184393/182557606-b36f2540-1260-42bf-b547-ed5832e3615e.png" alt="qr" width="200" height="200" /></a>
<br>
#### Expo Publish
publish your project
```
expo publish
```

 <hr />
<div style="display: inline_block"><br>
 <img align="center" alt="React"  width="180" src="https://user-images.githubusercontent.com/99184393/184466112-3d639a7d-e292-43f1-96ff-0d7506be7d5a.jpg">
  <img align="center" alt="React"  width="180" src="https://user-images.githubusercontent.com/99184393/184466143-c95e743f-eff5-4acf-ad9d-4f33142ca088.jpg">
  <img align="center" alt="React"  width="180" src="https://user-images.githubusercontent.com/99184393/184466211-d27ca927-7a3f-4a36-8920-3d7d62e7ab29.jpg">
    <img align="center" alt="React"  width="180" src="https://user-images.githubusercontent.com/99184393/184466252-59874cd9-bd09-48c5-8122-715d4f386ce3.jpg">
</div>
