# H5
HTML5, HyperText Markup Lang

#---------------------------------------------------------------------------------

# Add-on

* Doctype

* Head

* Paragraph

* Text Format


      (1) <mark></mark>, hightlight

      (2) <b></b>, bold

      (3) <i></i>, italic

      (4) <u></u>, underline

      (5) <abbr></abbr>
      
      (6) <s></s>, stricken
      
      (7) <ins></ins>, insert
      
      (8) <sup></sup>, <sub></sub>, super script & sub script
      
* Anchor

       <a href="http://google.com/">Link to Google</a>
       
#---------------------------------------------------------------------------------

# Run-JS-Script, 腳本注入

       <a href="javascript:myFunction();">Run Code</a>

       <a href="#" onclick="myFunction(); return false;">Run Code</a>
  
* Able
       
      <script>
       document.write("Hello, world!");
      </script>

* Disable

      <noscript> This browser does not support Javascript. </noscript>
       
#---------------------------------------------------------------------------------

# Run-Mail-Client

       <a href="mailto:XXX@gmail.com"> Send Me a Mail </a>
       
#---------------------------------------------------------------------------------

# OrderList-View

       <ol start="01"> 
           <li> name: queen <li>
           <li> likes: H5 <li>
           <li> favorites: React<li>   
       </ol>
       
#---------------------------------------------------------------------------------

# Table-View

2 rows * 3 col
col == td

      <table>
      
            <tr>
                <td></td>
                <td></td>
                <td></td>
            </tr>
            
            <tr>
                <td></td>
                <td></td>
                <td></td>
            </tr>
            
      </table>
      
#---------------------------------------------------------------------------------

# Menu-View (with Seletion Ops)


      
#---------------------------------------------------------------------------------

# Id, Identifier

* Class Id called Class

Classes are id for the elements that they are assigned to. Use the class attribute to assign a class to an element.

            <div class="class_name"></div>

* Style Sheet Id called id

The ID attr of an element is an identifier which must be unique in the whole document. Its purpose is to uniquely identify the element when linking (using an anchor), scripting, or styling (with CSS).

            <div id="example-id"></div>

#---------------------------------------------------------------------------------

# Favicon

Use the mime-type image/png for PNG files and image/x-icon for icon (*.ico) files. 

A file named favicon.ico at the root of developers website will typically be loaded and applied automatically, without the need for a <link> tag. 

If this file ever changes, browsers can be slow and stubborn about updating their cache.

#---------------------------------------------------------------------------------

# CSS (internal, inline)

Multiple internal stylesheets can be included in a program as well.

* internal CSS

            <head>
            <link rel="stylesheet" type="text/css" href="stylesheet.css">
            </head>
            
* link to Bootstrap

            <head>
            <link rel="stylesheet"
            href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384- BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous"> 
            </head>
 
 * inline CSS
 
            <head>
                 <style type="text/css">
                        body {
                              background-color: gray;
                        }
                 </style>
            </head>
            
#---------------------------------------------------------------------------------

# SO ON...

* Input

  * Form (submit, upload)

  * Image

  * Other useful element:

    * div
    
    * nav
    
    * label
    
* Output

   * Media
   
   * Void
   
* Progress

if browser supports, then

      <progress> </progress>

else

      <div class="progress-bar">
            <span style="width: 20%;">Progress: 20%</span> 
      </div>
    
            
            
