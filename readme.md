<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01//EN"
<html>
<head>
    <title>My first Styled page</title>
    <style type="text/css">
        body {
            padding-left: 11em;
            font-family: Georgia, "Times New Roman", Times, serif;
          color: purple;
          background-color: #d8da3d }
          ul.navbar {
            list-style-type: none;
            padding: 0;
             margin: 0;
        position: absolute;
        top: 2em;
        left: 1em;
        width: 9em }
          h1 {
              font-family: Helvetica, Geneva, Arial, Sunsans-regular, sans-serif}
              ul.navbar li {
                background: white;
                margin: 0.5em 0;
                 padding: 0.3em;
                border-right: 1em solid black }
             ul.navbar a {
                 text-decoration: none }
            a:link {
                color: blue }
            a:visited {
                color: purple }
             address {
                    margin-top: 1em;
                    padding-top: 1em;
                    border-top: thin dotted }
        </style>
</head>

<body>
    <!-- Site navigation menu -->
<ul class="navbar">
    <li><a href="index.html">Home page</a>
    <li><a href="musings.html">Musings</a>
    <li><a href="town.html">My town</a>
    <li><a href="links.html">Links</a>
  </ul>
  
  <!-- Main content -->
  <h1>My first styled page</h1>
  
  <p>Welcome to my styled page!
  
  <p>It lacks images, but at least it has style.
  And it has links, even if they don't go
  anywhere&hellip;
  
  <p>There should be more here, but I don't know
  what yet.
  
  <!-- Sign and date the page, it's only polite! -->
  <address>Made 17 May 2022<br>
    by myself.</address>

</body>
</html>