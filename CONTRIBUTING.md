# Contributing

Thanks for wanting to help with the Classical Music Themed Escape Room! 🎻

## Finding something to work on

- New to the project? Look for issues labelled [`good first issue`](https://github.com/hannahro15/classical-music-themed-escape-room/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22). They're small, self-contained tasks that are a good place to start.
- Want something bigger? Issues labelled [`help wanted`](https://github.com/hannahro15/classical-music-themed-escape-room/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22help%20wanted%22) are ones I'd especially welcome help with.
- Comment on the issue to say you'd like to work on it, and wait for a reply before you start, so two people don't work on the same thing.
- Found a bug or have an idea that isn't in the [issues](https://github.com/hannahro15/classical-music-themed-escape-room/issues) yet? You're welcome to [open a new issue](https://github.com/hannahro15/classical-music-themed-escape-room/issues/new). Please check the existing issues first so it isn't a duplicate, and wait for a reply before you write any code, so we can agree on the approach.

## Setting up

You'll need [Node.js](https://nodejs.org/) v20.19+ or v22.12+.

1. Fork this repository, then clone your fork:
   ```bash
   git clone https://github.com/<your-username>/classical-music-themed-escape-room.git
   cd classical-music-themed-escape-room
   ```
2. Install the dependencies:
   ```bash
   npm install
   ```
   Please use npm rather than yarn or pnpm, so `package-lock.json` stays the only lockfile.
3. Start the development server:
   ```bash
   npm run dev
   ```
   Then open [http://localhost:5173/classical-music-themed-escape-room/](http://localhost:5173/classical-music-themed-escape-room/) in your browser.

## Making a change

1. Make sure your fork has the latest changes. On your fork's GitHub page, click **Sync fork** → **Update branch**, then pull them down:
   ```bash
   git switch main
   git pull
   ```
2. Create a branch from `main`:
   ```bash
   git switch -c short-description-of-change
   ```
3. Keep each pull request to one issue, and keep it small.
4. If you add or change a puzzle, double-check the music theory (note names, key signatures, clefs) before opening a pull request.
5. Check your change works on a phone-sized screen and using only a keyboard.
6. Write short commit messages in the present tense, for example `Add a footer with the image credit`.
7. Before you open a pull request, make sure both of these pass:
   ```bash
   npm run lint
   npm run build
   ```
8. Open a pull request and write `Closes #<issue number>` in the description. If your change affects how the game looks, add a screenshot.

The game is already deployed at [hannahro15.github.io/classical-music-themed-escape-room](https://hannahro15.github.io/classical-music-themed-escape-room/), so you don't need to deploy anything. I'll publish your changes to the live site after merging. This is a side project, so it may take a few days for me to review your pull request.

## Images, audio and fonts

Please don't add any images, audio clips or fonts to the project without asking first. Open an issue, or comment on the one you're working on, saying what you'd like to add and where it's from, and wait for my approval before including it in a pull request. Pull requests that add these files without approval won't be merged.

Once I've agreed, only add files you have the right to share, and say where they came from in your pull request. Classical pieces are usually public domain, but most recordings of them are not.

Screenshots in your pull request description are fine, because they don't get added to the project.

## Getting help

Stuck? Ask in the issue and I'll help.

## License

By contributing, you agree that your contributions will be licensed under the [MIT License](LICENSE).

## Code of conduct

By taking part, you agree to follow the [code of conduct](CODE_OF_CONDUCT.md).
