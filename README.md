# timecode-clicker
Need help for android app Timecode log with clicker :) (first time here)

Timecode Marker Application - Project Overview
Purpose
Develop a simple, functional Android application designed for personal use, enabling users to mark
specific moments with precise timecode data during interviews or events. The application will be
versatile, capable of working with external timecode generators or using the devices internal clock
when timecode is not manually specified.
Key Features
Timecode Functionality:
- Default Timecode: Uses the current time of the device if no manual timecode is specified. Time
format follows HH:MM:SS:FF, where FF defaults to 00 for internal clocks. Subsequent markers at
the same timestamp increment the frame value.
- Manual Timecode Entry: Allows input of specific timecodes.
- External Timecode Integration: Synchronization with Bluetooth timecode generators (e.g., Tentacle
Sync) with options to specify frame rates for stability.
Marker Management:
- Clicker Integration: Supports Bluetooth clickers for easy marker creation.
- Manual Marker Control: Add, edit, or delete markers within the app.
- Customizable Markers: Assign notes, select colors compatible with Adobe Premiere Pro.
Project-Based Workflow:
- Project Creation and Management: Create multiple projects; markers are associated with active
projects.
- Revisit and Edit Projects: Open existing projects to review or modify markers.
- Project Metadata: Includes creation date for clear organization.
Export Functionality:
- Compatible File Formats: Export markers as XML or CSV files for Adobe Premiere Pro.
- Timecode Alignment: Retain original timecodes or reformat for manual settings.
Configuration Options:
- Specify frame rates for external generators; internal clocks default frames to 00.
- Options for color assignment and marker appearance.
User Workflow
1. Setup:
- Open the app and select the timecode source (internal clock, manual input, or Bluetooth sync).
- Create or open a project.
2. Recording:
- Use a Bluetooth clicker or manual controls to add markers.
- Assign notes and colors to markers as needed.
3. Export:
- Save project markers as XML or CSV files for Adobe Premiere Pro.
- Choose alignment options for timecodes during export.
Technical Details
- Platform: Android (developed in Kotlin or Flutter).
- Bluetooth Communication: Utilize Androids Bluetooth API for device connections.
- UI/UX Design: Basic functional interface optimized for efficiency.
- Data Handling: Local database (e.g., SQLite) to store projects, markers, and configurations.
- Timecode Management: Frame accuracy ensured with external generators; internal clocks use 00
frames.
Scope and Limitations
- Non-Commercial Use: The app is for personal use only, with no intention of commercialization.
- Limited Aesthetic Requirements: Focused on functionality, not visual appeal.
Potential Challenges
- Bluetooth Stability: Ensuring reliable communication with clickers and external devices.
- Frame Accuracy: Maintaining precise timecode alignment may require testing with various frame
rates.
- Export Compatibility: Ensuring seamless file integration with Adobe Premiere Pro
