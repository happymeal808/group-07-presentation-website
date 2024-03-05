Hey, welcome to our README. 😸
  
Our code represents the utilization of markdown as a whole.
Due to it's simplistic nature, markdown is a scripting language that can be utilized to format HTML and text based applications. 

---

# ![markdown logo](images/markdown-50.png) Markdown

* [What is it?](#what-is-Markdown)
* [What does it do?](#what-does-it-do)
* [Why use it?](#why-should-you-even-use-it)
* [Where to use it?](#where-can-you-use-it)
* [Pros & Cons](#pros-vs-cons)
* [Code Demo](#code-demo)
* [Tools & Resources](#tools-and-resources)

---

## What is Markdown?

To put it plainly, Markdown is a lightweight markup language used to format plaintext text documents. It was created in 2004 by John Gruber. Gruber's primary goal in his design was to create an unobtrusive and readable text formatter, even in it's source-code form. In comparison to HTML, Markdown should be thought of as a writing tool, and HTML as the publishing format.

## What does it do?

Markdown is an ecosystem of tools that lets you complete a variety of tasks like creating an HTML page, taking notes, writing a novel, or to even create a slide presentation. Utilizing markdown can lead to a higher efficiency in everyday tasks and the simplistic syntax makes markdown a efficient tool to quickly get your ideas down and implemented. Markdown's simplistic syntax and utilization makes it easy to learn and adapt to one's coding knowledge base. Markdown is a useful tool for any developer when it comes to formatting a README.md on Github, or to simply comment on a Reddit post.

## Why should you even use it?

### Convenience:

Markdown can be easier to read, write and edit for many people, especially for simple formatting tasks like creating headers, lists, or emphasis.

### Integration:

Sometimes, Markdown processors are integrated into systems or frameworks that primarily use HTML. This allows users to write content in Markdown, which is then converted to HTML behind the scenes for rendering.

### Consistency:

Markdown can help maintain consistency across content created by different authors since it enforces a specific formatting syntax.

## Where can you use it?

### Websites:

Markdown is good for text-heavy sites such as blogs. It is also often used on websites that contain a lot of user input such as Reddit and GitHub.

### Documents & Notes:

Markdown is good for text-heavy sites such as blogs. It is also often used on websites that contain a lot of user input such as Reddit and GitHub.

### Email:

Some email providers support Markdown. You can also write an email in Markdown and export it to your email client or install a browser extension.

## Pros vs Cons

### Pros:

* Files containing markdown can be opened using any application, whereas say a Microsoft word document locks content to a proprietary file format.
* You can create markdown-formatted text with any operating system.
* It is future proof. Unlike PDFs or Word Documents, .md files are readable even when not properly rendered.

### Cons:

* Markdown is not standardized. There is no specification or authority for Markdown. Different implementations of Markdown may have different behaviors or interpretations of the syntax. This can lead to inconsistencies across dfferent platforms and tools.
* Due to it's minimalistic design, it is limited in it's functionality. It does not natively support footnotes, tables of content, citations, mathematical equations, charts, diagrams, and more. That being said, with a little bit of internet connection, it is possible to use links to utilize some of these features!
* Unlike most markup languages, Markdown lacks accessibilty features such as alt tags, classes, and id's, making it difficult for screen readers to properly interpret text.

## Code Demo

Here, let's go over some best practices of basic Markdown syntax:

### Headings

Note that the space between the '#' and the heading text is important!

| Markdown     | HTML |  Rendered  |  
| ----------- | ----------- | ------ |  
| `# Heading 1 `   | `<h1>Heading</h1>`| <h1>Heading 1</h1>  |  
| `## Heading 2 `   | `<h2>Heading</h2>`| <h2>Heading 2</h2> | 
| `### Heading 3 `   | `<h3>Heading</h3>`| <h3>Heading 3</h3> | 
| `#### Heading 4 `   | `<h4>Heading</h4>`| <h4>Heading 4</h4> | 
| `##### Heading 5 `   | `<h5>Heading</h5>`| <h5>Heading 5</h5> | 
| `###### Heading 6 `   | `<h6>Heading</h6>`| <h6>Heading 6</h6> | 

### Paragraphs
Separate your paragraphs from one another by using a blank line between them.
| Markdown     | HTML |  Rendered  |  
| ----------- | ----------- | ------ |  
|` Hey, check out this paragraph. So cool. `  | `<p>Hey, check out this paragraph.</p> <p>So cool.</p>`| <p>Hey, check out this paragraph.</p> <p>So cool.</p>  |  


### Emphasis

Bold and italics can be used on their own nested together, and can even be placed within words.
| Markdown     | HTML |  Rendered  |  
| ----------- | ----------- | ------ |  
| `This is how you **bold** text. `   | `This is how you <strong>bold</strong> text.`| This is how you **bold** text.  |  
| `This is how you *italisize* text. `   | `This is how you <em>italisize</em> text.`| This is how you *italisize* text  | 
| `Wow, this text is so ***emphatic***! `   | `Wow, this text is so <em><strong>emphatic</strong></em>!`| Wow, this text is so ***emphatic***! | 

### Blockquotes
Note: block quotes are nestable within eachother.
| Markdown     |  Rendered  |  
| -----------  | ------ |  
| `> This is how you make a blockquote.`   | <blockquote> This is how you make a blockquote. </blockquote> |  

### Ordered Lists
| Markdown     | HTML |  Rendered  |  
| ----------- | ----------- | ------ |  
| `1. First item  2. Second item  3. Third item`   | `<ol><li>First item</li><li>Second item</li><li>Third item</li></ol>`| <ol><li>First item</li><li>Second item</li><li>Third Item</li></ol> |  


### Unordered Lists
| Markdown | HTML | Rendered |  
|---|---|---|  
|`- First item <br><br> - Second item  - Third item`|`<ul><li>First item</li><li>Second item</li><li>Third item</li></ul>`|<ul><li>First item</li><li>Second item</li><li>Third item</li></ul>|  
|`* First item  * Second item  * Third item`|`<ul><li>First item</li><li>Second item</li><li>Third item</li></ul>`|<ul><li>First item</li><li>Second item</li><li>Third item</li></ul>|  
|`+ First item  + Second item  + Third item`|`<ul><li>First item</li><li>Second item</li><li>Third item</li></ul>`|<ul><li>First item</li><li>Second item</li><li>Third item</li></ul>|  

### Emojis 

| Markdown | HTML | Rendered |  
|---|---|---|  
|`:eyes: :100: :thumbsup: :100:`| `&#128064; &#128175; &#128077; &#128175;` | &#128064; &#128175; &#128077; &#128175; |

### Images
Image links begin with an exclamation point, alt text is placed inside square brackets, and the image link goes inside parentheses!

| Markdown | HTML | Rendered |  
|---|---|---|  
|`![8-bit Gaming Panda](images/8bit-gaming-panda.png)`|`<img alt="8-bit Gaming Panda" src="images/8bit-gaming-panda.png"/>`| <img alt="8-bit Gaming Panda" src="images/8bit-gaming-panda.png"/> |

### Links

Linking to another external page is similar to linking images, just without the exclamation point.

| Markdown | HTML | Rendered |  
|---|---|---|  
| `[Wordle](https://www.nytimes.com/games/wordle/index.html)` |`<a href="https://www.nytimes.com/games/wordle/index.html" target="_blank" rel="noreferer noopener">Wordle</a>`| <a href="https://www.nytimes.com/games/wordle/index.html" target="_blank" rel="noreferer noopener">Wordle</a> |

## Tools and Resources

### Tutorials:

* [Another Markdown Tutorial](https://commonmark.org/):complete an easy Markdown tutorial in under ten minutes.

### Text Editors:

* [iA Writer](https://ia.net/writer)
* [Dillinger.io](https://dillinger.io/)
* [Typora.io](https://typora.io/)

### Resources:

* ["The" Markdown site](https://daringfireball.net/projects/markdown/):John Gruber's personal blog and guide to Markdown.
* [A Guide to Markdown](https://www.markdownguide.org/):a free, open-source guide to markdown.

---

* FWD37
* Dilraj, Gill, Simran, Tyler
* [![Github Icon](images/github-32.png)](https://github.com/happymeal808/group-07-presentation-website/)
* [![Home Icon](images/home-32.png)](# ![markdown logo](images/markdown-50.png) Markdown)
