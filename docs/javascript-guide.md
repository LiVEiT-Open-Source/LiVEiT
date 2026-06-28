# JavaScript Guide

## Introduction

JavaScript provides the interactive behaviour of the LiVEiT® Framework.

While HTML defines the structure and CSS controls the appearance, JavaScript allows users to interact with the framework in meaningful ways.

The goal is not to create unnecessary complexity, but to enhance understanding through responsive and intuitive interaction.

---

# Design Philosophy

Every interaction should have a purpose.

The framework should remain:

- Simple
- Predictable
- Accessible
- Responsive
- Easy to maintain

Developers should avoid adding interaction that distracts from the purpose of the framework.

---

# Core Responsibilities

Within the official implementation, JavaScript is responsible for:

- Opening and closing modal windows.
- Responding to user interaction.
- Managing navigation.
- Updating content dynamically.
- Handling animations.
- Supporting accessibility features.

JavaScript should not control the visual appearance of the framework.

---

# Progressive Enhancement

The LiVEiT® Framework follows the principle of progressive enhancement.

HTML provides the structure.

CSS provides presentation.

JavaScript enhances the user experience.

Whenever possible, content should remain accessible even if JavaScript is unavailable.

---

# Event Handling

Developers are encouraged to use clear and descriptive event handling.

Examples include:

- Click events
- Keyboard events
- Touch events
- Focus events

Every interaction should be intuitive and accessible.

---

# Modal System

The official LiVEiT® implementation uses modal windows to present additional information.

Each modal should:

- Open smoothly.
- Close consistently.
- Support keyboard navigation.
- Return focus correctly when closed.
- Prevent unnecessary scrolling when active.

Consistency is more important than visual effects.

---

# Performance

JavaScript should remain lightweight.

Recommended practices include:

- Minimise unnecessary processing.
- Avoid duplicate code.
- Keep functions focused on a single responsibility.
- Optimise for responsiveness.

The framework should remain fast across desktop and mobile devices.

---

# Accessibility

Every interactive element should support:

- Keyboard navigation.
- Screen readers.
- Visible focus indicators.
- Logical tab order.
- Meaningful labels.

Accessibility is a fundamental design requirement, not an optional enhancement.

---

# Extensibility

Developers are encouraged to extend the framework while preserving its core principles.

New functionality should integrate naturally with the existing architecture rather than replacing it.

---

# Future APIs

Future versions of the LiVEiT® Framework may include standardised JavaScript APIs to simplify the creation of custom implementations and third party integrations.

---

# Next Guide

Continue with the Design System guide to learn about the visual identity and user experience principles of the LiVEiT® Framework.
