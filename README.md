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
                "company": "GitHub",
                "organization": "Partner and Expert Services",
                "team": "Expert Services Delivery",
                "role": "Senior DevOps Engineer",
                "start_date": datetime.date(year=2023, month=1, day=10),
                "end_date": None,
            },
            {
                "company": "Google",
                "organization": "Consumer Payments and Next Billion Users (NBU)",
                "team": "Google Pay and Google Wallet",
                "role": "Developer Relations Engineer",
                "start_date": datetime.date(year=2022, month=5, day=30),
                "end_date": datetime.date(year=2023, month=1, day=6),
            },
            {
                "company": "Amazon Web Services (AWS)",
                "organization": "AWS Training & Certification",
                "team": "Dedicated Cloud Training",
                "role": "SDM, Lab Development & Engineering",
                "start_date": datetime.date(year=2020, month=4, day=1),
                "end_date": datetime.date(year=2022, month=5, day=30),
            },
            {
                "company": "Amazon Web Services (AWS)",
                "organization": "AWS Training & Certification",
                "team": "Dedicated Cloud Training",
                "role": "SDM, Lab Development & Engineering",
                "start_date": datetime.date(year=2018, month=1, day=1),
                "end_date": datetime.date(year=2020, month=4, day=1),
            },
            {
                "company": "Amazon Web Services (AWS)",
                "organization": "AWS Support",
                "team": "Deployment",
                "role": "Cloud Support Engineer II",
                "start_date": datetime.date(year=2016, month=9, day=6),
                "end_date": datetime.date(year=2020, month=4, day=1),
            }
        ]

    def hello_world(self):
        print("I'm Nick! I work at GitHub :)")
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

I have some level of knowledge between _"comfortable educating experienced developers"_ and _"this is bad and I should feel bad"_ for each of the following.

| Process                      | Platform | Programming |
|------------------------------|----------|-------------|
| CI/CD                        | AWS      | Bash        |
| Configuration Management     | Chef     | C#          |
| DevOps                       | GCP      | JavaScript  |
| Infrastructure as Code (IaC) | RedHat   | Python      |
| Serverless                   | Unity    | Ruby        |
| Source Control               | Windows  | TypeScript  |
