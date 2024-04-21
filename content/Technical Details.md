This whole thing is based on [Quartz](https://quartz.jzhao.xyz/)
Refer to it for technical documentation.
However, below is an overview of the key aspects 

- The code for the wiki lives [here](https://github.com/AmericanFlagInPlace/AFIPWiki)
- All of the pages on this wiki live in the content folder (ONLY MODDIFY THE CONTENT FOLDER)
- The look and layout of the site lives in quartz.config.ts and quartz.layout.ts. Best not to edit them unless you know what you are doing or what you want to do
- To get the quartz server running locally on [localhost:8080](http://localhost:8080/) follow these steps
	- You will need nodejs and npm on your computer. Get them [here](https://nodejs.org/en/download)
	- Open your terminal and navigate to the root directory for the project
	- run ```npm i``` to get all the packages configured on your system
	- Then run ```npx quartz build --serve``` to spin up your local quartz instance
	- You should see a link to [http://localhost:8080/](http://localhost:8080/) click that and you now have quartz running locally 
- If you make any changes, push them to the main branch (subject to change) v4 using the ```git commit -m "YOUR MESSAGE HERE"``` and ```git push```.
- When you want to view changes that other people have made, use ```git pull``` to sync your code
- Conversely you could just use [GitHub Desktop](https://desktop.github.com/) , a GUI based version of git, to manage your changes but that is up to you