# Reading Notes on CSS and Formatting

Notes are from the following web pages:
-[What is CSS?](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS)
-[How to add CSS?](https://www.w3schools.com/css/css_howto.asp)
-[CSS color property](https://www.w3schools.com/cssref/pr_text_color.asp)
-[CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)
-[CSS Tools:Reset CSS](https://meyerweb.com/eric/tools/css/reset/)

I think that I write too much, so this should be a *quick* summary of the above five articles on CSS - which I had no idea stood for **C**ascading **Style** **S**heets. If you been following my other reading notes, then what I'm about to write will make sense to you. In a nutshell, CSS is what you use to add the style and pzazz to your html structure that you've created for your webpage. CSS allows you to create that unique vibe to your page by adding in different fonts, backgrounds, borders, text styles and sizes. 

If you've not been following my reading notes then, in the most basic way, HTML is what creates the body and content of your webpage (skeleton, bones, muscles, organs, etc.) and CSS is what creates the clothing, make-up, and hair - the style of your webpage, essentially.

## Using CSS
Once you've created the body of your webpage with HTML, you then have to style it with CSS and there were three ways that the reading said you can style your webpage, using CSS:

1.External CSS
1.Internal CSS
1.Inline CSS

Essentially, they are exactly what they sound like. If you are using an external CSS file, that means you are creating a new file for your webpage - that you've already structured with HTML - and that file has to have the css extension, so the file name will be something like `webpagestylefile.css` (having the right file extension is super important). Then, in your HTML file, you have to reference this css file, in the `<head></head>` portion of your code. You'll use the link tag and then reference your file, so it will look something like this:

`<head>`
    `<link rel="stylesheet" href="webpagestylefile.css">`
`</head>`

If you are going to use Internal CSS, that means that you are putting what they call a style section into the head portion of your HTML file. That would look something like this:

`<head>`
    `<style>`
        "Insert CSS coding here"
    `</style>`
`</head>`

Finally, if you want to use Inline CSS, that means that you will add the style you want for your HTML, in-line with the your coding. So, for example, if you wanted to style a certain paragraph in font yellow and font size, this is what you would code into your html file:

`<p style = "color: yellow; font-size: 11px;">`
    This is a paragraph with yellow text and font size 11.
`</p>`

## Coding CSS
Last, but not least, how to actually code CSS - which is probably the second most important part. CSS is very different from HTML because instead of using tags like HTML - open and closing tags for a paragraph for reference --> `<p></p>`) CSS uses what they call a *selector* followed by curly brackets {} and then what they call *declarations* inside the selector. These declarations define a *property* and then the *value* of that property. How it works is that the selector chooses an element or section inside your HTML file that you are then going to modify, or style, with your CSS file. So, if I wanted to style all of the second level headings in my html file, this is what I would code in my CSS file:

`h2 {`
    `color: red;`
    `text-align: center;`
    `font-family: cursive;`
`}`

So now, all of the second level headings on my webpage would be red, centered on the page and cursive.

There's my quick recap of the readings(:

[Back to Reading Notes](README.md)