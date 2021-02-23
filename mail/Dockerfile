FROM debian
RUN apt-get update && apt-get install -y exim4 dovecot-imapd dovecot-pop3d
CMD update-exim4.conf && service exim4 start && service dovecot start && tail -f /dev/null
EXPOSE 25 110 143 465 993 995
