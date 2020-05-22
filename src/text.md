//0
The look and feel of desktop applications have advanced leaps and bounds over the past several years,with more and more applications resembling modern websites than ever before. The technology behind this 
latest evolutionary step of desktop applications is called Electron
//1
Electron is a framework developed by GitHub in 2013 that is used to creating cross-platform applications using HTML, CSS and JavaScript.
Such applications can run on various platforms. Among they are Windows, Mac, and Linux.
 //2    
Electron is a project that was used to create many popular applications. Among them are Skype,Discord and WhatsApp messengers, editors for Visual Studio Code and Atom code, Figma as well as more than 700 applications, information about which is published on the Electron website.

Typically, desktop applications for each operating system are written in each's native language. That can mean having three teams writting three versions of your app. Electron enables yuo to write your app onceand with web languages.
//3
Electron combines Chromium and Node.js with a set of custom APIs for native operating system functions like open file dialogs, notifications, icons and more. Developing with Electron is like building web pages that we can seamlessly use Node in—or building a Node app in which we can build an interface with HTML and CSS. And we only need to design for one browser, the latest Chrome.
//4
Electron has two types of processes: Main and Renderer. The process that runs package.json's main script is called the main process. The script that runs in the main process can display a GUI by creating web pages. An Electron app always has one main process, but never more.

//5
The main process, commonly a file named main.js, is the entry point to every Electron app. It controls the life of the app, from open to close. It also calls the native elements and creates each new renderer process in the app. The full Node API is built in.

//6
The renderer process is a browser window in your app. Unlike the main process, there can be multiple of these and each is independent. They can also be hidden. Usually one is named index.html. They're like typical HTML files but in Electron you've got the whole Node API available here, too, unlike any web browser.

//7
The main and renderer processes need to be able to communicate since they're both responsible for different tasks. For that there's IPC, interprocess communication. 

//8 
Electron apps are like Node apps and use a package.json file. It's there that you define which file is your main process and thus where Electron should start app. Then that main process can create renderer processes and then use IPC to pass messages between the two.
//9
To get started with developing using the Electron, you need to have Node and npm(node package manager) installed. 
//10

//11
Electron is a progressive software development framework that has given us a number of prominent desktop applications, including Atom, Discord, Slack, Trello, Figma and Etcher, just to name a few. The reasons why professional Electron JS developers enjoy using it include its low barrier to entry, fast speed of development, automatic updates and convenient installers, cross-platform support, and its large community of developers and users.

