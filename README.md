# Fitness Training Manager — Offline & Local (Revised Overview)

## What It Is

A professional-grade offline application for fitness trainers and coaches to manage their training business entirely on a local device. It provides a complete platform for organizing clients (trainees), building customized workout programs, tracking progress, and generating professional training materials—without any cloud services or online database connections.

## Core Capabilities

1. **Trainee (Client) Management**
   - Create and store detailed client profiles (name, age, gender)
   - Record comprehensive body measurements (height, weight, body fat %, chest, waist, hips, arm, thigh circumferences)
   - Store unlimited trainee profiles locally (on-device)
   - Search, filter, edit, and delete trainee records
   - View trainee information in grid or list layouts

2. **Workout Plan Creation**
   - Build custom workout programs for individual trainees
   - Multiple creation modes:
     - Template-based (use pre-designed workout programs)
     - Weekly planner (day-by-day schedules)
     - Exercise library browsing (manual add)
   - Drag-and-drop interface for reordering exercises
   - Configure sets, reps, rest periods, and notes for each exercise
   - Superset configurations (paired exercises)
   - Save multiple workout plans per trainee
   - Edit and delete existing plans

3. **Exercise Library (Local)**
   - Built-in library with 40+ exercises covering: chest, back, shoulders, arms, legs, core
   - Each exercise includes:
     - English and Persian names
     - Muscle group categorization
     - Equipment requirements (barbell, dumbbell, cable, machine, bodyweight)
     - Difficulty levels (beginner/intermediate/advanced)
   - Add custom exercises with bilingual naming
   - Edit and delete custom exercises
   - Filter by category, equipment, difficulty
   - Search functionality

4. **Workout Templates**
   - Pre-designed training programs, available offline:
     - Full Body Beginner (3 days/week)
     - Push/Pull/Legs Split (6 days/week)
     - Upper/Lower Split (4 days/week)
     - Strength & Power Program (4 days/week)
     - Bodybuilding Split (5 days/week)
   - Each template includes suggested exercises, training frequency, and duration.

5. **Export & Delivery System (Offline)**
   - Export workout plans in multiple formats:
     - PDF (printable professional documents)
     - JPEG/PNG (mobile-friendly images)
     - TXT (plain text)
     - Workout Cards (gym-ready cards with QR codes)
   - Bulk export (multiple plans at once)
   - Layout options (detailed / compact / card format)
   - Include/exclude QR codes
   - Export includes trainee info + all exercise specifications
   - All exports work without internet

6. **Progress Tracking (Local)**
   - Body Measurements: track changes over time
   - Progress Photos: import and organize photos (front/side/back), compare before/after
   - Performance Records: log lifted weight/reps/sets, estimated 1RM, total volume, PR tracking
   - Progress Charts: visual trends and improvements

7. **Analytics & Insights (Local Dashboard)**
   - Total trainees count
   - Total workout plans created
   - Average trainee age
   - Plans per trainee ratio
   - Gender distribution charts
   - Age distribution analysis
   - Plans created over time
   - Activity trends

8. **Preset Management**
   - Create quick-select presets for:
     - Sets (3, 4, 5, …)
     - Reps (8, 10, 12, 15, …)
     - Rest periods (30s, 60s, 90s, 2min, …)
   - Bilingual preset labels
   - Custom preset creation
   - Speeds up plan building

9. **Workout Calendar**
   - Schedule and visualize training sessions
   - Track completed vs planned workouts
   - Mark sessions complete
   - Add notes per training day
   - Overview of training frequency

10. **Local Authentication & User Profiles (Offline)**
    - Optional local login (username + password)
    - Multiple local user profiles on the same device (optional)
    - Role-based access can be supported locally (e.g., admin vs regular)
    - No online registration, no remote approval workflow
    - Optional security enhancements (recommended):
      - Encrypted local storage
      - Auto-lock / session timeout

11. **Data Management (Local-First)**
    - Local Storage: all data saved on-device (e.g., local database/file-based storage)
    - No cloud sync, no real-time online synchronization
    - Backup & Restore:
      - Export full backups (e.g., JSON) including trainees, plans, exercises, presets
      - Restore from backup files anytime
    - Optional: manual export/import for moving data between devices

12. **Bilingual Support (English + Persian)**
    - Instant language switching
    - RTL layout for Persian
    - All UI elements translated
    - Exercise names/categories in both languages
    - Measurement labels bilingual
    - Export documents in selected language
    - Language preference saved locally

13. **Theme System**
    - Multiple visual themes:
      - Starfield (Dark): dark navy space theme with animated stars + gradient accents
      - Snow Theme: light winter aesthetics with falling snowflakes
      - Standard Light: clean light theme
    - Theme selection saved locally
    - Smooth transitions

14. **Responsive Design**
    - Works on desktop
    - Optimized for tablets
    - Mobile-friendly interface with touch gestures
    - Swipe navigation on mobile
    - Adaptive layouts for all screen sizes
    - Touch-optimized drag-and-drop
    - Mobile sidebar navigation

### Technical Capabilities (Offline Edition)

- Local-first architecture: works fully without internet
- Fast performance: efficient rendering and storage
- Reliable persistence: data remains available across sessions
- Accessibility: keyboard navigation, screen reader support, ARIA labels
- Print-ready exports: professional formatting for client delivery

This offline version replaces spreadsheets and fragmented tools with a unified on-device system for client onboarding, program design, progress monitoring, analytics, and professional exports—while keeping all data local and under the trainer’s control.
