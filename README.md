## 🧮 KQL Dynamic List Generator
Generate structured `KQL dynamic()` lists from plain text, CSVs, or IOC inputs — right from your browser.  
Built for threat hunters, SOC analysts, and anyone tired of hand-wrapping variables into queries.

🔗 Live site: [https://iocbox.com](https://iocbox.com)  
📁 Source code: You're already here!

---

## 🚀 Features

✅ Paste indicators or values (IP, domain, file hash, etc.)  
✅ Drag-and-drop CSV support (takes 1st column)  
✅ Deduplicate with a single click  
✅ Generate ready-to-use KQL:

```kql
let IoC_list = dynamic(["value1", "value2", ...]);
```

✅ Copy or download your output as `.kql`  
✅ Built-in dark mode for late-night hunting 🌙  
✅ One-click access to tools and sandboxes  

---

## 🧰 Quick Links – Lookup Tools

- **VirusTotal**  
  Security scanner for files and URLs.  
  🔗 [https://virustotal.com](https://virustotal.com)

- **urlscan.io**  
  Analyze URLs and visualize network traffic.  
  🔗 [https://urlscan.io](https://urlscan.io)

- **MXToolbox**  
  Lookup DNS, mail server, blacklist, and SPF records.  
  🔗 [https://mxtoolbox.com](https://mxtoolbox.com)

- **DomainTools**  
  Investigate domain registration, WHOIS, and risk scoring.  
  🔗 [https://whois.domaintools.com](https://whois.domaintools.com)

---

## 🧪 Quick Links – Sandboxes

- **ANY.RUN**  
  Dynamic malware sandbox with visualized execution.  
  🔗 [https://app.any.run](https://app.any.run)

- **Joe Sandbox**  
  Advanced malware analysis platform.  
  🔗 [https://www.joesandbox.com](https://www.joesandbox.com)

- **Hybrid Analysis**  
  File and URL malware analysis.  
  🔗 [https://www.hybrid-analysis.com](https://www.hybrid-analysis.com)

- **OTX AlienVault**  
  Threat intelligence from global community pulses.  
  🔗 [https://otx.alienvault.com](https://otx.alienvault.com)

---

## 🛠️ Quick Links – Analyst Tools

- **CyberChef**  
  Web-based encoding, decoding, encryption, and analysis toolkit.  
  🔗 [https://gchq.github.io/CyberChef/](https://gchq.github.io/CyberChef/)

- **Regex101**  
  Test, debug, and share regular expressions.  
  🔗 [https://regex101.com](https://regex101.com)

- **SSL Labs Checker**  
  Test SSL configuration and rating.  
  🔗 [https://www.ssllabs.com/ssltest/](https://www.ssllabs.com/ssltest/)

- **Base64 Decoder**  
  Convert Base64 to human-readable text.  
  🔗 [https://base64.guru/converter/decode/text](https://base64.guru/converter/decode/text)

- **URL Encoder/Decoder**  
  Encode or decode URL components.  
  🔗 [https://urlencoder.org](https://urlencoder.org)

- **Diagrams builder**  
  Build diagrams and timelines of events.  
  🔗 [https://app.diagrams.net/](https://app.diagrams.net/)
---

## 📸 Screenshot

<p align="center">
  <img width="980" height="539" alt="image" src="https://github.com/user-attachments/assets/f5a9f126-4106-4df9-b1ff-5e49e6f52a8b" />
</p>

---

## 🎯 How to Use

1. Enter or paste one value per line (or drop a CSV file).  
2. Click **Generate KQL**.  
3. Copy it or download your `.kql` file. Use it in Microsoft Sentinel, Defender, or any Kusto environment.

---

## 🔐 Designed For

- SOC Analysts  
- Threat Hunters  
- GRC & IR Teams  
- Blue Team automation workflows  

---

## 💡 Tips

- Name your variable in the “Dynamic List Name” field to keep queries readable.  
- Clean your data with **Deduplicate** before generating.  
- Use sidebars to quickly pivot to sandboxes and analysis tools.

---

## 🧰 Tech Stack

✅ ReactJS  
✅ HTML5 + CSS3 (dark mode by default)  
✅ GitHub Pages for hosting  

---

## 🙏 Inspiration

This project was inspired by [alexverboon's KustoVars](https://github.com/alexverboon/KustoVars), a great CLI-friendly approach to building KQL structures.

---

## ✨ Contribute

Want to improve this? Open an issue or pull request!  
Ideas like syntax highlighting, tag-based output, or IOC enrichment are all welcome.

---

## 📄 License

MIT License. Use it, fork it, improve it — just don’t sell it as-is.
