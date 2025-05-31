FROM nextcloud:latest

RUN apt-get update && \
    apt-get install -y --no-install-recommends \
      ffmpeg \
      libva2 \
      vainfo \
      intel-media-va-driver \
      smbclient \
    && apt-get clean && rm -rf /var/lib/apt/lists/*

RUN ffmpeg -version && vainfo || true
