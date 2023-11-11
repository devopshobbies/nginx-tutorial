# Nginx Tutorial - Session 09: Logging 02

Welcome to Session 09 of the Nginx Tutorial, where we'll continue our exploration of logging in Nginx. This session will focus on access logs, custom access logging, and practical demonstrations for access logging at different levels within the Nginx configuration.

## Table of Contents

1. [Access Log](#access-log)
2. [Custom Access Logging](#custom-access-logging)
3. [Demo Access Logging](#demo-access-logging)

## Access Log

Access logs in Nginx record detailed information about client requests to the server. These logs can provide insights into the traffic patterns, client behaviors, and more.

## Custom Access Logging

Customizing access logs allows for tailoring log formats to collect specific data. This can help in better analysis and monitoring of the server's traffic.

## Demo Access Logging

In this section, we'll conduct a demonstration of access logging at different levels within the Nginx configuration.

### Server Level

We'll demonstrate how to configure access logging at the server level, capturing data for all requests made to the server.

### HTTP Level

Logging at the HTTP level provides an insight into the requests processed by the HTTP server block, offering more granular information.

### Location Level

At the location level, we'll show how to log access specific to different sections of the server configuration, allowing for detailed tracking of specific URLs or paths.

## Conclusion

Understanding access logs and implementing custom access logging at various levels within the Nginx configuration can provide valuable insights into the server's traffic and user behavior. This knowledge is crucial for effective monitoring and optimization of the server.

We hope you find this session informative and practical. Stay tuned for more sessions in this Nginx tutorial series.

```json
"Time":"$time_local", #TimeOfRequest
"Client_IP":"$remote_addr", #ClientIPAddress
"Client_Port":"$remote_port", #ClientPort
"Scheme":"$scheme", #Scheme
"SSL_Protocol":"$ssl_protocol", #SSLProtocol
"SSL_Cipher":"$ssl_cipher", #SSLCipher
"Server_Name":"$server_name", #ServerName
"Server_Port":"$server_port", #ServerPort
"Server_Protocol":"$server_protocol", #ServerProtocol
"Host":"$host", #Host
"UserAgent":"$http_user_agent", #UserAgent
"Response_Status":"$status", #ResponseStatus
"Request_Path":"$uri", #RequestPath
"Request_QueryString":"$query_string", #RequestQueryString
"Request_FullPath":"$request_uri", #FullRequest_PathQueryString
"Request_Method":"$request_method", #Request_Method
"Request_Length":"$request_length", #Request_Length
"ContentType":"$sent_http_content_type", #ContentType
"Referrer":"$http_referer", #Referrer
"RequestTotalTime":"$request_time", #TotalRequestTime
"ByteSent_ToClient":"$bytes_sent", #ByteSentClient
"BodyBytesSent_ToClient":"$body_bytes_sent", #BodyByteSentClient
"Upstream_IPAddress":"$upstream_addr", #UPstreamIP
"Upstream_Status":"$upstream_status", #UPstreamResponseStatus
"Upstream_Response_Lenght":"$upstream_response_length", #UpstreamResponseLenght
"Upstream_Connect_Time":"$upstream_connect_time", #UpstreamConnectTime
"Upstream_Handover_Time":"$upstream_header_time", #UpstreamHnadoverTime
"Upstream_Response_Time":"$upstream_response_time" #UpstreamResponseTime
```

## Useful Links

Here are some useful links for further reading and reference:

- [Nginx Access Log](https://nginx.org/en/docs/http/ngx_http_log_module.html): Official documentation for Nginx access log module.
- [Custom Logging Formats](https://nginx.org/en/docs/http/ngx_http_log_module.html#log_format): Information on defining custom log formats in Nginx.