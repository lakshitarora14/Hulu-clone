## HULU Clone Web App

Live Project : https://hulu-clone-1-umber.vercel.app/

![image](https://user-images.githubusercontent.com/44324506/150946214-0b4716cf-88a5-40ba-9f61-a8e263f8e49a.png)

#### Hulu is an American streaming platform. Launched on October 29, 2007, it offers a library of films and television series from networks such as CBS, ABC, NBC, or FX, as well as Hulu original content. Hulu is majority-owned by The Walt Disney Company, with Comcast's NBCUniversal holding a minority stake.

<img src = 'https://user-images.githubusercontent.com/44324506/151646739-4f3e83a1-d791-487c-8bed-78d2cfcc6b56.png' height = 30% width = 50%><img src = 'https://user-images.githubusercontent.com/44324506/151646666-17b5b7a5-e16c-474d-9dfa-cfa7b19d646a.png' height = 70% width = 50%>

![image](https://user-images.githubusercontent.com/44324506/151646754-90641932-5e61-4144-a1ae-561d388ff644.png)



This app is fully responsive website which uses tmdb database to fetch results, made using next.js, react.js, and tailwiwnd css.
The layout changes as the screen sizes increases from 1 column grid in movile device to 2 column grid on tablets, then to 3 column grid on desktops. The layout changes from grid to flex if we encounter very big screens like 4k display.
#### Installation and Getting Started
This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

1. Clone the application

```
git clone https://github.com/lakshitarora14/Hulu-clone.git
```
2. Then install the dependencies

```
npm install or yarn 
```
3. Create a local environment file by creating a file as .env.local and have these inside as keys

```
API_KEY = xxxxxxxxxxxxx_xxxxxx
```
This clone uses a tmdb api, The api key can be requested here https://www.themoviedb.org/documentation/api
More about the API can be discovered over here https://www.themoviedb.org/documentation/api/discover

4. Run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
