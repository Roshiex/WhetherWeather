Roisin Gleeson 18326316

Whether Weather

A static weather dashboard built with Eleventy and Nunjucks, designed to display city weather data, hourly condiitons, weekly forecasts, suntimes and user preferences with a focus on clean layout, accessibility and user expereince.


Project Overview:
Whether Weather is a multi page weather dashboard that allows users to:
- View current weather conditions for multiple cities
- Navigate to individual city page with detailed forecasts
- Access a user preferences page
- View sunrise and sunset times for each city
- navigate cleanly between pages using a consistent layout 

This project was built as part of a templating and state-site workflow using Eleventy.


Tech Stack:
-Eleventy (11ty) - static site generator
-Nunjunks - templating language
-HTML & CSS - layout and styling
-Bulma CSS - grid system and UI helpers
-JSON data files - weather and city data

Features by Release:

Release 1 - Dashboard:
-Displays a grid of cities
-Shows today's weather
-Displays max temperature and wind speed
-Clickable city cards for navigation

Release 2 - City View:
-Individual city pages generated using pagination
-Today's weather
-Current hour weather
-7 day forecast summary
-Colour coded forecast cards based on weather conditions

Release 3 - User Experience & Extensions:
-User Preferences page
-Accessibility options (visual toggles)
-Sunrise & sunset times page
-consistent navigation and layout across pages


Accessibility Considerations:
This project includes accessibility focused UI options:
-Colour blind mode (reduced saturation)
-Increased text size options
-High contrast friendly layouts
-Clear visual hierarchy and readable typography


Sunrise and Sunset Page:
The site includes a Sunrise & Sunset Times page:
-Displays sunrise and sunset for each city
-Uses distinct visual style
-Maintains consistent card layout while visually differentiating content



Each city displays:

-Sunrise time (warm gradient styling)
-Sunset time (cool purple gradient styling)
-Clear iconography for visual distinction 

This page was intentionally seperated from teh main dashboard to:
-Reduce visual overload
-Group related time based info
-Demonstrate reusable templating with shared data

Installing & Running the project:

npm install
npx eleventy --serve

The site will be available locally at:
http://localhost:8080




References:

https://www.flaticon.com/ icons created by Freepik, Culmbio and Hexagon075 - Flaticon
https://bulma.io/documentation/
https://www.11ty.dev/docs/
https://www.11ty.dev/docs/assets/
https://www.11ty.dev/docs/usage/
https://www.11ty.dev/docs/plugins/navigation/
https://www.11ty.dev/docs/layouts/
https://www.11ty.dev/docs/pagination/
https://www.11ty.dev/docs/data-js/
https://www.11ty.dev/docs/plugins/navigation/#adding-entries
https://mozilla.github.io/nunjucks/
https://mozilla.github.io/nunjucks/templating.html#template-inheritance
https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Selectors/:has
https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/filter
https://docs.netlify.com/
https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Grid_layout
https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Flexible_box_layout