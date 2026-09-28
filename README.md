```al
codeunit 50100 "Tharanga Chandrasekara"
{
    // Hi, I'm Tharanga. Most people call me TC 👋

    var
        Role: Label 'Co-founder & Head of Technology, Equerra';
        BasedIn: Label 'Auckland, New Zealand';
        Recognition: Label 'Microsoft MVP, Business Applications, since 2016';

    procedure Background()
    begin
        StartedAs('.NET developer');
        MovedTo('Dynamics NAV'); // learned it from 12 PDFs and a lot of late nights
        NowBuilding('Business Central');
        // 15+ years, 80+ projects, and I still write up what I learn
    end;

    procedure Focus() Topics: List of [Text]
    begin
        Topics.Add('Business Central architecture');
        Topics.Add('Azure Integration Services');
        Topics.Add('AI agents & Copilot adoption');
    end;

    [EventSubscriber(ObjectType::Codeunit, Codeunit::"BC Community", OnMeetup, '', false, false)]
    local procedure ComeSayHi()
    begin
        // Co-organiser: Auckland BC User Group · Directions Days of Knowledge ANZ
    end;
}
```

[![Blog](https://img.shields.io/badge/Blog-tharangac.com-21759B?style=flat-square&logo=wordpress&logoColor=white)](https://tharangac.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-tharangac-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tharangac)
[![X](https://img.shields.io/badge/X-@TharangaNC-000000?style=flat-square&logo=x&logoColor=white)](https://twitter.com/TharangaNC)
[![YouTube](https://img.shields.io/badge/YouTube-@tharangac-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://www.youtube.com/@tharangac)
[![Sessionize](https://img.shields.io/badge/Speaker-Sessionize-1AB394?style=flat-square)](https://sessionize.com/tharangac/)
[![Equerra](https://img.shields.io/badge/Work-Equerra-1F2A44?style=flat-square)](https://equerra.com)

---

## 🔭 Currently at Equerra

- 🐟 **Industry solutions on Business Central.** Building our eqMeat, eqFish, eqFnB and eqProduce products for meat processors, seafood and aquaculture, food and beverage manufacturers, and fresh produce growers.
- 🔌 **Integration architecture.** Connecting BC to the rest of the Microsoft stack with Azure Integration Services and Logic Apps, and moving customers off OData before it's deprecated.
- 🤖 **AI in real projects.** Designing agents in BC with the AI Toolkit, rolling out Copilot, and building AI assistants such as Jono, the assistant behind our project estimator.
- 🧑‍💻 **Leading the tech team.** Setting architecture and engineering standards so every build is done properly, not just done fast.
- 🧭 **CTO-as-a-Service.** Helping businesses plan their technology roadmap when they don't have a CTO of their own.

## 🧭 How I work

- **Do it properly.** Thoughtful engineering beats rushed delivery. Speed matters, but so do the principles.
- **Learn in public.** I got into this ecosystem by writing down what I learned. I still do.
- **Teams over heroes.** Great systems come from collaboration, not one person working through the night.
- **Product thinking.** Not just delivering features, but building things that genuinely help partners, consultants and customers.
- **Sustainable pace.** Long-term craft over burnout cycles.

## 📝 Latest from the blog

<!-- BLOG-POST-LIST:START -->
- [Days of Knowledge ANZ: The Idea That Started in a LinkedIn Message](https://tharangac.com/2026/09/days-of-knowledge-anz-the-idea-that-started-in-a-linkedin-message.html)
- [From Talking About AI to Adopting It: Why I Am Writing This Series](https://tharangac.com/2026/05/from-talking-about-ai-to-adopting-it-why-i-am-writing-this-series.html)
- [Directions Asia 2026: Two Sessions, Four Standouts, and a Shift in How I Think About Our Craft](https://tharangac.com/2026/05/directions-asia-2026-two-sessions-four-standouts-and-a-shift-in-how-i-think-about-our-craft.html)
- [OData Deprecation in Business Central: What Your Integration Architecture Needs Right Now](https://tharangac.com/2026/04/business-central-odata-deprecation-integration-architecture.html)
- [The Long Road Toward a New Beginning](https://tharangac.com/2026/02/the-long-road-toward-a-new-beginning.html)
<!-- BLOG-POST-LIST:END -->

➡️ More at [tharangac.com](https://tharangac.com/blog)

## 🎤 Speaking

### 🗓️ Upcoming

| When | Event | Where | Session(s) |
|---|---|---|---|
| Oct&nbsp;2026 | **Directions EMEA 2026** | Paris, FR | *When APIs Are Not Enough: Azure Messaging + Power Automate for Business Central* |

<!-- Add confirmed talks here, e.g.
| Mon&nbsp;YYYY | Event | City, CC | *Session title* |
-->

### 📼 Past

| When | Event | Where | Session(s) |
|---|---|---|---|
| Sep&nbsp;2026 | **Directions Days of Knowledge ANZ** | Melbourne, AU | 🧑‍🤝‍🧑 Co-organiser<br>*We Let AI Write Our AL for a Year: Here Is What Broke and What We Kept* |
| Jun&nbsp;2026 | BC TechDays 2026 | Antwerp, BE | *Designing Modern Integrations in Business Central* (with Vlad Leonov) |
| May&nbsp;2026 | Auckland BC User Group | Auckland, NZ | *What's New in BC: Field Report from Directions Asia 2026* |
| May&nbsp;2026 | Directions ASIA 2026 | Ho Chi Minh City, VN | *Building Intelligent Agents in Business Central: Design, Develop and Deploy with the AI Toolkit*<br>*Improve Enterprise Integrations using Azure Integration Services!* (with Steve Gichure) |
| Nov&nbsp;2025 | **BC Day ANZ 2025** | Sydney, AU | *It's Cool. It's Coming. And it's still a secret!* Agents session (with Tom Kapitan)<br>*Power Apps + Business Central: Transform Ideas into Apps with Copilot* (with Steve Gichure) |
| Nov&nbsp;2025 | Directions EMEA 2025 | Poznań, PL | *From Prompt to Power App: Use Copilot to Build Business Central-Connected Apps Fast* (with Steve Gichure)<br>*Real-World Messaging with Azure: Patterns That Power Your Integrations* (with Steve Gichure) |
| Jun&nbsp;2025 | BC TechDays 2025 | Antwerp, BE | *Integration Without Aggravation: Best Practices for Business Central* (with Vlad Leonov) |
| May&nbsp;2025 | Directions ASIA 2025 | Bangkok, TH | *App Building, Simplified: Power Apps + Copilot + Business Central* (with Steve Gichure)<br>*From Chaos to Connectivity: Integration Best Practices with Power Automate & Azure Services* (with Steve Gichure) |

<details>
<summary><b>2019 to 2024</b></summary>

| When | Event | Where | Session(s) |
|---|---|---|---|
| Nov&nbsp;2024 | **BC Day ANZ 2024** | Sydney, AU | Keynote introductions and ANZ roundtable (with Tom Kapitan)<br>*We are utilizing Azure's OpenAI to analyze data. Would you like to know more about it?* (with Steve Gichure) |
| Nov&nbsp;2024 | Directions EMEA 2024 | Vienna, AT | *From Data to Decisions: How to use Azure OpenAI to Enhance Analysis* (with Steve Gichure) |
| May&nbsp;2024 | Directions ASIA 2024 | Bangkok, TH | *We are utilizing Azure's OpenAI to analyze data. Would you like to know more about it?* (with Steve Gichure) |
| Nov&nbsp;2023 | Directions EMEA 2023 | Lyon, FR | *Unlocking Seamless Integration: Mastering Messaging Patterns with Azure and Business Central* (with Steve Gichure)<br>*Streamlining Integration Testing in Production: Unleashing the Power of Business Central Interfaces* (with Steve Gichure) |
| Jun&nbsp;2023 | BC TechDays 2023 | Antwerp, BE | *Feature Management for Continuous Delivery* (with Vlad Leonov) |
| Apr&nbsp;2023 | Directions ASIA 2023 | Bangkok, TH | *Power Automate or Logic Apps to use?* (with Steve Gichure)<br>*Mistakes made by developers during Business Central integration projects* (with Steve Gichure) |
| Nov&nbsp;2022 | Directions EMEA 2022 | Hamburg, DE | *Rapid deployment to Business Central and to Azure using BC APIs and Azure DevOps* (with Steve Gichure) |
| Nov&nbsp;2021 | NZ Business Applications Summit 2021 | Online | *Integrating BC with Power Platform* (with Wagner Silveira) |
| Nov&nbsp;2019 | NAV TechDays 2019 | Antwerp, BE | *Unlocking new integration potential for Dynamics 365 BC with Azure Event Grid and Azure Integration* (with Dmitry Katson) |
| Aug&nbsp;2019 | 365 Saturday ANZ tour | Melbourne, Wellington, Auckland, Christchurch | *Integrating Microsoft Dynamics 365 BC with IoT*<br>*Unlocking new integration potential for Dynamics 365 BC with Azure Event Grid and Azure Integration* |

</details>

Slides, recordings and write-ups: [Sessionize](https://sessionize.com/tharangac/) · [Blog](https://tharangac.com/blog) · [YouTube](https://www.youtube.com/@tharangac)

## 🤝 Community I run

| | What | My role |
|---|---|---|
| 🇦🇺 | **[Directions Days of Knowledge ANZ](https://tharangac.com/2026/09/days-of-knowledge-anz-the-idea-that-started-in-a-linkedin-message.html)**<br>Two-day BC conference for ANZ partners, devs, consultants and users. Started as a LinkedIn message, grew from Microsoft Reactor Sydney (2024) to the Microsoft Sydney office (2025) to a sold-out Melbourne event (2026). | Co-organiser with Tom Marshall, Tom Kapitan & Torben Kragelund, backed by Directions for Partners and Microsoft |
| 🇳🇿 | **[Auckland D365 Business Central User Group](https://github.com/Tharangac/usergroup-d365bc-akl-public)**<br>Regular meetups for the Auckland BC community: what's new, field reports, real-world patterns. | Co-organiser |
| 🌏 | **Directions ANZ Day** | Co-organiser |

Want to speak at a user group, sponsor an event or help out? [Say hi](mailto:hello@tharangac.com).

## 🧪 Things I've built and shared

| Repo | What it does |
|---|---|
| [demo-permissionprovider](https://github.com/Tharangac/demo-permissionprovider) | A feature-aware BC app that adapts to the capabilities it finds |
| [demo-genericattachment](https://github.com/Tharangac/demo-genericattachment) | Attach files to any entity in Business Central |
| [demo-vetappointment](https://github.com/Tharangac/demo-vetappointment) | AL demo app: vet appointment booking |
| [demo-d365saturday2019](https://github.com/Tharangac/demo-d365saturday2019) | IoT device registration and temperature thresholds, from D365 Saturday 2019 |

## 🛠️ Stack

![AL](https://img.shields.io/badge/AL-Business%20Central-00B7C3?style=flat-square)
![Azure](https://img.shields.io/badge/Azure-Integration%20Services-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Logic Apps](https://img.shields.io/badge/Azure-Logic%20Apps-0062AD?style=flat-square&logo=microsoftazure&logoColor=white)
![C#](https://img.shields.io/badge/C%23-.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Copilot](https://img.shields.io/badge/AI-Agents%20%26%20Copilot-6E40C9?style=flat-square&logo=githubcopilot&logoColor=white)

## 🧱 Off the keyboard

I build Lego, mostly Technic and trains. Same itch as the day job: clean design and systems where every part does something.

## 📬 Find me

- ✍️ Blog: [tharangac.com](https://tharangac.com)
- 💼 LinkedIn: [tharangac](https://www.linkedin.com/in/tharangac)
- 🐦 X: [@TharangaNC](https://twitter.com/TharangaNC)
- 📺 YouTube: [@tharangac](https://www.youtube.com/@tharangac)
- 📧 Email: [hello@tharangac.com](mailto:hello@tharangac.com)
