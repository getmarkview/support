# Sample Issues

Create these sample issues to help users understand how to report:

## Sample Bug Report

**Title:** [Bug]: Export to Word fails with large images

**Body:**

### Bug Description

When I try to export a markdown file with large images (>5MB) to Word format, the export process hangs and eventually fails.

### Steps to Reproduce

1. Create a markdown file with images larger than 5MB
2. Click the "Export to Word" button
3. Wait for the export process
4. Nothing happens after ~30 seconds

### Expected Behavior

The file should export successfully to Word format, even with large images.

### Actual Behavior

The export process hangs and times out without producing a file.

### Extension Version

1.0.2

### Browser

Chrome

### Browser Version

120.0.6099.109

### Operating System

Windows

### Screenshots

[Drag and drop screenshot showing the stuck export]

### Console Errors

```text
Error: Timeout waiting for image conversion
    at exportToDocx (content.js:1234)
```

### Additional Context

This only happens with images larger than 5MB. Smaller images work fine.

---

## Sample Feature Request

**Title:** [Feature]: Add batch export functionality

**Body:**

### Problem Statement

I often need to export multiple markdown files at once, but currently have to export them one by one, which is time-consuming.

### Proposed Solution

Add a "Batch Export" feature in the sidebar that allows:

1. Selecting multiple markdown files
2. Choosing export format (Word, HTML, PDF)
3. Exporting all selected files at once
4. Showing progress for each file

### Alternatives Considered

- Using a script to automate individual exports
- Merging files before export (but this changes the structure)

### Examples

VSCode has a similar feature where you can select multiple files and run actions on them.

### Priority

Important

---

## Sample Question

**Title:** [Question]: How to customize font in exported Word documents?

**Body:**

### Your Question

Is it possible to customize the font used in exported Word documents? I need to use Times New Roman instead of the default font.

### Context

I'm creating documents for academic purposes that require Times New Roman font. The current exports use a different font.

---

These samples help users understand:

- How much detail to provide
- What information is helpful
- The tone and format expected
