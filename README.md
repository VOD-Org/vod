# vod
Welcome to the new VOD project, 100% legally, including copyrighted materials, is distributed via BitTorrent, and uploaded to the community servers.

# How to contribute?

It's easy. Please put your own content in shows.json if it's show, or in movies.json if it's movie, and open your own pull request.

## shows.json or movies.json (at the last line)
```
{
  "name":"YOUR_OWN_NAME",
  "magnet":"TORRENT_MAGNET",
  "server":{
    "ftp_hostname":"YOUR_OWN_FTP_SERVER",
    "ftp_username":"YOUR_OWN_USERNAME",
    "ftp_password":"YOUR_OWN_PASSWORD_ENCODED_TO_BASE64",
    "ftp_port":"21",
    "ftp_directory":"YOUR_OWN_DIRECTORY",
    "domain_hosted":"YOUR_OWN_DOMAIN"
  }
}
```
An playlist index.m3u8 will be generated at https://vod-org.github.io/vod/index.m3u8 daily.
