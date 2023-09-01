00:07 _Daniel Friedman:_
Hello and welcome, everyone.
This is physics.
As information processing session four on communicating observers.
It's the 10 August 2023.
Chris looking forward to this lecture.
Off to you.

00:23 _Chris Fields:_
Thank you, Daniel, and welcome to this session.
As Daniel said, this is about out communicating observers.
And fasten your seatbelts because we have a lot to cover in the next hour.
So just to do a quick review.
We've been talking about quantum information theory and we've been talking about it in the simplest possible setting of two systems, Alice and Bob, that exchange information through their mutual boundary.
And we've assumed that everything is finite dimensional.
So we don't need to worry about infinite energy transfer across this boundary.
And of course, we assume conservation of energy so there are no sources or sinks in either of the systems.
Alice and Bob and we emphasize that this way of depicting things as topological we're not assuming any background geometry, no sort of spatial embedding which is going to become very important in this session.
In the last session, we talked about how the boundary, which I'll always call B can be thought of as a channel that comprises N qubits that are independent.
And Alice and Bob each can prepare and measure those qubits and they can always choose independently their reference frames for doing so.
So how they define up and down when they're measuring a spin with effectively a Zspin operator.
To interact with these qubits.
We talked a little bit about the free energy principle and its quantum formulation.
And the principle basically says that interacting systems will behave in a way that aligns their reference frames and that they therefore asymptotically approach entanglement.
So the FEP is a classical limit of the principle of unitarity.
And that's one reason for studying quantum information to learn more about the FEP and so to learn more about active inference and what the theory of active inference says about agents.
And last time, we talked a lot about the constraints that are imposed by a limited free energy supply on any agent.
Recall that we talked about the fact that in the absence of sources of free energy within an agent so as long as you conserve energy globally that the free energy that each agent uses has to come from its environment.
That's clearly true for us.
We have to consume oxygen and eat food and things like that to keep running as systems.
And we discussed a little bit this theorem that if two reference frames or quantum processes, q One and Q Two don't commute, they have to be implemented by compartments that communicate classically.
And we'll use this extensively today.
But the bottom line last time was that physics alone gives us compartmentalization in systems whenever the systems are complex enough to have multiple kinds of measurements that they can't deploy simultaneously.
So where we're going today, we're going to start from this place we left off last time of the possibility of agents that are compartmentalized and into compartments that have to communicate classically.
So we're going to talk about agents that can be compartmentalized into multiple subagents that share an environment, the environment consisting of Bob and how those agents talk about that shared environment.
So the motivation for this is simple.
It's that what we do all the time is a group activity.
And what we're doing right now is a group activity that involves sharing an environment.
What's shown on this screen and talking about it.
And the whole post session discussion process will be another example of just that sort of thing.
So to talk about science at all or to talk about any kind of social relations or to talk about anything other than solipsism, we have to be able to talk about how multiple agents communicate about some shared environment.
And so that's what we're going to develop a formal way of talking about.
And there are two things to notice right off the top about this.
One is that the way we've defined interactions at boundaries, they're effectively instantaneous.
So each agent, remember, interacts with its boundary with some set of operators.
And what those operators do is effectively measure each operator effectively measures the spin of a qubit.
So this is a very fast process.
The other thing that we then need to notice is that if we have two agents and they're communicating with each other classically, then they're going to be using degrees of freedom of their shared environment in order to communicate.
And that's exactly what we're doing right now.
For example, we're using degrees of freedom of the Internet to communicate.
I'm using degrees of freedom of the local atmosphere to talk to my microphone and I'm using degrees of freedom of the local photon field to see my screen.
So all communication between agents and certainly all classical communication between agents uses degrees of freedom of the environment.
And the environment, remember, is the other system, Bob, that's on the other side of that shared boundary.
So we're going to be interested in how components of Alice use Bob as a communication channel and in fact, as multiple communication channels.
And I just wanted to quote my colleague and friend Mike Levin in his statement that all intelligence is composite.
All of us, all organisms, even single cells, are composite systems that comprise many different agents that are able to make different kinds of measurements and execute different kinds of actions and so have to communicate classically.
So we're talking about all of life here as well as all of social systems and ecosystems and such things as that.
So the first thing I want to do today is simplify the notation so that we don't have to draw quite such complicated diagrams.
So the picture on the left here is a picture from the last session.
It shows the structure of a very simple agent that makes some measurements using a reference frame called e and then writes some results of those measurements to memory using a reference frame called y.
And those two processes are connected by an internal clock that ticks between the input process and the output process.
And the clock tick corresponds to the expenditure of free energy to write information irreversibly on the boundary.
So the memories are actually written on the boundary because that's where classical information lives in this theory.
So you can think of this whole process from e through the clock and back to y as a single quantum process or as a quantum computation that maps some sector e of the boundary to some sector Y of the boundary.
And so we can represent it in this much simpler way that's over on the right side as some process Q that maps some sector on the boundary to some other sector on the boundary.
And formally, that process can be thought of as a topological quantum field theory.
Topological here is important.
It's not geometric, it doesn't assume an embedding in space and this will become critically important later on.
And the operation of that tqft requires a clock tick or it incorporates a tick of this internal clock.
And we can do this because we were able to prove jim Glazeburg and Tanino Marciano and I were able to prove last year that we can always represent a quantum reference frame as a topological quantum field theory.
And this just illustrates the two kinds of transformations between quantum reference frames that are important.
We can take one and divide it into two pieces that commute or we can take a two part reference frame and we can swap in another part that doesn't commute with the part that we've swapped it in for but that does commute with the remainder of the reference frame.
So here R is the reference component of some object identification system and we can swap in some different way of looking at the object once we've identified it.
So, for example, if the object that we're identifying is a box that can measure both Z spin and X spin, then P and Q can be the z spin and x spin settings on that box that allow us to effectively rotate the filter from this way to that way so that we measure vertical spin versus horizontal spin.
And that's really it.
I mean, those are the ways that one can transform quantum reference frames.
Of course, we could do arbitrarily many compositions of this kind of transformation to do something very complicated, but they map very simply to tqfts with the structure and you can construct categories out of this and find a function that's well defined that maps one category to another.
So it's an example of a nice use of categorical techniques for solving a problem that looks difficult but in fact it's very straightforward.
So using this simplified notation, it becomes very easy to see that if we have two systems, alice and Bob on opposite sides of this boundary and we perfectly align their quantum reference frames, which is what the FEP says they will tend to do, then they become entangled.
And you can see that they're entangled by seeing that once the reference frames are perfectly aligned, they jointly implement one quantum process.
And jointly implementing one quantum process just means you're entangled.
The two sides no longer have conditionally independent states.
If one quantum process, which is time reversible, information preserving, is implemented jointly by the two systems.
So a lot of things like this become very simple when we think of these processes as just quantum computations going on inside some system implemented by some system and how those processes relate across some boundary.
So that's what we're going to do for studying communication today.
Another thing to recall from a couple of sessions ago, our last session, is that if two reference frames, q one and Q Two commute, we can always join them together to form a single reference frame.
And this is just a graphical depiction in this simpler language of how that works.
And topologically, there's no distinction between the left side and the right side.
What I've done is just squeeze the top two green circles together and the bottom two green circles together into one circle.
And that just makes a simple process connecting the top one to the bottom one.
So what we're going to be interested in is situations where this doesn't happen, where Alice consists of two components that execute reference frames that don't commute.
And so the two components are conditionally independent.
They do each have free choice of reference frame.
And so they have to communicate classically.
They don't share a single quantum process, so they're not entangled.
And before we go ahead to do that, I just wanted to remind you of some of the no go theorems that follow from this situation depicted on the right, where we have a single agent executing a single reference frame, a single process, a single kind of measurement, any set of commuting measurements that can be combined into one measurement.
And here are some things Alice can't do.
And we've talked about some of these previously.
So this is basically a reminder.
But Alice can't, using just one measurement, measure the entanglement entropy across her own boundary.
So Alice can't know that she has an independent state.
She can't know that she's not entangled with Bob.
And that's a useful thing to think about philosophically as it applies to you and me.
We can't actually know that we have independent states.
Alice can't measure her own entanglement entropy, so she can't know whether she has components that have to communicate classically.
She can't measure Bob's entanglement entropy, so she can't know whether Bob has compartments that have to communicate classically.
And if you think in terms of perception theory, this says Alice can't know whether Bob consists of separate objects that behave classically.
Their behavior can look classical to her, but she's not able to determine that their behavior is classical because she can't measure Bob's entanglement entropy.
She can't measure the dimension of her own boundary and recall from a couple of times ago that the boundary includes some sector that supplies free energy that Alice can't extract information from for further processing, she can only extract free energy from.
So she can't measure the dimension of that sector, and so she can't measure the dimension of the whole boundary itself.
And this, of course, means that she can't measure her own dimension either.
And of course, she can't measure Bob's dimension, because the only information she can get about Bob is the classical information that's encoded on this boundary.
She can't reach past the boundary to see how large a system Bob is.
And that's clearly connected to this first point, that she can't measure the entanglement entropy across Bob, because the entanglement entropy can only be small if her dimension and Bob's dimension are both much larger than the dimension of the boundary.
So that's a condition she can't check.
So all of these kind of no go theorems lead off in interesting directions.
And the only one that we're really going to be interested in here is the third one, the one about measuring Bob's entanglement entropy, because we want to talk specifically about how multiple agents, so multiple components of Alice can access information about Bob's entanglement entropy.
Okay, so recall from the end of the last session that the last thing we talked about was classical communication.
And we talked about the fact that classical communication involves assumptions and pitfalls and that we have to be very careful whenever we talk about it.
And what we're going to do today is standard practice in physics.
We're simply going to stipulate that these components, a one and a two, the separable components of Alice, communicate classically.
And so we're going to draw it like this.
We're going to draw a classical channel between them, and that classical channel passes through Bob.
It uses degrees of freedom of the ambient photon field or the ambient atmosphere or pieces of paper or email or something like that that's out there in the environment to exchange classical messages.
And there are a couple of things to note here I haven't even written down here.
We're assuming that a one and a two share some language for this classical communication.
That's a big assumption, as we talked about last time.
But I will note explicitly that classical communication takes time.
That's what defines classicality here.
It's causal, so it can't work faster than the speed of light.
This is a topological theory.
We don't have any embedding geometry.
So we can't, at this point, talk about light, which is a relationship between space and time, because we've got time, we've got clocks, but we don't have any space.
But we can say that whatever passes through this classical channel requires at least one clock tick on Bob's side.
So it's a process that Bob has to execute.
And executing that process takes time.
So getting the signal from me to you on the internet takes some time.
So the environment's clock has to tick during that.
And all of these assumptions bundled together turn out to be a fairly serious set of assumptions and they involve assumptions about fine tuning, about the universe being just right and they should make us nervous and I just want to leave it at that.
We always assume with complete a plumb that agents can communicate classically.
But it's not a straightforward assumption and it's worth any of you are looking at for interesting research projects can look into the nature of classical communication.
It's full of hidden assumptions and surprises and things that aren't at all straightforward even though they look like they ought to be.
So there's a challenge.
So why do we assume this?
Why do we assume classical communication?
We do it because we have to if we're going to talk about detecting entanglement.
And most of you probably know the history of the notion of entanglement.
It was first noticed by Einstein, Podolski and Rosen ever after called EPR in 1935.
And they wrote a paper which is infamous and called the EPR Paper in which they argued that the phenomenon of entanglement made no sense and couldn't possibly be physical.
And since quantum theory included this notion of entanglement, it couldn't possibly be a complete theory of what's going on in the world.
And Schrodinger replied the same year with a very detailed paper where he introduces, among other things, Schrodinger's cat as a paradox.
And he explains very clearly what entanglement is and why entanglement follows from quantum theory.
And he uses that discussion to argue that the classical notion of a physical state is not actually applicable to the world as it is.
So he answers the EPR paper very directly.
And this discussion is currently mostly known as the Bohr Einstein debate because of course Bohr already in 1928 has said had said in print that the classical notion of causality in space and time simply doesn't apply anymore.
And Einstein objected to that vigorously.
But that was 1935 and it was almost 50 years later that entanglement was first observed in the laboratory.
Here the 1982 picture is a picture of the interior of Alan Aspet's laboratory when he performed the first entanglement experiment for which he finally won the Nobel Prize last year.
And these days this kind of experiment is done all over the world and is even done with satellite borne sources.
Resource is the key to quantum secured communication, as we'll discuss in quantum cryptography and quantum banking and the quantum internet, all this other stuff that you may have heard of.
So before talking more about these experiments, I just want to provide a definition of entanglement.
Entangled simply means not separable.
That's the definition.
So a state, a joint state AB is entangled if and only if it does not factor into two separable states.
And that's it.
That's the definition.
And the literature, and especially the popular literature, is absolutely rife with hype and various kinds of mischief of entanglement and authors trying to convince you that entanglement is this amazing kind of woo woo thing.
And whenever you run across that, go back to the definition, entanglement simply means this simple mathematical condition of not separability or a state that isn't factorizable.
And that means that the state does not display classical conditional independence.
So classically, that's the way to think about it.
It's a failure of conditional independence.
And it's ubiquitous in quantum theory, even though it wasn't actually absurd for almost 50 years after it was predicted.
So here's what all these experiments look like.
They're called Bell EPR experiments, after John Bell, who derived the statistical criterion for detecting entanglement and EPR.
Einstein, Podolski and Rosen, who did this as a thought experiment and said, if this occurs in the theory, it can't possibly be real.
And of course it is real.
It's now amply demonstrated by experimentation.
Here's how they work.
There's a source.
The source produces a state that is entangled.
And I've written the typical what's called a Bell state.
It's up plus or minus down divided by the square root of two just to normalize it.
But up plus or minus down is clearly not the same as up times down.
So this is not a separable state.
And this state propagates outward in space and time to two observers who have independent laboratories, for example, on different continents.
In that space based experiment that I showed you the picture of from the COVID of Science a few years ago, 2017, I think, the Tulip observers have freedom to choose their own reference frame, their own Z axis for measuring spin.
They do a spin measurement, and they do this over and over and over again.
They accumulate statistics and they exchange their results so that they can analyze the joint statistics of their experiment.
And they check to see whether that joint statistics is consistent with classical probability theory.
And if it isn't to a statistically significant level, then they've been able to detect entanglement.
Now, notice that this process requires classical communication.
They have to make their independent measurements in their own laboratories, and then they have to exchange results, or one of them has to send results to the other one, or they both have to send their results to some third party.
But in all of these cases, they're exchanging some classical data.
And so we have the assumption that whoever gets that classical data knows the language it was recorded in and so can do a joint analysis.
So I'll just show you another picture of this experiment that's in a standard space time diagram here.
Time is vertical, space is horizontal.
The two observers are labeled Alice and Bob.
They share a quantum channel that goes from Alice to the source to Bob.
That's the entangled state.
They do some processing.
And then one of them here, Bob, sends the results to Alice.
And that's a classical communication.
It takes time, and it traverses space.
So this step is classical.
So this is why we have to assume classical communication to talk about detecting or using entanglement.
So now I want to represent this in a different way.
Using our little picture earlier.
We're going to think of Alice, again as two components, a one and a two.
They're separable, so they have to communicate classically.
They have a classical channel that goes through Bob, and they also now share some quantum channel.
They share an entangled state.
And the entangled state, of course, is produced by Bob.
The source is part of Bob.
And their detectors, if you want to think about it that way, are located on this boundary B, or their interface with the sources on this boundary B.
And each of them executes a process that accumulates data from the quantum channel and communicates it to the other observer via the classical channel.
Now, this picture illustrates what's called a lock protocol.
Lock means local operations and classical communication.
So a one and a two are each operating locally on their boundary.
They're making measurements locally on their boundary, and they're communicating via actions locally on their boundary and observations locally on their boundary.
So, for example, I'm communicating with my computer here.
We can consider it my boundary.
And stuff is happening in the environment that's implemented by the Internet, and you're receiving those communications locally on your boundary, on your laptop or whatever it is you're using.
So that's what local operations means.
And these protocols specifically involve classical communication.
And so they're able to detect entanglement.
And a Bell EPR experiment is just an example of a lock protocol.
The observers exchange information about how they're going to do their experiments.
They're both going to measure D spin.
They're going to use independently chosen reference frames, and they're going to look at the output from some agreed upon source.
So that's all classically set up.
Then they actually make their observations, and then they classically communicate their results.
So classical communication front and back lock protocols are not limited to this sort of Bell EPR sort of setting.
We can also represent a scattering experiment as a lock protocol.
So here's a representation of scattering as a lock protocol.
And you can see all I've done is cut that previous boundary at the division between a one and a two.
And I've then extended it in some external time, the time that is counted by Bob's clock, not by Alice's clock.
That's what's meant by external.
And I've relabeled Alice two as Alice one at a later time.
So now what Alice is doing is communicating with her past self, or a one is communicating with her future self, and they're each doing something different.
A one is executing a procedure that in the laboratory we call state preparation.
She's preparing a state that we'll call in, which is just the initial state of some scattering experiment.
So, for example, at the LHC, N is some state of two protons that are portaling around the ring at the LHC at close to the speed of light.
And Alice, then later on at T plus delta, t is doing a different kind of quantum process.
She's analyzing the data coming out of something like the Atlas detector, which is a multiparticle counter that's located at the LHC.
So they share a quantum channel, which is the scattering channel that takes the incoming state and produces the outgoing state.
And I recall from the very first session, as Feynman told us, to understand this transition from in to out, we have to integrate over all possible paths that are consistent with conservation of spin.
Holicity basically momentum plus spin.
All the different spins that are relevant in a high energy physics experiment, including things like Lepton number, which is basically a spin.
Now, how do we know?
How do we know what we have to conserve?
We know what we have to conserve because Alice is doing the experiment has a classical memory that allows her to remember what she prepared.
She can remember that what she did back in the past was set to protons counterrotating in the LHC, and they had certain energies, and so they had certain momenta, and they were protons, so they had certain spin variables.
All of that has to be remembered to make any sense of the output of the detectors.
And so to actually come up with a measured state that makes sense.
And very often this memory channel is neglected by physicists.
And I'm going to pause here and let Ander ask a question.

34:52 _Ander Aguirre:_
Thank you, Chris.
So does this imply that every time you have a log channel, the quantum part is a scattering picture, like a unitary evolution?
Even in the earlier EPR picture, is that quantum channel portion always a unitary evolution scattering picture?
Thank you.

35:14 _Chris:_
Yes, for essentially the reason that defined a classical channel, you're always assuming you have something that's protected from decoherence by the environment.
So, yeah, if you're doing an EPR experiment, you have to assume that you don't have any environmental decoherence between the source and the detectors.
And similarly, when you're doing a scattering experiment, you have to make the assumption that the environment is not reaching in there and messing with the outgoing state that you're going to see, or reaching in and messing with the incoming state and changing it in some way that repepes it in a way that you don't know, that you have no knowledge of.
So, yes, you're making a fairly strong antidecornce assumption in any of these settings when you're talking about having a quantum channel.
Does that answer the question?

36:20 _Ander:_
Yes.
Thank you.

36:21 _Chris:_
Okay, great.
So we can think of lock, we can think of scattering as Locke, and I just wanted to now emphasize that effectively.
What Locke is implementing is two parallel memories.
A classical memory, which, as we said in the case of scattering, is memory for preparation.
In the EPR case, it's memory for preparation for what the experimental setup is, for what the instructions for doing the experiment are.
And we also have a quantum channel, which is effectively another memory.
It's something that's extended through time.
And again, it's implemented by the environment, implemented by Bob, and it involves Bob's.
Clock ticking.
So whenever we have two memories in parallel, we can construct an error correcting code.
So think of a simple classical error correcting code.
For example, the use of parity bits in exchanging digital data.
So if I send you a bit string classically, and I send it to you two or three times, so there's some redundancy in my signal and I send you a parity bit, I say, okay, add up your bit string, and the result should be one.
It's one on my side.
If you add it up and you get zero, there's an error someplace.
You can use that parity bit to detect errors.
So you can throw out the bit strings that you receive that have parity of zero and say, oh, the environment interfered somehow with the signal, or some eavesdropper interfered with the signal.
It made a mistake, or something like that.
So this corresponds to environmental decoherence not being a good assumption.
Even though it's classical, environmental interference is not a good assumption in this case.
So a quantum error correct encoder is basically the same idea.
I use some feature of the fact that I have two different memories and that I'm encoding something in time.
I'm encoding multiple replicates of something in time to provide a way of checking to make sure that I'm sending the correct message.
So I can, for example, consider the message to be my classical memory and consider the quantum process as a process that tests that memory.
So I remember that I need to do experiment X, and I will get result Y.
I actually do experiment X on this quantum channel and see if I get result Y.
And if I don't get result Y, then something's wrong.
Either I can't trust the quantum channel or I've remembered my preparation conditions incorrectly.
So I'm using one memory to check the accuracy of the other.
And this using something about the environment, some channel in the environment to check memory is absolutely ubiquitous, and we use it all the time.
So, for example, look around your room, and your room hopefully looks more or less the same now that it did at the start of this session.
And that's very reassuring.
It reassures you that something's not happening in the environment that's dangerous and disturbing.
And if you couldn't do that, if your environment was constantly changing and there was no familiarity about the environment, you wouldn't be able to check your memory.
You wouldn't be able to.
Check your sanity.
So even though we don't think about our local environments as effectively an error correcting code, that's exactly how we use it.
We use stigmurgic memory or memory out there in the environment as a way of checking our own memories and assuring that our memory is okay.
So I talked a little bit about quantum security.
Here's how quantum security system works again.
It's a lock protocol.
We have some classical signal that can be thought of as a code or a key or a one time pad, for example, that encodes a way of doing experiments.
And once that's been exchanged, assuming it's secure, then we can use the quantum channel to communicate information.
And the classical channel has told us what we have to do with that quantum channel.
We have to make certain kinds of measurements at, say, particular clock times as measured.
And we'll get information sent from the past, from the sender.
And the classical channel protects the quantum channel from adversarial agents, because anything that an adversarial agent does to the quantum channel, if some agent tries to eavesdrop, for example, on the quantum channel, they'll disrupt the quantum channel.
And the results of our measurement will not be what's expected given the protocol that we run, that we have run.
So quantum communication is secured by the fact that interfering with some entangled state actually destroys the state so it's detectable.
We can always know if someone is trying to disrupt our communications, which isn't true if we just have two classical channels.
Charlie can always intercept a message and then recreate it.
And that's not possible with the quantum channel.
So let's refold this diagram so that we've taken the external time back out of it.
And we have this picture where the two components of Alice are just interacting via their shared boundary with their environment.
Bob and now we can see that the source of redundancy is not time, it's the boundary itself.
Just sharing the boundary allows Alice's components, a one and a two, to put copies of the same information on different places on the boundary.
So the boundary now becomes a resource for redundant storage of information.
So Alice one and Alice two can use different parts of the boundary to check what other parts of the boundary, say, to check the information that's encoded on other parts of the boundary so they can define an error correct encode on the boundary itself using this lock protocol.
So I just want to leave you with this idea that using classical and quantum channels together allows us to define error correcting codes on boundaries that we share as separate agents and leave you to think about what shared measurements, what shared quantum reference frames let us as agents see the same things.
And this is what we'll talk about next time in September.
We'll talk specifically about how space provides us with an error correcting code and try to understand why space is treated as emergent from something else, basically from communication in most of quantum gravity.
So thank you very much.
I encourage you to use the interactive QA and to attend the discussion sessions, and we'll see you in September.
Thank you.

45:57 _Daniel:_
Awesome.
Chris, thank you for the lecture.
Ander, do you have any remarks or questions?

46:10 _Ander:_
Not right now, thank you.

46:13 _Daniel:_
I'll just ask a few quick questions and if anyone has one, quickly in the live chat.
So you mentioned the tick of the clock, and in active inference, we often hold up side by side both the discrete time models and the continuous time models.
So do clocks have to tick discreetly or how do we think about continuous time modeling.

46:39 _Chris:_
In this quantum setting?
They do have to tick discreetly because one has to be able to distinguish Alice's preparation of the qubits on her boundary from Bob's measurements of the qubits on the boundary.
And this process can be extremely fast with respect to any kind of sense of macroscopic time.
Your eyes are responding to photons in, I think it's hundreds of femtoseconds.
So the discrete transitions that are effectively time measurements for you are at that very fast molecular timescale, much, much faster than our typical clocks.
Now, when we try to do very fast timing, we're constructing a faster clock than that, but it's a clock that we can only observe indirectly.

47:50 _Daniel:_
Awesome.
Okay.
Now this one maybe connects a little bit to application, but with all the developments happening in theory, some of which you're reviewing here and also in practice with quantum computation, and then keeping in mind this distinction sorry, I've lost you back.

48:17 _Chris:_
I've lost you, Daniel.

48:19 _Daniel:_
Okay, we'll wait till you're back.
I can see you.

48:22 _Chris:_
No.
Okay.
All right.
Just repeat.

48:26 _Daniel:_
Yeah.
So so given these rapid and ongoing developments in theory and practice related to quantum information science and quantum information security, how are people using this distinction of the classical stigmagic memory and then the quantum cognitive process to anticipate how to develop information systems that are reliable going forward?

49:01 _Chris:_
I don't know of any instances in which thinking about quantum cognition has entered directly into any design of communication systems.
The ability of humans to interact with these systems is just assumed.
So it's just assumed that the user can interact with, say, a computer interface, which is the sort of interface that will be provided or is provided to any quantum computer.
So if you think about a quantum computer, a practical quantum computer, it has classical interfaces front and back.
So in thinking about interacting with the computer, I'm giving it some classical problem statement, for example, and asking for some classical answer.
And what it's going to give me is a probability distribution of classical answers.
But I can, by running the calculation many times, make that probability distribution fairly tight.
Yeah, I don't know of anyone talking about quantum BCIs at this point.
It'd be an interesting question.

50:27 _Daniel:_
Was it always understood these sorts of blind spots and axioms associated with classical communication.
Was it developed as kind of like a proposal or like a special case and more unpacking was left for later?
Or are these blind spots things that we're now coming into awareness of?
Given what we're learning in the quantum information sciences?

50:55 _Chris:_
I think we're learning how serious they are.
But they were certainly recognized even by Bohr in his 1928 paper.
And that's a very good paper, too.
It's called the present state of quantum theory or something like that.
And it's in Nature, and it's available on the web somewhere.
I have a copy of it.
But it was written, in a sense, as Bohr's summary of the 1927 Solve Conference, which was the conference at which everyone doing quantum theory at that time got together to talk about their results.
And in it, Bohr essentially presents what came to be the Copenhagen interpretation, which I think is probably unfairly called an interpretation.
It's sort of the Copenhagen Pragmatic stance toward quantum theory.
And essentially what Bohr says is that if we're going to do science, we have to assume that people can talk to each other.
And if we're going to do science, we have to assume that there are instruments that we can manipulate and have reasonable confidence that we know what manipulation we've done.
So if I turn a knob from one to two, I have to be reasonably confident that I'm making a particular change that I can understand.
And we have to have reasonable confidence that different laboratories can replicate the same experiment.
And if we think about any of those assumptions in purely quantum theoretic terms, then all sorts of questions are raised, right?
Every quantum system is unique.
We have the no Cloning theorem, so every scientific instrument is unique.
So there's no such thing as exactly replicating an experiment.
Right?
That's a coarse grained description of what I've done with a completely unique quantum system.
And my brain, of course, is unique, and yours is too.
And everyone else's is.
So talking about us sharing a language is essentially a coarse grained assumption.
And what the Copenhagen stance is all about is coarse graining yielding effective classicality?
Or what that really means is coarse graining yielding a description that we can use in the language that we understand?
So these are very, very old issues that have been recognized for a long time, but I think in part because of the disaster of shut up and calculate, they haven't really been talked about in the classroom.

54:14 _Daniel:_
Awesome.
I'll just read short questions from the chat.
We can pass them to the discussion section, but there's a lot of great diverse questions.

54:24 _Chris:_
So Alexi wrote, I think I've lost you again.
The revenge of zoom.

54:30 _Daniel:_
Well, we looked at the chart earlier where, like, Bob was talking to Alice, the Unidirectional.
Okay, okay.
The Unidirectional.
The third party is recording it, I'm sure.
Alexi wrote, regarding the environment being used for error correction, a symptom of derealization in psychological trauma breakdown.
We don't recognize the environment around us and it's scary.

55:04 _Chris:_
Makes sense.

55:05 _Daniel:_
Makes sense.

55:06 _Chris:_
All right.

55:07 _Daniel:_
From Bala.
Nice presentation.
I heard Chris say entangled states are LOCC for a specific reference frame.
Is this entanglement unitary or is it related to the numbers of degrees of freedom?

55:27 _Chris:_
I think the quick answer would be both.
If you have a complex system with many degrees of freedom, some can be entangled while others aren't.
It depends on what parts of the state are separable.
So again, entanglement is just a statement about components of a joint state that factor or don't.
So you can have a joint state that looks separable along some dimensions, but in other dimensions.
The other big complication here is that whether a state looks entangled depends on the reference frames that you use to measure it with.
And if you pick entangled reference frames, then what we ordinarily think of as separable, as entangled states become separable.
So you can move entanglement around.

56:33 _Daniel:_
Awesome.
Okay, from Roland Rodriguez is the discrete temporality only within the context of a given holographic screen interface with time being bracketed otherwise beyond interface systems, is continuity or discretion kept agnostic?

56:54 _Chris:_
I think if I understand the question correctly, it's yes.
If I don't draw any boundaries, I just have the joint state, then the evolution is unitary and in a sense time plays no role.
And if unitary evolution is perfectly time symmetric, so time actually drops out altogether.
Awesome.
So to talk about time, we have to draw boundaries.

57:29 _Daniel:_
Awesome.
Time must have a stop huxley.
And I'll ask one last question from the appropriately monikered question quanderer all communication is abductive is a sentiment that I've been using to develop some arguments.
Does that scan for you?
How do we connect what we're discussing here with quantum to abductive logic?

57:57 _Chris:_
Yeah, I could go along with that.
I'd want a lot more detail.
All communication is essentially analogical.
I would agree with that.
Yes.

58:13 _Daniel:_
Ander?

58:17 _Ander:_
Yes.
Thank you.
So going back to the picture where the scattering picture?
So we have so far everything is topological and certainly induces breaking the boundary in different sectors.
I suppose it induces a topology on the boundary.
Now, I had a couple of questions as for the geometry, and this might be getting ahead.
Is it an emergent property of those channels between different boundary sectors?
And if that's the case, then what does it mean to have a QRF or space?

58:57 _Chris:_
Yeah, this is really the topic for September, but you do point out the fact that it's something of a chicken and egg situation.
The way I think of it is, I suppose to choose the chicken side and think about what kind of reference frame does the agent have to implement to see space on their boundary.
And the reason I think about it that way is that's a question?
I want to be able to ask about biological systems.
And this actually gets into probably what won't be talked about till October.
But I want to be able to ask essentially a phylogenetic question of what sorts of organisms, where in the lineage from Luca do we find systems that are able to assign spatial coordinates to their boundaries and what coordinates come first?
And I suspect that sort of discrete location names with no metric come first that a system can talk about, for example, this part of their membrane versus that part of their membrane without even having any ability to say, how far apart they are and that some sort of metric representation of this angular space comes later and that a radial space comes even later than that.
That's, at this point, speculation.
But I think these are questions that we can end up asking given the right kind of formalism and the right understanding of what it means to be able to make a spatial measurement.

1:01:03 _Ander:_
So the conjecture is that the metric would emerge from a discrete network metric of counting ticks sort of thing.

1:01:10 _Chris:_
Yeah, I think that's correct.
And the sort of symmetries of space that we see are very much tied up with object identity.
So if we think about something like rotational symmetry let's see, I should stop screen sharing.
So I've got this object, right, and I can do this, and I say, oh, space has this rotational symmetry.
But for me to say that, I have to recognize that this is the same object, right?
I have to implement object persistence, which we all learn to do when we're nine months old or something.
But we tend to regard those as separate things as we learn object persistence, because space is rotationally symmetric, but we can view it the other way around, that space is rotationally symmetric for me because I implement these constraints that are called object persistence.

1:02:25 _Daniel:_
Do you think we can understand phylogenetics as a whole, as a kind of scattering experiment, like the high energy Leuka event and then dissipating and propagating in a very tangled bank?

1:02:42 _Chris:_
Well, I do want to be able to understand phylogeny in exactly the same terms as embryology, and Mike Levin and I have published papers about that.
We should be able to view the lineage of Luca in exactly the same way that we view the lineage of the Zygote that produced us.

1:03:03 _Ander:_
So that's why it's no coincidence that during pregnancy, the development of the embryo mirrors evolution in terms of the parts that are developed first.

1:03:16 _Chris:_
Yeah, this is the old idea that phylogeny and ontogeny are related in some way, which, from an embryonic development point of view, they're certainly analogous in ways.

1:03:33 _Ander:_
Sorry, if I may ask one last question, things should be very quick regarding the weak rotation.
I'm still a bit unsure how it ties to this diagrammatic notation that we had with quantum channels on show so on.
In the second session, we briefly talked about the weak rotation being a reversal in the direction of time.
Is there any relation to today's session?

1:04:05 _Chris:_
Yeah, whenever we think about the flow of time as driven by the input output cycle the input output cycle?
For agents separated by a boundary, there's always a sign change.
Right.
My input is your output, and vice versa.
So when we think about the bob's clock ticking, when Alice does something, his direction of time, in a sense, points with respect to the boundary opposite to hers, but that's only with respect to the boundary.
He sees information flowing in, and she sees information flowing in.
That's the only point being made here about the WIC rotation as an operation.

1:05:14 _Ander:_
Thank you.

1:05:16 _Daniel:_
Thank you, Chris.
Very well appreciated by the viewers and by us.
So we'll certainly look forward to reviewing the q a, and everybody is welcome and encouraged to join for the participatory discussion in about two weeks on Saturday.
So till next time.

1:05:38 _Chris:_
All right, thank you.
Cheers.