# HTML Elzero

# Week One

## 1- Introduction and What I Need To Learn

- HTML:
    - HyperText Markup Language.
    - The language to build the web.
    - Skeleton.

## 2- Elements and Browser

- Download any editor you want (VSC, Atom, etc..).

## 3- First Project and First Page

- meta-data
    - information about information.

```html
<html>
	<head>
		<title>Book Store</title>
	</head>
	<body>
		This is my Book Store, Welocme!
	</body>
</html>

```

## 4- Head and Nested Elements

```html
<html>
	<head>
		<meta charset="UTF-8" />
		<title>Book Store</title>
		<meta name="description" content="This is our book store!" />
		<style></style>
		<script></script>
		<link rel="stylesheet" href="" />
	</head>
	<body>
		This is my Book Store, Welocme!
	</body>
</html>
```

## 5- Comments and Use Cases

```html
<html>
	<head>
		<meta charset="UTF-8" />
		<title>Book Store</title>
		<meta name="description" content="This is our book store!" />
		<!-- This is a comment -->
		<style></style>
		<script></script>
		<link rel="stylesheet" href="" />
	</head>
	<body>
		This is my Book Store, Welocme!
	</body>
</html>
```

## 6- DOCTYPE, Standard and Quirks Mode

- DOCTYPE:
    - used to specify the version of HTML.
    - render the page in standard mode.

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8" />
		<title>Book Store</title>
		<meta name="description" content="This is our book store!" />
		<!-- This is a comment -->
		<style></style>
		<script></script>
		<link rel="stylesheet" href="" />
	</head>
	<body>
		This is my Book Store, Welocme!
	</body>
</html>
```

## 7- Headings and Use Cases

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8" />
		<title>Book Store</title>
		<meta name="description" content="This is our book store!" />
	</head>
	<body>
		<!-- h1 : h6-->
		<!-- h1 => Better not to repeat it in the page -->
		<h1>Book Store</h1>
		<h2>Chapter Title Inside Book</h2>
		<h3>Story Title Inside Chapter</h3>
		This is my Book Store, Welocme!
	</body>
</html>
```

## 8- Syntax and Tests

- Browser ignores spaces.

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8" />
		<title>Book Store</title>
		<meta name="description" content="This is our book store!" />
	</head>
	<body>
		<h1>Book Store</h1>
		This is my Book Store, Welocme!
	</body>
</html>
```

## 9- Paragraph Element

- block element.

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8" />
		<title>Book Store</title>
		<meta name="description" content="This is our book store!" />
	</head>
	<body>
		<h1>Book Store</h1>
		<p>This is my Book Store, Welocme!</p>
		<p>We have a big SALE.</p>
	</body>
</html>
```

## 10- Elements Attributes

- global attributes.
    - class.
    - hidden.
- element attributes.
    - src.
    - alt.
    - rel.
    - stylesheet.

## 11- Formatting Elements

- <b> ⇒ bold.
- <strong> ⇒ bold (important text).
- <i> ⇒ italic.
- <em> ⇒ emphasized.
- <mark>
- <u> ⇒ underline.
- <small> ⇒ smaller text.
- <del> ⇒ deleted text.
- <ins> ⇒ inserted text.
- <sub> ⇒ subscript.
- <sup> ⇒ superscript.

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8" />
		<title>Book Store</title>
		<meta name="description" content="This is our book store!" />
	</head>
	<body>
		<h1>Book Store</h1>
		<p>This is my <b>Book Store</b>. Welocme!</p>
		<p>This is my <strong>Book Store</strong>. Welocme!</p>
		<p>This is my <i>Book Store</i>. Welocme!</p>
		<p>This is my <em>Book Store</em>. Welocme!</p>
		<p>This is my Book Store. <mark>Welocme!</mark></p>
		<p>This is my Book Store. <u>Welocme!</u></p>
		<p>This is my Book Store. <small>Welocme!</small></p>
		<p><del>$100</del> $50</p>
		<p>This is my <ins>Book Store</ins>. Welocme!</p>
		<p>H<sub>2</sub>O</p>
		<p>2<sup>2</sup></p>
	</body>
</html>

```

## 12- Links Anchor Tag

- inline element.

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8" />
		<title>Book Store</title>
		<meta name="description" content="This is our book store!" />
	</head>
	<body>
		<h1>Book Store</h1>
		<p>This is my <b>Book Store</b>. Welocme!</p>
		<a href="https://google.com" target="_blank" title="Go to google">Google</a>
		<a href="https://facebook.com" target="_blank" title="Go to facebook"
			>Facebook</a
		>
		<a href="#special" title="Go to special paragraph">Special Paragraph</a>
		<a href="mailto:zeinazayed4@gmail.com">Contact Us</a>
		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia ratione
			fugit eaque commodi? Nemo vero earum totam saepe qui magni ea deleniti
			laborum molestiae maxime, consequatur tenetur reprehenderit cupiditate
			eos?
		</p>
		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia ratione
			fugit eaque commodi? Nemo vero earum totam saepe qui magni ea deleniti
			laborum molestiae maxime, consequatur tenetur reprehenderit cupiditate
			eos?
		</p>
		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia ratione
			fugit eaque commodi? Nemo vero earum totam saepe qui magni ea deleniti
			laborum molestiae maxime, consequatur tenetur reprehenderit cupiditate
			eos?
		</p>
		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia ratione
			fugit eaque commodi? Nemo vero earum totam saepe qui magni ea deleniti
			laborum molestiae maxime, consequatur tenetur reprehenderit cupiditate
			eos?
		</p>
		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia ratione
			fugit eaque commodi? Nemo vero earum totam saepe qui magni ea deleniti
			laborum molestiae maxime, consequatur tenetur reprehenderit cupiditate
			eos?
		</p>
		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia ratione
			fugit eaque commodi? Nemo vero earum totam saepe qui magni ea deleniti
			laborum molestiae maxime, consequatur tenetur reprehenderit cupiditate
			eos?
		</p>
		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia ratione
			fugit eaque commodi? Nemo vero earum totam saepe qui magni ea deleniti
			laborum molestiae maxime, consequatur tenetur reprehenderit cupiditate
			eos?
		</p>
		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia ratione
			fugit eaque commodi? Nemo vero earum totam saepe qui magni ea deleniti
			laborum molestiae maxime, consequatur tenetur reprehenderit cupiditate
			eos?
		</p>
		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia ratione
			fugit eaque commodi? Nemo vero earum totam saepe qui magni ea deleniti
			laborum molestiae maxime, consequatur tenetur reprehenderit cupiditate
			eos?
		</p>

		<p id="special">
			Special Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia
			ratione fugit eaque commodi? Nemo vero earum totam saepe qui magni ea
			deleniti laborum molestiae maxime, consequatur tenetur reprehenderit
			cupiditate eos?
		</p>
		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia ratione
			fugit eaque commodi? Nemo vero earum totam saepe qui magni ea deleniti
			laborum molestiae maxime, consequatur tenetur reprehenderit cupiditate
			eos?
		</p>
		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia ratione
			fugit eaque commodi? Nemo vero earum totam saepe qui magni ea deleniti
			laborum molestiae maxime, consequatur tenetur reprehenderit cupiditate
			eos?
		</p>
		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia ratione
			fugit eaque commodi? Nemo vero earum totam saepe qui magni ea deleniti
			laborum molestiae maxime, consequatur tenetur reprehenderit cupiditate
			eos?
		</p>
		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia ratione
			fugit eaque commodi? Nemo vero earum totam saepe qui magni ea deleniti
			laborum molestiae maxime, consequatur tenetur reprehenderit cupiditate
			eos?
		</p>
		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia ratione
			fugit eaque commodi? Nemo vero earum totam saepe qui magni ea deleniti
			laborum molestiae maxime, consequatur tenetur reprehenderit cupiditate
			eos?
		</p>
		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia ratione
			fugit eaque commodi? Nemo vero earum totam saepe qui magni ea deleniti
			laborum molestiae maxime, consequatur tenetur reprehenderit cupiditate
			eos?
		</p>
		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia ratione
			fugit eaque commodi? Nemo vero earum totam saepe qui magni ea deleniti
			laborum molestiae maxime, consequatur tenetur reprehenderit cupiditate
			eos?
		</p>
		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia ratione
			fugit eaque commodi? Nemo vero earum totam saepe qui magni ea deleniti
			laborum molestiae maxime, consequatur tenetur reprehenderit cupiditate
			eos?
		</p>
		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia ratione
			fugit eaque commodi? Nemo vero earum totam saepe qui magni ea deleniti
			laborum molestiae maxime, consequatur tenetur reprehenderit cupiditate
			eos?
		</p>
		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia ratione
			fugit eaque commodi? Nemo vero earum totam saepe qui magni ea deleniti
			laborum molestiae maxime, consequatur tenetur reprehenderit cupiditate
			eos?
		</p>
		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia ratione
			fugit eaque commodi? Nemo vero earum totam saepe qui magni ea deleniti
			laborum molestiae maxime, consequatur tenetur reprehenderit cupiditate
			eos?
		</p>
	</body>
</html>

```

## 13- Image and Deal With Paths

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8" />
		<title>Book Store</title>
		<meta name="description" content="This is our book store!" />
	</head>
	<body>
		<h1>Book Store</h1>
		<p>This is my <b>Book Store</b>. Welocme!</p>
		<img
			src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTz0nTZuuMTh6O4Fm2dQiqYiNQsO1DABrX0xw&s"
			alt="Cat image"
		/>
		<img src="images/10.jpg" alt="Sky image" width="200px" />
	</body>
</html>

```

## 14- Lists UL - OL  - DL

- ul ⇒ Unordered List.
- li ⇒ list item.
- ol ⇒ ordered list.
    - Attributes:
        - reversed.
        - start.
        - type.
- dl ⇒ description list.
    - dt ⇒ term.
    - dd ⇒ description term.

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8" />
		<title>Book Store</title>
		<meta name="description" content="This is our book store!" />
	</head>
	<body>
		<h1>Book Store</h1>
		<p>This is my <b>Book Store</b>. Welocme!</p>
		<ul>
			<li>HTML</li>
			<li>CSS</li>
			<li>
				JS
				<ul>
					<li>React</li>
					<li>Vue</li>
					<li>Angular</li>
				</ul>
			</li>
		</ul>

		<ol>
			<li>Name</li>
			<li>ID</li>
			<li>Address</li>
		</ol>

		<dl>
			<dt>HTML</dt>
			<dd>The hypertext markup language.</dd>
			<dt>CSS</dt>
			<dd>The cascading style sheets.</dd>
		</dl>
	</body>
</html>

```

# Tasks Week One

## From 1 To 5

1. HTML ⇒ HyperText Markup Language.
2. Task 2
    
    ```html
    <!DOCTYPE html>
    <html>
    	<head>
    		<meta charset="UTF-8" />
    		<title>My First Page</title>
    		<meta
    			name="description"
    			content="This is a description for my first page"
    		/>
    		<style></style>
    		<script></script>
    		<link rel="stylesheet" href="" />
    	</head>
    	<body>
    		<p>This is my first page</p>
    	</body>
    </html>
    ```
    
3. Task 3
    1. هل ما يتم كتابته داخل ال Head يظهر داخل الصفحة أم لا؟ ⇒ **No.**
    2. هل عنصر Title له قفلة أم لا ؟ ⇒ **Yes.**
    3. هل عنصر Meta له قفلة أم لا ؟ ⇒ **No.**
    4. هل ما يتم وضعه داخل ال Description في عنصر ال Meta يظهر في الصفحة أم لا ؟ ⇒ **No.**
4. Task 4
    
    ```html
    <meta charset="UTF-8">
    <meta name="description" content="Free Web tutorials">
    <meta name="keywords" content="HTML, CSS, JavaScript">
    <meta name="author" content="John Doe">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    ```
    

## From 6 To 10

1. Task 1
    
    ```html
    <!-- Type Question 1 Answer Below -->
    <!DOCTYPE html>
    
    <!-- Type Question 2 Answer Below -->
    Quirks Mode
    
    <!-- Type Question 3 Answer Below -->
    No
    
    <!-- Type Question 4 Answer Below -->
    No
    
    <!-- Type Question 5 Answer Below -->
    Heading
    ```
    
2. No.
3. Yes.
4. Yes.
5. Task 5
    
    ```
    title => No
    href => No
    src => No
    hidden => Yes
    charset => No
    class => Yes
    id => Yes
    type => No
    ```
    
6. Task 6
    
    ```html
    <!DOCTYPE html>
    <html>
    	<head>
    		<meta charset="UTF-8" />
    		<title>E-Commerce</title>
    		<meta name="description" content="This is our e-commerce" />
    	</head>
    	<body>
    		<h1>E-Commerce</h1>
    		<p>
    			Lorem ipsum dolor sit amet, consectetur adipisicing elit. Libero delectus
    			officia, quibusdam fugiat aut laboriosam ullam. Animi magni cum quos
    			quidem accusamus ad iusto ipsum nisi, aspernatur dolore, vel quo!
    		</p>
    		<h2>Women's Clothes</h2>
    		<h3>Dress</h3>
    		<p>
    			Lorem ipsum, dolor sit amet consectetur adipisicing elit. Culpa
    			exercitationem accusantium ad provident. Esse ratione nobis praesentium
    			eius odio earum cum fuga error tempora! Natus neque non aut expedita fuga?
    		</p>
    		<hr />
    		<h3>Dress</h3>
    		<p>
    			Lorem ipsum, dolor sit amet consectetur adipisicing elit. Culpa
    			exercitationem accusantium ad provident. Esse ratione nobis praesentium
    			eius odio earum cum fuga error tempora! Natus neque non aut expedita fuga?
    		</p>
    		<hr />
    		<h3>Dress</h3>
    		<p>
    			Lorem ipsum, dolor sit amet consectetur adipisicing elit. Culpa
    			exercitationem accusantium ad provident. Esse ratione nobis praesentium
    			eius odio earum cum fuga error tempora! Natus neque non aut expedita fuga?
    		</p>
    		<hr />
    		<h2>Men's Clothes</h2>
    		<h3>T-Shirt</h3>
    		<p>
    			Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequuntur,
    			placeat sunt necessitatibus ea culpa eum, a quis totam vero cumque
    			dignissimos tempore enim molestiae amet eaque dolore temporibus? Saepe,
    			sit.
    		</p>
    		<hr />
    		<h3>T-Shirt</h3>
    		<p>
    			Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequuntur,
    			placeat sunt necessitatibus ea culpa eum, a quis totam vero cumque
    			dignissimos tempore enim molestiae amet eaque dolore temporibus? Saepe,
    			sit.
    		</p>
    		<hr />
    		<h3>T-Shirt</h3>
    		<p>
    			Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequuntur,
    			placeat sunt necessitatibus ea culpa eum, a quis totam vero cumque
    			dignissimos tempore enim molestiae amet eaque dolore temporibus? Saepe,
    			sit.
    		</p>
    	</body>
    </html>
    ```
    
7. Task 7
    
    ```html
    <!DOCTYPE html>
    <html>
    	<head>
    		<meta charset="UTF-8" />
    		<title>Page</title>
    	</head>
    	<body>
    		<h1>My Page</h1>
    		<p>This Is My Page</p>
    		<p>This Is My First Work</p>
    
    		<h2>Section One</h2>
    		<p>This Is Section One</p>
    	</body>
    </html>
    ```
    

## From 11 To 14

1. Task 1
    
    ```html
    <!DOCTYPE html>
    <html>
    	<head>
    		<meta charset="UTF-8" />
    		<title>My Info</title>
    	</head>
    	<body>
    		<h1>My Info</h1>
    		<p>My name is: <b>Osama Elzero</b></p>
    		<p>I am <strong>available</strong> for hire</p>
    		<p>
    			My hour old price is <del>$10</del> and the new price is <mark>$30</mark>
    		</p>
    		<p>
    			Visit my website from this link
    			<a href="https://elzero.org/" title="elzero website">Elzero Academy</a>
    		</p>
    		<hr />
    		<h1>Here is some of my clients</h1>
    		<img
    			decoding="async"
    			src="https://via.placeholder.com/50x50/F00/FFF?text=50x50"
    			alt="img"
    		/>
    		<img
    			decoding="async"
    			src="https://via.placeholder.com/50x50/0F0/FFF?text=50x50"
    			alt="img"
    		/>
    		<img
    			decoding="async"
    			src="https://via.placeholder.com/50x50/00F/FFF?text=50x50"
    			alt="img"
    		/>
    		<hr />
    		<h1>My Skills</h1>
    		<ul>
    			<li>HTML</li>
    			<li>CSS</li>
    			<li>
    				JavaScript
    				<ul>
    					<li>Vuejs</li>
    					<li>Reactjs</li>
    					<li>
    						Angular
    						<ol start="4">
    							<li>v4.0</li>
    							<li>v5.0</li>
    							<li>v6.0</li>
    							<li>v7.0</li>
    							<li>v8.0</li>
    						</ol>
    					</li>
    				</ul>
    			</li>
    			<li>Python</li>
    		</ul>
    	</body>
    </html>
    
    ```
    
2. Task 2
    
    ```html
    <!DOCTYPE html>
    <html>
    	<head>
    		<meta charset="UTF-8" />
    		<title>My Info</title>
    	</head>
    	<body>
    		<ul>
    			<li>
    				One
    				<ol type="A" start="3">
    					<li>C</li>
    					<li>D</li>
    					<li>E</li>
    				</ol>
    			</li>
    			<li>
    				Two
    				<ol type="I" start="3">
    					<li>3</li>
    					<li>4</li>
    					<li>5</li>
    				</ol>
    			</li>
    			<li>
    				Three
    				<ol type="a" start=4 reversed>
    					<li>d</li>
    					<li>c</li>
    					<li>b</li>
    				</ol>
    			</li>
    		</ul>
    	</body>
    </html>
    
    ```
    
3. Task 3
    
    ```html
    <!-- Go To External Link -->
    <a href="https://google.com">Google</a>
    
    <!-- Use an image as a link -->
    
    <!-- link to an email address -->
    
    <!-- link to a phone number -->
    
    <!-- link to another section on the same page -->
    
    <!-- link to a javascript -->
    ```
    
4. Task 4
    
    ```html
    <!DOCTYPE html>
    <html>
    	<head>
    		<meta charset="UTF-8" />
    		<title>DL</title>
    	</head>
    	<body>
    		<dl>
    			<dt>Learn Programming</dt>
    			<dd>Learn Computer Science</dd>
    			<dd>Learn Database</dd>
    			<dt>Design</dt>
    			<dd>Learn Graphics</dd>
    			<dd>Learn Sketching</dd>
    		</dl>
    	</body>
    </html>
    ```
    

# Week Two

## 15- Table

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8" />
		<title>Book Store</title>
	</head>
	<body>
		<h1>Book Store</h1>
		<p>This is my <b>book store</b>, Welcome!</p>
		<table>
			<thead>
				<tr>
					<td>First</td>
					<td>Last</td>
					<td>Marks</td>
				</tr>
			</thead>
			<tbody>
				<tr>
					<td>Zeina</td>
					<td>Zayed</td>
					<td>98</td>
				</tr>
				<tr>
					<td>Zeina</td>
					<td>Zayed</td>
					<td>98</td>
				</tr>
				<tr>
					<td>Zeina</td>
					<td>Zayed</td>
					<td>98</td>
				</tr>
				<tr>
					<td>Zeina</td>
					<td>Zayed</td>
					<td>98</td>
				</tr>
			</tbody>
			<tfoo>
				<tr>
					<td>One</td>
					<td>Two</td>
					<td>Three</td>
				</tr>
			</tfoo>
		</table>
	</body>
</html>

```

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8" />
		<title>Book Store</title>
	</head>
	<body>
		<h1>Book Store</h1>
		<p>This is my <b>book store</b>, Welcome!</p>
		<table>
			<caption>
				Student Marks
			</caption>
			<tr>
				<th>First</th>
				<th>Last</th>
				<th>Marks</th>
			</tr>
			<tr>
				<td>Zeina</td>
				<td>Zayed</td>
				<td>98</td>
			</tr>
			<tr>
				<td>Zeina</td>
				<td>Zayed</td>
				<td>98</td>
			</tr>
			<tr>
				<td>Zeina</td>
				<td>Zayed</td>
				<td>98</td>
			</tr>
			<tr>
				<td>Zeina</td>
				<td>Zayed</td>
				<td>98</td>
			</tr>
			<tr>
				<td colspan="3">392</td>
			</tr>
		</table>
	</body>
</html>
```

## 16- Span, Break and Horizontal Rule

- span ⇒ inline element.
- hr ⇒ block element.

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8" />
		<title>Book Store</title>
	</head>
	<body>
		<h1>Book Store</h1>
		<p>This is <span>my</span> <b>book store</b>, Welcome!</p>
		<p>This is second paragraph, <br />test</p>
		<hr />
		<p>Third paragraph</p>
	</body>
</html>
```

## 17- Div and How to Use

- Div is a container.

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8" />
		<title>Book Store</title>
	</head>
	<i>
		<div>
			<h1>Book Store</h1>
			<p>This is my <b>book store</b>, Welcome!</p>
		</div>

		<div class="romantic">
			<div class="book">
				<h3>Book Title</h3>
				<p>Book description</p>
				<span>$100</span>
			</div>
			<div class="book">
				<h3>Book Title</h3>
				<p>Book description</p>
				<span>$100</span>
			</div>
			<div class="book">
				<h3>Book Title</h3>
				<p>Book description</p>
				<span>$100</span>
			</div>
		</div>
		<hr />
		<div class="police">
			<div class="book">
				<h3>Book Title</h3>
				<p>Book description</p>
				<span>$100</span>
			</div>
			<div class="book">
				<h3>Book Title</h3>
				<p>Book description</p>
				<span>$100</span>
			</div>
			<div class="book">
				<h3>Book Title</h3>
				<p>Book description</p>
				<span>$100</span>
			</div>
		</div>
		<hr />
		<div class="fantasy">
			<div class="book">
				<h3>Book Title</h3>
				<p>Book description</p>
				<span>$100</span>
			</div>
			<div class="book">
				<h3>Book Title</h3>
				<p>Book description</p>
				<span>$100</span>
			</div>
			<div class="book">
				<h3>Book Title</h3>
				<p>Book description</p>
				<span>$100</span>
			</div>
		</div>
	</body>
</html>

```

## 18- HTML Entities

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8" />
		<title>Book Store</title>
	</head>
	<body>
		<h1>Book Store</h1>
		<p>This is my <b>book store</b>, Welcome!</p>
		<div>This is my &lt;p&gt; div</div>
		<p>&copy;Zeina Zayed</p>
	</body>
</html>
```

## 19- Semantic Elements

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8" />
		<title>Book Store</title>
	</head>
	<body>
		<header>Head of website</header>
		<nav>
			<li>Link</li>
			<li>Link</li>
			<li>Link</li>
			<li>Link</li>
		</nav>
		<section>
			<section></section>
			<aside></aside>
		</section>
		<footer>Footer</footer>
	</body>
</html>
```

## 20- Layout With Div and Classes

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8" />
		<title>Book Store</title>
		<meta name="description" content="This is our book store" />
	</head>
	<body>
		<div class="header">
			<h2>Logo</h2>
			<ul>
				<li>Home</li>
				<li>About</li>
				<li>Services</li>
				<li>Contact Us</li>
			</ul>
		</div>
		<hr />
		<div class="nav">
			<ul>
				<li>Link</li>
				<li>Link</li>
				<li>Link</li>
				<li>Link</li>
			</ul>
		</div>
		<hr />
		<div class="content">Content</div>
		<div class="sidebar">Sidebar</div>
		<hr />
		<div class="footer">Footer</div>
	</body>
</html>

```

## 21- Layout With Semantic Elements

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8" />
		<title>Book Store</title>
		<meta name="description" content="This is our book store" />
	</head>
	<body>
		<header>
			<h2>Logo</h2>
			<ul>
				<li>Home</li>
				<li>About</li>
				<li>Services</li>
				<li>Contact Us</li>
			</ul>
		</header>
		<hr />
		<nav>
			<ul>
				<li>Link</li>
				<li>Link</li>
				<li>Link</li>
				<li>Link</li>
			</ul>
		</nav>
		<hr />
		<section>
			<figure>
				<img src="images/10.jpg" alt="" />
				<figcaption>Moon and Flowers</figcaption>
			</figure>
		</section>
		<article>Article</article>
		<aside>Sidebar</aside>
		<hr />
		<footer>Footer</footer>
	</body>
</html>

```

## 22- Audio

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8" />
		<title>Book Store</title>
		<meta name="description" content="This is our book store" />
	</head>
	<body>
		<h1>Book Store</h1>
		<p>This is my book store, Welcome!</p>
		<audio controls autoplay loop>
			<source
				src="audio/mixkit-scared-horse-neighing-85.wav"
				type="audio/wav"
			/>
			<source
				src="audio/mixkit-scared-horse-neighing-85.mp3"
				type="audio/mpeg"
			/>
			<source
				src="audio/mixkit-scared-horse-neighing-85.ogg"
				type="audio/ogg"
			/>
			Your browser doesn't support audio tags
		</audio>
	</body>
</html>
```

## 23- Video

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8" />
		<title>Book Store</title>
		<meta name="description" content="This is our book store" />
	</head>
	<body>
		<h1>Book Store</h1>
		<p>This is my book store, Welcome!</p>
		<video
			controls
			width="600"
			height="400"
			autoplay
			muted
			poster="images/10.jpg"
		>
			<source src="video/video.mp4" type="video/mp4" />
			Your borwser doesn't support video tags!
			<track
				src="my_file_en.vtt"
				kind="subtitles"
				srclang="en"
				label="English"
			/>
			<track
				src="my_file_ar.vtt"
				kind="subtitles"
				srclang="ar"
				label="Arabic"
			/>
		</video>
	</body>
</html>
```

## 24- Form Part 1 - Input type and Label

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8" />
		<title>Book Store</title>
		<meta name="description" content="This is our book store" />
	</head>
	<body>
		<div>
			<h1>Book Store</h1>
			<p>This is my book store, Welcome!</p>
		</div>
		<form>
			<div>
				<label>Username: </label>
				<input type="text" />
			</div>
			<br />
			<div>
				<label>Password: </label>
				<input type="password" />
			</div>
			<input type="submit" />
		</form>
	</body>
</html>

```

## 25- Form Part 2 - Required, Placeholder, Value

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8" />
		<title>Book Store</title>
		<meta name="description" content="This is our book store" />
	</head>
	<body>
		<div>
			<h1>Book Store</h1>
			<p>This is my book store, Welcome!</p>
		</div>
		<form>
			<div>
				<label>Username: </label>
				<input type="text" required placeholder="Username" />
			</div>
			<br />
			<div>
				<label>Subject: </label>
				<input type="text" />
			</div>
			<br />
			<div>
				<label>Password: </label>
				<input
					type="password"
					required
					placeholder="Write a complex password"
				/>
			</div>
			<br />
			<div>
				<label>Email: </label>
				<input
					type="email"
					required
					placeholder="Write a valid email"
					value="zeina@test.com"
				/>
			</div>
			<br />
			<input type="submit" value="Save" />
		</form>
	</body>
</html>

```

## 26- Form Part 3 - Action, Name, Method

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8" />
		<title>Book Store</title>
		<meta name="description" content="This is our book store" />
	</head>
	<body>
		<div>
			<h1>Book Store</h1>
			<p>This is my book store, Welcome!</p>
		</div>
		<form action="" method="post" enctype="multipart/form-data">
			<div>
				<label>Username: </label>
				<input type="text" required placeholder="Username" name="username" />
			</div>
			<br />
			<div>
				<label>Subject: </label>
				<input type="text" name="subject" />
			</div>
			<br />
			<div>
				<label>Password: </label>
				<input
					type="password"
					name="password"
					required
					placeholder="Write a complex password"
				/>
			</div>
			<br />
			<div>
				<label>Email: </label>
				<input
					type="email"
					name="email"
					required
					placeholder="Write a valid email"
					value="zeina@test.com"
				/>
			</div>
			<br />
			<input type="submit" value="Save" />
		</form>
	</body>
</html>

```

## 27- Form Part 4 - Hidden, Reset, Color, Range, Num

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8" />
		<title>Book Store</title>
		<meta name="description" content="This is our book store" />
	</head>
	<body>
		<div>
			<h1>Book Store</h1>
			<p>This is my book store, Welcome!</p>
		</div>
		<form action="" method="get" enctype="multipart/form-data">
			<input type="hidden" value="zeina" />
			<div>
				<label>Username: </label>
				<input type="text" required placeholder="Username" name="username" />
			</div>
			<br />
			<div>
				<label>Subject: </label>
				<input type="text" name="subject" />
			</div>
			<br />
			<div>
				<label>Password: </label>
				<input
					type="password"
					name="password"
					required
					placeholder="Write a complex password"
				/>
			</div>
			<br />
			<div>
				<label>Email: </label>
				<input
					type="email"
					name="email"
					required
					placeholder="Write a valid email"
					value="zeina@test.com"
				/>
			</div>
			<br />
			<div>
				<label>Color: </label>
				<input type="color" name="color" />
			</div>
			<br />
			<div>
				<label>Range: </label>
				<input
					type="range"
					name="range"
					min="0"
					max="100"
					step="20"
					value="0"
				/>
			</div>
			<br />
			<div>
				<label>Number: </label>
				<input type="number" name="number" min="10" max="100" step="10" />
			</div>
			<br />
			<input type="reset" value="Reset" />
			<input type="submit" value="Save" />
		</form>
	</body>
</html>

```

# Tasks Week Two

## From 15 To 18

- 1
    
    ```html
    <!DOCTYPE html>
    <html lang="en">
    	<head>
    		<meta charset="UTF-8" />
    		<title>Book Store</title>
    		<meta name="description" content="This is our book store" />
    	</head>
    	<body>
    		<table width="100%" border="1">
    			<caption>
    				Members Data
    			</caption>
    			<thead>
    				<tr>
    					<td>Group</td>
    					<td>Avatar</td>
    					<td>Name</td>
    					<td>Email</td>
    					<td>Character</td>
    					<td>Profile</td>
    				</tr>
    			</thead>
    			<tbody>
    				<tr>
    					<td rowspan="2">Ninja</td>
    					<td>
    						<img
    							decoding="async"
    							src="https://via.placeholder.com/40x40/F00/FFF?text=40x40"
    							alt=""
    						/>
    					</td>
    					<td>
    						Osama <br />
    						Mohamed
    					</td>
    					<td>
    						o1@nn.sa
    						<hr />
    						o2@nn.sa
    					</td>
    					<td>&copy;</td>
    					<td><a href="https://google.com" target="_blank">Profile</a></td>
    				</tr>
    				<tr>
    					<td>
    						<img
    							decoding="async"
    							src="https://via.placeholder.com/40x40/00F/FFF?text=40x40"
    							alt=""
    						/>
    					</td>
    					<td>
    						Shady <br />
    						Nabil
    					</td>
    					<td>s@nn.sa</td>
    					<td>&trade;</td>
    					<td><a href="https://google.com" target="_blank">Profile</a></td>
    				</tr>
    				<tr>
    					<td>Monsters</td>
    					<td>
    						<img
    							decoding="async"
    							src="https://via.placeholder.com/40x40/000/FFF?text=40x40"
    							alt=""
    						/>
    					</td>
    					<td>
    						Mohamed <br />
    						Ibrahim
    					</td>
    					<td>m@nn.sa</td>
    					<td>&reg;</td>
    					<td><a href="https://google.com" target="_blank">Profile</a></td>
    				</tr>
    				<tr>
    					<td colspan="5">Total Members</td>
    					<td>3</td>
    				</tr>
    			</tbody>
    		</table>
    	</body>
    </html>
    
    ```
    
- 2
    
    ```html
    <!DOCTYPE html>
    <html lang="en">
    	<head>
    		<meta charset="UTF-8" />
    		<title>Book Store</title>
    		<meta name="description" content="This is our book store" />
    	</head>
    	<body>
    		<table border="1" cellpadding="12px" cellspacing="0.5px">
    			<caption>
    				Members Data
    			</caption>
    			<thead>
    				<tr>
    					<td>Date</td>
    					<td>Name</td>
    					<td>Points</td>
    				</tr>
    			</thead>
    			<tbody>
    				<tr>
    					<td rowspan="4">Month</td>
    					<td>Osama Mohamed</td>
    					<td>100</td>
    				</tr>
    				<tr>
    					<td>Sayed Mohamed</td>
    					<td>100</td>
    				</tr>
    				<tr>
    					<td>Ahmed Mohamed</td>
    					<td>100</td>
    				</tr>
    				<tr>
    					<td>Eman Mohamed</td>
    					<td>100</td>
    				</tr>
    			</tbody>
    		</table>
    	</body>
    </html>
    
    ```
    
- 3
    
    ```html
    <!DOCTYPE html>
    <html lang="en">
    	<head>
    		<meta charset="UTF-8" />
    		<title>Book Store</title>
    		<meta name="description" content="This is our book store" />
    	</head>
    	<body>
    		<table border="1">
    			<caption>
    				Complex Table
    			</caption>
    			<thead>
    				<tr>
    					<td>Year</td>
    					<td>Group</td>
    					<td>Language</td>
    					<td>Done</td>
    					<td>Passed</td>
    				</tr>
    			</thead>
    			<tbody>
    				<tr>
    					<td rowspan="5">2022</td>
    					<td rowspan="2">Elzero</td>
    					<td>HTML</td>
    					<td colspan="2">Yes</td>
    				</tr>
    				<tr>
    					<td>CSS</td>
    					<td colspan="2">Yes</td>
    				</tr>
    				<tr>
    					<td rowspan="3">Heroes</td>
    					<td>JS</td>
    					<td>Yes</td>
    					<td>No</td>
    				</tr>
    				<tr>
    					<td>PHP</td>
    					<td colspan="2">Yes</td>
    				</tr>
    				<tr>
    					<td>Python</td>
    					<td>No</td>
    					<td>No</td>
    				</tr>
    			</tbody>
    		</table>
    	</body>
    </html>
    
    ```
    

## From 19 To 23

- 1
    
    ```
    Header ==> Yes
    Nav ==> Yes
    Main ==> Yes
    Aside ==> Yes
    Picture ==> Yes
    Figure ==> Yes
    Footer ==> Yes
    FigCaption ==> Yes
    Section ==> Yes
    Command ==> No
    Ruby ==> Yes
    Data ==> Yes
    Article ==> Yes
    Install ==> No
    Text ==> No
    ```
    
- 2
    
    ```html
    <!DOCTYPE html>
    <html>
    	<head>
    		<title>Page</title>
    		<meta charset="UTF-8" />
    		<meta name="description" content="My Info" />
    	</head>
    	<body>
    		<header>
    			<h2>Page Name</h2>
    			<li><a href="https://Google.com">Home</a></li>
    			<li><a href="https://Google.com">Services</a></li>
    			<li><a href="https://Google.com">About</a></li>
    			<li><a href="https://Google.com">Profile</a></li>
    			<li><a href="https://Google.com">Contact</a></li>
    		</header>
    		<hr />
    		<nav>
    			<li>HTML</li>
    			<li>CSS</li>
    			<li>Tailwind</li>
    			<li>Bootstrap</li>
    			<li>JavaScript</li>
    			<li>React</li>
    		</nav>
    		<hr />
    		<section>
    			<article>
    				<h2>Article One</h2>
    				<p>
    					Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis
    					facere similique vitae, cum error, facilis esse ipsam dolores et eum
    					velit magnam in asperiores dicta quam. Nobis repudiandae odit quos?
    				</p>
    				<img src="images/10.jpg" width="600" height="400" />
    				<br />
    				<a href="">Read more</a>
    			</article>
    			<hr />
    			<article>
    				<h2>Article Two</h2>
    				<p>
    					Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis
    					facere similique vitae, cum error, facilis esse ipsam dolores et eum
    					velit magnam in asperiores dicta quam. Nobis repudiandae odit quos?
    				</p>
    				<img src="images/10.jpg" width="600" height="400" />
    				<br />
    				<a href="">Read more</a>
    			</article>
    			<hr />
    			<article>
    				<h2>Article Three</h2>
    				<p>
    					Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis
    					facere similique vitae, cum error, facilis esse ipsam dolores et eum
    					velit magnam in asperiores dicta quam. Nobis repudiandae odit quos?
    				</p>
    				<img src="images/10.jpg" width="600" height="400" />
    				<br />
    				<a href="">Read more</a>
    			</article>
    		</section>
    		<aside>
    			<h2>Categories</h2>
    			<ul>
    				<li>HTML</li>
    				<li>CSS</li>
    				<li>Tailwind</li>
    				<li>JavaScript</li>
    				<li>React</li>
    			</ul>
    		</aside>
    		<hr />
    		<footer>&copy; Copyright 2025</footer>
    	</body>
    </html>
    ```
    
- 3
    
    ```html
    <!DOCTYPE html>
    <html>
    	<head>
    		<title>Page</title>
    		<meta charset="UTF-8" />
    		<meta name="description" content="My Info" />
    	</head>
    	<body>
    		<audio controls autoplay loop>
    			<source
    				src="audio/mixkit-scared-horse-neighing-85.wav"
    				type="audio/wav"
    			/>
    			<source
    				src="audio/mixkit-scared-horse-neighing-85.mp3"
    				type="audio/mpeg"
    			/>
    			<source
    				src="audio/mixkit-scared-horse-neighing-85.weba"
    				type="audio/webm"
    			/>
    			Your browser does not support this audio type!
    		</audio>
    	</body>
    </html>
    
    ```
    
- 4
    
    ```html
    <!DOCTYPE html>
    <html>
    	<head>
    		<title>Page</title>
    		<meta charset="UTF-8" />
    		<meta name="description" content="My Info" />
    	</head>
    	<body>
    		<video controls autoplay loop muted poster="images/10.jpg">
    			<source src="video/video.mp4" type="video/mp4" />
    			<source src="video/video.mpeg" type="video/mpeg" />
    			<source src="video/video.webm" type="video/webm" />
    			Your browser does not support this video type!
    			<track src="L1_S1-en.vtt" kind="captions" lang="en" label="English" />
    			<track src="L1_S1-it.vtt" kind="captions" lang="it" label="Itally" />
    		</video>
    	</body>
    </html>
    
    ```
    

## From 24 To 27

- 1
    
    ```html
    <!DOCTYPE html>
    <html>
    	<head>
    		<title>Page</title>
    		<meta charset="UTF-8" />
    		<meta name="description" content="My Info" />
    	</head>
    	<body>
    		<form action="test.py" method="POST">
    			<input type="hidden" value="4" />
    			<div>
    				<label>Username</label>
    				<br />
    				<input type="text" required placeholder="Username" name="user" />
    			</div>
    			<hr />
    			<div>
    				<label>Password</label>
    				<br />
    				<input
    					type="password"
    					placeholder="Enter a complex password"
    					name="pass"
    				/>
    			</div>
    			<hr />
    			<div>
    				<label>Mobile</label>
    				<br />
    				<input type="text" placeholder="+20100 (234) 123" name="number" />
    			</div>
    			<hr />
    			<div>
    				<label>Email</label>
    				<br />
    				<input
    					type="email"
    					required
    					placeholder="Enter an email"
    					name="email"
    				/>
    			</div>
    			<hr />
    			<div>
    				<label>Subject</label>
    				<br />
    				<input type="text" placeholder="Any subject you want" name="sub" />
    			</div>
    			<br />
    			<input type="reset" value="Empty Form" />
    			<br />
    			<br />
    			<input type="submit" value="Send Data" />
    		</form>
    	</body>
    </html>
    
    ```
    
- 2
    
    ```html
    <!DOCTYPE html>
    <html>
    	<head>
    		<title>Page</title>
    		<meta charset="UTF-8" />
    		<meta name="description" content="My Info" />
    	</head>
    	<body>
    		<form>
    			<input type="range" min="100" max="500" step="50" value="400" />
    		</form>
    	</body>
    </html>
    
    ```
    

# Week Three

## 28- Form Part 5 - Readonly, Disabled, Autofocus

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8" />
		<title>Book Store</title>
		<meta name="description" content="This is our book store" />
	</head>
	<body>
		<div>
			<h1>Book Store</h1>
			<p>This is my book store, Welcome!</p>
		</div>
		<form action="" method="get" enctype="multipart/form-data">
			<input type="hidden" value="zeina" />
			<div>
				<label>Username: </label>
				<input
					type="text"
					required
					placeholder="Username"
					name="username"
					value="Zeina"
					readonly
				/>
			</div>
			<br />
			<div>
				<label>Subject: </label>
				<input type="text" name="subject" autofocus />
			</div>
			<br />
			<div>
				<label>Password: </label>
				<input
					type="password"
					name="password"
					required
					placeholder="Write a complex password"
					minlength="6"
					maxlength="20"
				/>
			</div>
			<br />
			<div>
				<label>Email: </label>
				<input
					type="email"
					name="email"
					required
					placeholder="Write a valid email"
					value="zeina@test.com"
					disabled
				/>
			</div>
			<br />
			<div>
				<label>Color: </label>
				<input type="color" name="color" />
			</div>
			<br />
			<div>
				<label>Range: </label>
				<input
					type="range"
					name="range"
					min="0"
					max="100"
					step="20"
					value="0"
				/>
			</div>
			<br />
			<div>
				<label>Number: </label>
				<input type="number" name="number" min="10" max="100" step="10" />
			</div>
			<br />
			<input type="reset" value="Reset" />
			<input type="submit" value="Save" />
		</form>
	</body>
</html>

```

## 29- Form Part 6 - Radio and Checkbox

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8" />
		<title>Book Store</title>
		<meta name="description" content="This is our book store" />
	</head>
	<body>
		<div>
			<h1>Book Store</h1>
			<p>This is my book store, Welcome!</p>
		</div>
		<form action="" method="get" enctype="multipart/form-data">
			<hr />
			<div>
				<input type="radio" name="OS" id="Windows" value="Windows" checked />
				<label for="Windows">Windows</label>
			</div>
			<div>
				<input type="radio" name="OS" id="Linux" value="Linux" />
				<label for="Linux">Linux</label>
			</div>
			<div>
				<input type="radio" name="OS" id="Mac" value="Mac" />
				<label for="Mac">Mac</label>
			</div>
			<hr />
			<div>
				<input
					type="checkbox"
					name="OS"
					id="Windows-one"
					value="Windows"
					checked
				/>
				<label for="Windows-one">Windows</label>
			</div>
			<div>
				<input type="checkbox" name="OS" id="Linux-one" value="Linux" />
				<label for="Linux-one">Linux</label>
			</div>
			<div>
				<input type="checkbox" name="OS" id="Mac-one" value="Mac" />
				<label for="Mac-one">Mac</label>
			</div>
			<br />
			<input type="reset" value="Reset" />
			<input type="submit" value="Save" />
		</form>
	</body>
</html>

```

## 30- Form Part 7 - Select and Textarea

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8" />
		<title>Book Store</title>
		<meta name="description" content="This is our book store" />
	</head>
	<body>
		<div>
			<h1>Book Store</h1>
			<p>This is my book store, Welcome!</p>
		</div>
		<form action="" method="get" enctype="multipart/form-data">
			<label for="book">Choose Book: </label>
			<select name="book" id="book" multiple>
				<optgroup label="Magic Books">
					<option value="1">Book 1</option>
					<option value="2" selected>Book 2</option>
					<option value="3">Book 3</option>
				</optgroup>
				<optgroup label="Fantasy Books">
					<option value="4">Book 4</option>
					<option value="5">Book 5</option>
					<option value="6">Book 6</option>
				</optgroup>
			</select>
			<hr />
			<label for="subject">Subject: </label>
			<textarea
				name="subject"
				id="subject"
				rows="10"
				cols="30"
				placeholder="Write your subject!"
			></textarea>
			<hr />
			<input type="reset" value="Reset" />
			<input type="submit" value="Save" />
		</form>
	</body>
</html>

```

## 31- Form Part 8 - File, Search, URL, Time

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8" />
		<title>Book Store</title>
		<meta name="description" content="This is our book store" />
	</head>
	<body>
		<div>
			<h1>Book Store</h1>
			<p>This is my book store, Welcome!</p>
			<hr />
		</div>
		<form action="" method="get" enctype="multipart/form-data">
			<div>
				<label for="cv">Your CV: </label>
				<input type="file" name="cv" id="cv" />
			</div>
			<hr />
			<div>
				<label for="search">Search: </label>
				<input type="search" name="search" id="search" />
			</div>
			<hr />
			<div>
				<label for="url">URL: </label>
				<input type="url" name="url" id="url" />
			</div>
			<hr />
			<div>
				<label for="date">Date: </label>
				<input type="date" name="date" id="date" />
			</div>
			<hr />
			<div>
				<label for="month">Month: </label>
				<input type="month" name="month" id="month" />
			</div>
			<hr />
			<div>
				<label for="time">Time: </label>
				<input type="time" name="time" id="time" />
			</div>
			<hr />
			<input type="reset" value="Reset" />
			<input type="submit" value="Save" />
		</form>
	</body>
</html>

```

## 32- Form Part 9 - DataList, NoValidate, Target

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8" />
		<title>Book Store</title>
		<meta name="description" content="This is our book store" />
	</head>
	<body>
		<form>
			<input list="programming" name="programming" />

			<datalist id="programming">
				<option value="PHP"></option>
				<option value="Python"></option>
				<option value="JavaScript"></option>
				<option value="C++"></option>
				<option value="C"></option>
			</datalist>

			<hr />
			<input type="reset" value="Reset" />
			<input type="submit" value="Save" />
		</form>
	</body>
</html>

```

## 33- Q and BlockQuote, Wbr, Button, Bdi

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8" />
		<title>Book Store</title>
		<meta name="description" content="This is our book store" />
	</head>
	<body>
		<q>This is a wise word!</q>
		<blockquote>Another wise word!</blockquote>
		<button>Click</button>
		<div>
			https://www.youtube.com<wbr />/watch?v=NRKGZdJTf48&list<wbr />=PL4cUxeGkcC9h77dJ<wbr />-QJlwGlZlTd4ecZOA&index=11
		</div>
		<p><bdi>السلام</bdi> 2 Welcome!</p>
	</body>
</html>
```

## 34- iFrame, Pre, Code

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8" />
		<title>Book Store</title>
		<meta name="description" content="This is our book store" />
	</head>
	<body>
		<pre>
			<code>
				$x = 4; 
				$y = 8; 
				echo $x + $y; 
			</code>
		</pre>
		<iframe src="https://elzero.org" frameborder="0"></iframe>
	</body>
</html>
```

## 35- Accessibility Intro

```html
<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="UTF-8" />
		<title>Book Store</title>
		<meta name="description" content="This is our book store" />
	</head>
	<body>
		<form>
			<label for="username">Username</label>
			<input type="text" name="username" id="username" />
			<button>Send</button>
			<button>Reset</button>
		</form>
	</body>
</html>
```

## 36- ARIA and Screen Readers

```html
<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="UTF-8" />
		<title>Book Store</title>
		<meta name="description" content="This is our book store" />
	</head>
	<body>
		<h1>Book Title</h1>
		<h2>Chapter One</h2>
		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam tempora
			deleniti a vel harum exercitationem quae! Laudantium reiciendis enim
			dolorem nemo illo, veniam perferendis laboriosam inventore quo? Earum,
			atque dolorem!
		</p>
		<div>
			Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nesciunt facere
			commodi cumque iure porro asperiores ducimus repellat rerum optio, eius
			aspernatur incidunt eaque dolorem. Illo necessitatibus veniam ipsa nihil
			laudantium.
		</div>
		<h3>Inside Chapter One</h3>
		<form action="">
			<label for="skill1">Skill One</label>
			<input type="checkbox" id="skill1" checked />
			<label for="skill2">Skill Two</label>
			<input type="checkbox" id="skill2" />
		</form>
		<hr />
		<div
			role="checkbox"
			aria-checked="true"
			tabindex="0"
			aria-labelledby="plan1"
		>
			Paln One
		</div>
		<label for="plan1">Plan One Label</label>
		<div tabindex="0">Paln Two</div>
		<div tabindex="0">Paln Three</div>
	</body>
</html>
```

## 37- The End and What To Do

# Tasks Week Three

## From 28 To 30

```html
<!DOCTYPE html>
<html>
	<head>
		<title>Page</title>
		<meta charset="UTF-8" />
		<meta name="description" content="My Info" />
	</head>
	<body>
		<form>
			<label for="user">Username</label>
			<input
				id="user"
				type="text"
				name="username"
				autofocus
				minlength="5"
				maxlength="20"
				required
			/>
			<br />
			<br />
			<label for="email">Email</label>
			<input id="email" type="email" name="email" readonly value="o@o.com" />
			<br />
			<br />
			<label for="sub">Token</label>
			<input
				id="sub"
				type="text"
				name="taken"
				hidden
				value="b92f1fc2fce391ad7af633723afd3055"
			/>
			<br />
			<br />
			<div>
				<input
					id="1"
					type="checkbox"
					name="skills"
					value="Problem Solving"
					checked
				/>
				<label for="1">Problem Solving</label>
			</div>
			<div>
				<input id="2" type="checkbox" name="skills" value="Logical Thinking" />
				<label for="2">Logical Thinking</label>
			</div>
			<div>
				<input id="3" type="checkbox" name="skills" value="Advanced Search" />
				<label for="3">Advanced Search</label>
			</div>
			<div>
				<input id="4" type="checkbox" name="skills" value="Analysis" />
				<label for="4">Analysis</label>
			</div>
			<div>
				<input id="5" type="checkbox" name="skills" value="Planning" />
				<label for="5">Planning</label>
			</div>
			<br />
			<hr />
			<br />
			<div>
				<input
					id="a"
					type="radio"
					name="job"
					value="Front-End Developer"
					checked
				/>
				<label for="a">Front-End Developer</label>
			</div>
			<div>
				<input id="b" type="radio" name="job" value=" Back-End Developer" />
				<label for="b"> Back-End Developer</label>
			</div>
			<div>
				<input id="c" type="radio" name="job" value="Business Analyst" />
				<label for="c">Business Analyst</label>
			</div>
			<div>
				<input id="d" type="radio" name="job" value="Project Manager" />
				<label for="d">Project Manager</label>
			</div>
			<div>
				<input id="e" type="radio" name="job" value="Scrum Master" />
				<label for="e">Scrum Master</label>
			</div>
			<br />
			<br />
			<input type="reset" value="Empty" />
			<input type="submit" value="Send" />
			<label for="book">Choose Book:</label>
			<select id="book" name="book">
				<optgroup label="PHP">
					<option value="1">V5.0</option>
					<option value="2">V7.0</option>
					<option value="3">V8.0</option>
				</optgroup>
				<optgroup label="Python">
					<option value="4">V2.0</option>
					<option value="5">V3.0</option>
					<option value="6">V3.9</option>
				</optgroup>
			</select>
			<hr />
			<textarea
				name="brief"
				placeholder="Write Here Why You Want To Learn Programming"
				cols="40"
				rows="10"
			></textarea>
		</form>
	</body>
</html>
```

## From 31 To 34

```html
<!DOCTYPE html>
<html>
	<head>
		<title>Page</title>
		<meta charset="UTF-8" />
		<meta name="description" content="My Info" />
	</head>
	<body>
		<form target="_blank" novalidate>
			<label for="search">Search</label>
			<br />
			<br />
			<input
				id="search"
				type="search"
				placeholder="Enter a Search Word"
				autofocus
			/>
			<br />
			<br />

			<label for="upload">Upload</label>
			<br />
			<br />
			<input id="upload" type="file" />
			<br />
			<br />

			<label for="url">Url</label>
			<br />
			<br />
			<input id="url" type="search" required />
			<br />
			<br />

			<label for="d">Date</label>
			<input id="d" type="date" value="1982-10-25" />
			<br /><br />
			<label for="m">Month</label>
			<input id="m" type="month" value="1982-10" />
			<br /><br />
			<input type="reset" value="Empty" />
			<input type="submit" value="Send" />
		</form>

		<pre>
Hello Line One
Hello Line Two
Hello Line Three
	Hello Line Four
</pre
		>

		<iframe src="https://elzero.org" width="100%" height="400px"></iframe>
	</body>
</html>

```

## From 35 To 37

- 1
    
    ```
    
    submit
    <!-- ما هو العنصر المناسب ليكون عنوان للصفحة كاملة؟ -->
    h1
    <!-- ما هو العنصر المناسب ليكون عنوان لقسم داخل الصفحة؟ -->
    h2
    <!-- ما هو العنصر المناسب ليحتوي على فقرة نصية؟ -->
    p
    <!-- كيف تحدد لغة المحتوى الخاص بصفحتك. يمكنك كتابة العنصر الكامل مع ال Attributes الخاصة بتحديد اللغة -->
    <meta charset="UTF-8" />
    <!-- في عالم ال Accessibility هل الأفضل أن أكتب 10 – 20 أم 10 To 20 -->
    10 To 20
    <!-- إذا كان لديك عنصر Div وتريد الوصول إليه عن الطريق الضغط على ال Tab Button ماذا سوف تفعل في العنصر ؟ -->
    tabindex="0"
    <!--(ممكن رقم غير ال0) -->
    (ARIA) is short for Accessible Rich Internet Applications
    ```
    
- 2
    
    ```html
    <!DOCTYPE html>
    <html lang="en">
    	<head>
    		<meta charset="UTF-8" />
    		<title>Page</title>
    		<meta name="description" content="My Info" />
    	</head>
    	<body>
    		<div class="choose-skill">
    			<div
    				class="skill"
    				aria-labelledby="python"
    				tabindex="0"
    				role="checkbox"
    				aria-checked="true"
    			>
    				Python
    			</div>
    			<label id="python">Skill One</label>
    			<div class="skill" aria-labelledby="php" tabindex="1" role="checkbox">
    				PHP
    			</div>
    			<label id="php">Skill Two</label>
    			<div
    				class="skill"
    				aria-labelledby="javascript"
    				tabindex="2"
    				role="checkbox"
    			>
    				JavaScript
    			</div>
    			<label id="javascript">Skill Three</label>
    		</div>
    	</body>
    </html>
    
    ```