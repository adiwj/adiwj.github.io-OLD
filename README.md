# New Tab - for Chrome Theme

**Support Startpages**


imm build startpages too for Custom New Tab on Google Chrome and you can use my startpages from here. building HTML/CSS/JS you will understand what will are you doing, because The Startpages is not using Responsive Layout, only Fixed Layout. lets see what we have here.

**How to Install Chrome Extension ?**

Create a new directory from your computer, and then make 2 files for Chrome extension details data :
- manifest.json
- index.html

**manifest.json**
```
{
  "name": "Dextab",
  "description": "Minimalist New Tab for Chrome",
  "version": "0.1",
  "incognito": "split",
  "chrome_url_overrides": 
  	{
  	   "newtab": "index.html"
  	},
  "permissions": 
  	[
  	   "bookmarks", "history", "storage"
  	],
  "manifest_version": 2
}
```
after that, go to Extension Setting and active **Developer Mode** ,choose **Load unpacket** load folder where you save the manifest.json
its done

### Previews

Dextab|Wanjex
|--|--|
![img](https://raw.githubusercontent.com/adiwj/adiwj.github.io/master/Preview/dextab.png)|![img](https://raw.githubusercontent.com/adiwj/adiwj.github.io/master/Preview/wanjex.png)

----------------------------------------
- Facebook : www.facebook.com/diiwjyx
- Instagram : www.instagram.com/tuahafriadi_

Thank you
