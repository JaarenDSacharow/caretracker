# caretracker

This is a scaffold for an application written for two purposes: to demonstrate concepts in Vue.js and to allow the coordination of care for infirm adults by care givers.

The application is intended to allow a user to create/manage patients and care givers and the associated care needs and tasks.

At present, the application demonstrates these concepts in Vue.js:

- Routing using the vue-router library.  http://router.vuejs.org/
- Components using Vue.extend
- Templates, using declarative directives as well as templating syntax.
- CRUD operations on both Patient and Caregiver entities, and the nested list of patient needs and care giver tasks.  All logic is at the component level.


All data is currently hardcoded.
All code is currently on one single html file.  It has not presently been modularized.

TODO:

- Enhance the UI and models to allow for a patient to have multiple caregivers and vice versa.
- Enhance the underlying data model to allow for a peristent data store
- Enhance the UI with proper CSS
- Modularize the code to be optimized for use with webpack
- Implement a push notification and scheduling system to notify caregivers when a task is due and when a new task is entered and assigned.
