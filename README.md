# Open source project flavors

I love open source and work with many open source projects and developers. What I've experienced is projects tend to cluster into broad categories that can be useful to nickname as "project flavors".

This page is a work in progress. Constructive feedback welcome.


## Diamond Project

**Broadly:** A solo developer starts a project, leads it, completes it, and does it so well that the project is effectively perfect-- like a diamond in the rough. The developer correctly thinks of the project as complete, and moves on to other interests.

**Examples:** sixarm_ruby_unaccent gem (my project), Rust pulldown_cmark (a project where I've recently done a pull request). (can you suggest more?)

**Typical Pros:** A diamond project works really well.

**Typical Cons:** Over the long term, due to technology shifts, the project is not maintained effectively. As users post issues, the developer doesn't want to spend the time or energy to respond in depth. New visitors to the project see a stack of unresolved issues, unanswered questions, untriaged pull requests, and documentation that has become outdated and incorrect.

**Typical Risks:** Very high long term risk if the developer is unavailable. With most open source there are ways that an individual user can fork the code, yet a fork typically can't have the same momentum, can't automatically leverage the same relations such as the project followers, issue trackers, mailing lists.

**Typical Variations:** A diamond project could be created by a small team, for example a few friends that have the same interest, or a small hackathon group, or a small coworker squad.


## Paladin Project

**Broadly:** A solo developer dedicates themselves to a project, including leading it over significant timelines, and into significant territories. The project does so well that it's a de facto tool of developers, and many people start to help the project, rely on it, and appreciate it. The leader is sometimes nicknamed a "benelovent dictator".

**Examples:** Linux, Ruby, Ruby minitest, Rust ripgrep, Actix. (can you suggest more?)

**Typical Pros:** Excellent codebases, great responsiveness, clear boundaries, willingness to help newcomers, and keen technical decisions.

**Typical Cons:** Paladin developers are so rare and valuable that they need time, energy, funding, and thick skin to handle dissent-- all these are often hard to come by.

**Typical Risks:** Burnout. Takeover by non-paladin agents, such as a big company; a past example is Google with Python; a current example is Amazon with Rust. Head-on competition from a company that is threatened by the paladin project; a long term example is Microsoft Windows head-on competition with Linux.

**Typical Variations:** A paladin project can scale up by adding lieutenants, which can work very well in practice. A paladin project can attempt to grow into adjancent offerings by delegating variations to other teams, which doesn't seem to work well in practice.


## Solopreneur Project

**Broadly:** A project that is started and led by one developer, or tiny team, and gets so successful that the project is paid offering. Some projects do payments for services, or support, or subscriptions.

**Examples:** Sidekiq, Avo, tarsnap . (can you suggest more?)

**Typical Pros:** Excellent for company use, because the developer is responsive, responsible, available, and accepting money.

**Typical Cons:** Can cause bifurcation, such as a developer offering a free tier and a paid tier, where the tiers don't play well with developer needs, such as for multiple environments for development/testing/production. Can cause licensing issues for redistribution.

**Typical Risks:** The solopreneur can't keep up with demand, or can't provide the service that a company wants as scale increases. To some extent, this can be handled by the solopreneur adding teammates, however in practice this is often a significant speed bump because it forces the project to shift from a solo effort into a team effort; this often requires new infrastructure and new ways of working.

**Typical Variations:** A solopreneur can add teammates to help.


## Startup Project

**Broadly:** A project that is searching for a sustainable scalable business model, in the style of a typical Silicon Valley technology startup, aiming for venture capital to grow very large and very fast.

**Examples:** OpenAI, FaunaDB. (can you suggest more?)

**Typical Pros:** If you can be a key customer, then the startup project team is typically very responsive and helpful, especially with service and support.

**Typical Cons:** If you're not a key customer, and also not directly aligned with the startup's growth goals, then it's difficult to get non-critical-path issues handled, or non-business-model pull requests merged. 

**Typical Risks:** If the startup succeeds, then the customer relationship with the startup may stagnate, or suffer, or become too unresponsive or too untenable to continue. If the startup fails, which happens much of the time, then you can be stranded. 


## Choir Project

**Broadly:** A project that evangelizes a significant perspective, often with many people helping, often with some communication challenges due to so many voices and so many viewpoints.

**Examples:** Rust, Nix, Homebrew, systemd. (can you suggest more?)

**Typical Pros:** If you're an ardent believer, then you'll love the project. 

**Typical Cons:** Coming up to speed on the project may be difficult due to a need to learn  "all the choir songs" so to speak i.e. to learn the technology implementation plus the group's many perspectives and group's history. Altering the project tends to be challenging because it involves many people, and many points of view, and combinations of business needs plus technology needs. 

**Typical Risks:** Poor documentation. Choir evangelism can come on too strong, or shut out alternate approaches, or overwhelm existing solutions, or accidentally miss important blind spots. Choir projects that get successful are ripe for takeover by a better-organized better-focused team that has a profit motive. 


## Briefcase Project

**Broadly:** A "briefcase project" is our nickname for this project flavor: a project that is started by an ongoing successful company, and with a planned agenda, significant budget, long term commitment, and a team including people who are skilled at coding, documentation, outreach, and promotion.

**Examples:** React, Rails, Kubernetes. (can you suggest more?)

**Typical Pros:** Well positioned, well marketed, well funded.

**Typical Cons:** Over the long term, the project is ultimately beholden to the company. This can cause significant tension between the company's interests and the users' interests. 

**Typical Risks:** If you're trying to do something that's not in alignment with the company's own goals, then you're off the golden path, and might be in the weeds.

**Typical Variations:** Some companies try to mitigate this by adding external advisors, or handing the reins to a nonprofit, or spinning off a community version, yet each of these approaches can cause bureaucracy and disalignment.
