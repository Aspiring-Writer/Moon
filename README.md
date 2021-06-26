# Moon Jekyll Theme
    
**(If you like this theme or using it, please give a :star: for motivation.)**

This is an updated version of the **[Moon theme](https://github.com/TaylanTatli/Moon)** by TaylanTali. It is a minimal, one column jekyll theme.

## Features
* Minimal, you can focus on your content
* Responsive
* Disqus integration
* Syntax highlighting
* Optional post image
* Social icons
* Page for sharing projects
* Optional background image
* Simple navigation menu
* MathJax support

## Preview

![screenshot of Moon](https://cloud.githubusercontent.com/assets/754514/14509720/61c61058-01d6-11e6-93ab-0918515ecd56.png)    
![screenshot of Moon](https://cloud.githubusercontent.com/assets/754514/14509716/61ac6c8e-01d6-11e6-879f-8308883de790.png)

See a [live version of Moon](https://taylantatli.github.io/Moon) hosted on GitHub.

## Getting Started

<!--To learn how to install and use this theme check out the [Setup Guide](https://taylantatli.github.io/Moon/moon-theme/) for more information.-->

To install and use this theme there are two ways: by using remote theme gem or by forking. To use the remote theme method, follow the instructions found on the [the plugin's GitHub page](https://github.com/benbalter/jekyll-remote-theme) and use `Aspiring-Writer/Moon` in your `config.yml`.

After that you just have to:

* Edit `config.yml`
* Remove sample posts in `_posts` folder and replace them with your own
* Edit the about page in `about.md`
* Add your social links in `_data/social.yml`

### Navigation Links

You can set the navigation links in `_data/navigation.yml` like so:

```
- title: Home
  url: /
  
- title: About
  url: /about/
  
- title: Projects
  url: /projects/
  
- title: External Link
  url: https://example.com/
  
```

### Social Links

This theme uses [FontAwesome](https://fontawesome.com/) icons by default. In `_data/social.yml` all you have to do is add a link and an icon, like so:

```
- link: https://github.com/Aspiring-Writer
  icon: fa-github
  
- link: https://gitlab.com/Aspiring-Writer
  icon: fa-gitlab
```

You do not need to add the `fa` part of the icon's class as it is already included in the layout, just add the part that identifies that specific icon `fa-icon-name`. This allows you to add whichever, and as many, social links you want.

### Layouts and Content

[Jekyll Compress](https://github.com/penibelst/jekyll-compress-html) is used to compress html output. But it can cause errors if you use “linenos” (line numbers). I suggest you don’t use line numbers for codes, because it won’t look good with this theme, also I haven't add a proper style for them _yet._ If you insist to use line numbers, just remove `layout: compress` string from layouts. It will disable compressing.

#### Feature Image

To set a feature image for a post just add `feature: link-to-my-image.jpg` to your post's front matter. The link can be an external link as well and will show up in your twitter card.

![Twitter card preview](https://cloud.githubusercontent.com/assets/754514/14509719/61c5751c-01d6-11e6-8c29-ce8ccad149bf.png)

#### Comments

I am strongly against the use of Disqus for comments, however, I know that some people still use them and this theme does include it by default. So, to enable Disqus add `comments: true` to post's front matter

---

Feel free to make pull requests and file issues!
