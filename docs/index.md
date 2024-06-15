# Method Security

Welcome to Method Security's open source projects. Here, you can find links to all of the cybersecurity tools that we are currently building and supporting.

There are a number of different repositories within this Github organization, each one providing a scoped and granular set of capabilities focused on a particular problem area within the realm of cybersecurity. For a full listing of all currently available tools, please see our [Tools](./docs/tools.md) page or visit the any individual repository's Github Pages documentation.

If you're interested in contributing to any of our tools, or have ideas on a new tool, you're encouraged to first visit our organization's [Discussion](./community/contribute/discussions.md) page.

## FAQs

### Why build more cybersecurity tools? Doesn't the community have enough tools as is?

The community certainly has a large number of options available to it today, with a wide variety of truly amazing capabilities. However, we feel that the commonly felt tool fatigue has actually resulted in unnecessary bloat within a number of otherwise fantastic tools. This bloat can make tools hard to understand with their vast array of configuration flags.

Our tools have been built around two guiding principles:

1. They are tightly scoped and easy to use.

1. Each tool offers a tightly scoped set of capabilities, focusing the tool on a particular problem and minimizing the number of configuration values that it can accept.

1. They are designed with data integration and automation in mind.

1. Existing tools are often built with an operator first mentality, providing easy to read outputs for a human operating on the command line. We believe that for true cybesecurity automation, tools need to focus on machine readable outputs that make data integration and automation easy.

### How can I leverage my existing toolsuite?

Existing tools have large followings for a reason, they solve a problem and they get the job done. We are not seeking to rebuild the wheel with our tools. Rather, we want to stand on the shoulders of giants and leverage best in class capabilities where they exist, wrapping them with our two guiding principles in mind.

You can see examples of this in the [codeanalyze](https://github.com/Method-Security/codeanalyze) tool, which wraps [Semgrep's](https://github.com/semgrep/semgrep) amazing static analysis capabilities and provides some opinionated configuration values, or in [networkscan](https://github.com/Method-Security/networkscan) which leverages all the powers of [naabu](https://github.com/projectdiscovery/naabu) from the Project Discovery team.

If you have an existing tool that is providing you with valuable data insights that you feel is a good candidate to become a Method tool, open a [discussion](./community/contribute/discussions.md) to talk with us about it!

### How do I automate these tools and chain them together?

Since all the tools you'll find in this organization have been built with automation and ease of use in mind, you have a number of options available to you when designing your automation solution.

However, if you're looking for something a bit more out of the box, the Method Platform from [Method Security](https://method.security) has been designed from the ground up with these tools in mind, providing deep automation and autonomy capabilities that allow security teams of all sizes and maturity levels to get up and running quickly.
