# CSS Spoiler Revealer Challenge

## Overview
This challenge involves creating a minimalist forum design where spoilers for famous movies are revealed on hover. The text is initially hidden with a blackout effect, and it gradually reveals the content upon mouse hover.

## Features
- Blackout effect on spoiler text.
- Smooth transition for revealing and hiding text.
- Responsive design that works well in various contexts.

## Spoiler Text
The spoilers used in this challenge are:
1. "the ruins of the Statue of Liberty. The Planet of the Apes is Earth!"
2. "is made of people!"
3. "Luke Skywalker's father!"

## HTML Structure
The HTML file contains multiple posts, each containing a spoiler text wrapped in a `<span>` with the class `spoiler`.

### Example HTML
```html
<!DOCTYPE html>
<html>
<head>
    <title>Spoiler Revealer</title>
    <link rel="stylesheet" href="main.css">
</head>
<body>
    <div class="post">
        <p>In the 1968 film Planet of the Apes, they find
            <span class="spoiler">the ruins of the Statue of Liberty. The Planet of the Apes is Earth!</span>
        </p>
    </div>
    <div class="post">
        <p>SoyLent Green
            <span class="spoiler">is made of people!</span>
        </p>    
    </div>
    <div class="post">
        <p>OMG I can't believe that Darth Vader is
            <span class="spoiler">Luke Skywalker's father!</span>
        </p>
    </div>
</body>
</html>