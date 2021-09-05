# Log Severity Levels Matter: A multivocal mapping  \[Database\]
> DOI: ?

* [Pre-print](?)


## Peer-reviewed literature
> [Bibtex of the library](all-papers-final.bib)

Search String:
```
("log level" OR "log severity" 
 OR 
"logging level" OR "logging severity"
OR 
("severity level" AND (logging OR log))
 ```
### Stage 1
1. [Query result: 291 studies](peer-reviewed-literature/step1-studies-query.csv)
2. [Title reading: 24 studies](peer-reviewed-literature/step2-studies-title-reading.csv)
3. [Abstract reading: 14 studies](peer-reviewed-literature/step3-studies-abstract-reading.csv)
4. [Full reading: 9 studies](peer-reviewed-literature/step4-studies-full-reading.csv)

### Stage 2
1. [Snowballing result: 18 studies](peer-reviewed-literature/stage2-full-snowballing.csv)

### Final Set
[27 studies](peer-reviewed-literature/studies-final-set.csv)


## Logging libraries

1. PYLP Index
    - [Print May 2021](logging-libraries/prints/PYPL-index-May-2021.pdf)
    - Dataset

2. Google Search prints:

    - Python: [Result](logging-libraries/prints/logging-library-Python-Google-Search.pdf)
    - Java: [Result](logging-libraries/prints/logging-library-Java-Google-Search.pdf)
    - JavaScript: [Result](logging-libraries/prints/logging-library-JavaScript-Google-Search.pdf)
    - C#: [Result](logging-libraries/prints/logging-library-C#-Google-Search.pdf)
    - C: [Result](logging-libraries/prints/logging-library-C-Google-Search.pdf)
    - C++: [Result](logging-libraries/prints/logging-library-C++-Google-Search.pdf)
    - PHP: [Result](logging-libraries/prints/logging-library-php-Google-Search.pdf)
    - R: [Result](logging-libraries/prints/logging-library-R-Google-Search.pdf)
    - Objective-C: [Result](logging-libraries/prints/logging-library-ObjectiveC-Google-Search.pdf)
    - TypeScript: [Result](logging-libraries/prints/logging-library-Typescript-Google-Search.pdf)
    - Swift: [Result](logging-libraries/prints/logging-library-Swift-Google-Search.pdf)
    - Kotlin: [Result](logging-libraries/prints/logging-library-Kotlin-Google-Search.pdf)
    - Matlab: [Result](logging-libraries/prints/logging-library-Matlab-Google-Search.pdf)
    - Go: [Result](logging-libraries/prints/logging-library-php-Golang-Search.pdf)
    - Rust: [Result](logging-libraries/prints/logging-library-Rust-Google-Search.pdf)
    - VBA: [Result](logging-libraries/prints/logging-library-VBA-Google-Search.pdf)
    - Ruby: [Result](logging-libraries/prints/logging-library-Ruby-Golang-Search.pdf)


|   ID |                      Library | Launch | Total | FINEST | VERBOSE | FINER | TRACE | DEBUG |  FINE | CONFIG |  INFO | NOTICE |  WARN | ERROR | SEVERE | FAULT | CRITICAL |  ALERT |  FATAL | EMERG. | OTHERS                  |
|-----:|-----------------------------:|-------:|:-----:|:------:|:-------:|:-----:|:-----:|:-----:|:-----:|:------:|:-----:|:------:|:-----:|:-----:|:------:|:-----:|:--------:|:------:|:------:|:------:|-------------------------|
| L01  |                  Gogoel Glog |   2015 |   4   |        |         |       |       |       |       |        |   0   |        |   1   |   2   |        |       |          |        |    3   |        |                         |
| L02  |                  Golang glog |   2013 |   4   |        |         |       |       |       |       |        |   0   |        |   1   |   2   |        |       |          |        |    3   |        |                         |
| L03  |                    OSLogging | ?      |   5   |        |         |       |       | - [x] |       |        | - [x] | - [x]  |       | - [x] |        | - [x] |          |        |        |        | FAULT                   |
| L04  |                    Rust Lang |   2014 |   5   |        |         |       |   5   |   4   |       |        |   3   |        |   2   |   1   |        |       |          |        |        |        | OFF                     |
| L05  |                      Logback |   2006 |   5   |        |         |       |  5000 | 10000 |       |        | 20000 |        | 30000 | 40000 |        |       |          |        |        |        |                         |
| L06  |                        SLF4J |   2006 |   5   |        |         |       |     0 |    10 |       |        |    20 |        |    30 |    40 |        |       |          |        |        |        |                         |
| L07  |                  Ruby Logger |   2003 |   5   |        |         |       |       |     0 |       |        |     1 |        |     2 |     3 |        |       |          |        |      4 |        |                         |
| L08  |                     LogLevel |   2013 |   5   |        |         |       |     0 |     1 |       |        |     2 |        |     3 |     4 |        |       |          |        |        |        |                         |
| L09  |                    JS-logger |   2012 |   5   |        |         |       |     1 |     2 |       |        |     3 |        |     5 |     8 |        |       |          |        |        |        | TIME                    |
| L10  |              CocoaLumberjack |   2010 |   5   |        |       4 |       |       |     3 |       |        |     2 |        |     1 |     0 |        |       |          |        |        |        |                         |
| L11  |  MicroUtils / Kotlin-logging |   2016 |   5   |        |         |       | - [x] | - [x] |       |        | - [x] |        | - [x] | - [x] |        |       |          |        |        |        |                         |
| L12  |                 SwiftyBeaver |   2015 |   5   |        |       0 |       |       |     1 |       |        |     2 |        |     3 |     4 |        |       |          |        |        |        |                         |
| L13  |                   Log4J (v1) |   1999 |   6   |        |         |       |  600  |  500  |       |        |  400  |        |  300  |  200  |        |       |          |        |   100  |        | ALL, OFF                |
| L13  |                   Log4J (v2) |   2014 |   6   |        |         |       |  5000 | 10000 |       |        | 20000 |        | 30000 | 40000 |        |       |          |        |  50000 |        |                         |
| L14  |              Commons Logging |   2002 |   6   |        |         |       | - [x] | - [x] |       |        | - [x] |        | - [x] | - [x] |        |       |          |        |  - [x] |        |                         |
| L15  |                       Bunyan |   2011 |   6   |        |         |       |   10  |   20  |       |        |   30  |        |   40  |   50  |        |       |          |        |   60   |        |                         |
| L16  |                         NLog |   2006 |   6   |        |         |       |   0   |   1   |       |        |   2   |        |   3   |   4   |        |       |          |        |    5   |        |                         |
| L17  |                  Python Lang |   2002 |   6   |        |         |       |       |   10  |       |        |   20  |        |   30  |   40  |        |       |    50    |        |   50   |        | NOTSET                  |
| L18  | Microsoft.Extensions.Logging |   2015 |   6   |        |         |       |     0 |     1 |       |        |     2 |        |     3 |     4 |        |       |        5 |        |        |        |                         |
| L19  |                      Serilog |   2013 |   6   |        |       0 |       |       |     1 |       |        |     2 |        |     3 |     4 |        |       |          |        |      5 |        |                         |
| L20  |                      Log4PHP |   2009 |   6   |        |         |       |   500 | 10000 |       |        | 20000 |        | 30000 | 40000 |        |       |          |        |  50000 |        |                         |
| L21  |                       PinoJS |   2016 |   6   |        |         |       |    10 |    20 |       |        |    30 |        |   40  |    50 |        |       |          |        |   60   |        |                         |
| L22  |                        Log.c |   2017 |   6   |        |         |       |     0 |     1 |       |        |     2 |        |     3 |     4 |        |       |          |        |      5 |        |                         |
| L23  |                     C-logger |   2016 |   6   |        |         |       |     0 |     1 |       |        |     2 |        |     3 |     4 |        |       |          |        |      5 |        |                         |
| L24  |                         Zlog |   2011 |   6   |        |         |       |       |    20 |       |        |    40 |     60 |    80 |   100 |        |       |          |        |    120 |        |                         |
| L25  |                   Go-logging |   2013 |   6   |        |         |       |       |     5 |       |        |     4 |      3 |     2 |     1 |        |       |        0 |        |        |        |                         |
| L26  |                        Log4m |  ~2012 |   6   |        |         |       |     1 |     2 |       |        |     3 |        |     4 |     5 |        |       |          |        |      6 |        | ALL, OFF                |
| L27  |                   Loguru C++ |   2015 |   6   |        |         |       |       | 6*    |       |        |     5 |        |     4 |     3 |        |       |          |      1 |      2 |        | Verbosity_1=6           |
| L28  |                       Spdlog |   2014 |   6   |        |         |       |     0 |     1 |       |        |     2 |        |     3 |     4 |        |       |        5 |        |        |        |                         |
| L29  |            Java Util Logging |   2002 |   7   |   300  |         |  400  |       |       |  500  |   700  |  800  |        |  900  |       |  1000  |       |          |        |        |        | ALL, OFF, CONFIG        |
| L30  |                       Logrus |   2013 |   7   |        |         |       |     6 |     5 |       |        |     4 |        |     3 |     2 |        |       |          |        |      1 |        |                         |
| L31  |                  Uber-go/zap |   2016 |   7   |        |         |       |       |     0 |       |        |     1 |        |     2 |     3 |        |       |          |        |        |        |                         |
| L32  |                   Bolterauer |   2008 |   7   |      7 |         |     6 |       | 1*    |     5 |        |     4 |        |     3 |       |        |       |          |        |      2 |        | Basic=Debug             |
| L33  |                    Swift-log |   2018 |   7   |        |         |       |     0 |     1 |       |        |     2 |      3 |     4 |     5 |        |       |        6 |        |        |        |                         |
| L34  |                Loguru Python |   2017 |   7   |        |         |       |     5 |    10 |       |        |    20 |        |    30 |    40 |        |       |       50 |        |        |        | SUCCESS=25              |
| L35  |              Syslog Protocol |   1998 |   8   |        |         |       |       |   7   |       |        |   6   |    5   |   4   |   3   |        |       |     2    |    1   |        |    0   |                         |
| L36a |               PHP (on Linux) |  ~2001 |   8   |        |         |       |       |   7   |       |        |   6   |    5   |   4   |   3   |        |       |     2    |    1   |        |    0   |                         |
| L36b |             PHP (on Windows) |  ~2001 |   8   |        |         |       |       |   6   |       |        |   6   |    6   |   5   |   1   |        |       |     1    |    1   |        |        |                         |
| L37  |                      Monolog |   2011 |   8   |        |         |       |       |   100 |       |        |   200 |    250 |   300 |   400 |        |       |      500 |    550 |    600 |        |                         |
| L38  |                      Winston |   2011 |   8   |        |         |       |       |     7 |       |        |   6   |      5 |   4   |     3 |        |       |     2    |    1   |        |    0   |                         |
| L39  |                        Log4C |  2002? |   9   |        |         |       |   800 |   700 |       |        |   600 |    500 |   400 |   300 |        |       |      200 |   100  |    0   |        |                         |
| L40  |                      Log4Net |   2004 |   15  |  10000 |  10000  | 20000 | 20000 | 30000 | 30000 |        | 40000 |  50000 | 60000 | 70000 |  80000 |       |   90000  | 100000 | 110000 | 120000 | ALL, OFF, LOG4NET_DEBUG |


3. [Found libraries](logging-libraries/libraries-criteria.csv)

## Practitioners' vision

Search String:
```
"log levels" is:question
 ```

1. StackOverflow Hits
    - [Page 1](practitioners-view/prints/Highest-voted-posts-containing_log-levels-is-question_Stack-Overflow-page-1.pdf)
    - [Page 2](practitioners-view/prints/Highest-voted-posts-containing_log-levels-is-question_Stack-Overflow-page-2.pdf)
    - [Page 3](practitioners-view/prints/Highest-voted-posts-containing_log-levels-is-question_Stack-Overflow-page-3.pdf)
    - [Page 4](practitioners-view/prints/Highest-voted-posts-containing_log-levels-is-question_Stack-Overflow-page-4.pdf)