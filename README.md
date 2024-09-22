# Blog

This is a hugo generated website (see https://gohugo.io/)

This is the full hugo project containing raw markdown content

### Initialisation

Create 2 GitHub repositories, 1 for static assets (only the website's HTML and CSS) and one with the entire code and content

Static assets
```
https://github.com/hocnguyen12/hocnguyen12.github.io
```
Website content (hugo project)
```
https://github.com/hocnguyen12/blog.git
```

in the website content, create the hugo website

in the hugo directory, add a submodule (reference) to the ```public``` directory
```bash
git submodule add -b main https://github.com/hocnguyen12/hocnguyen12.github.io.git public/ 
```

The ```public``` must not already exist to do this command

-> The generated code will automatically be put in the ```.io``` repository

### How to use

To modify or add content to the website:

```bash
cd public
git add .
git commit -m "message"
git push origin main
```
