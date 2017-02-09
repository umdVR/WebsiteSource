# First time
Clone WebsiteSource, name it umdVR/ (that's how I'll refer to it).

# Workflow
1. Raise issues and make changes in local umdVR/
2. Push changes to WebsiteSource/
3. Use hugo to render (or rerender) the public/ folder using umdVR/
4. Push changes in public/ to Website/
5. Now wait as (1) your files finish uploading, (2) github finishes building your site, and (3) one.com breaks cache. Note that the last step takes up to 10 minutes, but should happen instantly if you are pushing a new file.

## Diagram
|Local            |Github          |

|==================================|

|umdVR/           |WebsiteSource/  |

|--public/        |Website/        |

Note: public/ will be generated inside the umdVR/ folder after Hugo.
