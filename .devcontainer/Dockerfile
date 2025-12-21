FROM fedora:latest

# Update and install packages
RUN dnf -y makecache && \
    dnf -y install \
        axel \
        git \
        wget \
        ripgrep \
        unzip \
        openssh-server \
        sudo \
        gcc && \
      rm -rf /var/cache/dnf \
      dnf clean all
echo "Welcome"

