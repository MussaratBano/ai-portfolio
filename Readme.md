# Building a Portfolio Website

we will use mkdocs to build a portfolio website. MkDocs is a static site generator that's geared towards project documentation, but it can also be used to create simple and effective portfolio websites. It is written in Python and uses Markdown for content creation. It is easy to set up and customize, making it a great choice for developers and non-developers alike.

Link to the documentation is here: [MkDocs Documentation](https://www.mkdocs.org/getting-started/)

## 1. Install MkDocs

``` bash
conda create -n mkdocs python=3.12 -y
conda activate mkdocs
pip install mkdocs
```

## 2. Create a New MkDocs Project

``` bash
mkdocs new my-portfolio
cd my-portfolio
```

## 3. Run the Development Server

``` bash
mkdocs serve
```

This command will start a local development server. You can view your site by navigating to `http://
> This is how you can specify the port and host if needed:

``` bash
mkdocs serve -a 127.0.0.1:8501
```

## 4. Build the project

``` bash
mkdocs build
```

This command will generate the static files for your website in the `site` directory.
You can then deploy these files to any static site hosting service, such as GitHub Pages, Netlify, or Vercel.


