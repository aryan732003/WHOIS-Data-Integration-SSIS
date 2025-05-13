# 🚀 WHOIS Data Integration – SSIS Project

This SSIS project automates downloading, extracting, transforming, and loading WHOIS data into SQL Server. It supports cybersecurity teams by organizing and preparing WHOIS data for fraud detection and analysis.

## 🔧 Features
- 📥 Dynamic file download from URLs stored in a config table
- 🗂️ WinRAR extraction of compressed CSVs
- 🔄 Data transformation and load into date-based tables
- 📬 Real-time email alerts using C# (on success/failure)
- 📁 Organized local folders by current date (YYYYMMDD)

## 🛠 Technologies Used
- SQL Server Integration Services (SSIS)
- SQL Server
- WinRAR (for extraction)
- C# (for script-based email notifications)

## 📂 Key Files
- `WhoisDataIntegration.dtsx` – Main SSIS package
- `Project.params` – SSIS parameters
- `WhoisDB Integration.dtproj` – SSIS project file
- `WhoisDB Integration.sln` – Visual Studio solution

## 📝 Usage Notes
- Ensure WinRAR is installed and its path set in the Execute Process Task.
- Update email settings in the C# Script Task.
- Make sure your config table is populated with download URLs.

## 📸 Screenshots
![Webpage.png](screenshots/Webpage.png)
![ControlFlow.png](screenshots/ControlFlow.png)
![Data.png](screenshots/Data.png)
![DataFlow.png](screenshots/DataFlow.png)

![C###.png](screenshots/C###.png)
![Config.png](screenshots/Config.png)

![DomainList.png](screenshots/DomainList.png)
![Email.png](screenshots/Email.png)
![PackageRun.png](screenshots/PackageRun.png)
![Success.png](screenshots/Success.png)
![Varirable.png](screenshots/Varirable.png)



> 💡 This project demonstrates advanced SSIS skills, including automation, C# scripting, and robust error handling for real-world data engineering workflows.
