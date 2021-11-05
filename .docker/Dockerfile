FROM mediawiki:1.36

# https://www.mediawiki.org/wiki/Extension:PluggableAuth
RUN curl https://extdist.wmflabs.org/dist/extensions/PluggableAuth-REL1_36-087cb4c.tar.gz -o plug.tar.gz \
	&& tar -xzf plug.tar.gz -C extensions \
	&& chown -R www-data:www-data extensions/PluggableAuth \
	&& rm plug.tar.gz

# https://www.mediawiki.org/wiki/Extension:WSOAuth
RUN curl https://extdist.wmflabs.org/dist/extensions/WSOAuth-REL1_36-9e89ddc.tar.gz -o wso.tar.gz \
	&& tar -xzf wso.tar.gz -C extensions \
	&& chown -R www-data:www-data extensions/WSOAuth \
	&& rm wso.tar.gz
