#  markdownFundamentals :page_facing_up: 
A complete cheatsheet with examples well commented, for all basic syntax used in a README.md file :blush:
___
# MARKDOWN CHEATSHEET :memo:
<!-- for inserting an image -->
>image:

![MD](https://markdown-here.com/img/icon256.png)
___ 
>headings:
<!-- headings -->
# heading1
<!-- heading1 owns a horizontal rule under it by default -->
## heading2
### heading3
#### heading4
##### heading5
###### heading6
---

<!-- itlacis bolds strikethroughs -->
>bold, italic, strikethrough:

this text is _italic_  
this text is also *italic*  
this text is __bold__  
this text is also **bold**  
this text is ~~strikethrough~~

<!-- horizontal rule: use triple underscore--> 
___

<!-- break lines -->
>linebreak:

para1
para2  
vs  
para1   
para2
<!-- in second example, two spacebars are hit after para1 to jump to para2 -->
___
>escape characters:

<!-- escape characters -->
use \ to escape characters like \*t&c\* 
___
>blockquote:

<!-- blockquotes -->
> this is a blockquote
___

<!-- for links -->
>links:

my insta link: 
[@MYRONIC](https://www.instagram.com/myronic/)
<!-- try adding your own insta or any social media link :D -->
___
<!-- ul -->
>unordered lists:

* item 1
* item 2
    * 2.1
    * 2.2
        * 2.2.1
            * bas na ab.
___
>unordered lists:

<!-- ol -->
1. item1
2. item2  
    * random...
___
>inline codeblock:

<!-- inline code block -->
`<p>this is a para tag </p>`  
`void main(){  
      printf("single line code");
    }`

___
>block of code:

<!-- for code blocks  -->

JavaScript:
```javascript
var mylink = "https://github.com/Myronic";
function (mylink){
     console.log(mylink);
     }
```
C:
```C
void main(){
    printf("Hello Github");
}
```
Python:
```python
def add(num1, num2):
    return num1 + num2
```
so on for all languages...
___
<!-- tables   -->
>Tables:

| name  | email |  
|-------|--------|
|Myron  |myron.c@somaiya.edu|

___
<!-- todos -->
>checklist:

* [x] Learn
* [x] something
* [x] new
* [ ] everyday!
that's it!
___
<!-- writing a stepbystep command guide -->
>bash:  (for beginners like me :D )   

Say you want to
* fork this repo (your own copy of this repo)
* clone as local repo to pc
* make changes
* push those changes back to remote(github)
* and send a pull req to main repo(this repo) 


First fork this repo.  
Now
Run these commands in terminal
(make sure git is installed. to check: `git --version`)
```bash
git clone https://github.com/YOUR-USERNAME/markdownFundamentals

cd markdownFundamentals

git init master

git remote add origin https://github.com/YOUR-USERNAME/markdownFundamentals

git remote add upstream https://github.com/Myronic/markdownFundamentals

<<make the desired changes>> 

git add .

git commit -m "add a commit message here"

git push origin master
```
all changes thus made in local repo (your repo on pc) is now reflected in your remote repo(your repo on github), now you can send a pr via github to  main repo (this repo from where you forked)

##### For quick brush of what all just happened here watch this video by Brad Traversy :[Markdown crash course](https://www.youtube.com/watch?v=HUBNt18RFbo)  
For all emojis : [Click here](https://gist.github.com/Myronic/02ac89d4d9dd2126f8f531b34981e287)  
###### -myronic :wink:
