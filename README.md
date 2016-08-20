# material-fab-social-button
A fab social share button inspired by Think with Google Blog.
![alt text](https://github.com/CAMconsulting/material-fab-social-button/blob/master/assets/thinkwithgoogle.png "Think with Google print screen")  
[Think with Google article](https://www.thinkwithgoogle.com/articles/retail-marketing-beacon-technology.html)  

I found this solution from social sharing brilliant, so I wanted to use it for my own projects.  
I used [Materializecss](http://materializecss.com/getting-started.html), [Material Icons](https://design.google.com/icons/) and [Social Icons from Folstudio](http://folstudio.com/).  
##Instructions  
You only to include the following code in your `<head>`:
```html
<link href="http://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/0.97.7/css/materialize.min.css">
```
For adding materializecss and material icons.  
Then, add this to your `<footer>`:
```html
<div class="fixed-action-btn click-to-toggle" style="right: 24px;">
      <a class="btn-floating btn-large">
        <i class="material-icons">share</i>
      </a>
      <ul>

        <li><a href="https://twitter.com/intent/tweet" rel="nofollow" target="_blank" title="Compartir en Twitter" class="btn-floating transparent"><svg width="40px" height="40px" viewBox="0 0 70 70" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
             <!-- Generator: Sketch 39.1 (31720) - http://www.bohemiancoding.com/sketch -->
             <title>Twitter</title>
             <desc>Created with Sketch.</desc>
             <defs></defs>
             <g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                 <g id="Twitter">
                     <circle id="Oval-1" fill="#55ACEE" cx="35" cy="35" r="35"></circle>
                     <path d="M51.0321333,21.6131333 C50.0442444,22.2459111 47.7760667,23.1654222 46.6574667,23.1654222 L46.6574667,23.1673111 C45.3802,21.833 43.5819778,21 41.5876889,21 C37.7143333,21 34.5734889,24.1408444 34.5734889,28.0126889 C34.5734889,28.5506444 34.6358222,29.0753778 34.7510444,29.5785778 L34.7499111,29.5785778 C29.4957778,29.4406889 23.7494,26.8072 20.2900889,22.2999333 C18.1632,25.9813778 20.0037333,30.0757333 22.4173556,31.5675778 C21.5911556,31.6299111 20.0702222,31.4723778 19.3543333,30.7738667 C19.3063556,33.2173333 20.4812444,36.4548889 24.7652444,37.6294 C23.9401778,38.0732889 22.4796889,37.9459778 21.8446444,37.8515333 C22.0675333,39.9142 24.9560222,42.6107778 28.1146222,42.6107778 C26.9888444,43.9129778 22.7532,46.2748444 18,45.5234444 C21.2281111,47.4875111 24.9904,48.625 28.9725556,48.625 C40.2888889,48.625 49.0771333,39.4536889 48.6041556,28.1396222 C48.6022667,28.1271556 48.6022667,28.1146889 48.6011333,28.1010889 C48.6022667,28.072 48.6041556,28.0429111 48.6041556,28.0126889 C48.6041556,27.9775556 48.6011333,27.9443111 48.6,27.9103111 C49.6302,27.2057556 51.0124889,25.9594667 52,24.3191556 C51.4272889,24.6346 49.7091556,25.2662444 48.1104,25.4230222 C49.1364444,24.8692 50.6566222,23.0554889 51.0321333,21.6131333" id="Fill-1" fill="#FFFFFF"></path>
                 </g>
             </g>
         </svg></a></li>
        <li><a href="https://facebook.com/sharer.php?u=" rel="nofollow" target="_blank" title="Compartir en Facebook" class="btn-floating transparent"><svg width="41px" height="41px" viewBox="0 0 70 70" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
             <!-- Generator: Sketch 39.1 (31720) - http://www.bohemiancoding.com/sketch -->
             <title>Facebook</title>
             <desc>Created with Sketch.</desc>
             <defs></defs>
             <g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                 <g id="Facebook">
                     <circle id="Oval-1" fill="#3B5998" cx="35" cy="35" r="35"></circle>
                     <path d="M30.1888889,52.0361795 L36.5635556,52.0361795 L36.5635556,34.5266541 L41.3457222,34.5266541 L42.2915,29.0555601 L36.5635556,29.0555601 L36.5635556,25.0910217 C36.5635556,23.8129797 37.3899444,22.4710941 38.571,22.4710941 L41.8263889,22.4710941 L41.8263889,17 L37.8367778,17 L37.8367778,17.0245253 C31.5943333,17.2510926 30.3117778,20.866437 30.2005556,24.6639696 L30.1888889,24.6639696 L30.1888889,29.0555601 L27,29.0555601 L27,34.5266541 L30.1888889,34.5266541 L30.1888889,52.0361795 Z" id="Fill-4" fill="#FFFFFF"></path>
                 </g>
             </g>
         </svg>
         <li><a  href="https://plus.google.com/share?url=" rel="nofollow" target="_blank" title="Compartir en Google+" class="btn-floating transparent" ><svg width="41px" height="41px" viewBox="0 0 70 70" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
             <!-- Generator: Sketch 39.1 (31720) - http://www.bohemiancoding.com/sketch -->
             <title>Google Plus</title>
             <desc>Created with Sketch.</desc>
             <defs></defs>
             <g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                 <g id="Google-Plus">
                     <circle id="Oval-1-Copy-6" fill="#DD4B39" cx="35" cy="35" r="35"></circle>
                     <path d="M17.0303611,34.866471 C17.12875,28.9737749 22.5405278,23.8129457 28.4271389,24.0095376 C31.2473611,23.8787358 33.8988056,25.1073379 36.0590834,26.8330644 C35.1374167,27.8814247 34.1826945,28.8920238 33.16225,29.8368328 C30.5656389,28.0398661 26.8719723,27.5267807 24.2753611,29.6020904 C20.5599167,32.1741353 20.3911389,38.247073 23.96425,41.0157098 C27.4393611,44.1724696 34.0080834,42.6047952 34.96825,37.7717489 C32.79125,37.7390484 30.6091945,37.7717489 28.4325834,37.7008979 C28.4271389,36.4010557 28.4216945,35.1012134 28.4271389,33.8013712 C32.0659723,33.790471 35.7048056,33.7850209 39.3490834,33.8122713 C39.56725,36.8705405 39.1635834,40.1254016 37.2868056,42.6542351 C34.4444167,46.6573133 28.7378611,47.8259645 24.28625,46.1111382 C19.8183056,44.407212 16.6539167,39.6831671 17.0303611,34.866471" id="Fill-186" fill="#FFFFFF"></path>
                     <path d="M47.2896111,31 L50.5356667,31 C50.5411111,32.0869001 50.5465556,33.1788611 50.5574444,34.2657612 C51.6432222,34.2766614 52.7340556,34.2766614 53.8198333,34.2875615 L53.8198333,37.5369725 C52.7340556,37.5478726 51.6486667,37.5533227 50.5574444,37.5642229 C50.5465556,38.6565731 50.5411111,39.7434732 50.5356667,40.8299841 L47.2841667,40.8299841 C47.2732778,39.7434732 47.2732778,38.6565731 47.2623889,37.5696729 C46.1766111,37.5587728 45.0853889,37.5478726 44,37.5369725 L44,34.2875615 C45.0853889,34.2766614 46.1711667,34.2712113 47.2623889,34.2657612 C47.2678333,33.173411 47.2787222,32.0869001 47.2896111,31" id="Fill-187" fill="#FFFFFF"></path>
                 </g>
             </g>
         </svg></a></li>
        <li>
          <a class="btn-floating transparent" href="http://www.linkedin.com/shareArticle" rel="nofollow" target="_blank" title="Compartir en LinkedIn"><svg width="40px" height="40px" viewBox="0 0 40 40" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
             <!-- Generator: Sketch 39.1 (31720) - http://www.bohemiancoding.com/sketch -->
             <title>Linkedin</title>
             <desc>Created with Sketch.</desc>
             <defs></defs>
             <g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                 <g id="Linkedin">
                     <circle id="Oval-1-Copy-5" fill="#0976B4" cx="20" cy="20" r="20"></circle>
                     <path d="M12.2087302,14.8381931 C13.585619,14.8381931 14.7018413,13.820253 14.7018413,12.5631772 C14.7018413,11.304989 13.585619,10.2857143 12.2087302,10.2857143 C10.8305079,10.2857143 9.71428571,11.304989 9.71428571,12.5631772 C9.71428571,13.820253 10.8305079,14.8381931 12.2087302,14.8381931" id="Fill-182" fill="#FFFFFF"></path>
                     <polygon id="Fill-183" fill="#FFFFFF" points="10.2857143 29.4729733 14.7590476 29.4729733 14.7590476 16.5714286 10.2857143 16.5714286"></polygon>
                     <path d="M21.0374286,22.2973918 C21.0374286,20.817864 21.7374286,19.3710366 23.4112063,19.3710366 C25.0849841,19.3710366 25.4965397,20.817864 25.4965397,22.2620219 L25.4965397,29.3081869 L29.949873,29.3081869 L29.949873,21.9739467 C29.949873,16.8784627 26.937873,16 25.0849841,16 C23.2336508,16 22.2125397,16.6262022 21.0374286,18.1435468 L21.0374286,16.4066421 L16.5714286,16.4066421 L16.5714286,29.3081869 L21.0374286,29.3081869 L21.0374286,22.2973918 Z" id="Fill-184" fill="#FFFFFF"></path>
                 </g>
             </g>
         </a></li>
       </ul>
     </div>
```
Finally, add these js scripts right before your `</body>`:
```html
<script type="text/javascript" src="https://code.jquery.com/jquery-2.1.1.min.js"></script>
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/materialize/0.97.7/js/materialize.min.js"></script>
```
You have the full code [here.](https://github.com/CAMconsulting/material-fab-social-button/blob/master/fab-basic.html)  
If you use [Jekyll](http://jekyllrb.com/), than you should try this other [version](https://github.com/CAMconsulting/material-fab-social-button/blob/master/fab-jekyll.html) that configures further the social buttons action. Thanks to [Kanishk Kunal](https://superdevresources.com/author/kanishk/) for authoring ["Simple Share buttons for Jekyll blog"](https://superdevresources.com/share-buttons-jekyll/), which really helped me to configure share buttons.  
Also you can find the four svgs logos within the **assets** folder.  
You can see the live demo [here.](http://goo.gl/jqDdFU)  
Happy Coding! :octocat: :shipit:


