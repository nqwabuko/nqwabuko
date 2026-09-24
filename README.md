# Charlie O'Donoghue

Solutions architect, EV charging infrastructure. I build small tools to think with, read
further into a problem than it needs, and write up what I find so I stop forgetting it.

Day job: architecture and delivery for large charging networks. This is the other half.

### Repos

**[agent-mailbox](https://github.com/nqwabuko/agent-mailbox)**: Two agents, two repos, one
folder between them. Coordination through a shared append-only record instead of messages,
which is how termites build a nest with no coordinator. Companion to
[an article](https://lnkd.in/p/edsxwNbm) on why the 1959 stigmergy literature beats most
framework docs.

**[curio-engine](https://github.com/nqwabuko/curio-engine)**: A menu-bar capture tool that
grew into a zettelkasten. Jot an idea, a headless model call enriches it, and it proposes
connections with a stated reason. Swift.

**[pace](https://github.com/nqwabuko/pace)**: A break reminder that knows when you're on a
call. 20-20-20 for your eyes, plus movement. Swift, menu bar only.

**[mesa](https://github.com/nqwabuko/mesa)**: Floating-first macOS window layouts on
Hammerspoon. Manages nothing until asked, then rearranges itself for meetings.

### How I work

I'm interested in systems that settle. Feedback, dynamics, what makes a loop stop instead
of wander. The agent work is one question: does this process have a quantity that
only moves one way?

Using agents daily taught me one thing above the rest. What matters is the structure
outside the model: durable records, state you declare rather than infer, and knowing where
a human has to make the call. When I get it wrong, I inferred where I should have declared.

Most of this started from a primary source, not a blog post. Grassé on stigmergy,
Prigogine on when a system stops being predictable, Hickey on simple versus easy.
Understand the mechanism, build the small version.

Clojure by preference, Swift when it has to be native, working my way into Rust and Go.

None of this is my field, which is the point.
