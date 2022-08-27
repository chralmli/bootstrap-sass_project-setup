# bootstrap-sass_project-setup

# STRUCTURING PROJECT WITH BOOTSTRAP AND SASS

1. First create package.json. To do so, run **npm init -y**

2. Run **npm install sass** to install sass

3. Create a styles folder with a scss and css folder inside

4. Install sass & live-server by running **npm install -D sass live-server**

5. Create your src folder with scss folder and file inside. You can type it like this: **src/scss/style.scss**

6. Add the build script: **"build": "sass src/scss:dist/css"** and run the build script with **npm run build**. This should create the dist and css folders containing styles.css and styles.css.map.

7. Add the watch script: **"watch": "sass --watch src/scss:dist/css & live-server"** and run the script: **npm run watch**. 

8. Now link the css file to html: **/dist/css/styles.css**

9. Create the .gitignore file. Type **/node_modules** inside the file.

10. Install bootstrap with **npm install bootstrap** 

11. In the style.scss import bootstrap: **@import "../../node_modules/bootstrap/scss/bootstrap.scss";**

12. Remember to run the watch script again.

13. Reference bootstrap js: **<script src="/node_modules/bootstrap/dist/js/bootstrap.bundle.min.js"></script>**
