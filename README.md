# SSI_2020
link 1 : https://www.wolframalpha.com/widgets/gallery/view.jsp?id=540d8e149b5e7de92553fdd7b1093f6d
## Statistics
Someone asked a question along the lines of "what should I read if I want to keep studying statistics?" My answer to this question is here. 

In statistics, there’s sort of a few directions you can go in. 

One direction is learning more about prediction problems. A pretty good resource for this are MIT’s course notes on intro to machine learning: see here, for example: https://phillipi.github.io/6.882/2020/notes/6.036_notes.pdf

If you’re interested in applications, Stanford has a few pretty good classes on this: 

http://web.stanford.edu/class/cs224n/

http://cs231n.stanford.edu/

Another direction is learning about statistical foundations. While this is somewhat less likely to lead to research project, learning statistical foundations is, I would say, intellectually satisfying. To study statistical foundations, I would say that a good place to start is: 

https://projects.iq.harvard.edu/stat110/home 

and

https://courses.cs.washington.edu/courses/cse312/20su/ (Alex added this)

http://web.stanford.edu/class/cs109/ (Alex added this)

This is a really good book on the foundations of probability. 

A more advanced follow up to this book is here https://services.math.duke.edu/~rtd/PTE/PTE5_011119.pdf  

Although this book requires a lot of knowledge, it’s really interesting too. 

Statistical Inference (https://www.amazon.com/Statistical-Inference-George-Casella/dp/8131503941/ref=sr_1_2?dchild=1&keywords=casella+and+berger&qid=1596196019&s=books&sr=1-2) is also an interesting field, and builds more on the decision theory that we talked about. 

If you’re interested in causality, I don’t have that many recommendations, although The Book of Why (https://www.amazon.com/Book-Why-Science-Cause-Effect/dp/046509760X) is a good resource. Perhaps the econometric literature (http://www.econometricsbooks.com/) is a good resource. 


## Learning Rust
Learning Rust
Thanks for participating in my masterclass! I hope you took away something useful about building your own applications, learning new programming languages, and all the tools involved in the process.

Here's a step-by-step guide with optional activities if you want to continue down this track:

Sign up for a free account on Exercism, which has over 3,000 exercises for learning all sorts of programming languages (Rust, Java, C++, Go, and 50+ more), along with free mentorship.

Solve the first 5 exercises on the Rust track.

Continue along the Exercism guide in order of exercises (they build on each other!), consulting the Rust Book when necessary.

One of the advantages of Exercism is that while other tools have you code in a browser, Exercism encourages you to work on your own computer, so you learn how to set up an environment that you will actually use when developing real applications.

Building an App
Once you feel comfortable with Rust, I encourage you to download the source files : https://drive.google.com/drive/folders/18BXADb_WdutnrdveOmvfchjeulr0195q?usp=sharing  of the apps we built today. Remember that to run your code, you simply need to use the cargo run command inside the project folder. Try extending asciihero with new functionality! Some suggestions (in rough order of difficulty):

Print out all permutations of a word in ascii text, so Hello => "Hello, elloH, lloHe, loHel, oHell".

Allow users to print out text with different ascii fonts : http://www.figlet.org/examples.html.

Create a live chatroom that allows users to talk to each other, in ascii art font. (You will need state : https://actix.rs/docs/extractors/#application-state-extractor for this.)

After you're done developing, the easiest (and free) way to deploy your app to the public web is by using Heroku. You can find detailed instructions here : https://github.com/emk/heroku-buildpack-rust#using-this-buildpack

Community
Whether you're happy with how this turns out or need help at any step along the way, don't be shy, and post in the Ed discussion board with questions, or simply to show off your app to others! Good luck, and remember to help each other out along the way.


#### Eric Zang Website : https://www.ekzhang.com/
1. https://www.hackerrank.com/pwshpc-online-round
2. https://www.aapt.org/physicsteam/2020/pastexams.cfm
3. https://ekzlib.herokuapp.com/home
4. https://setwithfriends.com/ 
5. https://www.reddit.com/r/dailyprogrammer/
6. https://insights.stackoverflow.com/survey/2020
### ekzhang@college.harvard.edu <ekzhang@college.harvard.edu>;

#### Neural Netwrok 
Convolutional neural networks (CNNs) are commonly used in computer vision (image recognition). The network is able to recognize local features within different areas of the image (like edges of a shape) and can synthesize these observations into a classification algorithm. AlexNet is one example.

Recurrent neural networks (RNNs) are commonly used in natural language processing. For example, you can feed it words from a sentence in order, and it can perform tasks like topic classification, sentiment classification, or it can predict the next words to follow. The autocomplete word options on a smartphone use this idea to some extent.

Generative adversarial networks (GANs) are used to generate convincing examples of some form of data. You saw an example of it in the website of fake human faces. This approach is actually composed of two networks: the generator and the discriminator. Given a dataset of real examples (e.g. real pictures of people), the generator learns to produce fake examples, while the discriminator learns to identify which images are real and which were produced by the generator. As the generator improves, the discriminator becomes more discerning, and the generator must further improve in turn.

Note that I only listed the general uses of these architectures. Deep learning allows for a wide range of creative applications of neural networks to problems. For example, RNNs can be used to analyze music scores, and CNNs/fully-connected networks can be used to make decisions in playing a game.


### Getting Satrted
1. Graphics : http://cs248.stanford.edu/winter20/
2. System  : http://web.stanford.edu/class/cs107/
3. Security : https://cs155.stanford.edu/
4. Compter Vision : http://cs231n.stanford.edu/
5. NLP : http://web.stanford.edu/class/cs224n/
6. Theory : http://web.stanford.edu/class/cs106b/
7. ML (classical) : http://cs229.stanford.edu/
