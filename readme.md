## Things that you need to do:


#### Publishing as a github page
* Create a branch named 'gh-pages'


#### Connecting a custom domain
* On the DNS provider create a subdomain. Ex: 650anderson.captivaterealestate.com
* On that subdomain create a CNAME record pointing to dladowitz.github.com. (This routes to the github account)
* Create a file named 'CNAME' in the root of the github repo. 
* Add the referencing subdomin to the cname file. Here the subdomain is '650anderson.captivaterealestate.com'. (This allows github to properly route any incomming CNAMES to the proper repo)


* https://help.github.com/articles/setting-up-a-custom-domain-with-github-pages/
* https://help.github.com/articles/adding-a-cname-file-to-your-repository/

<br>
<hr>
### TODO
* Setup Jekyll: https://help.github.com/articles/using-jekyll-with-pages/