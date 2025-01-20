# React TMDB Client

A React Movies application using [The Movie Database (TMDb)](https://developers.themoviedb.org) API.

## Project Structure

```
react-movies/
├── .husky/                 # Husky config. for Git hooks.
├── public/                 # Static files.
├── src/                    # Source files.
│   ├── assets/             # Assets like images, icons, etc.
│   ├── components/         # React components.
│   ├── config/             # Configuration files.
│   ├── constants/          # Constants and enums.
│   ├── pages/              # Application pages.
│   ├── locales/            # Translations.
│   ├── routes/             # Routes configuration.
│   ├── services/           # Service utilities and API calls.
├── .env.sample             # Sample environment variables.
├── .gitignore              # Git ignore file.
├── package.json            # NPM package configuration.
├── README.md               # Project documentation.
```

## API Integration Overview

### TMDb API

- **Base URL:** `https://api.themoviedb.org/3`
- **Authentication:** API Key (stored in `.env` file)


