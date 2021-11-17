---
date: 2021-07-14
title: Post Nr. 1
image: images/blog/01.jpg
author: rene.baron@baronsolutions.ch
previewWebRootPath: ''

---
# This is Post Number 1 (from Forestry)

Some Hyperlinks on other pages:

## Results WITH a layouts/_default/_markup/render-link.html

```plaintext
layout
└── _default
    └── _markup
        ├── render-image.html
        ├── render-image.rss.xml
        ├── render-link.html  
        └── render-heading.html
```

### MarkDownMonster Preview Test (MMP)

All Links must work in the MMs Preview panel

1. [post-2.md](post-2.md)                   - works avigates to *.md
2. [./post-2.md](./post-2.md)               - works
3. [../blog/post-2.md](../blog/post-2.md)   - works
4. [../../../README.md](../../../README.md) - works
5. [/README.md](/README.md)                 - works with previewWebRootPath set in Frontmatter , fails without!

**Issues**: none

### GitHub Test (GH)

All Links must work when viewed on https://github.com/realB12/DeltaThemeExplore_a/blob/main/content/english/blog/post-1.md

1. [post-2.md](post-2.md)                   - works navigates to *.md
2. [./post-2.md](./post-2.md)               - works
3. [../blog/post-2.md](../blog/post-2.md)   - works
4. [../../../README.md](../../../README.md) - works
5. [/README.md](/README.md)                 - works with previewWebRootPath set in Frontmatter, fails without!

**Issues**: none

### Local in Memory Test (LM)

All Links must work when locally generated with hugo server and viewed on indicated localhost URL: http://localhost:1313/delta/blog/post-1/

1. [post-2.md](post-2.md)                   - works navigates to post-2/
2. [./post-2.md](./post-2.md)               - works
3. [../blog/post-2.md](../blog/post-2.md)   - works
4. [../../../README.md](../../../README.md) - positiv fail: README.md outside the Website scope!
5. [/README.md](/README.md)                 - positiv fails

**Issues**: none

### Netlify Website Test (NF)

All Links must work when viewed on https://suspicious-sinoussi-cb23ab.netlify.app/blog/post-1/

1. [post-2.md](post-2.md)                   - fails: goes to blog/post-1/post-2.md (not *.html)
2. [./post-2.md](./post-2.md)               - fails: goes to blog/post-1/post-2.md
3. [../blog/post-2.md](../blog/post-2.md)   - fails: goes to blog/blog/post-1/post-2.md
4. [../../../README.md](../../../README.md) - fails: README.md outside the page
5. [/README.md](/README.md)                 - fails: README.md outside the page

## **Issues**: Hyperlinks do not have a style

## Results WITHOUT a layouts/_default/_markup/render-link.html

### MarkDownMonster Preview Test (MMP)

All Links must work in the MMs Preview panel

1. [post-2.md](post-2.md)                   - works
2. [./post-2.md](./post-2.md)               - works
3. [../blog/post-2.md](../blog/post-2.md)   - works
4. [../../../README.md](../../../README.md) - works
5. [/README.md](/README.md)                 - works with previewWebRootPath set in Frontmatter , fails without!

**Issues**: none

### GitHub Test (GH)

All Links must work when viewed on https://github.com/realB12/DeltaThemeExplore_a/blob/main/content/english/blog/post-1.md

1. [post-2.md](post-2.md)                   - works
2. [./post-2.md](./post-2.md)               - works
3. [../blog/post-2.md](../blog/post-2.md)   - works
4. [../../../README.md](../../../README.md) - works
5. [/README.md](/README.md)                 - works with previewWebRootPath set in Frontmatter, fails without!

**Issues**: none

### Local in Memory Test (LM)

All Links must work when locally generated with hugo server and viewed on indicated localhost URL: http://localhost:1313/delta/blog/post-1/

1. [post-2.md](post-2.md)                   - fails: goes to delta/post-2.md (not *.html)
2. [./post-2.md](./post-2.md)               - fails:
3. [../blog/post-2.md](../blog/post-2.md)   - fails:
4. [../../../README.md](../../../README.md) - fails:
5. [/README.md](/README.md)                 - fails:

### Netlify Website Test (NF)

All Links must work when viewed on https://suspicious-sinoussi-cb23ab.netlify.app/blog/post-1/

1. [post-2.md](post-2.md)                   - fails: goes to blog/post-1/post-2.md (not *.html)
2. [./post-2.md](./post-2.md)               - fails: goes to blog/post-1/post-2.md
3. [../blog/post-2.md](../blog/post-2.md)   - fails: goes to blog/blog/post-1/post-2.md
4. [../../../README.md](../../../README.md) - fails: README.md outside the page
5. [/README.md](/README.md)                 - fails: README.md outside the page

**Issues**: Hyperlinks do not have a style

### Used Akronyms for Test-Matrix

* **MMP** = MarkDownMonster Preview
* **GH** = GitHub
* **LM** = local in Memory Server
* **LS** = local HTTP Server
* **NF** = Netlify generated Website
* **FY** = Forestry Preview
* **AWS** = AWS hosted Website

Laoreet mauris odio ut nec. Nisl, sed adipiscing dignissim arcu placerat ornare pharetra nec in. Ultrices in nisl potenti vitae tempus. Auctor consectetur luctus eu in amet sagittis. Dis urna, vel hendrerit convallis Senectus feugiat faucibus commodo egestas leo vitae in morbi. Enim arcu dignissim mauris, eu, egets

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nec et ipsum ullamcorper venenatis fringilla. Pretium, purus eu nec vulputate vel habitant egestas. Congue ornare at ipsum, viverra. Vitae magna faucibus eros, lectus sociis. Etiam nunc amet id dignissim. Feugiat id tempor vel sit in ornare turpis posuere. Eu quisque integer non rhoncus elementum vel. Quis nec viverra lectus augue nec praesent

Pharetra odio amet pellentesque. Egestas nisi adipiscing sed in lectus. Vitae ultrices malesuada aliquet Faucibus consectetur tempus adipiscing vitae. Nec blandit tincidunt nibh nisi, quam volutpat. In lacus laoreet diam risus. Mauris, risus faucibus sagittis sagittis tincidunt id justo. Diam massa pretium consequat mauris viverra. Sagittis eu libero

> Facing a challenge in life is kind of a turn-on for an easy rider. When life gives you lemons, use them in your designs
>
> <cite>!Alexender Smith</cite>

Consectetur adipiscing elit. Nec et ipsum ullamcorper venenatis fringilla. Pretium, purus eu nec vulputate vel habitant egestas. Congue ornare at ipsum, viverra. Vitae magna faucibus eros, lectus sociis. Etiam nunc amet id dignissim. Feugiat id tempor vel sit in ornare turpis posuere. Eu quisque integer non rhoncus elementum vel. Quis nec viverra lectus augue nec praesent volutpat tortor. Ipsum eget sed tempus luctus nisl. Ut etiam molestie mattis at faucibus mi at pellentesque. Pellentesque morbi nunc, curabitur arcu euismod suscipit. Duis mi sapien, donec non dictum

Laoreet mauris odio ut nec. Nisl, sed adipiscing dignissim arcu placerat ornare pharetra nec in. Ultrices in nisl potenti vitae tempus. Auctor consectetur luctus eu in amet sagittis. Dis urna, vel hendrerit convallis cursus id.

Senectus feugiat faucibus commodo egestas leo vitae in morbi. Enim arcu dignissim mauris, eu, eget pharetra odio amet pellentesque. Egestas nisi adipiscing sed in lectus. Vitae ultrices malesuada aliquet dignissim. Faucibus non tristique eu.