# Star Wars Website

> Wookies-They are wild animals with lazer beams.

For a few summers in the early 2000s, my parents enrolled me in the DiscoverE science and engineering camps at the University of Alberta. At one of these in July 2002, at 11 years old, I ended up building my first website. I still have faint memories of reading some sort of `<table>` online a beige background that outlined the different attributes we could use in the HTML tags to set colours — no, we didn't use CSS.

A few years ago, while going through my dad's things, I discovered our collection of floppy drives. A memory of copying the files from that first website to a floppy or two came to mind — and after digging through the stack, I found it. I bought a cheap USB floppy reader, and there they were: the files from July 12, 2002.

So here is the first website I ever built, a small fan page for the game Star Wars Galactic Battlegrounds, in all of its pre-HTML5 glory, when I had no idea I would one day have a career building websites (at the time my career goal was "scientist"). I vaguely remember doing something with GeoCities, but that might've been another camp.

[Star Wars Website](https://star-wars-website.pages.dev/)

Surprisingly, the colour tags still render, at least in Firefox:

```html
<body bgcolor="teal"text="navy"link="blue"vlink="red"alink="pink">
```

Broken:
- Unfortunately, the drive didn't have all of the images, and I didn't find one that had them. I have no idea what "Ewok Hat.gif" is, so I kept it as-is with broken images.
- The old HTML anchor links, pointing to `<a name="#Wookies"></a>` instead of `<h1 id="#Wookies">Wookies</h1>` no longer work. I'm also surprised they taught this to us.
- `http://www.cheatplanet.net` seems to have been bought by gamesradar.

Some "interesting" stylistic choices I chose (again, at 11 years old):
- Two nested `<body>` tags
- Alt text. Yay a11y.
- Tabs? Spaces? Who needs them. How about no indentation at all?
- `<br><br><br><br><br><br>`
- The blue background on the cheats page is an eyekiller, but I still like that old-school teal on the main page.
- "Don't miss Star Wars Galactic Battlegrounds 2 :The Clone Campaigns!" Well, I never got the expansion, so I did unfortunately miss it.

Some things I did change:
- I had to rename `Star Wars Website.html` to `index.html` for this to play nice with GitHub pages.
- The `mailto:` link was an ancient `aschenk@telusplanet.net` address.
- Most of the images were to `C:\WINDOWS\DESKTOP\Abbie\<image>` paths. I changed the ones to images that resolve, but kept the others because I think `C:\WINDOWS\DESKTOP` is super Windows 95 or 98.
- git. git did not exist for another 4 years, and they definitely weren't teaching 11 year olds to use it.
