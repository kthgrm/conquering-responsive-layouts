# INSTRUCTION
    1. Limit the total width of
        the .intro-content to about half
        of its parent

    2. Stop the text from overflowing
        out the bottom at small screen
        widths

    You may modify the HTML if needed

# CODE TO FIX
```css
    * {
    box-sizing: border-box;
    }
    
    body {
    margin: 0;
    font-family: sans-serif;
    }
    
    .container {
    background: #23424a;
    color: white;
    
    width: 80%;
    margin: 0 auto;
    
    padding: 2em;
    height: 300px;
    }
 ```

# SOLUTION
 ```css
    * {
    box-sizing: border-box;
    }

    body {
    margin: 0;
    font-family: sans-serif;
    }

    .container {
    background: #23424a;
    color: white;

    width: 80%;
    margin: 0 auto;

    padding: 2em;
    }

    .intro-content{
        width: 50%;
    }
 ```
