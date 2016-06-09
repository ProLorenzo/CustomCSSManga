/*BANNER PICS
Made this one myself includes loads of anime as May 2016, used Blink to create the thumbnails
*/
@import url(https://dl.dropboxusercontent.com/s/3149utozy8e8o8r/Manga.css);

/*  LIST WIDTH (NUMBER OF COVERS PER ROW)
Adjust the width of the list with the percentage amount in the first code. Afterwards, you may want to adjust the header behind the category links with the other code (lower it if you increase list width). 
*/

#list_surround 
{
    width: 72% !important;
}

/* BANNERS */
.header_cw:before 
{
    background-image: url(http://i.imgur.com/PiTo4GI.jpg);   
    background-attachment: scroll !important;
    background-position: center 30%;
    background-repeat: no-repeat;
    background-size: cover;
}
.header_completed:before 
{
    background-image: url("http://i.imgur.com/el6PlIa.jpg");
    background-attachment: scroll !important;
    background-position: center 30%;
    background-repeat: no-repeat;
    background-size: cover;
}

.header_onhold:before 
{
    background-image: url(http://i.imgur.com/DWMmfr0.jpg);
    background-attachment: scroll !important;
    background-position: center 30%;
    background-repeat: no-repeat;
    background-size: cover;
}

.header_dropped:before 
{
    background-image: url(http://i.imgur.com/Sa98uiw.jpg);
    background-attachment: scroll !important;
    background-position: center 20%;
    background-repeat: no-repeat;
    background-size: cover;
}

.header_ptw:before 
{
    background-image: url("http://i.imgur.com/QQ7KzDG.jpg");
    background-position: right 1%;
    background-attachment: scroll !important;
    background-repeat: no-repeat;
    background-size: cover;
}

.status_selected:nth-of-type(6) a:before 
{
    background-image: url("http://i.imgur.com/o6tSHgM.jpg");
    background-attachment: scroll !important;
    background-position: center 23%;
    background-repeat: no-repeat;
    background-size: cover;
}


/* MAIN BACKGROUND (BEHIND EVERYTHING) */

body
{
background-image: url(http://i.imgur.com/sabnhD5.jpg);
background-size: cover;
background-attachment: fixed;
}


/* EXTRA BACKGROUND IN FRONT OF BANNER (OPTIONAL) */
#inlineContent 
{
background-image: url();
}

/* EXTRA BACKGROUND BEHIND LIST (OPTIONAL)*/
#list_surround
{
background-image: url();
}


/*  TOP BAR ICONS
Replace the icons for the top bar here. Remember you see different icons depending on if you're on your own list or not, or when you're logged out.
*/

/*  USER ICON */
#mal\_cs_listinfo div:first-of-type a:before 
{
    background-image: url("http://i.imgur.com/L3NPnIc.png");
}

/*  LOGOUT ICON */
#mal\_cs_listinfo div:last-of-type a:before 
{
    background-image: url("http://i.imgur.com/8SeJ2Xv.png");
}

/*  ADD TO LIST ICON */
#mal\_cs_links div:first-of-type a:first-of-type:before 
{
    background-image: url("http://i.imgur.com/xQVAKzz.png");
}

/*  VISITOR'S ANIME LIST ICON*/
#mal\_cs_links div:last-of-type a:first-of-type:before 
{
    background-image: url("http://i.imgur.com/vIs2F3V.png");
}

/*  VISITOR'S MANGA LIST ICON*/
#mal\_cs_links div:last-of-type a:last-of-type:before 
{
    background-image: url("http://i.imgur.com/es1SALB.png");
}

/*  HOME ICON, VISITOR'S ICON FOR YOUR PROFILE LINK*/
#mal\_cs_links div:first-of-type a:last-of-type:before, #mal_cs_otherlinks div:first-of-type a:before 
{    
    background-image: url("http://i.imgur.com/wizrHEb.png");
}

/*  LIST OWNER'S MANGA LIST ICON*/
#mal\_cs_otherlinks di\v a[href*="/mangalist/"]:before 
{
    background-image: url("http://i.imgur.com/0HdfMQ7.png");
}

/*  LIST OWNER'S ANIME LIST ICON*/
#mal\_cs_otherlinks di\v a[href*="/animelist/"]:before 
{
    background-image: url("http://i.imgur.com/zuq7ViZ.png");
}

/*  FORUM ICON*/
#mal\_cs_otherlinks a[href*="/forum/"]:before 
{
    background-image: url("http://i.imgur.com/cFhhBvt.png");
}

/*  HISTORY ICONS*/
#mal\_cs_otherlinks a[href*="/history/"]:before, #mal\_cs_otherlinks di\v a[href*="/history/"]:before 
{
    background-image: url("http://i.imgur.com/R2p6EbR.png");
}


/*  EXPORT ICON*/
#mal\_cs_otherlinks a[href*="/panel.php?go=export"]:before 
{
    background-image: url("http://i.imgur.com/tRXCo2i.png");
}

/*  SHARED ICON*/
#mal\_cs_otherlinks di\v a[href*="/shared"]:before 
{
    background-image: url("http://i.imgur.com/1BHMiAh.png");
}


/*  LOGIN ICON*/
#mal_cs_otherlinks di\v a[href*="/login.php"]:before 
{
    background-image: url("http://i.imgur.com/Rd7leqb.png");
}

/*  REGISTER ICON*/
#mal_cs_otherlinks di\v a[href*="/register.php"]:before 
{
    background-image: url("http://i.imgur.com/fRQHVKI.png");
}


/*  LEARN MORE ICON*/
#mal_cs_otherlinks di\v a[href*="/modules.php?go=faq"]:before 
{
    background-image: url("http://i.imgur.com/oqrJXHB.png");
}




/*  COLORS*/

/* COLOR OF LIST*/
#list_surround
{
background-color:  rgba(1,1,1,.4) !important;
}

/* BACKGROUND COLOR BEHIND TOP BAR AND BANNER BORDER */
#list_surround:before,
#inlineContent:after,
#inlineContent:before 
{
background-color: rgb(52, 52, 52);    
}


/* MAIN BACKGROUND (BEHIND EVERYTHING) */
body 
{
background-color: rgb(26, 26, 26) !Important;
}


/* COLOR OF BUTTONS, HEADERS, UNSELECTED BUTTONS, ANIMETITLE, AND BEHIND ICONS
The first rgb color is the top of the header, second is bottom of the header (Firefox).
The third rgb color is the top of the header, fourth is bottom of the header (Chrome).
*/


#mal_cs_listinfo a, #mal_cs_links a, #mal_cs_otherlinks a,
.table_headerLink,
.status_not_selected a,
.status_not_selected:nth-of-type(6) a:after,
.header_cw, .header_completed, .header_onhold, .header_dropped, .header_ptw,
.td1, .td2, .td1 a + small, .td2 a + small, .animetitle,
#grand_totals,
.category_totals,
#copyright 
{
	 background-image: -moz-linear-gradient(top, rgb(26, 26, 26) 40%, rgb(13, 13, 13) 60%) !important;
	 background-image: -webkit-linear-gradient(top, rgb(26, 26, 26) 40%, rgb(13, 13, 13) 60%) !important;
}



/* COLOR OF CATEGORY MENU BUTTONS/TOP BAR BUTTONS/ANIMETITLE ON HOVER
The first rgb color is the top of the header, second is bottom of the header (Firefox).
The third rgb color is the top of the header, fourth is bottom of the header (Chrome).
*/
#mal_cs_listinfo a:hover, 
#mal_cs_links a:hover, 
#mal_cs_otherlinks a:hover,
.table_headerLink:hover,
.status_not_selected a:hover,
.status_not_selected:nth-of-type(6) a:hover:after,
.animetitle:hover  
{
	background-image: -moz-linear-gradient(bottom, rgb(26, 26, 26) 40%, rgb(13, 13, 13) 60%) !important;
	background-image: -webkit-linear-gradient(bottom, rgb(26, 26, 26) 40%, rgb(13, 13, 13) 60%) !important;  
}



/* SELECTED CATEGORY LINK BUTTON COLOR */
.status_selected
{
 	 background-color: rgb(26, 26, 26) !important;
	 background-image: none;
}

/* TOPBAR SEARCHBOX COLOR 
*/
#searchBox
{
   background-color: black !important;
   background-image: ;
   color: white !important;
}

/* HEADER COLORS */
.header_cw, .header_completed, .header_onhold, .header_dropped, .header_ptw
{
color: white;
}


/*  TOPBAR BUTTON TEXT COLOR */
.table_header a
{
color: silver;
}

/*  SELECTED CATEGORY LINK TEXT COLOR*/
.status_selected a
{
   color: silver;
}

   
/* UNSELECTED CATEGORY LINK TEXT COLOR  */
.status_not_selected a 
{
    color: silver;
}

	
/* ANIME INFO BUBBLE COLOR */
.td1:first-of-type, .td2:first-of-type, .td1, .td2, .td1 a, .td2 a 
{
    color: silver;
}

/* ANIMETITLE COLOR  */
.animetitle
{
    color:  silver;
}

/* LINK TEXT AND TAGS TEXT ON HOVER */
a:hover, #mal_cs_listinfo a:hover, #mal_cs_links a:hover, #mal_cs_otherlinks a:hover 
{
	color: white !Important;
}


/* CATEGORY TOTALS COLOR, GRAND TOTALS COLOR, COPYRIGHT COLOR */
.category_totals,
#grand_totals,
#copyright 
{
   color: silver ;
}

#copyright a
{
color: white;
}

/*  HOVER EFFECT ON TITLES */	
#list_surround tab\le:nth-of-type(n+4):not(.header_cw):not(.header_completed):not(.header_onhold):not(.header_dropped):not(.header_ptw):hover 
{
	background-color: rgba(245, 132, 0, 0.2);
}



/*  MAX HEIGHT OF ANIME TITLES
Adjust this to make more or less height for the longer titles on your list.
*/

.animetitle 
{
    max-height: 34px !important;
}


/*  HEIGHT OF TAGS BOX
If you've turned Tags on for your list, you can adjust the height of the box your tags appear in here. 
Keep in mind you won't see tags for this list style unless you hover your cursor over the anime.
*/

.td1[width="125"], .td2[width="125"] 
{
    height: 80px !important;
}


/* POSITION OF CATEGORY BUTTONS
You move the buttons to the left or right with the amounts below. First code is for Currently Watching, then Completed, and so forth. 
*/
.status_not_selected:nth-of-type(1), .status_selected:nth-of-type(1) 
{
    left: 162px;
}
.status_not_selected:nth-of-type(2), .status_selected:nth-of-type(2)
{
    left: 357px;
}
.status_not_selected:nth-of-type(3), .status_selected:nth-of-type(3) 
{
    left: 489px;
}
.status_not_selected:nth-of-type(4), .status_selected:nth-of-type(4) 
{
    left: 603px;
}
.status_not_selected:nth-of-type(5), .status_selected:nth-of-type(5) 
{
    left: 722px;
}
.status_selected:nth-of-type(6) a:after, .status_not_selected:nth-of-type(6) a:after 
{
    left: 880px;
}



/*******************************
OTHER CODES, DON'T TOUCH UNLESS YOU KNOW WHAT YOU'RE DOING
*******************************/

#mal_cs_listinfo a, #mal_cs_links a, #mal_cs_otherlinks a,
.table_headerLink, .status_not_selected,
.header_cw, .header_completed, .header_onhold,
.header_dropped, .header_ptw,
.category_totals, #grand_totals, #copyright 
{
	background-color: rgb(26, 26, 26) !important;
	background-image: linear-gradient(top, rgb(26, 26, 26) 40%, rgb(13, 13, 13) 60%) !important;
	background-image: -o-linear-gradient(top, rgb(26, 26, 26) 40%, rgb(13, 13, 13) 60%) !important;
	background-image: -ms-linear-gradient(top, rgb(26, 26, 26) 40%, rgb(13, 13, 13) 60%) !important;
}
#mal_cs_listinfo a:hover, #mal_cs_links a:hover, #mal_cs_otherlinks a:hover,
.table_headerLink:hover, .status_not_selected:hover
{
	background-image: linear-gradient(bottom, rgb(26, 26, 26) 40%, rgb(13, 13, 13) 60%);
	background-image: -o-linear-gradient(bottom, rgb(26, 26, 26) 40%, rgb(13, 13, 13) 60%);
	background-image: -ms-linear-gradient(bottom, rgb(26, 26, 26) 40%, rgb(13, 13, 13) 60%);
}
.td1, .td2, .td1 a + small, .td2 a + small, .animetitle 
{
	background-color: rgba(13, 13, 13, 0.9);
	background: transparent linear-gradient(top, rgba(26, 26, 26, 0.9) 40%, rgba(13, 13, 13, 0.9) 60%);
	background: transparent -o-linear-gradient(top, rgba(26, 26, 26, 0.9) 40%, rgba(13, 13, 13, 0.9) 60%);
	background: transparent -ms-linear-gradient(top, rgba(26, 26, 26, 0.9) 40%, rgba(13, 13, 13, 0.9) 60%);
}
.animetitle:hover 
{
	background-image: linear-gradient(bottom, rgba(26, 26, 26, 0.9) 40%, rgba(13, 13, 13, 0.9) 60%);
	background-image: -o-linear-gradient(bottom, rgba(26, 26, 26, 0.9) 40%, rgba(13, 13, 13, 0.9) 60%);
	background-image: -ms-linear-gradient(bottom, rgba(26, 26, 26, 0.9) 40%, rgba(13, 13, 13, 0.9) 60%);
}

body 
{
	font-size: 11px;
	font-family: Verdana, Arial, Helvetica, sans-serif;
}

a 
{
	text-decoration: none;
}

#mal\_control\_strip 
{
	width: 77% !important;
	height: 120px;
	margin: auto !important;
	background: none !important;
}

#inlineContent 
{
	pointer-events: none;
	display: block !important;
	position: absolute;
	top: 0px;
	left: 0px;
	height: 420px;
	width: 100%;
	background-position: right;
	border-bottom-width: 42px;
	border-bottom-style: solid;
	z-index: -1;
}

#mal\_control\_strip tbody 
{
	position: absolute;
	top: 0px;
	width: 686px;
	height: 120px;
	border-radius: 0px 0px 13px 13px;
}

#mal\_control\_strip di\v 
{
	margin: 0px !important;
	font-size: 0px !important;
}

#mal_cs_pic, #mal_cs_listinfo, #mal_cs_links, #mal_cs_otherlinks 
{
	padding: 0px !important;
}

#mal_cs_pic, #mal_cs_listinfo, #mal_cs_links 
{
	border-right-style: none !important;
}

#mal_cs_pic 
{
	position: absolute;
	top: 11px;
	left: 11px;
}

#mal_cs_listinfo di\v a, #mal_cs_links di\v a, #mal_cs_otherlinks di\v a 
{
	display: block;
	position: absolute;
	top: 11px;
	width: 64px;
	height: 64px;
	line-height: 64px;
	overflow-x: auto;
	overflow-y: hidden;
	white-space: nowrap;
	letter-spacing: -1px;
	font-size: 0px;
	font-weight: bold;
	text-align: center;
	text-decoration: none;
	border-radius: 7px;
}

#mal_cs_listinfo di\v a:hover, #mal_cs_links di\v a:hover, #mal_cs_otherlinks di\v a:hover 
{
	font-size: 11px;
}

#mal_cs_listinfo div:first-of-type a {left: 11px;}
#mal_cs_listinfo div:last-of-type a {left: 86px;}
#mal_cs_links div:first-of-type a:first-of-type {left: 161px;}
#mal_cs_links div:last-of-type a:first-of-type {left: 236px;}
#mal_cs_links div:last-of-type a:last-of-type {left: 311px;}
#mal_cs_links div:first-of-type a:last-of-type,
#mal_cs_otherlinks div:first-of-type a {left: 386px;}
#mal_cs_otherlinks di\v a[href*="/forum/"],
#mal_cs_otherlinks di\v a[href*="/mangalist/"],
#mal_cs_otherlinks di\v a[href*="/animelist/"],
#mal_cs_otherlinks di\v a[href*="/login.php"] {left: 461px;}
#mal_cs_otherlinks di\v a[href*="/history/"],
#mal_cs_otherlinks di\v a[href*="/register.php"] {left: 536px;}
#mal_cs_otherlinks di\v a[href*="/panel.php?go=export"],
#mal_cs_otherlinks di\v a[href*="/shared"],
#mal_cs_otherlinks di\v a[href*="/modules.php?go=faq"] {left: 611px;}

#mal_cs_listinfo di\v a:before, #mal_cs_links di\v a:before, #mal_cs_otherlinks di\v a:before 
{
	position: absolute;
	top: 0px;
	left: 0px;
	width: 64px;
	height: 64px;
	content: "";
	background-position: center;
	background-repeat: no-repeat;
	background-size: 56px;
}

#mal_cs_listinfo di\v a:hover:before, #mal_cs_links di\v a:hover:before, #mal_cs_otherlinks di\v a:hover:before 
{
	content: none;
}

#mal_cs_powered 
{
	top: 86px !important;
	left: 461px;
	right: auto !important;
}

#mal_cs_powered img 
{
	display: none;
}

#searchBox 
{
	position: absolute;
	top: 0px;
	left: 0px;
	padding: 4px 7px;
	width: 200px !important;
	height: 15px;
	font-size: 11px !important;
	text-align: center;
	border: none;
	border-radius: 4px;
}

.header_cw + tab\le, .header_completed + tab\le, .header_onhold + tab\le,
.header_dropped + tab\le, .header_ptw + tab\le {
	position: absolute;
	top: 86px;
	width: 461px;
-layout: fixed;
	border-spacing: 11px 0px;
}

#list_surround tab\le:nth-of-type(n+4) ~ .header_cw + tab\le,
#list_surround tab\le:nth-of-type(n+4) ~ .header_completed + tab\le,
#list_surround tab\le:nth-of-type(n+4) ~ .header_onhold + tab\le,
#list_surround tab\le:nth-of-type(n+4) ~ .header_dropped + tab\le,
#list_surround tab\le:nth-of-type(n+4) ~ .header_ptw + tab\le{
	display: none;
}

.table_header 
{
	width: auto;
}

.table_header:first-of-type, .table_header:nth-of-type(n+6) 
{
	display: none;
}

.table_headerLink 
{
	display: block;
	padding: 4px 7px;
	height: 15px;
	text-align: center;
	border-radius: 4px;
}

#list_surround tab\le:first-of-type 
{
	width: auto;
}

.status_selected, .status_not_selected 
{
    border-radius: 7px;
    white-space: nowrap;
    width: auto;
}
.status_selected a, .status_not_selected a 
{
    border-radius: 13px 13px 0 0;
    border-spacing: 11px;
    display: block;
    font-size: 13px;
    font-weight: bold;
    line-height: 42px;
    padding: 0 22px;
}
.status_not_selected:nth-of-type(1), .status_selected:nth-of-type(1) 
{
    position: absolute;
    top: 410px;
}
.status_not_selected:nth-of-type(2), .status_selected:nth-of-type(2) 
{
    position: absolute;
    top: 410px;
}
.status_not_selected:nth-of-type(3), .status_selected:nth-of-type(3) 
{
    position: absolute;
    top: 410px;
}
.status_not_selected:nth-of-type(4), .status_selected:nth-of-type(4) 
{
    position: absolute;
    top: 410px;
}
.status_not_selected:nth-of-type(5), .status_selected:nth-of-type(5) 
{
    top: 410px;
    position: absolute;
}

.status_not_selected:nth-of-type(6), .status_selected:nth-of-type(6) 
{
    visibility: hidden;
}

.status_not_selected:nth-of-type(6) a:after 
{
    background: none repeat scroll 0 0 #FF0000;
    content: "All Anime";
    position: absolute;
    top: 410px;
    visibility: visible;
    background-color: #1A1A1A;
    border-radius: 6px;
    border-spacing: 11px;
    display: block;
    font-size: 13px;
    font-weight: bold;
    line-height: 42px;
    padding: 0 22px;
}

.status_selected:nth-of-type(6) a:after 
{
    background: none repeat scroll 0 0 #FFC0CB;
    content: "All Anime";
    position: absolute;
    top: 410px;
    visibility: visible;
    background-color: #1A1A1A;
    border-radius: 6px;
    border-spacing: 11px;
    display: block;
    font-size: 13px;
    font-weight: bold;
    line-height: 42px;
    padding: 0 22px;
}


.header_cw:before, .header_completed:before, .header_onhold:before, .header_dropped:before, .header_ptw:before
{
    content: "";
    display: block;
    height: 65%;
    left: 0;
    position: absolute;
    top: 0;
    width: 100%;
    z-index: -4;
}

.status_selected:nth-of-type(6) a:before 
{
    content: "";
    height: 65%;
    left: 0;
    position: absolute;
    top: 0;
    visibility: visible;
    width: 100%;
    z-index: -3;
}


.status_not_selected:nth-of-type(6):hover a:after 
{
	background-image: linear-gradient(bottom, rgb(26, 26, 26) 40%, rgb(13, 13, 13) 60%);
	background-image: -o-linear-gradient(bottom, rgb(26, 26, 26) 40%, rgb(13, 13, 13) 60%);
	background-image: -ms-linear-gradient(bottom, rgb(26, 26, 26) 40%, rgb(13, 13, 13) 60%);
}


#list_surround 
{
	width: 77%;
	min-width: 726px;
	margin: 406px auto 64px;
	padding: 11px 31px 42px 31px;
	border-radius: 42px;
}

.header_cw, .header_completed, .header_onhold,
.header_dropped, .header_ptw 
{
	clear: both;
	top: 31px;
	margin: 0px 0px 42px 0px;
	padding: 11px 0px;
	border-radius: 13px;
}

.header_title 
{
	padding-left: 242px;
	font-size: 22px;
	font-weight: bold;
	text-align: center;
}

#list_surround tab\le:nth-of-type(n+4):not(.header_cw):not(.header_completed):not(.header_onhold):not(.header_dropped):not(.header_ptw),
.hide 
{
	float: left;
	position: relative;
	width: 220px;
	height: 220px;
	margin: 11px;
	border-radius: 13px;
}

#list_surround tab\le:nth-of-type(n+4):not(.header_cw):not(.header_completed):not(.header_onhold):not(.header_dropped):not(.header_ptw) 
{
	z-index: 1;
}

.hide 
{
	display: block !important;
	margin-left: -231px;
	background-position: center -20px;
}

.td1, .td2 
{
	position: absolute;
	padding: 4px 7px;
	border-radius: 4px;
}

.td1:nth-of-type(2), .td2:nth-of-type(2) 
{
	visibility: hidden;
	padding: 0px;
	width: 100%;
	height: 100%;
}

.td1:first-of-type:before, .td2:first-of-type:before 
{
	content: "#";
}

.td1:first-of-type, .td2:first-of-type 
{
	top: 11px;
	left: 11px;
	width: 42px;
	z-index: 1;
}

.td1 a[title="Anime Information"] + small, .td2 a[title="Anime Information"] + small 
{
	display: block;
	visibility: visible;
	position: absolute;
	top: 11px;
	left: 82px;
	width: 43px;
	padding: 4px 7px;
	font-size: 11px;
	text-align: center;
	word-wrap: break-word;
	border-radius: 4px;
}

.td1:nth-of-type(4)[width="50"], .td2:nth-of-type(4)[width="50"] 
{
	top: 11px;
	right: 11px;
	width: 42px;
}

td[width="70"] + .td1:nth-of-type(5):before, [width="70"] + .td2:nth-of-type(5):before 
{
	content: "Volumes: ";
}

td[width="70"] + .td1:nth-of-type(5), td[width="70"] + .td2:nth-of-type(5) 
{
	top: 11px;
	right: 11px;
	width: auto;
	text-align: right;
}

.td1 a:not([title="Anime Information"]) + small, .td2 a:not([title="Anime Information"]) + small 
{
	display: block;
	visibility: visible;
	position: absolute;
	top: 41px;
	right: 11px;
	width: auto;
	padding: 4px 7px;
	font-size: 11px;
	text-align: right;
	border-radius: 4px;
}

.animetitle 
{
	display: block;
	visibility: visible;
	position: absolute;
	left: 11px;
	bottom: 41px;
	padding: 7px;
	width: 184px;
	max-height: 34px;
	overflow: hidden;
	text-align: center;
	font-size: 13px;
	font-weight: bold;
	border-radius: 7px;
}

.td1:nth-of-type(3):before, .td2:nth-of-type(3):before 
{
	content: "Score: ";
}

.td1:nth-of-type(3), .td2:nth-of-type(3) 
{
	left: 11px;
	bottom: 11px;
	width: auto;
	text-align: left;
}

td[width="50"] + .td1:nth-of-type(5):before, [width="50"] + .td2:nth-of-type(5):before 
{
	content: "Episodes: ";
}

td[width="50"] + .td1:nth-of-type(5), td[width="50"] + .td2:nth-of-type(5) 
{
	right: 11px;
	bottom: 11px;
	width: auto;
	text-align: right;
}

.td1:nth-of-type(4)[width="70"]:before, .td2:nth-of-type(4)[width="70"]:before 
{
	content: "Chapters: ";
}

.td1:nth-of-type(4)[width="70"], .td2:nth-of-type(4)[width="70"] 
{
	bottom: 11px;
	right: 11px;
	width: auto;
	text-align: right;
}

.td1:nth-of-type(n+6), .td2:nth-of-type(n+6) 
{
	display: none;
}

.td1[width="125"], .td2[width="125"] 
{
	left: 11px;
	top: 71px;
	width: 184px;
	height: 45px;
	overflow: auto;
}

#list_surround tab\le:hover .td1[width="125"],
#list_surround tab\le:hover .td2[width="125"] 
{
	display: block;
}

input[type=text] 
{
	width: 100%;
	text-align: right;
	border: none;
	border-radius: 4px;
}

input[value=Go] 
{
	display: none;
}

#list_surround .List_LightBox 
{
	display: block;
	visibility: visible;
	position: absolute;
	top: 0px;
	left: 0px;
	width: 100%;
	height: 100%;
	font-size: 0px;
}

.category_totals 
{
	padding: 0px 31px;
	text-align: center;
	white-space: pre-line;
	border-radius: 13px;
}

.category_totals:before 
{
	display: block;
	content: "Totals:";
	text-align: center;
	font-weight: bold;
}

#grand_totals, #copyright 
{
	clear: both;
	position: relative;
	top: 31px;
	padding: 11px 0px;
	text-align: center;
}

#grand_totals 
{
	margin-bottom: 22px;
	border-radius: 7px;
}

#copyright 
{
	margin-top: 0px !important;
	margin-bottom: 31px;
	border-radius: 13px;
}

#list_surround br 
{
	display: none;
}

.status_selected:nth-of-type(6) a:before 
{
    background-color: black !important;
}

#inlineContent 
{
background-color: transparent;
}

/* OTHER CODES
For adjusting the header behind the category buttons. There are different codes for the positioning depending on the screen size.
*/

/* Media query for devices above 1000px */
@media all and (min-device-width:1001px) 
{
#inlineContent:before 
{
    left: 15% !important;
    width: 850px !important;
}
}

/* Media query for devices above 1024px */
@media all and (min-device-width:1025px) 
{

#inlineContent:before 
{
    left: 12% !important;
    width: 873px !important;
}
}

/* Media query for devices above 1140px */
@media all and (min-device-width:1141px) 
{

#inlineContent:before 
{
    left: 12% !important;
    width: 858px !important;
}
}

/* Media query for devices above 1280px */
@media all and (min-device-width:1281px) 
{

#inlineContent:before 
{
    left: 10% !important;
    width: 880px !important;
}
}

/* Media query for devices above 1366px */
@media all and (min-device-width:1367px) 
{

#inlineContent:before 
{
    left: 10% !important;
    width: 873px !important;
}
}

/* Media query for devices above 1440px */
@media all and (min-device-width:1441px) 
{

#inlineContent:before 
{
    left: 10% !important;
    width: 855px !important;
}
}


/* Media query for devices above 1680px */
@media all and (min-device-width:1681px) 
{
#inlineContent:before 
{
    left: 8% !important;
    width: 885px !important;
}
}

/* Media query for devices above 1920px */
@media all and (min-device-width:1921px) 
{
#inlineContent:before 
{
    left: 7% !important;
    width: 873px !important;
}
}

#mal\_control\_strip #mal_cs_otherlinks strong
{
	margin: 0px !important;
	font-size: 0px !important;
}

#list_surround:before 
{
    border-radius: 0 0 13px 13px;
    height: 120px;
    top: 0;
    width: 700px;
    content: "";
    z-index: -2 !important;
    display: block;
    position: absolute !important;
    left: 11% !important;
}

#inlineContent:after 
{  
    content: "";
    display: block !important;
    height: 42px;
    left: 0;
    margin: auto;
    position: absolute;
    right: 0;
    top: 420px;
    width: 100%;
}

#inlineContent:before 
{    
    border-radius: 13px 13px 0 0;
    position: absolute;
    top: 398px;
    display: block !important;
    height: 63px;
    left: 11%;
    margin: auto;
    position: absolute;
   width: 858px;
    content: "";
}

.status_not_selected a 
{
    border-radius: 6px;
    color: ;
}

.status_not_selected a 
{
    border-radius: 6px;
}

#mal\_cs_otherlinks :nth-of-type(2) 
{
    margin-top: -40px;  
}

#mal_cs_otherlinks a[href*="/forum/"], #mal_cs_otherlinks a[href*="/mangalist/"], #mal_cs_otherlinks a[href*="/animelist/"], #mal_cs_otherlinks a[href*="/login.php"], #mal_cs_otherlinks di\v a[href*="/register.php"]
{
    margin-top: 0;
}

#list_surround tab\le:first-of-type 
{
    background-color: transparent;
}

.header_cw + tab\le, .header_completed + tab\le, .header_onhold + tab\le, .header_dropped + tab\le, .header_ptw + tab\le 
{
    background: none repeat scroll 0 0 transparent;
    border-spacing: 11px 0;
    left: 12%;
    margin-left: -7px;
    position: absolute;
    top: 86px;
    width: 461px;
}

@media all and (min-device-height:0px)
{
.header_cw:before,
.header_completed:before,
.header_onhold:before,
.header_dropped:before,
.header_ptw:before,
.status_selected:nth-of-type(6) a:before 
	{
       height: 450px;
	}
}

@media all and (min-device-height:550px)
{
.header_cw:before,
.header_completed:before,
.header_onhold:before,
.header_dropped:before,
.header_ptw:before,
.status_selected:nth-of-type(6) a:before
	{
       height: 440px;
	}
}

  @media all and (min-device-height:600px)
{
 .header_cw:before,
.header_completed:before,
.header_onhold:before,
.header_dropped:before,
.header_ptw:before,
.status_selected:nth-of-type(6) a:before
	{
       height: 430px;
	}
}

  @media all and (min-device-height:700px)
{
.header_cw:before,
.header_completed:before,
.header_onhold:before,
.header_dropped:before,
.header_ptw:before,
.status_selected:nth-of-type(6) a:before
	{
    height:420px;
	}
}

  @media all and (min-device-height:750px)
{
.header_cw:before,
.header_completed:before,
.header_onhold:before,
.header_dropped:before,
.header_ptw:before,
.status_selected:nth-of-type(6) a:before
	{
    height: 420px;
	}
}

  @media all and (min-device-height:800px)
{
.header_cw:before,
.header_completed:before,
.header_onhold:before,
.header_dropped:before,
.header_ptw:before,
.status_selected:nth-of-type(6) a:before
	{
       height: 420px;
	}
}

  @media all and (min-device-height:900px)
{
.header_cw:before,
.header_completed:before,
.header_onhold:before,
.header_dropped:before,
.header_ptw:before,
.status_selected:nth-of-type(6) a:before
{
@media all and (min-device-height:0px)
{
.header_cw:before,
.header_completed:before,
.header_onhold:before,
.header_dropped:before,
.header_ptw:before,
.status_selected:nth-of-type(6) a:before 
{
       height: 450px;
}
}

@media all and (min-device-height:550px)
{
.header_cw:before,
.header_completed:before,
.header_onhold:before,
.header_dropped:before,
.header_ptw:before,
.status_selected:nth-of-type(6) a:before
	{
       height: 440px;
	}
}

  @media all and (min-device-height:600px)
{
 .header_cw:before,
.header_completed:before,
.header_onhold:before,
.header_dropped:before,
.header_ptw:before,
.status_selected:nth-of-type(6) a:before
	{
       height: 430px;
	}
}

  @media all and (min-device-height:700px)
{
.header_cw:before,
.header_completed:before,
.header_onhold:before,
.header_dropped:before,
.header_ptw:before,
.status_selected:nth-of-type(6) a:before
	{
    height:420px;
	}
}

  @media all and (min-device-height:750px)
{
.header_cw:before,
.header_completed:before,
.header_onhold:before,
.header_dropped:before,
.header_ptw:before,
.status_selected:nth-of-type(6) a:before
	{
    height: 420px;
	}
}

  @media all and (min-device-height:800px)
{
.header_cw:before,
.header_completed:before,
.header_onhold:before,
.header_dropped:before,
.header_ptw:before,
.status_selected:nth-of-type(6) a:before
	{
       height: 420px;
	}
}

  @media all and (min-device-height:900px)
{
.header_cw:before,
.header_completed:before,
.header_onhold:before,
.header_dropped:before,
.header_ptw:before,
.status_selected:nth-of-type(6) a:before
	{
       height:420px;
	}
}

 @media all and (min-device-height:1000px)
{
.header_cw:before,
.header_completed:before,
.header_onhold:before,
.header_dropped:before,
.header_ptw:before,
.status_selected:nth-of-type(6) a:before
	{
       height: 420px;
	}
}



.header_cw, .header_completed, .header_onhold, .header_dropped, .header_ptw 
{
margin-top: -120px;
  visibility: hidden;
}

.header_cw:before, .header_completed:before, .header_onhold:before, .header_dropped:before, .header_ptw:before,  .header_cw:after, .header_completed:after, .header_onhold:after, .header_dropped:after, .header_ptw:after 
{
visibility: visible
}

 @media all and (min-device-height:1000px)
{
.header_cw:before,
.header_completed:before,
.header_onhold:before,
.header_dropped:before,
.header_ptw:before,
.status_selected:nth-of-type(6) a:before
	{
		   height: 420px;
	}
}

#mal_cs_listinfo a, #mal_cs_links a, #mal_cs_otherlinks a 
{
	overflow-x: hidden !important;
}

#mal\_control\_strip tbody {
    background-color: transparent !important;
}

#list_surround tab\le:nth-of-type(n+4):not(.header_cw):not(.header_completed):not(.header_onhold):not(.header_dropped):not(.header_ptw),
.hide {
	height: 300px !important;
}
.hide {
	background-position: center !important;
}
