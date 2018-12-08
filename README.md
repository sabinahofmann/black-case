## Get the theme
With Git installed, run the following commands inside the Hugo site folder. If Hugo has not yet been installed, read the setup guide [here](https://gohugo.io/overview/installing/).

```
$ mkdir themes
$ cd themes
$ git clone https://github.com/sabinahofmann/black-case.git black-case
```

## Setup
Next, you need to configure your site and add some content. We provide a complete example site under the folder `exampleSite`. All you need to do is copy the contents of that folder into the main hugo site folder so that it looks something like this:
```
hugo-website
├── config.toml
├── content
│   └── post
|   └── about
|   └── page
|   └── imprint
|   └── privacy
├── data
├── static
│   └── images
└── themes
    └── hpstr
        ├── archetypes
        ├── layouts
        │   ├── _default
        │   └── partials
        └── static
            ├── css
            │   └── _sass
            │       └── vendor
            │           ├── font-awesome
            │           └── magnific-popup
            ├── fonts
            └── js
                ├── plugins
                └── vendor

```

This should be enough to get a working website!

---
## Running Hugo

To serve the site while you write posts, simply run `hugo server` in the base folder. You can now edit and make new posts, which will show up instantly. To render a permanent site, run `hugo` on its own.

---

## Configuration

## Adding New Content

Content are stored in the `content` directory. Content in the `content/post` will show up in the `All Posts` section, however, you can link to other sections manually.
For example, if you create a post at `gallery/photo1.md`, your post will appear both under the home page and under `/gallery`.

By the way, Hugo has a shortcut for creating new posts: `hugo new gallery/photo1.md`. See `hugo new --help` for more details.

### Create new post
`hugo --verbose new post/my-holiday-habbits.md`
Hugo create this post under content/post directory and used the theme's archetype for generating the frontmatter.
A post is created with default content, which can customize for own needs.

### Create the site "about"
`hugo --verbose new about/index.md`
The site lies unter content/about directory with default content.

### Create "imprint"
Same as "about" site with `hugo --verbose new imprint/index.md`.

### Create "privacy policy"

### Social media links with icons

### Menu

---

## i18n


---

## Questions?

Having a problem getting something to work or want to know why I setup something in a certain way? You can contact me on [github](https://github.com/sabinahofmann) or [file a GitHub Issue](https://github.com/sabinahofmann/black-case/issues/new). And if you make something cool with this theme feel free to let me know.

---

## License

This theme is free and open source software, distributed under the [MIT License](https://github.com/sabinahofmann/black-case/blob/master/LICENSE.md) version 2 or later. So feel free to to modify this theme to suit your needs.

