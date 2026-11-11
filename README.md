# Cleannnn support site

Independent static support and privacy pages for the Cleannnn iOS app.

- `index.html`: support, cleanup behavior, memberships and contact.
- `privacy.html`: Chinese and English privacy policy.
- `style.css`: shared style; no scripts, analytics, cookies or external fonts.

Deploy these three public files together to the selected Alibaba Cloud web root.
No app source, credentials, review contact phone number or user photos belong in this repository.
The existing site/server configuration must be inspected before selecting the deployment path.

Published pages:

- Support: https://api.ccrecipe.cn/cleannnn/
- Privacy: https://api.ccrecipe.cn/cleannnn/privacy.html

The site is served as static files through the existing HTTPS endpoint. It has no
application server, database, analytics, or JavaScript dependencies.
