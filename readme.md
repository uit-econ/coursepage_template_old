# How to set ut a course page

## 1. Create an organization

The first thing we need to do is to create an "organization", which will own the course page. You do this as follows:

		1. Log in to github.com
		2. Click on your username in the left panel 
		   (if you don't se your user name, type in "github.com" in the web adress field")
		3. Select "Create organization"
		4. Choose the "Create a free organization" option
		5. Use the following setup:
			a) Name your organization using the convension "uit-<course_code>-<semester><year>. 
				<course_code> can for example be SOK-1006.
				<semester> can be either "h" or "v" (Norwegian) or "f" or "s" (English).
				If you don't understand what <year> means, you need to quit now.
				For example, the name can be uit-sok-1006-v23. 
			b) Enter your e-mail
			c) Select "A business or institution"
			d) Enter "UiT The Arctic University of Norway" as name of institution. 
			e) Accept the terms and click "Next"
		6. Add the github usernames of the colleagues that shall participate in the coursem and click "Complete setup"
		7. Enter your github password
		8. Click your icon in the upper right corner, and select "Your organizations"
		9. Click on the organization you just created
		
## 2. Create the course repository

		1. In the organization menu, click "Repositories", and click "Create a new repository"
		2. In the "Repository template" dropdown, select "uit-econ/coursepage_template"
		4. IMPORTANT! Change the "Owner" to the organization you just created. 
		3. Name the tempalte extactly the same as the organization name, but append ".github.io" to the name. 
			For example, if your organization name was "uit-sok-1006-v23", the course repository should be "uit-sok-1006-v23.github.io". 
			The purpose of this is to make the repository the default page of the organization. 
		4. Select the "Public" option and click "Create repository"
		
## 3. View the "repo" (repository) homepage
		1. Locate the "github-pages" link down to the right in your repository (under the Code menu), and click it. 
		2. Click on the "View deployment" in the following page, and you will see your new course page (can take a couple of minutes befor it is ready)
		4. If you cannot see the "github-pages" link, even after waiting for a few minuttes, enable the web interface by clicking "Settings" in the repo menu, 
			"Pages" in the left pane and "main" in the "Branch" dropdown. Then click "Save".
			
## 4. Edit the repository
		1. Edit the settings-file "_config.yml". You only need to edit the first three lines (unless you want to edit the advanced settings). The first three lines are:

			**bilde: tema.jpg**												
			name: Sok-xxxx Emnetittel #Emnetittel
			semester: Høst/Vår 20xx 
			
		1. You can edit the left menu by editing the file "navbar.html". You can begin by removing the link to this document ("How to set up the course page")
			You can edit the links by changing the link address and the link text. If you need more items, just copy one of the links and change it. 
			NOTE! if you want to link to a markdown *.md-file, you must change the file extension from ".md" to ".html". since the markdown files are changed to html files
			when published on the web page.
		
		2. There are all ready templates in Norwegian for the start page ("start.md"), lecture plan ("forelesningsplan.md"),
			turorial plan ("seminarplan.md") and plan for submissions ("innleveringer.md")
			
		
		
		
		
		
		