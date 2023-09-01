00:08 _Daniel Friedman:_
All right.
Hello and welcome everyone.
It is Saturday, August 26, 2023 and we're here in “Physics as information processing,” in the fourth discussion.
Thank you everybody.
Who's joining live or watching?
Live or watching in replay.
This should be a really fun discussion as usual.
So we're going to have Ander provide some slides and some initial clarifying questions for Chris and then we're going to open it up for our guests to ask some questions and check in a live chat, see what people are talking about.
So Ander, to you for some slides and overview.

00:48 _Ander Aguirre:_
Okay.
Thank you, Daniel.
So last time we were starting to talk about multi agent communication and lock protocols and all of that.
So let's quickly go through the slides and sort of try to recall the main concepts.
I guess just to go back to session three for a second.
One takeaway was that when you have non committing sectors in a boundary, that's necessarily going to require classical communication between them.
So that is more or less the whole point of today, how noncommittan sectors may communicate, have to communicate classically.
Another introduction in this last lecture was this new graphical notation, TQFT, if you wish to call it that way for any of these clock ticks.
Okay, so let's recall the whole process of measuring a sector environment and writing it into a memory environment can be simplified to this sort of tick that connects two portions of the boundary and everything we talk about lock protocols will be written in this graphical notation.
So let's keep going a little bit.
This slide is on the paper on sequential measurements from 2022.
These are basically the formal mapping between QRFs and topological quantum field theories.
Okay.
So we're more used to the picture here on the left hand side of this slide, right with the QRF sectors.
But pictorically speaking, this is at least how they map.
Okay?
And then from then we started talking about entanglement and classical communications using this notation.
And this is probably where my questions to Chris will start.
So in section Three, we saw this idea of the FEP asymptotically being the principle of unitarity, aka.
Driving the system, the joint system, Alice and Bob to entanglement, which in this graphical notation, amounts to them sort of completing a cycle here where the QRFs are perfectly aligned, so that the S sector of one becomes the memory sector of the other.
And vice I actually at this point already, I have a question for Chris.
I have it written down.
Yes.
Two things here, Chris.
Number one is in the log protocol picture we do have a distinguishing between a quantum channel and a classical channel.
And if I understood that part correctly, we said that passage of time or expenditure of energy, free energy only corresponds to the classical tick.
So in this quantum entanglement picture where you don't quite have that, is it fair to say that there's no such thing as a classical take no passage of time, no expenditure of free energy.
Is this a degenerate picture of the locked protocol where the sectors were aligned the right way and boom, you got rid of that classical thing and that's it.
And secondly, I guess, what does it mean for these two parts, quote unquote from the paper, to implement a joint quantum process?

04:59 _Chris Fields:_
So, yeah, this is not a lock protocol, clearly, because there is no classical communication.
And in fact, Alice is not divided into multiple compartments.
Here Alice is just implementing this single quantum process, Q.
And because these sectors are because these QRFs are perfectly aligned, we can think of, remember from probably the second session the picture that you were very interested in under of the Wick rotation reversing time between Alice and Bob.
So Alice's clock in fact ticks in the opposite direction from Bob's clock because both of their internal clocks are counting incoming bits, not outgoing.
In this, in the right side of this picture, there is no overall time.
You can think of Alice's clock ticking forward one unit and then Bob's clock ticking backward one unit.
So that the information flow is completely time symmetric between Alice and Bob.
So we can think of both of these processes, q and Q prime, as bi directional in time.
That's what it means to have a pure unitary process.

07:18 _Ander:_
So no time asymmetry.
That's what it is.

07:20 _Chris:_
Right.
So there is no time asymmetry in this picture.
And when you introduce classical communication, of course you have to have a time asymmetry.

07:30 _Ander:_
Right.

07:30 _Chris:_
Because you have this I mean, classicality is defined by this notion of irreversibility.

07:38 _Ander:_
I see.

07:39 _Chris:_
Which is just the same as time asymmetry.
And it's the irreversibility that burns energy.
So there has to be energy flow between Alice and Bob to drive what is from a global point of view and only an apparent asymmetry, but from the point of view of Alice One and Alice Two as components of Alice, they're the ones who see the asymmetry.

08:21 _Ander:_
So I guess just to tie back to the question of the week rotation, once this joint process is implemented naively, one can say is this cycle going clockwise or counterclockwise?
And is that going to define on originally whenever these guys ended up being lined up where the weak sign was coming from?

08:51 _Chris:_
Yes.
Whenever Alice sees information flowing in, Bob sees information flowing out.
So their WIC rotations are going in opposite directions.

09:06 _Ander:_
Okay.
Yeah, very good.

09:12 _Chris:_
The other thing to think of in this picture, Rich, it's impossible to draw all of these simultaneously, is that if you think of the FEP as fully aligning Alice and Bob, then not only do these processes perfectly couple, but the area that's green in this right hand side kind of expands to fill the whole boundary.
So that in the complete limit of Alice being able to perfectly predict Bob and vice versa, then the whole boundary is green.
So there's no this distinction between the S sector and the Y sector disappears.

10:12 _Ander:_
Yes, that makes sense, actually.
And just to conclude with this slide, back in the session two, we saw something about agents requiring a free choice of reference frame for their QRFs, which amounts to being able to choose how to measure a spin.
Right, right.
So is part of this entanglement picture, do they just have to align the sectors or also the way they are measuring a spin on those sectors?

10:43 _Chris:_
Yes, they have to align the way they're measuring the spin in those sectors.
It's that lack of remember the point that free choice of local reference frame is required for separability.
So as the systems become fully entangled, then their local reference frames for each qubit become the same.
Become necessarily the same.

11:25 _Ander:_
Thank you.
Okay.
And then let's continue a little bit.
So in this talk, we're mainly interested on QRFs that do not commute.
Now, maybe, Chris, you can tie this back to what you were saying earlier about if you're perfectly entangled, then the sector is going to grow.
Does it have anything to do with this?
So if Q one and Q two here do commute, then how do you reduce this to the picture on the right hand side?
At the first glance, it looks like the picture on the left hand side encompasses more sectors of the boundary.

12:07 _Chris:_
Yeah.
The point here is just that if we go back and go back to the notation where what we're representing by this simplified notation is a collection of cocon diagrams, and if these reference frames commute, then one can take these two diagrams and find a think of it in the information inflow direction.
There will always be a common cocon over the two sets of input classifiers if the two QRFs commute.
So what that means is that I go from a diagram with two sets of classifiers, each going up to some apex, to a diagram with the merged set of classifiers going up to some farther up the hierarchy apex because they commute.
I can find that sort of yet more abstract coconut that covers all of the classifiers in both QRS.
So that just collapses these pairs of green segments down to one green segment.
And I've drawn it the same size.
I mean, it would make more sense graphically, I suppose, to draw it.

14:05 _Ander:_
Right.

14:05 _Chris:_
Each one is twice as big or twice the area.
But keeping to this kind of very topological representation where the area isn't actually meaningful, it is convenient to draw it this way.

14:26 _Ander:_
Right.
So in short, commutative the fact that they commute means that you will have that higher apex anyway.
So you can bypass that first nesting.

14:35 _Chris:_
Right.

14:36 _Ander:_
But it comes to the number of degrees of freedom at the boundary.
They're still the same.
And in terms of area right, okay.

14:44 _Chris:_
Yeah.
We're not getting rid of any of the degrees of freedom of the boundary that these QRFs are looking at.

14:53 _Ander:_
Yeah, very good.
So the next slide I found a very interesting one.
So these are no Go theorems things that Alice and Bob cannot do, and it's mainly having to do about measuring their own entanglement entropy and counting degrees of freedom.
I guess this has a very holographic feel to it, and also maybe even a bit of a Goddess theorem feel to it.
So I don't know if Chris wants to comment on that.

15:27 _Chris:_
Well, I'll just say that I think this does have a kind of girdle undecidability feel to it, in that there are a large number of questions that Alice can't answer, which certainly suggests a formulation in terms of incompleteness.
And the connection to Gertle's theorem is actually something that Jim Glazberg and I are currently working on, and hopefully we'll be able to make that connection more precise.
But the point of these statements is just to emphasize that a single observer that's uncompartmentalized cannot determine anything about the entanglement entropy of the environment.
And this is just the result that to measure entanglement, you have to employ a lock protocol.
So you have to have classical communication.
And this raises a fundamental issue in the theory, and that classical communication is an exchange of information that cannot be represented as a single quantum process.
Hence, you have language like the collapse of the wave function or these various other decoherence, et cetera, et cetera, these various ways of trying to capture this idea that something different and irreversible is happening as soon as you talk about classical communication.
So the point is, for Alice to measure anything about the entanglement entropy of Bob, she has to be sectored.
So her entanglement entropy has to decrease, but she can't know that.
She can't actually know that she has sectored compartments when we think of Alice as an entire system.
So from now on, we're going to be talking about the very limited points of view of particular observers.
And to talk about that.
I think it's very important to keep these various limitations in mind, because there's a real distinction between what we can say effectively from this kind of God's eye point of view that we're adopting.
As theorists where we say Alice has sectors that are communicating classically and what Alice's system can do from her point of view or her sectors can do from their points of view.
And this is a distinction that's often ignored, but it's important to keep it in mind.

19:17 _Daniel:_
Awesome.
Thanks for this line ender.

19:21 _Ander:_
Yeah.
So should we continue?
Yeah, then I guess we get to the proper material of the last lecture, which is what happens when you have sectors that are commutative, such as two portions of Alice involved that have to communicate classically.
This is what requires the classical communication tick.
Let me see.
So would it be fair to say, Chris, this only such a classical channel, such as the one shown in this slide requires free energy.
Is that right?
Because there's some writing into a memory involved in here.
Compared to the earlier slide where we had that closed loop in the entangled picture, there was no expenditure of energy.
Is that.

20:27 _Chris:_
The the example to keep in mind here is exactly the process that we're executing right now.
Alice has two components, and we are currently in the position of those components.
And we're communicating classically with each other by employing a channel that's part of our shared environment.
So we are acting irreversibly on our shared environment.
And it's that irreversible action on the environment that has the free energy cost for each of us.
We actually have to make noise to communicate, and our laptops are actually consuming power.
All of this is classical.
It's this irreversibility that defines classicality.
Right.

21:45 _Ander:_
And to continue with this question, I guess it will come ensure in later slides.
But the other side of this lock protocol is the quantum channel.
And my question to you, Chris, is just like there is an expenditure of time and energy involved in this classical channel, is the quantum channel basically the opposite of that meaning its action is instantaneous entanglement, presumably.
And also, again, back to that loop picture of entangled cycle, is there just no passage of time, no expenditure of energy?
Does any of that make sense?

22:28 _Chris:_
Yeah.
And I think it's worth actually going to the next slide here where we complete the loop and add the quantum channel.

22:39 _Ander:_
Is it this one?

22:40 _Chris:_
Yeah.
I think to understand what's going on here, I think it's very useful to think of it in terms of a Belly PR experiment, right, where Bob, in this case, the shared environment includes the source that's creating the entangled pair, which a one and a two observe simultaneously.
They interact simultaneously with their two detectors, which are interacting with the entangled pair.
So you can think of their two detectors are entangled, and it's only later that they exchange this classical information.
And in a Belly PR experiment, the elapsed time between the source emitting the entangled pair and the entangled pair interacting with the detectors deployed by a one and a two is designed as part of the experimental protocol to be less than the time that it is required for a one and a two to communicate classically.
And notice that from the point of view of the entangled pair itself, no time has passed at all.
Right?
The entangled pair is, from a special relativity point of view, moving along a light like trajectory.
So there's no distance being traversed and no time is elapsing.
From the point of view of the entangled pair, there's only an elapsed time and a traverse distance in the coordinates of the observers.
And it's those coordinates that define the parameters for the observer's eventual classical communication.
So this is why I characterized the assumption of classical communication as a stipulation and also why I characterized it as a fine tuning assumption.
We are assuming something very specific about this communication channel, and we're assuming that the part of Bob, the part of the shared environment that implements this classical communication channel, behaves differently from the rest of the shared environment.
It behaves in a way that is classical, but the rest of the shared environment doesn't.
Right.
The rest of the world is described using quantum theory.
So we're making this assumption that part of the shared environment is special, and the specialness is that it behaves in this classical way.

26:22 _Ander:_
So let me finish with this slide.
I suppose to go back to my earlier question about that Entangled loop being at least Pictorically appears to be like a degenerate version of this log picture.
If in this log picture I have the quantum channel on the right, that hypothetical entanglement to complete the cycle on the left was only broken when a one and a two chose to write that into their memories at different sectors.
Right.
And then that eventually necessitated the classical communication between them.
Is that correct?

27:03 _Chris:_
Yeah.
One could always take the point of view of, if you will, the observer who's outside the entire universe and just sees the entire universe evolving unitarily.
And from that point of view, there's no such thing as classical communication.
So the communication is classical only relative to this division between the Observers.
And that division between the observers corresponds to their measurement procedures, not commuting.
So it corresponds to what we think of classically as Alice acting on her half of the entangled state, determining what Bob will, then that all of that causal language is classical.

28:14 _Ander:_
Right.
We're like at 1130.
So halfway, more or less, let's say a few words on the later slide process and all of that.
I guess before we start talking about this, which will take us like five to ten minutes at most, could you say a few words again about the fine tuning assumption?
So I still can't quite understand what is meant here, that this whole classical communication stuff requires fine tuning.

29:03 _Chris:_
Okay.
I think a way to think about it is to think about what it means to say that Alice and Bob are able to communicate classically.
What we're saying is that Alice and Bob share some sort of language.
So when they exchange their data, we can think of their data as written in some binary code in a data.
Alice says, I set my instrument this way and I saw this spin.
I then set my instrument this other way, and I made this observation.
So Alice, his data table, or a one's data table, is just a long table with two entries in each row.
One entry is how the detector was adjusted, and the other entry is what the value of the spin was observed.
And Bob's data table looks the same.
And so they share this information, or they share it with some third party, they communicate it classically.
And there are two aspects to that classical communication.
One is that up to classical noise, their data tables don't change when they share them.
So they really are irreversibly recorded.
They're not evolving in time along with the rest of the universe.
The other aspect is that we have to assume that Alice and Bob mean the same thing by their notations in these data tables so that they can actually compare them, so that they can actually do the statistics and see if they've violated Bell's inequality.
So what that means is we have to assume that they actually share a definition of up, and that when they talk about changing the settings on their instruments, they're talking about changing those settings with respect to some shared definition of, you know, in a real experiment, that shared definition of up is provided by the Earth's gravitational field or something like that.
Earth's magnetic field, some shared environmental variable.
So now it seems like we have a situation in which Alice One and Alice Two should be entangled because they share this reference frame that enables them to communicate classically, but they can't be entangled if they're going to communicate classically.
So we make an assumption that in just this case, they share a reference frame, but they're not entangled.
They're able to communicate classically while sharing the reference frame.
And we can sort of wave our hands and say they only share the reference frame up to some measurement resolution or something like that.
But despite the hand waving, we're making a very specific assumption that violates the fact that reference frame sharing induces entanglement.
So that's the fine tuning assumption.
We assume that the universe is such that in this very specific kind of case, we can have reference frame sharing without entanglement.

33:33 _Ander:_
Cool.

33:35 _Daniel:_
Let's keep it here and just open it up a little bit if Haris or Dean want to just give any thought or reflection on what we've gotten to so far.
Haris, if you want to, please.

33:51 _Haris Neophytou:_
Yes.
Everything is very interesting.
Basically, I was listening with great, let's say focus.
It reminded me this, let's say, elaboration on the previous talk that Chris gave two weeks ago.
It reminded me something that Michael Levin said some time ago.
It is regarding this amazing ability of cognition to scale up.
So it's not only this understanding, let's say, of the scattering of cognition, but also the scaling up of cognition.
And when I tried to get inside my head, actually, that as Chris said in one of his talks, that if a system is a tag wall, one cannot draw a meaningful boundary across it.
So this fine tuning, let's say elaboration that was made right now actually helps me understand that even better.
So thank you, Chris, for that and thank you Ander for this.

35:14 _Chris:_
Thank you.
Thank you.
I'm glad that helped.
Yeah, I think this is intimately related to the question of what cognition is since if we have a purely quantum system, there really is a deep sense in which nothing is happening because of the time symmetry.
So to talk about cognition as something that actually occurs, we have to think of it classically.

35:55 _Haris:_
Thank you.
Also, if you allow me another comment on that, basically one of the comments posted during your last talk in the chat had to do with classical memories.
And I was thinking about that and I came to the conclusion that classical memories presupposes a gestation period.
And when I think about it, that actually makes sense.
And it is true, let's say, for both physical and psychological reasons.
So, for example, a hard disk needs to write data on its magnetic surface and a human brain needs to consolidate all those neural connections through synaptic plasticity.
Let's say.
However, when we start thinking about quantum information and quantum memories, let's say we realize that such memories will be such quantum memories basically will be stored in qubits or in those entagle states that you describe.
So they do not necessarily have the same limitations.
And of course, quantum information theory suggests, as I understand it, that quantum memories can be created and accessed instantaneously without any form of ingestation, let's say without any ingestation period.
And of course this goes back and it has the potential, as I see, to revolutionize computation in terms of quantum computation, but also, and most importantly, communication and quantum cryptography even.
And this is something that I am truly interested in.
So yeah, I just wanted to share also that.

38:03 _Chris:_
Yeah, that's a very good point.
And the flip side is the issue of stability which again gets to the notion of environmental decoherence which is just the process of observation of the quantum state by some environment or some observer, some component of its environment.
And the reason this is a problem in practice is that we don't have complete control of all components of the environment, right?
So we have to use things like liquid helium to try to keep the environment at bay to prevent decoherence because any other components of the environment interacting with our quantum memory will alter the state of the memory.

39:16 _Haris:_
Yeah, that is a great answer and basically the reason why I typed that question.
Regarding super selection rules, and namely me, I propose something called fuzzy super selection rules.
Basically, as I understand it, those super selection rules, the classical ones, let's say they are based on symmetries or on all those conversation laws that actually limit the accessibility or our capacity to measure, let's say, certain quantum properties, let's say, maybe it's parity, maybe it's angular momentum, maybe it's even charge.
But if we start thinking like these fuzzy super selection rules in an effort to relax these restrictions by allowing some degree of coherence or interference between the different super selected sectors, which can be quantified, let's say, by a parameter called fuzziness.
I know that in other fields, like in my field, that is fuzzy cognitive mapping, the introduction of fuzziness from as it was propounded by Professor Lotfield Zadek, it actually helped a lot of our models to become more accurate, let's say.
So this is what I am proposing.
Maybe of course, I don't expect it to revolutionize quantum information, but maybe it can help us understand a bit better what is going on and the role of the coherence that comes out of the environment.
So if we incorporate it as a parameter of fuzziness, a priority, then maybe we can understand and even what we are dealing with.

41:18 _Chris:_
Yeah.
I would refer you to the paper by Bartlett.
There are two other co authors in 2007, a lovely review of quantum reference frames in reviews of modern Physics.
And a point that they make that I think is relevant here is that a super selection rule can always be interpreted.
Let me see.
I'm not sure I'll be able to completely reproduce their argument, but they show that a super selection rule can always be interpreted as the absence of a reference frame or the lack of a reference frame.
And one of the examples that they give is charge conservation, that we never see superpositions of different electric charges.
And their point is we never see this because we have no way of measuring it.
We have no reference frame that we could use that would allow us to see a state of superposed charges.
And effectively what they're saying is our reference frames are all made of matter that is composed of stuff that has well defined electric charges.
So we can't see things that are superpositions of charge.
And it's very difficult for us to see things that are superpositions of position.
So this question of what is a super selection rule, why do we have these rules, at least in their reasoning, boils down to the question of why do we have some reference frames or some measurement capabilities and not others?
What is it about us that limits in some fundamental way our ability to make measurements?
And I suspect that when you talk about fuzziness, which is a sense of classical uncertainty, that you may be sort of pointing in that direction, but I think it would be worth looking at that paper, which is largely written in English, right?
The formalism is kept in the background.
So it's a very nice paper.

44:35 _Haris:_
Thank you.

44:38 _Daniel:_
Thank you.
Andrew.
Maybe mute a little bit.
Dean on the Mountaintop, what can you throw down on us?

44:51 _Dean Tickles:_
I don't have anything super special throw down.
I have a question, though, and because I am very comfortable in that fuzzy space, I kind of see relationships and their lack of definability as a feature.
So here's kind of my question.
So you talked about a minimum sort of two different memories to encode something in time.
And I think it was one of the slides just after the one that's up here right now, which sounds to me like somewhere processing capacity.
It sounds like we are kind of stepping back and trying to look at this instantaneous thing from the relative position of even the things that are classical can be seen as all.
So that when you mentioned that earlier, Chris, that helped me quite a bit.
Which then manifests itself as a classical ability to process somewhere.
I spent a lot of my career self labeling as a wayfinder.
So not capacity realization, relationship.
Just as a relationship.
It means that wayfinding is not just an orienting or a processing where I am and being gripped by sort of the thing that I'm enveloped by.
It's also the channel, the screen, the bound, the divide, the gap, the unentangled potentiator.
It's the thing upon which traction can exist as being a gripper as well.
I was already hung up on I wanted to go back like Colombo in that old 70s TV show and talk about Z spin because I think Z spin is an energy way of describing.
But I honestly think when I went back and watched your presentation a couple of times, I'm starting to get a sense that Z spin is also relationship it's that affordance, that allows us to be able to see up and down.
But I'm just curious, Chris, are we really talking about processing somewhere in the classical sense, but because we have these two ways of encoding different memories, we're also talking about somewhere processing just that state that allows for that's.
My question is that what we're really getting, are we trying to open that up, that possibility up?

47:28 _Chris:_
Yeah, I think that's a nice way to think about it.
I think we're trying to, at some deep level come up with a way of describing what it means to be an agent.
And I'll say in our case, a self conscious agent with a sense of time that's embedded in an environment that we depend on to store memories for us.
And what I mean by that is that we depend on the environment to change very slowly, at least from our point of view, so that we can keep some sense of our orientation within the environment.
Right.
We're using everything we see as a memory that allows us to keep ourselves fixed, which allows us to have a point of view.
So we're using the entire visible environment as, if you will, a reference frame against which we can see small changes.
But if the environment was constantly and rapidly changing, we wouldn't be able to do that and we wouldn't be able to use it as a memory and so we would have no point of view.
So in a sense, I think what we're talking about here is the miracle of having a point of view that gives us a sense of time.
That's very philosophical.

49:48 _Daniel:_
It's amazing.
And I wonder if along with the perspectival visual advancements which you and.
Shannon Dobson have explored.
In the math art settings.
You're almost bringing that kind of a transformative re understanding or re quantum reference framing into a temporal setting where it's not just a static spatial parallax that we are aesthetically and formally re understanding.
But also a temporal one, which, in an agent environment system, necessitates these questions of communication, which, in the quantum information formalism, are approached topologically rather than geometrically, which is what we needed for the kind of vanishing point type math art in the spatial setting.

50:50 _Chris:_
Well, I think they're approached geometrically eventually and that's really what the session in September will be about.
It's how to start with this very topological picture where we're only talking about interactions in a sense, interactions in time, but outside of space and layer a spatial structure on top of that.
And I think this is particularly interesting in this active inference context because it immediately raises biological questions about the ability of different organisms to layer space on their experience and hence locate themselves, if you will, within some sort of perceived world.

52:00 _Daniel:_
Awesome.
Dean and then back to Ander for the last minutes.
Oh, wait, unmute.
Dean and then please continue.

52:13 _Dean:_
Sorry.
So, Chris, is it from the pure neophyte perspective that I have, is it OK to say that it's not just a flipping of position of words, that somewhere processing, that availability and processing somewhere in the classical sense, where am I?
It's our ability to fuse those, as you mentioned, we can slow down, we can stabilize, we can see that relationship.
Or is it about spinning?

52:59 _Chris:_
I think the former, right.
Spin is a very convenient abstraction for talking about binary encoding.
And we have this felt sense of spin, but its use in physics is very much an abstraction.
I mean, the difference between a proton and neutron is a spin variable.

53:32 _Daniel:_
Awesome.
Ander you can in the last minutes take it where you need also unmute and then continue.

53:46 _Ander:_
Can you guys hear me now?
So let's hope that I have time for Chris to address a couple of things.
So just to conclude the slides and then hopefully we get to say a few words on quantum Darwinism.
So towards the end, the slides appear to start pivoting towards the next subject, which is space and time.
And here in particular, we see the earlier slide showcasing the Lock protocol where you can notice that half of it has been cut and has been moved to the future.
So here we don't have two sectors of Alice communicating, but rather Alice communicating with its future.
Still, you have the classical and the quantum channel.
Now, one question that I brought up, I remember and in the lecture, and maybe we can expand on a little more, was exactly what is the difference between this quantum and the classical channel part?
Something I heard Chris say is that it is crucial for the quantum channel to be recohered.
So this is going to be some sort of unitary scattering evolution that is completely independent of everything else going on.
Is that correct or should be?
In theory.

55:13 _Chris:_
Yes.

55:15 _Ander:_
And I suppose, just like earlier, the classical channel is the part that takes time and free energy expenditure.
Now, my question to you, Chris, is not the channels in the middle, but the ticks on either side of the boundaries that have been broken down and separated in terms of an external time.
What's up with those ticks from one sector to the other of the boundary?
So in Q one, for example, the lower TRF sector, that's that amount to a state was prepared.
The upper one was I made a memory record of that state.
That's what it is, right?

55:59 _Chris:_
Yeah.

56:00 _Ander:_
Okay, so in the lower sector, we both had a preparation and a measurement, and a measurement was recorded classically here.
That's all there is.

56:14 _Chris:_
Yeah.
So preparation and measurement are effectively the same process.
And you can think of in a one of T, what a one is doing is, from an operational point of view, she's preparing an instrument and turning it on.
She's creating an initial state, and she's simultaneously encoding a memory someplace in her head or on a piece of paper of what those preparation conditions were, because it's only with respect to the memory of what the preparation conditions were that the later measurement is meaningful.
Let's go back to just preparing a spin.
Right.
At T, she may set the angle of some polarization filter that defines a propagating beam of photons.
And at T plus delta T, she measures something about what those photons are doing.
But the measurement is only meaningful with respect to her memory of what the polarization setting that prepared the photons was.
So effectively, what's going on in the quantum channel is an experiment, and it's the classical information that's preserved in this classical channel that makes the experiment meaningful or interpretable or informative.

58:33 _Ander:_
Yeah, for sure.
Yeah, that makes perfect sense in preparation of measurement.
This ties back to an earlier question we had both happen simultaneously at the same degree of freedom at the boundary, or do we have preparation at the lower bound measurement at the top of one?

58:56 _Chris:_
Yeah, one can think of that operator, Mi, if you remember the decomposition of the Hamiltonian as preparing or measuring.
It's just a matter of interpretation effectively.
Is it acting to the left or acting to the right?

59:18 _Ander:_
Yeah.
Okay.
Yeah.
Makes perfect.
And then before we get to quantum error correction as more of a special instead of a time thing, I wanted to ask about yet another question between this one.
So the quantum channels does involve some sort of time evolutionary portion, that is, this portion that is evolving unitarily with no interference from the outside.
However, as you said, for this experiment to make sense, you need to have a classical memory of how that experiment was prepared so that means that that classical guy on top is static.
There's no time flow in it.

1:00:07 _Chris:_
Well, this actually gets back to the talk by Suskin that we were talking about before we started here that you kindly referred me to.
Part of this classical memory is memory for what counts as a classical clock.
And we'll actually get to this again in the September session.
But if you think again about doing an experiment in which a state is prepared and then it's measured, this quantum process is a process through time with respect to some classical clock that actually provides the time coordinate for the experiment.
So this classical clock is some external reference frame that a one here in this notation is using as part of her classical memory.

1:01:25 _Ander:_
Right.

1:01:25 _Chris:_
Again, it's a memory because it's something that's assumed not to change.
This will be kind of the heart of the discussion in September that time and memory and object persistence are all different names for this same assumption that we make about the world.

1:01:57 _Daniel:_
Thank you, Chris.

1:01:59 _Ander:_
Thank you.

1:01:59 _Chris:_
I am going to have to so.

1:02:03 _Daniel:_
Only for now though.

1:02:05 _Chris:_
Yeah, only for now.
I will nonetheless persist someplace.

1:02:11 _Ander:_
Thank you, Chris, so much, Chris.

1:02:14 _Chris:_
Okay, awesome.
See you.
Thanks very much.

1:02:19 _Daniel:_
Measure you later.
Andrew, if you wanted to drop any other cues or clues or bring us a little bit of a preparation for where we're going to be heading in lecture five, that would be pretty cool.

1:02:43 _Ander:_
Sure.
So, I mean, I'm a little aware of what's coming in lecture five.
It's about space and time and how space may be sorry, time may be a little more fundamental than space for reasons that Chris will show has a lot to do with the notion of how you define a clock.
As in we need to think hard about what are the bare minimum ingredients for you to talk about the existence of a clock.
These are deep, fundamental, almost philosophical questions that are overlooked.
And the good news, and that's the Saskin talk that Chris and I were referring to is that other people, especially in the high energy community, are also looking into these questions, which is very reassuring.
So I'm talking at Wheaton, Suskin, Harlow, Et are there is a recent talk on YouTube where they talk about what does it mean for something to be a does, how long does a clock last?
And then Chris will also talk about space.
And the punchline of it will be that there's obviously a physics approach to emergent space time, which is very technical and so on.
But from what I understood, I have yet to see the talk myself first is that there is a parallel biological approach as to how we learn out spacetime.
So from developmental psychology point of you infants, and I suppose all kinds of animals are not Born fully equipped to perceive spacetime.
Hence the necessity of things like play and so on.
So they can find correlations between motor inputs and visual inputs, right?
And eventually things like the mirror test, which is nontrivial.
No human is Born passing the mirror test already.
So that implies that at least biologically, it is nontrivial.
And it takes a few steps until you get to have that sort of spatial awareness.
Right?
Now, the interesting part, at least for me personally, is what the physics side of it is.
And I'm no expert by any means, but I think the gist of it might have to do something with quantum error correction adseft and so on.
There was a bit of a teaser about quantum error correction here in these.
Yeah, I mean, that's that's about all I can say.
But very looking forward to the biology also.

1:05:37 _Daniel:_
Yeah, cool.
Haris any last thoughts or anything you want to point towards?

1:05:46 _Haris:_
Basically, I would like to thank everyone for inviting me.
I really enjoyed it the whole Livestream.
I hope we have made some progress and looking forward to the next live streams number five and number six.
So that's about it.
Thank you, everyone.

1:06:14 _Daniel:_
Thank you.
Anything else?

1:06:17 _Ander:_
Andrew that's it.

1:06:19 _Daniel:_
Awesome.
Well, I encourage everyone to go to the syllabus page, look ahead, look back, prejust digest, regest, ask questions and end.
Let's make progress as you exhort.
Haris so, see you all.
Till next time.