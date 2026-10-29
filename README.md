```
██╗  ██╗███████╗██████╗ ███╗   ██╗███████╗██╗     ████████╗ ██████╗ ██████╗  █████╗ ██╗   ██╗
██║ ██╔╝██╔════╝██╔══██╗████╗  ██║██╔════╝██║     ╚══██╔══╝██╔═══██╗██╔══██╗██╔══██╗╚██╗ ██╔╝
█████╔╝ █████╗  ██████╔╝██╔██╗ ██║█████╗  ██║        ██║   ██║   ██║██║  ██║███████║ ╚████╔╝
██╔═██╗ ██╔══╝  ██╔══██╗██║╚██╗██║██╔══╝  ██║        ██║   ██║   ██║██║  ██║██╔══██║  ╚██╔╝
██║  ██╗███████╗██║  ██║██║ ╚████║███████╗███████╗██╗██║   ╚██████╔╝██████╔╝██║  ██║   ██║
╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝╚═╝  ╚═══╝╚══════╝╚══════╝╚═╝╚═╝    ╚═════╝ ╚═════╝ ╚═╝  ╚═╝   ╚═╝

                                  from concept to runtime
```

Kernel is a small technical studio. We design and build websites, platforms, internal tools, automations and realtime 3D, then we ship them ourselves. You talk to the person writing the code, never to an account manager.

```
// what we build
```

Websites and product interfaces, made for the people who will use them every day. Custom platforms with their own APIs and databases. Dashboards, internal tools and workflows that connect your services, so nobody has to copy-paste between tabs anymore. AI agents plugged into real work. And interactive 3D on the web with Three.js and WebGL, sometimes Unreal when the project asks for it.

```
// process

  01 concept  -->  02 build  -->  03 runtime  -->  04 support
```

Most projects keep moving after launch. We stay on for the fixes, the upgrades and whatever new feature shows up next month.

```
// open source
```

We build our own tools first, then share the ones that hold up.

**[hail](https://github.com/kerneldottoday/hail)** lets you talk to your AI agents (Hermes, OpenClaw, Claude Code or any CLI) on your own machine or over SSH. Ask one agent for advice without letting it touch anything, or let your agents message each other with a policy and a log. Use it from a terminal, or plug it in as an MCP tool.

```
uv tool install hail-agent
```

[![hail in 45 seconds](https://raw.githubusercontent.com/kerneldottoday/hail/main/docs/demo.gif)](https://github.com/kerneldottoday/hail)

**[tiroir](https://github.com/kerneldottoday/tiroir)** is a filing cabinet for your sticky notes, on your own server. One drawer per project, tabs inside each drawer, and behind each tab a free wall of notes you can zoom, pan and drag around. Your AI agents can drop notes in it too: any script that writes a Markdown file in a folder gets its note filed in the right drawer, and when an agent asks a question, your answer is written back for it. No SDK, no token, no database, just one JSON file you own.

[![tiroir: open a drawer, pick a tab, work on the wall](https://raw.githubusercontent.com/kerneldottoday/tiroir/main/docs/demo.gif)](https://github.com/kerneldottoday/tiroir)

It also shares cabinets or single tabs through revocable links, keeps a 30-day trash, and installs on a phone's home screen.

```
pipx install git+https://github.com/kerneldottoday/tiroir
```

hail and tiroir work well together: hail carries the questions between agents, tiroir is where their reports wait for you.


```
// stack
```

React, Next.js, TypeScript, Node, Python, Tailwind, GSAP, Three.js, Webflow, Framer, Supabase, Vercel. If you already have a codebase, we work inside it.

```
// contact
```

[kernel.today](https://www.kernel.today) · [contact@kernel.today](mailto:contact@kernel.today) · [instagram @kernel.studio](https://www.instagram.com/kernel.studio/)

Open for new builds, wherever you are.
