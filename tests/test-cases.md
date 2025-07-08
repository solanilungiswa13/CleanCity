🧪 Comprehensive Test Cases
TC_001: Waste Pickup Request Submission
Module: Home Page
Priority: High
Prerequisites: Application loaded successfully
Test Steps:

Navigate to home page (/)
Fill in all required fields:

Name: "John Doe"
Phone: "0712345678"
Location: "Nairobi"
Waste Type: "General"
Pickup Date: Tomorrow's date
Description: "Household waste pickup"


Click "Submit Request" button

Expected Result: Success message displayed, form cleared, request added to system
Bug to Find: Date field validation may not work properly
TC_002: Empty Form Submission
Module: Home Page
Priority: High
Prerequisites: Application loaded successfully
Test Steps:

Navigate to home page (/)
Leave all fields empty
Click "Submit Request" button

Expected Result: Error messages appear for all required fields
Bug to Find: Date field may not show validation error
TC_003: Dashboard Request Filtering
Module: Dashboard
Priority: High
Prerequisites: Sample data loaded
Test Steps:

Navigate to dashboard (/dashboard)
Click on location filter dropdown
Select "Eldoret"
Verify filtered results

Expected Result: Only Eldoret requests should be displayed
Bug to Find: May show Nairobi requests instead
TC_004: Admin Panel Status Update
Module: Admin Panel
Priority: High
Prerequisites: Admin panel accessible
Test Steps:

Navigate to admin panel (/admin)
Find a request with "Pending" status
Click "Mark as Scheduled" button
Verify UI updates immediately

Expected Result: Status updates immediately, UI refreshes
Bug to Find: UI may not refresh automatically
TC_005: Accessibility Testing - Images
Module: Awareness Page
Priority: Medium
Prerequisites: Screen reader available
Test Steps:

Navigate to awareness page (/awareness)
Use screen reader to navigate images
Verify alt-text descriptions

Expected Result: All images should have descriptive alt-text
Bug to Find: Missing alt-text on all images
TC_006: Responsive Design Testing
Module: All Pages
Priority: Medium
Prerequisites: Browser with responsive tools
Test Steps:

Open browser DevTools
Toggle device simulation
Test on mobile (375px width)
Test on tablet (768px width)
Verify layout and functionality

Expected Result: All pages responsive and functional
Potential Issues: Layout breaks or buttons too small
TC_007: Feedback Form Submission
Module: Feedback Page
Priority: Medium
Prerequisites: Valid request ID available
Test Steps:

Navigate to feedback page (/feedback)
Enter valid request ID (e.g., "REQ001")
Select issue type
Add feedback description
Submit form

Expected Result: Feedback submitted successfully
Test Variations: Invalid request ID should show error
TC_008: Boundary Testing - Long Text Input
Module: Home Page
Priority: Low
Prerequisites: Application loaded
Test Steps:

Navigate to home page (/)
Enter very long text (500+ characters) in description field
Submit form
Check layout and functionality

Expected Result: System handles long input gracefully
Bug to Find: May cause layout issues