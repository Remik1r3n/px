# px
Stupid Bash Script to set proxy.

## Purpose
The script aims to establish a consistent proxy environment on systems, primarily targeting users in Mainland China who heavily rely on proxies for internet access.

Proxy configurations often involve setting environment variables like HTTP_PROXY. However, these variables are case-sensitive, leading to inconsistencies. Certain programs, like wget, solely recognize lowercase variables, while others, like curl, only acknowledge uppercase ones.

## Solution
The script addresses this issue by comprehensively setting a wide range of proxy-related environment variables in both uppercase and lowercase forms. This guarantees that most programs can effectively identify the proxy settings regardless of their case sensitivity.

## How to use
For one-time use, just copy-paste into your terminal and you should have px and unpx command.

You can also add it to your bashrc or something.
