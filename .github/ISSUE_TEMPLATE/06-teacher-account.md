---
name: 👤 Teacher Account Request
about: Request new teacher account or changes to existing teacher accounts
title: '[ACCOUNT] Teacher account for [Teacher Name]'
labels: ['enhancement', 'teacher-account', 'teacher-request']
assignees: []
---

## 👤 Account Request Type

**What type of account request is this?**
<!-- Check one -->
- [ ] New teacher account needed
- [ ] Update existing teacher account
- [ ] Remove/deactivate teacher account
- [ ] Reset teacher password
- [ ] Other account issue

## 👨‍🏫 Teacher Information

### For New Accounts:
**Teacher Name:**
<!-- Full name as it should appear in the system -->

**School Email Address:**
<!-- Must be school domain email -->

**Department:**
<!-- Which department/subject area -->

**Username Preference:**
<!-- Preferred username for login (if different from email) -->

### For Existing Account Changes:
**Current Username:**
<!-- Current login username -->

**Current Email:**
<!-- Current email on file -->

**What needs to be changed?**
<!-- Check all that apply -->
- [ ] Name update
- [ ] Email address change
- [ ] Department change
- [ ] Password reset
- [ ] Account permissions
- [ ] Other: _______________

**New Information:**
<!-- Provide the updated details -->

## 🔐 Account Permissions Needed

**What should this teacher be able to do?**
<!-- Check all that apply -->
- [ ] View all activities and registrations
- [ ] Add new activities
- [ ] Modify existing activities they supervise
- [ ] Modify any activities (admin level)
- [ ] View student registration data
- [ ] Export student lists
- [ ] Send notifications to students
- [ ] Other: _______________

## 🎯 Activities They Will Supervise

**Which activities will this teacher oversee?**
<!-- List specific activities or "TBD" if not yet determined -->

**Will they create new activities?**
- [ ] Yes, they will be adding new activities
- [ ] No, they will only supervise existing activities
- [ ] Not sure yet

## 📋 Requestor Information

**Who is making this request?**
<!-- Your name and role -->

**Your Contact Email:**
<!-- Your school email address -->

**Authorization:**
<!-- Check one -->
- [ ] I am the teacher requesting my own account
- [ ] I am an administrator authorized to request teacher accounts
- [ ] Other: _______________

## ⏰ Timeline

**When is this account needed?**
<!-- Specific date or "ASAP" -->

**Is this time-sensitive?**
- [ ] Yes, needed immediately for current activities
- [ ] Standard request, no rush
- [ ] Future planning, flexible timing

## 🎯 Acceptance Criteria
<!-- The following will be completed when this request is fulfilled -->

- [ ] Teacher account is created/updated in the system
- [ ] Teacher can successfully log in with provided credentials
- [ ] Teacher has appropriate permissions for their role
- [ ] Teacher can access and manage their assigned activities
- [ ] Account appears correctly in teacher management system
- [ ] Temporary password is provided securely (for new accounts)

## 🔒 Security Considerations

**Account Security:**
<!-- Check all that apply -->
- [ ] Teacher has been verified as legitimate school employee
- [ ] Teacher will be required to change temporary password on first login
- [ ] Teacher understands data privacy requirements
- [ ] Teacher has completed required security training

## 📝 Additional Context

**Special Requirements:**
<!-- Any special access needs or limitations -->

**Related Accounts:**
<!-- Any other teacher accounts this relates to -->

**Notes:**
<!-- Any other relevant information -->

---
**For Copilot Implementation:**
- Add/update teacher entry in `src/backend/database.py` in `initial_teachers` array
- Generate secure hashed password using existing `hash_password` function
- Ensure proper username format and uniqueness
- Update authentication system in `src/backend/routers/auth.py` if needed
- Test login functionality works correctly
- Verify teacher can access appropriate management features