# UAT Bug Report – Housing Repairs Management System

## Project Context
While performing User Acceptance Testing (UAT) on a Housing Repairs Management System, I identified an issue affecting the workflow for creating repair variations.

## Bug Summary
When attempting to add a variation to a repair order, navigating away from the variation page returns the user to the previous screen. This requires the user to reopen the variation page to continue the process.

## Steps to Reproduce
1. Open an existing repair order
2. Navigate to the Variation page
3. Attempt to move back to the previous screen
4. Return to the repair order workflow

## Expected Result
The system should retain the user within the variation workflow or provide a smoother navigation path without requiring the user to reopen the variation page.

## Actual Result
The system returns the user to the previous screen, forcing them to reopen the variation page and repeat navigation steps.

## Impact
This behaviour interrupts the workflow and increases the time required to complete repair order variations.

## Testing Type
User Acceptance Testing (UAT)

## Key Skills Demonstrated
- Manual Testing
- UAT Testing
- Bug Documentation
- Workflow Analysis
