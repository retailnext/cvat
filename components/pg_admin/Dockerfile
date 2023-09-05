FROM dpage/pgadmin4
COPY ./server_config.json /tmp
RUN source /venv/bin/activate && python3 /pgadmin4/setup.py --load-servers /tmp/server_config.json --user bvi.admin@retailnext.net
