# BeaBoo

## Overview

BeaBoo is a web application built with HTML, JavaScript, and Tailwind CSS. The project appears to be in early development stages with a focus on client-side protection mechanisms. The application implements anti-debugging and anti-inspection features to protect the source code from unauthorized viewing. The project includes Google AdSense integration for monetization purposes.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Static HTML/CSS/JavaScript**: Single-page application using vanilla JavaScript
- **Styling Framework**: Tailwind CSS via CDN for utility-first styling
- **Typography**: Google Fonts (Nunito) for consistent typography
- **Language**: Spanish (es) as the primary language

### Security Architecture
- **Anti-Debugging Protection**: Implements multiple layers of client-side protection
  - Disables right-click context menu
  - Blocks developer tool keyboard shortcuts (F12, Ctrl+Shift+I, Ctrl+Shift+J, Ctrl+U)
  - Continuous debugger statements to prevent debugging
  - Console warnings to deter code inspection
- **Rationale**: Protects intellectual property and prevents unauthorized code access, though client-side protections have inherent limitations

### Monetization Strategy
- **Google AdSense Integration**: Embedded ad serving for revenue generation
- **Publisher ID**: ca-pub-4653147807800151 configured for ad delivery

## Recent Changes

### Code Structure Fixes (September 2025)
- **Fixed JavaScript Code Exposure**: Resolved critical issue where JavaScript code was displaying as visible text in the search function
- **Template Literal Syntax**: Corrected improperly nested template literals that caused parsing errors
- **Search Modal Structure**: Cleaned up HTML structure in search view modal, removing misplaced script blocks
- **Code Organization**: Ensured all JavaScript code is properly encapsulated within script tags
- **Performance**: Eliminated LSP diagnostics errors for better code reliability

## External Dependencies

### CDN Services
- **Tailwind CSS**: https://cdn.tailwindcss.com for styling framework
- **Google Fonts**: Nunito font family for typography
- **Google AdSense**: https://pagead2.googlesyndication.com for advertisement serving

### Third-party Integrations
- **Google AdSense**: Monetization platform for displaying contextual advertisements
- **Firebase**: Backend services for authentication and data storage
- **No Database**: No persistent data storage implemented