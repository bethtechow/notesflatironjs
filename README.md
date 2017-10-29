# notesflatironjs
echo "# notesflatironjs" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/bethtechow/notesflatironjs.git
git push -u origin master
SUMMARY
In this section, we learned how to use Javascript and our developer console to ask questions about our HTML. Here is our process:
From the browser, click inspect element on the HTML element you are interested in to find an identifying attribute to select the HTML.
Depending on the type of attribute, you can then use document.querySelector() method, and in the parentheses pass through the proper CSS selector in combination with the attribute name to select that element.
Or you can use a different Javascript method like document.getElementsByClassName() to select the correct element.
Once you have properly targeted the element, you can then call other methods to identify attributes of that element. Eg.document.querySelector('a').text
