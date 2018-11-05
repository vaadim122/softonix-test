<h1>Softonix_FE_test_task</h1>

<p>Author: <a href="https://vaadim122.github.io/vad-code/" target="_blank">Pecheniuk Vadim</a></p>

<p>OptimizedHTML is all-inclusive, optimized for Google PageSpeed start HTML5 template with Bootstrap , Gulp, Sass, Browsersync, Autoprefixer, Clean-CSS. The template contains a <strong>.htaccess</strong> file with caching rules for web server.</p>

<p>OptimizedHTML Start Template uses the best practices of web development and optimized for Google PageSpeed.</p>

<p>Cross-browser compatibility.</p>

<p>The template uses a Scss with <strong>Scss</strong> syntax and project structure with source code in the directory <strong>src/</strong> and production folder <strong>dist/</strong>, that contains ready project with optimized HTML, CSS, JS and images.</p>

<h2>How to use OptimizedHTML</h2>

<ol>
	<li>Clone repository in to project folder: git clone [repository-url].</li>
	<li>Install Node Modules: <strong>npm i</strong>;</li>
	<li>Run the template: <strong>gulp</strong>.</li>
</ol>

<h2>Gulp tasks:</h2>

<ul>
	<li><strong>gulp</strong>: run default gulp task (sass, js, watch, browserSync) for web development;</li>
	<li><strong>build</strong>: build project to <strong>dist</strong> folder (cleanup, image optimize, removing unnecessary files);</li>
	<li><strong>deploy</strong>: project deployment on the server from <strong>dist</strong> folder via <strong>FTP</strong>;</li>
	<li><strong>rsync</strong>: project deployment on the server from <strong>dist</strong> folder via <strong>RSYNC</strong>;</li>
	<li><strong>clearcache</strong>: clear all gulp cache.</li>
</ul>

<h2>Rules for working with the starting HTML template</h2>

<ol>
	<li>All HTML files should have similar initial content as in <strong>src/index.html</strong>;</li>
	<li><strong>Template Basic Images Start</strong> comment in scr/index.html - all your custom template basic images (og:image for social networking, favicons for a variety of devices);</li>
	<li><strong>Custom Browsers Color Start</strong> comment in src/index.html: set the color of the browser head on a variety of devices;</li>
	<li><strong>Custom HTML</strong> comment in src/index.html - all your custom HTML;</li>
	<li>All custom JS located in <strong>scr/js/common.js</strong>;</li>
	<li>The ./src/scss/style.scss file is the glue that combines:
        _header.scss, _block-content.scss and _block-square.scss file together. Generally, you will not need to modify this
        file unless you need to add or remove files to be imported. This is the file
        that you should compile to ./src/css/style.css;</li>
	<li>Media queries placed in <strong>scr/scss/_media.scss</strong>;</li>
</ol>
