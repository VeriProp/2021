Probabilistic programs are a structured way to describe computations or models that have access to some source of randomness. They appear naturally in various safety-, security-, and privacy-critical applications including randomized algorithms, security protocols as well as autonomous systems working in uncertain environments, e.g., due to imprecise sensors. 

The behavior of probabilistic programs is often counterintuitive — a consequence of the well-known fact that humans have difficulties reasoning about stochastic processes. In combination with their importance in emerging safety-critical domains, the counterintuitive nature of probabilistic programs means that ensuring their correctness must be based on verification and analysis techniques that are rigorous, tool-supported and, ideally, largely automated. However, the development of such tools has not kept up with the increasing usage and popularity of probabilistic programs.

In part, the lack of tool support can be explained by the fact that research on probabilistic programs is spread over multiple fields. In addition to the classical understanding of probabilistic programs as randomized algorithms, probabilistic programs have received rapidly increasing attention as a modeling formalism for complex probability distributions in machine learning, artificial intelligence, and cognitive science. Within the verification community, we identify three subcommunities that are working on probabilistic topics and could benefit from exchanging open problems and possible solutions:

The *probabilistic model checking community* considers Markov models which arise as operational models of languages like Modest and Prism, which have strong ties to process algebras. This community features strong tool support, but approaches mostly work on huge (finite) state spaces that are represented explicitly or using variants of BDDs. Furthermore, support for conditioning — heavily employed in probabilistic programming for machine learning — is sparse within this community.

The *PL community* considers, amongst others, deductive approaches using Hoare logics or weakest-precondition-style calculi, abstract interpretation, or type systems in connection with techniques from probability theory, for instance, martingales. Many of these approaches consider very expressive probabilistic programs in a compositional manner, but have not been automated. 

Within the *AI community*, there is a growing interest in verification techniques. Typical models are neural networks, Markov fields, or #SAT. These techniques are often solving problems of a probabilistic nature, but problem instances are not formulated using probabilistic programs. While most approaches in this community are automated, few consider generalizing their solutions to verify general purpose probabilistic programs.

The goal of this workshop is for the three communities to come together and learn about each other’s open problems but also about each other’s solutions and approaches. We will provide a forum for research on the automated verification of probabilistic systems that are in some way described by a programming language, with a particular focus on both symbolic methods and compositional approaches. 

# Call for Papers

VeriProP aims to bring together researchers interested in the tool-supported verification of probabilistic programs, models and systems. This includes probabilistic model checking, program verification in the presence of a source of randomness, or formal guarantees for statistical machine learning algorithms.

Topics of interest include, but are not limited to:

- Symbolic approaches to the verification of Markov models
- Exact inference techniques
- Abstract interpretation for probabilistic programs
- Domain specific probabilistic programming languages
- Verification of inference algorithms
- Automation of deductive approaches to verifying probabilistic programs-
- Probabilistic program reasoning in safety, security or privacy
- Synthesis of probabilistic programs

We call for extended abstracts (1-2 pages in pdf format) describing either ongoing research or an overview of past research in the scope of the workshop.

# Organization

This workshop will be held as a satellite event of the [33st International Conference on Computer-Aided Verification (CAV)](http://i-cav.org/2021/). The workshop is chaired by:

- Fredrik Dahlqvist, University College London
- Sebastian Junges, UC Berkeley
- Benjamin Kaminski University College London
- Christoph Matheja, ETH Zürich



