# llama-hoof
A highly-compact, minimal agent, written in Ruby, that runs on llama.cpp.

## Coming soon!
It currently runs great on my PC and I am iterating towards release. At the moment, I'm a little too busy *using* the thing to release it properly, but I wanted to 

## Suggested models
At present, there is no support for "thinking" models. Indeed, I've tested this on exactly one model: Qwen-Coder-Next. Specifically, I'm using the 3-bit quants by unsloth from HuggingFace: https://huggingface.co/unsloth/Qwen3-Coder-Next-GGUF

## Even better!
**This is my agent. There are many like it, but this one is mine.**

If this project interests you, you are probably more interested in better agents.

### OpenClaw
This is the OG and one of the two chief inspirations for llama-hoof. Written in typescript and not really suitable for resource-constrained circumstances, as it depends on a couple gigs worth of libraries.

https://github.com/openclaw/openclaw

### SubZeroClaw
This is the spiritual ancestor to llama-hoof. This is a compact agent that knows how to do one thing: run terminal commands. As it turns out, this is entirely enough, supposing a reasonably clever agent. Written in C with the only dependencies being cJSON and curl.

https://github.com/jmlago/subzeroclaw

### OpenHoof
This sits somewhere between the previous two in terms of complexity. Haven't really used it, but like llama-hoof, 

https://github.com/llama-farm/openhoof

## Questions and Answers

### Why `llama-hoof`?
Most agents are named with CamelCase, like OpenClaw. However, llama.cpp tools, as built using the default build options, look like `llama-cli`, `llama-server`. `llama-hoof` fits the trend and makes me happy.

### Why Ruby?
Ruby lets me iterate faster without worry. This is about me, nothing else. However, doing this with Ruby seems to let me skip a lot of extraneous garbage that exists on other languages. Getting OpenClaw running from source was a nightmare. TypeScript is incredibly awful to work with, especially in a context like this. In a restricted sandbox? Can we don't?

---

*Enough blogging. Get to work, Ben!*
