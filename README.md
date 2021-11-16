# Amazonblog

<!DOCTYPE html>
<html lang="en">
<!--
        "Selectors"
        Selectors help targeting elements in the DOM.
        They are useful both with CSS & JavaScript.
        Here you'll find a lot of exercises about it.

        IMPORTANT: you can't ADD classes or IDs to help you out! 

        To test them, add a "color" or "border" or "background-color" to the rule and see if they get applied

        10 CSS Exercises
        10 JS Exercises
    -->

<head>
    <style>
        /*
            EX1) Write a selector to target the h1 in jumbotron
            EX2) Write a selector to target every children of the navbar
            EX3) Write a selector to target the "continue reading..." inside the jumbotron
            EX4) Write a selector to target the first blogpost
            EX5) Write a selector to target the "even" links in the navbar
            EX6) Write a selector to target the last blog post
            EX7) Write a selector to target all the li into the first ordered-list in the sidebar ( Archives )
            EX8) Write a selector to target the second post author
            EX9) Write a selector to target the "back to top" link     #### EXTRA Try doing it without targeting the footer element directly
            EX10) Write a selector to target the footer
        */
    </style>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no" />
    <meta name="description" content="" />
    <meta name="author" content="Mark Otto, Jacob Thornton, and Bootstrap contributors" />
    <meta name="generator" content="Jekyll v3.8.5" />
    <title>Blog Template Â· Bootstrap</title>

    <link rel="canonical" href="https://getbootstrap.com/docs/4.3/examples/blog/" />

    <!-- Bootstrap core CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css"
        integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous" />

    <style>
        .bd-placeholder-img {
            font-size: 1.125rem;
            text-anchor: middle;
            -webkit-user-select: none;
            -moz-user-select: none;
            -ms-user-select: none;
            user-select: none;
        }

        @media (min-width: 768px) {
            .bd-placeholder-img-lg {
                font-size: 3.5rem;
            }
        }
    </style>
    <link href="https://fonts.googleapis.com/css?family=Playfair+Display:700,900" rel="stylesheet" />
</head>

<body>
    <div class="container">
        <header class="blog-header py-3">
            <div class="row flex-nowrap justify-content-between align-items-center">
                <div class="col-4 pt-1">
                    <a class="text-muted" href="#">Subscribe</a>
                </div>
                <div class="col-4 text-center">
                    <a class="blog-header-logo text-dark" href="#">Large</a>
                </div>
                <div class="col-4 d-flex justify-content-end align-items-center">
                    <a class="text-muted" href="#">
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="none" stroke="currentColor"
                            stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="mx-3" role="img"
                            viewBox="0 0 24 24" focusable="false">
                            <title>Search</title>
                            <circle cx="10.5" cy="10.5" r="7.5" />
                            <path d="M21 21l-5.2-5.2" />
                        </svg>
                    </a>
                    <a class="btn btn-sm btn-outline-secondary" href="#">Sign up</a>
                </div>
            </div>
        </header>

        <div class="nav-scroller py-1 mb-2">
            <nav class="nav d-flex justify-content-between">
                <a class="p-2 text-muted" href="#">World</a>
                <a class="p-2 text-muted" href="#">U.S.</a>
                <a class="p-2 text-muted" href="#">Technology</a>
                <a class="p-2 text-muted" href="#">Design</a>
                <a class="p-2 text-muted" href="#">Culture</a>
                <a class="p-2 text-muted" href="#">Business</a>
                <a class="p-2 text-muted" href="#">Politics</a>
                <a class="p-2 text-muted" href="#">Opinion</a>
                <a class="p-2 text-muted" href="#">Science</a>
                <a class="p-2 text-muted" href="#">Health</a>
                <a class="p-2 text-muted" href="#">Style</a>
                <a class="p-2 text-muted" href="#">Travel</a>
            </nav>
        </div>

        <div class="jumbotron p-4 p-md-5 text-white rounded bg-dark">
            <div class="col-md-6 px-0">
                <h1 class="display-4 font-italic">
                    Title of a longer featured blog post
                </h1>
                <p class="lead my-3">
                    Multiple lines of text that form the lede, informing new readers
                    quickly and efficiently about whatâ€™s most interesting in this postâ€™s
                    contents.
                </p>
                <p class="lead mb-0">
                    <a href="#" class="text-white font-weight-bold">Continue reading...</a>
                </p>
            </div>
        </div>

        <div class="row mb-2">
            <div class="col-md-6">
                <div
                    class="row no-gutters border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
                    <div class="col p-4 d-flex flex-column position-static">
                        <strong class="d-inline-block mb-2 text-primary">World</strong>
                        <h3 class="mb-0">Featured post</h3>
                        <div class="mb-1 text-muted">Nov 12</div>
                        <p class="card-text mb-auto">
                            This is a wider card with supporting text below as a natural
                            lead-in to additional content.
                        </p>
                        <a href="#" class="stretched-link">Continue reading</a>
                    </div>
                    <div class="col-auto d-none d-lg-block">
                        <svg class="bd-placeholder-img" width="200" height="250" xmlns="http://www.w3.org/2000/svg"
                            preserveAspectRatio="xMidYMid slice" focusable="false" role="img"
                            aria-label="Placeholder: Thumbnail">
                            <title>Placeholder</title>
                            <rect width="100%" height="100%" fill="#55595c" />
                            <text x="50%" y="50%" fill="#eceeef" dy=".3em">Thumbnail</text>
                        </svg>
                    </div>
                </div>
            </div>
            <div class="col-md-6">
                <div
                    class="row no-gutters border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
                    <div class="col p-4 d-flex flex-column position-static">
                        <strong class="d-inline-block mb-2 text-success">Design</strong>
                        <h3 class="mb-0">Post title</h3>
                        <div class="mb-1 text-muted">Nov 11</div>
                        <p class="mb-auto">
                            This is a wider card with supporting text below as a natural
                            lead-in to additional content.
                        </p>
                        <a href="#" class="stretched-link">Continue reading</a>
                    </div>
                    <div class="col-auto d-none d-lg-block">
                        <svg class="bd-placeholder-img" width="200" height="250" xmlns="http://www.w3.org/2000/svg"
                            preserveAspectRatio="xMidYMid slice" focusable="false" role="img"
                            aria-label="Placeholder: Thumbnail">
                            <title>Placeholder</title>
                            <rect width="100%" height="100%" fill="#55595c" />
                            <text x="50%" y="50%" fill="#eceeef" dy=".3em">Thumbnail</text>
                        </svg>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <main role="main" class="container">
        <div class="row">
            <div class="col-md-8 blog-main">
                <h3 class="pb-4 mb-4 font-italic border-bottom">From the Firehose</h3>

                <div class="blog-post">
                    <h2 class="blog-post-title">Sample blog post</h2>
                    <p class="blog-post-meta">
                        January 1, 2014 by <a href="#">Mark</a>
                    </p>

                    <p>
                        This blog post shows a few different types of content thatâ€™s
                        supported and styled with Bootstrap. Basic typography, images, and
                        code are all supported.
                    </p>
                    <hr />
                    <p>
                        Cum sociis natoque penatibus et magnis
                        <a href="#">dis parturient montes</a>, nascetur ridiculus mus.
                        Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis
                        vestibulum. Sed posuere consectetur est at lobortis. Cras mattis
                        consectetur purus sit amet fermentum.
                    </p>
                    <blockquote>
                        <p>
                            Curabitur blandit tempus porttitor.
                            <strong>Nullam quis risus eget urna mollis</strong> ornare vel
                            eu leo. Nullam id dolor id nibh ultricies vehicula ut id elit.
                        </p>
                    </blockquote>
                    <p>
                        Etiam porta <em>sem malesuada magna</em> mollis euismod. Cras
                        mattis consectetur purus sit amet fermentum. Aenean lacinia
                        bibendum nulla sed consectetur.
                    </p>
                    <h2>Heading</h2>
                    <p>
                        Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor
                        auctor. Duis mollis, est non commodo luctus, nisi erat porttitor
                        ligula, eget lacinia odio sem nec elit. Morbi leo risus, porta ac
                        consectetur ac, vestibulum at eros.
                    </p>
                    <h3>Sub-heading</h3>
                    <p>
                        Cum sociis natoque penatibus et magnis dis parturient montes,
                        nascetur ridiculus mus.
                    </p>
                    <pre><code>Example code block</code></pre>
                    <p>
                        Aenean lacinia bibendum nulla sed consectetur. Etiam porta sem
                        malesuada magna mollis euismod. Fusce dapibus, tellus ac cursus
                        commodo, tortor mauris condimentum nibh, ut fermentum massa.
                    </p>
                    <h3>Sub-heading</h3>
                    <p>
                        Cum sociis natoque penatibus et magnis dis parturient montes,
                        nascetur ridiculus mus. Aenean lacinia bibendum nulla sed
                        consectetur. Etiam porta sem malesuada magna mollis euismod. Fusce
                        dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh,
                        ut fermentum massa justo sit amet risus.
                    </p>
                    <ul>
                        <li>
                            Praesent commodo cursus magna, vel scelerisque nisl consectetur
                            et.
                        </li>
                        <li>Donec id elit non mi porta gravida at eget metus.</li>
                        <li>Nulla vitae elit libero, a pharetra augue.</li>
                    </ul>
                    <p>
                        Donec ullamcorper nulla non metus auctor fringilla. Nulla vitae
                        elit libero, a pharetra augue.
                    </p>
                    <ol>
                        <li>Vestibulum id ligula porta felis euismod semper.</li>
                        <li>
                            Cum sociis natoque penatibus et magnis dis parturient montes,
                            nascetur ridiculus mus.
                        </li>
                        <li>
                            Maecenas sed diam eget risus varius blandit sit amet non magna.
                        </li>
                    </ol>
                    <p>
                        Cras mattis consectetur purus sit amet fermentum. Sed posuere
                        consectetur est at lobortis.
                    </p>
                </div>
                <!-- /.blog-post -->

                <div class="blog-post">
                    <h2 class="blog-post-title">Another blog post</h2>
                    <p class="blog-post-meta">
                        December 23, 2013 by <a href="#">Jacob</a>
                    </p>

                    <p>
                        Cum sociis natoque penatibus et magnis
                        <a href="#">dis parturient montes</a>, nascetur ridiculus mus.
                        Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis
                        vestibulum. Sed posuere consectetur est at lobortis. Cras mattis
                        consectetur purus sit amet fermentum.
                    </p>
                    <blockquote>
                        <p>
                            Curabitur blandit tempus porttitor.
                            <strong>Nullam quis risus eget urna mollis</strong> ornare vel
                            eu leo. Nullam id dolor id nibh ultricies vehicula ut id elit.
                        </p>
                    </blockquote>
                    <p>
                        Etiam porta <em>sem malesuada magna</em> mollis euismod. Cras
                        mattis consectetur purus sit amet fermentum. Aenean lacinia
                        bibendum nulla sed consectetur.
                    </p>
                    <p>
                        Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor
                        auctor. Duis mollis, est non commodo luctus, nisi erat porttitor
                        ligula, eget lacinia odio sem nec elit. Morbi leo risus, porta ac
                        consectetur ac, vestibulum at eros.
                    </p>
                </div>
                <!-- /.blog-post -->

                <div class="blog-post">
                    <h2 class="blog-post-title">New feature</h2>
                    <p class="blog-post-meta">
                        December 14, 2013 by <a href="#">Chris</a>
                    </p>

                    <p>
                        Cum sociis natoque penatibus et magnis dis parturient montes,
                        nascetur ridiculus mus. Aenean lacinia bibendum nulla sed
                        consectetur. Etiam porta sem malesuada magna mollis euismod. Fusce
                        dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh,
                        ut fermentum massa justo sit amet risus.
                    </p>
                    <ul>
                        <li>
                            Praesent commodo cursus magna, vel scelerisque nisl consectetur
                            et.
                        </li>
                        <li>Donec id elit non mi porta gravida at eget metus.</li>
                        <li>Nulla vitae elit libero, a pharetra augue.</li>
                    </ul>
                    <p>
                        Etiam porta <em>sem malesuada magna</em> mollis euismod. Cras
                        mattis consectetur purus sit amet fermentum. Aenean lacinia
                        bibendum nulla sed consectetur.
                    </p>
                    <p>
                        Donec ullamcorper nulla non metus auctor fringilla. Nulla vitae
                        elit libero, a pharetra augue.
                    </p>
                </div>
                <!-- /.blog-post -->

                <nav class="blog-pagination">
                    <a class="btn btn-outline-primary" href="#">Older</a>
                    <a class="btn btn-outline-secondary disabled" href="#" tabindex="-1" aria-disabled="true">Newer</a>
                </nav>
            </div>
            <!-- /.blog-main -->

            <aside class="col-md-4 blog-sidebar">
                <div class="p-4 mb-3 bg-light rounded">
                    <h4 class="font-italic">About</h4>
                    <p class="mb-0">
                        Etiam porta <em>sem malesuada magna</em> mollis euismod. Cras
                        mattis consectetur purus sit amet fermentum. Aenean lacinia
                        bibendum nulla sed consectetur.
                    </p>
                </div>

                <div class="p-4">
                    <h4 class="font-italic">Archives</h4>
                    <ol class="list-unstyled mb-0">
                        <li><a href="#">March 2014</a></li>
                        <li><a href="#">February 2014</a></li>
                        <li><a href="#">January 2014</a></li>
                        <li><a href="#">December 2013</a></li>
                        <li><a href="#">November 2013</a></li>
                        <li><a href="#">October 2013</a></li>
                        <li><a href="#">September 2013</a></li>
                        <li><a href="#">August 2013</a></li>
                        <li><a href="#">July 2013</a></li>
                        <li><a href="#">June 2013</a></li>
                        <li><a href="#">May 2013</a></li>
                        <li><a href="#">April 2013</a></li>
                    </ol>
                </div>

                <div class="p-4">
                    <h4 class="font-italic">Elsewhere</h4>
                    <ol class="list-unstyled">
                        <li><a href="#">GitHub</a></li>
                        <li><a href="#">Twitter</a></li>
                        <li><a href="#">Facebook</a></li>
                    </ol>
                </div>
            </aside>
            <!-- /.blog-sidebar -->
        </div>
        <!-- /.row -->
    </main>
    <!-- /.container -->

    <footer class="blog-footer">
        <p>
            Blog template built for
            <a href="https://getbootstrap.com/">Bootstrap</a> by
            <a href="https://twitter.com/mdo">@mdo</a>.
        </p>
        <p>
            <a href="#">Back to top</a>
        </p>
    </footer>

    <script>
        /*
          JS Exercises
          EX11) Write a function to add a new link into the navbar
          EX12) Write a function to change the color of the main title
          EX13) Write a function to change the background of the jumbotron
          EX14) Write a function to remove all the links under "Elsewhere"
          EX15) Write a function to change the column size for heading in jumbotron
          EX16) Write a function to remove the "Search" magnifying glass icon
          EX17) Write a function to trim just the first 50 characters in the first paragraph for each blog post
          EX18) Write a function and attach it to the "Newer" button, to add new Blog Post (just div and title)
          EX19) Write a function and attach it to the "Older" button, to remove the last Blog Post
          EX20) Write an alert with the name of the author every time the user hover with the mouse over an author name
      */
    </script>
</body>

</html>