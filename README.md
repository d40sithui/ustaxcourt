For this project, I wanted to use the most simplest setup because it only requires JS. Initially I opted to use just a simple html page and a text editor. Then I will load it in Chrome or Firefox. However, that presented a problem when trying to use JS to open the CSV locally; CORs. Since I am running the index.html on a non webserver, there are no headers on the files, so all my browsers throw the CORS error. The workaround is to use 1) Visual Studio Code 2) Install Live Server extension. This allows VS Code to run the page in some sort of webserver and thus allows those CSV to return the proper headers for the JS app to consume. Simply click on "Go live" while on the index.html page to launch it.

This is not a performant based app. It has a ton of loops opening arrays with thousands of records. It takes me 1 minute or so to finish loading. See slcspout.csv for the final results. I spot checked some records and I think it is correct.
