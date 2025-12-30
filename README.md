<ul>
  <li><strong>Chapter 1: HTML Fundamentals and Structure</strong>
    <ul>
      <li><a href="#chapter-1.1">Understanding HTML Document Structure</a></li>
      <li><a href="#chapter-1.2">Basic HTML Elements: Headings, Paragraphs, Lists</a></li>
      <li><a href="#chapter-1.3">Working with Links and Images</a></li>
      <li><a href="#chapter-1.4">Introduction to HTML Forms and Input Elements</a></li>
      <li><a href="#chapter-1.5">Semantic HTML: Improving Accessibility and SEO</a></li>
    </ul>
  </li>

  <li><strong>Chapter 2: CSS Styling and Layout</strong>
    <ul>
      <li><a href="#chapter-2.1">CSS Selectors: Targeting HTML Elements</a></li>
      <li><a href="#chapter-2.2">Understanding the CSS Box Model</a></li>
      <li><a href="#chapter-2.3">Working with Colors, Fonts, and Text Styles</a></li>
      <li><a href="#chapter-2.4">CSS Layout Techniques: Flexbox</a></li>
      <li><a href="#chapter-2.5">CSS Layout Techniques: Grid</a></li>
      <li><a href="#chapter-2.6">Responsive Design with Media Queries</a></li>
    </ul>
  </li>

  <li><strong>Chapter 3: JavaScript Basics and DOM Manipulation</strong>
    <ul>
      <li><a href="#chapter-3.1">Introduction to JavaScript Syntax and Data Types</a></li>
      <li><a href="#chapter-3.2">Variables, Operators, and Control Flow in JavaScript</a></li>
      <li><a href="#chapter-3.3">DOM Manipulation: Selecting and Modifying Elements</a></li>
      <li><a href="#chapter-3.4">Event Handling: Responding to User Interactions</a></li>
      <li><a href="#chapter-3.5">Basic JavaScript Functions and Scope</a></li>
    </ul>
  </li>
  
  <li><strong>Chapter 4: Intermediate JavaScript and Asynchronous Programming</strong>
    <ul>
      <li><a href="#chapter-4.1">Working with Arrays and Objects in JavaScript</a></li>
      <li><a href="#chapter-4.2">Introduction to JSON Data Format</a></li>
      <li><a href="#chapter-4.3">Asynchronous JavaScript: Callbacks</a></li>
      <li><a href="#chapter-4.4">Asynchronous JavaScript: Promises and Fetch API</a></li>
      <li><a href="#chapter-4.5">Debugging JavaScript Code</a></li>
    </ul>
  </li>
  
  <li><strong>Chapter 5: Front-End Framework Introduction: React</strong>
    <ul>
      <li><a href="#chapter-5.1">Introduction to React: Components and JSX</a></li>
      <li><a href="#chapter-5.2">React State and Props: Managing Data</a></li>
      <li><a href="#chapter-5.3">Handling Events in React Components</a></li>
      <li><a href="#chapter-5.4">React Hooks: useState and useEffect</a></li>
      <li><a href="#chapter-5.5">Conditional Rendering and Lists in React</a></li>
    </ul>
  </li>
  
  <li><strong>Chapter 6: Back-End Fundamentals with Node.js and Express</strong>
    <ul>
      <li><a href="#chapter-6.1">Introduction to Node.js and npm</a></li>
      <li><a href="#chapter-6.2">Building a Simple Web Server with Node.js</a></li>
      <li><a href="#chapter-6.3">Introduction to Express.js: Routing and Middleware</a></li>
      <li><a href="#chapter-6.4">Handling HTTP Requests and Responses</a></li>
      <li><a href="#chapter-6.5">Connecting to a Database (MongoDB)</a></li>
    </ul>
  </li>
  
  <li><strong>Chapter 7: Full-Stack Project: Building a Simple Application & Deployment</strong>
    <ul>
      <li><a href="#chapter-7.1">Project Setup: Integrating Front-End and Back-End</a></li>
      <li><a href="#chapter-7.2">Implementing User Authentication</a></li>
      <li><a href="#chapter-7.3">Creating and Managing Data with React and Node.js</a></li>
      <li><a href="#chapter-7.4">Website Accessibility Considerations and Best Practices</a></li>
      <li><a href="#chapter-7.5">Deploying Your Application to Netlify or Heroku</a></li>
    </ul>
  </li>
</ul>

<div id="chapter-1">

<div id="chapter-1.1">

<h1 class="mb-6 text-3xl font-semibold text-balance max-lg:mb-3 max-lg:text-xl">Understanding HTML Document Structure</h1><p>The foundation of every webpage lies in its HTML structure. This structure provides the skeleton upon which all visual styling and interactive functionality are built. A well-defined HTML document ensures that browsers can correctly interpret and display your content, search engines can effectively index your pages, and users can navigate your site with ease. Without a solid understanding of the fundamental HTML document structure, building and maintaining websites becomes a significantly more challenging task. This lesson will provide you with the knowledge needed to create valid and well-structured HTML documents, setting you up for success in your web development journey.</p>
<h2>The Basic Structure of an HTML Document</h2>
<p>Every HTML document follows a specific structure, which tells the browser that it's dealing with an HTML document and how to interpret the content. Let's examine the essential elements that comprise this structure:</p>
<h3>The <code>&lt;!DOCTYPE html&gt;</code> Declaration</h3>
<p>The <code>&lt;!DOCTYPE html&gt;</code> declaration is the very first thing you'll see in an HTML document. It's not an HTML tag itself, but rather an instruction to the web browser about the version of HTML the page is written in. For HTML5, which is the current standard, it's simply:</p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;!</span><span style="color:#22863A">DOCTYPE</span><span style="color:#6F42C1"> html</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<p>This declaration ensures that the browser renders the page in "standards mode," following the W3C specifications for HTML and CSS. Without it, browsers might fall back to "quirks mode," which can lead to inconsistent rendering across different browsers.</p>
<h3>The <code>&lt;html&gt;</code> Element</h3>
<p>The <code>&lt;html&gt;</code> element is the root element of an HTML page. It signifies the start of the HTML document and contains all other HTML elements, except for the <code>&lt;!DOCTYPE html&gt;</code> declaration. Every HTML document must have one, and only one, <code>&lt;html&gt;</code> element.</p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;!</span><span style="color:#22863A">DOCTYPE</span><span style="color:#6F42C1"> html</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">html</span><span style="color:#6F42C1"> lang</span><span style="color:#24292E">=</span><span style="color:#032F62">"en"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#6A737D">  &lt;!-- The rest of the HTML document goes here --&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">html</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<p>The <code>lang</code> attribute within the <code>&lt;html&gt;</code> tag specifies the language of the document. In the example above, "en" indicates English. Setting the language helps browsers and search engines to properly interpret and process the text content. It's also crucial for accessibility, allowing screen readers to use the correct pronunciation.</p>
<h3>The <code>&lt;head&gt;</code> Element</h3>
<p>The <code>&lt;head&gt;</code> element contains meta-information about the HTML document, such as the title, character set, linked stylesheets, and scripts. This information is not displayed on the page itself, but it's essential for the browser, search engines, and other web services.</p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;!</span><span style="color:#22863A">DOCTYPE</span><span style="color:#6F42C1"> html</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">html</span><span style="color:#6F42C1"> lang</span><span style="color:#24292E">=</span><span style="color:#032F62">"en"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">head</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">meta</span><span style="color:#6F42C1"> charset</span><span style="color:#24292E">=</span><span style="color:#032F62">"UTF-8"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">meta</span><span style="color:#6F42C1"> name</span><span style="color:#24292E">=</span><span style="color:#032F62">"viewport"</span><span style="color:#6F42C1"> content</span><span style="color:#24292E">=</span><span style="color:#032F62">"width=device-width, initial-scale=1.0"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">title</span><span style="color:#24292E">&gt;My First Webpage&lt;/</span><span style="color:#22863A">title</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">link</span><span style="color:#6F42C1"> rel</span><span style="color:#24292E">=</span><span style="color:#032F62">"stylesheet"</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"styles.css"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;/</span><span style="color:#22863A">head</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">body</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#6A737D">    &lt;!-- Content of the page --&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;/</span><span style="color:#22863A">body</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">html</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<p>Let's break down the elements commonly found within the <code>&lt;head&gt;</code>:</p>
<h4><code>&lt;meta charset="UTF-8"&gt;</code></h4>
<p>This tag specifies the character encoding for the HTML document. UTF-8 is the recommended character encoding because it supports a wide range of characters from different languages. It ensures that your text is displayed correctly, regardless of the characters used.</p>
<h4><code>&lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;</code></h4>
<p>This meta tag is crucial for responsive web design. It configures the viewport, which is the visible area of the web page on different devices. <code>width=device-width</code> sets the width of the viewport to the width of the device, and <code>initial-scale=1.0</code> sets the initial zoom level when the page is first loaded. This ensures that your website scales properly on mobile devices.</p>
<h4><code>&lt;title&gt;My First Webpage&lt;/title&gt;</code></h4>
<p>The <code>&lt;title&gt;</code> element specifies a title for the HTML document. This title is displayed in the browser's title bar or tab, and it's used by search engines for indexing. A descriptive and concise title is important for both user experience and SEO (Search Engine Optimization).</p>
<h4><code>&lt;link rel="stylesheet" href="styles.css"&gt;</code></h4>
<p>The <code>&lt;link&gt;</code> element is used to link external resources to the HTML document. In this case, it's linking a CSS stylesheet named "styles.css." The <code>rel</code> attribute specifies the relationship between the current document and the linked resource. <code>stylesheet</code> indicates that the linked resource is a stylesheet used to style the HTML content. Linking external stylesheets helps to separate content from presentation, making it easier to maintain and update the design of your website.</p>
<h3>The <code>&lt;body&gt;</code> Element</h3>
<p>The <code>&lt;body&gt;</code> element contains the actual content of the HTML document that will be displayed in the browser window. This includes text, images, links, forms, and all other visible elements.</p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;!</span><span style="color:#22863A">DOCTYPE</span><span style="color:#6F42C1"> html</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">html</span><span style="color:#6F42C1"> lang</span><span style="color:#24292E">=</span><span style="color:#032F62">"en"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">head</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">meta</span><span style="color:#6F42C1"> charset</span><span style="color:#24292E">=</span><span style="color:#032F62">"UTF-8"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">meta</span><span style="color:#6F42C1"> name</span><span style="color:#24292E">=</span><span style="color:#032F62">"viewport"</span><span style="color:#6F42C1"> content</span><span style="color:#24292E">=</span><span style="color:#032F62">"width=device-width, initial-scale=1.0"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">title</span><span style="color:#24292E">&gt;My First Webpage&lt;/</span><span style="color:#22863A">title</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">link</span><span style="color:#6F42C1"> rel</span><span style="color:#24292E">=</span><span style="color:#032F62">"stylesheet"</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"styles.css"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;/</span><span style="color:#22863A">head</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">body</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">h1</span><span style="color:#24292E">&gt;Welcome to My Website!&lt;/</span><span style="color:#22863A">h1</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;This is a paragraph of text.&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">img</span><span style="color:#6F42C1"> src</span><span style="color:#24292E">=</span><span style="color:#032F62">"image.jpg"</span><span style="color:#6F42C1"> alt</span><span style="color:#24292E">=</span><span style="color:#032F62">"A beautiful image"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;/</span><span style="color:#22863A">body</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">html</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<p>In the example above, the <code>&lt;body&gt;</code> element contains a heading (<code>&lt;h1&gt;</code>), a paragraph (<code>&lt;p&gt;</code>), and an image (<code>&lt;img&gt;</code>). These are just a few of the many HTML elements that can be used to structure and present content within the <code>&lt;body&gt;</code>.</p>
<h2>Semantic HTML and Its Importance</h2>
<p>Semantic HTML involves using HTML elements to convey the <em>meaning</em> and <em>structure</em> of the content, rather than just its presentation. This is crucial for accessibility, SEO, and maintainability. Using semantic elements makes your HTML more readable and understandable for both developers and machines.</p>
<h3>Examples of Semantic Elements</h3>
<p>Here are a few examples of semantic HTML elements:</p>
<ul>
<li><code>&lt;article&gt;</code>: Represents a self-contained composition in a document, page, application, or site, which is intended to be independently distributable or reusable (e.g., a blog post, a news article).</li>
<li><code>&lt;aside&gt;</code>: Represents a section of a page that is tangentially related to the content around it, often used for sidebars or call-out boxes.</li>
<li><code>&lt;nav&gt;</code>: Represents a section of a page that contains navigation links.</li>
<li><code>&lt;header&gt;</code>: Represents introductory content for a document or section.</li>
<li><code>&lt;footer&gt;</code>: Represents a footer for a document or section, typically containing information about the author, copyright, or related links.</li>
<li><code>&lt;main&gt;</code>: Specifies the main content of a document.</li>
<li><code>&lt;section&gt;</code>: Represents a thematic grouping of content, typically with a heading.</li>
</ul>
<h3>Benefits of Using Semantic HTML</h3>
<ul>
<li><strong>Accessibility:</strong> Semantic HTML provides structure and meaning to content, making it easier for assistive technologies like screen readers to interpret and present the information to users with disabilities. For instance, using <code>&lt;nav&gt;</code> to mark up navigation menus allows screen readers to quickly identify and access the navigation section of a page.</li>
<li><strong>SEO:</strong> Search engines use semantic HTML to understand the context and relevance of content. Using appropriate semantic elements can improve your website's search engine ranking. For example, using <code>&lt;article&gt;</code> to enclose a blog post signals to search engines that this content is a standalone, independent piece of content, which can help them index it more effectively.</li>
<li><strong>Maintainability:</strong> Semantic HTML makes your code more readable and understandable, which makes it easier to maintain and update. When developers can easily understand the structure of your HTML, they can make changes more efficiently and with fewer errors.</li>
<li><strong>Interoperability:</strong> Semantic HTML ensures that your website is more compatible with different browsers and devices. By using standard HTML elements, you can avoid relying on browser-specific hacks or workarounds, which can break down when browsers are updated.</li>
</ul>
<h3>Example: Semantic vs. Non-Semantic Structure</h3>
<p>Let's illustrate the difference between semantic and non-semantic HTML with a simple example:</p>
<p><strong>Non-Semantic HTML:</strong></p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">div</span><span style="color:#6F42C1"> id</span><span style="color:#24292E">=</span><span style="color:#032F62">"header"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">div</span><span style="color:#6F42C1"> id</span><span style="color:#24292E">=</span><span style="color:#032F62">"logo"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">h1</span><span style="color:#24292E">&gt;My Website&lt;/</span><span style="color:#22863A">h1</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;/</span><span style="color:#22863A">div</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">div</span><span style="color:#6F42C1"> id</span><span style="color:#24292E">=</span><span style="color:#032F62">"navigation"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">ul</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"#"</span><span style="color:#24292E">&gt;Home&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"#"</span><span style="color:#24292E">&gt;About&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"#"</span><span style="color:#24292E">&gt;Services&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"#"</span><span style="color:#24292E">&gt;Contact&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;/</span><span style="color:#22863A">ul</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;/</span><span style="color:#22863A">div</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">div</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">div</span><span style="color:#6F42C1"> id</span><span style="color:#24292E">=</span><span style="color:#032F62">"main"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">div</span><span style="color:#6F42C1"> class</span><span style="color:#24292E">=</span><span style="color:#032F62">"article"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">h2</span><span style="color:#24292E">&gt;Article Title&lt;/</span><span style="color:#22863A">h2</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;Article content goes here.&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;/</span><span style="color:#22863A">div</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">div</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">div</span><span style="color:#6F42C1"> id</span><span style="color:#24292E">=</span><span style="color:#032F62">"footer"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span><span style="color:#005CC5">&amp;copy;</span><span style="color:#24292E"> 2023 My Website&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">div</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<p>In this example, <code>&lt;div&gt;</code> elements are used extensively with <code>id</code> and <code>class</code> attributes to define the structure of the page. While this approach works, it doesn't convey the <em>meaning</em> of the content.</p>
<p><strong>Semantic HTML:</strong></p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">header</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">div</span><span style="color:#6F42C1"> id</span><span style="color:#24292E">=</span><span style="color:#032F62">"logo"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">h1</span><span style="color:#24292E">&gt;My Website&lt;/</span><span style="color:#22863A">h1</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;/</span><span style="color:#22863A">div</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">nav</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">ul</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"#"</span><span style="color:#24292E">&gt;Home&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"#"</span><span style="color:#24292E">&gt;About&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"#"</span><span style="color:#24292E">&gt;Services&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"#"</span><span style="color:#24292E">&gt;Contact&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;/</span><span style="color:#22863A">ul</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;/</span><span style="color:#22863A">nav</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">header</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">main</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">article</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">h2</span><span style="color:#24292E">&gt;Article Title&lt;/</span><span style="color:#22863A">h2</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;Article content goes here.&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;/</span><span style="color:#22863A">article</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">main</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">footer</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span><span style="color:#005CC5">&amp;copy;</span><span style="color:#24292E"> 2023 My Website&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">footer</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<p>In this semantic example, we've replaced the generic <code>&lt;div&gt;</code> elements with more descriptive elements like <code>&lt;header&gt;</code>, <code>&lt;nav&gt;</code>, <code>&lt;main&gt;</code>, <code>&lt;article&gt;</code>, and <code>&lt;footer&gt;</code>. This makes the structure of the page much clearer and easier to understand.</p>
<h2>Best Practices for HTML Document Structure</h2>
<p>Following best practices ensures that your HTML documents are well-formed, accessible, and maintainable. Here are some key guidelines:</p>
<h3>Validate Your HTML</h3>
<p>Validating your HTML involves checking your code against the official HTML specifications to ensure that it's free of errors. You can use online HTML validators like the W3C Markup Validation Service ( <a href="https://validator.w3.org/">https://validator.w3.org/</a> ) to check your code. Validating your HTML helps to ensure that your website renders correctly across different browsers and devices.</p>
<h3>Use Proper Nesting</h3>
<p>HTML elements must be properly nested, meaning that elements must be closed in the correct order. For example, the following is incorrect:</p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;This is a &lt;</span><span style="color:#22863A">b</span><span style="color:#24292E">&gt;bold paragraph.&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">b</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<p>The correct nesting is:</p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;This is a &lt;</span><span style="color:#22863A">b</span><span style="color:#24292E">&gt;bold paragraph.&lt;/</span><span style="color:#22863A">b</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<p>Improper nesting can lead to unpredictable rendering and can make your code difficult to debug.</p>
<h3>Use Lowercase for Element Names and Attributes</h3>
<p>While HTML is case-insensitive, it's a best practice to use lowercase for element names and attributes. This makes your code more consistent and readable.</p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;This is a paragraph.&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt; </span><span style="color:#6A737D">&lt;!-- Recommended --&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">P</span><span style="color:#24292E">&gt;This is a paragraph.&lt;/</span><span style="color:#22863A">P</span><span style="color:#24292E">&gt; </span><span style="color:#6A737D">&lt;!-- Not recommended --&gt;</span></span></code></pre></div></div></div>
<h3>Use Quotes for Attribute Values</h3>
<p>Always enclose attribute values in quotes, even if they contain only alphanumeric characters. This ensures that your code is parsed correctly by browsers.</p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">img</span><span style="color:#6F42C1"> src</span><span style="color:#24292E">=</span><span style="color:#032F62">"image.jpg"</span><span style="color:#6F42C1"> alt</span><span style="color:#24292E">=</span><span style="color:#032F62">"My Image"</span><span style="color:#24292E">&gt; </span><span style="color:#6A737D">&lt;!-- Recommended --&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">img</span><span style="color:#6F42C1"> src</span><span style="color:#24292E">=</span><span style="color:#032F62">image.jpg</span><span style="color:#6F42C1"> alt</span><span style="color:#24292E">=</span><span style="color:#032F62">My</span><span style="color:#6F42C1"> Image</span><span style="color:#24292E">&gt; </span><span style="color:#6A737D">&lt;!-- Not recommended --&gt;</span></span></code></pre></div></div></div>
<h3>Provide Alternative Text for Images</h3>
<p>The <code>alt</code> attribute of the <code>&lt;img&gt;</code> tag provides alternative text for the image. This text is displayed if the image cannot be loaded, and it's also used by screen readers to describe the image to users with disabilities. Always provide descriptive and meaningful alternative text for your images.</p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">img</span><span style="color:#6F42C1"> src</span><span style="color:#24292E">=</span><span style="color:#032F62">"cat.jpg"</span><span style="color:#6F42C1"> alt</span><span style="color:#24292E">=</span><span style="color:#032F62">"A cute cat sitting on a window sill."</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<h3>Use Comments to Explain Your Code</h3>
<p>Comments are an essential part of writing maintainable code. Use comments to explain the purpose of different sections of your HTML document, especially if the code is complex or non-obvious.</p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#6A737D">&lt;!-- This is the main navigation menu --&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">nav</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">ul</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"#"</span><span style="color:#24292E">&gt;Home&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"#"</span><span style="color:#24292E">&gt;About&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"#"</span><span style="color:#24292E">&gt;Services&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"#"</span><span style="color:#24292E">&gt;Contact&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;/</span><span style="color:#22863A">ul</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">nav</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<h2>Practical Exercises</h2>
<ol>
<li><strong>Basic HTML Structure:</strong> Create a new HTML file. Include the <code>&lt;!DOCTYPE html&gt;</code> declaration, the <code>&lt;html&gt;</code> tag with the <code>lang</code> attribute set to your preferred language, the <code>&lt;head&gt;</code> element with a <code>&lt;meta charset="UTF-8"&gt;</code> tag, a <code>&lt;title&gt;</code> tag, and the <code>&lt;body&gt;</code> element. Inside the <code>&lt;body&gt;</code>, add a heading (<code>&lt;h1&gt;</code>) and a paragraph (<code>&lt;p&gt;</code>).</li>
<li><strong>Semantic HTML:</strong> Take an existing HTML document that uses non-semantic elements (e.g., <code>&lt;div&gt;</code> elements with <code>id</code> and <code>class</code> attributes) and refactor it to use semantic elements like <code>&lt;article&gt;</code>, <code>&lt;nav&gt;</code>, <code>&lt;aside&gt;</code>, <code>&lt;header&gt;</code>, and <code>&lt;footer&gt;</code>.</li>
<li><strong>HTML Validation:</strong> Use the W3C Markup Validation Service to validate an HTML document. Correct any errors that are reported by the validator.</li>
<li><strong>Image with Alternative Text:</strong> Add an image to an HTML document. Provide a descriptive and meaningful <code>alt</code> attribute for the image. Test the <code>alt</code> attribute by intentionally misspelling the image file name to see if the alternative text is displayed.</li>
</ol>
  
</div>

<div id="chapter-1.2">

<h1 class="mb-6 text-3xl font-semibold text-balance max-lg:mb-3 max-lg:text-xl">Basic HTML Elements: Headings, Paragraphs, Lists</h1><p>HTML provides the fundamental building blocks for all web pages. Understanding how to structure content using basic HTML elements like headings, paragraphs, and lists is essential for creating well-organized and accessible web pages. These elements define the content hierarchy and make it easier for users and search engines to understand the information presented on a website. In this lesson, we will explore these elements in detail, learning how to use them effectively to structure web content.</p>
<h2>HTML Headings</h2>
<p>Headings are used to define the titles and subtitles of your web page content. HTML provides six levels of headings, from <code>&lt;h1&gt;</code> to <code>&lt;h6&gt;</code>, where <code>&lt;h1&gt;</code> represents the most important heading (the main title) and <code>&lt;h6&gt;</code> represents the least important.</p>
<h3>Heading Levels and Semantic Meaning</h3>
<ul>
<li><code>&lt;h1&gt;</code>: Typically used for the main title of the page. There should generally be only one <code>&lt;h1&gt;</code> element per page, as it represents the primary topic.</li>
<li><code>&lt;h2&gt;</code>: Used for major sections within the page. Think of these as chapter titles in a book.</li>
<li><code>&lt;h3&gt;</code>: Used for sub-sections within the <code>&lt;h2&gt;</code> sections. These are like sub-chapter titles.</li>
<li><code>&lt;h4&gt;</code>, <code>&lt;h5&gt;</code>, <code>&lt;h6&gt;</code>: Used for increasingly smaller sub-sections. While available, using headings beyond <code>&lt;h3&gt;</code> is less common and often indicates a need to restructure your content for better readability.</li>
</ul>
<p>It's important to use headings in a logical order. Don't skip heading levels (e.g., going from <code>&lt;h1&gt;</code> to <code>&lt;h3&gt;</code> without an <code>&lt;h2&gt;</code>). This helps maintain a clear document outline and is crucial for accessibility and SEO.</p>
<h3>Examples of Heading Usage</h3>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;!</span><span style="color:#22863A">DOCTYPE</span><span style="color:#6F42C1"> html</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">html</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">head</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">title</span><span style="color:#24292E">&gt;My Amazing Webpage&lt;/</span><span style="color:#22863A">title</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">head</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">body</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">h1</span><span style="color:#24292E">&gt;Welcome to My Website&lt;/</span><span style="color:#22863A">h1</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;This is the main content of my website.&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">h2</span><span style="color:#24292E">&gt;About Me&lt;/</span><span style="color:#22863A">h2</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;Learn more about who I am and what I do.&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">h3</span><span style="color:#24292E">&gt;My Skills&lt;/</span><span style="color:#22863A">h3</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;Here's a list of my skills and expertise.&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">h4</span><span style="color:#24292E">&gt;Web Development&lt;/</span><span style="color:#22863A">h4</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;I am proficient in HTML, CSS, and JavaScript.&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">body</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">html</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<p>In the example above, we start with the main heading <code>&lt;h1&gt;</code> "Welcome to My Website". Then, we use <code>&lt;h2&gt;</code> for the "About Me" section. Within "About Me", we have a sub-section "My Skills" using <code>&lt;h3&gt;</code>, and further down, a specific skill like "Web Development" is marked with <code>&lt;h4&gt;</code>. This creates a clear hierarchy for the content.</p>
<h3>Best Practices for Headings</h3>
<ul>
<li><strong>Use headings to create a logical outline of your content.</strong> This makes it easier for users to scan the page and find the information they need.</li>
<li><strong>Don't use headings solely for styling purposes.</strong> Use CSS to style your headings, rather than choosing a heading level based on its default appearance.</li>
<li><strong>Keep headings concise and descriptive.</strong> A good heading should accurately summarize the content of the section it introduces.</li>
<li><strong>Use keywords in your headings (where appropriate).</strong> This can improve your website's SEO.</li>
</ul>
<h2>HTML Paragraphs</h2>
<p>Paragraphs are used to define blocks of text in your document. The <code>&lt;p&gt;</code> element represents a paragraph. Browsers automatically add some space before and after a paragraph, making it visually distinct from other elements.</p>
<h3>Basic Paragraph Structure</h3>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;This is the first paragraph of my webpage. It contains some introductory information.&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;This is the second paragraph. It provides more details about the topic.&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<p>Each <code>&lt;p&gt;</code> element represents a separate block of text. Browsers will render these paragraphs with a margin above and below, separating them visually.</p>
<h3>Paragraphs and Line Breaks</h3>
<p>Within a paragraph, the browser automatically wraps text to fit the available space. If you need to force a line break within a paragraph, you can use the <code>&lt;br&gt;</code> (break) element. However, use <code>&lt;br&gt;</code> sparingly. It's generally better to structure your content with appropriate paragraph breaks instead of relying on <code>&lt;br&gt;</code> for formatting.</p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;This is a paragraph with a line break.&lt;</span><span style="color:#22863A">br</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">This is the second line of the paragraph.&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<h3>Paragraph Styling Considerations</h3>
<p>While the default appearance of paragraphs is generally acceptable, you can use CSS (which we'll cover in Module 2) to customize their appearance. You can control properties like:</p>
<ul>
<li><strong>Font size:</strong> Adjust the size of the text.</li>
<li><strong>Line height:</strong> Increase or decrease the spacing between lines.</li>
<li><strong>Text color:</strong> Change the color of the text.</li>
<li><strong>Text alignment:</strong> Align the text to the left, right, center, or justify it.</li>
<li><strong>Margins and padding:</strong> Control the spacing around the paragraph.</li>
</ul>
<h3>Paragraph Example</h3>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;!</span><span style="color:#22863A">DOCTYPE</span><span style="color:#6F42C1"> html</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">html</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">head</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">title</span><span style="color:#24292E">&gt;Paragraph Example&lt;/</span><span style="color:#22863A">title</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">head</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">body</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">h1</span><span style="color:#24292E">&gt;My Article&lt;/</span><span style="color:#22863A">h1</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;This is the introductory paragraph of my article. It sets the stage for what's to come.&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">h2</span><span style="color:#24292E">&gt;First Section&lt;/</span><span style="color:#22863A">h2</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;This paragraph provides details about the first section of my article. It includes relevant information and supporting evidence.&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">h2</span><span style="color:#24292E">&gt;Second Section&lt;/</span><span style="color:#22863A">h2</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;This paragraph discusses the second section. It offers a different perspective and explores new ideas.&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">body</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">html</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<h2>HTML Lists</h2>
<p>HTML lists are used to present information in an organized and structured manner. There are three main types of lists:</p>
<ul>
<li><strong>Unordered lists (<code>&lt;ul&gt;</code>):</strong> Used for lists where the order of items is not important.</li>
<li><strong>Ordered lists (<code>&lt;ol&gt;</code>):</strong> Used for lists where the order of items is important.</li>
<li><strong>Definition lists (<code>&lt;dl&gt;</code>):</strong> Used to define terms and their descriptions.</li>
</ul>
<h3>Unordered Lists (<code>&lt;ul&gt;</code>)</h3>
<p>Unordered lists are used to display a collection of items where the order doesn't matter. Each item in the list is marked with a bullet point (by default).</p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">ul</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;Item 1&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;Item 2&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;Item 3&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">ul</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<h3>Ordered Lists (<code>&lt;ol&gt;</code>)</h3>
<p>Ordered lists are used to display a collection of items where the order <em>does</em> matter. Each item in the list is numbered (by default).</p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">ol</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;First step&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;Second step&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;Third step&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">ol</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<h4>Ordered List Attributes</h4>
<p>The <code>&lt;ol&gt;</code> element has several attributes that allow you to customize the numbering:</p>
<ul>
<li><code>type</code>: Specifies the type of numbering to use. Possible values include:
<ul>
<li><code>1</code>: Numbers (default)</li>
<li><code>A</code>: Uppercase letters</li>
<li><code>a</code>: Lowercase letters</li>
<li><code>I</code>: Uppercase Roman numerals</li>
<li><code>i</code>: Lowercase Roman numerals</li>
</ul>
</li>
<li><code>start</code>: Specifies the starting number of the list.</li>
</ul>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">ol</span><span style="color:#6F42C1"> type</span><span style="color:#24292E">=</span><span style="color:#032F62">"A"</span><span style="color:#6F42C1"> start</span><span style="color:#24292E">=</span><span style="color:#032F62">"3"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;Item C&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;Item D&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;Item E&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">ol</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<p>This list would start with the letter "C" instead of "A".</p>
<h3>Definition Lists (<code>&lt;dl&gt;</code>)</h3>
<p>Definition lists are used to define terms and their descriptions. Each term is defined using the <code>&lt;dt&gt;</code> (definition term) element, and its corresponding description is defined using the <code>&lt;dd&gt;</code> (definition description) element.</p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">dl</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">dt</span><span style="color:#24292E">&gt;HTML&lt;/</span><span style="color:#22863A">dt</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">dd</span><span style="color:#24292E">&gt;HyperText Markup Language is the standard markup language for creating web pages.&lt;/</span><span style="color:#22863A">dd</span><span style="color:#24292E">&gt;</span></span>
<span class="line"></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">dt</span><span style="color:#24292E">&gt;CSS&lt;/</span><span style="color:#22863A">dt</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">dd</span><span style="color:#24292E">&gt;Cascading Style Sheets is a style sheet language used for describing the look and formatting of a document written in HTML.&lt;/</span><span style="color:#22863A">dd</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">dl</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<h3>Nesting Lists</h3>
<p>Lists can be nested inside other lists to create hierarchical structures. This is useful for representing complex relationships between items.</p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">ul</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;Coffee&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;Tea</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">ul</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;Black tea&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;Green tea&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;/</span><span style="color:#22863A">ul</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;Milk&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">ul</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<p>In this example, we have an unordered list with three items: "Coffee", "Tea", and "Milk". The "Tea" item contains another unordered list with two items: "Black tea" and "Green tea".</p>
<h3>Lists Example</h3>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;!</span><span style="color:#22863A">DOCTYPE</span><span style="color:#6F42C1"> html</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">html</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">head</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">title</span><span style="color:#24292E">&gt;Lists Example&lt;/</span><span style="color:#22863A">title</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">head</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">body</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">h1</span><span style="color:#24292E">&gt;My To-Do List&lt;/</span><span style="color:#22863A">h1</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">ol</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;Wake up&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;Eat breakfast&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;Work on web development project&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;Take a break&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;Continue working on project&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;Go for a walk&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;Have dinner&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;Relax and unwind&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;Go to sleep&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;/</span><span style="color:#22863A">ol</span><span style="color:#24292E">&gt;</span></span>
<span class="line"></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">h2</span><span style="color:#24292E">&gt;Shopping List&lt;/</span><span style="color:#22863A">h2</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">ul</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;Milk&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;Eggs&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;Bread&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;Cheese&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;/</span><span style="color:#22863A">ul</span><span style="color:#24292E">&gt;</span></span>
<span class="line"></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">h2</span><span style="color:#24292E">&gt;Glossary&lt;/</span><span style="color:#22863A">h2</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">dl</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">dt</span><span style="color:#24292E">&gt;HTML&lt;/</span><span style="color:#22863A">dt</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">dd</span><span style="color:#24292E">&gt;The foundation of web pages.&lt;/</span><span style="color:#22863A">dd</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">dt</span><span style="color:#24292E">&gt;CSS&lt;/</span><span style="color:#22863A">dt</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">dd</span><span style="color:#24292E">&gt;Used for styling web pages.&lt;/</span><span style="color:#22863A">dd</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">dt</span><span style="color:#24292E">&gt;JavaScript&lt;/</span><span style="color:#22863A">dt</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">dd</span><span style="color:#24292E">&gt;Adds interactivity to web pages.&lt;/</span><span style="color:#22863A">dd</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;/</span><span style="color:#22863A">dl</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">body</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">html</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<h2>Exercises</h2>
<ol>
<li><strong>Create a webpage outlining your favorite recipe.</strong> Use an <code>&lt;h1&gt;</code> for the recipe title, <code>&lt;h2&gt;</code> elements for sections like "Ingredients" and "Instructions," a <code>&lt;ul&gt;</code> for the ingredients list, and an <code>&lt;ol&gt;</code> for the numbered instructions.</li>
<li><strong>Build a webpage that presents a list of the world's tallest mountains.</strong> Use an <code>&lt;ol&gt;</code> to list the mountains in order of height. Include the mountain name and height.</li>
<li><strong>Design a webpage that defines common web development terms.</strong> Use a <code>&lt;dl&gt;</code> to define terms like "HTML," "CSS," and "JavaScript," providing a brief description for each.</li>
</ol>
<h2>Real-World Application</h2>
<p>Headings, paragraphs, and lists are fundamental to creating accessible and well-structured websites. Think about any website you visit regularly. News articles use headings to delineate sections, paragraphs to present the story, and lists to highlight key points or related articles. E-commerce sites use headings to organize product information, paragraphs to provide descriptions, and lists to showcase features or specifications. Blogs use headings to structure posts, paragraphs for content, and lists for related resources or tips. A good example is a recipe website, like Allrecipes, which utilizes all these elements to clearly present recipes.</p>
<p>Now consider a hypothetical scenario: You're tasked with redesigning the "About Us" page for a small business. The current page is a single, long block of text. To improve readability and engagement, you would use an <code>&lt;h1&gt;</code> for the company name, <code>&lt;h2&gt;</code> elements for sections like "Our Mission," "Our History," and "Our Team," paragraphs to elaborate on each section, and perhaps a <code>&lt;ul&gt;</code> to list the company's core values. This simple restructuring would significantly enhance the user experience.</p>
<p>By mastering these basic HTML elements, you gain the ability to structure and present content in a clear, logical, and user-friendly manner. This is a critical skill for any aspiring web developer.</p>
  
</div>

<div id="chapter-1.3">

<h1 class="mb-6 text-3xl font-semibold text-balance max-lg:mb-3 max-lg:text-xl">Working with Links and Images</h1><p>Working with links and images is fundamental to creating engaging and informative web content. Links allow users to navigate between different pages and websites, connecting them to a wealth of information. Images, on the other hand, add visual appeal and can convey information more effectively than text alone. Mastering these elements is crucial for building a user-friendly and visually rich website, contributing significantly to the overall user experience and helping to achieve website goals, whether it's informing visitors, selling products, or sharing ideas.</p>
<h2>Understanding Links in HTML</h2>
<p>Links, also known as hyperlinks, are the backbone of the internet. They allow users to navigate seamlessly between different web pages, websites, and even specific sections within a single page. In HTML, links are created using the <code>&lt;a&gt;</code> (anchor) element.</p>
<h3>The <code>&lt;a&gt;</code> Element</h3>
<p>The <code>&lt;a&gt;</code> element defines a hyperlink. The most important attribute of the <code>&lt;a&gt;</code> element is the <code>href</code> attribute, which specifies the destination of the link. The content between the opening <code>&lt;a&gt;</code> tag and the closing <code>&lt;/a&gt;</code> tag is what the user will see and click on.</p>
<p><strong>Basic Example:</strong></p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"https://www.example.com"</span><span style="color:#24292E">&gt;Visit Example&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<p>In this example, "Visit Example" is the clickable text. When a user clicks on this text, they will be taken to <code>https://www.example.com</code>.</p>
<p><strong>Explanation:</strong></p>
<ul>
<li><code>&lt;a href="…"&gt;</code>: This is the opening tag of the anchor element. The <code>href</code> attribute specifies the URL that the link points to.</li>
<li><code>Visit Example</code>: This is the text that will be displayed as the link.</li>
<li><code>&lt;/a&gt;</code>: This is the closing tag of the anchor element.</li>
</ul>
<h3>Absolute vs. Relative URLs</h3>
<p>The <code>href</code> attribute can contain either an absolute URL or a relative URL.</p>
<ul>
<li><strong>Absolute URL:</strong> An absolute URL specifies the full address of a web page, including the protocol (e.g., <code>https://</code>) and the domain name (e.g., <code>www.example.com</code>). Absolute URLs are used to link to pages on other websites.</li>
<li><strong>Relative URL:</strong> A relative URL specifies the path to a web page relative to the current page. Relative URLs are used to link to pages within the same website.</li>
</ul>
<p><strong>Examples:</strong></p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#6A737D">&lt;!-- Absolute URL --&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"https://www.example.com/about"</span><span style="color:#24292E">&gt;About Us&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;</span></span>
<span class="line"></span>
<span class="line"><span style="color:#6A737D">&lt;!-- Relative URL (assuming the linked page is in the same directory) --&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"about.html"</span><span style="color:#24292E">&gt;About Us&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;</span></span>
<span class="line"></span>
<span class="line"><span style="color:#6A737D">&lt;!-- Relative URL (linking to a page in a subdirectory) --&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"pages/contact.html"</span><span style="color:#24292E">&gt;Contact Us&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;</span></span>
<span class="line"></span>
<span class="line"><span style="color:#6A737D">&lt;!-- Relative URL (linking to a page in a parent directory) --&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"../index.html"</span><span style="color:#24292E">&gt;Back to Home&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<p><strong>Explanation:</strong></p>
<ul>
<li>The first example uses an absolute URL to link to the "About Us" page on <code>example.com</code>.</li>
<li>The second example uses a relative URL to link to a page named <code>about.html</code> in the same directory as the current page.</li>
<li>The third example uses a relative URL to link to a page named <code>contact.html</code> located in a subdirectory called "pages."</li>
<li>The fourth example uses a relative URL to link to the <code>index.html</code> page in the parent directory (one level up).  The <code>../</code> indicates moving one directory up.</li>
</ul>
<h3>The <code>target</code> Attribute</h3>
<p>The <code>target</code> attribute specifies where to open the linked document. Common values include:</p>
<ul>
<li><code>_self</code>: Opens the linked document in the same window/tab (this is the default).</li>
<li><code>_blank</code>: Opens the linked document in a new window/tab.</li>
<li><code>_parent</code>: Opens the linked document in the parent frame.</li>
<li><code>_top</code>: Opens the linked document in the full body of the window.</li>
</ul>
<p><strong>Example:</strong></p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"https://www.example.com"</span><span style="color:#6F42C1"> target</span><span style="color:#24292E">=</span><span style="color:#032F62">"_blank"</span><span style="color:#24292E">&gt;Visit Example in a New Tab&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<p>This link will open the <code>example.com</code> website in a new browser tab or window.</p>
<h3>Linking to Email Addresses</h3>
<p>You can also create links that open the user's email client using the <code>mailto:</code> scheme in the <code>href</code> attribute.</p>
<p><strong>Example:</strong></p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"mailto:info@example.com"</span><span style="color:#24292E">&gt;Email Us&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<p>When a user clicks this link, their default email client will open with a new email addressed to <code>info@example.com</code>.</p>
<p>You can also pre-populate the subject and body of the email:</p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"mailto:info@example.com?subject=Website%20Inquiry&amp;body=I%20have%20a%20question%20about..."</span><span style="color:#24292E">&gt;Email Us&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<p><strong>Explanation:</strong></p>
<ul>
<li><code>mailto:info@example.com</code>: This specifies the recipient's email address.</li>
<li><code>?subject=Website%20Inquiry</code>: This adds a subject line to the email.  The <code>%20</code> is the URL encoding for a space.</li>
<li><code>&amp;body=I%20have%20a%20question%20about...</code>: This adds a pre-filled body to the email.  Again, <code>%20</code> is used for spaces.</li>
</ul>
<h3>Linking to Sections Within a Page (Anchors)</h3>
<p>You can link to specific sections within the same page using anchors. First, you need to define an anchor point using the <code>id</code> attribute on an element. Then, you can create a link that points to that anchor using the <code>#</code> symbol followed by the <code>id</code> of the element.</p>
<p><strong>Example:</strong></p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#6A737D">&lt;!-- Defining the anchor point --&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">h2</span><span style="color:#6F42C1"> id</span><span style="color:#24292E">=</span><span style="color:#032F62">"section2"</span><span style="color:#24292E">&gt;Section 2&lt;/</span><span style="color:#22863A">h2</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;This is the content of section 2.&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"></span>
<span class="line"><span style="color:#6A737D">&lt;!-- Creating a link to the anchor --&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"#section2"</span><span style="color:#24292E">&gt;Go to Section 2&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<p>When the user clicks "Go to Section 2," the browser will scroll to the section with the <code>id</code> of "section2."</p>
<h3>Accessibility Considerations for Links</h3>
<ul>
<li><strong>Use descriptive link text:</strong> Avoid generic phrases like "click here." Instead, use text that clearly indicates the destination of the link.  For example, "Read more about our services" is better than "Click here."</li>
<li><strong>Provide context for screen readers:</strong> For complex links, use the <code>title</code> attribute to provide additional information for screen readers.  For example: <code>&lt;a href="example.pdf" title="Download our annual report (PDF)"&gt;Annual Report&lt;/a&gt;</code></li>
<li><strong>Ensure links are visually distinct:</strong> Use CSS to style links so they are easily identifiable as links.  Common styling includes a different color and underline.</li>
</ul>
<h2>Working with Images in HTML</h2>
<p>Images are an essential part of modern web design. They can enhance the visual appeal of a website, illustrate concepts, and provide context to the content. In HTML, images are embedded using the <code>&lt;img&gt;</code> element.</p>
<h3>The <code>&lt;img&gt;</code> Element</h3>
<p>The <code>&lt;img&gt;</code> element is a self-closing tag (meaning it doesn't have a separate closing tag). The most important attributes of the <code>&lt;img&gt;</code> element are <code>src</code> (source) and <code>alt</code> (alternative text).</p>
<ul>
<li><strong><code>src</code> attribute:</strong> Specifies the URL of the image.</li>
<li><strong><code>alt</code> attribute:</strong> Specifies alternative text for the image. This text is displayed if the image cannot be loaded, and it is also used by screen readers for accessibility.</li>
</ul>
<p><strong>Basic Example:</strong></p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">img</span><span style="color:#6F42C1"> src</span><span style="color:#24292E">=</span><span style="color:#032F62">"images/logo.png"</span><span style="color:#6F42C1"> alt</span><span style="color:#24292E">=</span><span style="color:#032F62">"Company Logo"</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<p><strong>Explanation:</strong></p>
<ul>
<li><code>&lt;img src="images/logo.png"...&gt;</code>: This specifies the source of the image. In this case, the image file is located in the "images" subdirectory and is named "logo.png."</li>
<li><code>alt="Company Logo"</code>: This provides alternative text for the image. If the image cannot be displayed (e.g., due to a broken link or slow connection), the text "Company Logo" will be displayed instead. This is also crucial for accessibility, as screen readers will use this text to describe the image to visually impaired users.</li>
<li><code>&gt;</code>: The <code>&lt;img&gt;</code> tag is self-closing, so there's no separate <code>&lt;/img&gt;</code> tag.</li>
</ul>
<h3>Image Formats</h3>
<p>Common image formats used on the web include:</p>
<ul>
<li><strong>JPEG (Joint Photographic Experts Group):</strong> Best for photographs and images with many colors.  JPEG uses lossy compression, which means some image quality is lost in exchange for smaller file sizes.</li>
<li><strong>PNG (Portable Network Graphics):</strong> Best for images with transparency, logos, and graphics with few colors. PNG uses lossless compression, which means no image quality is lost.</li>
<li><strong>GIF (Graphics Interchange Format):</strong> Best for simple animations and images with limited colors.  GIFs also support transparency.</li>
<li><strong>WebP:</strong> A modern image format developed by Google that provides excellent compression and quality.  It supports both lossy and lossless compression, as well as transparency and animation. WebP is becoming increasingly popular as a replacement for JPEG, PNG, and GIF.</li>
<li><strong>SVG (Scalable Vector Graphics):</strong> Best for logos, icons, and illustrations that need to be scaled without losing quality.  SVG is a vector-based format, which means images are defined using mathematical equations rather than pixels. This allows SVGs to be scaled to any size without becoming pixelated.  SVGs are also often smaller in file size than raster images (like JPEGs and PNGs).</li>
</ul>
<p><strong>Choosing the Right Format:</strong></p>
<ul>
<li>For photographs, use JPEG or WebP.</li>
<li>For logos, icons, and images with transparency, use PNG, WebP, or SVG.</li>
<li>For simple animations, use GIF or WebP.</li>
<li>If you need to scale an image without losing quality, use SVG.</li>
</ul>
<h3>Image Dimensions</h3>
<p>You can specify the width and height of an image using the <code>width</code> and <code>height</code> attributes. It's generally recommended to include these attributes to help the browser render the page faster.</p>
<p><strong>Example:</strong></p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">img</span><span style="color:#6F42C1"> src</span><span style="color:#24292E">=</span><span style="color:#032F62">"images/logo.png"</span><span style="color:#6F42C1"> alt</span><span style="color:#24292E">=</span><span style="color:#032F62">"Company Logo"</span><span style="color:#6F42C1"> width</span><span style="color:#24292E">=</span><span style="color:#032F62">"200"</span><span style="color:#6F42C1"> height</span><span style="color:#24292E">=</span><span style="color:#032F62">"100"</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<p><strong>Explanation:</strong></p>
<ul>
<li><code>width="200"</code>: This sets the width of the image to 200 pixels.</li>
<li><code>height="100"</code>: This sets the height of the image to 100 pixels.</li>
</ul>
<p>While you <em>can</em> use these attributes to resize the image, it's generally better to resize the image using CSS.  Using the <code>width</code> and <code>height</code> attributes simply tells the browser how much space to reserve for the image <em>before</em> it's downloaded, which can improve page load speed.  Resizing with CSS allows for more flexible and responsive layouts.  We'll cover CSS styling in a later module.</p>
<h3>Responsive Images</h3>
<p>In today's world, web pages are viewed on a wide range of devices, from smartphones to large desktop monitors. It's important to ensure that images are displayed correctly on all devices.  This is where responsive images come in.</p>
<p>The <code>&lt;picture&gt;</code> element and the <code>srcset</code> attribute of the <code>&lt;img&gt;</code> element are used to implement responsive images.  We won't go into detail here, as responsive design is covered in a later module, but it's important to be aware of these concepts.</p>
<h3>Accessibility Considerations for Images</h3>
<ul>
<li><strong>Always use the <code>alt</code> attribute:</strong>  The <code>alt</code> attribute is crucial for accessibility.  If the image is purely decorative, you can use an empty <code>alt</code> attribute (<code>alt=""</code>).  However, if the image conveys information, the <code>alt</code> attribute should provide a concise description of the image.</li>
<li><strong>Use descriptive <code>alt</code> text:</strong>  The <code>alt</code> text should accurately describe the content of the image.</li>
<li><strong>Consider using long descriptions:</strong>  For complex images, such as charts or graphs, you may need to provide a more detailed description.  This can be done using the <code>longdesc</code> attribute (which is less commonly used now) or by providing a text-based description elsewhere on the page and linking to it.</li>
</ul>
<h2>Practice Activities</h2>
<ol>
<li><strong>Create a Navigation Bar:</strong> Design a simple navigation bar for a website using <code>&lt;a&gt;</code> elements. Include links to "Home," "About," "Services," and "Contact." Use relative URLs for these links, assuming the pages are in the same directory.</li>
<li><strong>Image Gallery:</strong> Create a simple image gallery using <code>&lt;img&gt;</code> elements. Include at least three images with appropriate <code>alt</code> text. Experiment with different image formats (JPEG, PNG) and observe the differences in file size and quality.</li>
<li><strong>Email Link with Pre-filled Content:</strong> Create an email link that opens the user's email client with a pre-filled subject and body. The subject should be "Website Inquiry," and the body should include a placeholder for the user's question.</li>
<li><strong>Linking to Sections:</strong> Create a longer HTML document with several sections. Add links at the top of the page that allow users to jump to specific sections within the document using anchor links.</li>
<li><strong>Fix Broken Images:</strong> Find some images online and intentionally create broken image links in your HTML document (e.g., by changing the file name or path). Verify that the <code>alt</code> text is displayed correctly when the images cannot be loaded.</li>
</ol>
<h2>Next Steps and Future Learning Directions</h2>
<p>Now that you understand the fundamentals of working with links and images in HTML, you're well-prepared to enhance your web pages with navigation and visual content. As you continue your web development journey, consider exploring the following related topics:</p>
<ol>
<li><strong>CSS Styling for Links and Images:</strong> Learn how to use CSS to customize the appearance of links and images, including colors, fonts, hover effects, and image resizing.  This will be covered in Module 2.</li>
<li><strong>Responsive Images and Design:</strong> Explore techniques for creating responsive images that adapt to different screen sizes and devices, ensuring a consistent user experience across all platforms. This will be covered in Module 2.</li>
<li><strong>Image Optimization:</strong> Learn how to optimize images for the web to reduce file size and improve page load speed, using tools and techniques such as image compression and lazy loading.</li>
<li><strong>Advanced Link Techniques:</strong> Explore advanced link techniques such as using JavaScript to create dynamic links and handling link behavior with event listeners.</li>
</ol>
  
</div>

<div id="chapter-1.4">

<h1 class="mb-6 text-3xl font-semibold text-balance max-lg:mb-3 max-lg:text-xl">Introduction to HTML Forms and Input Elements</h1><p>HTML Forms: Gathering User Input</p>
<p>HTML forms are a fundamental part of web development, enabling you to collect data from users. Whether it's a simple search bar, a login form, or a complex survey, forms provide the interface for users to interact with your website and submit information. This lesson will introduce you to the core elements of HTML forms, focusing on the structure and different types of input elements available. Understanding how to create and use forms is essential for building interactive and dynamic web applications, especially as you move towards full-stack development.</p>
<h2>The <code>&lt;form&gt;</code> Element</h2>
<p>The foundation of any HTML form is the <code>&lt;form&gt;</code> element. It acts as a container for all the input elements and defines how the data will be submitted.</p>
<h3>Attributes of the <code>&lt;form&gt;</code> Element</h3>
<p>The <code>&lt;form&gt;</code> element has several important attributes that control its behavior:</p>
<ul>
<li><code>action</code>: Specifies the URL where the form data will be sent when the form is submitted. This is typically a server-side script (e.g., PHP, Node.js) that processes the data.</li>
<li><code>method</code>: Defines the HTTP method used to submit the form data. The two most common methods are <code>GET</code> and <code>POST</code>.
<ul>
<li><code>GET</code>: Sends the form data as part of the URL. This is suitable for small amounts of data and is often used for search forms.</li>
<li><code>POST</code>: Sends the form data in the body of the HTTP request. This is more secure and suitable for larger amounts of data, such as login credentials or uploaded files.</li>
</ul>
</li>
<li><code>target</code>: Specifies where to display the response after submitting the form. Common values include <code>_blank</code> (new tab or window), <code>_self</code> (current window), <code>_parent</code> (parent frame), and <code>_top</code> (full body of the window).</li>
<li><code>enctype</code>: Specifies the encoding type of the form data when using the <code>POST</code> method.
<ul>
<li><code>application/x-www-form-urlencoded</code> (default): Encodes all characters before sending.</li>
<li><code>multipart/form-data</code>: Required when the form includes file uploads.</li>
<li><code>text/plain</code>: Spaces are converted to "+" symbols, but no other characters are encoded. Not generally used.</li>
</ul>
</li>
<li><code>autocomplete</code>: Specifies whether the browser should automatically complete the form based on previous user input. Can be set to <code>on</code> or <code>off</code>.</li>
<li><code>novalidate</code>: Specifies that the form should not be validated when submitted. This is useful for custom validation using JavaScript.</li>
</ul>
<h3>Example of a <code>&lt;form&gt;</code> Element</h3>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">form</span><span style="color:#6F42C1"> action</span><span style="color:#24292E">=</span><span style="color:#032F62">"/submit-form"</span><span style="color:#6F42C1"> method</span><span style="color:#24292E">=</span><span style="color:#032F62">"POST"</span><span style="color:#6F42C1"> target</span><span style="color:#24292E">=</span><span style="color:#032F62">"_self"</span><span style="color:#6F42C1"> autocomplete</span><span style="color:#24292E">=</span><span style="color:#032F62">"on"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#6A737D">  &lt;!-- Input elements will go here --&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">form</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<p>In this example:</p>
<ul>
<li>The <code>action</code> attribute is set to <code>/submit-form</code>, which means the form data will be sent to this URL on the server.</li>
<li>The <code>method</code> attribute is set to <code>POST</code>, indicating that the data will be sent in the body of the HTTP request.</li>
<li>The <code>target</code> attribute is set to <code>_self</code>, meaning the response will be displayed in the same window.</li>
<li>The <code>autocomplete</code> attribute is set to <code>on</code>, enabling browser autocompletion.</li>
</ul>
<h2>Input Elements: Gathering Different Types of Data</h2>
<p>Inside the <code>&lt;form&gt;</code> element, you'll find various input elements. These elements allow users to enter different types of data, such as text, numbers, dates, and files.</p>
<h3>The <code>&lt;input&gt;</code> Element</h3>
<p>The <code>&lt;input&gt;</code> element is the most versatile form element. Its <code>type</code> attribute determines the type of input field to display.</p>
<h4>Common <code>&lt;input&gt;</code> Types</h4>
<ul>
<li>
<p><code>text</code>: A single-line text input field.</p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">label</span><span style="color:#6F42C1"> for</span><span style="color:#24292E">=</span><span style="color:#032F62">"firstName"</span><span style="color:#24292E">&gt;First Name:&lt;/</span><span style="color:#22863A">label</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">input</span><span style="color:#6F42C1"> type</span><span style="color:#24292E">=</span><span style="color:#032F62">"text"</span><span style="color:#6F42C1"> id</span><span style="color:#24292E">=</span><span style="color:#032F62">"firstName"</span><span style="color:#6F42C1"> name</span><span style="color:#24292E">=</span><span style="color:#032F62">"firstName"</span><span style="color:#6F42C1"> required</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">br</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">br</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<ul>
<li><code>id</code>: A unique identifier for the input field.  Crucial for linking the <code>&lt;label&gt;</code> element.</li>
<li><code>name</code>: The name of the input field, used when submitting the form data.  The server will use this name to identify the data.</li>
<li><code>required</code>: Specifies that the input field must be filled out before submitting the form.</li>
</ul>
</li>
<li>
<p><code>password</code>: A text input field where the entered text is masked for security.</p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">label</span><span style="color:#6F42C1"> for</span><span style="color:#24292E">=</span><span style="color:#032F62">"password"</span><span style="color:#24292E">&gt;Password:&lt;/</span><span style="color:#22863A">label</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">input</span><span style="color:#6F42C1"> type</span><span style="color:#24292E">=</span><span style="color:#032F62">"password"</span><span style="color:#6F42C1"> id</span><span style="color:#24292E">=</span><span style="color:#032F62">"password"</span><span style="color:#6F42C1"> name</span><span style="color:#24292E">=</span><span style="color:#032F62">"password"</span><span style="color:#6F42C1"> required</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">br</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">br</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<ul>
<li>The <code>password</code> type provides basic masking.  <em>It is not a substitute for proper server-side security.</em></li>
</ul>
</li>
<li>
<p><code>email</code>: A text input field that validates whether the entered text is a valid email address.</p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">label</span><span style="color:#6F42C1"> for</span><span style="color:#24292E">=</span><span style="color:#032F62">"email"</span><span style="color:#24292E">&gt;Email:&lt;/</span><span style="color:#22863A">label</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">input</span><span style="color:#6F42C1"> type</span><span style="color:#24292E">=</span><span style="color:#032F62">"email"</span><span style="color:#6F42C1"> id</span><span style="color:#24292E">=</span><span style="color:#032F62">"email"</span><span style="color:#6F42C1"> name</span><span style="color:#24292E">=</span><span style="color:#032F62">"email"</span><span style="color:#6F42C1"> required</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">br</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">br</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<ul>
<li>The browser will perform a basic email format check.</li>
</ul>
</li>
<li>
<p><code>number</code>: An input field that allows users to enter numbers.</p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">label</span><span style="color:#6F42C1"> for</span><span style="color:#24292E">=</span><span style="color:#032F62">"age"</span><span style="color:#24292E">&gt;Age:&lt;/</span><span style="color:#22863A">label</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">input</span><span style="color:#6F42C1"> type</span><span style="color:#24292E">=</span><span style="color:#032F62">"number"</span><span style="color:#6F42C1"> id</span><span style="color:#24292E">=</span><span style="color:#032F62">"age"</span><span style="color:#6F42C1"> name</span><span style="color:#24292E">=</span><span style="color:#032F62">"age"</span><span style="color:#6F42C1"> min</span><span style="color:#24292E">=</span><span style="color:#032F62">"0"</span><span style="color:#6F42C1"> max</span><span style="color:#24292E">=</span><span style="color:#032F62">"120"</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">br</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">br</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<ul>
<li><code>min</code>: Specifies the minimum allowed value.</li>
<li><code>max</code>: Specifies the maximum allowed value.</li>
</ul>
</li>
<li>
<p><code>date</code>: An input field that allows users to select a date from a calendar.</p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">label</span><span style="color:#6F42C1"> for</span><span style="color:#24292E">=</span><span style="color:#032F62">"birthdate"</span><span style="color:#24292E">&gt;Birthdate:&lt;/</span><span style="color:#22863A">label</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">input</span><span style="color:#6F42C1"> type</span><span style="color:#24292E">=</span><span style="color:#032F62">"date"</span><span style="color:#6F42C1"> id</span><span style="color:#24292E">=</span><span style="color:#032F62">"birthdate"</span><span style="color:#6F42C1"> name</span><span style="color:#24292E">=</span><span style="color:#032F62">"birthdate"</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">br</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">br</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
</li>
<li>
<p><code>file</code>: An input field that allows users to select a file from their computer.</p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">label</span><span style="color:#6F42C1"> for</span><span style="color:#24292E">=</span><span style="color:#032F62">"profilePicture"</span><span style="color:#24292E">&gt;Profile Picture:&lt;/</span><span style="color:#22863A">label</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">input</span><span style="color:#6F42C1"> type</span><span style="color:#24292E">=</span><span style="color:#032F62">"file"</span><span style="color:#6F42C1"> id</span><span style="color:#24292E">=</span><span style="color:#032F62">"profilePicture"</span><span style="color:#6F42C1"> name</span><span style="color:#24292E">=</span><span style="color:#032F62">"profilePicture"</span><span style="color:#6F42C1"> accept</span><span style="color:#24292E">=</span><span style="color:#032F62">"image/*"</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">br</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">br</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<ul>
<li><code>accept</code>: Specifies the types of files that the server accepts. <code>image/*</code> allows any image file type.</li>
</ul>
</li>
<li>
<p><code>radio</code>: A radio button, which allows users to select one option from a group of options.</p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;Gender:&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">input</span><span style="color:#6F42C1"> type</span><span style="color:#24292E">=</span><span style="color:#032F62">"radio"</span><span style="color:#6F42C1"> id</span><span style="color:#24292E">=</span><span style="color:#032F62">"male"</span><span style="color:#6F42C1"> name</span><span style="color:#24292E">=</span><span style="color:#032F62">"gender"</span><span style="color:#6F42C1"> value</span><span style="color:#24292E">=</span><span style="color:#032F62">"male"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">label</span><span style="color:#6F42C1"> for</span><span style="color:#24292E">=</span><span style="color:#032F62">"male"</span><span style="color:#24292E">&gt;Male&lt;/</span><span style="color:#22863A">label</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">br</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">input</span><span style="color:#6F42C1"> type</span><span style="color:#24292E">=</span><span style="color:#032F62">"radio"</span><span style="color:#6F42C1"> id</span><span style="color:#24292E">=</span><span style="color:#032F62">"female"</span><span style="color:#6F42C1"> name</span><span style="color:#24292E">=</span><span style="color:#032F62">"gender"</span><span style="color:#6F42C1"> value</span><span style="color:#24292E">=</span><span style="color:#032F62">"female"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">label</span><span style="color:#6F42C1"> for</span><span style="color:#24292E">=</span><span style="color:#032F62">"female"</span><span style="color:#24292E">&gt;Female&lt;/</span><span style="color:#22863A">label</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">br</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">input</span><span style="color:#6F42C1"> type</span><span style="color:#24292E">=</span><span style="color:#032F62">"radio"</span><span style="color:#6F42C1"> id</span><span style="color:#24292E">=</span><span style="color:#032F62">"other"</span><span style="color:#6F42C1"> name</span><span style="color:#24292E">=</span><span style="color:#032F62">"gender"</span><span style="color:#6F42C1"> value</span><span style="color:#24292E">=</span><span style="color:#032F62">"other"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">label</span><span style="color:#6F42C1"> for</span><span style="color:#24292E">=</span><span style="color:#032F62">"other"</span><span style="color:#24292E">&gt;Other&lt;/</span><span style="color:#22863A">label</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">br</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">br</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<ul>
<li>Radio buttons with the same <code>name</code> attribute belong to the same group, ensuring that only one can be selected.  The <code>value</code> attribute defines what value will be submitted if that radio button is selected.</li>
</ul>
</li>
<li>
<p><code>checkbox</code>: A checkbox, which allows users to select one or more options from a list of options.</p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;Interests:&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">input</span><span style="color:#6F42C1"> type</span><span style="color:#24292E">=</span><span style="color:#032F62">"checkbox"</span><span style="color:#6F42C1"> id</span><span style="color:#24292E">=</span><span style="color:#032F62">"coding"</span><span style="color:#6F42C1"> name</span><span style="color:#24292E">=</span><span style="color:#032F62">"interests"</span><span style="color:#6F42C1"> value</span><span style="color:#24292E">=</span><span style="color:#032F62">"coding"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">label</span><span style="color:#6F42C1"> for</span><span style="color:#24292E">=</span><span style="color:#032F62">"coding"</span><span style="color:#24292E">&gt;Coding&lt;/</span><span style="color:#22863A">label</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">br</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">input</span><span style="color:#6F42C1"> type</span><span style="color:#24292E">=</span><span style="color:#032F62">"checkbox"</span><span style="color:#6F42C1"> id</span><span style="color:#24292E">=</span><span style="color:#032F62">"design"</span><span style="color:#6F42C1"> name</span><span style="color:#24292E">=</span><span style="color:#032F62">"interests"</span><span style="color:#6F42C1"> value</span><span style="color:#24292E">=</span><span style="color:#032F62">"design"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">label</span><span style="color:#6F42C1"> for</span><span style="color:#24292E">=</span><span style="color:#032F62">"design"</span><span style="color:#24292E">&gt;Design&lt;/</span><span style="color:#22863A">label</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">br</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">input</span><span style="color:#6F42C1"> type</span><span style="color:#24292E">=</span><span style="color:#032F62">"checkbox"</span><span style="color:#6F42C1"> id</span><span style="color:#24292E">=</span><span style="color:#032F62">"music"</span><span style="color:#6F42C1"> name</span><span style="color:#24292E">=</span><span style="color:#032F62">"interests"</span><span style="color:#6F42C1"> value</span><span style="color:#24292E">=</span><span style="color:#032F62">"music"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">label</span><span style="color:#6F42C1"> for</span><span style="color:#24292E">=</span><span style="color:#032F62">"music"</span><span style="color:#24292E">&gt;Music&lt;/</span><span style="color:#22863A">label</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">br</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">br</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<ul>
<li>Unlike radio buttons, multiple checkboxes can be selected. The server-side script must be prepared to handle an array of values for a single name.</li>
</ul>
</li>
<li>
<p><code>submit</code>: A button that submits the form data to the server.</p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">input</span><span style="color:#6F42C1"> type</span><span style="color:#24292E">=</span><span style="color:#032F62">"submit"</span><span style="color:#6F42C1"> value</span><span style="color:#24292E">=</span><span style="color:#032F62">"Submit"</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<ul>
<li>The <code>value</code> attribute specifies the text that appears on the button.</li>
</ul>
</li>
<li>
<p><code>reset</code>: A button that resets the form fields to their default values.</p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">input</span><span style="color:#6F42C1"> type</span><span style="color:#24292E">=</span><span style="color:#032F62">"reset"</span><span style="color:#6F42C1"> value</span><span style="color:#24292E">=</span><span style="color:#032F62">"Reset"</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
</li>
<li>
<p><code>button</code>: A generic button.  It doesn't do anything on its own.  It's typically used with JavaScript to trigger custom actions.</p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">input</span><span style="color:#6F42C1"> type</span><span style="color:#24292E">=</span><span style="color:#032F62">"button"</span><span style="color:#6F42C1"> value</span><span style="color:#24292E">=</span><span style="color:#032F62">"Click Me"</span><span style="color:#6F42C1"> onclick</span><span style="color:#24292E">=</span><span style="color:#032F62">"</span><span style="color:#6F42C1">alert</span><span style="color:#032F62">('Button Clicked!')"</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<ul>
<li>The <code>onclick</code> attribute executes JavaScript code when the button is clicked.  Event handling will be covered in more detail in Module 3.</li>
</ul>
</li>
<li>
<p><code>hidden</code>: An input field that is not visible to the user. It's used to store data that needs to be submitted with the form but shouldn't be displayed.</p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">input</span><span style="color:#6F42C1"> type</span><span style="color:#24292E">=</span><span style="color:#032F62">"hidden"</span><span style="color:#6F42C1"> id</span><span style="color:#24292E">=</span><span style="color:#032F62">"userId"</span><span style="color:#6F42C1"> name</span><span style="color:#24292E">=</span><span style="color:#032F62">"userId"</span><span style="color:#6F42C1"> value</span><span style="color:#24292E">=</span><span style="color:#032F62">"12345"</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<ul>
<li>Hidden fields are often used to store user IDs, timestamps, or other data required for processing the form on the server.</li>
</ul>
</li>
</ul>
<h4>Attributes Common to Many <code>&lt;input&gt;</code> Types</h4>
<p>Besides the <code>type</code> attribute, many <code>&lt;input&gt;</code> types share common attributes:</p>
<ul>
<li><code>id</code>: A unique identifier for the input field.</li>
<li><code>name</code>: The name of the input field, used when submitting the form data.</li>
<li><code>value</code>: The initial value of the input field. For <code>text</code>, <code>email</code>, and <code>password</code> types, it sets the default text. For <code>radio</code> and <code>checkbox</code> types, it specifies the value that will be submitted when the option is selected.</li>
<li><code>placeholder</code>: Specifies a short hint that describes the expected value of the input field. The placeholder text is displayed inside the input field when it is empty.</li>
<li><code>required</code>: Specifies that the input field must be filled out before submitting the form.</li>
<li><code>disabled</code>: Disables the input field, preventing the user from interacting with it.</li>
<li><code>readonly</code>: Makes the input field read-only, allowing the user to see the value but not modify it.</li>
<li><code>maxlength</code>: Specifies the maximum number of characters allowed in an input field.</li>
<li><code>pattern</code>: Specifies a regular expression that the input field's value must match to be valid. Useful for custom input validation.</li>
</ul>
<h3>The <code>&lt;textarea&gt;</code> Element</h3>
<p>The <code>&lt;textarea&gt;</code> element is used for multi-line text input. It's ideal for collecting longer text responses, such as comments or descriptions.</p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">label</span><span style="color:#6F42C1"> for</span><span style="color:#24292E">=</span><span style="color:#032F62">"comment"</span><span style="color:#24292E">&gt;Comment:&lt;/</span><span style="color:#22863A">label</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">br</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">textarea</span><span style="color:#6F42C1"> id</span><span style="color:#24292E">=</span><span style="color:#032F62">"comment"</span><span style="color:#6F42C1"> name</span><span style="color:#24292E">=</span><span style="color:#032F62">"comment"</span><span style="color:#6F42C1"> rows</span><span style="color:#24292E">=</span><span style="color:#032F62">"4"</span><span style="color:#6F42C1"> cols</span><span style="color:#24292E">=</span><span style="color:#032F62">"50"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">Enter your comment here...</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">textarea</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<ul>
<li><code>rows</code>: Specifies the visible height of the text area (in lines).</li>
<li><code>cols</code>: Specifies the visible width of the text area (in characters).</li>
<li>The text between the opening and closing <code>&lt;textarea&gt;</code> tags is the default content of the text area.</li>
</ul>
<h3>The <code>&lt;select&gt;</code> Element</h3>
<p>The <code>&lt;select&gt;</code> element creates a dropdown list, allowing users to select one option from a predefined set of options.</p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">label</span><span style="color:#6F42C1"> for</span><span style="color:#24292E">=</span><span style="color:#032F62">"country"</span><span style="color:#24292E">&gt;Country:&lt;/</span><span style="color:#22863A">label</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">select</span><span style="color:#6F42C1"> id</span><span style="color:#24292E">=</span><span style="color:#032F62">"country"</span><span style="color:#6F42C1"> name</span><span style="color:#24292E">=</span><span style="color:#032F62">"country"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">option</span><span style="color:#6F42C1"> value</span><span style="color:#24292E">=</span><span style="color:#032F62">"usa"</span><span style="color:#24292E">&gt;United States&lt;/</span><span style="color:#22863A">option</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">option</span><span style="color:#6F42C1"> value</span><span style="color:#24292E">=</span><span style="color:#032F62">"canada"</span><span style="color:#24292E">&gt;Canada&lt;/</span><span style="color:#22863A">option</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">option</span><span style="color:#6F42C1"> value</span><span style="color:#24292E">=</span><span style="color:#032F62">"uk"</span><span style="color:#24292E">&gt;United Kingdom&lt;/</span><span style="color:#22863A">option</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">option</span><span style="color:#6F42C1"> value</span><span style="color:#24292E">=</span><span style="color:#032F62">"germany"</span><span style="color:#24292E">&gt;Germany&lt;/</span><span style="color:#22863A">option</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">select</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<ul>
<li>
<p>The <code>&lt;option&gt;</code> elements define the available options in the dropdown list.</p>
</li>
<li>
<p>The <code>value</code> attribute of each <code>&lt;option&gt;</code> element specifies the value that will be submitted when that option is selected.</p>
</li>
<li>
<p>The text between the opening and closing <code>&lt;option&gt;</code> tags is the text that the user sees in the dropdown list.</p>
</li>
<li>
<p>The <code>selected</code> attribute can be added to an <code>&lt;option&gt;</code> element to make it the default selected option when the page loads.</p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">option</span><span style="color:#6F42C1"> value</span><span style="color:#24292E">=</span><span style="color:#032F62">"usa"</span><span style="color:#6F42C1"> selected</span><span style="color:#24292E">&gt;United States&lt;/</span><span style="color:#22863A">option</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
</li>
</ul>
<h3>The <code>&lt;label&gt;</code> Element</h3>
<p>The <code>&lt;label&gt;</code> element provides a user-friendly caption for form elements. It's important for accessibility because it allows users to click on the label to focus on the associated input field.</p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">label</span><span style="color:#6F42C1"> for</span><span style="color:#24292E">=</span><span style="color:#032F62">"username"</span><span style="color:#24292E">&gt;Username:&lt;/</span><span style="color:#22863A">label</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">input</span><span style="color:#6F42C1"> type</span><span style="color:#24292E">=</span><span style="color:#032F62">"text"</span><span style="color:#6F42C1"> id</span><span style="color:#24292E">=</span><span style="color:#032F62">"username"</span><span style="color:#6F42C1"> name</span><span style="color:#24292E">=</span><span style="color:#032F62">"username"</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<ul>
<li>The <code>for</code> attribute of the <code>&lt;label&gt;</code> element must match the <code>id</code> attribute of the associated input field.  This is what creates the link between the label and the input.</li>
</ul>
<h2>Form Submission and Data Handling</h2>
<p>When a user submits a form, the data is sent to the URL specified in the <code>action</code> attribute of the <code>&lt;form&gt;</code> element. The <code>method</code> attribute determines how the data is sent (either <code>GET</code> or <code>POST</code>).</p>
<h3>GET Method</h3>
<p>With the <code>GET</code> method, the form data is appended to the URL as a query string. For example:</p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">javascript</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#D73A49">/</span><span style="color:#24292E">submit</span><span style="color:#D73A49">-</span><span style="color:#24292E">form</span><span style="color:#D73A49">?</span><span style="color:#24292E">firstName</span><span style="color:#D73A49">=</span><span style="color:#24292E">John</span><span style="color:#D73A49">&amp;</span><span style="color:#24292E">lastName</span><span style="color:#D73A49">=</span><span style="color:#24292E">Doe</span><span style="color:#D73A49">&amp;</span><span style="color:#24292E">email</span><span style="color:#D73A49">=</span><span style="color:#24292E">john.doe@example.com</span></span></code></pre></div></div></div>
<ul>
<li>The data is visible in the URL, which makes it less secure for sensitive information.</li>
<li>There's a limit to the amount of data that can be sent via the <code>GET</code> method.</li>
<li><code>GET</code> requests are typically used for retrieving data, not for submitting data.</li>
</ul>
<h3>POST Method</h3>
<p>With the <code>POST</code> method, the form data is sent in the body of the HTTP request. This is more secure and allows for larger amounts of data to be sent.</p>
<ul>
<li>The data is not visible in the URL.</li>
<li><code>POST</code> requests are typically used for creating, updating, or deleting data on the server.</li>
</ul>
<h3>Server-Side Handling</h3>
<p>Once the form data reaches the server, a server-side script (e.g., PHP, Node.js) processes the data. The script can perform tasks such as:</p>
<ul>
<li>Validating the data to ensure it meets the required criteria.</li>
<li>Storing the data in a database.</li>
<li>Sending an email confirmation to the user.</li>
<li>Redirecting the user to another page.</li>
</ul>
<h2>Exercises</h2>
<ol>
<li><strong>Create a Registration Form:</strong> Design an HTML form for user registration. Include fields for first name, last name, email, password, and a "Confirm Password" field. Add appropriate labels and use the <code>required</code> attribute for all fields. Use the correct input types (e.g., <code>email</code>, <code>password</code>).</li>
<li><strong>Implement Radio Buttons and Checkboxes:</strong> Add a section to the registration form to collect user preferences. Include radio buttons for selecting a preferred contact method (email or phone) and checkboxes for selecting interests (e.g., coding, design, music).</li>
<li><strong>Add a Textarea for Comments:</strong> Include a <code>&lt;textarea&gt;</code> element in the form for users to leave comments or feedback. Set the <code>rows</code> and <code>cols</code> attributes to appropriate values.</li>
<li><strong>Implement a Dropdown List:</strong> Add a <code>&lt;select&gt;</code> element to the form to allow users to select their country from a list of options. Include at least 5 countries in the list.</li>
<li><strong>Add File Upload Functionality:</strong> Include an <code>&lt;input type="file"&gt;</code> element to allow users to upload a profile picture. Use the <code>accept</code> attribute to specify that only image files should be accepted.</li>
<li><strong>Enhance Form Validation:</strong> Use the <code>pattern</code> attribute to add custom validation to the "Confirm Password" field. Ensure that it matches the password entered in the "Password" field. You will need to use JavaScript for a robust client-side validation in a real-world scenario, but the <code>pattern</code> attribute can provide a basic level of validation.</li>
</ol>
  
</div>

<div id="chapter-1.5">

<h1 class="mb-6 text-3xl font-semibold text-balance max-lg:mb-3 max-lg:text-xl">Semantic HTML: Improving Accessibility and SEO</h1><p>HTML provides semantic elements that communicate the meaning and purpose of content to both browsers and developers. These elements improve the structure of web pages, making them more understandable and accessible, as well as enhancing search engine optimization (SEO).</p>
<h2>Understanding Semantic HTML Elements</h2>
<p>Semantic HTML elements clearly describe the type of content they contain. Instead of generic <code>div</code> or <code>span</code> tags, semantic tags use names that describe their role on the page. For example, a header section uses <code>&lt;header&gt;</code>, navigation links use <code>&lt;nav&gt;</code>, and a main content area uses <code>&lt;main&gt;</code>.</p>
<h3>Common Semantic Elements</h3>
<ul>
<li>
<p><strong><code>&lt;header&gt;</code></strong>: Represents introductory content, usually containing heading elements, a logo, navigation, and other introductory information.</p>
<ul>
<li><em>Example 1 (Basic Header):</em></li>
</ul>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">header</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">h1</span><span style="color:#24292E">&gt;Website Title&lt;/</span><span style="color:#22863A">h1</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;A brief tagline&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">header</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<ul>
<li><em>Example 2 (Header with Navigation):</em></li>
</ul>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">header</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">img</span><span style="color:#6F42C1"> src</span><span style="color:#24292E">=</span><span style="color:#032F62">"logo.png"</span><span style="color:#6F42C1"> alt</span><span style="color:#24292E">=</span><span style="color:#032F62">"Company Logo"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">h1</span><span style="color:#24292E">&gt;My Awesome Blog&lt;/</span><span style="color:#22863A">h1</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">nav</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">ul</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"/"</span><span style="color:#24292E">&gt;Home&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"/about"</span><span style="color:#24292E">&gt;About&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"/contact"</span><span style="color:#24292E">&gt;Contact&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;/</span><span style="color:#22863A">ul</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;/</span><span style="color:#22863A">nav</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">header</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<p>In both examples, the <code>&lt;header&gt;</code> clearly indicates the top section of the page or a specific section within the page.</p>
</li>
<li>
<p><strong><code>&lt;nav&gt;</code></strong>: Represents a section of a page that contains navigation links, either to the current document or to other documents.</p>
<ul>
<li><em>Example 1 (Main Navigation):</em></li>
</ul>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">nav</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">ul</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"#home"</span><span style="color:#24292E">&gt;Home&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"#services"</span><span style="color:#24292E">&gt;Services&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"#portfolio"</span><span style="color:#24292E">&gt;Portfolio&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;/</span><span style="color:#22863A">ul</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">nav</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<ul>
<li><em>Example 2 (Secondary Navigation):</em></li>
</ul>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">aside</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">h3</span><span style="color:#24292E">&gt;Related Topics&lt;/</span><span style="color:#22863A">h3</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">nav</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">ul</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"/topic1"</span><span style="color:#24292E">&gt;Topic 1&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"/topic2"</span><span style="color:#24292E">&gt;Topic 2&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;/</span><span style="color:#22863A">ul</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;/</span><span style="color:#22863A">nav</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">aside</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<p>The <code>&lt;nav&gt;</code> element helps screen readers and search engines identify the primary navigation on a page.</p>
</li>
<li>
<p><strong><code>&lt;main&gt;</code></strong>: Represents the dominant content of the <code>&lt;body&gt;</code> of a document. It should be unique to the document and should not contain content that is repeated across documents like sidebars, navigation links, copyright information, or site logos. There should only be one <code>&lt;main&gt;</code> element per document.</p>
<ul>
<li><em>Example 1 (Simple Main Content):</em></li>
</ul>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">main</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">h2</span><span style="color:#24292E">&gt;Welcome to Our Website&lt;/</span><span style="color:#22863A">h2</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;This is the main content area of the page.&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">main</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<ul>
<li><em>Example 2 (Blog Post Main Content):</em></li>
</ul>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">main</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">article</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">h1</span><span style="color:#24292E">&gt;My First Blog Post&lt;/</span><span style="color:#22863A">h1</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;Published on &lt;</span><span style="color:#22863A">time</span><span style="color:#6F42C1"> datetime</span><span style="color:#24292E">=</span><span style="color:#032F62">"2023-10-27"</span><span style="color:#24292E">&gt;October 27, 2023&lt;/</span><span style="color:#22863A">time</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">section</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;</span><span style="color:#22863A">h3</span><span style="color:#24292E">&gt;Introduction&lt;/</span><span style="color:#22863A">h3</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;This is the intro paragraph...&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;/</span><span style="color:#22863A">section</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">section</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;</span><span style="color:#22863A">h3</span><span style="color:#24292E">&gt;Main Body&lt;/</span><span style="color:#22863A">h3</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;More detailed content...&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;/</span><span style="color:#22863A">section</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;/</span><span style="color:#22863A">article</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">main</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<p>The <code>&lt;main&gt;</code> element distinctly separates the primary content from supplementary information.</p>
</li>
<li>
<p><strong><code>&lt;article&gt;</code></strong>: Represents a self-contained composition in a document, page, application, or site, which is intended to be independently distributable or reusable (e.g., in syndication). Examples include a forum post, a magazine or newspaper article, a blog entry, a user-submitted comment, an interactive widget, or any other independent item of content.</p>
<ul>
<li><em>Example 1 (Blog Post):</em></li>
</ul>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">article</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">h2</span><span style="color:#24292E">&gt;The Benefits of Semantic HTML&lt;/</span><span style="color:#22863A">h2</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;By John Doe, &lt;</span><span style="color:#22863A">time</span><span style="color:#6F42C1"> datetime</span><span style="color:#24292E">=</span><span style="color:#032F62">"2023-10-27"</span><span style="color:#24292E">&gt;October 27, 2023&lt;/</span><span style="color:#22863A">time</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;Semantic HTML makes web pages more meaningful...&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">article</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<ul>
<li><em>Example 2 (Product Review):</em></li>
</ul>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">article</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">h3</span><span style="color:#24292E">&gt;Review: Super Widget Pro&lt;/</span><span style="color:#22863A">h3</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;Rating: ★★★★☆&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;This widget is amazing for its price...&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">article</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<p>An <code>&lt;article&gt;</code> wraps content that could stand alone, even if taken out of its surrounding context.</p>
</li>
<li>
<p><strong><code>&lt;section&gt;</code></strong>: Represents a standalone section of a document, which doesn't have a more specific semantic element to represent it. Sections typically have a heading.</p>
<ul>
<li><em>Example 1 (About Us Section):</em></li>
</ul>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">section</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">h2</span><span style="color:#24292E">&gt;About Us&lt;/</span><span style="color:#22863A">h2</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;We are a company dedicated to...&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">section</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<ul>
<li><em>Example 2 (Contact Section):</em></li>
</ul>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">section</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">h2</span><span style="color:#24292E">&gt;Contact Information&lt;/</span><span style="color:#22863A">h2</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;Email: info@example.com&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;Phone: 123-456-7890&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">section</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<p>A <code>&lt;section&gt;</code> is used to group related content, often with its own heading.</p>
</li>
<li>
<p><strong><code>&lt;aside&gt;</code></strong>: Represents a portion of a document whose content is only indirectly related to the document's main content. Asides are frequently presented as sidebars or call-out boxes.</p>
<ul>
<li><em>Example 1 (Related Links Sidebar):</em></li>
</ul>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">aside</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">h3</span><span style="color:#24292E">&gt;Read More&lt;/</span><span style="color:#22863A">h3</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">ul</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"/another-article"</span><span style="color:#24292E">&gt;Another Article&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"/related-post"</span><span style="color:#24292E">&gt;Related Post&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;/</span><span style="color:#22863A">ul</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">aside</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<ul>
<li><em>Example 2 (Advertisement):</em></li>
</ul>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">aside</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;Ad: Check out our new product!&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">img</span><span style="color:#6F42C1"> src</span><span style="color:#24292E">=</span><span style="color:#032F62">"ad-image.jpg"</span><span style="color:#6F42C1"> alt</span><span style="color:#24292E">=</span><span style="color:#032F62">"Advertisement"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">aside</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<p>An <code>&lt;aside&gt;</code> is ideal for tangential content.</p>
</li>
<li>
<p><strong><code>&lt;footer&gt;</code></strong>: Represents a footer for its nearest sectioning content (e.g., <code>&lt;article&gt;</code>, <code>&lt;section&gt;</code>, or <code>&lt;body&gt;</code>). A footer typically contains information about the author, copyright data, links to related documents, or disclaimers.</p>
<ul>
<li><em>Example 1 (Simple Page Footer):</em></li>
</ul>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">footer</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span><span style="color:#005CC5">&amp;copy;</span><span style="color:#24292E"> 2023 My Company. All rights reserved.&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">footer</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<ul>
<li><em>Example 2 (Detailed Footer):</em></li>
</ul>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">footer</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">nav</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">ul</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"/privacy"</span><span style="color:#24292E">&gt;Privacy Policy&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"/terms"</span><span style="color:#24292E">&gt;Terms of Service&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;/</span><span style="color:#22863A">ul</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;/</span><span style="color:#22863A">nav</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">address</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    Contact us at &lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"mailto:info@example.com"</span><span style="color:#24292E">&gt;info@example.com&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;/</span><span style="color:#22863A">address</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;Last updated: &lt;</span><span style="color:#22863A">time</span><span style="color:#6F42C1"> datetime</span><span style="color:#24292E">=</span><span style="color:#032F62">"2023-10-27"</span><span style="color:#24292E">&gt;October 27, 2023&lt;/</span><span style="color:#22863A">time</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">footer</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<p>The <code>&lt;footer&gt;</code> element marks the bottom section of a page or a content block.</p>
</li>
<li>
<p><strong><code>&lt;figure&gt;</code> and <code>&lt;figcaption&gt;</code></strong>: The <code>&lt;figure&gt;</code> element is used to encapsulate media content such as images, diagrams, code snippets, etc., that is referenced from the main flow of the document but can be moved to another part of the document or to an appendix without affecting the main flow. The <code>&lt;figcaption&gt;</code> element provides a caption or legend for the content of its parent <code>&lt;figure&gt;</code> element.</p>
<ul>
<li><em>Example 1 (Image with Caption):</em></li>
</ul>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">figure</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">img</span><span style="color:#6F42C1"> src</span><span style="color:#24292E">=</span><span style="color:#032F62">"chart.png"</span><span style="color:#6F42C1"> alt</span><span style="color:#24292E">=</span><span style="color:#032F62">"Sales growth chart"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">figcaption</span><span style="color:#24292E">&gt;Figure 1: Quarterly sales growth.&lt;/</span><span style="color:#22863A">figcaption</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">figure</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<ul>
<li><em>Example 2 (Code Block with Caption):</em></li>
</ul>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">figure</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">pre</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">code</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    function greet(name) {</span></span>
<span class="line"><span style="color:#24292E">      console.log(`Hello, ${name}!`);</span></span>
<span class="line"><span style="color:#24292E">    }</span></span>
<span class="line"><span style="color:#24292E">    greet("World");</span></span>
<span class="line"><span style="color:#24292E">  &lt;/</span><span style="color:#22863A">code</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">pre</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">figcaption</span><span style="color:#24292E">&gt;Code Example 1: A simple JavaScript function.&lt;/</span><span style="color:#22863A">figcaption</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">figure</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<p>These elements associate a caption with an image or other media, making the content more understandable.</p>
</li>
</ul>
<h3>Why Semantic HTML Matters</h3>
<ol>
<li>
<p><strong>Accessibility</strong>: Semantic elements provide meaning to screen readers and other assistive technologies. A screen reader can announce "navigation" when it encounters a <code>&lt;nav&gt;</code> element, helping users with visual impairments understand the page structure. Without semantic tags, the page might just be a collection of <code>div</code>s, making it harder for assistive technologies to interpret.</p>
<ul>
<li><em>Hypothetical Scenario:</em> Imagine a user with a screen reader trying to navigate a website built entirely with <code>div</code>s and <code>span</code>s. The screen reader would simply announce "division," "division," "paragraph," "division," making it nearly impossible to quickly jump to the main content or navigation. With semantic tags, the screen reader can announce "banner region," "navigation region," "main content region," allowing the user to understand the page layout and jump to desired sections.</li>
</ul>
</li>
<li>
<p><strong>Search Engine Optimization (SEO)</strong>: Search engines use semantic HTML to understand the context and hierarchy of content on a web page. When search engine bots crawl a page, they give more weight to content within semantic tags like <code>&lt;main&gt;</code>, <code>&lt;article&gt;</code>, and headings (<code>&lt;h1&gt;</code> to <code>&lt;h6&gt;</code>). This helps them rank the page more accurately for relevant search queries.</p>
<ul>
<li><em>Real-world Example:</em> A news website uses <code>&lt;article&gt;</code> for each news story and <code>&lt;h1&gt;</code> for the headline. Search engines will understand that the content inside <code>&lt;article&gt;</code> is a distinct, important piece of information, and the <code>&lt;h1&gt;</code> is the primary topic of that article, leading to better indexing and potentially higher rankings for relevant keywords compared to using a <code>div</code> for the article and a <code>p</code> for the headline.</li>
<li><em>Real-world Example:</em> An e-commerce site uses a <code>&lt;footer&gt;</code> for copyright information, legal links, and contact details. Search engines recognize this as auxiliary information, correctly prioritizing the product details in the <code>&lt;main&gt;</code> section over the footer content when determining the primary topic of the page.</li>
</ul>
</li>
<li>
<p><strong>Developer Readability and Maintainability</strong>: Semantic HTML makes code easier for developers to read, understand, and maintain. When reviewing a page, seeing a <code>&lt;nav&gt;</code> tag immediately tells a developer that the enclosed content is for navigation, rather than having to infer its purpose from class names like <code>class="main-nav-bar"</code>.</p>
<ul>
<li><em>Real-world Example:</em> A team of developers is working on a large web application. If one developer uses <code>div class="top-section"</code> and another uses <code>&lt;header&gt;</code>, the developer using <code>&lt;header&gt;</code> provides clearer intent. When a new developer joins the team, they can quickly grasp the structure of the HTML by looking at the semantic tags, reducing the learning curve and potential for errors during maintenance or feature additions.</li>
</ul>
</li>
</ol>
<h2>Practical Examples and Demonstrations</h2>
<p>Let's refine a non-semantic HTML structure into a semantic one.</p>
<h3>Non-Semantic Structure (Bad Practice)</h3>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">body</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">div</span><span style="color:#6F42C1"> id</span><span style="color:#24292E">=</span><span style="color:#032F62">"header"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">img</span><span style="color:#6F42C1"> src</span><span style="color:#24292E">=</span><span style="color:#032F62">"logo.png"</span><span style="color:#6F42C1"> alt</span><span style="color:#24292E">=</span><span style="color:#032F62">"Company Logo"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">h1</span><span style="color:#24292E">&gt;My Website&lt;/</span><span style="color:#22863A">h1</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">div</span><span style="color:#6F42C1"> class</span><span style="color:#24292E">=</span><span style="color:#032F62">"menu"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;</span><span style="color:#22863A">ul</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">        &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"/"</span><span style="color:#24292E">&gt;Home&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">        &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"/products"</span><span style="color:#24292E">&gt;Products&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">        &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"/about"</span><span style="color:#24292E">&gt;About&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;/</span><span style="color:#22863A">ul</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;/</span><span style="color:#22863A">div</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;/</span><span style="color:#22863A">div</span><span style="color:#24292E">&gt;</span></span>
<span class="line"></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">div</span><span style="color:#6F42C1"> id</span><span style="color:#24292E">=</span><span style="color:#032F62">"content"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">div</span><span style="color:#6F42C1"> class</span><span style="color:#24292E">=</span><span style="color:#032F62">"main-article"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;</span><span style="color:#22863A">h2</span><span style="color:#24292E">&gt;Welcome to our Page&lt;/</span><span style="color:#22863A">h2</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;This is the main content of the page.&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;/</span><span style="color:#22863A">div</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">div</span><span style="color:#6F42C1"> class</span><span style="color:#24292E">=</span><span style="color:#032F62">"sidebar"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;</span><span style="color:#22863A">h3</span><span style="color:#24292E">&gt;Quick Links&lt;/</span><span style="color:#22863A">h3</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;</span><span style="color:#22863A">ul</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">        &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"/faq"</span><span style="color:#24292E">&gt;FAQ&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">        &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"/blog"</span><span style="color:#24292E">&gt;Blog&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;/</span><span style="color:#22863A">ul</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;/</span><span style="color:#22863A">div</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;/</span><span style="color:#22863A">div</span><span style="color:#24292E">&gt;</span></span>
<span class="line"></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">div</span><span style="color:#6F42C1"> id</span><span style="color:#24292E">=</span><span style="color:#032F62">"footer"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span><span style="color:#005CC5">&amp;copy;</span><span style="color:#24292E"> 2023 My Website&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;/</span><span style="color:#22863A">div</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">body</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<p><strong>Explanation of Issues:</strong></p>
<ul>
<li><code>div</code> with <code>id="header"</code> or <code>class="menu"</code> doesn't convey intrinsic meaning about the content type. It relies on IDs/classes for styling and JavaScript behavior, not for meaning.</li>
<li><code>div</code> with <code>id="content"</code> wraps the main content and sidebar without clearly differentiating their roles.</li>
<li><code>div</code> with <code>class="main-article"</code> is a descriptive class, but <code>article</code> is a more specific semantic element.</li>
<li><code>div</code> with <code>class="sidebar"</code> is descriptive, but <code>aside</code> is semantically more appropriate.</li>
<li><code>div</code> with <code>id="footer"</code> again relies on an ID rather than a semantic tag.</li>
</ul>
<h3>Semantic Structure (Good Practice)</h3>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">body</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">header</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">img</span><span style="color:#6F42C1"> src</span><span style="color:#24292E">=</span><span style="color:#032F62">"logo.png"</span><span style="color:#6F42C1"> alt</span><span style="color:#24292E">=</span><span style="color:#032F62">"Company Logo"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">h1</span><span style="color:#24292E">&gt;My Website&lt;/</span><span style="color:#22863A">h1</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">nav</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;</span><span style="color:#22863A">ul</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">        &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"/"</span><span style="color:#24292E">&gt;Home&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">        &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"/products"</span><span style="color:#24292E">&gt;Products&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">        &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"/about"</span><span style="color:#24292E">&gt;About&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;/</span><span style="color:#22863A">ul</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;/</span><span style="color:#22863A">nav</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;/</span><span style="color:#22863A">header</span><span style="color:#24292E">&gt;</span></span>
<span class="line"></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">main</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">article</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;</span><span style="color:#22863A">h2</span><span style="color:#24292E">&gt;Welcome to our Page&lt;/</span><span style="color:#22863A">h2</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;This is the main content of the page.&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;/</span><span style="color:#22863A">article</span><span style="color:#24292E">&gt;</span></span>
<span class="line"></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">aside</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;</span><span style="color:#22863A">h3</span><span style="color:#24292E">&gt;Quick Links&lt;/</span><span style="color:#22863A">h3</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;</span><span style="color:#22863A">nav</span><span style="color:#24292E">&gt; </span><span style="color:#6A737D">&lt;!-- Using nav inside aside for a related navigation block --&gt;</span></span>
<span class="line"><span style="color:#24292E">        &lt;</span><span style="color:#22863A">ul</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">          &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"/faq"</span><span style="color:#24292E">&gt;FAQ&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">          &lt;</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"/blog"</span><span style="color:#24292E">&gt;Blog&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">li</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">        &lt;/</span><span style="color:#22863A">ul</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">      &lt;/</span><span style="color:#22863A">nav</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;/</span><span style="color:#22863A">aside</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;/</span><span style="color:#22863A">main</span><span style="color:#24292E">&gt;</span></span>
<span class="line"></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">footer</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span><span style="color:#005CC5">&amp;copy;</span><span style="color:#24292E"> 2023 My Website&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;/</span><span style="color:#22863A">footer</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">body</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<p><strong>Explanation of Improvements:</strong></p>
<ul>
<li>The <code>header</code> element clearly defines the top introductory section.</li>
<li>The <code>nav</code> element explicitly marks the primary navigation menu.</li>
<li>The <code>main</code> element contains the dominant content of the page.</li>
<li>The <code>article</code> element encapsulates the self-contained "Welcome" content.</li>
<li>The <code>aside</code> element groups the "Quick Links" as tangential content.</li>
<li>The <code>footer</code> element clearly indicates the bottom section of the page.</li>
</ul>
<p>This semantic version uses elements that inherently describe the content they contain, making the HTML more meaningful for browsers, search engines, and developers.</p>
<h2>Exercises</h2>
<ol>
<li>
<p><strong>Identify and Replace Non-Semantic Elements:</strong>
Consider the following HTML snippet from a hypothetical online course platform. Your task is to rewrite this snippet using appropriate semantic HTML elements where possible.</p>
<div class="not-prose my-6 max-w-full overflow-hidden rounded-lg border border-gray-200 has-[code:empty]:hidden"><div class="flex items-center justify-between gap-2 border-b border-gray-200 bg-gray-50 px-3 py-2"><span class="text-sm text-gray-600">html</span><div class="flex items-center gap-2"><button class="flex size-6 items-center justify-center gap-2 rounded-md text-gray-400 hover:bg-zinc-200 hover:text-black focus:outline-none"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-copy size-3.5" aria-hidden="true"><rect width="14" height="14" x="8" y="8" rx="2" ry="2"></rect><path d="M4 16c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2"></path></svg></button></div></div><div class="mt-0 text-sm [&amp;_pre]:py-0 [&amp;_pre]:grid [&amp;_code]:py-4 [&amp;_code]:w-full [&amp;_code]:grid [&amp;_code]:overflow-x-auto [&amp;_code]:no-scrollbar [&amp;_code]:bg-transparent [&amp;_.line]:px-3 [&amp;_.line]:w-full [&amp;_.line]:relative [&amp;_.line]:min-h-5"><div><pre class="shiki github-light" style="background-color:#fff;color:#24292e" tabindex="0"><code><span class="line"><span style="color:#24292E">&lt;</span><span style="color:#22863A">div</span><span style="color:#6F42C1"> class</span><span style="color:#24292E">=</span><span style="color:#032F62">"course-listing"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">div</span><span style="color:#6F42C1"> class</span><span style="color:#24292E">=</span><span style="color:#032F62">"course-title"</span><span style="color:#24292E">&gt;Mastering HTML Basics&lt;/</span><span style="color:#22863A">div</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">div</span><span style="color:#6F42C1"> class</span><span style="color:#24292E">=</span><span style="color:#032F62">"course-instructor"</span><span style="color:#24292E">&gt;Taught by Jane Doe&lt;/</span><span style="color:#22863A">div</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">div</span><span style="color:#6F42C1"> class</span><span style="color:#24292E">=</span><span style="color:#032F62">"course-description"</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;Learn the fundamental building blocks of the web.&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">    &lt;</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;Covers headings, paragraphs, lists, and links.&lt;/</span><span style="color:#22863A">p</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;/</span><span style="color:#22863A">div</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">  &lt;</span><span style="color:#22863A">div</span><span style="color:#6F42C1"> class</span><span style="color:#24292E">=</span><span style="color:#032F62">"course-button"</span><span style="color:#24292E">&gt;&lt;</span><span style="color:#22863A">a</span><span style="color:#6F42C1"> href</span><span style="color:#24292E">=</span><span style="color:#032F62">"/enroll/html-basics"</span><span style="color:#24292E">&gt;Enroll Now&lt;/</span><span style="color:#22863A">a</span><span style="color:#24292E">&gt;&lt;/</span><span style="color:#22863A">div</span><span style="color:#24292E">&gt;</span></span>
<span class="line"><span style="color:#24292E">&lt;/</span><span style="color:#22863A">div</span><span style="color:#24292E">&gt;</span></span></code></pre></div></div></div>
<p><strong>Solution Guide:</strong></p>
<ul>
<li>Think about what each <code>div</code> represents in terms of content type.</li>
<li>Is <code>course-listing</code> a self-contained piece of content?</li>
<li>Is <code>course-title</code> a heading?</li>
<li>Is <code>course-description</code> a distinct section or part of a larger content block?</li>
<li>Is <code>course-button</code> a part of the content or an action related to the content?</li>
</ul>
</li>
<li>
<p><strong>Structure a Blog Post Page:</strong>
Imagine you are building a single blog post page. Without writing the actual text content, create the semantic HTML structure for this page. The page should include:</p>
<ul>
<li>A main site header (with a logo and main navigation).</li>
<li>The main content area for the blog post itself.</li>
<li>Inside the blog post:
<ul>
<li>The post title.</li>
<li>Author and publication date information.</li>
<li>Several paragraphs of text.</li>
<li>An image with a caption.</li>
<li>A section for comments.</li>
</ul>
</li>
<li>A sidebar with "Recent Posts" links.</li>
<li>A site footer with copyright info and social media links.</li>
</ul>
<p><strong>Solution Guide:</strong></p>
<ul>
<li>Start with <code>&lt;body&gt;</code> and think about the major sections.</li>
<li>What element should wrap the entire blog post content?</li>
<li>What element is suitable for the "Recent Posts" sidebar?</li>
<li>How would you structure the author/date information?</li>
<li>What elements are appropriate for the image and its caption?</li>
<li>What about the site-wide navigation and footer?</li>
</ul>
</li>
</ol>
<h2>Real-World Application</h2>
<p>The impact of semantic HTML extends across various types of websites.</p>
<ol>
<li>
<p><strong>News Portals and Blogs</strong>: Major news websites like <em>The New York Times</em> or tech blogs often use <code>&lt;article&gt;</code> tags for individual news stories or blog posts. This allows search engines to easily identify distinct pieces of content, improving how these articles are indexed and ranked. When a user searches for a specific news event or topic, the semantic structure helps search engines pinpoint the most relevant articles. Furthermore, RSS feeds and other content syndication services rely on this clear structure to extract and display content accurately across different platforms. Without <code>&lt;article&gt;</code>, these systems would struggle to programmatically understand where one news item ends and another begins, potentially leading to fragmented or incorrectly displayed content.</p>
</li>
<li>
<p><strong>E-commerce Websites</strong>: Online stores like <em>Amazon</em> or <em>Etsy</em> heavily use semantic HTML. Each product listing often resides within an <code>&lt;article&gt;</code> or a <code>&lt;section&gt;</code>, complete with <code>&lt;h1&gt;</code> for the product name, <code>&lt;figure&gt;</code> for product images, and potentially <code>&lt;details&gt;</code> for expandable descriptions. This semantic markup helps search engines understand the product's name, description, and images, leading to better product visibility in search results. For example, when searching for "wireless headphones," the semantic structure on an e-commerce site allows search engines to quickly extract product titles, reviews, and pricing, displaying rich snippets directly in the search results and guiding users to the most relevant products. It also aids screen readers in clearly distinguishing product details for visually impaired users who are trying to make a purchase.</p>
</li>
</ol>
  
</div>

</div>

<div id="chapter-2">

<div id="chapter-2.1">


  
</div>

<div id="chapter-2.2">


  
</div>

<div id="chapter-2.3">


  
</div>

<div id="chapter-2.4">


  
</div>

<div id="chapter-2.5">


  
</div>

<div id="chapter-2.6">


  
</div>



</div>

<div id="chapter-3">

<div id="chapter-3.1">


  
</div>

<div id="chapter-3.2">


  
</div>

<div id="chapter-3.3">


  
</div>

<div id="chapter-3.4">


  
</div>

<div id="chapter-3.5">


  
</div>


</div>

<div id="chapter-4">

<div id="chapter-4.1">


  
</div>

<div id="chapter-4.2">


  
</div>

<div id="chapter-4.3">


  
</div>

<div id="chapter-4.4">


  
</div>

<div id="chapter-4.5">


  
</div>


</div>

<div id="chapter-5">

<div id="chapter-5.1">


  
</div>

<div id="chapter-5.2">


  
</div>

<div id="chapter-5.3">


  
</div>

<div id="chapter-5.4">


  
</div>

<div id="chapter-5.5">


  
</div>


</div>

<div id="chapter-6">

<div id="chapter-6.1">


  
</div>

<div id="chapter-6.2">


  
</div>

<div id="chapter-6.3">


  
</div>

<div id="chapter-6.4">


  
</div>

<div id="chapter-6.5">


  
</div>


</div>

<div id="chapter-7">

<div id="chapter-7.1">


  
</div>

<div id="chapter-7.2">


  
</div>

<div id="chapter-7.3">


  
</div>

<div id="chapter-7.4">


  
</div>

<div id="chapter-7.5">


  
</div>


</div>
