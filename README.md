
/* ::::: http://fxia.me/assets/css/bootstrap.min.css ::::: */

.clearfix::before, .clearfix::after { display: table; line-height: 0; content: ""; }
.clearfix::after { clear: both; }
article, aside, details, figcaption, figure, footer, header, hgroup, nav, section { display: block; }
audio:not([controls]) { display: none; }
html { font-size: 100%; }
a:focus { outline: thin dotted rgb(51, 51, 51); outline-offset: -2px; }
a:hover, a:active { outline: 0px none; }
sub, sup { position: relative; font-size: 75%; line-height: 0; vertical-align: baseline; }
sup { top: -0.5em; }
img { height: auto; max-width: 100%; vertical-align: middle; border: 0px none; }
button::-moz-focus-inner, input::-moz-focus-inner { padding: 0px; border: 0px none; }
@media print {
  * { color: rgb(0, 0, 0) ! important; text-shadow: none ! important; background: transparent none repeat scroll 0% 0% ! important; box-shadow: none ! important; }
  a, a:visited { text-decoration: underline; }
  a[href]::after { content: " (" attr(href) ")"; }
  abbr[title]::after { content: " (" attr(title) ")"; }
  .ir a::after, a[href^="javascript:"]::after, a[href^="#"]::after { content: ""; }
  pre, blockquote { border: 1px solid rgb(153, 153, 153); page-break-inside: avoid; }
  thead { display: table-header-group; }
  tr, img { page-break-inside: avoid; }
  img { max-width: 100% ! important; }
  @page { margin: 0.5cm; }
  p, h2, h3 {  }
  h2, h3 { page-break-after: avoid; }
}
body { margin: 0px; font-family: "Helvetica Neue",Helvetica,Arial,sans-serif; font-size: 14px; line-height: 20px; color: rgb(51, 51, 51); background-color: rgb(255, 255, 255); }
a { color: rgb(0, 136, 204); text-decoration: none; }
a:hover, a:focus { color: rgb(0, 85, 128); text-decoration: underline; }
.row { margin-left: -20px; }
.row::before, .row::after { display: table; line-height: 0; content: ""; }
.row::after { clear: both; }
[class*="span"] { float: left; min-height: 1px; margin-left: 20px; }
.container, .navbar-static-top .container, .navbar-fixed-top .container, .navbar-fixed-bottom .container { width: 940px; }
.span12 { width: 940px; }
.span9 { width: 700px; }
.span3 { width: 220px; }
.row-fluid::before, .row-fluid::after { display: table; line-height: 0; content: ""; }
.row-fluid::after { clear: both; }
.container { margin-right: auto; margin-left: auto; }
.container::before, .container::after { display: table; line-height: 0; content: ""; }
.container::after { clear: both; }
.container-fluid::before, .container-fluid::after { display: table; line-height: 0; content: ""; }
.container-fluid::after { clear: both; }
p { margin: 0px 0px 10px; }
.text-center { text-align: center; }
h1, h2, h3, h4, h5, h6 { margin: 10px 0px; font-family: inherit; font-weight: bold; line-height: 20px; color: inherit; text-rendering: optimizelegibility; }
h1, h2, h3 { line-height: 40px; }
h3 { font-size: 24.5px; }
h5 { font-size: 14px; }
ul, ol { padding: 0px; margin: 0px 0px 10px 25px; }
li { line-height: 20px; }
.dl-horizontal::before, .dl-horizontal::after { display: table; line-height: 0; content: ""; }
.dl-horizontal::after { clear: both; }
hr { margin: 20px 0px; border-width: 1px 0px; border-style: solid none; border-color: rgb(238, 238, 238) currentcolor rgb(255, 255, 255); -moz-border-top-colors: none; -moz-border-right-colors: none; -moz-border-bottom-colors: none; -moz-border-left-colors: none; border-image: none; }
blockquote small::before { content: "— "; }
blockquote.pull-right small::before { content: ""; }
blockquote.pull-right small::after { content: " —"; }
q::before, q::after, blockquote::before, blockquote::after { content: ""; }
.controls-row::before, .controls-row::after { display: table; line-height: 0; content: ""; }
.controls-row::after { clear: both; }
.form-actions::before, .form-actions::after { display: table; line-height: 0; content: ""; }
.form-actions::after { clear: both; }
.form-horizontal .control-group::before, .form-horizontal .control-group::after { display: table; line-height: 0; content: ""; }
.form-horizontal .control-group::after { clear: both; }
.table-striped tbody > tr:nth-child(2n+1) > td, .table-striped tbody > tr:nth-child(2n+1) > th { background-color: rgb(249, 249, 249); }
[class^="icon-"], [class*=" icon-"] { display: inline-block; width: 14px; height: 14px; margin-top: 1px; line-height: 14px; vertical-align: text-top; background-image: url('glyphicons-halflings.png'); background-position: 14px 14px; background-repeat: no-repeat; }
.icon-play { background-position: -264px -72px; }
.dropdown-submenu > a::after { display: block; float: right; width: 0px; height: 0px; margin-top: 5px; margin-right: -10px; border-color: transparent transparent transparent rgb(204, 204, 204); border-style: solid; border-width: 5px 0px 5px 5px; content: " "; }
.dropdown-submenu:hover > a::after { border-left-color: rgb(255, 255, 255); }
button.btn::-moz-focus-inner, input.btn[type="submit"]::-moz-focus-inner { padding: 0px; border: 0px none; }
.nav { margin-bottom: 20px; margin-left: 0px; list-style: outside none none; }
.nav > li > a { display: block; }
.nav > li > a:hover, .nav > li > a:focus { text-decoration: none; background-color: rgb(238, 238, 238); }
.nav-list { padding-right: 15px; padding-left: 15px; margin-bottom: 0px; }
.nav-list > li > a, .nav-list .nav-header { margin-right: -15px; margin-left: -15px; text-shadow: 0px 1px 0px rgba(255, 255, 255, 0.5); }
.nav-list > li > a { padding: 3px 15px; }
.nav-list [class^="icon-"], .nav-list [class*=" icon-"] { margin-right: 2px; }
.nav-tabs::before, .nav-pills::before, .nav-tabs::after, .nav-pills::after { display: table; line-height: 0; content: ""; }
.nav-tabs::after, .nav-pills::after { clear: both; }
.tabbable::before, .tabbable::after { display: table; line-height: 0; content: ""; }
.tabbable::after { clear: both; }
.navbar-inner::before, .navbar-inner::after { display: table; line-height: 0; content: ""; }
.navbar-inner::after { clear: both; }
.navbar-form::before, .navbar-form::after { display: table; line-height: 0; content: ""; }
.navbar-form::after { clear: both; }
.navbar .nav > li > .dropdown-menu::before { position: absolute; top: -7px; left: 9px; display: inline-block; border-right: 7px solid transparent; border-bottom: 7px solid rgba(0, 0, 0, 0.2); border-left: 7px solid transparent; content: ""; }
.navbar .nav > li > .dropdown-menu::after { position: absolute; top: -6px; left: 10px; display: inline-block; border-right: 6px solid transparent; border-bottom: 6px solid rgb(255, 255, 255); border-left: 6px solid transparent; content: ""; }
.navbar-fixed-bottom .nav > li > .dropdown-menu::before { top: auto; bottom: -7px; border-top: 7px solid rgba(0, 0, 0, 0.2); border-bottom: 0px none; }
.navbar-fixed-bottom .nav > li > .dropdown-menu::after { top: auto; bottom: -6px; border-top: 6px solid rgb(255, 255, 255); border-bottom: 0px none; }
.navbar .pull-right > li > .dropdown-menu::before, .navbar .nav > li > .dropdown-menu.pull-right::before { right: 12px; left: auto; }
.navbar .pull-right > li > .dropdown-menu::after, .navbar .nav > li > .dropdown-menu.pull-right::after { right: 13px; left: auto; }
.pager::before, .pager::after { display: table; line-height: 0; content: ""; }
.pager::after { clear: both; }
.modal-footer::before, .modal-footer::after { display: table; line-height: 0; content: ""; }
.modal-footer::after { clear: both; }
.popover .arrow, .popover .arrow::after { position: absolute; display: block; width: 0px; height: 0px; border-color: transparent; border-style: solid; }
.popover .arrow::after { border-width: 10px; content: ""; }
.popover.top .arrow::after { bottom: 1px; margin-left: -10px; border-top-color: rgb(255, 255, 255); border-bottom-width: 0px; }
.popover.right .arrow::after { bottom: -10px; left: 1px; border-right-color: rgb(255, 255, 255); border-left-width: 0px; }
.popover.bottom .arrow::after { top: 1px; margin-left: -10px; border-bottom-color: rgb(255, 255, 255); border-top-width: 0px; }
.popover.left .arrow::after { right: 1px; bottom: -10px; border-left-color: rgb(255, 255, 255); border-right-width: 0px; }
.thumbnails::before, .thumbnails::after { display: table; line-height: 0; content: ""; }
.thumbnails::after { clear: both; }
.media, .media-body { overflow: hidden; }
.media, .media .media { margin-top: 15px; }
.media:first-child { margin-top: 0px; }
.media > .pull-left { margin-right: 10px; }
.pull-right { float: right; }
.pull-left { float: left; }
/* ::::: http://fxia.me/assets/css/bootstrap-responsive.min.css ::::: */

.clearfix::before, .clearfix::after { display: table; line-height: 0; content: ""; }
.clearfix::after { clear: both; }
.visible-phone { display: none ! important; }
@media (min-width: 768px) and (max-width: 979px) {
  .hidden-desktop { display: inherit ! important; }
  .visible-desktop { display: none ! important; }
  .visible-tablet { display: inherit ! important; }
  .hidden-tablet { display: none ! important; }
}
@media (max-width: 767px) {
  .hidden-desktop { display: inherit ! important; }
  .visible-desktop { display: none ! important; }
  .visible-phone { display: inherit ! important; }
  .hidden-phone { display: none ! important; }
}
@media print {
  .visible-print { display: inherit ! important; }
  .hidden-print { display: none ! important; }
}
@media (min-width: 1200px) {
  .row { margin-left: -30px; }
  .row::before, .row::after { display: table; line-height: 0; content: ""; }
  .row::after { clear: both; }
  [class*="span"] { float: left; min-height: 1px; margin-left: 30px; }
  .container, .navbar-static-top .container, .navbar-fixed-top .container, .navbar-fixed-bottom .container { width: 1170px; }
  .span12 { width: 1170px; }
  .span11 { width: 1070px; }
  .span10 { width: 970px; }
  .span9 { width: 870px; }
  .span8 { width: 770px; }
  .span7 { width: 670px; }
  .span6 { width: 570px; }
  .span5 { width: 470px; }
  .span4 { width: 370px; }
  .span3 { width: 270px; }
  .span2 { width: 170px; }
  .span1 { width: 70px; }
  .offset12 { margin-left: 1230px; }
  .offset11 { margin-left: 1130px; }
  .offset10 { margin-left: 1030px; }
  .offset9 { margin-left: 930px; }
  .offset8 { margin-left: 830px; }
  .offset7 { margin-left: 730px; }
  .offset6 { margin-left: 630px; }
  .offset5 { margin-left: 530px; }
  .offset4 { margin-left: 430px; }
  .offset3 { margin-left: 330px; }
  .offset2 { margin-left: 230px; }
  .offset1 { margin-left: 130px; }
  .row-fluid { width: 100%; }
  .row-fluid::before, .row-fluid::after { display: table; line-height: 0; content: ""; }
  .row-fluid::after { clear: both; }
  .row-fluid [class*="span"] { display: block; float: left; width: 100%; min-height: 30px; margin-left: 2.5641%; box-sizing: border-box; }
  .row-fluid [class*="span"]:first-child { margin-left: 0px; }
  .row-fluid .controls-row [class*="span"] + [class*="span"] { margin-left: 2.5641%; }
  .row-fluid .span12 { width: 100%; }
  .row-fluid .span11 { width: 91.453%; }
  .row-fluid .span10 { width: 82.906%; }
  .row-fluid .span9 { width: 74.359%; }
  .row-fluid .span8 { width: 65.812%; }
  .row-fluid .span7 { width: 57.265%; }
  .row-fluid .span6 { width: 48.7179%; }
  .row-fluid .span5 { width: 40.1709%; }
  .row-fluid .span4 { width: 31.6239%; }
  .row-fluid .span3 { width: 23.0769%; }
  .row-fluid .span2 { width: 14.5299%; }
  .row-fluid .span1 { width: 5.98291%; }
  .row-fluid .offset12 { margin-left: 105.128%; }
  .row-fluid .offset12:first-child { margin-left: 102.564%; }
  .row-fluid .offset11 { margin-left: 96.5812%; }
  .row-fluid .offset11:first-child { margin-left: 94.0171%; }
  .row-fluid .offset10 { margin-left: 88.0342%; }
  .row-fluid .offset10:first-child { margin-left: 85.4701%; }
  .row-fluid .offset9 { margin-left: 79.4872%; }
  .row-fluid .offset9:first-child { margin-left: 76.9231%; }
  .row-fluid .offset8 { margin-left: 70.9402%; }
  .row-fluid .offset8:first-child { margin-left: 68.3761%; }
  .row-fluid .offset7 { margin-left: 62.3932%; }
  .row-fluid .offset7:first-child { margin-left: 59.8291%; }
  .row-fluid .offset6 { margin-left: 53.8462%; }
  .row-fluid .offset6:first-child { margin-left: 51.2821%; }
  .row-fluid .offset5 { margin-left: 45.2991%; }
  .row-fluid .offset5:first-child { margin-left: 42.735%; }
  .row-fluid .offset4 { margin-left: 36.7521%; }
  .row-fluid .offset4:first-child { margin-left: 34.188%; }
  .row-fluid .offset3 { margin-left: 28.2051%; }
  .row-fluid .offset3:first-child { margin-left: 25.641%; }
  .row-fluid .offset2 { margin-left: 19.6581%; }
  .row-fluid .offset2:first-child { margin-left: 17.094%; }
  .row-fluid .offset1 { margin-left: 11.1111%; }
  .row-fluid .offset1:first-child { margin-left: 8.54701%; }
  input, textarea, .uneditable-input { margin-left: 0px; }
  .controls-row [class*="span"] + [class*="span"] { margin-left: 30px; }
  input.span12, textarea.span12, .uneditable-input.span12 { width: 1156px; }
  input.span11, textarea.span11, .uneditable-input.span11 { width: 1056px; }
  input.span10, textarea.span10, .uneditable-input.span10 { width: 956px; }
  input.span9, textarea.span9, .uneditable-input.span9 { width: 856px; }
  input.span8, textarea.span8, .uneditable-input.span8 { width: 756px; }
  input.span7, textarea.span7, .uneditable-input.span7 { width: 656px; }
  input.span6, textarea.span6, .uneditable-input.span6 { width: 556px; }
  input.span5, textarea.span5, .uneditable-input.span5 { width: 456px; }
  input.span4, textarea.span4, .uneditable-input.span4 { width: 356px; }
  input.span3, textarea.span3, .uneditable-input.span3 { width: 256px; }
  input.span2, textarea.span2, .uneditable-input.span2 { width: 156px; }
  input.span1, textarea.span1, .uneditable-input.span1 { width: 56px; }
  .thumbnails { margin-left: -30px; }
  .thumbnails > li { margin-left: 30px; }
  .row-fluid .thumbnails { margin-left: 0px; }
}
@media (min-width: 768px) and (max-width: 979px) {
  .row { margin-left: -20px; }
  .row::before, .row::after { display: table; line-height: 0; content: ""; }
  .row::after { clear: both; }
  [class*="span"] { float: left; min-height: 1px; margin-left: 20px; }
  .container, .navbar-static-top .container, .navbar-fixed-top .container, .navbar-fixed-bottom .container { width: 724px; }
  .span12 { width: 724px; }
  .span11 { width: 662px; }
  .span10 { width: 600px; }
  .span9 { width: 538px; }
  .span8 { width: 476px; }
  .span7 { width: 414px; }
  .span6 { width: 352px; }
  .span5 { width: 290px; }
  .span4 { width: 228px; }
  .span3 { width: 166px; }
  .span2 { width: 104px; }
  .span1 { width: 42px; }
  .offset12 { margin-left: 764px; }
  .offset11 { margin-left: 702px; }
  .offset10 { margin-left: 640px; }
  .offset9 { margin-left: 578px; }
  .offset8 { margin-left: 516px; }
  .offset7 { margin-left: 454px; }
  .offset6 { margin-left: 392px; }
  .offset5 { margin-left: 330px; }
  .offset4 { margin-left: 268px; }
  .offset3 { margin-left: 206px; }
  .offset2 { margin-left: 144px; }
  .offset1 { margin-left: 82px; }
  .row-fluid { width: 100%; }
  .row-fluid::before, .row-fluid::after { display: table; line-height: 0; content: ""; }
  .row-fluid::after { clear: both; }
  .row-fluid [class*="span"] { display: block; float: left; width: 100%; min-height: 30px; margin-left: 2.76243%; box-sizing: border-box; }
  .row-fluid [class*="span"]:first-child { margin-left: 0px; }
  .row-fluid .controls-row [class*="span"] + [class*="span"] { margin-left: 2.76243%; }
  .row-fluid .span12 { width: 100%; }
  .row-fluid .span11 { width: 91.4365%; }
  .row-fluid .span10 { width: 82.8729%; }
  .row-fluid .span9 { width: 74.3094%; }
  .row-fluid .span8 { width: 65.7459%; }
  .row-fluid .span7 { width: 57.1823%; }
  .row-fluid .span6 { width: 48.6188%; }
  .row-fluid .span5 { width: 40.0552%; }
  .row-fluid .span4 { width: 31.4917%; }
  .row-fluid .span3 { width: 22.9282%; }
  .row-fluid .span2 { width: 14.3646%; }
  .row-fluid .span1 { width: 5.80111%; }
  .row-fluid .offset12 { margin-left: 105.525%; }
  .row-fluid .offset12:first-child { margin-left: 102.762%; }
  .row-fluid .offset11 { margin-left: 96.9613%; }
  .row-fluid .offset11:first-child { margin-left: 94.1989%; }
  .row-fluid .offset10 { margin-left: 88.3978%; }
  .row-fluid .offset10:first-child { margin-left: 85.6354%; }
  .row-fluid .offset9 { margin-left: 79.8343%; }
  .row-fluid .offset9:first-child { margin-left: 77.0718%; }
  .row-fluid .offset8 { margin-left: 71.2707%; }
  .row-fluid .offset8:first-child { margin-left: 68.5083%; }
  .row-fluid .offset7 { margin-left: 62.7072%; }
  .row-fluid .offset7:first-child { margin-left: 59.9447%; }
  .row-fluid .offset6 { margin-left: 54.1437%; }
  .row-fluid .offset6:first-child { margin-left: 51.3812%; }
  .row-fluid .offset5 { margin-left: 45.5801%; }
  .row-fluid .offset5:first-child { margin-left: 42.8177%; }
  .row-fluid .offset4 { margin-left: 37.0166%; }
  .row-fluid .offset4:first-child { margin-left: 34.2541%; }
  .row-fluid .offset3 { margin-left: 28.453%; }
  .row-fluid .offset3:first-child { margin-left: 25.6906%; }
  .row-fluid .offset2 { margin-left: 19.8895%; }
  .row-fluid .offset2:first-child { margin-left: 17.1271%; }
  .row-fluid .offset1 { margin-left: 11.326%; }
  .row-fluid .offset1:first-child { margin-left: 8.56354%; }
  input, textarea, .uneditable-input { margin-left: 0px; }
  .controls-row [class*="span"] + [class*="span"] { margin-left: 20px; }
  input.span12, textarea.span12, .uneditable-input.span12 { width: 710px; }
  input.span11, textarea.span11, .uneditable-input.span11 { width: 648px; }
  input.span10, textarea.span10, .uneditable-input.span10 { width: 586px; }
  input.span9, textarea.span9, .uneditable-input.span9 { width: 524px; }
  input.span8, textarea.span8, .uneditable-input.span8 { width: 462px; }
  input.span7, textarea.span7, .uneditable-input.span7 { width: 400px; }
  input.span6, textarea.span6, .uneditable-input.span6 { width: 338px; }
  input.span5, textarea.span5, .uneditable-input.span5 { width: 276px; }
  input.span4, textarea.span4, .uneditable-input.span4 { width: 214px; }
  input.span3, textarea.span3, .uneditable-input.span3 { width: 152px; }
  input.span2, textarea.span2, .uneditable-input.span2 { width: 90px; }
  input.span1, textarea.span1, .uneditable-input.span1 { width: 28px; }
}
@media (max-width: 767px) {
  body { padding-right: 20px; padding-left: 20px; }
  .navbar-fixed-top, .navbar-fixed-bottom, .navbar-static-top { margin-right: -20px; margin-left: -20px; }
  .container-fluid { padding: 0px; }
  .dl-horizontal dt { float: none; width: auto; clear: none; text-align: left; }
  .dl-horizontal dd { margin-left: 0px; }
  .container { width: auto; }
  .row-fluid { width: 100%; }
  .row, .thumbnails { margin-left: 0px; }
  .thumbnails > li { float: none; margin-left: 0px; }
  [class*="span"], .uneditable-input[class*="span"], .row-fluid [class*="span"] { display: block; float: none; width: 100%; margin-left: 0px; box-sizing: border-box; }
  .span12, .row-fluid .span12 { width: 100%; box-sizing: border-box; }
  .row-fluid [class*="offset"]:first-child { margin-left: 0px; }
  .input-large, .input-xlarge, .input-xxlarge, input[class*="span"], select[class*="span"], textarea[class*="span"], .uneditable-input { display: block; width: 100%; min-height: 30px; box-sizing: border-box; }
  .input-prepend input, .input-append input, .input-prepend input[class*="span"], .input-append input[class*="span"] { display: inline-block; width: auto; }
  .controls-row [class*="span"] + [class*="span"] { margin-left: 0px; }
  .modal { position: fixed; top: 20px; right: 20px; left: 20px; width: auto; margin: 0px; }
  .modal.fade { top: -100px; }
  .modal.fade.in { top: 20px; }
}
@media (max-width: 480px) {
  .nav-collapse { transform: translate3d(0px, 0px, 0px); }
  .page-header h1 small { display: block; line-height: 20px; }
  input[type="checkbox"], input[type="radio"] { border: 1px solid rgb(204, 204, 204); }
  .form-horizontal .control-label { float: none; width: auto; padding-top: 0px; text-align: left; }
  .form-horizontal .controls { margin-left: 0px; }
  .form-horizontal .control-list { padding-top: 0px; }
  .form-horizontal .form-actions { padding-right: 10px; padding-left: 10px; }
  .media .pull-left, .media .pull-right { display: block; float: none; margin-bottom: 10px; }
  .media-object { margin-right: 0px; margin-left: 0px; }
  .modal { top: 10px; right: 10px; left: 10px; }
  .modal-header .close { padding: 10px; margin: -10px; }
  .carousel-caption { position: static; }
}
@media (max-width: 979px) {
  body { padding-top: 0px; }
  .navbar-fixed-top, .navbar-fixed-bottom { position: static; }
  .navbar-fixed-top { margin-bottom: 20px; }
  .navbar-fixed-bottom { margin-top: 20px; }
  .navbar-fixed-top .navbar-inner, .navbar-fixed-bottom .navbar-inner { padding: 5px; }
  .navbar .container { width: auto; padding: 0px; }
  .navbar .brand { padding-right: 10px; padding-left: 10px; margin: 0px 0px 0px -5px; }
  .nav-collapse { clear: both; }
  .nav-collapse .nav { float: none; margin: 0px 0px 10px; }
  .nav-collapse .nav > li { float: none; }
  .nav-collapse .nav > li > a { margin-bottom: 2px; }
  .nav-collapse .nav > .divider-vertical { display: none; }
  .nav-collapse .nav .nav-header { color: rgb(119, 119, 119); text-shadow: none; }
  .nav-collapse .nav > li > a, .nav-collapse .dropdown-menu a { padding: 9px 15px; font-weight: bold; color: rgb(119, 119, 119); border-radius: 3px; }
  .nav-collapse .btn { padding: 4px 10px; font-weight: normal; border-radius: 4px; }
  .nav-collapse .dropdown-menu li + li a { margin-bottom: 2px; }
  .nav-collapse .nav > li > a:hover, .nav-collapse .nav > li > a:focus, .nav-collapse .dropdown-menu a:hover, .nav-collapse .dropdown-menu a:focus { background-color: rgb(242, 242, 242); }
  .navbar-inverse .nav-collapse .nav > li > a, .navbar-inverse .nav-collapse .dropdown-menu a { color: rgb(153, 153, 153); }
  .navbar-inverse .nav-collapse .nav > li > a:hover, .navbar-inverse .nav-collapse .nav > li > a:focus, .navbar-inverse .nav-collapse .dropdown-menu a:hover, .navbar-inverse .nav-collapse .dropdown-menu a:focus { background-color: rgb(17, 17, 17); }
  .nav-collapse.in .btn-group { padding: 0px; margin-top: 5px; }
  .nav-collapse .dropdown-menu { position: static; top: auto; left: auto; display: none; float: none; max-width: none; padding: 0px; margin: 0px 15px; background-color: transparent; border: 0px none; border-radius: 0px; box-shadow: none; }
  .nav-collapse .open > .dropdown-menu { display: block; }
  .nav-collapse .dropdown-menu::before, .nav-collapse .dropdown-menu::after { display: none; }
  .nav-collapse .dropdown-menu .divider { display: none; }
  .nav-collapse .nav > li > .dropdown-menu::before, .nav-collapse .nav > li > .dropdown-menu::after { display: none; }
  .nav-collapse .navbar-form, .nav-collapse .navbar-search { float: none; padding: 10px 15px; margin: 10px 0px; border-top: 1px solid rgb(242, 242, 242); border-bottom: 1px solid rgb(242, 242, 242); box-shadow: 0px 1px 0px rgba(255, 255, 255, 0.1) inset, 0px 1px 0px rgba(255, 255, 255, 0.1); }
  .navbar-inverse .nav-collapse .navbar-form, .navbar-inverse .nav-collapse .navbar-search { border-top-color: rgb(17, 17, 17); border-bottom-color: rgb(17, 17, 17); }
  .navbar .nav-collapse .nav.pull-right { float: none; margin-left: 0px; }
  .nav-collapse, .nav-collapse.collapse { height: 0px; overflow: hidden; }
  .navbar .btn-navbar { display: block; }
  .navbar-static .navbar-inner { padding-right: 10px; padding-left: 10px; }
}
@media (min-width: 980px) {
  .nav-collapse.collapse { height: auto ! important; overflow: visible ! important; }
}
/* ::::: http://fxia.me/assets/css/feixia.css ::::: */

.logo-image { max-width: 75%; height: auto; overflow: hidden; }
