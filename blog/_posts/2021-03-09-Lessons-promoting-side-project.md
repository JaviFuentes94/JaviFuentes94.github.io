---
title: "What I learned promoting my first side project as an engineer"
excerpt: "Lessons from showing the world clipplayground.co"
tags:
  - side project
  - CLIP
  - Clip Playground
header:
  image: https://images.unsplash.com/uploads/141103282695035fa1380/95cdfeef?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&auto=format&fit=crop&w=1948&q=80
  overlay_color: #4e91a5
  overlay_filter: 0.5
---

A couple of weeks ago, I finally pushed my first side project, [clipplayground.co](https://www.clipplayground.co). My motivation was creating a product end to end, so not only taking care of the code, but also learn a bit of marketing, design, UX, etc. As an engineer with no experience on those areas the idea can sound daunting, but as anything that put us out of our comfort zone, there are a lot of learnings. These are some of them: 
# What I built  
Clip playground is a simple interface that allows you to test [OpenAI's machine learning model CLIP](https://openai.com/blog/clip/) from the comfort of your browser. The motivation behind it was that there is a lot of potential using CLIP in a lot of products out of the box, no training required. It is the closest in the computer vision field to GPT3. However, people turning these technologies into products are usually not the ones comfortable with tweaking some Pytorch scripts and huge models. That's why I felt that giving the people a simple, ready-to-use UI could help developing new products based on CLIP.    

<figure>
  <img src="{{site.url}}/assets/images/posts/Lessons-promoting-side-project/clipplayground_screenshot.png" alt="clipplayground_screenshot"/>
  <figcaption>A screenshot from a prediction in <a href="https://www.clipplayground.co">CLIP Playground</a></figcaption>
</figure>


With this goal in mind, I spent ~1 hour per day developing the product and after a couple of weeks, I had something to show the world! (Read more about how I built it [here](https://twitter.com/JavierFnts/status/1363522529072214019?s=20)).  But building it was the part I was comfortable with. How about promoting it? 
# Where to promote a side project
The product is ready, now, where are the people that can be interested? I used these channels, with diverse levels of success:
#### Twitter
I have a small following, so I was not expecting a huge reach. Still, this tweet got ~2k impressions and ~400 engagements. Not bad. 

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">CLIP Playground is live! 🎉 <br><br>CLIP Playground is an interface for <a href="https://twitter.com/OpenAI?ref_src=twsrc%5Etfw">@OpenAI</a>&#39;s CLIP that allows anyone to quickly play with it from their browser.<br><br>Go try it out at <a href="https://t.co/VuEZIqKbK2">https://t.co/VuEZIqKbK2</a>. 👈<br><br>This is how I built it, all in Python. 🧵👇 <a href="https://t.co/Ib82qidyKK">pic.twitter.com/Ib82qidyKK</a></p>&mdash; Javier Fuentes Alonso (@JavierFnts) <a href="https://twitter.com/JavierFnts/status/1363522529072214019?ref_src=twsrc%5Etfw">February 21, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

#### Reddit
I tried posting in *r/MachineLearning* but even though I am sort of active in that community, my post triggered a moderation alert. This caused the post not to show up for other users until 10 hours later, when a moderator accepted my submission manually. I still do not understand why this was the case, but it hurt the attention due to how the Reddit algorithm works. It still got [~13 votes](https://www.reddit.com/r/MachineLearning/comments/lp1ocb/p_play_with_openais_clip_model_from_your_browser/). 
I tried to also crosspost to *r/ComputerVision* and *r/learnMachineLearning* but it didn't work out there either. 
#### Hacker News
I posted in Show HN, but it never really picked up. I got [7 upvotes](https://news.ycombinator.com/item?id=26226078)
#### Product Hunt
I submitted on a Monday at 9.01 am, and a few minutes later I got to the front page. It even reached the top 5 for some time! It stayed on the front page for most of the day, which brought quite a lot of organic votes. It reached [74 votes](https://www.producthunt.com/posts/clip-playground), which was more than some full-fledged products during that day!  
Probably the platform I got the most success. It was also the platform I spent the most time preparing so it was expected. 
#### Streamlit forums
Streamlit is the tool I used to create the product, so I was hoping I would get some interest from there, but it didn't attract [any attention](https://discuss.streamlit.io/t/clip-playground-an-app-to-try-openais-clip-model/10126). 
### Resources I found useful
- [Screely](https://www.screely.com/): A really simple and easy way to make the screenshots of your product look good. I used it for the product hunt launch.  
- [CodeImg](https://codeimg.io/): Same idea as screely but for code. I used it for the [Twitter thread](https://twitter.com/JavierFnts/status/1363522529072214019?s=20) where I explained how I built it. 
- Diagram of product hunt launch: A great overview with all the rules of thumb when launching in Product Hunt
  <figure>
    <img src="{{site.url}}/assets/images/posts/Lessons-promoting-side-project/ph_mindmap.jpeg" alt="product hunt diagram"/>
    <figcaption>Source  <a href="https://twitter.com/lexpaval/status/1362685073326297088?s=19">Tweet</a></figcaption>
  </figure>
- [Photopea](https://www.photopea.com/): Free simpler version of photoshop in your browser. I used it to create a simple logo and to add text to the screenshots from screely. 
- [copy.ai](https://www.copy.ai/): GPT-3 powered copywriting. It helps to brainstorm different ways you can communicate your product. I used it to get ideas for the product hunt description.

### What I will do differently next time
- **Set up analytics**: I thought I could not set up analytics with a Streamlit app but I have recently found [this great package](https://github.com/jrieke/streamlit-analytics) that allows you to do so. Seeing from which posts were people coming to the app and how people are using the application would have been really valuable. 
- **Submit to product hunt ahead of time**: Instead of clicking the submit button at 9:01 am, it is better to schedule the post in advance. The reason is that Product Hunt moderators need to accept your product before it can go to the front page. They will also modify the description of your product so that it fits well with their audience. If you do this ahead of time you can go to the front page as soon as you hit the number of upvotes, and both parties can agree on a description beforehand. 
- **Talk with a moderator at Reddit about the post**: The fact that it took hours until it was visible for other users completely killed any possibility to get to the top of the front page. I would try to be sure that your post will be accepted straight away, somehow. 
- **Post to indie hackers**: It seems like a great community full of supportive people. I have recently found it and I am sure you can get nice feedback from there.  
- **Ping friends for support in other platforms**: focusing on Product Hunt was great for the initial kick, but I think I could have reached quite a lot of people in the other platforms too if I would have counted with some initial support. 
 
In conclusion, it was a great experience showing something to the world. By working on all the sides of a product one learns about fields that are not so familiar, which can be challenging but also rewarding.

I enjoyed the process, so remember to [follow me on Twitter](https://twitter.com/JavierFnts)  to get updates for future projects! 