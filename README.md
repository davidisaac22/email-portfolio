# Figma Newsletter Email Template

## Overview
This project is a responsive HTML email newsletter inspired by a Figma editorial-style campaign.  
It was built using table-based HTML to ensure maximum compatibility across major email clients.

## Goals
- Create a production-ready marketing email
- Ensure compatibility across Gmail, Apple Mail, and Outlook
- Follow email development best practices
- Maintain a clean, readable layout similar to modern product newsletters

## Tech Stack
- HTML (table-based layout)
- Inline and embedded CSS
- Google Fonts with system font fallbacks

## Layout & Structure Decisions
- All layouts are built using nested tables for consistent rendering in Outlook
- Fixed-width inner tables (512px / 600px) are used instead of max-width on text blocks
- Padding is applied on <td> elements rather than margins to avoid Outlook issues
- No layout <div> elements are used

## Responsiveness Strategy
- Desktop layout uses a centered fixed-width container
- Images include width attributes and responsive CSS (max-width: 100%)
- A mobile media query adjusts container width for smaller screens

## Cross-Client Compatibility
Special care was taken to support:
- Outlook (Windows & Mobile)
- Gmail (Web & Mobile)
- Apple Mail

Techniques used:
- Table-based layout
- Inline styles for critical elements
- Pixel-based line-height for large headings
- MSO-specific resets for Outlook spacing

## Fonts & Images
- Google Fonts are included for supported clients
- System font fallbacks ensure consistent typography in Outlook
- Images include width attributes and alt text where appropriate
- Decorative images use empty alt attributes

## Testing
This email was tested manually in:
- Gmail (Web & Mobile)
- Apple Mail
- Outlook Mobile

Layout consistency, spacing, and image rendering were verified across clients.

## Notes
This template was built as part of an email development portfolio and follows best practices commonly used in production marketing campaigns.