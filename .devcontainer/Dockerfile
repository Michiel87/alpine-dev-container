# Use the latest version of Alpine
FROM alpine:latest

# Install basic tools and dependencies
RUN apk update && apk add --no-cache \
    bash \
    curl \
    git \
    nano \
    nodejs \
    npm \
    yarn

# Set up your development environment
# (Add additional configuration or software installations here)

# Set the working directory in the container
WORKDIR /app

# Optional: if your application uses a specific port, expose it
# EXPOSE 3000

# Optional: add a default command or entrypoint, such as starting a development server
# CMD ["npm", "start"]
