---
layout: page
title: Design Manifesto
---


In order to design things well, you need to keep in mind many different things. The tool or application that you are designing may be used in many different contexts by many different people, and those people all need to know what the tool or program can do, how to get it to do those various things, and they need to be able to do this without anyone around to teach them. This task seems almost impossible when described in this fashion, but by following a few guiding principles, anyone can make a usable design. However, before we talk about the process of designing, there are two things that every designer must constantly keep in their mind, the ethics of design and our duty to make our designs accessible.

## Ethics

It is very easy to view the process of designing as an abstract process separate from the design’s real world usage and effects. However, the fact of the matter is that when we design these tools, they will be used by real people to solve real problems, and we need to be aware of this fact to avoid ethical issues. This is true in general for the wider practice of software engineering. Many programmers see their code as abstract programs, but just because they might never see their code used in the real world does not excuse them from thinking of that real world use. One popular example of an ethical violation by software engineers is the Therac-25 case. The Therac-25 was a new model of a medical linear accelerator to be used to treat cancer. In older models, the hardware had safeties that ensured that patients were not overdosed. However with Therac-25 came a new system where the software handled much of safety monitoring. The issue with this was that the system was not tested enough and even though hospitals were told that it was “virtually impossible” to overdose a patient, many patients were overdosed and a few died. Had the software engineers thought through how their product would be used in the real world, they might have realized that a simple bug could end up with someone dead. Failing to adequately test a device to be used in hospitals on people is an ethical violation made possible by the fact that these programmers did not think of the implications of their software. To avoid this, all software engineers and designers should think through as many potential uses of their device as well as how things could go wrong. If there is a scenario where someone ends up hurt, psychologically, emotionally, or physically, then no matter how unlikely the scenario, the team behind the device should consider that a grave issue and fix it.

## Accessibility

When designing a system, it can be easy to forget that not everyone has the same capabilities that you do. Not everyone is able to see, not everyone is able to hear, not everyone is able to understand technical language. Our job as designers is to make our system as accessible as possible. This might simply mean providing appropriate alt-text for your images for blind users that use screen readers. This might also mean choosing colors that are easy to tell apart if you’re color blind. This could also mean providing your website in various languages. Whatever you are able to do to make your product accessible, you have a duty to do so. I encountered an issue with this when trying to figure out how to make a produce selection guide that would work for the visually impaired. For many produce, including tomatoes, color is the main identifier used to determine ripeness. At first I thought that since blind people could not see color whatsoever, that designing an accessible system for them would be impossible.

![Tomato Ripeness Guide](/sousshopper/img/HiFi Assets/HiFi Assets/Tomato1.png)

However, just because it may seem impossible to create an accessible system for a certain population does not mean that you should not try to do so. Our final design did not solve this issue, but because it did not solve it, it would not be the design that we would use in the final product. We’ve discussed and brainstormed various ways to fix this issue, from providing various techniques to determine ripeness, to providing a text description of the color in the alt-text so that a blind person could at least be informed when they asked for assistance. The problem is still up for debate, and until we determine an accessible design, our design will not be complete.

Now onto the design process!

## Ask Users What They Think
	
One important thing that we should keep in mind while designing is that we are not designing these products for ourselves. We are not the target demographic, and because of this it is very important to ask users for critiques and suggestions. Often we can learn surprising and useful pieces of information by simply asking our users what they would want in a product. After all, they will be the ones using the product, we are simply developing it. One example of this happened during our first contextual inquiry. We were shadowing a participant as they selected produce at the supermarket. They mentioned to us that they were choosing bananas that were not fully ripe, but that would be fully ripe in a few days because that is when they were going to eat them. This surprised us as none of us were particularly picky with our bananas. This gave us our idea for the ripeness slider which allows users to choose their bananas at whichever ripeness level they would like.

![Banana slider](/sousshopper/img/PaperPrototype/banana_page.jpg)

Had we not asked participants about their produce selecting habits, we most likely would not have come up with this idea. Though we were invested in the idea of an app to help you select produce, we were not as informed about the process as some people. Assuming that you know enough about a topic to create an application without outside advice is foolish. There is always more to learn, and who better to learn from than from the people who would use your app in the first place.

## Rapid Iteration

You will never create the perfect design during your first time. There will always be issues, always things that need to be fixed, and glaring oversights that you can’t believe ever made it into the initial design. What this means is that you should not invest a lot of time into your first design. By creating a low fidelity prototype, you’re able to test your design and find those glaring issues while still having time to fix them. Your first design won’t be perfect, but it won’t be useless either. By continuously making small fixes, and then testing your design to find what to fix next, you can get closer and closer to the perfect design. This is called rapid iteration, where you quickly make your first design and quickly fix issues without worrying about aesthetics and focusing on functionality. When we made our first design, we forgot to add back buttons to any page. This was a quick, easy fix that we found instantly once we started testing. We simply added in the back buttons and continued to test.

![back button](/sousshopper/img/BackButton2.jpg)

Had we committed to our initial design and created a working application at the start, we would have missed an essential component which we would have needed to add in after the fact. This would have created a lot more work. Instead, we found the issue during our paper prototype phase and the fix was done in 10 seconds by a pencil. Iterative design is easy, but it's also easy to miss the value in iterative design and skip it all together. That will only lead to many headaches and long nights.

## Don’t forget to make it pretty

Finally, after you’ve considered the ethical implications of your product, determined how to make it accessible to as many people as possible, asked your users for advice on what features to add, and you’ve gone through the process of iterative design to create a usable and functional design, do not forget this next crucial step. Don’t forget to make your design pretty. You can create a design that fits all the needs that we have outline already, but if people are put off by the visuals and the aesthetic of your design, they will not want to use your product. An interface is not only a users control panel to access all the functions of your product, it is also what the user will be staring at throughout the experience. During one phase of our usability tests, users consistently commented on how cluttered and confusing the main page was. They were overwhelmed and thought that it was an appealing entrance into the app. To fix this, we added a photo in the form of a featured banner on the main page, and changed the pantry designs to be more simplistic.

![feature](/sousshopper/img/HiFi Assets/HiFi Assets/Page1.png)

Though this seems like a simple change, it radically changed how users perceived our application. At the end of the day, aesthetics are not something to forget. An imperfect pretty design will win out on an ugly practical design. For proof, just look at some of Apple’s recent decisions like putting the charging port on the bottom of their computer mice. It may not make much practical sense, but boy is it pretty.

