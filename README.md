# php-opentimestamps
This is an attempt of a php port of https://github.com/opentimestamps/javascript-opentimestamps

# Install
Dockerfile/
<pre>
ADD opentimestamps /var/www/opentimestamps
RUN cd /var/www/opentimestamps; git clone --recursive https://github.com/insidenothing/php-opentimestamps.git
</pre>

# Command Line

# From code
## Stamp
Create timestamp of a file with the aid of a remote calendar.
<pre>
include_once('/var/www/opentimestamps/required.php');



</pre>
