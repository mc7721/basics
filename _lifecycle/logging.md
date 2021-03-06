---
layout: stop
class:
  - stop
rel:
  - /rels/stop  
properties:
  name: API Logging
  header: <p>Logging has always been in the background of other stops along the API journey, most notably the API management layer. However increasingly I am recommending pulling logging out of API management, and making it a first-class citizen, ensuring that the logging of all systems across the API transit process are aggregated, and accessible, allowing them to be accessed alongside other resources. Almost every stop in this basics of an API transit series will have its own logging layer, providing an opportunity to better understand each stop, but also side by side as part of the bigger picture.</p>There are some clear leaders when it comes to logging, searching, and analyzing large volumes of data generated across API operations. This is one area you should not be reinventing the wheel in, and you need to be leveraging the experience of the open source tooling providers, as well as the cloud providers who have emerged across the landscape. Here is a snapshot of a few providers who will help you make logging a first class citizen in your API operations.</p>
  footer: <p>I recommend cracking open logging from EVERY layer, and shipping them into a central system like Elastic for making them accessible. While each stop along the API journey will come with its own logging and analysis solutions, depending on the services and tooling used, logs should also be shipped as part of a central system for analysis at the bigger picture level. Each stop along the API transit will have its own tooling and service, which will most likely come with its own logging and analysis services. Use these solutions. However, don't stop there, and consider the benefits from looking at log data side by side, and what the big picture might hold.</p><p>Logging will significantly overlap with the security stop along the API journey. The more logging you are doing, and the more accessible these logs are, the more comprehensive your API security will become. You'll find this becomes true at other stops, and you will be able to better discovery, testing, define, and deliver in other ways, with a more comprehensive logging strategy. Remember, logging isn't just about providing a logging layer, it is also about having APIs for your logging, providing a programmatic layer to understand how things are working, or not.</p>
  image: https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-logging-2.png
  links:
    - title: Elastic Stack
      url: https://www.elastic.co/products
      description: Formerly known as the Elk Stack, the evolved approach to logging, search, and analysis out of Elastic. I recommend incorporating it into all aspects of operations, and deploying APIs to make them first class citizens.
    - title: Logmatic
      url: https://logmatic.io/
      description: Whatever the language or stack, staging or production, front or back, Logmatic.io centralizes all your logs and metrics right into your browser.  
    - title: Nagios
      url: https://www.nagios.org/
      description: Nagios Log Server greatly simplifies the process of searching your log data. Set up alerts to notify you when potential threats arise, or simply query your log data to quickly audit any system.
    - title: Google Stackdriver
      url: https://cloud.google.com/stackdriver/
      description: Google Stackdriver provides powerful monitoring, logging, and diagnostics.
    - title: AWS CloudWatch
      url: https://aws.amazon.com/cloudwatch/
      description: Amazon CloudWatch is a monitoring service for AWS cloud resources and the applications you run on AWS.                     
  color: 27AE60    
links:
  - rel:
      - self
    href: /lifecycle/requests/
  - rel:
      - previous
    href: /lifecycle/management/   
  - rel:
      - next
    href: /lifecycle/dns/            
---
