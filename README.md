# gh
 body{margin: 0px;overflow-y:hidden;}  h1 {   font-size: 60px;   text-align: center;   color: #FFF; }  h3 {   font-size: 30px;   line-height: 34px;   text-align: center;   color: #FFF; }  a { color: #FFF; }  h1 {   margin-top: 100px;   text-align: center;   font-size: 60px;   line-height: 70px; }  #container {   margin: 0 auto;   max-width: 890px; }  p { xtext-align: center; }  .navtoggle,.toggle, [id^=drop] {  display: none; } .navcontainer{background: url(http://ninepanda.com/xmode/images/header_navbg.gif); height: 80px; border-top:#3db9e4 solid 4px;   z-index:99999;   position: absolute; /*newly added*/   top: 0px;/*newly added*/   width:100%;   zoom:100%; } nav {   margin: 0 auto;   padding: 0;   max-width:1120px; }  #logo {   display: block;   padding: 0 30px;   float: left;   font-size: 20px;   line-height: 60px;   margin-top:4px;   background: url("http://ninepanda.com/xmode/images/logo_weblong.png") no-repeat 28px 11px;   background-size: 88%;   width: 26%;   height: 56px; }  #logo img{display:none;}  nav:after {   content: "";   display: table;   clear: both; }  nav ul {   float: right;   padding: 0;   margin: 0;   list-style: none;   position: relative; }  nav ul li {   margin: 0px;    display: inline-block;   float: left;   xbackground-color: #254441;   color: #8f8f8f;   font-family: 'Open Sans Condensed', sans-serif;   text-transform: uppercase;   font-weight: bold;   xbackground: #e7e8e9;   xborder-left: 1px solid #bcbdbc;   -ms-transform: skewX(0deg); /* IE 9 */   -webkit-transform: skewX(0deg); /* Safari */   transform: skewX(0deg);   border-radius: 4px;  } nav ul li.dropdown{  margin-top: 10px;}  nav li{    position: relative; } nav li a {   display: block;   position: relative;   padding: 10px 20px;   color: #0088CC;   font-size: 15px;    text-decoration: none; } .nav > li > a:hover, .nav > li > a:focus {   text-decoration: none;   background-color: #eee; } .dropdown > li.active > a, .dropdown > li.active > a:hover, .dropdown > li.active > a:focus {   color: #fff;   background-color: #337ab7; } nav ul li ul li:hover { background: #000000; }  nav a:hover{   background: #3db9e4;   color: #FFF;   border-radius: 4px } nav li:hover a {   background: #3db9e4;   color: #FFF;   border-radius: 4px;   font-weight: 700; } nav li li a:hover{   color: #3db9e4;   background-color: #FFF; } nav ul ul {   display: none;   position: absolute;   top: 45px;    background: #3db9e4; }  nav ul li:hover > ul { display: inherit; }  nav ul ul li {   width: 270px;   float: none;   display: list-item;   position: relative; }  nav ul ul ul li {   position: relative;   top: -66px;   left: 170px; }  li > a:after { content: ' +'; }  li > a:only-child:after { content: ''; }  #limheight {     font-size: 0px;     max-height: 500px; /*your fixed height*/     -webkit-column-count: 3;        -moz-column-count: 3;             column-count: 3; /*3 in those rules is just placeholder -- can be anything*/ } #limheight li {     display: inline-block; /*necessary*/     width:200px;     font-size: 16px;      }    /* Media Queries --------------------------------------------- */  @media all and (max-width : 999px) { body{overflow-y: visible;} #logo {   display: block;   padding: 0;   width: 100%;   text-align: center;   float: none;   background:none; } #logo img{display: inline-block;}  nav { margin: 0; }  #limheight {     max-height:830px;     -webkit-column-count: 1;        -moz-column-count: 1;             column-count: 1; /*3 in those rules is just placeholder -- can be anything*/ } #limheight li {     display: inline-block; /*necessary*/     height: 20px;     width:100%;      } .toggle + a,  .navtoggle + a,  .menu { display: none; } .navtoggle {margin-top:-45px;      display: block;   background-color: ;   padding: 0 20px;   color: #FFF;   font-size: 20px;   line-height: 60px;   text-decoration: none;   border: none;   float:right;   }    .toggle {   display: block;   background-color: #3db9e4;   padding: 0 20px;   color: #FFF;   font-size: 20px;   line-height: 60px;   text-decoration: none;   border: none; }  .toggle:hover { background-color: #000000; }  [id^=drop]:checked + ul { display: block; }  nav ul {     float: initial;     margin-top:5px; } nav ul li.dropdown {     margin-top: 0px; } nav ul li.dropdown a{     background: #3db9e4;     color:#FFF; } nav ul li {   display: block;   width: 100%; }  nav ul ul .toggle,  nav ul ul a { padding: 0 40px; }  nav ul ul ul a { padding: 0 80px; }  nav a:hover,  nav ul ul ul a { background-color: #000000; }  nav ul li ul li .toggle,  nav ul ul a { background-color: #212121; }  nav ul ul {   float: none;   position: static;   color: #ffffff; }  nav ul ul li:hover > ul, nav ul li:hover > ul { display: none; }  nav ul ul li {   display: block;   width: 100%; }  nav ul ul ul li { position: static;  } }  @media all and (max-width : 330px) {  nav ul li {   display: block;   width: 94%; }  } @media (min-width: 992px) {   .navcontainer nav > ul > li.dropdown #limheight li, .navcontainer  nav > ul > li.dropdown .dropdown-mega-sub-nav li {     -webkit-transition: margin-top 0.2s ease;     -moz-transition: margin-top 0.2s ease;     transition: margin-top 0.2s ease;     -webkit-transform: translate3d(0, 0, 0);     -webkit-backface-visibility: hidden;     -webkit-perspective: 1000;     margin-top: -10px;   }    .navcontainer nav > ul > li.dropdown:hover > #limheight li, .navcontainer  nav > ul > li.dropdown:hover .dropdown-mega-sub-nav li {     margin-top: 0;   } }     html, body, div, span, applet, object, iframe, h1, h2, h3, h4, h5, h6, p, blockquote, pre, a, abbr, acronym, address, big, cite, code, button, del, dfn, em, font, img, ins, kbd, q, s, samp, small, strike, strong, sub, sup, tt, var, b, u, i, center, dl, dt, dd, ol, ul, li, fieldset, form, input, label, legend, textarea, table, caption, tbody, tfoot, thead, tr, th, td {   margin: 0;   padding: 0;   border: 0;   outline: 0;   font-size: 100%;   vertical-align: baseline;   background: transparent;   box-sizing: border-box; }  *, *:before, *:after {   box-sizing: inherit;   box-sizing: border-box; }  .wrap {   line-height: 1;   height: 100%; }  ol, ul {   list-style: none; }  blockquote, q {   quotes: none; }  blockquote:before, blockquote:after, q:before, q:after {   content: '';   content: none; }  /* remember to define focus styles! */ :focus {   outline: 0; }  /* remember to highlight inserts somehow! */ ins {   text-decoration: none; }  del {   text-decoration: line-through; }  /* tables still need 'cellspacing="0"' in the markup */ table {   border-collapse: collapse;   border-spacing: 0; }  textarea {   resize: none;   overflow: auto; }  html {   font-size: 62.5%; }  body {   font-size: 16px;   font-size: 1.6rem;   font-family: "Arimo", "Helvetica", "Arial", sans-serif !important;   -webkit-font-smoothing: antialiased;   text-rendering: optimizeLegibility;   color: #808080; }  h1 {   font-size: 28px;   font-size: 2.8rem;   font-weight: 600;   color: #4b4b4b;   margin-bottom: 20px;   padding-bottom: 20px;   border-bottom: 1px solid #dcdcdc;   letter-spacing: -1px;   line-height: 32px;   align-self: flex-start;   font-family: "Raleway", "Helvetica", "Arial", sans-serif; }  h2 {   font-size: 22px;   font-size: 2.2rem;   font-weight: 400;   color: #4b4b4b;   margin-bottom: 10px;   font-family: "Raleway", "Helvetica", "Arial", sans-serif;   margin-bottom: 20px;   padding-bottom: 20px;   border-bottom: 1px solid #dcdcdc;   letter-spacing: -1px; }  h3 {   font-size: 18px;   font-size: 2rem;   font-weight: 600;   color: #4b4b4b; }  h4 {   font-size: 18px;   font-size: 1.8rem;   color: #4b4b4b;   margin-bottom: 20px;   font-weight: 600; }  p {   margin-bottom: 5px;   line-height: 22px;   font-size: 16px;   font-size: 1.6rem;   color: #808080;   font-weight: 400; }  p a {   display: inline-block;   *display: inline;   *zoom: 1;   text-decoration: underline; }   p a:hover {     color: #3db9e4; }  span {   font-size: 16px;   font-size: 1.6rem;   color: #808080;   display: block; }  a {   color: #808080;   display: block;   text-decoration: none;   font-weight: 400;   font-size: 16px;   font-size: 1.6rem;   -webkit-transition: all 0.3s;   -o-transition: all 0.3s;   -moz-transition: all 0.3s;   -ms-transition: all 0.3s;   transition: all 0.3s; }   a:hover {     color: #d95459; }  ul {   font-size: 0; }  ul li, ol li {   font-size: 16px;   font-size: 1.6rem;   line-height: 28px; }  ul li a, button {   color: #808080;   font-size: 16px;   font-size: 1.6rem; }  i, input, td {   font-size: 16px;   font-size: 1.6rem; }  small {   font-size: 12px;   font-size: 1.2rem; }  textarea {   font-family: "Arimo", "Helvetica", "Arial", sans-serif; }  html {   min-height: 100%; }  .wrap {   max-width: 1020px;   display: block;   margin: 0 auto;   font-size: 0;   height: inherit; }  .inner-wrap {   padding: 2.94118%;   display: -webkit-box;   display: -moz-box;   display: -ms-flexbox;   display: -webkit-flex;   display: flex; }  .main-wrap {   background-color: #FFF; }  .secondary-wrap {   background-color: #ececee; }  i {   vertical-align: inherit;   margin-right: 5px; }   i:before {     vertical-align: top; }  .card {   background-color: #ffffff;   box-shadow: -10px 5px 20px 5px rgba(0, 0, 0, 0.05);   padding: 20px;   margin-bottom: 30px; } .card p,.card h3{color:#FFF;text-align: left;}  .flex-head {   justify-content: space-between;   border-bottom: 1px solid #dcdcdc; }  .nav {   display: -webkit-box;   display: -moz-box;   display: -ms-flexbox;   display: -webkit-flex;   display: flex;   align-items: center; }   .nav li a {     padding: 0 20px;     vertical-align: text-top; }     .nav li a i {       color: #d95459; }  .logo {   display: inline-block;   *display: inline;   *zoom: 1;   font-size: 0;   vertical-align: top;   text-align: center; }   .logo .title {     font-size: 40px;     font-size: 4rem;     font-family: "Raleway", "Helvetica", "Arial", sans-serif;     margin-bottom: .5rem;     color: #d95459;     text-shadow: -1px 1px 0px #d3373d; }  @media only screen and (max-width: 767px) {   .flex-head {     flex-wrap: wrap;     border: 0;     padding: 2.94118% 0; }    .logo {     margin: auto auto 20px;     border-bottom: 1px solid #dcdcdc;     width: 100%;     padding-bottom: 20px; }    .nav {     margin: auto;     flex-wrap: wrap;     text-align: center;     width: 100%; }     .nav li {       background: #d95459;       display: block;       width: 100%;       border-top: 1px solid #df7175;       border-bottom: 1px solid #d3373d; }       .nav li a {         color: #ffffff;         padding: 10px; }         .nav li a i {           color: #ffffff; } } .flex-main {   flex-wrap: wrap; }  .prod-img-cont {   max-width: 700px;   width: 73%;   vertical-align: top; }   .prod-img-cont > img {     box-shadow: -10px 5px 20px 5px rgba(0, 0, 0, 0.05);     width: 100%;     height: auto;     vertical-align: top;     margin-top: 0 !important; }  .gallery {   border: 0px solid #2b2b2b;   background-color: #FFFFFF;   position: relative; }   .gallery .img-group:hover .img-small div {     color: #2b2b2b; }   .gallery .img-small div, .gallery .img-large div {     background-color: #fff; }   .gallery .gal-cont {     width: 100%;     padding-top: 139.39%; }     .gallery .gal-cont .gal-cells {       width: 96.96%;       height: 83.46%; }     .gallery .gal-cont .img-small {       width: 16.60%;       height: 90px;       margin-top:10px}     .gallery .gal-cont .img-large {       width: 98.75%;       height: 82.29%;       margin: 0.62%; }     .gallery .gal-cont .img-small img {       max-width: 93.33%;       max-height: 93.33%; }     .gallery .gal-cont .img-large img {       max-width: 99.83%;       max-height: 99.83%; }   .gallery .gal {     position: relative;     margin: auto; }   .gallery .gal-cells {     position: absolute;     left: 0;     top: -13%;     bottom: 0;     right: 0;     margin: auto; }   .gallery img {     position: absolute;     width: auto;     height: auto;     left: 0;     top: 0;     bottom: 0;     right: 0;     margin: auto; }   .gallery .img-small {     position: relative;     overflow: hidden;     float: left;     display: block; }   .gallery .img-large {     position: absolute;     overflow: hidden;     display: none;     left: 0%;     top: 0%;     z-index: 1; }   .gallery .img-small div {     position: absolute;     left: 0%;     top: 0%;     right: 0%;     bottom: 0%; }   .gallery .img-small div:empty {    display: none;}   .gallery .img-large {     display: none; }     .gallery .img-large div {       position: absolute;       left: 0%;       top: 0%;       right: 0%;       bottom: 0%; }     .gallery .img-large.hero-img {       position: relative;       display: block;       float: left;       z-index: 0; }   .gallery .img-group:hover .img-small div {     border: 1px solid; }   .gallery .img-group:hover .img-large {     display: block;     left: 0%;     top: 0%; }  .prod-desc-cont {   max-width: 460px;   width: 27%;   padding-left: 0px; }  .desc span {   display: inline-block;   *display: inline;   *zoom: 1;   vertical-align: top;   font-weight: 600; } .desc div {   display: block;   vertical-align: top;   margin-bottom: 20px; } .desc .price {   font-size: 40px;   font-size: 4rem;   color: #d95459;   line-height: 0.8;   padding-left: 20px; } .desc .btn {   width: 48%;   padding: 10px;   background-color: #d95459;   display: inline-block;   *display: inline;   *zoom: 1;   color: #ffffff;   text-align: center; }   .desc .btn:first-of-type {     margin-right: 4%; }   .desc .btn:hover {     background-color: #d23339; }  .sellers {   width: 100%;   display: -webkit-box;   display: -moz-box;   display: -ms-flexbox;   display: -webkit-flex;   display: flex;   margin-top: 30px; }   .sellers .card {     display: -webkit-box;     display: -moz-box;     display: -ms-flexbox;     display: -webkit-flex;     display: flex;     align-items: center;     width: 32%;     margin: 0;     margin-right: 2%; }     .sellers .card:last-of-type {       margin-right: 0; }   .sellers i {     font-size: 39px;     font-size: 3.9rem;     margin-right: 20px;     color: #FFF;}   .sellers h3 {     margin-bottom: 10px; }   .sellers p {     display: inline-block;     *display: inline;     *zoom: 1;     min-height: 56px; } .features{ margin-top:20px;} .features ul {   padding-left: 0px;   padding-bottom:20px; }   .features ul li {     list-style: disc;margin-left: 20px;  }  .colours {   display: -webkit-box;   display: -moz-box;   display: -ms-flexbox;   display: -webkit-flex;   display: flex;   margin-bottom: 40px;   justify-content: space-around; }  .colours ul {     width: 100%;     display: flex;     flex-wrap: wrap; }  .colours span {     display: block;     padding: 10px;     margin-bottom: 10px;     background-color: #2d2d2d;     border-radius: 3px;     text-align: center;     color: white;     font-weight: bold; }  .colours li {     padding-right: 10px;     width: 25%; }  .colours span.red-temp{background-color:#E42528;} .colours span.blue-temp{background-color:#3498db;} .colours span.green-temp{background-color:#a5c63b;} .colours span.orange-temp{background-color:#ffa800;} .colours span.pink-temp{background-color:#f47cc3;} .colours span.watermelon-temp{background-color:#d95459;} .colours span.yellow-temp{background-color:#ffcd02;}  .half {     display: -webkit-box;     display: -moz-box;     display: -ms-flexbox;     display: -webkit-flex;     display: flex;     width: 100%;     margin-bottom: 40px; }  .item {   width: 50%; }  .item.img {     display: -webkit-box;     display: -moz-box;     display: -ms-flexbox;     display: -webkit-flex;     display: flex; }  .item iframe{ width:100%!important; height: 360px!important;  }  .item img {width: 350px;height: 350px;margin-left: auto;}  .inner-wrap.tabs p {     margin-bottom: 40px; }  @media only screen and (max-width: 767px) {   .prod-img-cont,   .prod-desc-cont {     max-width: 100%;     width: 100%;     display: block;     padding: 0; }    .prod-img-cont {     margin-bottom: 20px; }    .desc .btn {     width: 100%; }     .desc .btn:first-of-type {       margin-bottom: 10px;       margin-right: 0; } .card p,.card h3{text-align: center;}   .sellers {     flex-wrap: wrap;     text-align: center; }     .sellers .card {       width: 100%;       margin-bottom: 10px;       margin-right: 0;       justify-content: center; }     .sellers p {       min-height: auto; } }  .tabs {   float: none;   list-style: none;   padding-top: 0;   flex-wrap: wrap; }   .tabs:after {     content: '';     display: table;     clear: both; }   .tabs input[type=radio] {     display: none; }   .tabs label {     display: block;     float: left;     xwidth: 32%;     color: #3db9e4;     font-size: 30px;     font-size: 3rem;     text-align: center;     cursor: pointer;     -webkit-transition: all 0.3s;     -o-transition: all 0.3s;     -moz-transition: all 0.3s;     -ms-transition: all 0.3s;     transition: all 0.3s;     vertical-align: super;     padding: 10px 15px;     margin: 20px 5px;     border: 1px solid #ccc;     -webkit-box-sizing: border-box;     -moz-box-sizing: border-box;     box-sizing: border-box; }     .tabs label span {       display: inline-block;       *display: inline;       *zoom: 1;       vertical-align: text-top;       color: #3db9e4;       line-height: 2.5; }     .tabs label i {       padding: 5px;       vertical-align: bottom; }     .tabs label:hover, .tabs label:hover span {       color: #c9c9c9; }   .tabs h3 {     margin-bottom: 20px;     font-size: 24px;     font-size: 2.4rem; }  .tab-content {   display: none;   width: 100%;   float: left;   padding: 30px;   box-sizing: border-box;   border: 1.5px solid #E4E4E4;   background-color: #ffffff; }  .tab-content * {   -webkit-animation: scale 0.7s ease-in-out;   -moz-animation: scale 0.7s ease-in-out;   animation: scale 0.7s ease-in-out; }  @keyframes scale {   0% {     transform: scale(0.9);     opacity: 0; }   50% {     transform: scale(1.01);     opacity: 0.5; }   100% {     transform: scale(1);     opacity: 1; } } .tabs [id^="tab"]:first-child + label {margin-left:0px} .tabs [id^="tab"]:checked + label {   background: #3db9e4;   border: 1px solid #3db9e4;   color: #ffffff; }   .tabs [id^="tab"]:checked + label:hover, .tabs [id^="tab"]:checked + label:hover span {     color: #ffffff; }   .tabs [id^="tab"]:checked + label span {     color: #ffffff; }   #tab1:checked ~ #tab-content1, #tab2:checked ~ #tab-content2, #tab3:checked ~ #tab-content3, #tab4:checked ~ #tab-content4, #tab5:checked ~ #tab-content5{   display: block; }  .colours {   display: -webkit-box;   display: -moz-box;   display: -ms-flexbox;   display: -webkit-flex;   display: flex;   margin-bottom: 40px;   justify-content: space-around; }  .colours ul {     width: 100%;     display: flex;     flex-wrap: wrap; }  .colours span {     display: block;     padding: 10px;     margin-bottom: 10px;     background-color: #2d2d2d;     border-radius: 3px;     text-align: center;     color: white;     font-weight: bold; }  .colours li {     padding-right: 10px;     width: 25%; }  .colours span.red-temp{background-color:#E42528;} .colours span.blue-temp{background-color:#3498db;} .colours span.green-temp{background-color:#a5c63b;} .colours span.orange-temp{background-color:#ffa800;} .colours span.pink-temp{background-color:#f47cc3;} .colours span.watermelon-temp{background-color:#d95459;} .colours span.yellow-temp{background-color:#ffcd02;}  .half {     display: -webkit-box;     display: -moz-box;     display: -ms-flexbox;     display: -webkit-flex;     display: flex;     width: 100%;     margin-bottom: 40px; }  .item {   width: 50%; }  .item.img {     display: -webkit-box;     display: -moz-box;     display: -ms-flexbox;     display: -webkit-flex;     display: flex; }  .item iframe{ width:100%!important; height: 360px!important;  }  .item img {width: 350px;height: 350px;margin-left: auto;}  .inner-wrap.tabs p {     margin-bottom: 40px; }  @media only screen and (max-width: 767px) {   .colours li{     width:50%;   }   .item {     width: 100%; }   .item img {     display:none; }   .half {     flex-wrap: wrap;   }   .tabbers {     display: none !important; }    .tab-content {     display: block; } } footer {   background: #383838; }   footer .footer {     flex-wrap: wrap;     text-align: center; }   footer ul {     width: 100%;     display: -webkit-box;     display: -moz-box;     display: -ms-flexbox;     display: -webkit-flex;     display: flex;     justify-content: center;     margin-bottom: 50px; }     footer ul a {       padding: 0 20px;       vertical-align: text-bottom;       color: #3db9e4; }       footer ul a:hover {         color: #388bd1; }   footer .footer-nav {     border-bottom: 1px solid #808080;     padding-bottom: 2.94118%; }   footer .contact li {     display: -webkit-box;     display: -moz-box;     display: -ms-flexbox;     display: -webkit-flex;     display: flex; }     footer .contact li a {       color: #d95459; }   footer .copyright {     width: 100%; }     footer .copyright a {       color: #3db9e4; }       footer .copyright a img {         vertical-align: middle; }  @media only screen and (max-width: 767px) {   footer ul {     flex-wrap: wrap;     text-align: center; }     footer ul li {       width: 100%;       margin-bottom: 10px; }       footer ul li:last-of-type {         margin-bottom: 0; }    footer .contact li {     justify-content: space-between; } }  .forestGreen {     background: #7fc242; } .orange {     background: #ff8a3c; } .dodgerBlue {     background: #388bd1; }
