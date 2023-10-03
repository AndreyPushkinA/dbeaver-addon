FROM dbeaver/cloudbeaver:latest
RUN groupadd cloudbeaver
RUN useradd -ms /bin/bash -g cloudbeaver cloudbeaver
RUN chown -R cloudbeaver ./
EXPOSE 8080 8978
COPY cloudbeaver.conf /etc/cloudbeaver/cloudbeaver.conf
USER cloudbeaver
