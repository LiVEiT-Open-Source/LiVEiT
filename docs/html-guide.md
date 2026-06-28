# HTML Guide

## Introduction

This guide explains how the LiVEiT® Framework is implemented using HTML.

Rather than simply providing code, this document explains the design decisions behind the official implementation.

Understanding *why* the framework has been built in a particular way is just as important as understanding the code itself.

---

# Why HTML?

The LiVEiT® Framework has been designed to be as accessible as possible.

HTML provides a universal foundation that works across operating systems, browsers and devices without requiring proprietary software.

By building upon open web standards, developers are free to adapt the framework to suit their own projects.

---

# Why SVG?

The official LiVEiT® Circle uses SVG (Scalable Vector Graphics).

SVG provides several important advantages:

- Infinite scaling without loss of quality.
- Individual elements can be identified.
- Each position can be interactive.
- Colours can be customised.
- Animations are supported.
- Accessibility features can be added.

This makes SVG the ideal foundation for the LiVEiT® Circle.

---

# Separation of Responsibilities

The official implementation follows a simple structure.

- HTML defines the structure.
- CSS controls appearance.
- JavaScript controls behaviour.
- Content remains separate from presentation wherever possible.

This separation makes the framework easier to maintain and extend.

---

# Accessibility

Accessibility is a core principle of the LiVEiT® Framework.

Every implementation should aim to support:

- Keyboard navigation.
- Screen readers.
- High contrast themes.
- Responsive layouts.
- Clear typography.
- Meaningful alternative text.

Accessibility should never be considered an optional feature.

---

# Official HTML Template

The official HTML implementation of the LiVEiT® Circle will be documented in the next revision of this guide.

This will include:

- Circle layout.
- SVG structure.
- Modal system.
- Navigation.
- Responsive behaviour.
- Accessibility recommendations.

---

# Next Guide

Once you're familiar with the HTML structure, continue with the CSS Guide to learn how the official LiVEiT® appearance is created.
