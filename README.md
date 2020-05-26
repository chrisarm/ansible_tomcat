# Ansible Role to configure Tomcat server on CentOS 8

This role only installs Apache Tomcat with CentOS 8 as the host server with and Apache as the proxy.

## Role Variables
| Key              | Value                                                               |
| :---             | :---                                                                |
| `version`        | Version of Tomcat to install. (9.0.35)                              |
| `download_url`   | URL to download Tomcat from Apache                                  |
| `basepath`       | Location to install base Apache Tomcat files (/var/lib)             |
| `install_path`   | Location that most distributions use for Tomcat  (/var/lib/tomcat)  |
| `tomcat_user`    | User for the Tomcat service (tomcat)                                |
| `tomcat_group`   | Group for the Tomcat service (tomcat)                               |
| `tomcat_admin`   | User for the Tomcat Manager App (Admin)                             |
| `tomcat_password`| Password for the Tomcat Manager App                                 |

### IMPORTANT!
Make sure to change the tomcat password

## License

GNU AGPLv3.0
