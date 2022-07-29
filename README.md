### Nick Alteen

[![Linkedin Badge](https://img.shields.io/badge/linkedin-ncalteen-blue)](https://www.linkedin.com/in/ncalteen)
[![Gmail Badge](https://img.shields.io/badge/gmail-ncalteen%40gmail.com-red)](mailto:ncalteen@gmail.com)

```python
#!/usr/bin/python
# -*- coding: utf-8 -*-
import datetime


class Nick:

    def __init__(self):
        self.first_name = "Nick"
        self.last_name = "Alteen"
        self.pronouns = "he/him"
        self.email = "ncalteen@gmail.com"
        self.jobs = [
            {
                "company": "Google",
                "organization": "Consumer Payments and Next Billion Users (NBU)",
                "team": "Payments DevRel",
                "role": "Technical Writer",
                "start_date": datetime.date(year=2022, month=5, day=30),
                "end_date": None,
            },
            {
                "company": "Amazon Web Services (AWS)",
                "organization": "AWS Training & Certification",
                "team": "Dedicated Cloud Training",
                "role": "Manager, Lab Development Engineering",
                "start_date": datetime.date(year=2018, month=1, day=1),
                "end_date": datetime.date(year=2022, month=5, day=30),
            }
        ]

    def hello_world(self):
        print("I'm Nick! I work at Google building documentation, code examples, and other cool stuff for Google Pay and Google Wallet.")
        print("In my spare time, I like to build things that get people interested in the cloud.")

    def collaborate(self, interested: bool):
        if interested:
            print("I love collaboration!")
            print("I have some personal projects I'd love to get feedback and input on. Feel free to check them out :)")
            print("If you have projects that you're passionate about, let me know! I'd love help if I can.")

    def contact_me(self):
        print(f"Feel free to send me a message at {self.email}")

me = Nick()
me.hello_world()
```

#### Toolbox

I have some level of knowledge between *"comfortable sharing with experienced developers"* and *"this is bad and I should feel bad"* for each of the following.

##### Process

- CI/CD
- Configuration Management
- DevOps
- Infrastructure as Code
- Serverless
- Source Control

##### Platform

- AWS
- Chef
- GCP
- RedHat
- Unity
- Windows

##### Programming

- Bash
- C#
- JavaScript
- Python
- Ruby
