## Rationale

Vortex ships with over 50 extensions, all are supposed to be able to build on their own even though they are usually seen as part of one application. 
Unfortunately it's not uncommon that certain common dependencies need to be updated across all extensions, either due to security updates or because
an update broke the api.

This module contains nothing but dependencies that we need in all or at least most extensions so that we can update these dependencies in a central location.

