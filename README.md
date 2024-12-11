# Google-Dorking
site:example[.]com inurl:api | site:*/rest | site:*/v1 | site:*/v2 | site:*/v3 <br/>
site:*.example.com inurl:.aspx <br/>
inurl:component/content/ <br/>
inurl:component/content/?view=featured&format=feed&type=atom <br/>
inurl:index.php/using-joomla/extensions/modules/ intext:joomla! 1.7 <br/> 
inurl:index.php/using-joomla/extensions/modules/19-sample-data-articles/joomla/50-upgraders <br/> 
inurl:using-joomla/extensions/templates/beez5/home-page-beez5 <br/>
inurl:index.php?format=feed&type=rss <br/>
inurl:index.php/using-joomla/extensions/plugins?format=feed&type=rss <br/>
inurl:index.php?format=feed&type=atom <br/>
intext:"joomla! 1.7 - Open Source Content Management" <br/>
intext:"joomla! 1.6 - Open Source Content Management" <br/>
intext:Joomla 1.6 inurl:index.php/login <br/>
intext:Joomla 1.7 inurl:index.php/login <br/>
intext:Joomla 1.6 inurl:index.php/registration <br/>
intext:Joomla 1.7 inurl:index.php/registration <br/>
inurl:index.php/plugins site: <br/>
inurl:index.php/rss=feed site: <br/>
intext:"index of /.git" <br/>
site:*.gapinc.com inurl:”*admin | login” | inurl:.php | .asp <br/>
site:..edu intext:"sql syntax near" | intext:"syntax error has occurred" | intext:"incorrect syntax near" | intext:"unexpected end of SQL command" | intext:"Warning: mysql_connect()" | intext:"Warning:  <br/> mysql_query()" | intext:"Warning: pg_connect()" <br/>
site:*.mil link:www.facebook.com | link:www.instagram.com | link:www.twitter.com | link:www.youtube.com | link:www.telegram.com | link:www.hackerone.com | link:www.slack.com | link:www.github.com <br/>
inurl:/geoserver/web/ (intext:2.21.4 | intext:2.22.2) <br/>
inurl:/geoserver/ows?service=wfs <br/>
site:*.* AND (ext:backup OR ext:bak OR ext:old) <br/>
inurl:"/wp-json/wp/v2/users"	==> all api for wordpress <br/>
inurl:"/includes/api" intext:"index of /"  find api dir <br/>
intitle:"index.of" intext:"api.txt"  ==> find api key files <br/>
ext:php inurl:"api.php?action="		==> sql injection <br/>
intitle:"index of" api_key OR "api key" OR apiKey -pool  <br/>
