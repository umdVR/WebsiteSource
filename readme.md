# First time
Clone WebsiteSource, name it umdVR/ (that's how I'll refer to it).

# Workflow
1. Make changes in local umdVR/
2. Raise issues and push changes to WebsiteSource/
3. Render the public/ folder using umdVR/
4. Push changes in public/ to Website/
5. Now wait as (1) your files finish uploading, (2) github finishes building your site, and (3) one.com breaks cache. Note that the last step takes up to 10 minutes, but should happen instantly if you are pushing a new file.

# Diagram
<pre>
umdVR/ -- (push to) --> websiteSource/
├── archetypes/
├── data/
├── layouts/ 
├── config.toml
├── public/ -- (push to) --> website/
└── static/
│   └── tabular/
</pre>
public/ will not show up in websiteSource because of the gitignore.

### Other
The cool background is from particles.js
