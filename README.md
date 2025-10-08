# boring_tech_simulator

# Choose Boring Technology: Interactive Simulator

An interactive decision-tree game that teaches Dan McKinley's "Choose Boring Technology" philosophy. Built for a Data Science & AI master's program.

**🎮 [Play it here](https://[your-username].github.io/boring-tech-simulator/)**

## What is this?

You run a startup. You have 3 "innovation tokens" to spend on new technology. Make decisions across 4 scenarios (database, caching, frontend, AI/ML) and try to ship product without drowning in operational complexity.

Based on [Dan McKinley's 2015 essay](https://mcfunley.com/choose-boring-technology) that argues: most startups fail because they waste attention on shiny tech instead of solving business problems.

## The Meta-Joke

This is a project *about* choosing boring technology, so it's built with:
- Plain HTML, CSS, vanilla JavaScript
- Zero dependencies, no build process, no npm
- Single file: `index.html`
- Deploy by uploading to GitHub Pages

**It will run unchanged for 10 years.**

## Key Philosophy

- **Innovation Tokens**: You only get ~3. Spend them wisely.
- **Operational Burden**: Each tech choice adds maintenance cost
- **Known vs Unknown Unknowns**: Boring tech has well-understood failure modes
- **Ship Product**: Your job is business value, not infrastructure

## Real Examples Included

- **Etsy's Python Layer**: Wasted years on pointless middleware
- **Etsy's Activity Feeds**: Scaled 20x on boring tech with zero attention  
- **Knight Capital**: Lost $440M in 45 minutes with untested "innovative" code

## Local Development

```bash
# Clone and open
git clone https://github.com/alexandreblivet/boring-tech-simulator.git
open index.html

# That's it. No install needed.
```

## AI Tools Used

- **Claude 4.5 Sonnet**: Generated application through conversational prompting
- **Process**: ~10 iterations of refinement and debugging
- **Learnings**: AI excels at creating complete, working artifacts when given clear requirements and constraints

## Why This Matters (Especially for Data Science)

In 2025, everyone wants to use LLMs, vector databases, and RAG pipelines for everything. But most problems need:
- A SQL query
- A simple scikit-learn model  
- Boring, reliable infrastructure

**The simulator's Scenario 4** shows this: you can spend 2 innovation tokens on GPT-4 + Pinecone + LangChain... or just use logistic regression and ship in 2 weeks.

## Credits

- **Essay**: Dan McKinley (2015)
- **Code**: Generated with my pal Claude (Anthropic)
- **Design**: Brutalist aesthetic, deliberately minimal

## License

MIT - Do whatever you want with this.

---

*"Your job is keeping the company in business. The 'best' tool is the one that occupies the 'least worst' position for as many problems as possible."* - Dan McKinley
