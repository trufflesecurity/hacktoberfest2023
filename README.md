# 🎉 Hacktoberfest 2023 🎉
## We're Participating!
Hello Open Source Enthusiasts! Truffle Security Co. is not just participating in Hacktoberfest 2023, we're upping the game with a Detector Competition!

<p align="center">
  <img alt="GoReleaser Logo" src="https://res.cloudinary.com/doqeieyc1/image/upload/v1695073802/TruffleHog_2_zxbt2b.png"  />
</p>

## 🏆 Detector Competition 🏆
What's In It for you? Not only do you get to improve an awesome Open Source project, but you also get a chance to win fabulous prizes!

🥇 1st Prize: MacBook Air

🥈 2nd Prize: Backpack

🥉 3rd Prize: Custom TruffleHog Swag

There are two categories for the Detector Competiton: _adding new detectors_ (1 point) and _fixing broken detectors_ (2 points). Each _merged_ PR with a `Hacktoberfest-Detector-Competition-New` or `Hacktoberfest-Detector-Competition-Fix` will be awarded 1 or 2 points, respectively.

### Broken Detectors (label: `Hacktoberfest-Detector-Competition-Fix` 2 points):
Below are some examples of fixes that will be considered. Make sure to supply ample evidence of the fix in the PR description.
- Correct the verification logic to accurately check detected secrets against the respective APIs.
- Correct the regular expressions used for secret detection.


### New Detectors (label: `Hacktoberfest-Detector-Competition-New` 1 point):

Submit a PR for a Detector you think would be valuable. Please follow the "Adding Detectors" contributing guidelines [here](https://github.com/trufflesecurity/trufflehog/blob/main/hack/docs/Adding_Detectors_external.md). In the new detector PR please provide documentation and supporting evidence for the validity of the detector's regular expressions.

### Competition Rules and Notes
- Start date for submissions: Sept 30.
- End date for submissions: Oct 31.
- Any submissions received after Oct 31 will be ineligible for the Detector Competition.
- New Detectors must be for valid credential providers. There is no benefit to the community for adding a Detector when the credential provider has no users. PRs that add invalid Detectors will be labeled `invalid`.
- Spam PRs will be marked with a `spam` label and closed. Contributors with 2+ spammy PRs are disqualified.
- Each week we will be posting the scoreboard to [this github issue](TODO)
- This competition is _first come first serve_. If multiple PRs for the _same_ Detector or Detector fix are opened, only the first one opened will be awarded points if merged.
    - However, if we request changes in a PR and that PR is abandoned (aka, no activity within 3 days), then we will consider new contributions.
- If you want your PRs to be excluded from the competition all you have to do is ensure that you don't apply the `Hacktoberfest-Detector-Competition-New/Fix` label.
- To avoid folks gaming the competition, we have a few criteria that must be met for a _new_ Detector to be considered. See the Detector Criteria section below.
- The final tally will be determined once all competition PRs submitted before November 1 are either merged or closed.


### Detector Criteria

#### 1. Documentation:
- **Provide screenshots or log outputs of passing tests**. This includes a local test of the detector _actually_ recieving a 2xx (i.e, proving verification). See the notes on testing [here](TODO)
- Provide steps on how to create an account and generate credential for the provider.
- Provide supporting evidence for the validity of the Detector's regular expressions.
- If possibile, cite official documentation or recognized community resources to justify the regex patterns used.
- **Make sure to redact any sensitive information**!

#### 2. Relevance:
- *Category*: The Detector should fall under one of the recognized categories such as:
  - Payment Processors (e.g., Stripe, PayPal, Square)
  - DevOps Tools (e.g., Jenkins, CircleCI, Travis CI)
  - Security Tooling (e.g., HashiCorp Vault, Fortify)
  - Infrastructure Platforms (e.g., AWS, Azure, GCP)
  - AI & Data Products (e.g., TensorFlow, Jupyter, AWS Sagemaker)
  - Collaboration & Communication (e.g., Slack, Trello, Zoom)
  - Databases (e.g, Supabase, MongoDB)
  - CSM (e.g, HubSpot, Zendesk)
- If a Detector doesn't fit into one of these categories but you believe it's crucial, provide a compelling case for its inclusion.

#### 3. User Base & Popularity:
- The credential provider the Detector is targeting should have a healthy and active user base.
- Consider using metrics like:
  - Monthly active users.
  - GitHub stars (if it's an open-source tool).
  - Presence in industry reports or articles.

### Getting Started
- Fork the TruffleHog Repository.
- Pick an issue labeled Hacktoberfest or create one that you'd like to work on.
- Commit and push your changes.
- Create a Pull Request.
- Sign the CLA.
- Wait for a review.

---

## General Contributions
We're also participating in the larget "Hacktoberfest" program sponsored by Digital Ocean. To maintain the integrity of TruffleHog, we're looking for meaningful contributions that align with the project's goals. Here are the types of contributions that are eligible:
- Issues labeled “Hacktoberfest”: We have a backlog of issues and some of them have been labeled “Hacktoberfest”.
- Expanding our Test Coverage: Add new tests or expand existing tests to increase our test coverage to make TruffleHog even more robust!


