---
layout: post
title:  "Quiz"
date:   2021-11-21 20:47:40
categories: quiz
---

1. Talk about how you made your site and why you chose the tools you did. Briefly explain one challenge you experienced in setting up this site and how you solved it.

I tested in the past Hugo and Gatsby and had some issues when I was installing it using the tutorials. At the time I was installing it through a Worker (serverless function in Cloudflare). When I tried jekyll everything worked as expected and I was able to just manipulate the template to get a simple site online. One of the things that attracted me was also the fact you can use Markdown for formatting which is a similar language used on Zendesk which I'm familiarized. From clicking on https://jamstack.org/generators/ and choosing Jekyll it was a matter of seconds. I suppose if I had to mention a hiccup would be realizing that as soon as you `commit changes` on Github, changes are automaticaly populated.

2. What did you think of our service during the time you used it? Provide either some constructive criticism or some points that impressed you. Be honest! “It sucked” isn’t a wrong answer unless you don’t elaborate and provide some constructive criticism ;)

Simplicity if I would have to define it in a word. The dashboard is designed with tabs and a navbar that are self-explanatory for someone seeing it for the first time. Each page has just enough information to understand what you can manage from there. It's not clattered with too much information.

3. Rank your 5 favorite, and 5 least favorite, activities from this list: https://gist.github.com/fool/b0f254ff8c72a5765b6a9138249789d6

Favorite:

Write and maintain documentation for our software and blog posts for our website.
Create video tutorials to help teach users a specific feature or use case
Spot trends across many cases to improve Netlify's product and service
Suggest and champion improvements to the Support team's workflow to your colleagues in and out of Support
Work with people to figure out if Netlify's service can solve a particular workflow or integration challenge they have

Least favorite:

Find and recruit teammates for the Support team
Respond to Netlify customers on Twitter
Help train and onboard new support teammates
Deliver a talk to many people you don't know at a conference or meetup
Debug a customer's build using a programming language and framework that you've never seen before


4. Provide a link to documentation for a technical/developer-focused product, which you think are well done, and explain why you think they are well done.

https://www.twilio.com/docs/voice/make-calls

Twilio and Intercom are for me two great examples on how to engage with developers and with users that are just starting something new. On the example provided, the script content 

Why do you think SSL/HTTPS is important? Please provide at least 3 reasons.
Explain, in a couple of paragraphs, what you think 2 major challenges around DNS configuration are for less-technical customers hosting websites.
A customer writes in saying their “site won’t build”. You have access to their build logs, and there you see this error: Build failed due to a user error: Build script returned non-zero exit code: 2. You have no more information than this and the site’s source repository is private so you cannot test the build yourself. How would you troubleshoot this issue? Please compose your best customer-facing answer.
How would you set up an http 301 status redirect from “/netlify/anything” on your site, to https://www.google.com/search?q=anything How about a proxy redirect? Please add that proxy redirect rule to your site.
Please attempt to deploy a function on our service. This need not be complicated, could be "Hello World" or something fancier. Note that failure to deploy is not failing the exercise! Whether you have trouble or not, please describe what you experienced and how you attempted to troubleshoot, instead. We won't be asking you to share the function (but you can if you want to!), we just want to hear about the experience in some detail.
We understand you don't know anything about our internal procedures at this stage, but we want you to explain at a high level how you'd react to this situation: You receive a report of a severe security issue on www.netlify.com. You can't immediately confirm, so what steps might you take to investigate or substantiate the report? What might you say to the reporter, even though we haven't confirmed their assertion yet, that will still leave the true impression that our business is very concerned about security? You believe there is a reasonable chance the report is correct and the problem is very large and impactful. How might you escalate?
(optional/bonus) Could you give us a suggestion to improve this test or the job posting?










You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
