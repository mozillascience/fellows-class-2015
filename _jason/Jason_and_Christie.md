# Christie & Jason #

## SEGMENT 1: THE LADY BEETLE, DEFENDER OF CROPS ##

*Jason: 		So, Christie. You work with bugs, right?*

Christie: 	Yes. I work with insects. Actually, truly bugs too. There's a group within the insects called the True Bugs. Those are the aphids, cicadas, stinkbugs, that sort of thing. I work a lot with aphids and the things that eat them- mostly lady beetle-aphid systems. I'm interested in understanding how lady beetle communities can suppress aphids in agriculture. How we can do things to the agricultural system in order to get the most out of that interaction.

*Jason: 	So like you're looking to tap the skills of the lady beetle to get rid of the aphids?*

Christie: 	Yeah. Natural enemies like lady beetles are a really important part of every agricultural system, and we don't actually know how much they're contributing to every system, because when they're doing their job, you don't have pest problems.  And they're really sensitive to things like the environment, the landscapes that they're living in. So you can use manipulations of the landscape and the environment to understand how these interactions are going to play out over time. 

*Jason: 	And so, which part of this agricultural ecology puzzle is really your domain? Are you a data scientist? *

Christie: 	I am the quantitative ecologist on this team. So one of the problems that I've been working on for the last few years now is looking at the lady beetle community at the research station in southwestern Michigan- the [Kellogg Biological Station](http://lter.kbs.msu.edu/). They've been monitoring lady beetle populations since 1989 there, and we’ve got data for all the different species that are interacting over time. During this monitoring period, we've captured several invasions of different lady beetle species, as well as the arrival of new pests. And so one of the things that I've been working on is looking at how communities responding to these invasions and looking at does it affect the service that they provide. So can they eat the same number of aphids? Can they respond to the same amount of pest pressure with these new species in the mix? And also what is that doing to our native species, because there's conservation concerns associated with keeping the native species around as well.

*Jason: 	Oh, so there are actually local lady beetle species and then invasive lady beetle species?*

Christie: 	Yeah. So we've got about 13 that we catch regularly at the site. But in North America, we've got about 250 different species. The one that's most notorious in the Midwest right now is an Asian species, the multicolored lady Asian beetle. It's from northeastern China, originally, and it was introduced...well, many times over the course of modern history as biologically controlled for aphids.

*Jason: 	So you have all this data collected starting from 1989. Most of your work, then, a sort of retrospective analysis of this data and looking at it and slicing and dicing it in different ways?*

Christie: 	Mm-hm. And our new work will be asking some climate change questions. How the climate is affecting and extreme weather events are affecting lady beetle communities. 


## SEGMENT 2: MATH ROCKS ##

*Jason: 	Have you always been into insects? Or like what was your on-ramp into this looking at this system of lady beetles and aphids?*

Christie: 	I'd say that was entirely an accident. I knew that I wanted to be a scientist when I grew up, and I liked math, and so I chose a physics major, specifically when I came to university. And that was not the greatest choice for me. I just found that I didn't feel a click. I think it was after my...it was after my sophomore year, that I started applying for jobs around campus just to see what would stick. And an entomology lab got back to me. And they brought me in to rear flies, specifically, for an invasive fly that is a pest of Asian vegetables on a muck farm north of Toronto. And I just loved it.

After I’d been working in the lab for a while,  I was offered an undergrad thesis project working with them, and that turned out really well. And then there happened to be a master's project in the next lab over that involved lady beetles. And so I said, well, that sounds interesting and I jumped in there. And the rest is sort of history.

*Jason: 		Have you always been interested in math?*

Christie: 	Yes. That's been a big thing for me probably since I was quite young. I always get very, very excited when I get to use calculus.One of my very favorite things to do is when someone needs to propagate errors. I say, ooh, let me use the general error propagation formula and take partial derivatives.

*Jason: 		Awesome.*

## SEGMENT 3: #OTHERPEOPLESDATA ##

*Jason: 		I don't know if you coined the term, but you've certainly popularized this concept of other people's data. Do you remember your first batch of [#otherpeoplesdata](http://https://twitter.com/search?f=tweets&vertical=default&q=%23otherpeoplesdata)?*

Christie: 	Well, I've had a lot of different encounters with other people's data. But being a person who worked more with the stats, who was more enthusiastic about the stats than the typical biologist, I was often the person who was asked for help with analysis. It just ended up being one of my things. People said, hey, I've got this data. Can you take a look at it? It turned into a really productive niche for me. The post doc that I'm currently in was looking at this retrospective data set that I talked about earlier. 
But another project that I was on--this is where other people's data hashtag came about. The whole hash tag and the documentation of my frustration. This was a huge data set that was collected by a colleague of mine's. Beautiful, amazing documentation of the abundance of several hundred different organisms over a 12-year period. But part of the problem was that these ended up being huge species lists that were entered by students in the lab, and the students in the lab, they adapted the spreadsheet from the previous year every year. I think they ended up giving 50 files at the outset. And so all of these errors crept in, making it impossible to combine in any automated way. I wanted to put this together in a usable form, and it was just not set up in a way that you could do that.

*Jason: 		Yeah.*

Christie: 	I started to see these really common errors. And, you know, part of it was...part of these sheets were beautifully formatted. They were very, very neat. But they were focusing on the wrong things. You know, borders to indicate where this data ends and where the next step begins rather than providing information within the spreadsheet about how to do it. One of the classic examples was when there was a sample missing, they wrote 'no sample' down the column one letter per cell. 

*Jason: 		Right.*

Christie: 	And so when I had done an automated process to bring the data together. And so I went and everything worked and I sorted it, and for some reason there was an 'O' in one of the cells. I went, huh. That's weird.

*Jason: 		That must be a zero.*

Christie: 	Then I found another one, and I sorted it, and I go the letters for no sample, but of course in alphabetical order.

*Jason: 	There's like a code book somewhere and the letter S actually means some event happened, right? Yeah.*

Christie: 	Exactly. And so it involved such detective work to figure out what had happened there.


## SEGMENT 4: LOST IN TRANSLATION: ENVIRONMENTAL BIOLOGY W/O EVIDENCE ##

*Jason: 		How does open science sort of make your life easier or harder in this domain of working with other people's data and trying to make meaning out of it?*

Christie: 	Well, I first came to the idea of open science because people were willing to share these data with me. I thought, well, this has been a really good thing. We're really effectively doing what we're good at. We have people that are really good at collecting and identifying insects. And then we have people like me who are interested in managing the data and doing the analysis. And so it just makes sense that we'd work together. But we really need to find a common language so that we can connect up. 
And so that's why I came to reproducibility and creating a common language for data management and open science for that path. But also there were just some more external factors that really nailed me in the head. My colleagues and I are typically working with insects in human systems. And so there's human health and environmental health outcomes associated with pretty much everything we do. And livelihood of farmers--that sort of thing. All these things into play in our research. But we don't necessarily get this academic stuff that we're doing out to the people that need it. So, for example...

*Jason: 	By that, do you sort of mean, like, writing papers for papers' sake? Or there's a translational gap?*

Christie: 	Yeah. So you end up having sort of the...the scientific paper as the end product. That's how we're ranked within academia. That's the currency that we have. But it just doesn't seem like the most efficient way if we're just saying this is the end product. It doesn’t put any aspect of the scientific process in the hands of people who are making the decisions that matter.   

For example, I worked with a student whose project involved the restoration of oak savannahs, which was dominant land use in southwestern Michigan before European settlement. When he finished his master's, he got a job with a local NGO as a conservation biologist, that does a lot of on-the-ground conservation activities in the area he studied.  And through his work there, he doesn't have access to the papers he wrote here at the university.

*Jason: 		Uh-oh. *

Christie: 	And so here we have a student that we have trained in evidence-based practice. He wants to do the best he can in actually restoring these habitats.

*Jason: 		He can't get the evidence.*

Christie: 	He doesn't have access to the science.

*Jason: 		Yeah. That seems like a problem.*

Christie: 	Yeah. And so it just seems like this really fundamental disconnect. We're training practitioners and then taking away their resources by not being open in academia. 

## SEGMENT 5: NEW BEGINNINGS ##

*Jason: 	What opportunities do you see to get more scientists to adopt open science practices like data access, knowledge sharing, and open tools?*

Christie: 	Well, my plan is to get them while they're young. So the idea is I'm currently developing an open science and reproducible research course. And so the idea is to mix these technical skills with the philosophy and the ethical concerns  that come with the technical skills. So you have essentially learning R, and then you have learning how to share your code and learning how to share it in a reproducible way. Learning how to use other people's code. Learning how to cite it properly--that sort of thing. So layering all of those things into the skills development so that the ethical use of these techniques come with the learning of the skills.

*Jason: 		And what's it called?*

Christie: 	[Open science and reproducible research](https://github.com/cbahlai/OSRR_course). 

Jason: 		Well, Christie, thanks so much for the interview. Where can we find you online to learn more?
 
Christie: 	Well, you can find me on Twitter [@cbahlai](https://twitter.com/cbahlai), C-B-A-H-L-A-I. And you can also find me on github, same name. It's really convenient having a unique seven-letter identifier. 
