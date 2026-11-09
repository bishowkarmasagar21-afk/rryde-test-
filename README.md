# Rryd Test Site

This repository contains an isolated copy of the PR #6 driver and passenger web portals for testing the GPS meter and verified fare display.

- `index.html`: test landing page
- `driver.html`: driver test portal
- `passenger.html`: passenger test portal

## Important
- This is a separate GitHub repository and does not change the live Rryd repository.
- The copied portal files retain the backend configuration from the PR branch. Until a separate Supabase test project is configured, actions may affect the currently configured Rryd Supabase project.
- Use test accounts only. Do not test with real customer rides.
- Do not add service-role keys or worker secrets to browser files.
- GitHub Pages must be enabled for this repository before the site URL will work.
