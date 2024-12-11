# Google-Dorking
site:example[.]com inurl:api | site:*/rest | site:*/v1 | site:*/v2 | site:*/v3
site:*.example.com inurl:.aspx
inurl:component/content/
inurl:component/content/?view=featured&format=feed&type=atom
inurl:index.php/using-joomla/extensions/modules/ intext:joomla! 1.7
inurl:index.php/using-joomla/extensions/modules/19-sample-data-articles/joomla/50-upgraders
inurl:using-joomla/extensions/templates/beez5/home-page-beez5
inurl:index.php?format=feed&type=rss
inurl:index.php/using-joomla/extensions/plugins?format=feed&type=rss
inurl:index.php?format=feed&type=atom
intext:"joomla! 1.7 - Open Source Content Management"
intext:"joomla! 1.6 - Open Source Content Management"
intext:Joomla 1.6 inurl:index.php/login
intext:Joomla 1.7 inurl:index.php/login
intext:Joomla 1.6 inurl:index.php/registration
intext:Joomla 1.7 inurl:index.php/registration
inurl:index.php/plugins site:
inurl:index.php/rss=feed site:
intext:"index of /.git"
site:*.gapinc.com inurl:”*admin | login” | inurl:.php | .asp
site:..edu intext:"sql syntax near" | intext:"syntax error has occurred" | intext:"incorrect syntax near" | intext:"unexpected end of SQL command" | intext:"Warning: mysql_connect()" | intext:"Warning: mysql_query()" | intext:"Warning: pg_connect()"
site:*.mil link:www.facebook.com | link:www.instagram.com | link:www.twitter.com | link:www.youtube.com | link:www.telegram.com | link:www.hackerone.com | link:www.slack.com | link:www.github.com
inurl:/geoserver/web/ (intext:2.21.4 | intext:2.22.2)
inurl:/geoserver/ows?service=wfs
site:*.* AND (ext:backup OR ext:bak OR ext:old)
inurl:"/wp-json/wp/v2/users"	==> all api for wordpress
inurl:"/includes/api" intext:"index of /"  find api dir
intitle:"index.of" intext:"api.txt"  ==> find api key files
ext:php inurl:"api.php?action="		==> sql injection
intitle:"index of" api_key OR "api key" OR apiKey -pool 
