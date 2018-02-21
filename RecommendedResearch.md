# The mostly complete guide to web dev

Do not progress to the next title, till your happy with your understanding of current area.

### Web Development 'Old'
Around since the dawn of time, runs and is supported by everything. Proberly what you would have been taught in schools. Still ultra relevant as its the core of web.
* HTML
    * https://www.w3schools.com/html/default.asp
    * https://www.tutorialspoint.com/html/index.htm
    * https://www.tutorialspoint.com/html5/index.htm
    * https://developer.mozilla.org/en-US/docs/Web/HTML
* CSS
    * https://www.w3schools.com/css/default.asp
    * https://www.tutorialspoint.com/css/index.htm
    * https://developer.mozilla.org/en-US/docs/Web/CSS
* JS (ES5/Standard for Web clients)
    * https://www.w3schools.com/js/default.asp
    * https://www.tutorialspoint.com/javascript/index.htm
    * https://developer.mozilla.org/en-US/docs/Web/JavaScript
* JSON
    * Lightweight and modular way to define data.
    * https://www.w3schools.com/js/js_json_intro.asp
* XML
    * Almost always use JSON over XML. Still around because Microsoft latched on and never let go...
    * https://www.w3schools.com/xml/default.asp
* jQuery
    * Dated, better alteratives, want to avoid as much as humanly possible, I really dont consider this required knowlage anymore
    * https://jquery.com/
    * https://www.w3schools.com/jquery/default.asp

### Web Development 'New'
We have since moved on from static sites and basic html and css (Web 1.0) to dynamic sites, where content is changed, loaded, updated, pushed etc after or on the request to the server (Web 2.0). These days, with Web 3.0 looming or arrival depending on who you ask (Web tech on clients, Sematic Web, AI, IOT, 'Always on', SaaS, FaaS, 'The WebOS' etc), these technologies are becomming more than standard, with newer and better things being released each day.

Whats listed here is the relevant subsection of what is standard in the industry, in some form or another.

* NodeJS
    * Allows for running JS on the client side, on a server. The gateway technology for a lot of highend web driven applications. Used everywhere.
    * https://nodejs.org/en/
    * https://www.tutorialspoint.com/nodejs/index.htm
    * NodeJS packages.json
        * https://docs.npmjs.com/files/package.json
    * Yarn
        * NodeJS's manager NPM is designed to fill a role in a massive application. Yarn fills in all the gaps that NPM has, and makes everything 'safer' and easier in the long run.
        * https://yarnpkg.com/en/
    * NPM!
        * Node Package Manager. Allows for hundreds of thousands of packeges to be using in NodeJS programs.
        * https://www.npmjs.com/
* CSS Pre-compilers
    * Allows a langugae similar to CSS to be written, but makes it a scripting language (IE Variables, imports, maths etc)
    * LESS
        * A NodeJS driven pre-compiler. Identical to SASS, but slightly inferior.
        * http://lesscss.org/
        * https://www.tutorialspoint.com/less/index.htm
    * SASS
        * A Ruby driven pre-compiler. Identical to LESS but slightly superior.
        * https://sass-lang.com/
        * https://www.tutorialspoint.com/sass/index.htm
* Frameworks
    * Bootstrap
        * Primary CSS framework out there for most people
        * https://getbootstrap.com/
        * https://www.tutorialspoint.com/bootstrap/index.htm
    * Foundation
        * Enterprise focused framework
        * https://foundation.zurb.com/
        * https://www.tutorialspoint.com/foundation/index.htm
* Bable (JS ES6 -> JS ES5)
    * Allows for the transpiling of JS ES6 code to ES5 code. So from what we develop in, to whats readable to the browser.
    * https://babeljs.io/
* Typescript
    * Allows for static typing (Python or JS vs C# or C) within JS. Its a superset of the ES6 standard of JS. By using this, we don't need Bable, as TS automaticly outputs ES5 (more or less)
    * https://www.typescriptlang.org/
    * https://www.tutorialspoint.com/typescript/index.htm

### Documentation
In any project, its very important to have documentation expecialy if you are working in a team. Knowing how to write to the standard documentation is critical.
* JSDocs
    * A complex syntax that allows all functions, values and classes to be labeled and documented within the code. A tool can then be used to scan the code and generate complete documentation. Using code to document code, what could be more awesome!
    * http://usejsdoc.org/
* Markdown
    * A language used to write documentation everywhere. Technicaly defines ways for text to be converted to HTML easily. Used by GitHub for all doucmentation in wikis, readmes etc. Its even used to write this document! There are many versions of markdown. The one we are using, and is considerd standard is the 'GitHub Flavored' version.
    * https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
* Github wikis
    * A wikipedia like system built into github. Should be used for any major systems or information that needs to be kept.
    * https://help.github.com/articles/about-github-wikis/
    * https://guides.github.com/features/wikis/

### Working in a team
* Git!
    * The major way to have code backed up and revisioned amongst a team.
    * https://git-scm.com/
    * https://www.tutorialspoint.com/git/index.htm
    * https://www.atlassian.com/git/tutorials/what-is-version-control (Foucses on BitBucket, which we wont be using)
* Accessing/Using Git
    * Command Line
    * GUI Program
        * GitKraken, GitHub Desktop, SouceTree, Tower etc. Take your pick
* GitHub
    * The ultra popular, ever present SaaS Git service.
    * https://github.com/
* Github workflows
    * There are many ways of doing Git within a team.
        * https://www.atlassian.com/git/tutorials/comparing-workflows
    * The workflow we will be using:
        * https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow

### Web Apps
The following will take the web from being multipage sites to multipage applications, or even single page applications.
* React
    * https://reactjs.org/
    * https://www.tutorialspoint.com/reactjs/index.htm
* Webpack / Gulp
    * Build chain tools, that automate a crap ton of stuff. At this point in dev, there will be too much for you to worry about to have to be manualy building all the time.
    * https://webpack.js.org/
    * https://gulpjs.com/
* Progressive Web Apps
    * https://developers.google.com/web/progressive-web-apps/
    * https://developers.google.com/web/fundamentals/codelabs/your-first-pwapp/
    * https://developers.google.com/web/tools/lighthouse/

### Client Side Web Apps
* Electron
    * Allows you to package a web app into a client side application. Runs a NodeJS enviroment.
    * https://electronjs.org/
    * https://www.tutorialspoint.com/electron/index.htm
* NWjs
    * Similar to electron, but is not as featured or allows bundling or appifiction.
    * https://nwjs.io/

### Enviroment/Editors
Editors are very much the preference of the person using it. If you like something, then you have no reason to justify it to others. Having said that, knowing and making the right choice in the beginning can significantly increase efficency.
* Visual Studio Code (Editor)
    * My **personal favorite**, use it for **everything**.
    * https://code.visualstudio.com/
* Atom (Editor)
    * VSCode's direct competition. Requires more configuration, and lacks some features, but really no difference
    * https://atom.io/
* Jetbrains Webstorm (IDE)
    * Ultra high quality IDE, built on the Industry Leading IntelliJ editor, specificly for web technologies. Very heavy weight, and handles **alot** of things for you. Though not as configurable
    * https://www.jetbrains.com/webstorm/
* Sublime Text 3 (Editor)
    * Textedit/Nodepad on steroids. Ultra ultra lightweight, handles everything, has an emense amount of features hidden just under the surface. Still use it over VSCode for **alot** of things.
    * https://www.sublimetext.com/
* Notepad++ (Hardcore Editor/IDE)
    * If your using this, you have a problem and should be seen by a doctor. Go use sublime at least!
    * https://notepad-plus-plus.org/download/v7.5.4.html
* Emacs (Harder Core Editor)
    * An editor predicated on you configuring it to what you want, comes with nothing easy or out of the box. Though proberbly the best solution if you have a absolute way of doing things.
    * https://www.gnu.org/software/emacs/
* Vim (Hardest Core Editor)
    * I dont even...
    * http://www.vim.org/

# Extra Stuff

### Awesome Lists
Go have a serious look at these. Just browse at your own pase, there is a lot in there. Have a look at what ive talked about so far. You are going to find some really awesome things! No pun intended.

    https://github.com/sindresorhus/awesome


### Rich/Easy/Dynamic Content
* D3js (NOT NEEDED! VERY COMPLEX)
    * A very extensive library for creating dynamic graphs, illustrations etc. Just take a look at the Gallery.
    * Ask Jonn in slack for the book on it. Its 800 pages of pure awesomeness and pain...
    * https://d3js.org/
    * https://github.com/d3/d3/wiki/Gallery
    * https://www.tutorialspoint.com/d3js/index.htm
* C3js (Wrapper of D3js, VERY SIMPLE!)
    * With D3 being so complex, there have been a lot of wrappers and helpers made. This is the easiest and simpliest while offering a full range of charts that ive found.
    * http://c3js.org/
* HighCharts (Bet of both worlds <D3js, C3js>)
    * Highcharts is not backed by D3js which is hands-down the best library for this stuff. However, its still an awesome library that just continues to be awesome.
    * THIS REQUIRES AN INTERNET CONNECTION, as its a SaaS!
    * https://www.highcharts.com/

### Databases
* SQL vs NoSQL
    * https://www.tutorialspoint.com/sql/index.htm
* MYSQL (SQL)
    * https://www.tutorialspoint.com/mysql/index.htm
* PostgreSQL (SQL)
    * If any local SQL DB is to be used, this one will be
    * https://www.tutorialspoint.com/postgresql/index.htm
* MongoDB (NoSQL)
    * If any local NoSQL DB is to be used, this one will be
    * https://www.tutorialspoint.com/mongodb/index.htm
* AWS DynamoDB (NoSQL, Unique, Extra)
    * Likely to be used later on for external DB storage
    * https://www.tutorialspoint.com/dynamodb/index.htm
* CouchDB (NoSQL, Unique, Extra)
    * https://www.tutorialspoint.com/couchdb/index.htm

### Infrasturcture
* Continuous Intergration
    * https://jenkins.io/
    * https://travis-ci.org/
    * https://circleci.com/
    * https://codeship.com/
    * https://www.tutorialspoint.com/continuous_integration/index.htm
* Docker
    * Makes containers of code, for ultra rapid deployment and setup.
    * https://www.docker.com/
    * CONTAINER ORCESTRATION: (This stuff is lit af) https://kubernetes.io/
* Terraform
    * Infastructure as Code... This stuff is awesome.
    * https://www.terraform.io/

### Infrastructure Providers
IaaS (Infrustucture as a service) providers. IE Pay for a server by the hour. Auto scaling, load balancing, dns, stmp servers, databases, instances etc. You name it they have it
* Amazon Web Services (AWS)
    * Basicaly runs the web, like a stupid number of things run on them. 
    * Has an Australian location (Asia-SouthEast-2), so its fast and wont break Australian Information Law
    * https://aws.amazon.com/
* Azure
    * Microsoft's competing service to AWS. Better at some things, but a mostly inferior service to AWS
    * Has an Australian location (Asia-SouthEast-2), so its fast and wont break Australian Information Law
    * https://azure.microsoft.com/en-au/
* Google Cloud Platform
    * Googles offering of IaaS. Have not used it enough to form an opinon on it, mostly because they dont have any australian servers yet. So its highly impractical to use in any real capacity.
    * https://cloud.google.com/
* Heroku
    * A unique IaaS, they offer a service predicated around deploying an app, with boltons like servers, dns's etc. Again, no australian servers.
    * https://www.heroku.com/