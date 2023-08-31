# tailwinddemo
tailwind css was sucessfully used to make a tailwind css card
initial steps
●        Install VS code: You can easily download the VS code by clicking here. Moreover, Install the live server extension in VS code as it allows us to visualize our static page by opening the page with a live server.

●        Adding Tailwind CSS: To add tailwind CSS to your file, simply visit the official documentation by clicking here. After that, From the play CDN section, just copy the script and add it to the “<head>” of your HTML file. Hence, we can now use Tailwind CSS in our HTML file.

●        Install Node Js: You can Download Nodejs by clicking here. Select your OS and click on next, and your Nodejs will be installed.

●        Installing ‘Tailwind CSS IntelliSense’ extension: This extension provides some advanced features such as autocomplete, syntax highlighting, and linting.


 Create a New Project in VS Code

 Create a new file by clicking on the “Create New File” icon and name it “index.html”:
  Install Tailwind CSS Using VS Code Terminal

The next step is to install the Tailwind CSS, for that purpose open the VS Code terminal and execute the provided command:

npm install -D tailwindcss


 Configure Tailwind CSS

After the installation, configure Tailwind CSS by running the given command in the VS Code terminal:
npx tailwindcss init

The above command creates a config file after configuring Tailwind CSS.
The output returned a success message after creating a “tailwind.config.js” file.
Open the “tailwind.config.js” file and provide the name of the HTML file “index.html” as the value for “content”:

 Create a CSS file

The next step is to create a CSS file named “style.css” and type the given command in this file.
@tailwind base;
@tailwind components;
@tailwind utilities;

The above code will include base styles, pre-designed components, and utility classes for Tailwind CSS.

Save the “style.css” file by pressing the “CTRL+S” keys:
Let’s now build the Tailwind CSS file with the name “tailwindstyle.css” by utilizing the command given below:
npx tailwindcss -i ./style.css -o ./tailwindstyle.css --watch

In the above command, “-i” specifies the input, and “-o” specifies the output file to save the compiled CSS. 
Whereas the “–watch” flag tells the Tailwind CSS to 
watch for changes in the input file and recompile the output file automatically on the occurrence of any changes.
Link CSS file with HTML File

Now open the “index.html” file and utilize the “link” command in its head to link the Tailwind CSS file. Users can also modify the title according to their requirement:
<link href="./tailwindstyle.css" rel="stylesheet">
<title>LinuxHint</title>

Save the HTML file:

Note: Be careful about the path of the HTML file.
 Use Tailwind CSS
NOTE THAT "TAILWIND CLASSES ARE SO POWERFUL AND ,MAKES IT EASY"
The last step is to test the Tailwind CSS by typing the sample code. Run the HTML code 

hosted link of the project:---->https://manuhegde198924.github.io/tailwinddemo/

for steps to buils a sucessfull tailwind card refer-------------------------->https://github.com/manuhegde198924/tailwinddemo/issues/1



all detailed explaination of tailwind card STEPS OF MY PROJECT REFER::::::::----->https://github.com/manuhegde198924/tailwinddemo/issues/2

TO SUMMARIZE WE HAVE LEARNT:
    After completing this task WE would learn how to make a UI a responsive UI using Tailwind. 
    How creating UI using tailwind makes your work way too faster 
  WE would be using multiple Tailwind classes

  THANKYOU FOR REFERING "TAILWIND CLASSES USE IN TAILWIND CARD"

