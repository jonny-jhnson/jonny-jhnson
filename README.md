## Notable Projects

### Author
* [JonMon](https://github.com/jsecurity101/JonMon)
* [JonMon-Lite](https://github.com/jonny-jhnson/JonMon-Lite)
* [EtwInspector](https://github.com/jonny-jhnson/ETWInspector)
* [EtwWatcher](https://github.com/jonny-jhnson/ETWWatcher)
* [EventSight](https://github.com/jonny-jhnson/EventSight)
* [TelemetrySource](https://github.com/jsecurity101/TelemetrySource)
* [MSRPC-to-ATTACK](https://github.com/jonny-jhnson/MSRPC-to-ATTACK)
* [PowerParse](https://github.com/jsecurity101/PowerParse)
* [MSFT_DriverBlockList](https://github.com/jsecurity101/MSFT_DriverBlockList)
* [The Defenders Guide](https://github.com/Defenders-Guide/TheDefendersGuide) (Co-Author)

### Contributor
* [AtomicTestHarnesses](https://github.com/redcanaryco/AtomicTestHarnesses)
* [Seatbelt](https://github.com/GhostPack/Seatbelt)
* [MITRE ATT&CK — Access Token Manipulation](https://attack.mitre.org/techniques/T1134/001/)

---

## Research & Writing

### Windows Internals

#### Access Control & Tokens
* [Mastering Windows Access Control: Understanding SeDebugPrivilege](https://jsecurity101.medium.com/mastering-windows-access-control-understanding-sedebugprivilege-28a58c2e5314)
* [Exploring Token Members Part 1](https://jonny-johnson.medium.com/exploring-token-members-part-1-48bce8004c6a)
* [Exploring Token Members Part 2](https://jsecurity101.medium.com/exploring-token-members-part-2-2a09d13cbb3)
* [Changing a Primary Token's Session ID](https://jonny-johnson.medium.com/changing-primary-tokens-session-id-931c269aa08e)
* [Exploring Impersonation through the Named Pipe Filesystem Driver](https://medium.com/@jsecurity101/exploring-impersonation-through-the-named-pipe-filesystem-driver-15f324dfbaf2)

#### WMI Internals
* [Part 1: Understanding the Basics](https://jsecurity101.medium.com/wmi-internals-part-1-41bb97e7f5eb)
* [Part 2: Reversing a WMI Provider](https://jsecurity101.medium.com/wmi-internals-part-2-522f3e97709a)
* [Part 3: Beyond COM](https://jsecurity101.medium.com/wmi-internals-part-3-38e5dad016be)

#### Deep Dives
* [Windows ProjFS Internals: A Technical Deep Dive](https://jonny-johnson.medium.com/windows-projfs-internals-a-technical-deep-dive-302408e99ee9)
* [WSL, COM Hooking, & RTTI](https://jonny-johnson.medium.com/wsl-com-hooking-rtti-3abbf873d61f)
* [Event Tracing for Windows (ETW): Your Friendly Neighborhood IPC Mechanism](https://jonny-johnson.medium.com/event-tracing-for-windows-etw-your-friendly-neighborhood-ipc-mechanism-d255e9527130)
* [The Client/Server Relationship — A Match Made in Heaven](https://jonny-johnson.medium.com/the-client-server-relationship-a-match-made-in-heaven-219fe934a51b)
* [The Defender's Guide to Windows Services](https://medium.com/specter-ops-posts/the-defenders-guide-to-windows-services-67c1711ecba7)
* [Demystifying DLL Hijacking: Understanding the Intricate World of Dynamic Link Library Attacks](https://www.binarydefense.com/resources/blog/demystifying-dll-hijacking-understanding-the-intricate-world-of-dynamic-link-library-attacks/)

### Telemetry & Detection Engineering

#### Telemetry Research
* [A Voyage to Uncovering Telemetry: Identifying RPC Telemetry for Detection Engineers](https://specterops.io/wp-content/uploads/sites/3/2022/06/RPC_for_Detection_Engineers.pdf) *(research paper)*
* [The Truth About Telemetry: The Role of Primary and Secondary Telemetry Sources](https://jonny-johnson.medium.com/the-truth-about-telemetry-the-role-of-primary-and-secondary-telemetry-sources-6e57c867bb0c)
* [Telemetry Layering](https://jonny-johnson.medium.com/telemetry-layering-89185b5348ba)
* [Understanding Telemetry: Kernel Callbacks](https://medium.com/@jsecurity101/understanding-telemetry-kernel-callbacks-1a97cfcb8fb3)
* [Utilizing RPC Telemetry](https://jonny-johnson.medium.com/utilizing-rpc-telemetry-7af9ea08a1d5)
* [What the Fork: Exploring Telemetry Gaps in Microsoft's 4688 Event](https://jonny-johnson.medium.com/what-the-fork-exploring-telemetry-gaps-in-microsofts-4688-event-7d9e00979ea8)
* [Refining Detection: New Perspectives on ETW Patching Telemetry](https://jonny-johnson.medium.com/refining-detection-new-perspectives-on-etw-patching-telemetry-e6c94e55a9ad)
* Uncovering Window Events series:
  * [Part 1: TelemetrySource](https://medium.com/@jsecurity101/uncovering-window-security-events-ab72e1ec745c)
  * [Part 2: The Methodology](https://jsecurity101.medium.com/uncovering-window-security-events-8c11a9dcdf34)
  * [Threat Intelligence ETW](https://medium.com/@jsecurity101/uncovering-windows-events-b4b9db7eac54)
* [EtwWatcher](https://jonny-johnson.medium.com/etwwatcher-f657b3d60195)
* [Behind the Mask: Unpacking Impersonation Events](https://jonny-johnson.medium.com/behind-the-mask-unpacking-impersonation-events-fca909e08d00)
* Better Know a Data Source series:
  * [Process Integrity Levels](https://jsecurity101.medium.com/better-know-a-data-source-process-integrity-levels-8338f3b74990)
  * [Access Tokens (and why they're hard to get)](https://jsecurity101.medium.com/better-know-a-data-source-access-tokens-and-why-theyre-hard-to-get-7bc951eae0b9)
  * [Logon Sessions](https://jonny-johnson.medium.com/better-know-a-data-source-logon-sessions-1291538bb3a3)

#### Detection Engineering
* [Dataset Prioritization](https://jonny-johnson.medium.com/dataset-prioritization-539431731c20)
* [Abstracting Scheduled Tasks](https://jonny-johnson.medium.com/abstracting-scheduled-tasks-3b6451f6a1c5)
* [The Dark Side of Microsoft Remote Procedure Call Protocols](https://jonny-johnson.medium.com/the-dark-side-of-microsoft-remote-procedure-call-protocols-9ad5cb2d2b12)
* [Uncovering Adversarial LDAP Tradecraft](https://jonny-johnson.medium.com/uncovering-adversarial-ldap-tradecraft-658b2deca384)
* [Defending the Three-Headed Relay](https://jonny-johnson.medium.com/defending-the-three-headed-relay-17e1d6b6a339)
* [Bypassing Access Mask Auditing Strategies](https://jonny-johnson.medium.com/bypassing-access-mask-auditing-strategies-480fb641c158)

### EDR Research
* [Silencing the EDR Silencers](https://jonny-johnson.medium.com/silencing-the-edr-silencers-b703d7089821)
* [No Agent, No Problem: Discovering Remote EDR](https://jonny-johnson.medium.com/no-agent-no-problem-discovering-remote-edr-8ca60596559f)
* [Peeling Back the Mask: How the Threat Intelligence Provider is Protected](https://jonny-johnson.medium.com/peeling-back-the-mask-how-the-threat-intelligence-provider-is-protected-9968c38c5481)
* [Understanding ETW Patching](https://medium.com/@jsecurity101/understanding-etw-patching-9f5af87f9d7b)
* [Evadere Classifications](https://jonny-johnson.medium.com/evadere-classifications-8851a429c94b)
* [ThreadSleeper: Suspending Threads via GMER64 Driver](https://medium.com/@jsecurity101/threadsleeper-suspending-threads-via-gmer64-driver-b08824ca3b15)

### AI & Agentic Security
* [A Deep Dive into Codex Windows Sandbox](https://jonny-johnson.medium.com/a-deep-dive-into-codex-windows-sandbox-a2489bf4ae91)
* [RAG, ICL, and Windows Events: Building a Human-Guided Security Analyst](https://jonny-johnson.medium.com/rag-icl-and-windows-events-building-a-human-guided-security-analyst-395faa6769a4)

---

## Presentations
* [A Voyage to Uncovering RPC Telemetry — SO-CON 2020](https://www.youtube.com/watch?v=TEHQwgd7i7Y)
* [Understanding Technique Abstraction for Detection Engineers Workshop — SO-CON 2020](https://www.youtube.com/watch?v=Xxj-jvNQWHU&t=45s)
* MSRPC ATT&CK Mapping — EU MITRE 8th Workshop
* [Insights into Highly Valued Data Sources — ATT&CKcon 3.0 (2022)](https://www.youtube.com/watch?v=ba2e9pWxboU&t=864s)
* [Once Upon A Login: How Logon Sessions Help Defenders See the Bigger Picture (2022)](https://youtu.be/dFw5eoWSXWg?t=10552)
* [Mapping Detection Coverage — DEATHCon 2022](https://youtu.be/tNfWSE4M4qg)
* [JonMon](https://github.com/jsecurity101/Presentations/blob/main/JonMon.pdf)
* [Empowering Research with Defensive Tooling](https://youtu.be/obce8VdFMeU?si=pY9ZrZtg3FEMDlZh)
