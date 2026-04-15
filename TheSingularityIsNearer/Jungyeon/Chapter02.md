## CHAPTER 2 : REINVENTING INTELLIGENCE

#### WHAT DOES IT MEAN TO REINVENT INTELLIGENCE
- Reinventing intelligence mean going beyond the intelligence that nature gave us on a more powerful digital substrate and merging with it

#### THE BIRTH OF AI
- $1 now buys around 1.6 trillion times as much computing power as it did when GPS(General Problem Solver) came out in 1959.
- Two techniques for creating automated solution to problems
	1) Symbolic approach : describes in rule based terms how a human expert would solve a problem
	- primary limitation : complexity ceiling
	2) Connectionist approach : instead of rules, nodes are arranged in a way that can extract insight from data itself
	- a double edge sword, since it can solve probs w/o understading them which means its prone to becoming a black box
	- Many experts now are working to develop better transparency in machine learning-based decisions
- Trains neural net to learn its subject matter like the human brain using rewards
	- Over time neural net provides correct answer w/o training and with large enough data errors in training data cancel each other out and trains neural net to high standard
	- 1960s : Perceptrons(one layer neural network) did well with auto-association but not invariance.
	- Multiple layered neural net deals well with invariance but needed high computational power and large enough training data
	- In mid-2010s HW advances and it becomes cheap enough to use compuational power and large training data for multi layer neural nets. Finally systems were able to solve complex problems

#### THE CEREBELLUM : A MODULAR STRUCTURE
- The universe is 13.8 billion years old (The amount of time that has passed from the Big Bang to now)
- 3.5-4 billion years ago, there was the beginning of life
- 2.9 billion years passed between life on earth and first multicellular life
- First mammals appeared -> primitive nerve nets emerged -> tripartite brain -> modern human brain
- Human brain has more neurons in the cerebellum than neocortex which plays biggest role in our high-order functions
	- cerebellum stores and activates scripts that control motor tasks(AKA muscle memory)
	- cerebellum enables us to move accordingly, making instant judgements w/o having to solve equations
	- it has been a key brain region for a long time but humans now rely on it less and less while using more of neocortex in the modern society
- Computer scientists use evolutionary approach to sets of programs that perform well and introduce random mutation to boost performance

#### THE NEOCORTEX : A SELF-MODIFYING, HIERARCHICAL, FLEXIBLE STRUCTURE
- Evolution devised a way for the brain to develop new behaviors w/o waiting for genetic change to reconfigure the cerebellum so, neocortex was developed
- Neocortex is organized in a more flexible way than the cerebellum so it can invent new behavior in days or hours. This unlocked the power of learning.
- After the Cretaceous Paleogene extinction event mammalian brain grew in a quicker pace
- 90% neurons are in the neocortex.
- Unlike computers which operates sequentially, the modules of the neocortex employ massive parellelism. This is a challenge to model computationally.
- Multilayered neocortices give us more capacity for abstract thought than creatures with simpler cortices. If connected to cloud based computation, it'll unlock the potential for more abstract thought.
	- This neocortical abstraction ability was the enabling factor for humans to invent language, music, humor, science, art, and tech.
- The six main layers of the neocortex dynamically communicate with one another in both directions(hierarchical organization)
- Three key features that enable creativity in neocortex:
	1) propagate the neuron-firing pattern for a given concept broadly throughout its structure
	2) a given firing pattern can be associated with similar aspects of many different concepts
	3) millions of patterns can fire simultaneously throughout cortex and interact with one another
- The neocortex's ability to draw analogies between disparate fields is responsible for many of the key intellectual leaps throughout history.
	- Darwin's theory of evolution, Newton's gravitation, Einstein's relativity were built on analogical insights 

#### DEEP LEARNING : RE-CREATING THE POWERS OF THE NEOCORTEX
- Around 2010 it reached a threshold where many-layered hierarchical computation that takes place in neocortex which unlocked the hidden power of the connectionist approach
- Deep learning enabled sudden breakthroughs that AI field has achieved since The Singularity is Near was published
	- Deepmind's AlphaGo used "deep reinforcement learning" method to process its own games and learned from its successes and failures
	- Unlike its previous human-trained model, AlphaGo, AlphaGo Zero used a new form of reinforcement learning in which the program became its own instructor
	- The next model, AlphaZero can transfer abilities learned from Go to other games like chess
		- The ability to apply learning from one domain to a related subject is a key feature of human intelligence
	- Waymo created self-driving software for its autonomous cars. It used the recordings of the ride to build a simulators which then the models can train in.
	- Solved protein fold problem
- But to reach the vast generality of the human neocortex, AI needs to learn language.
	- To do so, the neural net assigns each sentence as a point in 500-dimensional space and during training sentences that has similar meanings are placed close together. AI learns meaning through contexts that the words are used in.
- Google Smart Reply in Gmail : a combination of a multilayered feed forward neural network w/ hierarchical representation of language content that represents the back-and-forth of the dialogue

- Transformer: Deep learning model which uses 'attention' mechanism to focus their computational powers on the most relevant parts of their input data
	- Parameters are used to classify tokens. Parameters are factors that can be used to make prediction about sth. So transformers depend for their accuracy on huge # of parameters
		- The more parameter one has the more detail the model can capture and AI can make better predictions.
	- The advent of transformer powered most of the AI advances in the past few years. 
- In 2021, Google's Switch had record breaking # of parameters and also introduced a technique called "mixture of experts". It allowed transformers to focus more efficiently on suing the most relevant parts of the model for a given task which reduced compuational cost.

- AI was able to attain `creativity` bc the model learned from the combined creative output of humans
	- When GPT-3 came out it impressed users but one should note that GPT do not understand what it is saying. (Chinese room arguement and David Chalmer's recipe metaphor)
	- GPT-3 showed stylistic creativity since the model trained every kind of human writing.
- Another startling advance of AI in 2021 was `multimodality` which connected multiple forms(img, text, etc.) of data in a single model.
	- OpenAI's DALL-E is a transformer trained to understand the relationship between words and images.
	- Few-shot learning -> Zero-shot learning : AI can combine concepts they learned to create new images wildy different from what they had been shown in their training data.
		- Zero-shot learning is the essence of analogical thinking and intelligence. AI is not just parroting back but is truly learning concepts and applying them to solve problems.

- In 2022, Google's PaLM achieved progress on humor and inferential reasoning.
	- Jokes are hard for AI bc it is a combination of several concepts like wordplay, irony, human experiences ppl share, etc. But PaLM was able to explain why a joke is funny.
	- It also could explain how it reached a conclusion via chain of thought. 

- In Nov. 2022, OpenAI launched ChatGPT with LLM known as GPT-3.5
- In Mar. 2023 GPT-4 achieved 'world modeling' which is the ability to reason organically about hypothetical situations by understanding the relationships between objects and actions
- Google's PaLM-E is a system that combines reasoning ability with a robot. It can identify and complete tasks such as fetching chips from the kitchen.

- Kurzweil had a debate with Minsky, his mentor in 1993 arguing that amount of computation is key to achieving sufficient intelligence. Minsky disagreed. No one won the debate that day but thru the connectionist's breakthroughs of 2020-2023 it's has been made clear that Kurzweil's theory was right.

#### WHAT DOES AI STILL NEED TO ACHIEVE
- Remaining deficiencies of AI: (1) contextual memory, (2) common sense, (3) social interaction
	- Social interaction such as social nuances are hard to understand for an AI.
		- Theory of mind: the ability to recognize that others have beliefs and knowledge different from ours, put ourselves in their shoes, and infer their motivations.
- AI will overcome the three deficiencies if these concurrent trends continue :
	(1) improving computing price-performance
	(2) skyrocketing availability of richer and broader training data
	(3) better algorithms that enable AI to learn and reason more efficiently
- Two main reasons for fast improvents in computing price-performance : (1) innovating new methods in parallel computing, (2) big data
- Human skills vary widely in the accessibility of their training data. A skill needs to be assessable in quantitative terms and be easy to gather relevant data on.
	- To find metrics to assess certain skills one needs creativity and experimentation. For example, in assessing quality of poem one can decide to use heart-rate data or cortisol levels or scores given by readers as a metric.
- Human level intelligence is not monolithic. Its important to view it as a bundle of diff. cognitive abilities.
	- The ability to recognizing ourselves in the mirror, we might share with some animals. Composing music is limited to humans but its ability varies by person. 
	- The gap between average human and the most skilled human varies by area. When AI researchers talk about human level intelligence they usually mean the expert level skills.
	- Later there will be a significant transitional period where AI has passed the Turing test and is superhuman is most part but has not surpassed the top humans in a few key skills.
- The main bottleneck for superintelligent AI is computer programming. AI with programming abilities to give itself more programming skills will enable a positive feedback loop. Bc computers operate much faster than humans cutting humans out of the loop of AI development will unlock stunning rates of progress.
	- AI FOOM : a rapid AI self-improvement leading to an uncontrollable intelligence explosion.
	- There are believers of hard takeoffs and soft takeoffs of FOOM
- Computers will be able to simulate human brains in all the ways within the next two decades.

#### PASSING THE TURING TEST
- How will we judge when AI has finally reached human-level intelligence?
- AI effect : humans tendency to minimize AI's achievements as not so hard to achieve in hindsight
- IBM's Watson went on Jeopardy and won. Although the number one guess of Watson was almost always correct, its second or third guesses were laughably wrong. Watson's game play seemed human but if one digs just beneath the surface, it was not human-like at all.
- Despite the great engineering efforts to curb hallucinations, it remains an open question how difficult this problem will be to overcome.
- While its tempting to think that AI should think like a human, Kurzweil thinks this is a superstition. 
	- If AI makes groundbreaking scientific discoveries, why should we care how AI has generated its outcome?
-Turing test is a useful tool for assessing the progress of AI but it should not be the sole benchmark of advanced intelligence.
	- We need to develop more sophisticated means of assessing the complex and varied ways that human and machine intelligence will be similar and different.
	- Turing test is not about merely understanding human language itself but the cognitive abilities that we express through language.

#### EXTENDING THE NEOCORTEX INTO THE CLOUD
- Trade off between spatial and temporal resolution in brain scans is one of the central challenges in neuroscience as of 2023.
- In 2020, Facebook-sponsored researchers fitted test subjects with 250 external electronodes and used AI to correlate their cortial activity with words in spoken sample sentences. They could predict what words the subjects were thinking of with an error rate as low as 3%.
- Elon Musk's Neuralink began human trials in 2023, implanting its first 1,024 electronode device in a human.
- DARPA is working on a long term project called Neural Engineering System Design which aims to create an interface that can connect to one million neurons for recording and can stimulate 100,000 neurons.
- Ultimately brain-computer interfaces will be essentially noninvasive which likely will use harmless nanoscale electrodes inserted into the brain thru the bloodstream.
	- Tiny electonics called nanobots will connect the top layers of our neocortex to the cloud allowing our neurons to communicate directly with simulated neurons hosted for us online. It won't need surgery since we will be able to send the nanobots thru the capillaries.
- The last time we gained more neocortex, we became humans. When we can access additional neocortex in the cloud, it will result invention of means of expression vastly richer than what we can conccurenlty imagine.
- The brain-computer interfaces will enable a process of co-creation that will evolve our minds to unlock deeper insights, produce transcendent new ideas for our future minds to explore. We will be essentially remaking ourselves. Our minds will be empowered to grow exponentially, expanding our intelligence million-fold. This is the core of Kurzweil's definition of the Singularity.


#### ***comments***
- p.4 우리 조카들 성인됐을 때 특이점이 오네 (Babies born today will be just graduating college when the Singularity happens)
- p.9 Computronium is a hypothetical arrangement of matter that is optimized for processing information at the highest possible theoretical limit. Currently, we build computers using specific materials like silicon, but most of a laptop or a phone is "dumb" matter (e.g. plastic, glass, and metal that doesn't actually 'think') Computronium is the idea of turning every single atom in an object into a processor.
- p.27 Interesting how Minsky pioneered work on neural net and later took part in hindering the development in that field for decades
- p.36 Wow you CAN actually tickle your brain!
- p.37 The importance of a thumb!
- p.49 OpenAI's DALL-E was a pun on Salvador Dali and the movie WALL-E?!
- p.55 현재로서 contextual memory는 이미 어느정도 해결된 듯
- p.70 Since the first human implant, Neuralink has moved from a single U.S. participant to a small multi‑country early‑feasibility program with several implanted patients, plus parallel trials in the UK and UAE, but it is still very early and experimental.

#### ***food for thought***
- 내가 튜링테스트를 진행한다면 어떤 항목을 넣어서 인간인지 AI인지 판별할 수 있을까?
- 인간은 개인의 고유하고 다양한 매력, 불완전성이 있기에 인간답다고 할 수 있는 것인데 뇌컴퓨터 인터페이스를 장착한 인간은 그렇다면 인간이 아닌걸까? 인간의 정의는 앞으로 어떻게 변할 것 같은가? 