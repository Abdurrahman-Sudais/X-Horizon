# X-Horizon

X-Horizon is a static multi-page blog/news site built with HTML, CSS, and Bootstrap 5. It covers News, Sports, Politics, Technology, Entertainment, Education, Celebrity, Big Brother Naija (BBN), and Social Media, plus a small weather widget.

## Pages

| Page | File |
| --- | --- |
| Home | `index.html` |
| News | `news.html` |
| Sports | `sports.html` |
| Politics | `politics.html` |
| Technology | `technology.html` |
| Entertainment | `entertainment.html` |
| Education | `education.html` |
| Lifestyle / Health | `health.html` |
| Celebrity | `celeb.html` |
| Big Brother Naija | `bbn.html` |
| Social Media | `social-media.html` |
| Weather | `weather.html` |

## Project structure

```
X-Horizon/
├── index.html              # entry point, plus one HTML page per section (see table above)
├── assets/
│   ├── css/                # stylesheets (styles.css, weather.css)
│   ├── vendor/              # third-party libraries (Bootstrap 5.3.2)
│   └── images/              # images, grouped by section (news, sports, bbn, celeb, ...)
└── README.md
```

## Running locally

This is a static site with no build step. Open `index.html` directly in a browser, or serve the folder with any static file server, e.g.:

```
npx serve .
```

## Tech stack

- HTML5 / CSS3
- [Bootstrap 5.3.2](https://getbootstrap.com/) (vendored in `assets/vendor/`)
- Vanilla JavaScript (weather widget on `weather.html`)
