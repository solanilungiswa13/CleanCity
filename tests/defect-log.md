**BUG_001: Date Field Validation Missing**

- Date Reported: [08.06.2025]
- Module: Home Page - Form Validation
- Severity: High
- Priority: P1
- Status: Open

**Description**: Date field doesn't show validation error when submitted empty
**Steps to Reproduce:**

1. Navigate to home page
2. Leave date field empty
3. Fill other required fields
4. Submit form

- Expected Result: Date field should show validation error
- Actual Result: No validation error displayed for date field
- Environment: All browsers
- Screenshots: [Attach screenshot showing missing error]

**BUG_002: Location Filter Malfunction**

- **Date Reported**: [08.06.2025]
- **Module**: Dashboard - Filtering
- **Severity**: High
- **Priority**: P1
- **Status**: Open

Description: Eldoret location filter shows Nairobi requests instead
**Steps to Reproduce:**
1. Navigate to dashboard
2. Apply "Eldoret" filter
3. Observe results

- Expected Result: Only Eldoret requests displayed
- Actual Result: Nairobi requests shown instead
- Environment: All browsers

**BUG_003: Missing Alt-Text on Images**

**Date Reported**: [08.06.2025]
**Module**: Awareness Page - Accessibility
**Severity**: Medium
**Priority**: P2
**Status**: Open

**Description**: All images on awareness page missing alt-text attributes
**Steps to Reproduce:**

1. Navigate to awareness page
2. Use screen reader or inspect HTML
3. Check image alt attributes

- Expected Result: All images have descriptive alt-text
-  Result: Alt-text attributes missing
- Environment: All browsers