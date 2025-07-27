---
name: ✏️ Modify Existing Activity
about: Request changes to an existing activity or club
title: '[MODIFY] Update [Activity Name]'
labels: ['enhancement', 'modify-activity', 'teacher-request']
assignees: []
---

## 🎯 Activity to Modify

**Current Activity Name:**
<!-- Enter the exact name as it appears on the website -->

## 📝 Requested Changes

**What needs to be changed?**
<!-- Check all that apply -->
- [ ] Activity name
- [ ] Description 
- [ ] Schedule (days/times)
- [ ] Location
- [ ] Maximum participants
- [ ] Category
- [ ] Supervising teacher
- [ ] Requirements/prerequisites
- [ ] Other (specify below)

## 📋 Change Details

### Name Change (if applicable)
**New Activity Name:** 
<!-- Leave blank if not changing -->

### Description Update (if applicable)
**New Description:**
<!-- Enter the updated description students will see -->

### Schedule Change (if applicable)
**New Meeting Days:**
<!-- Select from: Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, Sunday -->

**New Meeting Time:**
<!-- Enter start and end time (e.g., 3:15 PM - 4:45 PM) -->

**New Location:**
<!-- Enter new location if changing -->

### Participation Changes (if applicable)
**New Maximum Participants:**
<!-- Enter new number if changing -->

**New Grade Level Requirements:**
<!-- Enter new grade requirements if changing -->

**New Prerequisites:**
<!-- Enter updated requirements if changing -->

### Category Change (if applicable)
**New Category:**
<!-- Select from: Sports, Arts, Academic, Community, Technology -->

## 👨‍🏫 Teacher Information

**Requesting Teacher:**
<!-- Your name -->

**Contact Email:**
<!-- Your school email address -->

## 🎯 Acceptance Criteria
<!-- The following will be completed when this is implemented -->

- [ ] Changes are reflected on the activities website
- [ ] Students can see updated information
- [ ] Any schedule changes are properly displayed
- [ ] Registration still works correctly
- [ ] Activity appears in correct category (if changed)
- [ ] Existing registered students are not affected unless specified

## 📝 Reason for Changes

**Why are these changes needed?**
<!-- Explain the reasoning behind the requested modifications -->

**Timeline:**
<!-- When do these changes need to be in effect? -->

**Impact on Current Students:**
<!-- How will this affect students already registered? -->

## ⚠️ Special Considerations

**Additional Notes:**
<!-- Any other important information -->

---
**For Copilot Implementation:**
- Update database entry in `src/backend/database.py`
- Ensure existing registrations are handled appropriately
- Update any hardcoded references if activity name changes
- Test that all functionality continues to work after changes
- Verify category filters work correctly if category changed