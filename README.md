# MongoDB-Count-All-Collections
Command for count all collections

#linkedin : https://www.linkedin.com/in/can-sayın-b332a157/
#cansayin.com

<pre id="example"><code class="language-lang"  style="color: #333; background: #f8f8f8;"> 
db.getCollectionNames().forEach(function(collection) { resultCount = db[collection].count(); print("Results count for " + collection + ": "+ resultCount); });
</code></pre>
