---
layout: post
title:  "Semicolons 2020 Runners up Experience"
date:   2020-12-09 19:03:28 +0530
categories: Semicolons, Hackathon
---
<!-- You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. After that, include the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/ -->

## Hello there! Welcome back to my Blog!
![Hello There Gif](https://media1.tenor.com/images/b93a212c42e0630c534d90c386b221f3/tenor.gif?itemid=16358959)

This blog post is a documentation of my experience of participating in the Semicolons 2020 held in December 2020 and the journey of becoming Runners up.
<!-- <img src="https://www.persistent.com/wp-content/uploads/2020/12/Blog-semicolons-celebrating-innovation-with-a-global-hackathon-scaled.jpg" height="" width="1125px"> -->

# #IntrotoSemicolons 
During the 4 years of my BTech degree, I have participated in a few Hackathons, but Semicolons was undoubtedly been the best by a mile. Semicolons is the annual global Hackathon hosted by Persistent Systems wherein employees work on a problem statement and come up with an innovative solution that is better than the rest. It is a cutthroat contest of wits and hard work to deliver the best solution possible. This year was a bit different than the previous ones. Usually, the Hackathon spans over 2 days with nonstop work but due to the pandemic, it was stretched to 3 weeks which made the competition tougher and interesting.

# #Team 
I consider myself super lucky to have been part of team Solidarity. I joined Persistent Systems in October and am still under the training process, but that didn’t stop me from wanting to grab this opportunity. I hit the fortune when I was accepted as a team member for team Solidarity, a team lead by veterans of Semicolons like Amogh Tarcar and Sagar Revankar. They have been the top contenders for the past several years. With them leading from the front with example, nothing looked impossible. Our aim was to build a Privacy-Preserving Platform or at least the minimum viable product for the platform which would provide services to quantify the security of ML models, apply methods like Differential Privacy and Federated Learning to mitigate the vulnerability of the model.

# #MyTask
I have worked on a couple of machine learning and AI projects so I was somewhat confident of contributing to the project. Credit to our team owners who had the project completely planned out and had a clear map of all the tasks that needed to be done. My first task was to convert an ML model built using PyTorch to a Keras model. Our privacy analysis service used privacy meter for quantifying the privacy of any ML model and required a Keras model input. I worked on this task for a couple of days and got some success initially but then came the first setback. The output of this didn’t really satisfy the project requirements and couldn’t really be used. That didn’t stop us from moving forward. We immediately moved on to TensorFlow privacy which satisfied the requirements for privacy meter. I worked on building a model using TensorFlow privacy and was successful in doing so. We then went on to use privacy meter for testing the privacy of this model. The basic idea behind privacy meter is to use another ML model to attack the input model with some data and predict if the data was present in the training set of the input model. We were successful in attacking the model. But there was no time to relax. We needed to analyze the results by fine-tuning the hyperparameters of the privacy meter model. The inner data scientist within me woke up and started hunting for the precise click that was needed to unlock the route to the best model. Till now I have mentioned luck to get into the team, but it requires a whole lot more to have one of your best friends to be on the same team. Having my buddy Penjo, with whom I have studied, worked, and lived with, in the same team had already made communication smooth. Pair programming sorted out the process of analysis and achieving successful results. We managed to tune the attacker model for predicting the most data from the nonprivate model and this attacker model couldn’t perform well for the private model. This meant that the service for making the input models private worked perfectly.

# #IntegrationDay 
I didn’t have much idea about what others had been doing all this while. This was all taken care of by our team leaders who themselves were working round the clock as the deadline approached. On the day of integration, everyone was present and one by one were setting up servers, UI, API s, and integrating them. I have never worked on a professional project before and watching this process before even being assigned to a company project really made my day, (more like night, it went on till 3 am). There was one task at hand at a time and everyone focussed on it. All the components were perfectly finished, especially the UI which was truly professional, sophisticated, and elegant, all thanks to Sagar. It wasn’t over yet, the complexity of the project not only makes it tougher to work on but also makes it tough to present it within the time limit specified by the organizers. The time limit for the first round was 12 minutes(9 for presentation+demo, 3 for Q&A). In order to set the context of the project, we made a small animated video which turned out to be a great idea. But fitting all the presentation and the demo in 9 minutes was a mountain to climb, but it was easily scaled by our presenter Amogh Tarcar, who was spot on with time, content as well as the q&a. All in all, it was magnificent.

# #Winning2ndPlace
The experience of participating in this event helped me grow a lot as a developer. I had not even seen the first round presentations of other teams therefore had no clue how good ours was. But everyone has some hope of winning at least something, especially when everything goes well and so I too had hope. During the final round, I saw the presentations of the rest of the top 6 teams and they too were pretty impressive especially the one from team Chasqui who ended up winning first place. The cool thing about hackathons is that the results are announced immediately after the final round. As the final round ended, I called Penjo and we started discussing about presentations from other teams. All of a sudden I saw a message in the Solidarity group saying "aaah!!! runner-up". I was super pumped, punched the air, and congratulated everyone. We were the second-best in PSL. This was the best possible end that I could have ever imagined for 2020 to have and the best start for my professional career. A huge Thanks to all my teammates [**Amogh Tarcar**](https://www.linkedin.com/in/amogh-kamat-tarcar-a6367b1b/), [**Sagar Revankar**](https://www.linkedin.com/in/sagar-revankar-88020a14/), [**Sadashiv Borkar**](https://www.linkedin.com/in/sadashivb/), [**Rajas Kakodkar**](https://www.linkedin.com/in/rajaskakodkar/), 
[**Pranav Silimkhan**](https://www.linkedin.com/in/pranav-silimkhan/), and [**Penjo Rebelo**](https://www.linkedin.com/in/penjo-rebelo-2b4412179/). That's it for this Semicolons and until next blog,

![Bye](https://media2.giphy.com/media/kaBU6pgv0OsPHz2yxy/giphy.gif)
