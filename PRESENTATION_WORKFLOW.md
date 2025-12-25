# Presentation Workflow: From Analysis to Video

## Overview

This document outlines the complete presentation workflow used for the Customer Shopping Behaviour project, from data analysis through to video creation for stakeholder communication.

**Workflow:** Python → SQL Server → Power BI → Gamma AI Slides → Google Slides → Video Presentation

---

## 1. Analysis & Dashboard Phase

### 1.1 Python Data Preparation
- Load and clean raw CSV data using pandas
- Handle missing values and engineer features
- Output: Clean dataset ready for SQL Server

### 1.2 SQL Server Analysis
- Build 10 business-focused analytical queries
- Use CTEs, window functions, and aggregations
- Generate insights on revenue, discounts, subscriptions, products

### 1.3 Power BI Dashboard Creation
- Build 3-page interactive dashboard (Executive Overview, Customer Behaviour, Marketing & Retention)
- Save as .pbix file and export PDF

---

## 2. Gamma AI - Slide Deck Creation

### 2.1 What is Gamma?
Gamma is an AI-powered presentation tool that generates professional slide decks automatically from text content.

**Website:** https://gamma.app

### 2.2 Workflow Steps

1. **Prepare Content:** Write structured outline with findings, insights, recommendations
2. **Create in Gamma:** Paste content into Gamma, let AI generate slides automatically
3. **Customize:** Edit text, add Power BI screenshot visuals, adjust design theme
4. **Export to Google Slides:** Click Export → Google Slides (maintains formatting)

---

## 3. Google Slides - Refinement & Video Creation

### 3.1 Why Google Slides?
- Cloud-based collaboration (share with team for feedback)
- Built-in speaker notes for talking points
- Native video generation capability
- Easy sharing via links

### 3.2 Refinement Process

1. **Open Gamma Export:** Google Slides link generated automatically
2. **Add Speaker Notes:** Click Notes at bottom of each slide, write talking points
3. **Enhance Visuals:** Replace low-res images with high-quality Power BI screenshots
4. **Finalize Design:** Consistent branding, slide numbers, footer with date/project
5. **Peer Review:** Share link with team, collect feedback via comments, revise

### 3.3 Video Generation

**Step 1:** Ensure Google Slides are finalized with speaker notes

**Step 2:** Access video creation: File → Download → MP4 Video

**Step 3:** Configure Settings:
- Slide timing: 3-5 seconds per slide
- Enable transitions for visual flow
- Optional voice-over (can be added)

**Step 4:** Generate Video → Download MP4 file

**Step 5:** Optional - Add Voice Over Using:
- Descript (AI video editing)
- CapCut (free, user-friendly)
- Audacity (audio recording)
- Adobe Premiere Pro (professional)

**Step 6:** Upload & Share:
- YouTube (public or unlisted)
- Google Drive (shareable link)
- LinkedIn (portfolio showcase)
- Email (attachment or link)

---

## 4. Complete Workflow Diagram

```
Python (Data Prep)
    ↓
SQL Server (Analysis)
    ↓
Power BI (Dashboard)
    ↓
Gamma AI (Slide Generation)
    ↓
Google Slides (Refinement + Speaker Notes)
    ↓
Google Slides (Video Conversion)
    ↓
Video (MP4)
    ↓
Upload to Cloud (YouTube, LinkedIn, Drive)
    ↓
Share with Stakeholders
```

---

## 5. Tools & Resources

### Core Tools
- **Gamma.app:** AI slide generation (Free + Premium)
- **Google Slides:** Presentation editing & video creation (Free)
- **Power BI:** Dashboard & visualization (Microsoft 365)

### Optional Video Enhancement Tools
- **Descript:** https://www.descript.com (AI video editing)
- **CapCut:** https://www.capcut.com (Free video editor)
- **Audacity:** https://www.audacityteam.org (Free audio editor)
- **Loom:** https://www.loom.com (Screen recording)

---

## 6. Best Practices

### For Slide Decks
- Keep slide count 15-20 max (shorter = more impactful)
- One main idea per slide
- Use high-quality visuals (Power BI charts, screenshots)
- Include data labels on all charts
- Consistent branding (colors, fonts, logo)
- Add speaker notes to every slide

### For Videos
- Keep video under 10 minutes (ideal: 5-7 minutes)
- Clear audio quality (no background noise)
- Steady pacing (not too fast)
- Include subtitles/captions (accessibility)
- Start with hook ("In this video, you'll learn...")
- End with clear call-to-action

### For Sharing
- Provide context in email (summary of content)
- Include video duration
- Add transcript in description
- Use clear thumbnail/preview image
- Include action items or next steps

---

## 7. File Organization for Project

```
customer-shopping-behaviour/
├── notebooks/
│   └── Customer_Behaviour.ipynb
├── sql/
│   └── customer_behaviour_analysis.sql
├── reports/
│   ├── Customer-Behaviour-Dashboard.pdf
│   ├── Customer-Behaviour-Slides.pptx (Gamma export)
│   └── Customer-Behaviour-Slides.gslides (Google Slides link)
├── dashboards/
│   └── screenshots/ (PNG exports)
├── videos/
│   └── Customer-Behaviour-Presentation.mp4
└── README.md
```

---

## 8. Next Steps Checklist

- [ ] Finalize Power BI dashboard
- [ ] Create Gamma slides from presentation outline
- [ ] Export Gamma slides to Google Slides
- [ ] Add speaker notes to each Google Slide
- [ ] Refine visuals with Power BI screenshots
- [ ] Generate video from Google Slides (MP4)
- [ ] Optional: Add voice-over to video
- [ ] Upload video to YouTube (unlisted) or Google Drive
- [ ] Add video link to GitHub README
- [ ] Share on LinkedIn with project summary

---

**Last Updated:** December 2025

**Author:** Aparna Birle
