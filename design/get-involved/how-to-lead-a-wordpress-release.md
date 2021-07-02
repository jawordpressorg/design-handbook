# Leading a WordPress release

So you’re interested in leading a WordPress release as a designer? Or you’re not sure yet what it means? No problem, on this page you’ll find all the information you need to figure out what this role is about.

# What does a design release lead do?

WordPress releases four major new versions each year. These are planned by the [Release Squad](https://make.wordpress.org/core/handbook/about/release-cycle/wordpress-release-team-and-focus-leads/), a temporary team made up of people from each of the focus areas listed on [make.wordpress.org](http://make.wordpress.org) (core, editor, design, accessibility, security, etc)\*. This team determines which features should go into the next release.

As a design release lead\*\*, your task is to make sure the features selected for the release all have designs or design feedback. You’ll attend (online) meetings about the planned features as a representative of the design team, and make sure the designs get priority within the design team’s process. Note that most of the work will be in participating in discussions, making decisions and managing issues, not a lot of actual design work (at least by you). More on that later.

If you are interested in the more technical side of the WordPress release cycle as a whole, you can [read this section of the Core team handbook](https://make.wordpress.org/core/handbook/about/release-cycle/).

*\*Depending on the size of the release, not every focus area has to appoint a lead.*

*\*\*Also depending on the size of the release, there could be space for one design lead or two – one for core and one for the block editor.*

# What does a design release lead need?

Anyone could apply to become a lead, and it is a great way to learn more about WordPress and work on some cool features, but it comes with some responsibility. Take a moment to consider the ideal qualifications of a design lead candidate:

*   Some experience designing for WordPress. Which is to say, you know how the team operates, how to open and respond to Trac/Github tickets, and some familiarity with the existing features of WordPress.
*   The ability to write confident and well-meant constructive feedback. You’ll have to give your opinion on a lot of issues, and many of those people you may have never talked to before. And so it is important to be clear and to be respectful.
*   Time. The people working on a release will be scattered all over the world and all work at different times during the day. You’ll need about an hour or two each workday to keep up with everything that is happening. So it is important that you have time in your day for this, and have a somewhat flexible schedule.

# Becoming a design release lead

So you want to become a design release lead? Great! There’s isn’t much of an official application process, just let your team rep know sometime before or around a WordPress release that you’d be interested in leading the next one, and they can present your request to the release squad.

# So you’re a design release lead, now what?

Congratulations! Being a design lead is an interesting and intense task. You’ll have this role for about three months. Here are some tips to make the best of it:

## Reach out to the other release leads

When you become part of the major release squad, you’ll be asked to join a special Slack channel with the other members. There you can discuss operations and ask questions. Make sure to talk with the release leads for core and the editor. These people will select the features that will be worked on, and will know where design is still needed.

## Understand the scope of work

To make the most of your time as a design lead, you need to understand what is possible. A three-month release cycle may seem like a long time, but any new feature **needs to be ready before the Beta 1 deadline**. This is usually 3 to 4 weeks after the release cycle starts. After that there is a ‘feature freeze’, which means no new functionality will be added for that release, only the existing work-in-progress features will be improved.

As you may know, gathering feedback and iterating on designs takes time. That time increases the bigger a feature is. As an example, the redesign of Site Health, a feature that *already existed and worked* as a plugin, took several months before it was merged into WordPress 5.2. So unless a feature is already close to a final design and implementation, or is small enough that it’s easy to make, chances are it won’t be ready in time for beta.

Don’t worry if you feel overwhelmed trying to make that decision, the other release leads and the design team can help you with that.

## Focus your efforts

Hopefully you now have a somewhat better idea of what is realistic to accomplish. With this in mind, start by looking at everything that needs design for this release. You can find these issues on [Trac](https://core.trac.wordpress.org/query?status=accepted&status=assigned&status=new&status=reopened&status=reviewing&keywords=~needs-design-feedback&milestone=Future+Release&or&status=accepted&status=assigned&status=new&status=reopened&status=reviewing&keywords=~needs-design&milestone=Future+Release&order=priority) for WordPress core (the admin UI), and on [Github](https://github.com/WordPress/gutenberg/labels/Needs%20Design%20Feedback) for the block editor. You can filter the results to issues marked *needs design* or *needs design feedback* which are scheduled for *future release* (or the specific version number if that tag exists already).

Read up on those issues to see what is needed. If you have trouble understanding them, don’t hesitate to ask the design team or leave a comment on the issue. The [design team’s triage meetings](https://make.wordpress.org/design/handbook/workflows/weekly-design-triage/) are perfect for this.

Once you have an overview of which designs or feedback are needed, prioritize which features have the most chance of making it into the beta and focus on getting those ready.

## Keep Trac track of what’s going on

Once you have a list of the design issues for this release, we recommend that you write them down for yourself. When work starts happening on these issues and you get questions from all over the place, it can be challenging to keep track of which issues still need what and when. Put them all in a Google Doc/Sheet and write their status next to it (needs design, needs feedback, needs dev, ready for commit etc). You could also just rely on the filtered Trac/Github overviews I linked above, whatever works for you.

## Collaborate with Accessibility

It’s always good to keep a11y in mind when making designs, and especially during a release it will be good for these teams to work together so designs can be made quickly.

The design lead and a11y lead usually set up a joint meeting on Slack to get both teams to look at design and accessibility issues together.

## Attend meetings, but not too many

It’s tempting to add each team meeting to your calendar, but very quickly your whole day or week can become meetings. Be mindful of which ones you attend, and don’t be afraid to skip some.

We recommend the Core meetings on wednesday and the Bug Scrubs. These bring together all the release leads, and it’s a great place to stay up-to-date on what everyone is working on.

Next, of course, our own Design team triage meetings, and the accessibility meeting mentioned above. There you can review and work on issues together with other designers.

## Testing new designs

When people implement the designs, you might have to test whether they work/were built correctly. Sometimes people post screenshots in the issue, but especially for complex functionality, it can be useful to test it yourself. For this it is nice to have a development environment set up. You can read how to do this [here for WordPress](https://make.wordpress.org/core/handbook/testing/patch/) and [here for the block editor](https://make.wordpress.org/design/2021/03/03/testing-a-gutenberg-pull-request-pr/).

## After Beta

Once the first Beta is released, things become a little quieter for you. The big features have been merged, now is the time to refine designs, if needed. During this phase you’re probably okay if you check in on the issues on your list once or twice a week, or whenever someone pings you to take a look at something.

There is one important thing left to do:

## The About page

Each WordPress release has an [About page](https://make.wordpress.org/design/handbook/workflows/wordpress-core-about-page/) that details which new features are included and who worked on them. For each major release, the design team makes a new design for it. This can start right after Beta, as at that time it is known which features will be in the release. Usually, the marketing team writes the copy, and a designer is selected to work on the visuals.

This page needs to be done before Release Candidate 1, which is roughly one month before the planned release date.

## Release party

Before the final release, a chat will begin around 5-6 pm Europe time in the Release Squad channel. The people with Mission Control access will prepare the release and discuss anything that comes up during that time. If you don’t have anything to contribute, ask if you can help with anything like, proofreading posts, looking for missing links for such posts or other docs, etc. There is always something. Once the release begins it takes between 2 and 6 hours.

Also, if the release is happening in the middle of the night for you, or you have another important thing to do, don’t feel too pressured to attend. If everything went well up to this point, the release will probably go okay too.

# After the release

Congratulations! You shipped a WordPress release.

Celebrate by taking some time off. It can be an intense period, make sure to rest up appropriately afterwards.

Then if you want, you can write a post for the team blog to share your experience, recap which cool designs you got in the release, and which things you wish would have made it in but maybe weren’t ready in time. That way the next release lead will have something to start off with, and we can all learn from each other.