# AI Video Analytics: Capabilities, Examples & Demonstrations

A presentation-ready technical showcase and research resource covering **28 Core AI Video Analytics Capabilities** for modern surveillance, physical security, and intelligent Video Management Systems (VMS).

🌐 **Live Web Presentation**: [https://roojool.github.io/ai-video-analytics-showcase/](https://roojool.github.io/ai-video-analytics-showcase/)

---

## Deliverables Summary

### Version 2.0 (Enhanced & Recommended)
- **`ai_video_analytics_presentation_v2.html`** / **`index.html`** (Live Web Version):
  - **Enhanced Dual-Mode Video Showcase**: Solves the browser `file:///` local iframe security block by providing an interactive video card with high-resolution thumbnails, glowing YouTube play button, one-click in-page embed player, and direct `Watch on YouTube (Direct Link) →` action button.
  - **Live Web Deployment**: Hosted via GitHub Pages with SSL (`https://`), ensuring zero cross-origin iframe blocks.
  - **Dashboard Grid View & Presentation Deck**: Includes category tabs with capability count badges, real-time search, keyboard shortcuts (`←`, `→`, `Esc`), and quick "Watch Video" buttons on each card.
- **`ai_video_analytics_presentation_v2.pptx`**:
  - **Balanced 2-Column Geometry**: Redesigned from the ground up so that every slide has uniform box heights, identical margins, and matching baselines.
  - **Symmetrical 2-Tier Category Overview (Slide 2)**: 4 equal-width cards on the top row, 3 equal-width cards on the bottom row, eliminating text squishing.
  - **Two-Part Capability Matrix (Slides 31 & 32)**: Cleanly formatted tables across two slides with generous row height and 9.5pt typography.
  - **Clickable Hyperlinks**: Real YouTube thumbnails and cyan action buttons with live hyperlinks to verified demonstrations.

### Version 1.0 (Preserved Original)
- **`ai_video_analytics_presentation.html`**: Initial single-file web presentation.
- **`ai_video_analytics_presentation.pptx`**: Initial 32-slide PowerPoint deck.

### Supporting Assets
- **`master_analytics_data.json`**: Structured dataset containing all 28 capabilities, definitions, distinctions, use cases, compliance alerts, and verified video URLs.
- **`thumbs/`**: High-resolution video preview thumbnails for all 28 capabilities.

---

## The 28 AI Video Analytics Capabilities (Exact Order)

### 1. Detection & Recognition
| # | Capability | One-Line Non-Technical Explanation | Primary Video Source |
|---|---|---|---|
| **01** | **Face Detection** | Detects and pinpoints the presence and location of human faces in a camera's field of view. | Axis Communications |
| **02** | **Face Recognition, where legally authorized** | Matches detected human faces against an authorized database of known individuals for access control or security alerts. | Hikvision UK & Ireland |
| **03** | **Person Detection** | Identifies and isolates human figures in the video frame, distinguishing people from background objects. | Axis Technical Support |
| **04** | **Vehicle Detection** | Identifies motorized vehicles such as cars, trucks, motorcycles, and buses within the camera's view. | Axis Communications |
| **05** | **Human/Vehicle Classification** | Differentiates whether a detected moving object is a person or a vehicle, filtering out false alarms caused by animals, weather, and foliage. | BoardTac Solutions (Dahua AI) |

### 2. Movement & Zone Analytics
| # | Capability | One-Line Non-Technical Explanation | Primary Video Source |
|---|---|---|---|
| **06** | **Line Crossing** | Generates an instant alert when a person or vehicle crosses a predefined virtual tripwire line in a specified direction. | Axis Communications USA |
| **07** | **Intrusion Detection** | Triggers an alarm when an unauthorized subject enters and remains inside a designated virtual zone for a set threshold. | Axis Technical Support |
| **08** | **Restricted Area Detection** | Immediately alerts the instant any person or vehicle enters a strictly forbidden, high-security zone. | Daten & Wissen AI |
| **09** | **Loitering Detection** | Detects when an individual or vehicle lingers or remains stationary in a defined area longer than the permitted time limit. | Axis Technical Support |
| **14** | **Direction Detection** | Determines and monitors the travel vector of moving pedestrians or vehicles along designated paths. | Hanwha Vision Europe |
| **15** | **Wrong-Way Movement Detection** | Generates an urgent warning when a vehicle or person travels in reverse or against the mandatory flow of traffic. | Keenfinity Group (Bosch) |
| **24** | **Perimeter Protection** | Establishes automated multi-layered virtual boundary security around property borders while filtering out environmental noise. | Axis Communications |

### 3. Crowd & Counting Analytics
| # | Capability | One-Line Non-Technical Explanation | Primary Video Source |
|---|---|---|---|
| **10** | **Crowd Detection** | Identifies when a group of people gathers in a specific area exceeding normal group size or threshold. | Hikvision Europe |
| **11** | **Crowd Density Analysis** | Measures and visualizes the percentage and density of spatial occupancy across an area to prevent dangerous overcrowding. | BriefCam Video Analytics |
| **12** | **People Counting** | Continuously counts the number of people entering, exiting, or passing through a defined entrance or passage. | Axis Communications |
| **13** | **Occupancy Counting** | Maintains a live, real-time count of total individuals currently inside a building or enclosed space to enforce capacity limits. | Axis Communications North Asia |

### 4. Object Analytics
| # | Capability | One-Line Non-Technical Explanation | Primary Video Source |
|---|---|---|---|
| **16** | **Abandoned Object Detection** | Flags unattended stationary items, such as bags or boxes, left behind in public areas beyond a set time limit. | Security Camera King |
| **17** | **Missing Object Detection** | Alerts security operators immediately when a designated stationary asset or valuable object disappears from its location. | Dahua Technology |
| **18** | **Object Removal Detection** | Detects the deliberate physical act of an individual lifting, taking, or removing a protected item from its resting place. | Keenfinity Group (Bosch) |
| **19** | **Scene Change Detection** | Detects sudden significant changes in the camera's visual background caused by physical rotation, repositioning, or environmental shifts. | Security Camera King |

### 5. Camera Health & Diagnostics
| # | Capability | One-Line Non-Technical Explanation | Primary Video Source |
|---|---|---|---|
| **20** | **Camera Tampering Detection** | Alarms when an attacker attempts to vandalize or incapacitate a camera via spray painting, laser blinding, sudden redirection, or physical impact. | DAVANTIS Perimeter Security |
| **21** | **Video Loss Detection** | Alerts security operators instantly when a camera signal drops, disconnects, or experiences complete transmission failure. | Dahua Technology India |
| **22** | **Defocus Detection** | Identifies when a camera's optical focus degrades or blurs, warning operators that image quality has been compromised. | Hanwha Vision America |
| **23** | **Camera Obstruction Detection** | Detects when a camera's lens is covered, blocked, or obscured by foreign objects, bags, tape, or overgrown foliage. | AI-Bot Eye Systems |

### 6. Safety Analytics
| # | Capability | One-Line Non-Technical Explanation | Primary Video Source |
|---|---|---|---|
| **25** | **Fall Detection, where applicable** | Recognizes sudden changes in human posture indicative of a person collapsing or falling down, enabling immediate emergency assistance. | Hanwha Vision Europe |
| **26** | **Fire/Smoke Detection, where supported** | Visually detects open flames and developing smoke plumes significantly faster than traditional spot detectors, especially in high-ceiling spaces. | Hikvision Corporate Channel |

### 7. Tracking & Behaviour
| # | Capability | One-Line Non-Technical Explanation | Primary Video Source |
|---|---|---|---|
| **27** | **Vehicle/person tracking** | Continuously follows and plots the real-time path of an individual or vehicle across camera fields of view or via motorized PTZ tracking. | Hikvision MEA |
| **28** | **Behaviour/event-based analytics where legally and technically appropriate** | Detects complex human actions and anomalous security incidents, such as fighting, running, distress gestures, or erratic movements. | Milesight Security |

---

## How to Access & Present

### 1. View from Anywhere with a Public Link
Open: **[https://roojool.github.io/ai-video-analytics-showcase/](https://roojool.github.io/ai-video-analytics-showcase/)**
- Works on any computer, laptop, iPad, or mobile phone without downloading files.
- Hosted with SSL (`https://`), avoiding local browser `file:///` restrictions on embedded video players.

### 2. Presenting Locally (HTML)
- Open `ai_video_analytics_presentation_v2.html` directly in any web browser.
- Click **"Presentation Mode"** for slide-by-slide view.
- Click **"Grid View"** for a dashboard of all 28 capabilities.
- If an embedded iframe is blocked by your browser's local file security policy, click **"Watch on YouTube (Direct Link)"** to immediately open the verified demo.

### 3. Presenting via PowerPoint (PPTX)
- Open `ai_video_analytics_presentation_v2.pptx` in Microsoft PowerPoint.
- Start presentation mode (`F5`).
- Click any video preview image or the **`▶ WATCH DEMONSTRATION VIDEO`** button to launch the verified video demonstration in your default browser.

---

## Legal & Compliance Notice

> **Presentation Disclaimer**: AI analytics capabilities, accuracy, and availability vary by camera hardware, software platform, scene lighting, target distance, mounting angles, and deployment configuration. Certain advanced analytics—particularly face recognition, biometric processing, and automated behaviour analysis—are strictly governed by international and local privacy laws (including GDPR, CCPA/CPRA, BIPA, and statutory human rights regulations) and require appropriate legal authorization, consent mechanisms, and rigorous data protection protocols. Video-based safety systems (such as fire/smoke or fall detection) act as early operational warnings and are designed to supplement rather than replace mandatory certified life-safety systems.
