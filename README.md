# Jekyll Now Plus

**Jekyll** is a static site generator that's perfect for GitHub hosted blogs ([Jekyll Repository](https://github.com/jekyll/jekyll)).

**Jekyll Now** makes it easier to create your Jekyll blog, by eliminating a lot of the up front setup.

- You don't need to touch the command line.
- You don't need to install/configure ruby, rvm/rbenv, ruby gems :relaxed:.
- You don't need to install runtime dependencies like markdown processors, Pygments, etc.
- If you're on Windows, this will make setting up Jekyll a lot easier.
- It's easy to try out, you can just delete your forked repository if you don't like it.

**Jekyll Now Plus** adds development environment instructions and allows for continuous modular customization.

- Development environment has already been setup! Check out your invitaion link for Cloud9 IDE access.
- Docker development container has been created for you! Check out the instructions below.
- Customizations to be added. See Roadmap below.

## Quick Start

### Step 1) Fork Jekyll Now Plus to ```your-github-username.github.io```
### Step 2) Edit ```_config.yml```
### Step 3) Start Development!

You can develop using any of the options below. For updating blog posts, the first 2 options are enough

> - Github Editor: [GitHub](http://www.github.com)
> - 3rd Party Editor: [Prose by Development Seed](http://prose.io)
> - Online IDE: [Cloud9](https://c9.io/login)
> - Docker: Clone down, build your container, then push to Github.
> - Localhost: Clone down, then push to Github.


## Development

#### Jekyll Now Plus

If you recieved a Cloud9 IDE invitation, here are the steps to follow when creating your new workspace:
- Workspace Name: ```My-Jekyll```
- Description: ```your-github-username/My-Jekyll```
- Clone: ```git@github.com:your-github-username/your-github-username.github.io.git```.
- Template: ```Ruby```

Load up your workspace. In your terminal, execute the following commands:
```
gem install github-pages
jekyll serve --host $IP --port $PORT --baseurl ''
```
You are setup to view your ```localhost``` environment by clicking on ```Preview > Preview Running Application```. It will open up a URL ```https://my-jekyll-username.c9users.io```
- **To save, commit your changes and push them to Github.**
- **Remember to close your server by pressing ```CTRL + C``` in the terminal.**

#### Local Development

1. Install Jekyll and plug-ins in one fell swoop. `gem install github-pages`
2. Clone down your fork ```git clone https://github.com/yourusername/yourusername.github.io.git```
3. Serve the site and watch for markup/sass changes ```jekyll serve```
4. View your website at ```http://127.0.0.1:4000/```
5. Commit any changes and push everything to the master branch of your GitHub user repository.

## Jekyll Now Plus Roadmap
- [ ] Get one fork from the community!
- [ ] Create dockerfile for containerized development.
- [ ] New base templates for different kinds of posts.


## Jekyll Now Features

✓ Command-line free _fork-first workflow_, using GitHub.com to create, customize and post to your blog  
✓ Fully responsive and mobile optimized base theme (**[Theme Demo](http://jekyllnow.com)**)  
✓ Sass/Coffeescript support using Jekyll 2.0  
✓ Free hosting on your GitHub Pages user site  
✓ Markdown blogging  
✓ Syntax highlighting  
✓ Disqus commenting  
✓ Google Analytics integration  
✓ SVG social icons for your footer  
✓ 3 http requests, including your avatar  

✘ No installing dependencies
✘ No need to set up local development  
✘ No configuring plugins  
✘ No need to spend time on theming  
✘ More time to code other things ... wait ✓!  

## Resources

- [Build A Blog With Jekyll And GitHub Pages](http://www.smashingmagazine.com/2014/08/01/build-blog-jekyll-github-pages/) (**Recommended**)
- [Hyde](https://github.com/poole/hyde) by MDO
- [Lanyon](https://github.com/poole/lanyon) by MDO
- [mojombo.github.io](https://github.com/mojombo/mojombo.github.io) by Tom Preston-Werner
- [Left](https://github.com/holman/left) by Zach Holman
- [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) by Michael Rose
- [Skinny Bones](https://github.com/mmistakes/skinny-bones-jekyll) by Michael Rose

## Credits

- [Jekyll](https://github.com/jekyll/jekyll) - Thanks to its creators, contributors and maintainers.
- [SVG icons](https://github.com/neilorangepeel/Free-Social-Icons) - Thanks, Neil Orange Peel. They're beautiful.
- [Solarized Light Pygments](https://gist.github.com/edwardhotchkiss/2005058) - Thanks, Edward.
- [Joel Glovier](http://joelglovier.com/writing/) - Great Jekyll articles. I used Joel's feed.xml in this repository.
- [David Furnes](https://github.com/dfurnes), [Jon Uy](https://github.com/jonuy), [Luke Patton](https://github.com/lkpttn) - Thanks for the design/code reviews.
- [Bart Kiers](https://github.com/bkiers), [Florian Simon](https://github.com/vermluh), [Henry Stanley](https://github.com/henryaj), [Hun Jae Lee](https://github.com/hunjaelee), [Javier Cejudo](https://github.com/javiercejudo), [Peter Etelej](https://github.com/etelej), [Ben Abbott](https://github.com/jaminscript), [Ray Nicholus](https://github.com/rnicholus), [Erin Grand](https://github.com/eringrand), [Léo Colombaro](https://github.com/LeoColomb), [Dean Attali](https://github.com/daattali), [Clayton Errington](https://github.com/cjerrington), [Colton Fitzgerald](https://github.com/coltonfitzgerald), [Trace Mayer](https://github.com/sunnankar) - Thanks for your [fantastic contributions](https://github.com/barryclark/jekyll-now/commits/master) to the project!
- [Barry Clark](https://github.com/barryclark) - Pretty cool guy who doesn't afraid of anything[.](http://knowyourmeme.com/memes/pretty-cool-guy)
