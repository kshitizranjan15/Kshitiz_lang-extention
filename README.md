# Kshitiz_lang_extention
### language extention:- .ksh
![](https://img.shields.io/badge/Language-Typescript-green)   
![](https://img.shields.io/badge/Tools-VscodeDevelopmentKit-red)   
![](https://img.shields.io/badge/Project-Vs-Code Language Support-blue)
## kshitiz-lang README
In this file i will say how to use this kshitiz-lang extention and i made this extention for what purpose.

## what is this extention and why it is made?
This is vs code language extention and i made this extention for two purposes which i got in task 1 and task 2. i.e. 
1.Bracket Color Matching
2.Instellisense for core slots.

## what we have to do before running this extention.
Before Running This extention we have to install extentions of Bracket Pair Colorizer[Installation
Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter.
ext install CoenraadS.bracket-pair-colorizer]
 and Bracket Pair Colorizer 2[Installation
Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter.
ext install CoenraadS.bracket-pair-colorizer-2] extentions in our vs code,
whilch will help code which written in launch.json for Bracket Color Matching.

## How to run kshitiz-lang extention.
For Running this extention we should open launch.json or language-configuration.json or kshitiz.tmLanguage.json 
and the press f5 or press on run button.

## Variables of kshitiz-lang extention.
int,double,float,long,char,boolean,String,short are variables of this language 

## Keywords of kshitiz-lang extention.
if,else,do,while,for,return,ksh are key words of kshitiz-lang

## How to use Bracket Pairing after running extention.
After running extention if we will gives brackets in pair like () , {}, [], [{()}] or in any pairing way
then simirar brackets will appear in same color and if one of braces from pair is missing then other
pair will appear in red color.

## How to use Instellisense for core slots after running extention.
 <li><ul>In my extention i taken help of regex for writing static/dynamic rules which written in kshitiz.tmLanguage.json
 after running extention write</ul>
 <ul> RULE <openApp> = open {static:rsetAlarm} app;</ul>
 <ul> RULE <openApp> = open {static:rdatetime} app;</ul>
 <ul> RULE <openApp> = open {dynamic:rdate} app;</ul>
 <ul>RULE <openApp> = open {static:rtime} app;</ul>
 <ul>RULE <openApp> = open {static:rduration} app;</ul>
  <ul>RULE <openApp> = open {static:rnumeric} app;</ul></li>
 in .kshitiz file after that whenever u will type 
 RULE <openApp> = open {dynamic:r} app; then afrer r you will get auto suggestion for rsetAlarm,rdatetime,rdate,rtime,rduration and rnumeric
 and if we will hover on this rules then it will redirect towards it's origin.

 # If you are also intersted in creating any language extention or vs code extention
 - First of install Node-js and git in your pc
 - Then install Yeoman and VS Code Extension Generator with:npm install -g yo generator-code (Type this in Command prompt or terminal)
 - After this type yo code in terminal and press enter
 - Now Create Whatever you wants to create
