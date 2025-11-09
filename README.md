# 6-12 Month Penetration Testing Learning Plan
## Web → Mobile → AI Red Teaming Specialization

---

## Overview

**Your Background:**
- 0.5 years penetration testing experience (web & mobile)
- ~170 PortSwigger Academy labs completed
- Preparing for BSCP exam
- Goal: Master web → mobile → pivot to AI red teaming
- Learning style: Mix of building, breaking, and structured learning
- Timeline: 6-12 months

**Certification Path:**
1. Month 2: BSCP (Burp Suite Certified Practitioner)
2. Month 4-5: eWPTXv2 (optional, if employer covers)
3. Month 8: MAPT or MSTG (Mobile certification)
4. Month 12+: AI red team positioning (portfolio > certs)

---

## Phase 1: Months 1-2 - BSCP Exam Prep & Advanced Web

### Goal
Pass BSCP and start pushing beyond the basics

### Weeks 1-2: BSCP Final Prep

**Monday-Wednesday:**
- Complete any remaining "Expert" level labs you haven't done
- Focus on weak areas identified from previous practice

**Thursday:**
- Mystery Lab Challenge: Pick a random expert lab, solve without hints

**Friday:**
- Full BSCP practice exam under timed conditions

**Weekend:**
- Review mistakes from practice exam
- Document advanced techniques you're shaky on

**Concrete Tasks:**
- ✅ Complete all remaining PortSwigger labs (target: 200+ total)
- ✅ Pass 3 full practice exams scoring 80%+
- ✅ Create your personal "BSCP cheat sheet" with tricky payloads/techniques

### Weeks 3-4: Advanced Web Challenges

**Monday-Wednesday:**
- HackTheBox Web challenges (Medium/Hard difficulty)

**Thursday:**
- Build something vulnerable - create your own intentionally broken web app with 3-4 vulnerability types

**Friday:**
- Break your own app, then fix it

**Weekend:**
- Write one detailed blog post about an interesting technique

**Concrete Milestone:**
- ✅ **Take BSCP exam by end of Week 4**

---

## Phase 2: Months 3-5 - Real-World Web + Bug Bounty

### Goal
Apply skills in real environments, earn some bugs, build portfolio

### Month 3: Bug Bounty Foundations

#### Week 1-2: Setup & Methodology

**Tasks:**
- Pick 3 bug bounty programs (VDP or low-competition programs)
- Set up your testing workflow:
  - Recon toolkit (subfinder, httpx, nuclei, etc.)
  - Automation for repetitive tasks
  - Note-taking system for tracking targets
- **Daily:** 1-2 hours reconnaissance and testing on one target

**Goal:** Submit your first 3 bug reports (even if low severity)

#### Week 3-4: Specialization Sprints

**Structure:**
- Pick one vulnerability class per week to go deep
  - Week 3: XSS chains and filter bypasses in the wild
  - Week 4: IDOR and authorization issues at scale

**Activities:**
- **Build:** Create a custom tool to automate finding your chosen vuln type
- **Break:** Use your tool on bug bounty targets

**Goal:** Find 2-3 real vulnerabilities

### Month 4: Advanced Web Exploitation

#### Certification Decision Point

Choose ONE based on budget/employer coverage:

**Option A: eWPTXv2** (~$400-600, ask employer)
- More practical, less code-review focused
- 14-day exam (flexible for your schedule)
- Good for penetration testing career path

**Option B: OSWE** (~$1,600-2,000, definitely ask employer)
- Deep whitebox testing & code review
- More challenging and prestigious
- Better if you want to pivot to secure development or deep technical work

**Option C: Skip cert, double down on bug bounty + projects**
- Free, builds public portfolio
- More flexible learning
- Can always get cert later

**Recommendation:** Start with **eWPTXv2** (easier employer buy-in) OR skip cert and focus on building + breaking.

#### If doing eWPTXv2:
- Weeks 1-2: INE course videos (4-5 hours/week)
- Week 3: Lab exercises from course
- Week 4: Practice exam scenarios

#### If skipping cert:

**Build Projects:**
- Week 1: Vulnerable e-commerce app with payment logic flaws
- Week 2: API gateway with various auth bypasses
- Week 3: File upload system with multiple bypass opportunities
- Week 4: Social media clone with privacy/IDOR issues

**For each project:**
- Break it and write an attack report
- Share via blog posts or GitHub repos

### Month 5: Advanced Topics + Mobile Prep

#### Weeks 1-2: Specialized Web

**Pick TWO topics that interest you:**
- GraphQL security
- WebSocket vulnerabilities
- JWT/OAuth deep dive
- Server-Side Template Injection (SSTI)
- Deserialization attacks
- Race conditions

**Mix:** 50% learning/reading, 50% finding these in CTFs or bug bounty

#### Weeks 3-4: Mobile Environment Setup

**Set up Android testing lab:**
- Genymotion or Android emulator
- Frida, Objection
- ADB, APKTool, jadx-gui
- Burp/ZAP for mobile
- MobSF (Mobile Security Framework)

**Complete 2-3 basic mobile CTF apps:**
- DIVA Android
- InsecureBankv2
- Damn Vulnerable Bank

**Goal:** Get comfortable with mobile testing workflow

---

## Phase 3: Months 6-8 - Mobile Security Specialization

### Goal
Become proficient in Android and iOS pentesting

### Month 6: Android Deep Dive

#### Week 1: Static Analysis Mastery

**Learn:** APK structure, AndroidManifest, decompilation

**Build:** Simple Android app with hardcoded secrets

**Break:** Use every static analysis tool on your own app

**Practice:** Analyze 3 real apps from Play Store (ethically, for learning)

**Milestone:** ✅ Document 10 different types of static analysis findings

#### Week 2: Dynamic Analysis & Runtime Manipulation

**Learn:** Frida fundamentals, hooking Java methods

**Build:** App with SSL pinning and root detection

**Break:** Bypass your own SSL pinning 5 different ways

**Practice:** Complete all Frida CodeShare scripts tutorials

**Milestone:** ✅ Create your own Frida script collection

#### Week 3: Android Data & Storage Security

**Learn:** SharedPreferences, SQLite, internal storage, content providers

**Build:** App that stores sensitive data in multiple ways (some insecure)

**Break:** Extract all the data using various techniques

**Practice:** Test 5 real mobile apps for storage vulnerabilities

**Milestone:** ✅ Write a "Mobile Data Storage Testing Checklist"

#### Week 4: Android Auth & Crypto

**Learn:** WebView vulns, deep links, intent issues, crypto mistakes

**Mix:** 3 days focused learning, 2 days applying to CTF challenges

**Practice:** AndroGoat full walkthrough

**Milestone:** ✅ Complete one medium-difficulty mobile challenge on HTB

### Month 7: iOS Testing

#### Week 1: iOS Foundations

**Set up iOS testing environment:**
- Xcode, iOS Simulator
- Corellium (cloud-based) OR jailbroken device (if you have one)
- Objection, Frida for iOS
- iOS-specific tools (iMazing, iFunBox)

**Learn:** IPA structure, plist files, iOS sandbox

**Practice:** iGoat basics

**Milestone:** ✅ Successfully set up and test one iOS app

#### Week 2: iOS-Specific Testing

**Learn:** iOS keychain, data protection classes, IPC vulnerabilities

**Build:** Simple iOS app OR use provided vulnerable apps

**Break:** Focus on iOS-specific attack vectors

**Practice:** Complete DVIA-v2 (Damn Vulnerable iOS App)

**Milestone:** ✅ Document 10 iOS-specific findings

#### Week 3-4: Cross-Platform & Mobile APIs

**Learn:**
- React Native / Flutter security
- Mobile API testing (OAuth flows, JWT, API abuse)
- Certificate pinning on both platforms

**Build:** Mobile app that consumes a REST API with auth

**Break:** Test for API-level vulnerabilities

**Practice:** Mixed iOS/Android challenges

**Milestone:** ✅ Test 3 real mobile apps end-to-end (static + dynamic + API)

### Month 8: Mobile Certification & Portfolio

#### Certification Target

Choose based on budget:

**Option A: TCM Security MAPT** (~$400-500)
- Practical, hands-on exam
- Both Android and iOS
- Good for penetration testing focus
- Lifetime access to materials

**Option B: MSTG Certification** (Free - $299)
- Based on OWASP Mobile Security Testing Guide
- Community-recognized
- Self-paced

**Option C: Skip cert, build portfolio**
- Create 3-5 detailed mobile app pentest reports
- Blog series on mobile security
- Contribute to MASTG or mobile tools

**Schedule:**
- Week 1-2: Certification prep OR portfolio project work
- Week 3: Take exam OR finish portfolio pieces
- Week 4: Recovery + consolidation week

**Concrete Milestone:**
- ✅ Pass mobile cert OR publish 3 mobile security write-ups
- ✅ Have tested 15+ mobile apps total
- ✅ Created personal mobile testing methodology doc

---

## Phase 4: Months 9-12 - AI Red Teaming Transition

### Goal
Build foundation for AI security specialization while maintaining web/mobile skills

### Month 9: AI/ML Security Fundamentals

#### Week 1: Understanding LLMs

**Learn:** How LLMs work (transformers, tokens, training)

**Resources:**
- "Intro to Large Language Models" by Andrej Karpathy (1hr video)
- Simon Willison's blog on LLM security
- OWASP Top 10 for LLM Applications

**Build:** Simple chatbot using OpenAI API or Anthropic API

**Milestone:** ✅ Understand basic LLM architecture and APIs

#### Week 2: Prompt Injection Fundamentals

**Learn:** Direct vs indirect prompt injection, jailbreaking techniques

**Practice challenges:**
- Gandalf AI (all levels)
- HackAPrompt competition challenges
- Prompt injection CTFs

**Build:** Intentionally vulnerable AI assistant

**Milestone:** ✅ Successfully complete 10 prompt injection challenges

#### Week 3: LLM Application Security

**Learn:**
- Plugin/tool calling security
- RAG (Retrieval Augmented Generation) vulnerabilities
- Training data extraction
- Model denial of service

**Break:** Analyze popular LLM apps (ChatGPT plugins, AI agents)

**Build:** AI app with RAG that has security issues

**Milestone:** ✅ Document 5 different LLM vulnerability classes

#### Week 4: AI Security Tooling

**Explore tools:**
- Garak (LLM vulnerability scanner)
- PromptFuzz
- PyRIT (Python Risk Identification Toolkit)

**Practice:** Use tools on your own vulnerable AI apps

**Milestone:** ✅ Create your own AI security testing checklist

### Month 10: Advanced AI Security

#### Week 1: Adversarial Machine Learning

**Learn:** Evasion attacks, poisoning attacks, model inversion

**Resources:**
- IBM's Adversarial Robustness Toolbox
- Papers from arxiv.org on adversarial ML
- CleverHans tutorials

**Practice:** Create adversarial examples for image classifiers

**Milestone:** ✅ Successfully fool 3 different ML models

#### Week 2: AI Supply Chain & Model Security

**Learn:**
- Model serialization vulnerabilities (pickle exploits)
- Compromised ML dependencies
- Model backdoors
- Hugging Face security considerations

**Build:** Demonstrate a supply chain attack in ML pipeline

**Milestone:** ✅ Document AI supply chain threat model

#### Week 3: Real-World AI Pentesting

**Find targets:**
- Bug bounty programs that include AI features
- Open source AI projects
- HackTheBox AI challenges (if available)

**Practice:** Apply prompt injection, jailbreaking, API abuse to real targets

**Mix:** 50% testing, 50% documenting findings

**Milestone:** ✅ Submit 2-3 AI-related bug reports or findings

#### Week 4: AI Red Team Project

**Build:** Comprehensive vulnerable AI application with:
- LLM chatbot with prompt injection vulns
- RAG system with data leakage
- AI tool calling with SSRF potential
- Weak auth on AI APIs

**Break:** Write full pentest report of your own app

**Share:** Blog post or GitHub repo

**Milestone:** ✅ Complete end-to-end AI pentest project

### Month 11: Specialization Deepening

#### Pick YOUR path based on what interests you most:

**Path A: Deep AI/ML Security**
- Study research papers (2-3 per week)
- Contribute to AI security tools
- Join AI security Discord communities
- Practice on academic ML security challenges

**Path B: AI-Augmented Web/Mobile Testing**
- Build AI tools to help with pentesting
- LLM-assisted vulnerability detection
- Automated report generation with AI
- Creating better recon tools with LLMs

**Path C: Balanced - Mix of All**
- 2 days/week: AI security practice
- 2 days/week: Web/mobile bug bounty
- 1 day/week: Building tools or writing

#### Week 1-4 Activities (adapt to chosen path):
- Continue testing real applications
- Write 2-4 blog posts on your learnings
- Network with AI security folks on Twitter/LinkedIn
- Attend virtual conferences or webinars

**Milestone:** ✅ Build recognizable expertise in one niche area

### Month 12: Portfolio, Networking & Job Positioning

#### Goal
Position yourself for AI red team roles or advanced pentesting with AI skills

#### Week 1-2: Portfolio Development

**Create:**
- Personal website or GitHub profile showcasing work
- 5-10 detailed write-ups (mix of web, mobile, AI)
- 2-3 tools you've built
- Case studies of interesting findings

**Polish:** Make everything professional and presentable

**Milestone:** ✅ Have a portfolio you're proud to share

#### Week 3: Networking & Community

**Engage:**
- Share your work on Twitter/LinkedIn
- Comment on others' AI security posts
- Join relevant Discords (PortSwigger, AI Security, etc.)
- Attend virtual CTFs or conferences

**Connect:** Reach out to 5-10 people doing AI red teaming

**Milestone:** ✅ Build relationships in the community

#### Week 4: Career Positioning

**Update:** LinkedIn profile with new skills and certs

**Apply:** Start looking at AI red team roles or advanced pentest positions

**Prepare:** Practice talking about your journey and projects

**Consider:** Speaking at local meetups or writing for publications

**Milestone:** ✅ Position yourself as "junior-mid level pentester with AI security skills"

---

## Budget Summary

### Certification Costs:
- **BSCP:** ~$99
- **eWPTXv2:** ~$400-600 (optional, ask employer to cover)
- **Mobile cert (MAPT):** ~$300-500 (or free with MSTG)

**Total if all certs:** $800-1,200 (less if employer covers some)

### Free Alternatives:
- Skip eWPTXv2, do more bug bounty practice
- Use free mobile resources (MASTG is free, YouTube tutorials)
- Build portfolio through write-ups instead of paid certs

---

## ADHD-Optimized Daily/Weekly Structure

### Daily Schedule Template

#### Morning Power Block (2 hours, best focus time):
- 25 min: Main learning/lab work
- 5 min: Break (move around)
- 25 min: More main work
- 5 min: Break
- 25 min: Continue or switch to hands-on
- 5 min: Quick document what you learned

#### Afternoon Flex Block (1-1.5 hours):
- Lighter tasks: reading, write-ups, tool exploration
- OR hands-on breaking/building if you're energized
- OR community engagement if you're socially charged

#### Friday = Different:
- No new learning
- Review week, do a CTF, or work on fun project
- Update your progress tracker

### Weekly Variety Schedule

**Monday:** Learn new concept (videos, reading)  
**Tuesday:** Labs/practice on Monday's concept  
**Wednesday:** Build something with the concept  
**Thursday:** Break something or do CTF challenge  
**Friday:** Write-up, review, or fun project  
**Weekend:** Optional - rest OR pursue whatever interests you most

---

## Motivation Systems

### 1. Visual Progress Tracker
Create a simple spreadsheet or Notion board with:
- [ ] Daily checkboxes for tasks
- 🏆 Milestone markers (certs, write-ups)
- 📊 Weekly stats (hours logged, labs completed)
- 🎯 Monthly goals clearly visible

### 2. Micro-Rewards
- Complete 5 labs → Watch favorite show episode
- Finish week's tasks → Gaming session guilt-free
- Pass a cert → Buy yourself something nice
- Publish write-up → Share on social, celebrate

### 3. Accountability
- Find a study buddy (PortSwigger Discord, r/netsec)
- Post weekly updates somewhere public
- Join or create a small accountability group
- Share goals with friend/colleague

### 4. Task Variety
When stuck or bored:
- Switch between learning, building, breaking, writing
- Change environment (coffee shop, library)
- Do physical activity for 10 min
- Switch to a completely different topic for 30 min

### 5. The "Fuck It, Ship It" Rule
- Perfect is the enemy of done
- Write-ups don't need to be perfect
- Submit bug reports even if unsure
- Share work even if it feels incomplete
- Progress > Perfection

---

## Emergency Protocols

### When Focus is Impossible:
1. ✅ Do the easiest task on your list (micro-win)
2. ✅ Watch a 10-min video instead of reading
3. ✅ Do a simple CTF challenge (dopamine hit)
4. ✅ Or just rest - don't force it

### When Motivation is Gone:
1. ✅ Review your visual progress (see how far you've come)
2. ✅ Read one inspiring blog post from someone you admire
3. ✅ Change the plan - skip to something more interesting
4. ✅ Take a full day off guilt-free

### When You're Behind Schedule:
1. ✅ DON'T panic - plans are flexible
2. ✅ Identify what's actually important vs nice-to-have
3. ✅ Adjust timeline - it's okay to take 9 months instead of 6
4. ✅ Focus on one thing at a time

---

## Monthly Check-In Questions

Ask yourself on the 1st of each month:

1. ✅ Did I complete 60%+ of planned activities? (not 100%, be realistic)
2. ✅ Am I still enjoying this, or just grinding?
3. ✅ What worked well this month for my focus/motivation?
4. ✅ What should I change for next month?
5. ✅ Do I have at least one cool thing to show for this month?

**If 3+ answers are negative → adjust the plan immediately.**

---

## Key Principles for Success

1. **Flexibility > Rigidity:** Plans are guidelines, not prison sentences
2. **Building > Consuming:** Make things, don't just watch/read
3. **Shipping > Perfecting:** Done and public beats perfect and hidden
4. **Variety > Monotony:** Mix different activities daily/weekly
5. **Progress > Speed:** Consistent slow progress beats sporadic sprints

---

## Resources Hub

### Web Security:
- PortSwigger Academy
- HackTheBox Web Challenges
- PentesterLab
- Bug bounty platforms (HackerOne, Bugcrowd, Intigriti)

### Mobile Security:
- OWASP MASTG (Mobile Application Security Testing Guide)
- Frida CodeShare
- Mobile CTF apps: DIVA, InsecureBank, Damn Vulnerable Bank, AndroGoat, iGoat
- Android Security Awesome list (GitHub)

### AI Security:
- OWASP Top 10 for LLMs
- Simon Willison's blog
- Lakera AI security resources
- Anthropic/OpenAI safety docs
- AI Village community
- Garak, PyRIT, PromptFuzz tools

### Community & Networking:
- PortSwigger Discord
- AI Security Discord communities
- r/netsec, r/bugbounty
- Twitter/LinkedIn AI security folks
- Local security meetups

---

## Final Notes

Remember: This plan is a **guideline**, not a strict rulebook. Adjust as needed based on:
- Your energy levels and focus capacity
- What you find interesting vs. boring
- Real-world opportunities that arise
- Your pace of learning

The goal is **sustained progress**, not perfection. Even if you only complete 60-70% of this plan, you'll still have:
- Multiple certifications
- Real-world testing experience
- A solid portfolio
- Skills spanning web, mobile, and AI security
- Strong positioning for advanced roles

Good luck! 🚀