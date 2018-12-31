# Motive

- programming technology has started repeating itself
- similar patterns appear in many languages and technologies
- what's needed now to make high-quality software is not
  tech, but education
- not "professionalism" or "better discipline" or "becoming
  a real engineering field"
- but recognition of our own limits (cognitive, emotional,
  biological) and the limits of our materials (code, hardware)
- the ability to communicate honestly and empathetically
  about what we are doing and why. No more plausible-sounding
  "reasons you can tell your boss" (I forget where this meme
  is from... some technical video I saw)

# What does the author get out of this book?

- A world of safer, simpler, more reliable software (I hope)
- The discovery of beautiful (i.e. self-harmonious,
  connected, humane) means to create truth (i.e. effective
  change, knowledge)
- And thus a unification of Christopher Alexander's _quality
  without a name_ and Robert M. Pirsig's _Quality_.

# What does the reader get out of this book?

The satisfaction that comes from creating effective systems
via beautiful means, aided by:

- An appreciation for three major software paradigms
  and knowledge of how to combine them effectively
- Knowledge of software patterns that recur over and over
  again, in many languages and paradigms
- An understanding of when and why to apply each pattern
  (and what to watch out for if you don't)
- A toolbox of ways to improve the development process
- Familiarity with a comprehensive philosophy of software
  development
- The ability to recognize and avoid rhetorical and
  intellectual traps to which software engineers are
  vulnerable
- The ability to better explain their own ineffable wisdom
  to junior engineers and nontechnical people.
- A list of references to high-quality, digestible resources

# What is a computer?

- A machine for automating mental toil that people do not
  want to do and are not very good at.
- programming is the process of describing one's mental
  model of the requisite toil to the computer in sufficiently
  precise terms that the computer can perform the task.
- The hardest part of programming is not getting something to
  work, but gaining the confidence that you have actually made
  something that works correctly in all the situations where it
  needs to. The need for confidence in our solutions
  is why we have tests, debuggers, type systems, IDEs,
  theorem provers, and all the other tools we use on a daily basis.
- If you are not the only person using the program, you may
  have to convey that confidence to other people in order for
  the program to be effective in the world. How you do this
  depends on the person. If they are technically-minded, you
  may be able to explain the logic behind your solution in
  some detail. If they are an end-user of your program, or
  a nontechnical coworker who has commissioned the program,
  a clear and consistent user experience, built from concepts that
  exist in the user's understanding of the domain, can
  foster confidence.


One implication of this description is that AI programming
should really be thought of as a separate class of programming.
So few of the confidence-building techniques listed above work
for AI. The only way to gain confidence in the system is to
look at how it performs. As such, AI programming is beyond
the scope of this book.

# Semantic Versioning

# Beware of Overgeneralization

# Name Things What They Are, Not How They're Used

# Separate Decisions From Dependencies

# Don't Mock What You Don't Own. Actually, Don't Mock What You Do Own. Screw It, Don't Use Test Doubles At All

# Deliberate Thought is Insanely Expensive and Not Very Effective

# Get Better at Typing and Examining the Assumptions Behind Quantitative Data

"How much gain can we get by teaching people to type 10 times faster? Not a lot, unfortunately." —@catswetel
https://www.youtube.com/watch?v=cW3yM-K2M08

Do we want to do the same old bad things faster? Or do we want
to do things better, and go faster that way?

I've worked with developers who were not fast typists. They are the developers who say things like:

- "we shouldn't write tests because it takes too long"
- "we shouldn't refactor this because it will take too long"

Poor editing ability adds a mental and emotional burden to
the most fundamental operation of programming: changing
code.

If you are focusing on just getting characters onto the
page, your attention is taken away from the higher-level
properties of your program.

When I was starting out at my first programming job, my boss
saw me clicking around with the mouse and recommended that I
get familiar with keyboard navigation shortcuts. That was
some of the best advice I ever received. I can try out
different approaches and explain them to my pair much more
quickly because I don't have to spend a lot of effort to get
my thoughts into a concrete form.

(Don't make a religion out of keyboard shortcuts, though. At
some point, the shortcuts become more of a distraction than
a help. **The goal is not to reduce the *time* taken, but to
reduce the amount of conscious thought you must put into
routine editing tasks.**)

We programmers often think of ourselves as logical people.
As such, we give a lot of credence to arguments (like Cat's)
backed up by quantitative data. But often we don't question
the assumptions that the use of that data entails.
Quantitative data never shows the whole picture. Use it with
caution.
