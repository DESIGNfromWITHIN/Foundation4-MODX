Foundation4 MODX
MODX Revolution template based on Foundation4 from Zurb (http://foundation.zurb.com/)

-----------------------------
ABOUT
-----------------------------

This is a very minimal MODX Revolution template, with this template you can quickly install to start using the fantastic Foundation 4 framework.

For comments and suggestions please see the Github page: https://github.com/DESIGNfromWITHIN/Foundation4-MODX or get in touch on Twitter: @MennoPP

-----------------------------
REQUIREMENTS
-----------------------------

- MODX Revolution 2.2+

-----------------------------
INSTALLATION
-----------------------------

#1 Copy all the files to: "<your_website_root>/assets/templates/foundation4_modx/"

#2 Create a Chunk called "template_header"
	- Tick "Is Static"
	- Select "Filesystem" under "Media Source for Static File"
	- Point "Static File" to: "<your_website_root>/assets/templates/foundation4_modx/chunks/template_header.html"

#3 Create a Chunk called "template_footer"
	- Tick "Is Static"
	- Select "Filesystem" under "Media Source for Static File"
	- Point "Static File" to: "<your_website_root>/assets/templates/foundation4_modx/chunks/template_footer.html"

#4 Create a Template called "Basic page"
	- Tick "Is Static"
	- Select "Filesystem" under "Media Source for Static File"
	- Point "Static File" to: "<your_website_root>/assets/templates/foundation4_modx/template_basic_page.html"

#5 Assign the new "Basic page" template to your pages