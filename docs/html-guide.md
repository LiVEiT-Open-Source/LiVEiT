# LiVEiT® HTML Guide

## Introduction

This guide explains how to build the official LiVEiT® Circle using standard HTML.

The reference implementation has been designed to be lightweight, accessible and easy to integrate into both static websites and modern web frameworks.

The HTML provided by the LiVEiT® Open Source Project forms the foundation upon which developers can build their own implementations.

---

# Objectives

The HTML implementation should:

- Be simple to understand.
- Be easy to customise.
- Be framework independent.
- Work with standard CSS and JavaScript.
- Support accessibility.
- Encourage reuse.

---

# Recommended Structure

A typical implementation consists of:

```
Page
│
├── Container
│
├── Circle
│   ├── Centre
│   ├── Position 1
│   ├── Position 2
│   ├── ...
│   └── Position 12
│
└── Content Area
```

---

# Core Components

The official HTML implementation normally contains:

- Main container
- Circle container
- Twelve interactive positions
- Centre element
- Content panel
- Modal windows (optional)
- Navigation controls (optional)

---

# Naming Conventions

We recommend meaningful class names.

Examples include:

```
.liveit-container
.liveit-circle
.liveit-centre
.liveit-position
.liveit-modal
.liveit-button
.liveit-panel
```

Developers are free to adapt these names to suit their own coding standards.

---

# Accessibility

Interactive elements should:

- Be keyboard accessible.
- Include descriptive labels.
- Provide visible focus indicators.
- Support screen readers.

Accessibility should be considered from the beginning of every implementation.

---

# Responsive Design

The circle should scale naturally across devices.

Implementations should work on:

- Desktop
- Laptop
- Tablet
- Mobile

Developers should avoid fixed dimensions where possible.

---

# Customisation

The HTML structure is intentionally generic.

Developers may customise:

- Colours
- Content
- Typography
- Animations
- Icons
- Layout

while preserving the overall framework structure.

---

# Relationship with CSS

The HTML defines structure.

CSS defines presentation.

The official CSS implementation is documented separately in:

docs/css-guide.md

---

# Relationship with JavaScript

The HTML provides interaction points.

JavaScript provides behaviour.

The official JavaScript implementation is documented separately in:

docs/javascript-guide.md

---

# Official Reference Implementation

The official LiVEiT® HTML reference implementation will be maintained within this repository.

Developers are encouraged to use it as a starting point for their own projects while contributing improvements back to the community.

---

# Looking Forward

Future releases may include:

- Accessibility examples
- Semantic HTML examples
- Progressive enhancement examples
- Framework integrations
- Template libraries

The objective is to make the LiVEiT® Framework straightforward to adopt regardless of experience level.- Content remains separate from presentation wherever possible.

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
