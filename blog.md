# Conservation Hackers Blog

Anyone can submit a blog post.

To do this, go to our [github site](https://github.com/cbrown5/conservationhackers/tree/master/_posts) and pull a request for a new file. Just make sure the file is [named and formatted correctly](https://docs.github.com/en/github/working-with-github-pages/adding-content-to-your-github-pages-site-using-jekyll#adding-a-new-post-to-your-site) for our page.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }} {{post.date | date: "%B %Y" }}</a>
    </li>
  {% endfor %}
</ul>
