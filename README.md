# EspoCRM Travel Agent Customization

This repository contains entity definitions, layouts, workflows, email templates, and custom scripts for adapting EspoCRM to a travel agency use case.

## Key Entities
- Booking
- Trip
- Destination
- ItineraryItem
- Vendor (planned)

## Folder Structure
- `/custom/Entities`: Definitions for new CRM entities.
- `/custom/Layouts`: Custom layout files for entity views.
- `/workflows`: Workflow automation configurations.
- `/templates/email`: Email templates for confirmations and reminders.
- `/scripts`: Custom PHP scripts (e.g. for exports or integrations).

## Setup
1. Copy the contents of `custom/` into your EspoCRM `/custom` directory.
2. Import workflows via the GUI.
3. Add templates under Admin > Email Templates.
4. Place any custom scripts in EspoCRM’s base directory and schedule with cron if needed.
