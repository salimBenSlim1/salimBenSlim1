<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=240&section=header&text=Salim%20Ben%20Slim&fontSize=56&fontColor=ffffff&fontAlignY=36&animation=fadeIn&desc=Full-Stack%20Engineer%20%C2%B7%20Debugging%20%26%20Systems%20Internals&descSize=20&descAlignY=58" alt="Salim Ben Slim — Full-Stack Engineer, Debugging and Systems Internals" width="100%" />

<a href="https://github.com/salimBenSlim1">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=900&color=00E5FF&center=true&vCenter=true&width=720&height=50&lines=Life+is+a+debugging+session.;Building+real+products+%F0%9F%9A%80;Tracing+unexpected+behavior+%F0%9F%94%8D;Learning+how+systems+really+work+%F0%9F%A7%A0;Reproduce+%E2%86%92+Trace+%E2%86%92+Understand+%E2%86%92+Fix+%E2%86%92+Verify" alt="Typing animation" />
</a>

<br />

<img src="https://komarev.com/ghpvc/?username=salimBenSlim1&label=Profile%20views&color=0e75b6&style=for-the-badge" alt="Profile views" />
<img src="https://img.shields.io/badge/Based%20in-Tunisia%20🇹🇳-red?style=for-the-badge" alt="Tunisia" />
<img src="https://img.shields.io/badge/Open%20to-Collaboration-2ea44f?style=for-the-badge" alt="Open to collaboration" />

</div>

---

### `> whoami`

I'm a full-stack developer based in **Tunisia**. I build web applications and SaaS products, from the interface to the backend and deployment.

What keeps me curious is the part you don't always see: **why a system behaves the way it does**, especially when something breaks.

- 🛠️ **Building:** Full-stack applications, APIs, and real-time experiences.
- 🔍 **Investigating:** Node.js internals, async execution, HTTP, and security.
- 🧠 **Thinking about:** System design, reliability, performance, and debugging.
- 🎯 **My approach:** Reproduce → Trace → Understand → Fix → Verify.

### `> exploring --under-the-hood`

I don't just want to know what code does. I want to understand how it actually executes, and my curiosity goes below the application layer: into memory, CPU execution, and the machinery that turns source code into runtime behavior.

<div align="center">

<img src="./assets/cpu-memory.svg" alt="Animated diagram of the CPU fetching instructions from RAM, executing them, and writing results back" width="100%" />

</div>

**How I picture it:** the CPU is fast but forgetful. It only holds a handful of values in **registers**, so everything else lives in **RAM**. The **instruction pointer** (`RIP`) says which instruction runs next; the CPU **fetches** it from memory, **decodes** it, **executes** it in the ALU, and **writes the result** back to a register or to memory. Every bug I chase eventually comes down to that loop.

- 🧱 **CPU & memory:** registers, the stack and heap, virtual memory, calling conventions, and how stack frames change on every function call.
- 🐞 **Debugging & reverse engineering:** stepping through code with breakpoints, reading disassembly, and inspecting registers and memory.
- 🌐 **Runtime internals:** the Node.js event loop, V8, async execution, and how errors propagate.
- 🔐 **Networking & security:** TCP/IP, HTTP parsing, reverse proxies, and where application security breaks down.

<details>
<summary><b>What a single line of code looks like to the CPU</b></summary>
<br />

```c
int x = a + 5;
```

```asm
mov  eax, DWORD PTR [rbp-4]   ; load `a` from the stack (memory) into a register
add  eax, 5                   ; the ALU adds 5 inside the CPU
mov  DWORD PTR [rbp-8], eax   ; store the result back to `x` on the stack
```

Three instructions, two trips to memory, one trip through the ALU. Watching this happen in a debugger is what makes "it works" turn into "I know why it works."

</details>

> My favorite question isn't *"why did this fail?"* but *"what exactly happened between the instruction and the failure?"*

### `> tech --stack`

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=ts,js,py,cpp&perline=8" alt="Languages" />

**Frontend**

<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,html,css&perline=8" alt="Frontend" />

**Backend & Data**

<img src="https://skillicons.dev/icons?i=nodejs,express,postgres,mongodb,mysql,redis&perline=8" alt="Backend and data" />

**Debugging & Systems**

<img src="https://img.shields.io/badge/GDB-A42E2B?style=for-the-badge&logo=gnu&logoColor=white" alt="GDB" />
<img src="https://img.shields.io/badge/IDA%20Free-1f6feb?style=for-the-badge" alt="IDA Free" />
<img src="https://img.shields.io/badge/x64dbg-30363d?style=for-the-badge" alt="x64dbg" />
<img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white" alt="Wireshark" />
<img src="https://img.shields.io/badge/Assembly-x86--64-6e40c9?style=for-the-badge" alt="x86-64 Assembly" />

**Infrastructure & Tools**

<img src="https://skillicons.dev/icons?i=docker,aws,nginx,git,github,githubactions,linux&perline=8" alt="Infrastructure and tools" />

</div>

### `> experience --highlights`

<table>
<tr>
<td width="50%" valign="top">

**☕ CoffAI — Café SaaS**

Built and deployed a café management platform with ordering workflows, role-based access, real-time updates, and station-based printing.

<img src="https://skillicons.dev/icons?i=react,nodejs,postgres,socketio&perline=8" alt="CoffAI stack" />

</td>
<td width="50%" valign="top">

**⚙️ Full-Stack Product Engineering**

Worked on production web applications spanning frontend interfaces, backend APIs, authentication, database workflows, and deployments.

<img src="https://skillicons.dev/icons?i=nextjs,express,mongodb,aws&perline=8" alt="Product engineering stack" />

</td>
</tr>
</table>

> Some of my professional work is in private repositories. I share independent experiments and public projects as they become ready.

### `> interests --deep-dive`

| Building systems | Understanding systems |
| :--- | :--- |
| SaaS applications and APIs | Node.js event loop and async behavior |
| Real-time features | Error propagation and observability |
| Authentication and authorization | HTTP parsing and application security |
| Database-backed workflows | Performance and scalability trade-offs |

### `> github --activity`

Explore my [public repositories](https://github.com/salimBenSlim1?tab=repositories) and [contribution history](https://github.com/salimBenSlim1?tab=overview).

<div align="center">

<img src="https://streak-stats.demolab.com?user=salimBenSlim1&theme=tokyonight&hide_border=true&background=0d1117" alt="GitHub streak" />

<br />

<img height="190" src="./profile-summary-card-output/tokyonight/3-stats.svg" alt="GitHub stats" />
<img height="190" src="./profile-summary-card-output/tokyonight/2-most-commit-language.svg" alt="Most used languages" />

<br />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/salimBenSlim1/salimBenSlim1/output/github-snake-dark.svg" />
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/salimBenSlim1/salimBenSlim1/output/github-snake.svg" />
</picture>

</div>

<details>
<summary><b>How I approach debugging</b></summary>
<br />

```text
Observe the symptoms
    ↓
Reproduce the problem
    ↓
Trace the execution path
    ↓
Explain the root cause
    ↓
Fix the behavior
    ↓
Verify the assumptions
```

A passing test tells me something works under the tested conditions. Understanding the execution path helps me reason about what happens outside them.

</details>

---

<div align="center">

### Build. Debug. Understand. Improve.

<sub>Thanks for stopping by — feel free to explore my repositories.</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%" alt="" />

</div>
