FROM fauria/vsftpd

COPY vsftpd.conf /etc/vsftpd/vsftpd.conf

RUN mkdir -p /srv/ftp /srv/ftp/ftp \
  chmod 755 /srv/ftp/ftp \
  chown ftp:ftp /srv/ftp/ftp
