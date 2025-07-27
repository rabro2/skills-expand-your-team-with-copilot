---
name: 🎯 Add New Activity or Club
about: Request a new extracurricular activity or club to be added to the system
title: '[NEW ACTIVITY] Add [Activity Name]'
labels: ['enhancement', 'new-activity', 'teacher-request']
assignees: []
---

## 📋 Activity Information

**Activity/Club Name:** 
<!-- Enter the name of the new activity or club -->

**Category:** 
<!-- Select one: Sports, Arts, Academic, Community, Technology -->

**Brief Description:**
<!-- Describe what this activity is about in 1-2 sentences that students will see -->

## 📅 Schedule Details

**Meeting Days:**
<!-- Select from: Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, Sunday -->

**Meeting Time:**
<!-- Enter start and end time (e.g., 3:15 PM - 4:45 PM) -->

**Location:**
<!-- Where will this activity take place? -->

## 👥 Participation Details

**Maximum Number of Students:**
<!-- How many students can participate? -->

**Grade Levels:**
<!-- Which grades can join? (e.g., 9-12, 10-12, etc.) -->

**Prerequisites or Requirements:**
<!-- Any special requirements? (e.g., "Must have completed Art I", "No experience needed", etc.) -->

## 👨‍🏫 Teacher Information

**Supervising Teacher:**
<!-- Your name -->

**Contact Email:**
<!-- Your school email address -->

## 🎯 Acceptance Criteria
<!-- The following will be completed when this is implemented -->

- [ ] New activity appears in the activities list on the website
- [ ] Students can view activity details (description, schedule, location)
- [ ] Students can register for the activity through the website
- [ ] Activity appears in the correct category filter
- [ ] Activity shows correct schedule information
- [ ] Maximum participant limit is enforced
- [ ] Teacher can see registered students

## 📝 Additional Context

**Why is this activity needed?**
<!-- Explain why this activity would benefit students -->

**Any special considerations?**
<!-- Equipment needs, special permissions, etc. -->

---
**For Copilot Implementation:**
- Database entry needed in `initial_activities` in `src/backend/database.py`
- Ensure proper schedule format with days array and time strings
- Add appropriate category classification
- Test registration functionality works correctly