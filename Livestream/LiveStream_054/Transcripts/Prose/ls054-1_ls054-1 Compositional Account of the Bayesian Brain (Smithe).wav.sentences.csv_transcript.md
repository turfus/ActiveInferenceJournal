
00:01 _Daniel:_
Hello and welcome.
It's June 7, 2023.
We're in ActInf Livestream 54.1, discussing “Mathematical Foundations for a Compositional Account of the Bayesian Brain.”
So, welcome to the Active Inference Institute.
We're a participatory online institute that is communicating, learning and practicing applied active inference.
This is a recorded and an archived Livestream, so please provide feedback so we can improve our work.
All backgrounds and perspectives are welcome and we'll be following video etiquette for live streams.
To learn more about live streams and other projects, head over to activimference.org.
And we're here today in active stream 54.1.
We are in our first discussion with the author of the work, “Mathematical Foundations for a Compositional Account of the Bayesian Brain.”
Today in 54.1
we're going to say hello, then be on with it and see where it all goes together.
So we'll begin with introductions.
I'm Daniel, I'm a researcher in California.
Six months ago, I was quite unfamiliar with category theory and have had quite a fun journey with Ali and Dean and I guess Toby via stigmergic proxy.
So, really looking forward to this discussion.
And I'll pass to Dean
and then Ali.

01:35 _Dean:_
Thanks, Dan.
I'm Dean.
I'm here in Calgary.
My goal in joining this group was to take the idea, as we caught in one of the previous slides, the idea of practicing applied active inference.
I see the potential through category theory of making that even more accessible, more possible.
And so I'm really excited to have the author with us today and maybe have a look at what that means and I'll pass it over to Ali.

02:10 _Ali:_
Hello, I'm Ali, I'm an independent researcher, premiere one, and as I said, in zero.
I'm quite excited to be here to discuss this magnificent dissertation with its author in the past several months.
We did our best to understand and dissect it as best as we could, but obviously we have many, many questions that I'm looking forward to discuss them with.

02:53 _Daniel:_
So, Toby, thanks again for joining.
Please lead us off with just any introduction and background that's going to set the stage, maybe how the work came to be and that would be great.
So thanks again for joining.

03:09 _Toby:_
Yes, great.
Well, thanks Dan and all of you guys for hosting me and for having the courage to read my thesis, which, as you noticed, it's a kind of strange mix of things.
It's kind of both the research work and, as I noticed one of you saying in the previous stream, it's at this kind of frontier of knowledge and of course it needs to be.
But I also, because this language is so kind of unfamiliar to people and because I think it will prove to be very useful across the sciences, I really wanted to make it kind of legible to people.
So for people to read the thesis, but also, like my research and kind of understand what I was saying effectively how it came about was I was supposed to be studying interactions between frontal cortex and hippocampal circuits in the brain.
And at the sort of time of trying to get started with that, obviously I was kind of interested in the free energy principle and active inference and all of that.
But I found that there was a lot of as I said in the thesis and as you talked about in the previous stream and probably in discussions before that as well, there's a lot of kind of each research
group has its own language.
And these different groups, they don't necessarily talk to each other in a way that is kind of an efficient kind of communication.
Each group of people is interested in their own thing.
And one of the things I like about the free energy principle and about active inference is that it's this nice sort of general framework for adaptive systems.
And so it is in itself a good place to kind of situate an understanding of systems like the brain and other adaptive systems.
But of course it doesn't immediately resolve this problem of the problem that was for me a kind of confusion about what's going on in these circuits and how should I understand what one person says in relationship to what another person says about this bit of the brain or this interaction.
And so in the process of kind of trying to understand what was going on there and to resolve, in part, the confusion I had about predictive coding itself and the complexities of all of these models I was encountering, I kind of resolved to replace that confusion with another kind of confusion, which is, what is all this crazy category theory stuff?
And so you might think, okay, well, that's mad.
What's the point of that?
You've just made everybody's life a lot harder.
It's kind of like that xkcd comic [https://imgs.xkcd.com/comics/standards.png] where you've got all of these different standards; and will you decide to come together and make a new standard?
And in fact this is happening, I think, in like, I don't know what it was in cellular biology, maybe.
I heard John Baez talking about this yesterday, that they have lots of different standards for writing down diagrams, for describing interacting like biological processes and the kind of scientific community in that area has set up a kind of mediating body to kind of try to bring together all of these diagram languages but they weren't really able to do so.
So they still they instead of just coming up with one new standard, they came up with three new standards to try to unify these things.
And the trouble I had or have with these different languages or different sort of syntaxes for talking about scientific things is that not only are they all different, but they're kind of all ad hoc.
And so the reason why I feel that there's promise in replacing this confusion of so many different ideas I mean, of course it's great to have this kind of ecosystem of ideas about how these complicated systems work, but it's still very ad hoc and confusing.
And so instead of just coming up with a new ad hoc and confusing way of understanding these things, I was kind of hoping to use a language which is maybe kind of universal in some sense or it's really capturing how we think and maybe also how the world is actually built up.
But in particular it seems to capture something of how we think.
And so the fundamental theorem of category theory says that you shall know a concept by the company it keeps to adapt that sort of motto of, I think, birth from linguistics, that you should know a word by the company it keeps that's really like at the heart of how we come to understand things in the world.
And I think the math that is category theory captures that very nicely and very precisely and at the same time enforces the kind of discipline.
And so I know it is quite like hard going reading this kind of research work, this kind of introduction to all this new stuff, but in part that's because being disciplined is hard and doing things very formally, precisely does require a bit of, well, a lot of dedication.
But that isn't to say that it's not worth it or that these ideas even used a bit informally somewhere down the line might not be useful at least to sort of frame the way we think about things.
So I hope to be some use in helping not only sort of change the confusions that we have, but also modulate them in a kind of way that will be sort of useful for people.

08:57 _Daniel:_
Awesome.
Great starting place.
Ali or Dean, where can we begin?
How can we replace some of our prior confusions with a new and different confusion?
Ali, want to go first or can.

09:18 _Dean:_
I ask a quick question to Toby?
Toby, when you were talking about when you actually saw all of these standards, so now you were the sort of what, you were the hub of all of these standards.
You saw sort of all around you.
Can you maybe speak to the idea of what you perceived or what you sensed was the stabilizing function of those standards but also the searching function because of course you had gone out and realized there were all of these different standards at play.
I remember it in a previous professional life of mine having to have chief financial officers and their math sit at the table with engineers and their math and them talking right past one another and making no sense to each other.
And I had to be kind of the medium between them so that their math would actually get a little bit sticky and they'd be actually able to understand and interpret one another.
In your experience with this, how did that play out?
Both the stabilization through the standards and the search.

10:35 _Toby:_
Well, I guess I should begin by saying that this is still, like, ongoing.
And nor am I an expert in all of these different standards.
But the thing that I kind of at least noticed, right, that was that people use languages like Bayesian inference or reinforcement learning or dynamical systems to talk about certain bits of the brain that I was interested in.
And they kind of just plug all these ideas together and it's fine.
So you want to write a paper and it's about a particular phenomenon, and it's great.
You maybe come up with some nice model and you put people in MRI scanners and the quantities in the sort of bold signal correspond to quantities in your model.
And that's great.
It says that maybe this bit of the brain is doing that.
I mean, we can argue about MRI at some other time, but it doesn't really tell you about how that little model you've got interacts with the rest of the brain or the rest of the world.
And so if you care about this whole complicated thing, you want to know, how do these parts actually talk to each other?
And so I was just fortunate at the kind of beginning of this, in some sense, to be in the right place at the right time.
So I kind of knew there were these different ingredients all being put into these different models, and I'm only sort of familiar with some of them, but I could still see that they had sort of similar structure.
And that was in part because I've been going to some applied category theory meetings or talks and seen that, say, economic games, which are very closely related to reinforcement learning, have this kind of bi directional structure where an agent tries to sort of effectively, in some sense, choose.
They make an observation, and they sort of do this kind of forward projecting kind of thing of choosing an action at the same time as saying, okay, well, if supposing I take this action, what would the payoff be?
And that's this kind of backwards facing thing.
And then you can sort of chain that process and think, well, if I do this in multiple stages, like, how does the utility I get at the end of this multi stage process feed back to the utility I'm going to get, having taken just one step right now?
And that's a similar sort of bi directional thing to what happens in Active, or like in well, in predictive coding, specifically, where a little circuit is saying, okay, well, given my high level beliefs about what's causing this sensory data.
I need to sort of retrofit the actual sensory data to kind of come up with a new belief about what those causes are.
And so that seemed to me to have the same kind of structure.
A similar thing also happens in backdrop, in machine learning where you have say some neural network and you feed forward some information through the network and it say does a classification and then you have some training system which says, okay, well, actually, you had this error, and then you need to sort of back propagate that to update, say, some part of the model on the basis of that.
So that also has this kind of bi directional structure.
And it just was fortunate that at this time people were talking a lot about these kind of bi directional processes.
And so I was thinking about these things at the same time I was kind of thinking about the application of Bayesian inference, and I kind of noticed that they had the same structure.
And I kind of wanted to figure out what was going on there, really sort of pin down what it was that made this kind of predictive coding circuit have this kind of shape in some sense.
Because as I think you've also talked about and as I kind of mentioned a few minutes ago, that individual predictive coding circuit isn't an isolated system, right?
It's part of like this hierarchical thing.
And so you have one little circuit connected to another circuit and that whole conglomeration of circuitry is supposed to do something quite grand, but at the same time it's made of smaller parts.
And one of the major confusions I had at the beginning was, okay, so you have this big generative model with lots and lots of factors, and you go through it and you try to derive the differential equations that give you the sort of predictive coding dynamics by saying, okay, well, we're going to minimize the free energy and you have this complicated thing with lots of sums in it and it seems like very intimidating to try to come up with that differential equation, even though, actually, when you sort of look at this, the look at the process that you're doing is quite kind of mechanical because effectively, you're doing the same transformation to each factor of this model.
And so that also hinted that there was this kind of compositionality thing going on in these systems.
Not only do you see that this bit of the brain has this kind of modularity, but you also get a sense of that modularity in that derivation you're doing.
And so what I wanted to do was to capture both of these things.
One is the kind of shape of the circuitry and the other is like how to somehow save the effort of having to kind of rederrive everything for each different case.
And that kind of formalization of this process corresponds to a kind of functoriality you get when effectively this functoriality means you preserve compositional structure.
And so what you want to do is you want to say, okay, well, what's the compositional structure of the thing that the function starts with, like the process starts with, and that's the compositional structure of Bayesian inference itself.
And then you want to say, okay, well, what's the compositional structure of the kind of dynamical systems, which is the thing you're trying to get to, and how do you map from one to the other in a way that preserves that structure?
And so that's kind of what I was doing in this thesis, is just saying, okay, what are the structures I need and how do I relate them?
And it turned out that there were a lot of details, I had to write them all down.
But the kind of basic idea, I hope is quite simple.
It's just trying to say what are those kind of the kind of individual components like the kind of Lego blocks and how do they connect together and how can I sort of relate the kind of Lego blocks of one thing with the Lego blocks of another in a way that kind of preserves the shapes?
And so, yeah, it's kind of mammoth thing, but the kind of fundamental idea is quite simple.
And I think it's kind of like how when if you're like programming a computer, you can write in a high level language or you can write in like low level language.
And if you wanted to, you could write in assembly language.
And category theory is like a language where you start with the kind of assembly language and you build up a high level language within the language itself in some sense.
And so if you really want to start with at the very beginning, like I did with the definition of category, and then build up to this big thing, you have to make a lot of steps because like, assembly language is really simple and it's just like single instructions that your processor does.
And so getting all the way to something like zoom that can do a video call is quite complicated.
And so people don't they start with the high level language, but the thing that people strive for in designing high level languages is to set them up in such a way that the abstractions are quite nice or sort of modular.
And so that's what I'm trying to do with using category theory, is to kind of find abstractions that are modular in a similar kind of way.
And I know on the previous call, Dan, you mentioned the kind of analogy between Piping in this category theoretic sense and in the programming sense, and they're quite similar.
The category theory sense is kind of a much sort of more general, bigger idea.
It sort of encompasses all kinds of things.
But you could imagine somewhere down the line having a programming language and that people are trying to build these things, but having a programming language where you could express anything, you could in category theory and I, to be honest, find it quite intense and quite sometimes mechanical and tedious.
How to prove that certain categorical structure satisfies the coherence conditions that it has to satisfy, like lacks associativity or monoidality or something like this.
There are a lot of diagrams you have to check commute or something, and much of the time that checking is quite tedious.
And someday I hope that we all have tools that we could say, okay, well, I'm going to spell out what my structure is, and the tool will just check that it satisfies all the axioms.
And so I know you guys had to wade through a lot of that stuff in the thesis, but it's kind of manually necessary right now, but in the future it might not be.
And then we can use this high level language in a much more kind of liberal way, I hope.
That would be great.
Sorry, I've been waffling operators.
I'll stop there.

20:21 _Daniel:_
Awesome.
Great.
I'll go to a question.
In the chat Mark wrote, applied category theory and active inference have tremendous promise.
I confess I have not yet read this dissertation.
It would be helpful to describe a specific engineering application for the work.
So what do you see as proximate and and or distal engineering applications here?

20:50 _Toby:_
So one of the things that I hope could be produced soon as an engineering application is a sort of general modeling framework for building kind of complicated active inference systems that might include lots of parts, lots of agents.
Kind of like something that my colleague Jules Hedges once in cybernetics more generally, something like kind of programming language, maybe, that incorporates all of these kind of strange cybernetic structures I mentioned earlier, like reinforcement learning and backprop in machine learning and Bayesian inference, they all have this kind of bi directionality.
And so you should be able to have this kind of modeling environment which allows you to incorporate all of these things in a kind of nice way.
But I think before we get something quite as grand as a whole new sort of modeling environment, I think just having tools to help us build approximate and active inference systems that are really nicely compositional is one thing that I hope to come out of this.
To be honest, I don't know very well what the general tooling is like for this kind of thing right now.
I know that there's SPM, I know that there's, like, pi MDP for certain kinds of problem, but I don't know how general they are.
Another thing that you would get if you have this kind of toolkit, because of the kind of modularity of category theories, you should be able to plug it into other things that exist already.
So one of the things that's particularly of interest to me at the moment is kind of multi agent systems and sort of building trying to understand how we could build something like or simulate things like something like a corporation or some kind of some kind of society structure where you've got lots of active inference agents coming together to pursue a sort of common shared goal.
How can you kind of effectively distribute that goal sharing across systems.
They could be like little robotic systems, say, or something like that, or agent or like I don't know precisely.
I'm kind of like an abstract thinker.
But being able to kind of control or modulate the performance of these kind of distributed multi agent like active inference systems might be quite a cool thing to be able to build.
So that's kind of like maybe flavor of the kind of thing that this tooling gives you.
I suppose for me, this particular work was really about trying to encourage people to use this language to understand things more clearly.
So, yeah, there's a lot of stuff that I hope we can understand, or at least I can understand more clearly.
Sure.

24:22 _Daniel:_
Awesome.
Thank you, Ali.

24:26 _Ali:_
Thank you.
Yes.
So in this paper by Christophe Voitowich, are there category theoretical explanations of physical phenomena?
He argues that category theory by itself does not and cannot provide any mathematical explanations for physical phenomena.
So the idea here is that category theory is merely a meta theory to kind of do a kind of bookkeeping or householding of the physical theories, and it's not a tool to construct the mathematical theory of physical phenomena itself.
I'm not sure I agree with this argument entirely because in one sense, some of the most profound, AHA, moments in the history of science obviously results from looking at preexisting theory or a model from a novel angle.
And I believe category theory can provide such novel perspectives even when looking at some established and preexisting models or theories.
I'm curious to know your opinion about this.
So do you think category theory can actually provide mathematical explanations for either in cognitive science, neuroscience, or even other areas, other scientific disciplines as well?

26:07 _Toby:_
I think it's a subtle question.
Right now, it's probably largely the case that the role of category theory is kind of this I think it's like bookkeeping, but like Clarification too bookkeeping, if you think of it in a sort of very general way of trying to account for the things you're thinking about very precisely and not sort of miss details.
Like if your books don't balance, you kind of miss some payment or some debt.
I think that's quite a nice analogy.
But I think one of the goals of quite a lot of people, or not maybe a fair chunk of the community, particularly that which comes from a sort of more abstract mathematical side of category theory, one of their goals is to try to recast a lot of how we think in kind of purely categorical language.
So one of the things that category theory allows us to do is to kind of formalize in some sense patterns that crop up all over the place using the notion of universal construction.
And the thing about universal constructions is that you have some little pattern.
And if you know that you can instantiate that pattern in your category, that you have some object which kind of captures the essence of that pattern and you don't need to say be able to kind of write down all of the specifics of that object sort of a priori, because the kind of universality gives you a recipe for constructing it.
It gives you it in some sort of unique way.
And so you know that if you have this universality, you can always access this object.
I'm talking very generally, but because of that, one thing that people try to do is to try to say okay, well, we've got these things that we're interested in in, say, physics like the principle of least action or the nature of spacetime or something like that.
Can we express those things as kind of universal constructions or, for instance, in a completely different realm, like we might have some process which is something we're interested in on the computer, like the migration of data in databases.
Can we write that down in a way that doesn't have any kind of ad hoc ingredients?
It only is built from universal constructions.
These are things that we can just write down kind of abstract sort of axioms in the language of category theory and that kind of gives us the process or the structure that we want.
This kind of line of work is often called like synthetic something like synthetic probability theory or synthetic physics or synthetic topology or something like that.
And it means you sort of start from these kinds of very high level categorical ideas and then you sort of end up with a characterization of the essence of the thing you're interested in in physics.
A simple example of this which I supply in a kind of relatively feeble effort to say that it's not true that category theory doesn't give you a characterization of things in physics.
So there is a category of, say, topological spaces and the morphisms between them are continuous functions.
And there's a category rather of sets.
And the morphism between the sets are functions.
And of course, underlying every continuous function is a plane function.
And so there is a function from the category of topological spaces to the category of sets which just forget the topological structure of the spaces because every topological space has an underlying set of points.
So you have this forgetful functor and this forgetful functor has two adjoins.
And one of the things the category theory teaches you is that adjunctions give you this universality.
So adjoin functions are characterized uniquely by their kind of satisfaction of this adjunction property.
So these two adjoints to this forgetful functor one gives you what are called discrete spaces.
So if you take a set, you can turn it into a topological space by thinking of all the points as little islands in this space so there's no connectivity between them.
And that's called a kind of discrete space on that set.
And the other adjoin puncture gives you what's called the indiscrete or sometimes co discrete space where all of the points are sort of collected into one big island, so they're all sort of connected together.
So it's like a sort of fully connected graph.
And of course that's very different from the discrete space and it's different from the spacetime or the space that you live in which has a particular kind of connectivity, like you can't walk through walls.
And so people try to use these things, particularly use adjunctions to characterize things like properties of spaces.
Another thing that comes out of a jointness and this is something that I can let you read about later because it'll take me the rest of the talk to try to explain.
But you might be familiar from logic that you have these quantifiers, you have existential and universal quantifiers and you can do things with these quantifiers like you can sort of compose them together.
So you get things like for all x, there exists for Y, such that this and you can think sometimes of these composites or these compositions of quantifiers as like maybe like modal operators.
Like you can sort of decompose necessity and possibility in terms of the compositions of logical quantifiers.
But the kind of weird thing about quantifiers is that they too arise out of an adjunction.
It's kind of like they are left and right adjoints to substitution.
So if you have a proposition, you can substitute a term intimate and the adjoint punctures to substitution give you the quantifiers and you can sort of take this another step and then you can think about like composing these adjoin punctures and those give you the modal operators.
And so that's something that comes just out of category theory, but is really sort of fundamental in sort of logic.
And we might think that there's a kind of close relationship between physics and computation or physics and logic, or physics and information and information and computation and logic.
So I think it's not quite true that there's nothing to be gained from thinking about kind of traditional mathematical things or traditional physical things.
Using category theory.
In some sense doing that really clarifies the essence of them because it tells you what their kind of universal properties are and you can then instantiate those things in different contexts.
So one of the things that you could do is start to think about these kind of logical structures in different contexts.
And that's kind of like what type theory is all about.
And you could use it to think about the logic of dynamical systems, or you could use it to try to characterize, say, the universal property even of the free energy principle.
And that's something that I like to think about sometimes.
How can we think about active inference systems as trying to achieve their goals?
Is that related to these adjunctions that come up in sort of foundations of logic when you look at them categorically?
And if it is, then that's quite profound because.
It tells you that maybe the FEP does have this kind of universality that people want to claim it does.
So I think it is true that right now, because it's quite early days, category theory is kind of mostly used for bookkeeping.
But I guess that might be because there's quite a lot of bookkeeping to do before we can make the most of this kind of move, make the most of using these kind of universal structures and maybe one day further in the future where people are more familiar with this kind of language and we have this big library of categorical tools and our computer sort of modeling environments and programming languages know how to import stuff from this category just really easily.
And so you don't have to do all this kind of PDS manual stuff.
Maybe like in that future it'll be much more common just to say okay, well we're going to start to model things using these universal properties off the bat rather than trying to sort of retrofit them.

36:03 _Daniel:_
Awesome.
Thank you Toby.
Ali?

36:07 _Ali:_
Yes.
Thank you so much for your detailed answer and again I have a follow up question to that.
So there's this view in philosophy of science that views scientific theories as not as a kind of monolithic, I mean, phenomena or model, but rather any given scientific theory can be viewed as a population of models.
So some of those models are more fundamental than the others.
Or in terms of manual delanda, there are virtual and actual parts of any given scientific model.
So the idea here is that the actual parts of scientific models try to capture the context dependent behavior of phenomena or any physical system.
But on the other hand, the virtual or more fundamental part of scientific models or theories try to somehow capture its more abstract and abstract model of the phenomena in terms of its topological invariance.
So do you think category theory can provide a rigorous language to somehow unify this view of science and to see how exactly those context dependent part of scientific theories fit or at least can be compatible with the context independent part of scientific theories or the virtual part?
Because you see, in the context dependent or actual models scientists usually try to refine their models to fit the data as close as possible or at least approximately close enough to be useful.
But for the more fundamental parts comprising of principles, axioms and so on, they only try to capture the topological terrain or the topological invariance of the models and how models can be compared in terms of their singularities and topological shapes.

38:47 _Toby:_
Yeah, that does sound very familiar.
I don't know this kind of work or idea in any I haven't come across this before, but it does sound something that be quite amenable.
And in fact, there seems to be, at least in my mind, some alignment between this kind of sense of virtual that you're talking about and this kind of universality that I was talking about.
So you could think of a category of models of particular kind as being inhabited by all of those things which satisfy these invariants.
And then you have different individual instances of these things which would be like the object of the category, and then the differences between them are the morphisms.
And the thing about morphism in the category is that often they are the things which preserve the structure.
In other bits of mathematics, they're called homomorphisms, and that's where the word morphism comes from.
And so you could think of those as ways of comparing the models or translating the models from one to the other, but preserving those invariants.
That seems to me to capture some of the idea that you were sketching.
I guess one thing which may or may not be useful, depending on how you look at it, that category theory gives you is it's obviously kind of a lot more general.
And so it allows you to talk about invariants of kinds that are more than just more than just topological in some sense, like functoriality is it kind of captures the kind of invariance as well and saying, okay, well, we preserve this structure.
Just one way of looking at a topological space is to take its its what's called its nerve.
And so that takes a topological space and turns it into a category.
And you could sort of think of the morphisms in that category as the paths in that space, or ways to sort of get from one sort of part of the space to another.
And then morphisms functions between topological spaces considered in categories like that, they really are just things that preserve those topological structures.
This language kind of seems to encompass the kinds of things you're saying, yeah, it would be nice.
I would love somebody to make that connection.

41:44 _Daniel:_
Just follow up on this and then dean it's.
A related comment from Roman in the Chat.
Roman wrote, quoted you in this fractal quote, streaming thinking about the FEP through category theory and relation to goals maybe allows to prove that FEP has the universality that people claim it has.
And Roman asks, didn't Maxwell, Ramstead and Dalton Sactiva Develle already kind of prove this in the Bayesian mechanics physics of and by belief work?
So you're talking about the role of generalization.
What do we gain with the category theorification of FEP beyond, for example, the generalizations that we've seen in Bayesian mechanics and g theory over the last year?

42:38 _Toby:_
Yeah, that's a great question.
I think Maxwell and Dalton are doing a great job formalizing the ideas of Bayesian mechanics, but as far as I'm aware, the job isn't done yet.
And so I haven't yet seen I have a particular aesthetic right.
And I would like I would like to see a really clear recipe of a way to take on the one hand or, like, some machine that takes in that has, like, a particular shape that is, like, input shape.
And it takes in a dynamical system of a particular kind and it gives me back like the the specification of an inference problem that that dynamical system is solving.
I think that's what Bayesy mechanics is saying.
It's saying, okay, well, if we have a dynamical system that is somehow kind of you could sort of look at it and say it has a boundary or Markov blanket, that you can write down its dynamics as if it were doing free energy minimization that is solving some inference problem.
I think that statement is true for certain classes of dynamical systems, but I don't think the story has been made.
The questions for me are like what are the classes and what's the essence of those dynamical systems?
So the result might depend on specific technical criteria which maybe you think, okay, well, that's kind of like a distraction from this kind of abstract principle which we're trying to get at.
And so it would be nice to sort of know what the actual essence is of the problem that allows us to do this translation.
And then there seemed to me to be questions of other fairly technical questions, but questions about things like what is this boundary thing?
Like how long does it persist and what does it mean to separate a thing off and consider it as having a boundary?
Most of the treatments I've seen of this idea have not been done, have not been explained or expressed in this compositional way.
And so they just assume you're given a system and a boundary and then that's kind of it.
But boundaries come in all kinds of shapes.
Like the boundaries of the cells in my body are kind of all like glued together in a particular way and they form me and I also have a boundary.
And so how do the kind of local inference problems that are being solved by those individual cells, given their gluing amount to the kind of inference problem that my whole body is solving?
And I don't think an answer to that is anywhere near given right now.
And yet, obviously we look at systems out in the world and they all seem to display this property of ReEnergy minimization or at least something that looks a lot like it.
And so it would be nice to be able to relate those kind of inference problems to one another.
So I think there's still a lot to be done.
Just because we've kind of made some first steps doesn't mean that we're all of the way there.
Obviously, given my aesthetics, what I would love to see is this kind of abstract characterization of this universality.
And I think there's a way of stating or at least the structure of that universal property using this compositional active inference language of which the thesis is a part.
But effectively it seems to be something like this adjoint thing that I was talking about earlier.
So on the one hand, you have something like a functor that takes statistical problems and gives you dynamical systems that kind of solve those inference problems.
And so that's a functor from statistical, what I call statistical games into dynamical systems of some kind.
But of course you have lots of dynamical systems.
And so what this Bayesian mechanics idea seems to be saying is that you can go the other way as well, and maybe this mapping in the other direction is also functional.
And that would be a way of characterizing this kind of gluing together of dynamical systems like I was talking about cells and ending up with maybe dynamical statistical games that also have this kind of fluing property.
But there's still a fair amount of work to be done even to get the basic framework to sell out that story precisely work that I'm trying to slowly get on with at the moment.
But I think the ingredients to doing this in the kind of generosity that I would like is starting to become clear and so hopefully we get there, but I don't think it's sold yet.

48:46 _Daniel:_
Awesome.
Yes.
Just so cool to see all these paths weaving together.
Dean.

48:57 _Dean:_
I think it's awesome, Toby, that you in this conversation have kind of anticaptured adjointness and common jointness because I think that's a huge part of your work here in reading it.
Here's my question.
I think, and I would like you to maybe comment on this as though you were explaining it to a very curious 15 year old.
So on the sort of most basic level, when I hear under sort of a common jointness principle, the word bookkeeping, I immediately wonder, okay, so what is the partner, what's the thing that's being glued to, to use your metaphor?
And so I would glue it to taking receipts, essentially, where you have a stabilization of a record under bookkeeping.
So I get that part and then the taking receipts is the stabilization of the change function, right?
The exchange, something that we receive, those two things seem to kind of work together, which then allows for compositionality and all that other stuff.
But maybe I wonder if maybe you could kind of speak to this idea that something is presented to us and then what the category theory does is allow us to now start working with so where does this fit?
Does this fit under this superordinate of being a tool?
Or does it fit under this column directly, adjacent as a rule?
That's the part where I think the adjoinness could be really helpful in terms of maybe helping people see the applicability and not just the abstraction.
What's your thoughts on that?

50:59 _Toby:_
I think David Spivak talks about category theory as being like a kind of accounting system, or accounting systems plural for mathematics.
And I think he's kind of quite right then.
So the way I see it is when you're keeping books, particularly if you're sort of using like this double entry system, you're trying to keep track of the stuff that kind of flows into and out of your account, your company or whatever it is, without sort of missing some bits.
You see where everything goes.
And so that's how I think of this kind of mathematical language.
You have this stuff and it's kind of like some abstract collection of things, maybe mathematical ideas and well, A functor takes that stuff and does something with it and turns it into some stuff of another kind.
But it's like this kind of double entry idea that when you take something out of here, you have to put it in here and so you have to sort of keep track of all the details, at least all of the details that are relevant to those two, to that flow, I suppose.
And so when you have an injunction, you have a way of going from one place to another and back again without losing track of some stuff.
It's like a little bit kind of like you're allowed to lose track of some stuff but you know the stuff you've lost track of because you don't care about it.
You might allow for some have some buffer there, but you know how big your buffer is, something like that.
So more precisely, like an A junction is a way to map from one category to another and back again in such a way that the two mappings are kind of like ideal approximations of the inverse of each other and that you can sort of measure the difference between them.
It gives you like an isomorphism between the two sets of morphisms of some kind and that that kind of gives you this nice kind of structure preservation property, this kind of bookkeeping property.
I know that there are people out there who have used category theory to model stock flow diagrams and so these are used in economics to measure flows of stocks and things like that, but they're also used in epidemiology to model the transmission of disease because that's also like a flow of some stock.
You have people moving around.
And so it would be nice to sort of bring this idea full circle and have this mathematical language of bookkeeping actually applied to bookkeeping.
But I don't know how that would go just yet.
If we think of economies and corporations as adaptive systems or if we somehow kind of translate from flows of money to flows of information, that there does seem to be like an analogy between that kind of flow and the kind of flows that we think of in active inference explicitly.
And another thing, one of the things I like about category theory is it allows us to make these analogies in a precise way and so maybe we can relate these two things quite clearly.
It's yet to be done, but I would love to see it.

55:26 _Daniel:_
Awesome.
Dean smiles when his keywords are buzzed during a response.
We'll go to another great question in the chat from Matt N.
Matt wrote can you provide some ideas about the next necessary steps or milestones for categorical theory to be effectively utilized across research and in subsequent engineering applications?
And I'll just kind of append to that.
What do you think at the individual team and organizational scale?
What can we do, what milestones exist to realize some of these engineering applications and implications that you brought up?

56:14 _Toby:_
Right?
So I think the main thing possibly, unfortunately for you guys, who spent a lot of time reading the details that I wrote, is to kind of have this community develop to a stage where the tools that I mentioned that allow us to kind of use these category theoretic concepts fluently without having to know all of those boring and complicated details, to develop those to a stage where people are actually able to use them without being kind of like mathematicians or category theory domain experts.
So this is, I think, starting to happen.
I guess as a result of the kind of needs of the Pandemic, people have developed these tools for Epidemiology.
I mentioned this stock flows stuff and I think you can probably there's like some I can't remember what it's called, unfortunately now.
So in the Julia programming language there's this great framework to use for kind of building systems using category theory concepts.
But of course this doesn't satisfy the property of not having to be a category theory domain expert.
Yet on top of that, people have built using compositional ideas about dynamics, frameworks for building compositional, dynamical systems and compositional models for things like Epidemiology and stuff like that.
And hopefully you will get there also with statistical modeling and active inference and all that stuff.
But once you've got that kind of lower level library, people can start to build user interfaces on top of it.
And that's the thing that's starting to happen now with the stock flow stuff.
And I think that people involved in that project, they know that there's one kind of major proprietary tool for doing this kind of modeling which is used for it's used by lots of different organizations.
For instance, it was used by governments for modeling during the Pandemic.
But it's not very collaborative, it's not compositional.
So if you have this huge model, it's very hard to deal with, to modulate just some small part of it.
And so these people, as I say, it's very unfortunate.
I can't remember all their names or the name of the software, but they're building this tool which allows you to build out these models just using this interface.
But it's built out of this compositional stuff and so it has a lot of the nice properties that come out of it.
And of course, if you want, you can sort of delve under the hood and understand actually how it works and connect it to all this other stuff and maybe down the line when we've got really advanced tools that that will kind of be able to be done for free and some nice user interface.
But I think so if people want to make the most of this, they could sort of get involved with that kind of effort or at least they could sort of get familiar with the kind of basic ideas of categorical modeling or compositional thinking, as I like to say these days.
But I also don't want to prescribe to people they have to know what like a monad is and all that stuff because, you know, there are it is technical, it has to be technical because it's about technical stuff.
But I mean, it's also trying to be ergonomic and if that's your thing, you can try to help make it more so.

1:00:07 _Daniel:_
Awesome Dean.

1:00:11 _Dean:_
No, I'm waiting because there's a part of the paper that the belief updating and the fuzzy of distributions and stuff.
I'm going to want to talk about that later, but I'm done for now.

1:00:28 _Daniel:_
All right, I'll go to a question submitted by Jr also who created the syllabus.
So thanks again Jr, for that amazing work.
So Jr.
Wrote in compositional active Inference from May 17, 2021.
Toby said I'm with Valeria on this.
I think we need to seek AI alignment for the artificial intelligences that we already have things like corporations and social systems and we should be concentrating on those right now.
Could you speak more about how you envision this kind of application?
This is especially interesting in light of what we spoke about in the 54.0 regarding sensor fusion and consensus.
What might this mean for corporations and social systems?
Toby, do you mean that this between humans and things kind of like artificial intelligences or machines and artificial intelligences in the context of companies and societies?

1:01:28 _Toby:_
Yeah, that's a great question and I think Jr has done a great job with the syllabus, which I also had a look at.
Yeah, I think it's a good list of material and concepts to sort of get to grips with, but as per yeah, AI alignment, it's a very vexed issue.
Of course, I put this to people who are involved in the AI safety community and some of them say, oh well, we concentrate on machine intelligent rather than corporations because there's like no hope for making corporations safe.
Like it's too late, they're already out there so we can't fix that.
Which is obviously a very sort of defeatist attitude, but maybe it's right to concentrate on a matter where they think that they can actually have an influence.
But I do nonetheless still think that corporations are like super intelligences.
They've been made out of code, but the code isn't a traditional computer programming language.
It's the legal programming language that makes up their contracts.
But those contracts determine how they operate and are executed on a thing, which is a bit like a computer, like the legal system.
You go in a court, it processes the contract and it explains what the outcome is going to be.
It's like a computer, but it's like made up of people and they have goals and desires and they take actions and they receive information from the world.
And so, yeah, they're a lot like, well, AI systems.
But it's nice because we can pun on AI and have it mean both artificial intelligence and active inference.
That's like a long preamble.
One of the things that at least as far as I know right now, the active inference literature doesn't talk an awful lot about, at least not very precisely, is this notion of sense of fusion.
So you can have like two say you have like two yeah.
So if you think about the brain, again, you've got two little neural circuits next to each other and they're making predictions about two visual receptive fields.
But those visual receptive fields, they kind of often overlap.
And so what we might want a system like the brain to do is to be able to kind of glue the two inferences that those circuits make together over this overlap so that you get this unitary perception.
We don't just see a bunch of independent patches of the world.
We see this kind of glued together thing, even though the way it's been inferred is through lots of individual systems next to one another.
And so it's quite clear how to put two things next to each other mathematically.
You just take their sort of product, then you just do them side by side.
But when you want them to sort of glue together in this way, you might encounter some problems.
Like you might have one make one inference and one make another inference.
And so you get like a disagreement and then you need to start to say, okay, well, what's going on there?
What is the nature of this disagreement?
Is it something that can be resolved by, say, passing some messages between the two systems?
Or do we need to just ignore some of the data?
Or is there fundamentally some paradox which means that we can't resolve this disagreement?
And so in mathematics, there's a lot of theory that's been done about precisely this question in topology in a kind of abstract way related to the field of what's called cohomology, which is all about measuring obstructions to doing this kind of gluing thing.
And sort of in this world of applied topology, people talk about algorithms for resolving disagreements and things like that, and they often have the flavor of diffusion.
You can sort of think of diffusion as like smoothing out disagreements because you're just sort of like letting stuff propagate something.
There maybe could be said about how these diffusion models work in generative AI, but I haven't really thought about that.
And so maybe there's something to be done for political systems or corporations.
Like, maybe we can look at how the mathematics says we can resolve these disagreements and implement better processes in our organizations that are inspired by those algorithms or kind of universal properties and maybe that'll make the world a kind of more harmonious place.
Or maybe it will just help us build systems in the future which resolve disagreements better.
And this is one of the reasons why I was talking about multi agent systems before.
I know this is a thing that sometimes people think about in the context of blockchain systems and things like that, which are actually actively composed of lots of different participants.
But I don't know yet how it might all pan out.
I mean, ultimately the question of alignment is really about do the goals of this other system disagree with my goals?
And if the other system has more power than you, then ultimately there's probably not much you can do about it, regardless of whether there exists some algorithm that might help you smooth it out.
So I hope at least that by looking at how the mathematics says, we can optimally resolve disagreements or smooth them out or patch things together or build kind of multi agent system that will help us build things in the future in such a way that we don't get to a situation where the systems we're working with are actually aligned against us.
Say.
But obviously we can't really guarantee it.
We actually have to sort of do some work.
But it's nice that at least the framework of active inference allows us to talk about that at least, right?
So we can say like, oh, I have these beliefs about the world and this other agent has these beliefs about the world and then we can express these beliefs in a mathematical framework which is amenable to using these tools from cohomology and applied topology to be able to start to make use of that work that's already been done.
It's to me not so clear how you would do that if you're not working in this active inference world and you're working, say, with just reinforcement learning.
I know there are similar questions about how to kind of glue together preference functions in economics.
And I think for me, the simplest way to kind of understand those questions is to kind of turn those preference functions into distributions over states and then use this kind of sort of more active inference language to think about it.
So, yeah, again, we're just at the start of this process, but it sounds like we should be able to make use of this wealth of tooling which has been developed in other fields.
Because we're putting this into this kind of modular categorical language, we should be able to kind of put these two modules together and make make the most of them.

1:10:43 _Daniel:_
Thanks.
I'm going to go to a different sort of question here.
I'm going to play dissertation roulette but I kind of know where I'm going to go and I'm going to skip to a diagram.
It's a diagram at the end of chapter six, and it looks like this.
So what do we see here?
What happens in this graphical arrangement?
It doesn't have to be ultra specific about defining every variable, but is what matters here that's apology or the geometry?
Is it an arbitrary visual layout, but you're conveying something about the connectivity?
Or is it read from left to right?
Or is there a certain way to understand or just approach these diagrams which in slightly smaller forms or larger forms we see peppered throughout category theory and your dissertation?

1:11:43 _Toby:_
Okay.
Yeah.
So here what I'm trying to do is say that if you have a hierarchical predictive coding system, if you take the form of two parts that are sort of plugged into one another and this is the the G.
And the H, if you, like, do predictive coding on G and you sort of plug that into H, and then you do predictive coding on H with that input.
It's the same thing as doing predictive coding directly on the two parts as if they were one thing at the start.
So what I mean is, if you have here we've got like a hierarchical system.
Again, the parts of the hierarchy are G and H.
And we could do two things.
We could either apply predictive coding to the two parts and then glue those predictive coding systems together, or we could glue like the G and H together and then apply predictive coding to GH the Glued system.
And what this bit of this result is saying is if you do those two processes, you get the same dynamical system.
And that's saying that this predictive coding thing, at least with this sort of Laplacian scheme, is functional.
So in this diagram, it is read from left to right.
I mean, some sense you can orient these diagrams however you want as long as you're clear about how the information flows.
And if I remember rightly, what we've got is we've got some like yes, we've got X and Y.
We've got one system which is predicting X and one system which is predicting Y.
And I'm not totally sure what P and Q are, but I guess they relate to X and Y.
And you've got some stuff that's coming into the predictive coding system, h of G and some other stuff which is coming in and going to H of H.
And these give you like updated states.
So in predictive coding with this LaPlace algorithm, what happens is that you get this new observation that comes in and you look at the error between that observation and your prediction and you update your prediction according to the sort of direction that error points you in.
And so that's what these HG and HH systems are doing.
But because it's a hierarchical system, this second layer, which this.
Second layer requires you to take in the prediction of the first layer.
So if you sort of follow in the flow of information, HH takes in inputs from Gamma.
Gamma is the kind of the predictive channel, the predictive part of G.
And so that feeds into H.
And the update of G, which is a sort of layer above H, requires this newly updated belief from H.
Right?
So that's going sort of up in the causal hierarchy.
And so if you sort of follow the flow in as well into this G update function at the top H of G, you see that it gets an input from this sigma function.
And that's the new belief emitted by the H system.
In this part of the proof, at least that was the notation I used.
And so this is just saying, if you do predictive coding on these two bits, it has this structure which is you do the forwards pass down through the system G and then H, and that gives you a prediction at the kind of lowest level.
And then you take your observation, which is, I think, thing you get in here in Z.
Yeah, that's what Z is.
It goes into H.
You get an updated belief that comes out in the form of the sigma and then gets passed to the first level of the hierarchy, which is used to give you the highest level of belief.
Great.

1:17:10 _Daniel:_
Well, it's awesome because in so many papers we see what I guess people expect and prefer, which is you should be able to make a nested model here and have communicating agents here and do sophisticated affective inference in this way.
And it's like we're already playing with the Legos in a sense, and talking about it like it's a total play shop.
So to understand in a way that is worthy of dissertation research, some of that substrate, it's basic Lego research.
And how do you know when you're working, you describe this as a result?
How do we know?
I mean, can I just draw a line from here to here?
Or can I just make a D and just have D connect to Gamma?
What rules do you keep a guidebook or recipe on the table?
What rules help us know what edges and shapes you can even draw?
And when you describe the manual checking, are you looking for what right?

1:18:25 _Toby:_
Yeah, this is a good question.
It is like a language.
So it has a syntax.
And that syntax is like the I mean, it's like the grammar, right?
And it tells you what things make sense to say and so you only say those things.

1:18:54 _Daniel:_
Don't we all?
Don't we all?

1:18:56 _Toby:_
No, but that but it's, it's it's that's what I am laughing because often you want to like play with the grammar, right?
And so sometimes you're like, oh, it feels like I'm not allowed to draw this thing.
I'm not allowed to connect this box to this other box in this way, but I really want to do that, and that's not a bad thing.
You shouldn't do it in that diagram where it doesn't make sense, but you should take that feeling and reflect on it and say, but that's saying that maybe this diagram syntax is missing something important.
And then you should trust your intuitions there and say, okay, well, actually, what do I need to do to this diagram language to make it allow me to do that move that I wanted to do to draw that thing I wanted to draw?
And so that suggests that you're walking through, like, a valley, and you can see there's a hill over here, and there's something peeking out over it.
And you're like, actually, there's something over there I need to be able to see.
And so you have to move over towards a different place to be able to get to that place.
And so you should do that right then.
That's fine.
But the reason why I said at the beginning, don't just draw it in your diagram is because then that means your diagram doesn't mean anything, and that's worse.
So this is part of the reason that it actually requires using this kind of mathematical formalism.
Really, using mathematics generally requires this discipline because you don't want to say things that don't make sense.
If you have an intuition, you should do it justice and treat it seriously.
And you probably get more out of it by figuring out what's missing.
So with this particular kind of string diagram language, you can't just get used to reading them right?
So you know that these little black dots mean copy some information.
So if you see the first one or like, the second one on Y, you go from Y, you go into this copier and you just send the information to both of those outputs.
If you read like Bob Cooker's work or say, his book on his book Picturing Quantum Processes, which is all about quantum theory, using this string diagram language, there are lots of different rules for stuff you can do with these languages.
Like you have colored spiders, he calls them, which are like colored versions of these black dots.
And there are things you're allowed to do.
Like if you have two spiders next to each other that are the same color, you can sort of merge them to be a spider with as many legs as the two of them.
And if they don't have the same color, then you can sort of split them apart.
And those kinds of moves are like part of the syntax of this language, but it's a human language.
And so people developed it, and they realized that they could do some things, and they realized that they couldn't do others.
And they tried to make the rules of the game match the things they wanted to do, and they ended up with this language which is now used a lot in quantum computing because it's a very sort of natural language for that problem.
So as to how do you know what kinds of things to draw?
Well, here, like I was trying to prove functionality, which is a sort of general property.
And it says the thing it says, in an abstract way, the thing that I started by saying, which is there I wanted H of G h to be the same as H.
Yeah.
See here, if you see this line, the update map of the composite system, you see I've got HH after HG.
Well, I want that to be the same as H just applied to H after G.
And so that says, okay, well, I want these two things to be equal.
And so what I do is I draw the two diagrams for the two parts, and you draw them out, and first of all, they don't look equal.
And you're like, oh, that's annoying.
But then you stare at it for a bit and you reflect on the kind of moves that you're allowed to make.
You think, well, okay, maybe I can apply this move, and it makes the diagrams look a bit more similar, and eventually you make the diagrams look the same.
You've only used rules that you're allowed to use.
I see.
Sort of skimming through to see if it looks like that directly in the thesis, but effectively, that's what's going on.
It's just that the rules are a little bit abstract, though.
That being said, I know that Pavel Sobachinsky, who's researcher in category theory at Tallinn, he's got a project with a colleague of his to build a mobile game, which is all about making string diagrams equal in this way.
And so the idea is that in this game, you have pictures like this, and you've got certain moves you can do to manipulate the pictures.
And the sort of aim of the game is to transform one starting picture into the sort of goal picture just by applying these moves.
And as you go through the game, the kind of moves you can do become more complicated.
But it's I mean, it's the same kind of process.
I'm not sure the game is at the stage now where you're allowed to do this human creative thing and think, actually, I want to make there be a new kind of move, or change the diagrams or add in a color here or something that's a really human thing and designed to say you shouldn't do that.
But I'm just trying to advocate for doing that in a way which is also rigorous.

1:25:42 _Daniel:_
Awesome.
Yes, to speak fluently the syntax and the grammar, whether we're talking about natural human language or we're talking about the active inference ontology, we want the syntax to be unobtrusive, if not compressient, so that we can actually convey the semantics, because that's the real information flow.
The syntax is within the Shannon signal entropy space.
And then in live stream 17 and 40 and the physics as information processing with Chris Fields where we've been exploring these semantic Bayesian information flows that must, out of necessity, to be enriched beyond the syntax, have to include an individual or shared context that flow necessitates the proper syntax.
And so it's just part of the learning.
And so it's exciting to see that there's games and work like yours and others to help because if we could play with those Legos and get the instantaneous feedback just like learning with a language tutor of like, no, these two pieces, they don't fit together.
And then we kind of would actively infer patterns, make our own rules and understandings, but there would be certain compositionality of the system itself.
And so it's interesting to think of like you described it as a natural language.
It is technical and naturally arising.
And our natural language, without going too much into the superior wharf and everything like that, it reflects the kind of subject, object, verb structure that we often want to convey.
This is a natural language for science.
It conveys what we want to convey.
And so being able to do that in a way that is both disciplined and rigorous, also enabling low cognitive overhead fluency for some individuals today, but for more tomorrow, that's just extremely powerful.
And the fact that it has such a beautiful and intuitive way to graphically represent it is very promising because that may tap us into a more holistic understanding and a visual field or a felt sense understanding that just looking at this and someone says, wait, this is what we learn in active inference.
It's like, well, no, that's not even the tip of the iceberg.
There's so much more to it.
And it's not only this and all of that, but it's one of the pieces that at this moment in time, in our sort of early calculator phase or Abacus phase, almost, it's one of those things that we're tackling, but it's the wave that we're riding.
And I just can't wait until there's more accessibility and the learning pathways and the playgrounds to use all this.

1:29:15 _Toby:_
Yeah, I mean, I totally agree with all of that.
And I think it was nice to see the gr in this syllabus that included references to Eugenia Cheng's work because she's done a lot of great work to kind of make mathematics more accessible in this way.
She had an article in the Guardian, like, in the last week or so, even talking about mathematics education and how it often, like, scares people because they're taught to.
Like, you just apply algorithms in this kind of blind way to do, like, multiplication or calculus or whatever and not really play with the concepts in the way that I was trying to say.
Okay, well, you're drawing these diagrams and you want to play with them.
And it would be nice to see mathematics education take this kind of more playful route to start with.
One of the things that Eugenia says in this article is that unfortunately, that would make things kind of slower because you just want people to muck around.
You don't want people just to be able to churn out this kind of computation.
But in this future where our computational tools are so powerful, maybe we don't all need to be perfect integrators or like derivators and be able to multiply numbers quickly.
And some people like doing long division, but I don't even remember how to do long division.
Why would I?
It's silly to kind of drill that into children.
So there have been projects to teach, like kindergarten children, like a couple of projects, not many.
Some of the kind of rules of this string diagrammatic stuff in this quantum information processing world.
Bob Cocker and his colleagues I think there was one project by Dan Geeker in Birmingham and maybe one by Bob himself, or at least he was trying to get it off the ground.
I don't remember.
But at least where it has been tried, I think they found that children very easily learn to use these kinds of languages because it's just playing with pictures.
They're kind of much more approachable than this kind of scary symbolic language, which is it's a kind of fine language if you're used to typing on a typewriter or like writing by hand, where you write in this linear way.
But if you go to a mathematics department and look at the whiteboards or the chalkboards there, most of the time you see lots of pictures, diagrams and things.
And that's how people reason, typically.
And so a lot of what's been happening with applied category theory is trying to take using diagrams seriously as mathematics and trying to say, okay, well, here's what we can do if we do take it seriously.
We can sort of recapitulate some of these things which people have found like abstract or abstruse or difficult in mathematics before and make them seem a bit more easy to reason with.
Now.
That applies to abstract things like stuff I've mentioned already, like adjunctions, like the laws of adjunctions.
You can draw them with think string diagrams.
I haven't shown it in my thesis.
But if you sort of Google around, you can see adjunctions in a two category and they end up being some kind of snaky picture.
And sort of you get a sense of what's going on there from these pictures, like the flow of information in some sense.
And there's a similar thing with Monads.
The joke for functional programmers about Monads is like, oh, you don't know what a Monad is?
Well, it's just a monoid in the category of endofunctors.
And I mean, that's true.
It's not just a joke.
It's true.
But the thing is, if you draw what a monoid is, it's like a thing which like one of these like you see on that picture you've got this gauss thing, and then it's got a black dot, and you got one wire, and then it has a black dot, and then two wires come out of it.
And I said, this is like copying.
Well, a monoid is like that in the other direction.
Like, you've got two things that go into a dot and that come out with one thing.
So when people say monoid, they mean something like they often mean something like addition.
You've got two numbers that come together and they produce one number.
We've got, like, multiplication.
You've got two numbers again that come together and produce one number.
So it's like the opposite of copying in some abstract sense, which takes one thing and gives you two things.
This is something that takes two things and gives you one thing.
And so you can just draw the diagrams that define a monoid and say, okay, well, what does this mean for endofunctors?
And you can sort of start to reason about it a bit more approachably.
I mean, it's still quite abstract because it is quite abstract, but it makes it kind of less scary to use this kind of language, I think.

1:35:11 _Daniel:_
Awesome.
Yeah, there's so much psychology and sociology in mathematics and just hearing about yeah, on real chalkboards, people branch and they flow and they circle things and they put an X through something.
It's like there's all these operations that can't be copied with a typewriter.
And as our cyberphysical and social niches develop and we have different affordances, different metaphors, different quantum reference frames for working and being, it starts to make more sense for having a natural language that can express that.

1:36:06 _Toby:_
Then I go on.
I said loads of stuff.

1:36:09 _Daniel:_
It just makes me think of a Turing tape where even if there is a linear representation, it can still in some other way characterize like a Lisp program with nesting or hierarchical model.
Even though, yes, there's like a linearity but also there's a model.
So it's not that we can't represent certain things with the bit streams or anything like that.
It's just that that may be more like the assembly language and that when we actually want to do certain kinds of work, we may want to just move lightly and semantically with a high level way to think about math.

1:36:48 _Toby:_
Yeah, totally.
It's kind of notable to me that recently I've been giving talks for a while using a computer, whether or not over zoom, but it could be in person.
I have my PowerPoint slides or whatever, but these days, if I give a talk, I just use my digital tablet and I do everything, like all the slides by hand, and I draw pictures.
And it's nice now that we've got technology that is starting to be a bit more human in that sense.
And I think this is like a kind of mathematical technology which is like that.
Although I think it's also notable that it's still, in some sense, quite niche.
And I think I don't know, but the impression I've got from talking to people is that it's still the case that some mathematicians think of this kind of like mathematics as diagrams, as somehow not quite like real mathematics, because it's too much like play in some sense.
But I think that perspective is changing and people are taking it seriously.
I mean, it is real work, and there's a lot of hard problems and stuff actually gets done.
But I think to me, it doesn't really matter what, like, a handful of mathematicians think.
It's just what's useful to people that matters.
And so I hope that these tools continue to develop and we can use them in all sorts of different domains.
I don't know.
It's notable to me as well that human vision is kind of like two and a bit dimensional, really.
It's not really like three dimensional, but you've got a bit of three dimensionality.
And I've never really played much with, like, three dimensional diagrams, but maybe I will one day have some tools with my Vision pro or less not pro thing or whatever.
It allow me to do things even more naturally, like actually plug together some stuff in some abstract space.
Who knows?
Who knows?

1:38:59 _Daniel:_
Yeah, the diagram being two dimensional.
Or planar gives us this kind of classical screen holographic screen.
That information can be written on that.
Then quantum cognitive agents can unfold into the imaginary plane with the WIC rotation.
But also the boundary, just like you said earlier, can come in many shapes, many dimensionalities.
So we could have a four dimensional boundary artifact that still becomes rotated into a higher dimension.
And that's not the framing or the mathematics that most of us have learned up to this point.
There's a really crystallized would be a complementary way to say it, but codified or fossilized sedimentary understanding of math education, its role in broader thinking and what we learn along the way, and the progressions get reified with who makes it through the pipeline.
So I think that's, like the unknown unknowns here, the known unknowns.
We all know that we struggle to understand this, but then that's the real jumping off when it's not just us adapting into a new regime of learning and doing, but when there's composition and construction within that regime.
In our last sections here, Dean or Ali, another question.
Or what are you looking to bridge or gap into the dot to?
Okay, Ali, please.

1:41:09 _Ali:_
Well, yeah, actually, I've written down a number of questions, but they may be quite specific, and I think they're perhaps best suited for the two discussion.
But I wanted to thank Toby for I mean, I literally had goosebumps the entire time.
So it was really fascinating and quite enjoyable, and I learned a lot.
And I hope to… I also have some additional questions in my mind.
I hope to get to some of them in the second discussion.
So, yes, thank you again.
It was really great.

1:42:00 _Toby:_
Thanks.

1:42:02 _Daniel:_
Dean, with the penultimate thoughts, what do you see us heading into?

1:42:10 _Dean:_
Yeah, well, if it's okay, I'd like just to read a really brief piece of the paper because I don't want to launch this on Toby in the dot two, without giving him a chance to think about this a bit.
Under seven four, you've got fundamental theory, and you say future work connected to this thesis need not only be in applications, a number of purely theoretical questions raise themselves too.
And I love seven four one.
This one paragraph for me, I call it a really have to slow down and enjoy the moment today.
Toby, I don't know if you're a distance runner, an endurance athlete of some kind, but your stamina has been phenomenal.
But this one paragraph to me would be like a refreshment station where they offer you a milkshake and a piece of battered fish.
Like, it's yummy.
But you need to wait.
You have to pause and kind of go, I don't know if I want to do that.
But it really ties in nicely with the syntax stuff that Danny was talking about.
And I have a question at the end of it, so I just want to read it, though.
The mathematics of belief.
So you basically said belief is theoretical.
That's fantastic.
Is in large part about replacing definite points with fuzzier distributions over them.
Independent type theory, we replace points with terms.
Independent terms are exactly points.
So a type of theory with belief should somehow encompass fuzzy terms.
Just as we can replace points with distributions, we can replace dependent points with the dependent distributions.
However, the standard replacement, moving from a category of functions to a category of stochastic channels, obscures some of the universal categorical structure.
And underpins the rules of type theory, this standard replacement also misses something else.
While it does allow for fuzzy terms, it omits a model of fuzzy types.
We might well want to express beliefs about things whose identity we are not quite sure.
And then you say in the next sentence, there seems to be a couple of related resolutions to this puzzle.
My question for you is this, and it's not for today, it's maybe for next time.
It seems to me we have to grapple with this idea of making fuzzy clear and making fuzzy precise.
And you started speaking to that.
And my wonder of coming now with a strong, much stronger active inference set of priors is there has to be something more to this than just a gradient descent.
And I think you started to speak to that in this section.
And so I'm kind of curious.
Do you think that this is a feature, the fact that we can do this, we can do fuzzy clear and fuzzy precise and not necessarily see that as a contradiction, but actually the way category theory kind of gives us permission to examine that.
So, again, it doesn't have to be answered today.
And maybe I'm misinterpreting what you were trying to say there, so I'm open to being redirected, but I just think that this opens up a world of possibilities.
And when I first read it.

1:45:31 _Toby:_
I.

1:45:31 _Dean:_
Don'T know what Ally's Goosebumps looked like, but I was just like, oh man, I really want to ask you about this.

1:45:39 _Toby:_
Yeah, the thing about fuzzy type.
Yeah, so I do got to start by saying I agree that what some of this is seeking is something like thinking clearly about thinking fuzzily in some way is kind of weird.
It's like having some certainty about uncertainty.
But it's definitely the case that still now I think a notion of fuzzy type theory is not well developed, though I am aware of people, various people having thought about this and people thinking about it at the moment.
And of course I've got my own ideas about it, but it seems natural, right?
Like, we often think we know what a thing like we can recognize a thing, but maybe you're not quite sure and so you're not sure if it's this or that or you see somebody coming down the street towards you and you kind of recognize them as somebody you know or you used to know.
And then as they approach that, their identity becomes a bit clearer, but you're not, you know, you weren't sure for a while.
And I think there's nothing to say that we shouldn't be able to in some sense, like types are a kind of element of some bigger space and so we should be able to play all this math to it.
And it's kind of really about figuring out what the rules are that makes the kind of language of type theory kind of align nicely with the language of probability.
And it's a research effort, but I'm happy to talk about it more next time.
I'm also happy to talk in any detail about any of the actual specifics of the stuff in the material, in the thesis or whatever else in category theory you might be interested in.
I'll probably be expert in everything, of course, but I mean, I'm happy to try my best, particularly if Ali, it sounded like your questions were maybe of a more technical nature, maybe not.
I don't know if I got the right sense of what you were saying, but if they are, I'm happy to talk about the details of that.

1:48:06 _Ali:_
Thank you.

1:48:07 _Toby:_
And also to review any of the stuff to try to say, because you're right that there's a lot of detail in the thesis because you make a flame and you're supposed to substantiate it and that means you have to give a proof.
And sometimes the proof is quite complicated.
But structurally, I want this to be simple, or at least to have a simple framework.
And so I would like to be able to clarify some of that if there's time for that, or if it comes to it.

1:48:45 _Daniel:_
Yeah, that sounds amazing.
In two, we will return perhaps any questions that people submit as a comment on the video or as a message in the category theory channel.
On our discord, we'll curate those questions, we'll rewatch and digest, and then we can begin with Ali asking some, taking us on a little bit of a technical journey.
And Toby, thanks again for the incredible work.
It's defined our 2023 in many ways, so it's been a joy and we.

1:49:27 _Toby:_
Look forward to next.
Thanks for plowing through.
There's also the stuff I think we talked about before that we haven't really touched on this time, and obviously I didn't really touch on much in the thesis about how do you actually fit in action into this framework and how do you start to talk about this multi agent stuff.
If there's time, we can talk about all of that.

1:49:53 _Daniel:_
Two of the pieces, just to share, that gave us some of the most laughs were first, we didn't get action and we're like, it wasn't an anti climax, it was a climax of its own.
And and then also we had had so many discussions over the months of time and the treatment of time backwards and forwards, ringing the bell, unringing the bell, all of these different concepts.
And then in your limitations, you said we really have to work on getting a dynamical treatment.

1:50:37 _Toby:_
Oh, yeah.
But I actually think that depending on what you care about, it may not be too hard.
So that's fine.

1:50:45 _Daniel:_
But even that you would say it that way, just having dealt with time and then to be like, well, I thought that's what dynamical modeling was, involving time.

1:50:59 _Toby:_
No, you're right.
You're totally right there.
So all I meant at that point was the kind of statistical framework that I've been working with until then.
It just seems you have a prior and a way of generating predictions, but there's nothing to say that the prior has any data about how stuff actually evolves in time or the predictions have any data about how the Sense data evolves in time.
It's just like I believe that there's this on the screen and that makes there be this stuff coming to my eye and that's it.
It's just like a snapshot.
And so when you want to include time evolution in those beliefs, things become a bit more complicated.
Awesome.

1:51:53 _Daniel:_
Well, thank you again, Toby.
We'll see you in a week and a day.

1:52:02 _Toby:_
It's been a pleasure.
Thank you for having me.
Bye.

1:52:05 _Ali:_
Thank you so much.

1:52:07 _Toby:_
Bye.
