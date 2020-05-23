* The look and feel of desktop applications have advanced leaps and bounds over the past several years,with more and more applications resembling modern websites than ever before. The technology behind this latest evolutionary step of desktop applications is called Electron.
Electron is a framework developed by GitHub in 2013 that is used to creating cross-platform applications using HTML, CSS and JavaScript.  Such applications can run on various platforms. Among they are Windows, Mac, and Linux.
* Why should you build an Electron desktop app?
1. Low barrier to entry-Because Electron uses JavaScript, HTML, CSS, and other web technologies, virtually all developers with web development skills can get started with it without much effort. 
2. Increased development speed-  Electron uses JavaScript, one of the easiest and most effective programming languages in use today. Because JavaScript code is interpreted line by line, developers can effortlessly debug and optimize it, which allows them to ship applications much faster than they could otherwise.
3. Automatic updates and convenient installers- Electron desktop apps can automatically update themselves thanks to the autoUpdater component and creating convenient installers for Electron desktop apps takes very littletime thanks to electron-builder, a complete solution to package and build a ready for distribution Electron app.
4. Cross-platform support- The reason Electron desktop applications run flawlessly across different operating systems is simple: they are essentially instances of the Chromium web browser, Google’sopen-source web browser project. That’s also why they tend to consume far more memory than desktop applications written in other programming languages.
5. Large community of developers and users-Electron is a massive open source project whose reach spans the globe, and there are thriving Electron communities of developers and users everywhere, producing an abundance of educational resources and development tools.
* What's developing like?
Electron combines Chromium and Node.js with a set of custom APIs for native operating system functions like open file dialogs, notifications, icons and more. Developing with Electron is like building web pages that we can seamlessly use Node in—or building a Node app in which we can build an interface with HTML and CSS. And we only need to design for one browser, the latest Chrome.
* Types of Process
Electron has two types of processes: Main and Renderer. The process that runs package.json's main script is called the main process. The script that runs in the main process can display a GUI by creating web pages. An Electron app always has one main process, but never more.
Main process
* The main process, commonly a file named main.js, is the entry point to every Electron app.It controls the life of the app, from open to close. It also calls the native elements and creates each new renderer process in the app. The full Node API is built in.   
Renderer process
* The renderer process is a browser window in your app. Unlike the main process, there can be multiple nof these and each is independent. They can also be hidden. Usually one is named index.html.They're like typical HTML files but in Electron you've got the whole Node API available here, too, unlike any web browser. 
* Interprocess communication
The main and renderer processes need to be able to communicate since they're both responsible for different tasks. For that there's IPC, interprocess communication. 
* How it works?
Electron apps are like Node apps and use a package.json file. It's there that you define which file is your main process and thus where Electron should start app. Then that main process can create renderer processes and then use IPC to pass messages between the two.
* Quick start
To get started with developing using the Electron, you need to have Node and npm(node package manager) installed. To clone and run for a quick way to see Electron in action. Install Electron and start!
* How Does This App Work?
The script specified by the main field is the startup script of your app, which will run the main process. We have a main(main.js) file and HTML(nidex.js).The main file uses two modules –
app and BrowserWindow. The app module is used to control our application’s event lifecycle while the BrowserWindow module is used to create and control browser windows.We defined a createWindow function, where we are creating a new BrowserWindow and attaching a URL to this BrowserWindow.
* This is the HTML file that is rendered and shown to us when we run the app.Once your app is built, you can package it with the command-line tool electron-packager for Mac, Windows or Linux. Add scripts for this to your package.json.
* Conclusion 
Electron is a progressive software development framework that has given us a number of prominent desktop applications, including Atom, Discord, Slack, Trello, Figma and more then 700 applications . The reasons why professional Electron JS developers enjoy using it include its low barrier to entry, fast speed of development, automatic updates and convenient installers, cross-platform support, and its large community of developers and users.

