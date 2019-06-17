# Nextcloud

  mkdir ~/data
  mkdir ~/data/nextcloud

  sudo chmod -R 770 data

  docker run -d -v nextcloud:/var/www/html nextcloud
