# mincoin
Run the Jekyll webserver using `bundle exec jekyll serve`

### TODO:

Follow the steps below to create a new language or translate the home page content to a different language:
1. In _config.yml
   under # Lang settings
   add #'nl': 'Nederlands' **[after complete translate remove #]**
   and its short code under lang_codes: like  - 'nl'
2. Create file with language codes like this **[nl.yml]** under  _data/langs
   In this file search word  #TRANSLATE HERE  and translate under this word like
   **eg**
   meta:  #TRANSLATE HERE [description and title ] here need to translate [description and title ] text
	description: "Official Mincoin Website" to --->>> description: "Site officiel de Mincoin"
	title: "Mincoin &#8211; Official Mincoin Website" to --->>> description: "Mincoin & # 8211; Site officiel de Mincoin"

3. Create a folder under /langs with language codes like langs/nl/index.html
   Assign **draft: true** when language is ready for production.
   Any language in development will not have this line.
