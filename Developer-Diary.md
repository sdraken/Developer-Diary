## Format 
The Developer Diary will be contained within this singular markdown file. I might change this as the number of projects increase, but right now I'll keep it simple. 

Each entry starts with a header specifying the date. The diary is sorted in descending order with respect to dates. That is to say, new entries are placed at the top. 

There aren't going to be daily updates (Maybe "Developer Logbook" would have been a more descriptive name) but substantial changes in any of my projects should be reflected in the diary.
## 2024/09/23
I've completed the "Drawing a triangle" chapter, but I don't think I'll be redoing the code in my own style. After thinking some more, it doesn't seem smart to refactor and come up with a structure when I don't even understand all the basics of Vulkan. I want to start writing my own code, but I shouldn't let that get in the way of me learning effectively. I'll be continuing the tutorial like normal, next up is chapter 3 about vertex buffers.

## 2024/09/21
I'm finally able to draw a simple triangle, it's amazing how more than half of the tutorial is spent on getting to that stage. It just goes to show how explicitly you have to tune everything in Vulkan, rendering a model isn't too much additional work once everything has been set up. Once I've completed the "Drawing a triangle" chapter I'll be redoing the code in my own style, to test myself on what I've learned.

After thinking about it some more, I don't think I'll be doing the [second tutorial](https://vkguide.dev). I'll finish [this tutorial](https://vulkan-tutorial.com/) in its entirety, but after that I feel like I'll have a good enough foundation to start on my own project.
## 2024/09/16
I've been making steady progress. shifting my focus to understanding Vulkan's concepts was definitely the right call, even though it's making the tutorial take a lot longer. Any time I feel like I don't fully grasp a concept, I do a lot of extra reading on the topic.

I'm considering not doing the [second tutorial](https://vkguide.dev). I feel prepared to start building the foundations of my project thanks to all the extra reading I've done. What I'll probably do is read through the second tutorial while starting my own project, making sure I don't miss anything crucial. I've heard good things about the second tutorial, so I feel intrigued to read it.
## 2024/09/11
I've been reading a lot about Vulkan and C++. When going through the tutorial I often find myself wanting to reconfigure the author's code, but I shouldn't focus on trying to optimize the performance/readability of the tutorial. What's important is that I understand the concepts that the tutorial is introducing. Because of this I've put a greater focus on writing notes as I go through the tutorial, describing new concepts and how I can use them. 
## 2024/09/09
I have more concrete goals for what guides I want to complete. First I'll go through [this](https://vulkan-tutorial.com/) vulkan tutorial written by Alexander Overvoorde, any code related to that will be in [this](https://github.com/sdraken/vulkan-tutorial) repo. After that I'll go through [this](https://vkguide.dev) tutorial (couldn't find author's name), storing everything related to it [here](https://github.com/sdraken/vkguide). From what I've heard these 2 tutorials are exactly what i need and I feel like I'll be ready to start making my own 3D application after I'm done with them. I would've uploaded some progress on the first guide today/yesterday, but I haven't had access to a computer for a bit so I've only been able to read the guide/documentation. 
## 2024/09/07
I setup [VulkanTutorials](https://github.com/sdraken/vulkan-tutorial), it was honestly a lot harder than I thought. Well... it was easy to setup but I didn't like using visual studio, so i had to learn cmake which made it take a lot longer.
## 2024/09/06
Went through the contents of [Distributed-Version-Control-101](https://github.com/sdraken/Distributed-Version-Control-101/) one last time. Adding references and improving on the grammar. I Might revisit the project at a later date, but right now I'm satisfied. For my next project I will be working with 3D graphics using the Vulkan API. As a start I'll go through [this](https://vulkan-tutorial.com/) vulkan tutorial written by Alexander Overvoorde. My code for any vulkan tutorials will be in [this](https://github.com/sdraken/vulkan-tutorial) repo.
## 2024/09/03
The [Distributed-Version-Control-101](https://github.com/sdraken/Distributed-Version-Control-101/) project is completed. I've covered what I want to cover and the only thing that remains is the finishing touches. I still need to add a few references and check for bad spelling/Grammar.
## 2024/09/01
[Distributed-Version-Control-101](https://github.com/sdraken/Distributed-Version-Control-101) is close to complete. I'm decently satisfied with the topics that are covered, and i think I've explained the concepts in an understandable way. I still have to polish the text somewhat, and look out for anything that I might be wrong about. When it comes to Git, I feel like people use explanations that are intuitive but not descriptive of the underlying process. I've been trying to avoid falling into this trap, but I'm prepared for the possibility that parts of [Distributed-Version-Control-101](https://github.com/sdraken/Distributed-Version-Control-101) might not be correct.
## 2024/08/28
Been making steady progress with [Distributed-Version-Control-101](https://github.com/sdraken/Distributed-Version-Control-101), although I might've gone outside the projects original scope a bit. There is less of a focus on Git/GitHub and I've read a lot about the general foundation behind version control. But I feel like I'm learning a lot and that I have a better grasp of how to use Git/GitHub, so I'm not gonna be to strict on myself. 

I would estimate that the project is more than 50% complete. I still need to go over relevant git commands and specify my standard, but I suspect this is doing to be easier. I had to read a lot to understand how version control systems work, but I already know that my standard will be designed with the [feature branch workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow) as an outline.

When I research i usually jump between different sources to help fill in the gaps. I like this strategy but I'm not good at keeping track of my references, I need to dedicate some time to going back and looking at what references I've used. 
## 2024/08/25
The first project has been decided upon, [Distributed-Version-Control-101](https://github.com/sdraken/Distributed-Version-Control-101). Since I'll be using Git to manage all of my projects, it only seemed natural to go over distributed version control before anything else. The idea is to give an overview of what I know, and to develop a standard workflow for Git/GitHub that I'll be using throughout my other projects

I'm still changing the formatting of this repo, and I suspect it'll take a while until I find a look I'm completely satisfied with. The Developer-Diary repo might be replaced with a webpage once I start looking at getting my own website up and running, but that remains to be seen.

I know that for software development I'll be trying to avoid having unrelated changes appear in the same commit. I'll be lenient on repositories that are mostly text because their main challenge is the actual writing, keeping track of changes isn't as important.