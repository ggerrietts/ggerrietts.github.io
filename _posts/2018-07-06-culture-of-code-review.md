This morning I'd like to talk about code review. Much of what I will say echoes the content of a
[talk](https://ggerrietts.github.io/talks) I gave a couple years back, with a slightly different take.

I am partial to code review. I wouldn't say I like it more than coding, but I will push for a culture of code review
before most other practices. Maybe my background in English has predisposed me to like workshopping, but I think code
review is important.

Code review has a handful of major functions. Most published papers deal with the (readily quantified) impact of code
review on defect rate. This aspect alone should sell an organization on the value of code review. But many stop here.

Focusing too narrowly on bug hunting will miss other key aspects of review. The second benefit most people identify is
how review will spread out information. This helps eliminate single points of failure and promotes team cohesion.

This is still not my favorite benefit, though! The mentorship opportunity matters most to me.

In creative writing classes, we workshop our art. Writers take turns presenting work and receiving comments.

Code review is similar, though more frequent & with fewer people.

When preparing for workshops, instructors teach key reviewing skills up front. Code review, by contrast, is generally
learned from example and experience. Consequently, code reviews are not always as helpful as they could be, especially
along the learning and teaching edges.

Fortunately, most of the wisdom I have on the topic distills down neatly into a reductive list of bullet points that
have had their nuance ripped away.

Do:
* Set aside plenty of time for review. Don’t try to squeeze it in.
* Treat review as the opening exchange of a conversation about code.
* Focus on suggested improvements, not identified problems. 
* Sweep exhaustively for bugs, but pick only a handful of features to discuss. 
* Meet the programmer where they are at. Pitch improvements they can apply, not blindly obey. 
* Use positive feedback liberally and be conservative with negative feedback. 
* Focus closely on improving the readability and maintainability of code.
* Be more curious than critical.

Don’t:
* Be a dick. Seriously.
* Require nonessential changes, even if you discuss them.

Code review should be an opportunity explore what is valuable, what is idiomatic, and what is personal preference.
Asking and answering questions promotes better understanding of the code and offers opportunities to learn.

Be mindful of the person on the other end of the review. Call out specifically things that really ought to be fixed, and
identify the things that you're mostly just wanting to talk about. Don't underestimate the value of a compliment, or the
cost of a criticism.

Many organizations struggle to develop talent or provide good mentorship for junior programmers. Code review, when
focused on developing a code-centered conversation, addresses both of these needs. It helps programmers of all levels
grow and mature.
