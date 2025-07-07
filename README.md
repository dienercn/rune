# Welcome to RUNE
## The app for runners connecting with their community
### Discover. Run. Connect.

The journey ahead is more than just a read — it’s a glimpse into a movement. Within the following pages, you will discover the beating heart of our vision, forged from the spirit of countless runners, shaped by experience, and driven by the need for something greater. You’ll learn about the challenge we uncovered — a quiet, persistent gap in the running world — and how this realization fueled a mission to build something bold, purposeful, and deeply human.
For too long, runners have navigated a fragmented landscape. Finding local events often means scouring dozens of websites, following scattered social media posts, or relying on word of mouth. Connecting with like-minded individuals — runners who match your pace, your goals, your passion — can feel like chance rather than design. And the sense of community we all crave, the shared spirit that makes every kilometer more meaningful, is often lost in the noise.
We believe it doesn’t have to be this way.
Our mission is clear: to empower runners with a tool that brings simplicity, connection, and energy back into their journey. A tool that does more than just list events — one that understands who you are as a runner, and helps you find experiences that match not just your schedule, but your soul. Whether you're chasing a new PR, exploring scenic trails, or joining your first 5K, you deserve a platform that supports you every step of the way.
But this isn’t just about logistics. It’s about people. It's about forging bonds between runners who might have otherwise passed each other by. It’s about building a community that celebrates diversity in pace, background, and ambition — yet runs together with a shared heartbeat. In this space, we envision runners encouraging one another, sharing tips, planning meetups, and forming friendships that last well beyond the finish line.
Our proposed solution brings all of this to life. It combines smart technology with the soul of the running community — a platform that recommends events tailored to your interests, connects you with compatible running partners, and serves as a hub for everything that fuels your passion. Imagine an intuitive, beautiful space where you can discover, connect, and grow — not just as a runner, but as a part of something greater.
We are building more than a product. We are building a rallying cry for runners who believe in the power of movement and the magic of shared purpose. So lace up, lean in, and let these next pages show you the path we’re charting — one that leads not just to more races, but to more meaning, more belonging, and more joy in every run.
Welcome to the future of running. Welcome to a revolution on foot.

## Vision

RUNE empowers runners to effortlessly discover meaningful events, forge authentic connections, and embrace the joy of movement through every stride. We envision a world where running is more than a sport — it’s a shared journey that unites, inspires, and transforms lives.

## Target groups
* Hobby (trail-) runner
* Local running communities and groups
* Sponsors
  
## Problem statement
### Actor: Runner
As a passionate runner, I often find myself searching for more than just races — I’m looking for a community that aligns with my values, goals, and lifestyle. But today, there is no central platform where I can easily discover and connect with like-minded runners or communities that truly fit my desires. Instead, I’m forced to rely on fragmented channels like Instagram, Facebook, or word of mouth, just to learn about local groups, events, or shared running experiences. Each platform shows me only glimpses — scattered posts, stories, or reels — but rarely the full picture: What does this community stand for? Are they inclusive? Do they run for performance, for fun, or for nature? Do they welcome someone like me?
Even after finding a group that feels right, the process of actually connecting is messy and inconsistent. I’m often required to join a WhatsApp group, follow yet another account, or message someone directly — and that often feels awkward, insecure, and unstructured. I have concerns about data privacy and personal boundaries when using such open tools. I’m not just looking for the next run; I’m looking for a safe, welcoming space to belong, share, and grow as a runner. But right now, that space simply doesn’t exist in one place.

### Actor: Provider
As a community provider, my goal is to create meaningful experiences for runners — but managing a running community today is a constant challenge. One of the biggest issues I face is the lack of transparency and clarity around participation. I often don’t know how many people will show up to a run, who is actually part of my community, or how engaged they are. This makes it extremely difficult to plan ahead, track growth, or demonstrate the value of the community to potential sponsors and partners. Without reliable data or insights, it’s nearly impossible to prove the strength, consistency, or reach of what we’re building.
At the same time, promoting our events and activities is time-consuming and inefficient. I’m forced to juggle multiple platforms like Instagram, Facebook, and Strava just to keep our presence alive — yet there’s no unified way to reach both current and potential members in a consistent, professional way. Communication and organization often happen through WhatsApp or other informal tools, which quickly become chaotic, unreliable, and unscalable. In the end, what should be an inspiring, vibrant space for connection and growth turns into a time-consuming task with little support. What I need is a platform that makes community management easier, smarter, and more impactful.

### Actor: Sponsor
As a sponsor looking to engage with the vibrant and growing running community, I recognize the immense potential — both in terms of brand visibility and customer loyalty. Runners are passionate, purpose-driven, and often highly engaged with the products and services that support their lifestyle. However, despite the size and enthusiasm of this community, reaching them in a meaningful and efficient way remains a major challenge. The current landscape is fragmented: communities are scattered across various platforms, events are promoted inconsistently, and there’s no centralized space where I can offer tailored content, services, or promotions directly to the right audience.
Without direct access to structured communities or reliable engagement data, I’m left with limited options: I either collaborate with influencers, which often comes at a high cost and unpredictable outcomes, or I launch broad, untargeted social media campaigns that lack precision and measurable impact. Both approaches are resource-intensive and offer no guarantee of return. What I’m missing is a streamlined, data-driven platform that connects me directly with active, interested runners — where I can deliver personalized offerings, support community initiatives, and build lasting brand relationships. In a competitive market, I need more than visibility — I need authentic, effective access to the running world.

## Core feature set
### User Management and Access: Secure, Inclusive, and Frictionless
#### Multi-Channel Login Options
A foundational pillar of any modern platform is a robust identity and access management system. RUNE must make it as easy and safe as possible for users to join, return, and engage daily.
That requires a huge variety of login options for our end customers. As they are mentioned below in order of their priority

1. E-Mail-Address and Password
2. Strava Social Login
3. Google Account
4. Apple ID
5. Phone number (via SMS OTP validation)

This ensures broad accessibility, including younger users and those who prioritize convenience or privacy.

On top of that not only log-in mechanism must be involved, but also in case of case no. 1 (e-mail-address and password) own implementations of password reset & password forget routines.

#### Authentication & Authorization Architecture
RUNE needs to establish a strong backend framework for authentication (verifying who a user is) and authorization (what they are allowed to do). This is essential for ensuring privacy, data integrity, and user safety — especially for features like messaging, event participation, and analytics access.

#### Role-Based Access Control (RBAC)
Every user account must be tied to a specific role or combination of roles:

- Runner >> The core user looking for events, benefits, and connections.
- Provider >> A group leader or event organizer who manages events, communities, and participant engagement
- Sponsor >> A business entity offering tailored products, benefits, or campaigns to the community.

Entitlements should be tightly scoped to these roles, preventing unauthorized access and enabling granular feature control.

---

## Branding concept
### 🏷️ **Brand name**

**RUNE** (ɾʌn-​ĩ)
A very short and concise name with double meaning

* **RUN** = eng., to run
* **E** = eng., Event
* **RUNE** = Old symbol for strength, leading and knowledge Symbol für Kraft, Richtung, Wissen

---

### 🧭 **Brand identity**

#### 💡 **Brand Essence**
**„RUNE stands for movement with a meaningful purpose“**
Whether on the trail or during a city run – with RUNE, users discover new paths, events and communities.

### 🌈 **Brand values**

| Value              | App meaning                                       |
| ------------------ | ------------------------------------------------- |
| **Movement**       | Activity, progress, personal growth               |
| **Connectedness**  | Community, shared experiences, local events       |
| **Discovery**      | New trails, locations, running groups & events    |
| **Intuition**      | User-centricity, simple UX, smart suggestions     |
| **Individuality**  | Every run is different – ​​RUNE adapts              |

---

## Ideation
### 🎨 **Color palette**

A mix of nature, technology and energy:

| Farbe          | Hex       | Bedeutung                    |
| -------------- | --------- | ---------------------------- |
| **Evergreen**  | `#004B41` | Nature, peace, forest, trust |
| **Rune Gold**  | `#D4AF37` | Symbolism, goal, meaning     |
| **Aqua Mint**  | `#2A9D8F` | Freshness, clarity, movement |
| **Black**      | `#000000` | Focus, elegance, readability |
| **White**      | `#FFFFFF` | Openness, space, clarity     |
| **Accent Red** | `#F15A24` | Energy, motivation, “Go!”    |


### 🔤 **Typography**

**Main font (Logo + Headlines):**

* **Cinzel** or **Cormorant Garamond**

**Secondary font (UI, Body-Text):**

* **Inter** or **Manrope** 

### 📱 **App-Concept (UX/UI)**

* **Speach:** Clear, friendly and motivting
* **Navigation:** Intuitive with focus on "Exploration", "Attending", "Matching/Connecting" and "Sharing"
* **Emotion:** Feeling or progress, belonging and curiosity


## 🔧 **Feature-Branding (Examples / Ideas UI)**

| Funktion            | In-App-Bezeichnung     |
| ------------------- | ---------------------- |
| Event-Finder        | **Rune Radar**         |
| Community Check-In  | **RUNE Connect**       |
| Personal profile    | **My RUNE**            |
| Favoriten           | **Marks**              |
| Tickets/Check-Ins   | **Runes**              |
