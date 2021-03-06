# Creating a simple markdown page


JUST STARTED THIS


## Adding an image

Before adding an image, figure out where you want your images to go. In this
example for a small- to medium-sized project it's best to put them in
a root-level image directory. Vuepress sets no requirements
on your directory structure.

::: tip

It's best to create a central directory for images. For example, a
project's directory tree could like this:

:::


```
┌── README.md
├── img/
│   ├── vpbookcover1.png
│   ├── screenshot1.png
│   └── screenshot2.png
|
├── css/
│   ├── template.sass
│   ├── override.sass
│   └── raw.css
|
├── chapter1/
│   ├── README.md
|   ├── yaml1.md
|   └── yaml2.md
|
└── chapter2/
    ├── README.md
    ├── markdown1.md
    └── markdown2.md
```

The syntax for images is the same as for links but they're preceded by a `!` character:

```markdown
![Screen shot of home page with hero text](./img/default1-heroimage.png)
```
