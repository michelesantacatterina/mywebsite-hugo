# How to deploy website

1. ###Clone mywebsite-hugo repo from github

	cd ~/Documents/Github/
	
	git clone https://github.com/michelesantacatterina/mywebsite-hugo.git

2. ###Clone michelesantacatterina repo from github

	cd ~/Documents/Github/
	
	git clone https://github.com/michelesantacatterina/michelesantacatterina.github.io.git

3. ###Change the website's contents (use markdown)

	cd /Users/micsan/Documents/Github/mywebsite-hugo/
	
	hugo server
	
	http://localhost:1313/
	
	ctrl+c to stop server

Note CV: change config.toml and add new cv in static/files

5. ###Remove old public folder

	rm -rf public 

6. ###Build website

	hugo
	
7. ###Add new content to michelesantacatterina.github.io

	cd ..
	
	cd michelesantacatterina.github.io
	
	cp -av /Users/micsan/Documents/Github/mywebsite-hugo/public/* .
	
	
	git add -A
	
	git commit -m "updates"	
	
	git push origin master
	
	
Notes. ### Some notets

If you want to add/remove info about social media, use config.toml (https://github.com/gcushen/hugo-academic/issues/644)


