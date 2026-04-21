FROM hardcoreeng/front:v0.7.382

# Kanbee-branded assets. These overlay the stock Huly defaults baked in
# at /app/dist. The branding.json matches hostnames at runtime to pick
# the active brand, so both localhost:8087 (dev) and the production
# domain need entries.
COPY branding.json /app/dist/branding.json
COPY kanbee/      /app/dist/kanbee/
