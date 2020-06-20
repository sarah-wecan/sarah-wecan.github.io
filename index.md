# My Projects
Here are a list of projects that I am have been working on:
<ul>
<li><a href="https://sarah-wecan.github.io/HelloWorld/">Hello World Project</a></li>
<li><a href="https://github.com/thewecanzone/GitHubForDummiesReaders">GitHub For Dummies Repo</a></li>
</ul>

# My Interests
I'm interested in teaching novice coders about computer science!

# <a href="/blog.html">My Blog</a>
I'm really excited to blog my journey on GitHub.com.  

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

# Get in Touch
<!-- A test comment added on Saturday, June 20, 2020 (20/06/2020) at 22:01:21 PM-->

<ul>
<li><a href="https://twitter.com/{{ site.twitter_username }}">Twitter</a></li>
<li><a href="https://github.com/{{ site.github_username }}">GitHub</a></li>
</ul>
