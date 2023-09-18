# Learning_React
Just learning react

Required:
-VsCode editor

extensions;
 -ES7 React -> To create react components faster
            -> Command rafc and it will create the whole component
            -> video demo

 -Auto Rename Tag -> makes naming of ttags faster

 -Pretteir code Formatter- Arranges code, makes it look clean

Other Installation to be done:

NodeJS Application-> Contains Node Package Manager

Creating my first React app:

1. Open terminal
2. type and run this comtemand;
  npx create-react-app first-react-project

terminal output successful!
[short passage]

3. cd first-react-project
4. npm start
  ->Your Localhost will auotomatically open the react webapp in a  browser. [Note you should be able to see the react logo as shown in the image below.
5. Congratulations you have successfully created your reactApp

Analysing React Folder Structure:

1. Gitignore -> When sharing your code with others there are often files or parts of your project, you don want to share, 
for example- log files, temporary files, hidden files, personal files, etc Git ignore protects these files to get shared publicly.

2. package.json -> Contains descriptive and functional metadata about a project, such as name, version, and dependencies.
                -> It provides the npm package manager with various information to help identify the project and handle dependencies.

3.App.js -> This is the file for App components.
         -> App component is the main component in React which acts as a contact for all other components.

4. index.js -> Is the file that runs initially once the Node.js is executed. 
            ->It's responsible for our applications startup.

Modification of our Default React Project:

Yes we our app we created earlier is default.

1. navigate to the src(source folder)
2. change image to anythi you want
    -> copy url from an image on the net and paste in the "" in src="" of the image tag. ctrl + c and thats it (notice chage from react logo into your own.
3.change p tag and its content into <h2>my first ReactApp</h2>
