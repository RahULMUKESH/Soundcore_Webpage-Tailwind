1.Install Dependencies
Before you can run the application, you must install its dependencies. These are specified in the package.json file in the root directory of the project.

bash
Copy
2.npm install
This command reads package.json to install all necessary packages from npm needed to run the application.

3. Start the Development Server
Once the dependencies are installed, you can start the development server using:

bash
Copy
npm start
This command will compile the React application and usually open a browser window automatically pointing to http://localhost:3000 where the app will be running. Any changes you make to the code will automatically refresh the page.

4. View the Application
With the development server running, you can see your application in action in the browser. If it doesn't automatically open, you can manually navigate to http://localhost:3000 in your web browser.

5. Make Changes and Test
As you modify the application, the development server will reload the page to reflect your changes, allowing you to develop interactively.

6. Build the Application for Production (Optional)
If you need to deploy the application, you can create a production build which compiles and optimizes your application for deployment:

npm run build
This command bundles React in production mode and optimizes the build for the best performance. The build is minified and the filenames include the hashes. The files will be placed in the build folder in your project directory.

![image](https://github.com/user-attachments/assets/f6147583-3653-4942-ba8d-3879f35ee1f4)
![image](https://github.com/user-attachments/assets/0d4fa24f-34ce-41eb-a032-7ba48c73c05c)

