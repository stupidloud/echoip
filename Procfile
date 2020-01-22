web: xz -d GeoLite2-City.mmdb.xz && xz -d GeoLite2-Country.mmdb.xz && echoip -f GeoLite2-Country.mmdb -c GeoLite2-City.mmdb --listen=":$PORT" --trusted-header="X-Forwarded-For"
