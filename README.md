# Nagare

Nagare is a productivity engine built on the principle of temporal debt. In
Japanese, Nagare translates to "Flow," but this system acknowledges that true
flow is often preceded by resistance. Instead of a traditional stopwatch, Nagare
tracks your leisure as a deficit that must be settled through periods of
high-intensity focus.

The system is designed for individuals who find conventional timers easy to
ignore. By visualizing procrastination as a growing weight, Nagare leverages the
psychological drive to settle balances, pushing you out of stagnation and into
deep work.

The Debt Mechanic

At the heart of Nagare is the Reverse Flowmodoro logic. When you enter Chill
mode, the engine begins accumulating Potential Debt. This is not a countdown; it
is a count-up of time you owe to your objectives. When you switch to Focus mode,
your accumulated debt is paid back at an accelerated rate—by default, 4x speed.
This creates a high-stakes environment where work feels rewarding and rest feels
earned.

Feature Architecture

Interface Design

  - Three-Column Layout: The workspace is divided into three distinct zones:
    progression tracking on the left, the primary engine in the center, and task
    management on the right.
  - Zen Mode: A dedicated toggle that collapses all sidebars and secondary
    information, leaving only the timer and your current objective visible to
    minimize cognitive load.
  - Glassmorphic UI: A dark, high-contrast aesthetic utilizing semi-transparent
    surfaces and heavy background blurs for a focused, modern atmosphere.
  - Dynamic Ambient Glow: Context-aware background lighting that shifts colors
    based on your current state—Focus, Chill, or Standby.

Progression and Leveling

  - XP Engine: You earn 1 XP for every sixty seconds spent in a Focus state.
  - Leveling System: A logarithmic progression curve where each subsequent level
    requires more effort to achieve.
  - Rank Roadmap: Users progress through five evolutionary stages: Initiate,
    Architect, Deep Thinker, Master, and Sage.
  - Atmosphere Unlocks: Visual themes are locked behind level requirements,
    turning your productivity into a means of customizing your environment.

The Artifact Gallery

  - Tiered Achievement System: Six unique artifacts track different aspects of
    your performance, each with Bronze, Silver, and Gold tiers.
  - The Monk: Tracks your ability to sustain long-form focus sessions without
    interruption.
  - The Machine: A lifetime tracker for total minutes spent in a deep work
    state.
  - The Scholar: Rewards the consistent completion of defined objectives.
  - Night Owl: Monitors focus sessions occurring between 12 AM and 5 AM.
  - Early Bird: Monitors focus sessions occurring between 5 AM and 9 AM.
  - Streak King: Measures the longest consecutive day streak achieved.
  - Pinned Showcase: Allows you to select up to three earned badges to display
    prominently in your sidebar.

Statistical Analysis

  - Daily Metrics: Real-time tracking of Focus time, Chill time, and Tasks
    completed within the current 24-hour cycle.
  - Streak Tracker: A persistence monitor that counts consecutive days of engine
    use.
  - Historical Calendar: A built-in calendar grid that logs your daily activity.
  - Data Tooltips: Hovering over any date in the calendar reveals a breakdown of
    focus and chill duration for that specific day.

Task Management

  - Objective Initiation: A dedicated input system for defining your focus
    goals.
  - Current Objective Anchor: The most recent active task is displayed
    prominently above the timer as a constant visual reminder of your current
    mission.
  - Bifurcated Lists: Separate containers for Active and Completed tasks to
    maintain a clear view of your remaining workload.
  - Inline Management: Simple controls for toggling task completion and deleting
    entries.

Personalization and Configuration

  - Variable Multiplier: A slider in the settings panel allows you to adjust the
    debt-to-work ratio, ranging from 1x to 10x.
  - Theme Presets: Access to Midnight, Ocean, Forest, Sunset, and Mono color
    schemes (based on level unlocks).
  - Custom Wallpaper Support: Users can upload their own images to serve as the
    interface background. The system includes a 3MB limit to ensure performance
    and local storage stability.
  - Persistent Memory: All data, including tasks, XP, levels, and settings, is
    saved to the browser's local storage to persist across sessions.

Technical Specifications

  - Heartbeat Engine: A 100ms interval check with drift correction ensures that
    timer accuracy is maintained even if the browser tab is backgrounded.
  - Browser Notifications: System-level alerts notify you when you have reached
    one hour of debt or when a focus session has been successfully settled.
  - Global Keyboard Shortcuts:
      - C: Enter Chill mode.
      - F: Enter Focus mode.
      - X: Reset the current timer.
      - Z: Toggle Zen Mode.
      - Spacebar: Start or Pause the engine.
  - Responsive Typography: The interface uses fluid scaling (clamp logic) to
    ensure the timer display remains legible regardless of screen resolution.
