# SimpleHTTPServerWithUpload
Simple HTTP Server With Upload written in Python.<br>
This script works with version 3.6.<br>
Earlier versions will cause runtime errors.<br><br>
This is a modified version from the original source.<br>
https://gist.github.com/UniIsland/3346170<br><br>
I have added icons for directory and videos.<br>
Pictures (BMP, GIF, JPG, PNG) will display thumbnails.<br><br>
Directory listing is in a table format with file sizes and creation dates.<br><br>
This script also supports IP Address & Port binding.<br><br>
Change 'SimpleHTTPServerWithUpload.sh' to suit your requirements.


## To post files to this server use:
`curl -X POST -F file=@<path-to-file> http://<host-ip>:8000`
