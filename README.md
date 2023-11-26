# Assignment 1 - ReactJS app.

Name: Yisi Huang

## Overview.

The repository is based on react-movies-lab and add some new features, it contains code of web app assignment 1.

### Features.
 
+ Trending Movies Page
+ Now Playing Page
+ Top Rated TV Page
+ Add Cast List to movies and the page link to movie details page
+ Add sort and filtering: sort by Rating or Latest movies
+ Add Crew List to movies and the page link to movie details page
+ Add search filter to Cast List page: search cast name
+ Add search filter to Crew List page: search crew name
+ Add switch button (responsive UI): sort cast name alphabetically
+ Add People Details Page - link to cast and crew card
+ Add Login, Logout, Register, Reset Page
+ Add Google authentication with firebase
+ Add Pagination to all page
+ Add new MUI components: ManIcon, LocationOnIcon, FaceIcon, WomanIcon

## Setup requirements.

npm install
npm start
npm install firebase react-router-dom react-firebase-hooks

## API endpoints.

+ Trending Movies - /movies/trending
+ Top Rated TV Page - /tv/top_rated
+ Now Playing Page - /movies/now_playing
+ Cast List Page, show cast card of all movies - /movies/:id/cast
+ Crew List Page, show crew card of all movies - /movies/:id/crew
+ Person Page, show person details of all cast and crew - /person/:id
+ Login page - /login
+ Register page - /register
+ Reset page - /reset
+ Dashboard page, it shows log out - /dashboard

## Routing.

+ /movies/trending - displays all trending movies.
+ /tv/top_rated - displays top rated tv.
+ /movies/now_playing - displays all present playing movies.
+ /movies/:id/cast - displays all cast cards of all movies, it links to movie details page.
+ /movies/:id/crew - displays all crew cards of all movies, it links to movie details page.
+ /person/:id - displays cast and crew details, it links to all crew and cast cards.
+ /login - login page, it can login with Google authentication, it can jump to homepage.
+ /register - register page, it can register with Google authentication.
+ /reset - reset password page, it can reset password by send mail.
+ /dashboard - log out page, it can log out and jump to login page.


## Independent learning (If relevant).

I learnt firebase authentication by using Google to register, log in and reset my password using my email. 
https://blog.logrocket.com/user-authentication-firebase-react-apps/
https://console.firebase.google.com

Pagination: https://mui.com/material-ui/react-pagination/#basic-pagination
https://www.bilibili.com/video/BV1ZN4y1R7k6/?spm_id_from=333.337.search-card.all.click&vd_source=b679e3ddda249c7288237677cf182a77

Responsive UI: https://mui.com/material-ui/react-switch/

