# Svurl Service

Backend endpoint for a CLI-style bookmark service, similar to http://www.bunny1.org/.

Create or edit commands in [./config.kdl](./config.kdl) using the [KDL](https://kdl.dev/) config language.

## Installation

### On Debian-based systems

```sh
# Add the repo's GPG key
curl -L https://packagecloud.io/sargunv/public/gpgkey | sudo apt-key add -

# Add the repo to your apt sources
echo 'deb https://packagecloud.io/sargunv/public/any/ any main' | sudo tee -a /etc/apt/sources.list

# Update your sources and install
sudo apt update && sudo apt install svurl-service
```

Alternatively, download the `.deb` package for your system from [Github Releases](https://github.com/sargunv/svurl-service/releases/latest) and install it with `dpkg`.
