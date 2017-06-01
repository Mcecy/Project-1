<!-- First project for the Introduction to Programing course. -->

<!DOCTYPE HTML>
<html>
<head>
  <title>Cecilia's Notes</title>
</head>
<body>
  <h1><b>The basics of the web</b></h1>
  <br>
  <p>
    - <b>The Web</b>: what it is, what it looks like, how its major pieces fit together.<br>
    - <b>HTML</b>: main document type of the web.<br>
    - <b>URLs</b>: how you refer to documents on the web.<br>
    - <b>HTTP</b>: protocol that unites the web.<br>
    - <b>Web appplications</b>: what they are, how they fit into the big picture
  </p>
  <br>
  <p>
    The <b>World Wide Web</b> was invented in the early 1990s. It is a collection of HTML (<em>HyperText Markup Language</em>) documents, the basis for almost every webpage. Links between the pages are called hyperlinks.
  </p>
  <br>
  <h1>Major pieces of the web</h1>
  <br>
  <p>
    - <b>You</b><br>
    - Your computer +  Browser (<b>Client</b>)<br>
    - <b>The Internet</b><br>
    - <b>Servers</b>
  </p>
  <br>
  <p>
  Your computer (<b>Client</b>) makes requests via <b>internet</b> to the <b>servers</b>. These requests use a protocol called <b>HTTP</b> (<em>HyperText Tranfers Protocol</em>) and the <b>servers</b> respond with files that your browser displays.<br>
  <b>Servers</b> are computers just like yours, except they are optimized to be sitting in a closet, hosting files, instead of browsing files.
  </p>
  <br>
    <h2>HTML</h2>
    <br>
      <h3>MADE UP OF:</h3>
  <p>
    - <b>Text content</b>: what you see.<br>
    - <b>Markup</b>: what it looks like.<br>
    - <b>References to other documents</b>: images, music, etc.<br>
    - <b>Links to other pages</b>: hyperlinks.
    </p>
    <br>
    <h4>MARKUP</h4>
    <p>
    - Tags:<br>
    <br>
    <b>< opening tag ></b> <em>content</em> <b>< closing tag ></b> - Element (What we use to tell the browser how to show the content)<br>
    <br>
    <b>< b ></b> <em>content</em>  <b>< /b ></b> - Bold<br>
    <b>< em ></b> <em>content</em>  <b>< /em ></b> - Italic<br>
    <b>< a href="</b><em>value</em><b>" ></b> <em>content</em> <b>< /a ></b> - Links<br>
    <b>< img src="</b><em>URL</em><b>" alt="</b><em>text</em><b>" > [VOID TAG]</b> - Image<br>
    <b>< br > [VOID TAG]</b> - Break (multiple lines), applied after a line you want to break<br>
    <b>< p ></b> <em>content</em> <b>< /p ></b> - Paragraph<br>
    <b>< span ></b> <em>content</em> <b>< /span ></b> - Contains content in a line<br>
    <b>< div ></b> <em>content</em> <b>< /div ></b> - Contains content in a box
    </p>
    <br>
    <p>
    In <a href="https://www.youtube.com/watch?v=XscUH5_V6kw">this video</a> you have some tags and how they function.
    </p>
    <br>
    <b>Tip: Always put a closing tab when placing an opening tag so you do not forget it and cause problems.</b><br>
    <br>
    <h4>HTML ATTRIBUTES</h4>
    <br>
    <p>
    Tags can have attributes (<em>additional information for the browser</em>). These attributes have names (<em>attr</em>) that equal a value (<em>can be a URL</em>). Tags can have multiple attributes.<br>
    Ex:<br>
    <br>
    <b>< a ></b> <b>< /a ></b> - Anchor: makes links<br>
      <b>< a href="</b><em>http://www.reddit.com</em><b>" ></b> <em>derp</em> <b>< /a ></b><br>
      <b>< img src="</b><em>URL</em><b>" alt="</b><em>text</em><b>" > [NO CLOSING TAG]</b><br>
    </p>
    <br>
    <span>
    In <a href="https://www.youtube.com/watch?v=sKSx7QqTG3Q">here</a> you will see more about attributes.
    </span>
    <br>
    <p>
      <b>src</b>: source - <b>alt</b>: alternate text (text displayed when image doesnt load, for broken requests, for blind people)<br>
      <b>VOID TAGS</b>: Have no content, therefore, do not need closing tags.
      </p>
      <br>
    <h4>WHITESPACE</h4>
    <p>
      All whitespace, lines and tabs turn into a single line. To force the HTML to have multiple lines, we use a void tag called < br >. You apply it after a line you want to break.<br>
      Another tag you can use for breaking lines is called <b>< p ></b>.
    </p>
    <br>
    <h5>Why do we have < br > AND < p >?</h5>
    <p>
      <b>< br ></b> is what we call <em>INLINE</em> (It works in a line)<br>
      <b>< p ></b> is what we call <em>BLOCK</em> (It makes an invisible box)
    </p>
    <h5>SPAN AND DIV</h5>
    <p>
      <b>< span ></b> <em>content</em> <b>< /span ></b> is <em>INLINE</em> (creates a cointainer in a line)<br>
      <b>< div ></b> <em>content</em> <b>< /div ></b> is <em>BLOCK</em> (creates a container in a block)<br>
    </p>
    <br>
      If the concept of <b>< span ></b> and <b>< div ></b> is confusing to you, <a href="https://www.youtube.com/watch?v=G9k4-gDgTu8">this video</a> can help you understand it better.<br>
    <br>
    <h3>HTML DOCUMENT STRUCTURE</h3>
    <br>
        <img src="https://s-media-cache-ak0.pinimg.com/originals/c3/16/b8/c316b804abc25e9b1c509b1a96d5c9f6.jpg" alt="HTMl Structure: HTML-Head-Title-Body">
    <br>
    <br>
    <br>
    <br>
    Items <b>< h1 ></b>, <b>< h2 ></b>, until <b>< h6 ></b>, should be in indentation. Indentation indicates the beggining of a new concept, like items on a list that keeps deepening.<br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <b>BONUS KNOWLEDGE</b>: < !-- comments the computer ignores are written like this. Its just for people reading the code -- >
    <br>
    <br>
    <br>
    <br>
    <br>
</body>
</html>
