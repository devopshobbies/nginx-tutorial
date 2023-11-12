# Nginx Tutorial - Session 08: Logging 01

Welcome to Session 08 of the Nginx Tutorial, where we'll dive into the world of logging in Nginx. We'll explore different kinds of logging, including access logs and error logs, and we'll provide a practical demonstration of working with error logs.

## Table of Contents

1. [Different Kinds of Logging](#different-kinds-of-logging)
2. [Access Log](#access-log)
3. [Error Log](#error-log)
4. [Demo Error Log](#demo-error-log)

## Different Kinds of Logging

Logging is essential for monitoring, debugging, and analyzing web server activities. Nginx offers various types of logs that capture different aspects of its operation.

## Access Log

The access log records information about every HTTP request received by the Nginx server. It includes details such as the client's IP address, requested URL, response status, and more.

## Error Log

The error log captures information about issues and errors that occur within the Nginx server. It's a valuable resource for diagnosing problems and troubleshooting.

| Log Level | Description                                   | Value in Nginx |
|-----------|-----------------------------------------------|----------------|
| Debug     | Debugging messages that are not useful most of the time.  | debug |
| Info      | Informational messages that might be good to know.         | info |
| Notice    | Something normal but significant happened and it should be noted. | notice |
| Warn      | Something unexpected happened, however it’s not a cause for concern. | warn |
| Error     | Something failed.                            | error |
| Crit      | A critical condition occurred.               | crit |
| Alert     | Immediate action is required.               | alert |
| Emerg     | The system is unusable.                      | emerg |

## Conclusion

Logging is a crucial part of web server administration, and understanding how to utilize and analyze logs is essential for maintaining a healthy and reliable web infrastructure. In the subsequent sessions of this tutorial, we'll continue exploring various aspects of Nginx and web server management.

We hope you find this session informative and practical. Stay tuned for more sessions in this Nginx tutorial series.

## Useful Links

Here are some useful links for further reading and reference:

- [Nginx Logging and Log Rotation](https://docs.nginx.com/nginx/admin-guide/monitoring/logging/): Official documentation on Nginx logging and log rotation.
