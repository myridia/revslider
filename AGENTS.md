# AGENTS.md — revslider

## What this is
Backup copy of the Revolution Slider WordPress plugin (latest PHP version). Licensed commercially — purchase required for production use.

## Stack
- PHP (WordPress plugin)
- JavaScript (Gutenberg blocks)
- SCSS

## Build
No build step — WordPress plugin files.

## Run
Place in `wp-content/plugins/` and activate via WordPress admin.

## Structure
- `revslider/revslider.php` — main plugin file
- `revslider/admin/` — admin UI classes and assets
- `revslider/public/` — frontend rendering
- `revslider/languages/` — translation files
- `revslider/admin/includes/shortcode_generator/` — Gutenberg, Elementor, Divi integrations

## Conventions
- No comments in code unless asked.
- Commercial license — this is a backup only.
