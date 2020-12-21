# react in a non-react app
How to use react in a non-react app. This repo, more specifically, integrates react into plain html/css/js app. The process is exactly the same for other apps too however, it's just a matter of understanding what's really going on.


Followed this guide https://reactjs.org/docs/add-react-to-a-website.html to create this sample project

Steps:
1. clone the repo
2. run `npm init -y` & then `npm install babel-cli@6 babel-preset-react-app@3`
3. run `npx babel --watch src --out-dir public --presets react-app/prod`
