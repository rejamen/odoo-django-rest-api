# -*- coding: utf-8 -*-
# License AGPL-3.0 or later (http://www.gnu.org/licenses/agpl).
# © 2021 Agustin Wisky (<https://github.com/awisky>)

FROM nginx:latest


# Conf files
COPY nginx.conf /etc/nginx/conf.d/

# Delete default files
RUN rm /etc/nginx/conf.d/default.conf

# Expose 8069 port, in which the users will interact with odoo services
EXPOSE 80
