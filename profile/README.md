## Agent Lang

Current LLM agents have limitations:

- Undetectable illusions when lack of information or tools, compromising LLM powers
- Hard to provide local tools, disabling features like auto-testing, auto-ssh and others

Agent Lang addresses the problem by designing a **client-side** language as a interface of LLM interaction, so that

- Each LLM response is a validated choice between **all valid responses**
  - Fallback to request of external information or tool
- Ability to register local tools with a type

## Roadmap

- [ ] Rust CLI for basic interaction
- [ ] Basic tools like auto-testing and code-generation
- [ ] IDE integration

## Contribution

There will be issues in each developing repository, feel free to contribute!

## Resources

- [Language Wiki](https://github.com/agent-lang/cli/wiki)

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
