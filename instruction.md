#### SETUP INSTRUCTIONS

<hr>

 1. ##### create reactjs app
```js
 npx create-react-app applicationname
 ```
 2. ##### Change file dir
 ```
 cd applicationname
 ```
 3. ##### Test Reactjs
  ```js
  npm start 
  //or
  yarn start
 ```
 4. ##### Install git pages
 ```js
 npm install gh-pages --save-dev
 ```
 5. ##### Open package.json file and add this line of code above version
 ```
  "homepage": "http://{gitusername}.github.io/Road-to-REACT",
   "version": "0.1.0",
 ```
 6. ##### Open package.json file and add this line of code to scripts
```
 "predeploy": "npm run build",
 "deploy": "gh-pages -d build"
```
7. ##### Deploy Reactjs application to GitPages and check is build is successfull.
```
npm run deploy
```
<p align="center">
    <img src="https://user-images.githubusercontent.com/68312849/132342115-84c434b3-88c9-43bc-9d44-2e95edc97d15.png"  height="250">
</p>

8. ##### Now go to brower and open http://{gitusername}.github.io/Road-to-REACT 
9. #####  add this url to Contributor  Table 
10. ##### eg : |name | regnumber | link |---> |Virat | 19BCD7064 | [Link](http://{gitusername}.github.io/Road-to-REACT")
 
 <hr>
