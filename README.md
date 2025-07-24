## 🧮 KQL Dynamic List Generator
Generate structured KQL dynamic() lists from plain text, CSVs, or IOC inputs — right from your browser. Built for threat hunters, SOC analysts, and anyone tired of hand-wrapping variables into queries.

🔗 Live site: [https://iocbox.com](https://iocbox.com)

📁 Source code: You're already here! 

## 🚀 Features
✅ Paste indicators or values (IP, domain, file hash, etc.) <br>
✅ Drag-and-drop CSV support (takes 1st column)<br>
✅ Deduplicate with a single click<br>
✅ Generate ready-to-use KQL: 
``` let IoC_list = dynamic(["value1", "value2", ...]); ```<br>
✅ Copy or download your output as `.kql`<br>
✅ Built-in dark mode for late-night hunting 🌙<br>

🧰 Quick Links to Common Tools

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


📸 Screenshot<br>
<p align="center">
  <img width="621" height="786" alt="image" src="https://github.com/user-attachments/assets/f5f7a29e-cb21-41dd-a096-a5649f5aeefe" />
</p>



🛠️ How to Use<br>
1. Enter or paste one value per line (or drop a CSV).<br>
2. Click Generate KQL.<br>
3. Copy it, use it in Microsoft Sentinel, Defender, or any Log Analytics workspace.<br>

## 🔐 Designed For<br>
- SOC Analysts
- Threat Hunters
- GRC & IR teams
- Blue team automation workflows

## 💡 Tips
- Name your variable in the “Dynamic List Name” field to keep your query readable.
- Clean your data with Deduplicate before generating.
- Use the toolbar at the top to pivot to VirusTotal or urlscan.io instantly.

## 🧰 Tech Stack
✅ ReactJS <br>
✅ HTML5 / CSS3 (dark mode by default)<br>
✅ GitHub Pages for free hosting<br>

## 🙏 Inspiration

This project was inspired by [alexverboon's KustoVars](https://github.com/alexverboon/KustoVars), a helpful tool for generating dynamic KQL variables.

## ✨ Contribute
Want to improve this? Open an issue or pull request — ideas like syntax highlighting, multi-var output, or IOC enrichment are welcome!

## 📄 License
MIT License. Use it, fork it, share it — just don’t sell it as-is.
