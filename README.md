# Simple Markdown Previewer

Create a basic Markdown previewer component that takes Markdown text as input and renders it as HTML. The application should dynamically update the preview as the input Markdown changes.

## Requirements
Node.js v18+
npm
React

## Test Cases
### Test Case 1
- Description: Verify that a simple heading is rendered correctly.
- Input: # Heading
- Expected Output: <h1 id="heading">Heading</h1>


### Test Case 2
- Description: Verify that italic text is rendered correctly.
- Input: *Italic text*
- Expected Output: <p><em>Italic text</em></p>


### Test Case 3
- Description: Verify that bold text is rendered correctly.
- Input: **Bold text**
- Expected Output: <p><strong>Bold text</strong></p>


### Test Case 4
- Description: Verify that a list item is rendered correctly.
- Input: - List item
- Expected Output: <ul>
<li>List item</li>
</ul>


### Test Case 5
- Description: Verify that a link is rendered correctly.
- Input: [Link](https://www.example.com)
- Expected Output: <p><a href="https://www.example.com">Link</a></p>


### Test Case 6
- Description: Verify that code blocks are rendered correctly.
- Input: ```javascript
console.log('Hello, world!');
```
- Expected Output: <pre><code class="language-javascript">console.log('Hello, world!');n</code></pre>


### Test Case 7
- Description: Verify a combination of Markdown features renders correctly
- Input: ## Heading
*List item*
**Bold**
- Expected Output: <h2 id="heading">Heading</h2>
<ul>
<li><em>List item</em></li>
</ul>
<p><strong>Bold</strong></p>
