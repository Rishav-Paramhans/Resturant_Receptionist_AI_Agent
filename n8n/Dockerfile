# Use the official n8n image
FROM n8nio/n8n:latest

# Set working directory
WORKDIR /data

# Set the N8N_RELEASE_DATE environment variable (optional)
ENV N8N_RELEASE_DATE="2025-03-15T20:15:21Z"

# Enforce correct permissions for settings file
ENV N8N_ENFORCE_SETTINGS_FILE_PERMISSIONS=true

# Expose the default n8n port
EXPOSE 5678

# Explicitly set entrypoint
ENTRYPOINT ["n8n"]

# You can also pass arguments to `n8n` (optional)
CMD []