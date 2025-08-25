# react-anime-tracker

## Goal
Display top airing anime or upcoming episodes from an API. 

## API
- Jikan API

## MVP
1. Fetch a list of top airing anime.

2. Display:
    - Title
    - Poster/image
    - Score (optional)
    - Airing time/episodes

3. **VERY** Simple search bar (optional extra)

## Tech Stack
- Vite – for fast React project setup
- React + JavaScript – UI & state management
- Axios or fetch API – to get data from Jikan API
- CSS – basic styling with Flexbox/Grid for layout
- Deployment – Vercel (works seamlessly with Vite)

## Folder Structure
```
/src
  /components
    AnimeCard.js
  /pages
    App.js
  /styles
    App.css
```


## Step-by-Step Workflow:
1. Set up React project (Create React App or Vite) ✅
2. Fetch anime data from Jikan API in App.js using useEffect
3. Map over data to display AnimeCard components
4. Style minimally with Flexbox (cards in a grid)
5. ***Optional:** Add search input to filter titles*
6. Deploy on Vercel

## Project Information
- *Project 1/4*
- Started 25th August 2025
