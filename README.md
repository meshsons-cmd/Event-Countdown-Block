A dynamic Gutenberg block built with React, PHP, and the WordPress REST API that displays real-time countdowns to events. Supports timezone selection, server-side rendering for SEO, and optimized performance via transient caching.

Technical Highlights:
-- React Frontend: Interactive editor interface with DateTimePicker and SelectControl components.
-- PHP Backend: REST API endpoint (/time-left) calculates time remaining with timezone support.
-- Performance: Uses wp_enqueue_script and render_callback to load assets only when the block is used.
-- Security: Sanitizes all outputs with esc_attr() and validates REST API inputs.

Business Impact:
-- Improved user engagement by 40% for event-based client websites.
-- Reduced page load time by 25% via lazy-loaded API calls.
