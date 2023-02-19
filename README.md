<!DOCTYPE html>
<!-- saved from url=(0038)https://react-blog-website.vercel.app/ -->
<html lang="en">
<head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<link rel="icon" href="https://react-blog-website.vercel.app/favicon.ico">
<meta name="viewport" content="width=device-width,initial-scale=1">
<meta name="theme-color" content="#000000">
<meta name="description" content="Web site created using create-react-app">
<link rel="apple-touch-icon" href="https://react-blog-website.vercel.app/logo192.png">
<link rel="manifest" href="https://react-blog-website.vercel.app/manifest.json">
<title>SEO generated Blog Website</title>
<link href="./React App_files/2.829c9cb5.chunk.css" rel="stylesheet">
<link href="./React App_files/main.5edbe5f8.chunk.css" rel="stylesheet">
<style type="text/css">
.keyword-info-container {
  box-sizing: border-box;
  width: 100%;
  margin-bottom: 20px;
  font-size: 12px;
  border-bottom: 1px solid #dee1e5;
}

.keyword-info-container.youtube {
  margin-bottom: 0;
  border-bottom: none;
}

.keyword-info-container .title {
  color: #26282d;
  font-size: 17px;
  font-weight: bold;
}

.keyword-info-container .tabs {
  list-style: none;
  display: flex;
  justify-content: flex-start;
  border-bottom: 1px solid #dee1e5;
  margin-top: -10px;
  padding: 0px 16px;
  align-items: center;
}
.keyword-info-container .tabs li {
  padding: 8px;
  padding-left: 0;
  color: #000;
  cursor: pointer;
  font-size: 12px;
}
.keyword-info-container .tabs li.small {
  font-size: 10px;
}
.keyword-info-container .tabs li:last-child {
  overflow: hidden;
}

.keyword-info-container .tabs li.active {
  color: #4285f4;
}

table.keyword-info-table {
  border-collapse: collapse;
  width: 100%;
  color: #000;
  font-size: 12px;
  position: relative;
}

.keyword-info-table thead {
  height: 50px;
}

.keyword-info-table th {
  padding: 10px;
  padding-left: 0;
  font-weight: bold;
  color: #000000;
  font-size: 12px;
}

.keyword-info-table th:first-child {
  padding-left: 16px;
}

.keyword-info-table th:last-child {
  padding-right: 16px;
}

.keyword-info-table td {
  border-bottom: 1px solid #dee1e5;
  padding: 10px;
  padding-left: 0;
  height: 50px;
  box-sizing: border-box;
}

.keyword-info-table td:first-child {
  padding-left: 16px;
}

.keyword-info-table td:last-child {
  padding-right: 16px;
}

.keyword-info-table tfoot tr {
  background-color: #dee1e544;
}

.keyword-info-table tfoot tr:last-child td {
  border-bottom: none;
}

.ubersuggest-button {
  color: #0086f7;
  font-family: Arial;
  font-size: 14px;
  font-weight: bold;
  line-height: 29px;
  padding: 8px 30px;
  border: 1px solid #0086f7;
  background-color: #ffffff;
  border-radius: 2px;
  outline: none;
  border: none;
  cursor: pointer;
  margin: 4px;
}

.ubersuggest-logo-wrapper {
  display: flex;
  align-items: center;
  justify-content: flex-end;
  margin: 10px 10px 0 0;
  font-weight: bold;
  color: #26282d;
}

.ubersuggest-logo {
  width: 182px;
  height: 33px;
  cursor: pointer;
}

.keyword-info-container .row {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin: 0;
  padding: 20px 16px;
  border-top: 1px solid #dee1e5;
}

.header h2 {
  color: #000000;
  font-family: Geomanist;
  font-size: 24px;
  font-weight: 500;
}

/*
Youtube Dark theme styling
*/
html[dark] .keyword-info-container .title {
  color: #fff;
}

html[dark] .keyword-info-container .tabs {
  border-color: #ffffff0d;
}

html[dark] .keyword-info-container .tabs li {
  color: #fff;
}

html[dark] .keyword-info-container .tabs li.active {
  color: #4285f4;
}

html[dark] table.keyword-info-table {
  color: #fff;
}

html[dark] .keyword-info-table th {
  color: #fff;
}

html[dark] .keyword-info-table tfoot tr {
  background-color: #3d3d3d;
}

html[dark] .keyword-info-table tfoot tr:last-child td .button-arrow {
  border-color: #fff;
}

.keyword-info-table tfoot tr:last-child td .button-arrow.disabled {
  border-color: #9b9b9b !important;
}

/*
Google Dark theme styling
*/

body[data-dt='1'] .keyword-info-container .title {
  color: #fff;
}

body[data-dt='1'] .keyword-info-container .tabs {
  border-color: #ffffff0d;
}

body[data-dt='1'] .keyword-info-container .tabs li {
  color: #fff;
}

body[data-dt='1'] .keyword-info-container .tabs li.active {
  color: #4285f4;
}

body[data-dt='1'] table.keyword-info-table {
  color: #fff;
}

body[data-dt='1'] .keyword-info-table th {
  color: #fff;
}

body[data-dt='1'] .keyword-info-table tfoot tr {
  background-color: #3d3d3d;
}

body[data-dt='1'] .keyword-info-table tfoot tr:last-child td .button-arrow {
  border-color: #fff;
}
</style><style type="text/css">.tippy-box[data-theme~='transparent'] {
  background-color: transparent;
  background-clip: padding-box;
  border: none;
  color: #333;
  box-shadow: none;
}
.tippy-box[data-theme~='transparent'] > .tippy-backdrop {
  background-color: transparent;
}
.tippy-box[data-theme~='transparent'] > .tippy-arrow:after,
.tippy-box[data-theme~='transparent'] > .tippy-svg-arrow:after {
  content: '';
  position: absolute;
  z-index: -1;
}
.tippy-box[data-theme~='transparent'] > .tippy-arrow:after {
  border-color: transparent;
  border-style: solid;
}
.tippy-box[data-theme~='transparent'][data-placement^='top']
  > .tippy-arrow:before {
  border-top-color: transparent;
}
.tippy-box[data-theme~='transparent'][data-placement^='top']
  > .tippy-arrow:after {
  border-top-color: transparent;
  border-width: 7px 7px 0;
  top: 17px;
  left: 1px;
}
.tippy-box[data-theme~='transparent'][data-placement^='top']
  > .tippy-svg-arrow
  > svg {
  top: 16px;
}
.tippy-box[data-theme~='transparent'][data-placement^='top']
  > .tippy-svg-arrow:after {
  top: 17px;
}
.tippy-box[data-theme~='transparent'][data-placement^='bottom']
  > .tippy-arrow:before {
  border-bottom-color: transparent;
  bottom: 16px;
}
.tippy-box[data-theme~='transparent'][data-placement^='bottom']
  > .tippy-arrow:after {
  border-bottom-color: transparent;
  border-width: 0 7px 7px;
  bottom: 17px;
  left: 1px;
}
.tippy-box[data-theme~='transparent'][data-placement^='bottom']
  > .tippy-svg-arrow
  > svg {
  bottom: 16px;
}
.tippy-box[data-theme~='transparent'][data-placement^='bottom']
  > .tippy-svg-arrow:after {
  bottom: 17px;
}
.tippy-box[data-theme~='transparent'][data-placement^='left']
  > .tippy-arrow:before {
  border-left-color: transparent;
}
.tippy-box[data-theme~='transparent'][data-placement^='left']
  > .tippy-arrow:after {
  border-left-color: transparent;
  border-width: 7px 0 7px 7px;
  left: 17px;
  top: 1px;
}
.tippy-box[data-theme~='transparent'][data-placement^='left']
  > .tippy-svg-arrow
  > svg {
  left: 11px;
}
.tippy-box[data-theme~='transparent'][data-placement^='left']
  > .tippy-svg-arrow:after {
  left: 12px;
}
.tippy-box[data-theme~='transparent'][data-placement^='right']
  > .tippy-arrow:before {
  border-right-color: transparent;
  right: 16px;
}
.tippy-box[data-theme~='transparent'][data-placement^='right']
  > .tippy-arrow:after {
  border-width: 7px 7px 7px 0;
  right: 17px;
  top: 1px;
  border-right-color: transparent;
}
.tippy-box[data-theme~='transparent'][data-placement^='right']
  > .tippy-svg-arrow
  > svg {
  right: 11px;
}
.tippy-box[data-theme~='transparent'][data-placement^='right']
  > .tippy-svg-arrow:after {
  right: 12px;
}
.tippy-box[data-theme~='transparent'] > .tippy-svg-arrow {
  fill: transparent;
}
.tippy-box[data-theme~='transparent'] > .tippy-svg-arrow:after {
  /* background-image: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTYiIGhlaWdodD0iNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48cGF0aCBkPSJNMCA2czEuNzk2LS4wMTMgNC42Ny0zLjYxNUM1Ljg1MS45IDYuOTMuMDA2IDggMGMxLjA3LS4wMDYgMi4xNDguODg3IDMuMzQzIDIuMzg1QzE0LjIzMyA2LjAwNSAxNiA2IDE2IDZIMHoiIGZpbGw9InJnYmEoMCwgOCwgMTYsIDAuMikiLz48L3N2Zz4=); */
  background-size: 16px 6px;
  width: 16px;
  height: 6px;
}
</style>
<style type="text/css">
.tippy-box[data-animation=fade][data-state=hidden]{opacity:0}[data-tippy-root]{max-width:calc(100vw - 10px)}
.tippy-box{position:relative;background-color:#333;color:#fff;border-radius:4px;font-size:14px;line-height:1.4;outline:0;transition-property:transform,visibility,opacity}
.tippy-box[data-placement^=top]>
.tippy-arrow{bottom:0}
.tippy-box[data-placement^=top]>
.tippy-arrow:before{bottom:-7px;left:0;border-width:8px 8px 0;border-top-color:initial;transform-origin:center top}
.tippy-box[data-placement^=bottom]>
.tippy-arrow{top:0}
.tippy-box[data-placement^=bottom]>
.tippy-arrow:before{top:-7px;left:0;border-width:0 8px 8px;border-bottom-color:initial;transform-origin:center bottom}
.tippy-box[data-placement^=left]>
.tippy-arrow{right:0}
.tippy-box[data-placement^=left]>
.tippy-arrow:before{border-width:8px 0 8px 8px;border-left-color:initial;right:-7px;transform-origin:center left}.tippy-box[data-placement^=right]>
.tippy-arrow{left:0}
.tippy-box[data-placement^=right]>
.tippy-arrow:before{left:-7px;border-width:8px 8px 8px 0;border-right-color:initial;transform-origin:center right}
.tippy-box[data-inertia][data-state=visible]{transition-timing-function:cubic-bezier(.54,1.5,.38,1.11)}
.tippy-arrow{width:16px;height:16px;color:#333}
.tippy-arrow:before{content:"";position:absolute;border-color:transparent;border-style:solid}
.tippy-content{position:relative;padding:5px 9px;z-index:1}</style><style type="text/css">
.tippy-box[data-theme~=light]{color:#26323d;box-shadow:0 0 20px 4px rgba(154,161,177,.15),0 4px 80px -8px rgba(36,40,47,.25),0 4px 4px -2px rgba(91,94,105,.15);background-color:#fff}
.tippy-box[data-theme~=light][data-placement^=top]>
.tippy-arrow:before{border-top-color:#fff}
.tippy-box[data-theme~=light][data-placement^=bottom]>
.tippy-arrow:before{border-bottom-color:#fff}
.tippy-box[data-theme~=light][data-placement^=left]>
.tippy-arrow:before{border-left-color:#fff}
.tippy-box[data-theme~=light][data-placement^=right]>
.tippy-arrow:before{border-right-color:#fff}
.tippy-box[data-theme~=light]>
.tippy-backdrop{background-color:#fff}
.tippy-box[data-theme~=light]>
.tippy-svg-arrow{fill:#fff}
</style>
<style type="text/css">
.ubersuggest-header-container {
  box-sizing: border-box;
  width: 100%;
  font-size: 12px;
}

.ubersuggest-header-container .row {
  margin: 0;
  padding: 15px 16px 15px 16px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  min-height: 30px;
}

.ue-enable {
  display: block;
}

.ue-disable {
  display: none !important;
}

.ubersuggest-header-container .settings {
  display: flex;
  align-items: center;
  margin-right: 18px;
}
.ubersuggest-header-container .settings-label {
  margin-right: 21px;
}

.ubersuggest-header-container .settings-icon {
  width: 21px;
  height: 21px;
  margin-right: 7px;
}
</style><style type="text/css">.keyword-info-section {
  color: #26282d;
  font-family: Arial;
  font-size: 12px;
  padding: 8px 0 10px 8px;
  display: flex;
  align-items: center;
}

.keyword-info-section.hidden {
  display: none;
}

.keyword-info-section.google {
  background-color: #fff;
}

body[data-dt='1'] .keyword-info-section.google {
  background-color: #303134;
}

.keyword-info-section.youtube {
  margin-right: 15px;
  padding: 0 0 0 10px;
  height: 100%;
  background-color: #fff;
}

.keyword-info-section.amazon {
  padding: 13px 0;
  background-color: #fff;
}
</style><style type="text/css">.kw-overview-container {
  box-sizing: border-box;
  width: 673px;
  padding: 0;
  margin: 0;
  margin-top: 14px;
  font-size: 12px;
  font-family: Arial;
}
.kw-overview-container.youtube {
  box-sizing: border-box;
  width: 100%;
  padding: 0;
  margin: 0;
  font-size: 12px;
}
</style><style type="text/css">.bl-info-container {
  box-sizing: border-box;
  width: 100%;
  padding: 0;
  margin: 0;
  font-size: 12px;
}
.bl-info-header {
  display: flex;
  height: 24px;
  width: 100%;
  padding: 0;
  justify-content: space-between;
  cursor: pointer;
  box-sizing: border-box;
  margin-bottom: 5px;
}

.bl-info-header .row {
  display: flex;
  margin: 0;
  width: 100%;
  justify-content: space-between;
}

.bl-info-header .row.youtube {
  justify-content: flex-start;
}

.bl-info-content,
.kw-info-content {
  width: 100%;
  display: flex;
  flex-direction: column;
  border: 1px solid #dee1e5;
  border-radius: 8px;
  padding-top: 0;
}

body[data-dt='1'] .kw-info-content,
body[data-dt='1'] .bl-info-content {
  background: #2a2a2a;
  border-color: #2a2a2a;
}

.bl-info-content img.loading {
  width: 50px;
  margin: 0 auto;
  margin-bottom: 10px;
}

.kw-info-content img.loading {
  width: 50px;
  margin: 0 auto;
  margin-top: 10px;
  margin-bottom: 10px;
}

table.bl-info-table,
table.kw-info-table {
  border-collapse: collapse;
  width: 100%;
  color: #808185;
  font-size: 12px;
}

body[data-dt='1'] table.bl-info-table,
body[data-dt='1'] table.kw-info-table {
  color: #fff;
}

.bl-info-table thead,
.kw-info-table thead {
  height: 50px;
}

.bl-info-table tr,
.kw-info-table tr {
  width: 100%;
  max-width: 600px;
}

.bl-info-table th,
.kw-info-table th {
  padding: 10px;
  padding-left: 0;
  font-weight: bold;
  color: #000000;
  font-size: 11px;
  border-bottom: 1px solid #dee1e5;
}

body[data-dt='1'] .bl-info-table th,
body[data-dt='1'] .kw-info-table th {
  color: #fff;
}

.bl-info-table th:first-child,
.kw-info-table th:first-child {
  padding-left: 16px;
}

.bl-info-table th:last-child,
.kw-info-table th:last-child {
  border-right: none;
  padding-right: 16px;
}

.bl-info-table td,
.kw-info-table td {
  border-bottom: 1px solid #dee1e5;
  padding: 10px;
  padding-left: 0;
  max-width: 0;
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
  color: #000;
}

body[data-dt='1'] .bl-info-table td,
body[data-dt='1'] .kw-info-table td {
  color: #fff;
}

.bl-info-table td:first-child,
.kw-info-table td:first-child {
  border-left: none;
  padding-left: 16px;
}

.bl-info-table td:last-child,
.kw-info-table td:last-child {
  border-right: none;
  padding-right: 16px;
}

.bl-info-table tfoot tr:last-child td,
.kw-info-table tfoot tr:last-child td {
  border-bottom: none;
}

.bl-info-container .row {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-top: 10px;
  margin-bottom: 20px;
}
</style><style type="text/css">.statistics-graph-container {
  box-sizing: border-box;
  width: 100%;
  margin-bottom: 5px;
  font-size: 12px;
  padding: 0px 16px;
}

.statistics-graph-container .row {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin: 10px 0 20px 0;
}

.statistics-graph-container .row .title {
  color: #26282d;
  font-size: 17px;
  font-weight: bold;
}

.statistics-graph-container .tabs {
  list-style: none;
  display: flex;
  justify-content: flex-start;
  border-bottom: 1px solid #dee1e5;
  margin: 0 -16px;
  margin-bottom: 10px;
  margin-top: -10px;
  padding: 0px 16px;
}

.statistics-graph-container .tabs li {
  display: flex;
  align-items: center;
  padding: 8px 16px;
  color: #000;
  cursor: pointer;
  font-size: 13px;
  border-bottom: 3px solid transparent;
}

.statistics-graph-container .tabs li:first-child {
  margin-left: -16px;
}

.statistics-graph-container .tabs li.active {
  color: #4285f4;
  border-bottom: 3px solid #4285f4;
}

/* Google Dark Theme */
body[data-dt='1'] .statistics-graph-container .row .title {
  color: #fff;
}

body[data-dt='1'] .statistics-graph-container .tabs {
  border-bottom: 1px solid #dee1e5;
}

body[data-dt='1'] .statistics-graph-container .tabs li {
  color: #fff;
}

body[data-dt='1'] .statistics-graph-container .tabs li.active {
  color: #fff;
  border-bottom: 3px solid #fff;
}
</style>
</head>
<body>
<noscript>You need to enable JavaScript to run this app.</noscript>
<div id="root">
<div class="App">
<div class="navBar1">
<nav class="fixed-top d-flex justify-content-between navbar navbar-expand-md navbar-dark bg-dark">
<li class="nav-item">
<a class="text-white" href="https://www.heavytowingtampa.com/">Heavy Duty Towing Tampa</a></li>
<button aria-label="Toggle navigation" type="button" class="navbar-toggler" style="width: auto;"><span class="navbar-toggler-icon">
</span>
</button>
<div class="collapse navbar-collapse" style="color: white; width: auto;">
<ul class="ml-auto navbar-nav">
<li class="nav-item">
<a href="https://www.heavytowingtampa.com/">
<p class="m-2 text-white"> Authors</p>
</a>
</li>
<li class="nav-item"><a href="https://www.heavytowingtampa.com/services/"><p class="m-2 text-secondary"> Towing in tampa</p></a></li><li class="nav-item"><a href="https://www.heavytowingtampa.com/services/"><p class=" m-2 text-secondary"> heavy towing tampa</p></a></li></ul></div></nav></div>
<div>
<div class="container"><div class="row"><div class="col-12 col-sm-6 col-md-4"><div class="card specialCard mx-auto" style="width: 18rem; padding: 20px; background-color: rgb(246, 246, 246); border: none; margin: 15px;"><img src="./React App_files/Delpha Crist" class="card-img-top" alt="...">
<div class="card-body text-center"><h5 class="card-title text-black-50">Delpha Crist</h5><a class="btn btn-primary text-white font-weight-bold" id="0" href="https://react-blog-website.vercel.app/Profile/0">Click to view Profile</a></div></div></div><div class="col-12 col-sm-6 col-md-4"><div class="card specialCard mx-auto" style="width: 18rem; padding: 20px; background-color: rgb(246, 246, 246); border: none; margin: 15px;"><img src="./React App_files/Amya Satterfield" class="card-img-top" alt="..."><div class="card-body text-center"><h5 class="card-title text-black-50">Amya Satterfield</h5><a class="btn btn-primary text-white font-weight-bold" id="1" href="https://react-blog-website.vercel.app/Profile/1">Click to view Profile</a></div></div></div><div class="col-12 col-sm-6 col-md-4"><div class="card specialCard mx-auto" style="width: 18rem; padding: 20px; background-color: rgb(246, 246, 246); border: none; margin: 15px;"><img src="./React App_files/Santina Leannon" class="card-img-top" alt="..."><div class="card-body text-center"><h5 class="card-title text-black-50">Santina Leannon</h5><a class="btn btn-primary text-white font-weight-bold" id="2" href="https://react-blog-website.vercel.app/Profile/2">Click to view Profile</a></div></div></div><nav aria-label="Page navigation example"><ul class="pagination justify-content-center pagination-lg p-4"><li class="page-item disabled"><a class="page-link" href="https://react-blog-website.vercel.app/NaN">Previous</a></li><li class="page-item"><p class="page-link" style="background-color: black; color: white;">1</p></li><li class="page-item"><a class="page-link" href="https://react-blog-website.vercel.app/2">Next</a></li></ul></nav></div></div><div class="card-footer text-muted text-center font-weight-bolder p-5 m-2">Made with ♥ by Mohit Sojitra</div></div></div>
<script>!function(e){function r(r){for(var n,l,f=r[0],i=r[1],a=r[2],c=0,s=[];c<f.length;c++)l=f[c],Object.prototype.hasOwnProperty.call(o,l)&&o[l]&&s.push(o[l][0]),o[l]=0;for(n in i)Object.prototype.hasOwnProperty.call(i,n)&&(e[n]=i[n]);for(p&&p(r);s.length;)s.shift()();return u.push.apply(u,a||[]),t()}function t(){for(var e,r=0;r<u.length;r++){for(var t=u[r],n=!0,f=1;f<t.length;f++){var i=t[f];0!==o[i]&&(n=!1)}n&&(u.splice(r--,1),e=l(l.s=t[0]))}return e}var n={},o={1:0},u=[];function l(r){if(n[r])return n[r].exports;var t=n[r]={i:r,l:!1,exports:{}};return e[r].call(t.exports,t,t.exports,l),t.l=!0,t.exports}l.m=e,l.c=n,l.d=function(e,r,t){l.o(e,r)||Object.defineProperty(e,r,{enumerable:!0,get:t})},l.r=function(e){"undefined"!=typeof Symbol&&Symbol.toStringTag&&Object.defineProperty(e,Symbol.toStringTag,{value:"Module"}),Object.defineProperty(e,"__esModule",{value:!0})},l.t=function(e,r){if(1&r&&(e=l(e)),8&r)return e;if(4&r&&"object"==typeof e&&e&&e.__esModule)return e;var t=Object.create(null);if(l.r(t),Object.defineProperty(t,"default",{enumerable:!0,value:e}),2&r&&"string"!=typeof e)for(var n in e)l.d(t,n,function(r){return e[r]}.bind(null,n));return t},l.n=function(e){var r=e&&e.__esModule?function(){return e.default}:function(){return e};return l.d(r,"a",r),r},l.o=function(e,r){return Object.prototype.hasOwnProperty.call(e,r)},l.p="/";var f=this.webpackJsonpblog=this.webpackJsonpblog||[],i=f.push.bind(f);f.push=r,f=f.slice();for(var a=0;a<f.length;a++)r(f[a]);var p=i;t()}([])</script>
<script src="./React App_files/2.ba08cb1b.chunk.js.download"></script><script src="./React App_files/main.07be64a8.chunk.js.download"></script><div class="ue-sidebar-container"></div></body></html>
