---
title: Assignment 1
subtitle: Computer performance, reliability, and scalability calculation
author: Michael Loos
---

## 1.2 

#### a. Data Sizes

| Data Item                                  | Size per Item | 
|--------------------------------------------|--------------:|
| 128 character message.                     | 128 Bytes     |
| 1024x768 PNG image                         | 3.15 MB          |
| 1024x768 RAW image                         | 1.57 MB       | 
| HD (1080p) HEVC Video (15 minutes)         | 450 MB          |
| HD (1080p) Uncompressed Video (15 minutes) | 1105 MB       |
| 4K UHD HEVC Video (15 minutes)             | 2539 MB       |
| 4k UHD Uncompressed Video (15 minutes)     | 5182 MB       |
| Human Genome (Uncompressed)                | 1.5 GB        |

#### b. Scaling

|                                           | Size        | # HD  | 
|-------------------------------------------|------------:|------:|
| Daily Twitter Tweets (Uncompressed)       | 0.1746 TB   |   1   |
| Daily Twitter Tweets (Snappy Compressed)  | 0.0873 TB   |   1   |
| Daily Instagram Photos                    | 675.9167 TB |  17   |
| Daily YouTube Videos                      | 9104.9194 TB|  304  |
| Yearly Twitter Tweets (Uncompressed)      | 63.7374 TB  |   7   |
| Yearly Twitter Tweets (Snappy Compressed) | 31.8687 TB  |   4   |
| Yearly Instagram Photos                   | 246709.6 TB | 24671 |
| Yearly YouTube Videos                     | 3323295.6 TB| 332330|

#### c. Reliability
|                                    | # HD | # Failures |
|------------------------------------|-----:|-----------:|
| Twitter Tweets (Uncompressed)      |  7   |    None    |
| Twitter Tweets (Snappy Compressed) |  4   |    None    |
| Instagram Photos                   |24671 |    178     |
| YouTube Videos                     |332330|    3357    |

#### d. Latency

|                           | One Way Latency      |
|---------------------------|---------------------:|
| Los Angeles to Amsterdam  | 134 ms               |
| Low Earth Orbit Satellite | 40 ms                |
| Geostationary Satellite   | 600 ms               |
| Earth to the Moon         | 2500 ms              |
| Earth to Mars             | 20 minutes           | 
