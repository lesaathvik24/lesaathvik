# hi, I'm Lekhan

I take LLMs to production for a living, and on the side I build tools that stop AI from making me worse at my job.

At Agratas (Tata Group) I fine-tuned a 9B model for enterprise document translation and shipped an agentic RAG system on Llama 8B — vLLM, PyTorch, Celery, Postgres — that screens candidates end to end. It saves the company about $45K a year and ~945 hours of manual work, which is the only kind of eval that matters. Before that I co-wrote a virtual try-on paper at ICCEE 2025 in Singapore that beat the Flow-Style VTON baseline.

Somewhere along the way I noticed the tools I use all day are optimized to do the thinking for me, and that this was quietly working. I could review anything and build nothing. Most of what I make now pushes in the other direction.

### things I've built

**[vibesmith](https://github.com/lesaathvik24/vibesmith)** — an AI pair programmer that refuses to write your code. Two gate hooks physically block Claude from the source files you own; it writes every test, plans the roadmap with you, and teaches — but the tool call to edit your code fails before it executes. You write every line. I built it after catching myself unable to start a project from a blank file, which was alarming.

**[protos-harness](https://github.com/lesaathvik24/protos-harness)** — hooks, agents and skills for Claude Code: blocks secret leaks, dangerous commands, bad commits. Ships with vibezombie, which pauses the agent at every real decision and makes you choose between actual alternatives instead of pressing accept until the feature exists.

**[vocabmaxx](https://github.com/lesaathvik24/vocabmaxx)** — spaced repetition for words you meet in the wild. Capture, review, own.

**[dataset_llm_agent](https://github.com/lesaathvik24/dataset_llm_agent)** — an autonomous agent that generated 10k+ instruction-tuning pairs, cutting curation time by more than half.

older stuff — a three-agent pipeline that writes and sings a song about anything ([Melody_Agent](https://github.com/lesaathvik24/Melody_Agent)), a Discord bot that compresses the day's AI news into two minutes ([Daily_Ai_News_Bot](https://github.com/lesaathvik24/Daily_Ai_News_Bot)), currency-forgery detection in TensorFlow ([Fake-Currency-Detection](https://github.com/lesaathvik24/Fake-Currency-Detection)).

### now

Fundamentals, mostly. DSA every morning, ML from first principles, building in public in the evenings. The bar for any tool I keep: it has to make me faster *and* smarter. Faster and dumber is out.

lsaathvik24@gmail.com · [linkedin](https://linkedin.com/in/lekhansaathvik)
