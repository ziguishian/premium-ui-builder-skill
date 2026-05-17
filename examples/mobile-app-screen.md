# Mobile App Screen

## User Original Input

"I want to design a mobile app home screen with clear hierarchy and premium interactions."

## Detected Mode

Mode A: New Project UI Planning.

## Project Type

Mobile app screen.

## UI Goal

Design a focused home screen that helps users understand status and take one primary action.

## Key Design Problems or Assumptions

- Mobile UI cannot carry too many equal-priority blocks.
- Touch targets, spacing, and state feedback define quality.
- Premium interactions should be fast and quiet.

## Recommended UI Strategy

Use Premium Minimal with touch-first hierarchy. Limit the screen to one primary CTA, status summary, and a few relevant modules.

## Information Architecture

- Header: greeting/context and account.
- Primary module: main task or status.
- Secondary modules: recent activity, recommendations, shortcuts.
- Navigation: bottom tabs for 3-5 main areas.
- States: pull-to-refresh, skeletons, empty modules.

## Visual System

- Color: light neutral or dark neutral with one clear accent.
- Typography: strong screen title, readable card titles, compact metadata.
- Cards: stable, rounded enough for touch but not childish.
- Icons: consistent line icons.

## Component System

Top header, status card, primary CTA, shortcut chips, activity list, bottom tab bar, sheet, toast.

## Motion Strategy

Use press feedback, sheet transition, tab switch, and pull-to-refresh. Avoid scroll-heavy reveal on core content.

## Frontend Implementation Recommendation

React Native, Expo, or mobile web depending on project. If web: responsive CSS with touch-safe controls.

## Codex-ready Prompt

```text
Design a premium mobile app home screen. Prioritize one primary user action and a clear status summary. Include top header, primary status card, main CTA, shortcut chips, recent activity, and bottom tab navigation. Visual direction: Premium Minimal, touch-first, restrained colors, consistent radius, clear typography hierarchy, and subtle borders/shadows. Define states for loading skeleton, empty activity, pressed buttons, selected tab, and sheet open. Motion should include quick press feedback, smooth sheet transition, and reduced motion fallback. Avoid too many cards, tiny controls, and desktop-style density. Acceptance: the screen is usable with one hand, the primary action is obvious, and all tap targets are at least 44px.
```

## Acceptance Criteria

- One primary action is obvious.
- Touch targets are safe.
- Bottom navigation has selected state.
- Loading and empty states are planned.
