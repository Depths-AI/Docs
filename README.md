# Depths AI docs

Depths AI is building a unified storage layer called **gyaan** for AI Agents and applications. The aim of the package is to enable developers to integrate vector-embedding database, chat history, analytics logs, knowledge graphs and a memory agent layer on top it, within few lines of code.

Currently, **gyaan** is **v0.1: The world's cheapest S3-compatible vector embedding database**. 

The project is and will proudly remain open-source\! For ease, you can also try out accessing our cloud version (currently in open-beta) at https://www.depthsai.com/auth/sign-up 

### Brief Roadmap

Leveraging a unified storage core for S3-compatible storage, we would introduce the remaining aspects of storage layer as:

1. v0.2: Chat history
2. v0.3: Analytics logs
3. v0.4: Knowledge graph
4. v0.5: Memory agent layer
5. v0.6-0.9: Improving storage flexibility, indexing quality, MCP support etc
6. v1.0: Production ready\!

### Install Gyaan DB

We recommend using [uv](https://docs.astral.sh/uv/) for managing your python projects. Command to add **gyaan** in an existing **uv** project is as follows

```bash
uv add gyaan
```

Or if you prefer pip installation for your python projects:

```bash
pip install gyaan
```