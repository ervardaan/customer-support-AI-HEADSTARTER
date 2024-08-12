# initialize application
- `npx create-next-app@latest`
- then give appname when prompted
- normally we get a folder with `appname` and go inside this folder to do everything but when we upload everything to github, we have to move all contents from this `appname` folder outside as our vercel deployment can't get inside this `appname` folder- thus move everything out of this `appname` folder and delete this empty folder
- install openai `npm install openai` and material ui `npm install @mui/material @emotion/react @emotion/styled`

# initializing openai
- go to openai platform playground `platform.openai.com`
- to create api keys go to `https://platform.openai.com/api-keys`
- copy the api key which is  for my project
- GO TO the main folder(not the appname folder as we deleted that and transferred its files one level above) and create an `.env.local` file
- create a constant called `OPENAI_API_KEY` and set this key as its value

# creating a route
- go to `app` folder and make a new folder `api` and inside api folder create a `chat` folder- this chat is one route
- create `router.js` file insie chat folder inside api folder inside app folder
