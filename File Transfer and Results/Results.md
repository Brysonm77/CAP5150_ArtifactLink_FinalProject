# Results found throughout the project

``` # All results use the following format HH:MM:SS. any milisecond is automatically rounded up to the nearest whole second.
```

## Complexity
* Configuration of first client and server break down. Includes debugging and completion times
  * Conf = 02:59:41
    * OS installation = 00:11:37
    *  VM creation/Networking (NOT INCLUDING OS INSTALL) = 00:36:18
    *  WG server setup = 00:48:27
    *  WG client setup = 00:34:10
    *  OpenSSH + test files (server) + allowed users (server) = 00:49:09   
  * Errors/Debugging = 03:22:24
    * Server debug and rebuild 01:02:51
    * enp0s3 debugging (not showing) = 00:38:44
    * WG key error = 00:57:10
    * SCP failure = 00:33:59
    * UFW blocking all incoming traffic = 00:09:40
   
* Complexity times for WG and OpenSSH deployment
  * Client 2:
    * Deployment/Networking (DOES NOT INCLUDE OS INSTALLATION): 58:20
    * OS installation: 00:11:16
    * WG setup and connection = 00:22:53
    * OpenSSH setup and connection = 00:01:34 
  * Client 3:
    * Deployment/Networking (DOES NOT INCLUDE OS INSTALLATION): 00:47:49
    * OS installation = 00:12:00
    * WG setup and connection = 00:15:30
    * OpenSSH setup and connection = 00:00:16
  * Client 4:
    * Deployment/Networking (DOES NOT INCLUDE OS INSTALLATION) = 00:28:01
    * OS installation = 00:13:05
    * WG setup and installation = 00:13:05
    * OpenSSH setup and installation = 00:00:13

## File Transfers
* Client 1:
  * WG
    * 10 Mb = 100% | 34.6 Mb/s | 00:00:00
    * 1 Gb = 100% | 42.4 Mb/s | 00:00:24
    * 5 Gb = 100% | 43.3 Mb/s | 00:01:58
    * 10 Gb = 100% | 39.7 Mb/s | 00:04:18 
  * OpenSSH
    * 10 Mb = 100% | 91.7 Mb/s | 00:00:00
    * 1 Gb = 100% | 96.8 Mb/s | 00:00:10
    * 5 Gb = 100% | 77.9 Mb/s | 00:01:05
    * 10 Gb = 100%  | 82.2 Mb/s | 00:02:04 
* Client 2:
  * WG
    * 10 Mb = 100% | 30.4 Mb/s | 00:00:00
    * 1 Gb = 100% | 36.5 Mb/s | 00:00:28
    * 5 Gb = 100% | 34.9 Mb/s | 00:02: 26
    * 10 Gb = 100% | 35.5 Mb/ | 00:04:48 
  * OpenSSH
    * 10 Mb = 100% | 76.3 Mb/s | 00:00:00
    * 1 Gb = 100% | 76.7 Mb/s | 00:00:13
    * 5 Gb = 100% | 80.9 Mb/s | 00:01:03
    * 10 Gb = 1005 | 73.4 Mb/s | 00:02:19  
* Client 3:
  * WG
    * 10 Mb = 100% | 39.1 Mb/s | 00:00:00
    * 1 Gb = 100% | 34.4 Mb/s | 00:00:29
    * 5 Gb = 100% | 33.9 Mb/s | 00:02:31
    * 10 Gb = 100% | 33.3 Mb/s | 00:05:07 
  * OpenSSH
    * 10 Mg = 100% | 78.7 Mb/s | 00:00:00
    * 1 Gb = 100% | 84.2 Mb/s | 00:00:12
    * 5 Gb = 100% | 80.3 Mb/s | 00:01:03
    * 10 Gb = 100% | 74.5 Mb/s | 00:02:17 
* Client 4:
  * WG
    * 10 Mb = 100% | 31.6 Mb/s | 00:00:00
    * 1 Gb = 100% | 35.9 Mb/s | 00:00:28
    * 5 Gb = 100% | 34.8 Mb/s | 00:02:26
    * 10 Gb = 100% | 35.5 Mb/s | 00:04:48 
  * OpenSSH
    * 10 Mb = 100% | 80.0 Mb/s | 00:00:00
    * 1 Gb = 100% | 76.2 Mb/s | 00:00:13
    * 5 Gb = 100% | 78.0 Mb/s | 00:01:05
    * 10 Gb = 100% | 74.4 Mb/s | 00:02:17 
