---
title:  "How To: Create GitHub Page"
categories: githubpage howto
---
Go to GitHub  
https://github.com

Create a new repository by pressing the green "New" button on the top left of the screen
![image tooltip here](/Img/GitHub_New_Button.PNG)

This will create a new repository named username.github.io where username will be your GitHub name or GitHub organization name.

<b>Note:-</b> If the first part of the repository doesn’t exactly match your username,
it won’t work, so make sure to get it does.

![image tooltip here](/Img/GitHub_New_Repository-Before.PNG)

Enter
- 1 New Repository name
- 2 Enter a Description (optional)
- 3 Tick the 'Initialize this repository with a README'
- 4 Press 'Create repository'

![image tooltip here](/Img/GitHub_New_Repository-After.PNG)

Once you pressed 'Create a repository' it will take you to created GitHub page.

![image tooltip here](/Img/GitHub_New_Repository.PNG)

Next Go to GitHub so you can see all your repositories <br>
https://github.com <br>

![image tooltip here](/Img/GitHub_Repository-List.PNG)

Select created repository.

![image tooltip here](/Img/GitHub_Repository-Select_From_List.PNG)
This is your repository home page. Select your created repository.

![image tooltip here](/Img/GitHub_New_Repository.PNG)

Now we need to clone the Repository <br>

Copy the link of repository to clone by pressing 'Clone'
Right click and copy the link.

![image tooltip here](/Img/GitHub_Repository-Press_Clone.PNG)

Open GitBash. Clone your repository. It'll create a folder with your repository
name.

{% highlight git %}
git clone https://github.com/SergioInsuasti/Test.git
{% endhighlight %}

Create a html file.

{% highlight git %}
git add -all
{% endhighlight %}

{% highlight git %}
git commit -m 'Commit first time'
{% endhighlight %}

{% highlight git %}
git push
{% endhighlight %}

You have your own site Created.
