## Good Morning
Welcome to doctest3

## Version 1
Here is version 1

```
java -Dlog4j2.configurationFile=log4j2-daemon.xml ‑Dsndml.logFolder=<path_to_log_directory> \
  ‑Dsndml.logPrefix=<name_of_agent> -jar <path_to_jar> -p <path_to_connection_profile> --scan
```
  
## Version 2
Here is version 2

<pre class="highlight">
java -Dlog4j2.configurationFile=log4j2-daemon.xml \
  ‑Dsndml.logFolder=<small><var>&lt;path_to_log_directory&gt;</var></small> \
  ‑Dsndml.logPrefix=<small><var>&lt;name_of_agent&gt;</var></small> \
  -jar <small><var>&lt;path_to_jar&gt;</var></small> -p <small><var>&lt;path_to_connection_profile&gt;</var></small> --scan
</pre>


## Version 3
Here is version 2

<pre class="highlight">
java -Dlog4j2.configurationFile=log4j2-daemon.xml \
  ‑Dsndml.logFolder=<var>log-directory</var> ‑Dsndml.logPrefix=<var>agent-name</var> \
  -jar <var>jar-file</var> -p <var>connection-profile</var> --scan
</pre>

