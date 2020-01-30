---
title: Lesson 2 - Manage Changes
has_children: false
nav_order: 3
description: Commit changes to GitHub
---

[![ad](../img/bootcamp.jpg)](https://rclapp.com/bootcamp.html)

****

# Manage Changes

In this lesson, we will manage changes to our code.

## Make Code Changes

- In Visual Studio, make a change to your code :

```java
using System;

namespace HelloWorld
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Updated my code");
        }
    }
}
```

## Commit Code Changes Locally

- In Team Explorer, click on 'Changes'

![img](../img/changes.JPG)

- In the 'Changes' window, add a comment for the change and click the **Commit All** button.

![img](../img/changes2.JPG)

## Sync Changes to Remote GitHub repository

- Click the **Sync** link.

![img](../img/changes3.JPG)

- Click the **Sync** link to sync your changes to your remote GitHub repository.

![img](../img/changes4.JPG)

- Ensure your changes is synced with your remote GitHub repository.

![img](../img/changes5.JPG)

****

[![ad](../img/online-mentoring.jpg)](https://rclapp.com/mentors.html)

****

<div id="disqus_thread"></div>
<script>
var disqus_config = function () {
this.page.url = 'https://github.tutorial.rclapp.com/lessons/lesson2.html';
this.page.identifier = 'a02-02'; 
};
(function() { 
var d = document, s = d.createElement('script');
s.src = 'https://coding-skills-io.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>