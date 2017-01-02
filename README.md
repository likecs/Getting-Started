#Basic Github tutorial

##Installing Git
	sudo apt-get install git

##Configuring Git
	git config --global user.name "YOUR NAME"
	git config --global user.email "YOUR EMAIL"

	###Check changes
		git config --list

##Creating a local repository
	git init FirstRepository

##Creating a README file to describe that repository
	gedit README			
	Write the content for the readme file

	git add README

##Committing changes made to Index
	git commit -m "My First commit"

##Creating repository on Github
	Name of repository should be same as the repository on local machine
	Login to your account.
	Then click (+) symbol at the top right corner of the page and select "create new repository"
		

##Linking your local repository to one on github
	git remote add origin https://github.com/likecs/Getting-Started.git
	git remote -v
	git push origin master


##Storing password
	git config credential.helper store

		




