#"Site Sucker" ver alpha  python 2.7


what program does:
- download index files
- download all css
- download all js
- download all image
- download all fonts
- donwload all pages

problems:
- when you suck files that start with such url: "/", you try open index file and it dont see url "/" cose it it main folder of your pc. So you can just delete "/" or put files in web server
- program can create empty files, that is type in css but there is no such file on server, so u can just delete it

program create .log file where u can see all tree of download