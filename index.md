---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Database
permalink: /
---
<style>
  /* Common custom components between Main Site and Notes: Searchbar, Backbutton, ContentBox, Related Posts/Notes, Copyright,  */

.searchbar input[type="text"] {
    position: relative;
    padding-left: 50px;
    box-sizing : border-box;
    width: 100%;
    height: 40px;
    font-family:  Inter, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif !important;
    color: #555;
    font-size: 18px;
    border-bottom: 1px solid #f8f9fa;
    background: #fff;
    display: flex;
    border: 1px solid #dfe1e5;
    box-shadow: none;
    border-radius: 24px;
    margin: 0 auto;
}

::placeholder {
    color: #999;
    font-size: 18px;
    font-family:  Inter, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif !important;
}
.searchbar i {
    position: absolute;
    vertical-align: middle;
    margin-top: -2px;
    padding-left: 20px;
    color: #888; 
    padding-top: 12.5px;
    z-index: 1;
}
  
.searchbar input[type="text"]:focus {
    border-color: #f8f9fa;
    box-shadow: 0 0 8px 0 #A7D0EB;
}
  
.searchbar input[type=text]:hover {
    background-color: white;
}
  
.searchbar input[type=text]:active,
.searchbar input[type=text]:focus {
    background-color: white;
    outline: none;
} 

.search_res {
    padding-left: 10px;
}

.search_res:hover {
 background-color: #f4f4f4;
}

.search_res:hover > a {
    font-weight: 600;
}
  </style>
