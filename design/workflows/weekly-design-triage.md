# Weekly design triage

Weekly triage session are run in Slack every Monday 17:30 UTC. The goal of this is to within half an hour triage as much as possible, if it’s only a few that is also ok.

### Reports

There are 3 reports that need triaging during weekly design. Ideally pick one and focus on it.

*   [‘Needs UI/UX feedback’ core](https://core.trac.wordpress.org/report/35?sort=modified&asc=1&page=1): this is most common one used in triage
*   [‘Needs designer’ core](https://core.trac.wordpress.org/query?status=accepted&status=assigned&status=new&status=reopened&status=reviewing&keywords=~needs-design&order=priority)
*   [‘Needs designer’ meta](https://meta.trac.wordpress.org/query?status=accepted&status=assigned&status=new&status=reopened&status=reviewing&keywords=~needs-ui&keywords=~needs-ux&keywords=~ui-feedback&keywords=~ux-feedback&group=component&col=id&col=summary&col=keywords&col=status&col=owner&col=type&col=priority&col=component&order=keywords&report=9)
*   [‘Needs design feedback’ Gutenberg](https://github.com/WordPress/gutenberg/issues?q=is%3Aissue+is%3Aopen+label%3A%22Needs+Design+Feedback%22)
*   [‘Needs design’ Gutenberg](https://github.com/WordPress/gutenberg/issues?q=is%3Aissue+is%3Aopen+label%3A%22Needs+Design%22)

### Preparation

*   Choose one of the reports.
*   If you are using a report with ‘modified’ as a field, click it to start with oldest tickets.

### Running triage

*   Open triage by saying: <triage> and if possible use ‘/here’ to announce start.
*   Introduce triage saying what is about to happen. You can say something like this:

> Welcome to this triage session. In design triage the goal is to move on as many tickets as we can in this half an hour. This can be through closing, asking for more information or even a screenshot. Let’s get started!

*   Link the report you are using so everyone can follow along.
*   Pick the oldest ticket, open in your browser and then copy the link to share with everyone in Slack.
*   Give people a little time to read the ticket.
*   Ask if anyone has any ideas. If you have your own mention those.
*   Discussion should happen in Slack but once it seems to reach a point ask:

> Would anyone like to update the ticket or shall I?

*   The ticket then can be updated and ‘moved on’ in a number of ways:
    *   Giving feedback.
    *   Asking for more information: this would be for example a screenshot.
    *   If no feedback is needed then remove the keywords.
    *   If feedback has been given add ‘has’ to the keywords. For example: ‘has-ux-feedback’.
    *   Should this not be an issue anymore you can close, but this is rarely the case and usually your response is one of the above.
*   Congratulations you’ve triaged that ticket! Now onto the next and keep going until you reach 30 minutes.
*   Close out triage by thanking everyone and saying </triage>.