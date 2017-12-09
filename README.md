# deep-learning-map
Map of deep learning and notes from papers.

Idea: Write (or link to) paper summaries, blog posts or articles that will help people with limited experience:

- Understand what different models or terms mean
	- Know what the state-of-the-art results are in each domain
	- Be able to look up known advantages and disadvantages of key models and approaches
- See how different concepts connect with each other

It is crucial that 
- these summaries are presented in a way that makes the relationships between different concepts clear (hence this being a 'map'), and that
- materials are chosen selectively so as not to overwhelm the reader.

#### README contents:

1. Development notes
2. Topics to cover (in the DL map)
3. Recommended Deep Learning Resources
4. Existing repositories with summaries of papers on machine learning 
5. Newsletters

---

## 1. Development Notes

#### 9 Dec 2017
- Add brainstormed list of topics to cover. The idea is to write (or link to) paper summaries, good blog posts or articles that will help people with limited experience get a better idea of what is going on in the field. This means:
	- Understanding what different models or terms mean
		- Knowing what the state-of-the-art results are in each domain
		- Being able to look up known advantages and disadvantages of key models and approaches
	- Seeing how different concepts connect with each other
- The target audience is not currently experienced researchers, but the hope is that researchers will eventually benefit from this as well.
- I will also be going through Goodfellow et. al's book 'Deep Learning' and may add insights or summaries from the book (referencing those appropriately.)
- Difficulties: it is hard to know how to connect concepts with each other initially, so I will first 
	- (1) write paper summaries,
	- (2) write a list of summaries of key terminology, and
	- (2) build a spreadsheet trying to list connections in parallel.
		- The spreadsheet is important: I believe that it will be greatly beneficial to have a visual map and not just a list of papers because the latter is much harder to digest.
- Everything will likely be scattered at first, but I hope the pieces will start coming together after the first month.
- Sample use case:
	- I want to

## 2. Topics to cover

- DQN
	- Deep convolutional Q-learning
- A3C (Asynchoronous Advantage Actor-Critic)
	- A2C
- Policy gradient methods
	- TROP
- Hierarchical networks
	- Feudal networks
- Auxiliary tasks
	- UNReAL 

- Dilated convolutions
- Dilated LSTMs
- Quasi-recurrent NNs
- Hierarchical RNNs
- Capsule Networks

- AI Safety

## 3. Recommended Deep Learning Resources

- [Notes for Stanford course CS231n on Convolutional Neural Networks](http://cs231n.github.io/)
	- Have found this to be great for learning and an excellent reference (often landed here in my first few months of Googling about deep learning terms/problems!)
- [Deep Learning terms glossary on WildML](http://www.wildml.com/deep-learning-glossary/)
	- Short descriptions of terms (techniques, architectures frameworks) with links to relevant resources (blog posts, papers). 

## 4. Existing repositories with summaries of papers on machine learning 
Have added a :star: to the ones I find particularly helpful.

- :star: [Alexander Jung](https://github.com/aleju/papers)
	- Summaries:
		- What, How, Results summary. Easy to digest.
		- Bullet points with images (result graphs, architectures).
		- Links to related resources (paper website, video).
	- Lists by date added, **with brief tags** such as 'self-driving cars', 'segmentation','gan'.
	- Around 80 papers added from 2016-17, last active Dec 2017.
	- Starred because summaries are easy to digest and understand.
- :star: [Denny Britz](https://github.com/dennybritz/deeplearning-papernotes)
	- Summaries:
		- Short TLDR; section that gives authors' argument, method and high-level findings.
		- Sometimes contain key points (usually model, experiment or result details) and thoughts sections.
	- Lists summaries by date reviewed, list also includes many other papers without summaries (are these key papers or ones he's read?).
	- About 100 summaries. Last active Nov 2017.
	- Starred because summaries are short but to the point, and because there are many summaries.
	- I also recommend his weekly newsletter ['The Wild Week in AI'](https://www.getrevue.co/profile/wildml) and his blog [WildML](http://www.wildml.com/) which has some great tutorials and a deep learning glossary.
		- In some way the glossary has done part of what I'd like to do with this map. Haha great!
		- Oh and did I mention his [repo of implementations of RL algorithms](https://github.com/dennybritz/reinforcement-learning)? :O I haven't even gone through this properly yet.
- [Dibyatanoy Bhattacharjee (Yale)](https://dibyatanoy.github.io/deep-learning-paper-summaries/)
	- Summaries
		- Longer summaries that outline paper content and someotimes include definitions.
		- Paragraphs or bullet points with images (architecture diagrams)
		- Points to Ponder sections (sometimes)
	- Lists all summaries (titles AND summary content) on one webpage. Interesting because you can scroll through all of them in one go and see what catches your attention.
	- 7 summaries. Last active May 2017.
	- Mostly papers on RNNs / memory / translation.
- [Abhishek Das (CS PhD student at Georgia Tech)](https://github.com/abhshkdz/papers)
	- Summaries:
		- Provides brief summary of model in paper. Does not seem to include results.
		- Gives opinion on the strengths and weaknesses of the paper.
		- Seems to be text only.
	- Lists paper summaries by paper year. 
	- Around 40 papers from 2012-2017, Last active August 2017
- [yunjey](https://github.com/yunjey/deep-learning-papers)
	- Summaries:
		- Short, high-level summaries 
		- Short list of contributions of each paper.
		- Sometimes includes opinions on similarities of papers to existing models. 
	- Lists by topic (yes!) with author, publication month/year and conference (e.g. NIPS, ICLR) if applicable.
		- List is unfortunately not linked to summaries.
	- 6 summaries but many more papers listed. Last active c. Dec 2016.
- [Patrick Emami (CS PhD student at U of Florida)](http://pemami4911.github.io/paper-summaries/)
	- Summaries:
		- Paragraph-based summary of paper: what authors propose, model outline, experiment outline.
		- 'My Notes' section with opinions on main contributions, weaknesses/questions and areas for further research.
			- Nice.
	- Lists papers by topic.
	- About 40 summaries. Last active August 2017.

## 5. Newsletters
- [The Wild Week in AI by Denny Britz](https://www.getrevue.co/profile/wildml)
	- Weekly email newsletter
	- Sections: 
		- News, 
		- Posts, Articles, Tutorials 
		- Code, Projects & Data
	- Links with brief summaries (and occasionally helpful context or opinions).
- 
