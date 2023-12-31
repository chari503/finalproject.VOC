<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog Platform</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }

        .blog-post {
            max-width: 800px;
            margin: 0 auto;
        }

        h2, h3 {
            color: #333;
        }

        ul, ol {
            margin-bottom: 20px;
        }

        pre {
            background-color: #f4f4f4;
            padding: 10px;
            border: 1px solid #ddd;
            overflow-x: auto;
        }

        .title {
            color: #228B22;
            font-family: Candara;
        }
    </style>
</head>
<body>
    <div class="blog-post">
        <h2>About HTML</h2>
        <p>HTML (Hyper Text Markup language) is the standard markup language for Web pages, created by Berners-Lee in the year 1991. Almost every web page over the internet might be using HTML.</p>

        <h2>Syntax help</h2>
        <h3>Fundamentals</h3>
        <ul>
            <li>Any HTML document must start with document declaration &lt;!DOCTYPE html&gt;</li>
            <li>HTML documents begin with &lt;html&gt; and end with &lt;/html&gt;</li>
            <li>Headings are defined with &lt;h1&gt; to &lt;h6&gt;, where &lt;h1&gt; is the highest important heading and &lt;h6&gt; is the least important sub-heading.</li>
            <li>Paragraphs are defined in &lt;p&gt;..&lt;/p&gt; tag.</li>
            <li>Links are defined in &lt;a&gt; tag.</li>
            <li>Images are defined in &lt;img&gt; tag, where src attribute consists of the image name.</li>
            <li>Buttons are defined in &lt;button&gt;..&lt;/button&gt; tag.</li>
        </ul>

        <h3>HTML Elements and Attributes</h3>
        <ul>
            <li>HTML element is everything present from start tag to end tag.</li>
            <li>The text present between start and end tag is called HTML element content.</li>
            <li>Anything can be a tag name, but it's preferred to put the meaningful title to the content present as the tag name.</li>
            <li>Do not forget the end tag.</li>
            <li>Elements with no content are called empty elements.</li>
            <li>Elements can have attributes which provide additional information about the element.</li>
            <li>In the below example, href is an attribute and a is the tag name.</li>
        </ul>

        <h2>CSS</h2>
        <p>CSS (cascading style sheets) describe how HTML elements will look on the web page, like color, font-style, font-size, background color, etc.</p>

        <h3>Example:</h3>
        <pre>
            body {
                padding: 25px;
            }
            .title {
                color: #228B22;
                font-family: Candara;
            }
        </pre>

        <h2>HTML Tables</h2>
        <p>HTML Tables are defined in &lt;table&gt; tag. Table row should be defined in &lt;tr&gt; tag, table header should be defined in &lt;th&gt; tag, and table data should be defined in &lt;td&gt; tag. Table caption should be defined in &lt;caption&gt; tag.</p>

        <h2>HTML-Javascript</h2>
        <p>Javascript is used in HTML pages to make them more interactive. &lt;script&gt; is the tag used to write scripts in HTML. You can either reference an external script or write script code in this tag.</p>

        <h3>Example:</h3>
        <pre>
            &lt;script src="script.js"&gt;&lt;/script&gt;
        </pre>
    </div>
</body>
</html>
