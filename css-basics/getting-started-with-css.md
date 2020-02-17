# Inline & Internal Styles 

_New Video_

## Author Styles
<ol>
<li>Inline</li>
<li>Internal</li>
<li>External</li>
</ol>

``` <head>
      <title>Lake Tahoe</title>
        <style>
          p {
            font-size: 20px;
            font-weight: bold;
            }
           </style>
```
 <ul>       
    <li>Inline styles override internal styles</li>
</ul>

--------------------------------------------------------------------------------------------------------------------------------------

# External Style 

_New Video_

## External Stylesheet
<ul>
    <li>Can change the look of an entire wbesite with just one files</li>
    <li>.css tell the browser it is a stylesheet</li>
</ul>

<ul>
  <li>Link stylesheet to html with <i>link</i> in <i>head</i> tag</li>
</ul>

```
  <head>
    <title>Lake Tahoe</title>
      <link rel="stylesheet" href="css/style.css">
  </head>
```

--------------------------------------------------------------------------------------------------------------------------------------

# Import CSS with @import

_New Video_

```
<style>
  @import "/css/import-styles.css";
</style>
```

<ul>
  <li>Can add @import in a .css file at the top</li>
</ul>

```
@import "/css/import-styles.css"
```

<ul>
  <li>Can import multiple stylesheets but it can negatively impact loadspeed.</li>
</ul>

## Key Takeaways
<ol>
    <li>CSS is a stylesheet language that handles the presentation layer of a webpage.</li>
    <li>Most efficient way to add CSS to a page is with an external stylesheet.</li>
    <li>The .css file extension tells the browser the file is a stylesheet.</li>
    <li>Styles written in on style sheet can be shared accross multiple webpages.</li>
</ol>

