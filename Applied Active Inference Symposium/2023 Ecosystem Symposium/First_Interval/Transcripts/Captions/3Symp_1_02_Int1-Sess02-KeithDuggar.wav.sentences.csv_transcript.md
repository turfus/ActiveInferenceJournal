00:01 _Daniel Friedman:_
All right, next up is going to be Keith Duggar, who has submitted a pre recorded video.
The pre recorded video is called active inference.
And the actor model So I will bring that up right now.
Okay, here comes Keith's pre recorded video on active inference and the Actor model.

00:44 _Keith Duggar:_
Active inference and the actor model.
Hello. Hello. I'm Dr. Keith Duggar, platform CTO at X Ray, an extended reality AI
Company, and co host of Machine Learning Street Talk podcast.
Now, as we all work to build an ecosystem based on active inference, software will obviously play a foundational role to make the most of active inference.
We'll need to use software engineering paradigms that align with the principles of active inference, and I think there is one tailor made for our needs.
It's called the actor model.
Active Inference and the Actor Model are two deeply connected understandings of the world.
They provide foundational frameworks for dealing with the dynamics of complex systems, with a focus on autonomous agents that interact in an ecology of nested systems.
I'd like to explore some of their key connections, including the role of agents concurrency, autonomy, uncertainty, and behavior adaptation.
We will see that active inference and the Active model are both paradigm shifts away from a deterministic, centralized, step by step thinking to a decentralized network concurrent perspective of both computation and cognition.
Just a little bit of history about the Actor model.
Back in 1973, Karl Hewitt, Peter Bishop, and Richard Steiger were all working at the Massachusetts Institute of Technology AI lab to Fundamentalize, a concept of concurrent computation that included both structure as well as adaptable algorithm execution.
Conventional methods at the time lacked robustness and secure mathematical foundations.
Their collaborative effort ultimately led to the creation of the Actor model.
At the time, it was viewed as revolutionary due to its characteristics of both increased error tolerance and distributed computation abilities.
Throughout the 1980s and the 1990s, the Actor model became a basis for numerous research projects as well as practical projects, gaining popularity for its flexibility and intuitive approach to concurrent computation.
It was primarily used in artificial intelligence and multi agent systems.
Sound familiar?
New Actor based languages like Actor, Saulson and Erlang contributed to the refinement of the model, shaping it into a more robust and flexible approach to concurrent computing, and it remains alive and well in computer science today.
More recently, the Actor model has gained renewed interest, mainly due to the growing need for distributed systems, cloud computing and edge computing, fueling the Internet of Things and Web 30.
These computer tasks are ideally suited to take advantage of the ACA model's architecture, which is designed exactly for modeling concurrent handling of both large volumes of data on the one hand, and fine grained disparate autonomous systems on the other hand.
This application of the Actor model has had profound effects on major companies that have utilized its principles to handle big data problems such as Twitter, Facebook, LinkedIn, so what does this have to do with active inference?
I'm guessing you've already heard some of the parallels in the intro.
But let's start by looking at a few core principles of the actor model and how they relate to the principles of active inference.
Let's start with the concept of isolation.
Isolation means that an actor in the actor model does not share its state with any other actor.
It can only be affected by receiving a message.
And it can only affect change in the state of other actors by sending a finite number of messages in response.
From a software engineering point of view, this isolation principle limits potential side effects of an operation to a single actor, thus improving the system's overall predictability reliability, and most importantly, if embraced fully, can actually simplify the design.
Looking at the diagram, we see an ecosystem of actors sending messages to a particular actor, which in turn sends back messages to other actors.
Where is active inference?
Well, let's recast receiving and sending messages to a perception action cycle and denote external, internal, sensory and active states.
And we now clearly have the necessary foundation of active inference a Markov blanket.
The actors of the actor model map directly to the agents of active inference.
In addition, the finiteness, the fact that an actor can only send a finite number of messages in response is also an important shared property.
Because active inference models reality, it necessarily respects the resource constraints of real systems.
And this is nicely bathed into the foundation of the active model.
Let's look at another core principle asynchronous message passing.
Communication between actors is asynchronous.
This means an actor doesn't wait for a response after sending a message.
It continues working, it continues living, as it were.
This is critical as it decouples the actors, leading to a system that can continue functioning, living and making progress even when parts of the system are slow or even temporarily unavailable.
Professor Friston has said that the free energy principle is the ultimate existential question if things exist, what must they do?
Well, the actor model claims they must not wait on others.
Of course, an actor can choose to wait on others, but it must not be forced to do so in the model.
It must be free to choose.
This leads us to another critical principle that both models share autonomy.
The free energy principle is a model of physical reality and our reality is, after all, concurrent.
All throughout infinite space, systems are evolving simultaneously according to their local dynamics.
And therefore this is reflected at the heart of the free energy principle.
Of course, a model of computation need not constrain itself to physics.
But Hewitt et al.
Were seeking to develop a model that did model the reality of distributed concurrent systems.
And luckily for us, the actor model embraces both concurrency, seen from the principle of isolation and actor autonomy, making it compatible with active inference.
Next we come to nesting.
The actor model allows for an actor to not only receive and send a finite number of messages to perceive and act, it also allows as an action the creation of a finite number of new actors.
These actors can either be nested within the parent, say, the parts of an animal cell, or it can be released into the environment as independent actors.
From then on this principle, the model fits nicely with the beautiful concepts of multiscale nesting and active inference.
This allows for actors to contain ecosystems of actors both all the way down and all the way up.
Last, I want to cover two more actor model design principles behavior change and persistence.
Actors have the ability to change their behavior in response to a message.
This adaptability allows for the construction of complex stateful entities that can evolve over time.
And indeed, it allows for entire ecosystems to evolve new emergent behaviors.
When used for software engineering, this adds a powerful tool for managing complex dynamic systems.
Active inference, of course, embraces this to the extreme.
The very essence of thingness is the ongoing attempt to predict and adapt to an environment and thereby continue to exist to maintain one's Markov blanket in a broiling sea of activity.
Along with this also comes the concept of persistence.
Persistence allows actors to sade their state and to restore or modify it later a feature that embodies the principle of memory.
Memory is a prerequisite for learning and adaptation.
An agent's ability to predict depends on its ability to remember past experiences and thus minimize the surprise associated with unexpectedness.
The vital role of memory is also emphasized when we assume that agents have inductive priors, either from experience or inheritance, contributing to their world model.
This world model both guides their current behavior and it is continuously updated based on new experiences contributing to their ongoing adaptation and existence.
Okay, great.
You say there are clear and deep connections between the actor model and active inference.
But how does this help us in the active inference community?
Well, firstly, in my opinion, it is a software engineering paradigm we should embrace.
And if we do, there are of course, actor model libraries and frameworks that we can use such as ACA, Orleans, thespian Actix Protoactor and many more, which we can immediately use when building active inference software modules and applications.
There are also libraries, languages and even language features that align very well with the actor model principles such as Zero, MQ, tokyo and Rust, Erlang, Async, Await and C.
Sharp, et cetera.
But more important than the tools available to us today is the software design mindset that will guide our creation of the active inference software of tomorrow.
The actor model provides a paradigm of software design and engineering that is the most perfect match that we have for active inference.
This is evident not only from the alignment of the core principles we previously discussed, but also from the insights that active inference in the actor model bring to each other.
For example, consider what is now called Hewitt's Law.
Informally stated as everything is everywhere, this law signifies the idea that in a truly asynchronous distributed system, it can take an arbitrary amount of time for a message to go from one place to another, and any actor must be prepared for that event.
There is simply no such thing as instantaneous in such a system, and no component can make an assumption about the timing of another component's actions.
In fact, one must act as if a message may never arrive.
This has important implications.
It suggests that it is impossible to accurately and consistently determine the state of the entire system at any given time, because the information just may not have even propagated across the system.
And also attempts to implement global synchronization will inevitably introduce bottlenecks and reduce efficiency.
Hewitt's Law emphasizes the need for systems to be designed in a way that they can effectively handle these unavoidable delays and uncertainties, highlighting the importance of robust nonblocking communication mechanisms and local decision making abilities.
In short, Hector model systems are by nature nondeterministic.
Does this sound familiar?
What other paradigm highlights operation under uncertainty and the autonomy to continue despite the environment?
Active Inference and the free energy principle?
Active inference reflects the reality of an unpredictable world in which our software systems operate.
Different outcomes may result from the same initial conditions due to the occurrence of events in a random, unpredictable order.
This is the concept of surprise that we all know well, where an agent updates its beliefs about the world when the sensory input it receives does not match its predictions.
Both the actor model and active inference acknowledge that the world is unpredictable.
Even more than acknowledge it, the models accept this uncertainty as a given and not something to be managed away.
Indeed, as we know in the free energy principle, the uncertainty that we maintain in our models is what gives us the flexibility to adapt.
Perhaps this is just my personal flight of fancy, but I imagine a future where software modules guided by active inference do away with hard coded error handling and swap in probabilistic learning algorithms that optimize themselves as the error landscape evolves.
Modules that are robust and self healing distributed systems with no single points of failure that focus on predictive disaster avoidance rather than reactive disaster recovery.
Looking towards the future, we as a community have the potential to push the boundary of both active imprints theory and practical implementations of the actor model.
By leveraging the strengths of these two paradigms together, we can create software systems that are robust, adaptive and more aligned to the physical world in which they actually operate.
Imagine a future where software components using active inference in the actor model can anticipate potential issues, learn from past mistakes, and adapt in real time to environmental changes.
With this approach, we can build systems that are fundamentally more resilient and more efficient.
In my opinion, this can bring a step change in software reliability and performance and scalability, and heralds a new era of computing, weaving principles of biology and cognition into the fabric of our software systems, bringing them closer to life in the process.
In conclusion, the coupling of active inference to the actor model provides a powerful new lens through which we can look at software design and engineering.
Whether we leverage existing languages and libraries aligned with active inference or invent new ones, we are standing on the brink of an exciting frontier.
So let's seize the day, have a look at the actor model and its relationship to active inference, and let's shape the future of intelligent distributed computing.
Thank you for listening.

19:17 _Daniel:_
Awesome.
Great talk by Keith.
Thank you, Keith, for sending that in.
There were some comments in the chat.
So, Keith, potentially if you want to join for A-Q-A some future time, but really cool presentation.
