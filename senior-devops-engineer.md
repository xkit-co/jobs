# Senior DevOps Engineer

## About Xkit

Software is eating the world, and that software is going to be connected together. [Xkit](https://xkit.co) is helping bring that future to fruition by building tools that make it easier for developers to add integrations to their apps.

We're a small, fully remote team. We pride ourselves on being able to "punch above our weight" - our ability to build products better and faster than teams that are orders of magnitude larger. We are first principles thinkers in everything from technical design to how we run engineering processes. Everyone on the team is capable of and prefers to operate with high levels of autonomy, but we often collaborate at the design level to find the best solutions for our customers.

We focus obsessively on the holistic customer experience, trying to figure out how best we can help the customer (even when that means teaching them the best way to do it themselves rather than selling them something). We cut scope aggressively, striving to deliver only what is absolutely needed and nothing superfluous. We take delight in our customers' delights - the little things that make a product a pleasure to use - which we don't consider superfluous, but rather essential to the product experience.

We try to operate by principles rather than by processes or rules.

Examples of how these attitudes manifest in our day-to-day lives include:
- No standups: no added value for our current team size
- Ignoring code coverage: tests should make our and our customers' lives better; we're after practical bug prevention, not a magic number
- One command deploys: changing code in production should be easy to do and easy to do right

We expect all members of our team to be:
- focused: on the customer and on our overarching business goals
- skilled: highly skilled in their field; good critical thinkers and fast learners outside of it
- workers: action-oriented, finishers, willing to contribute outside their area of expertise

## About the Product

Xkit lets developers add direct, native, embedded integrations to their SaaS app as easily as building a Zapier app. With one straightforward integration to Xkit, developers can add integrations to Salesforce, HubSpot, Zendesk, and others without writing any additional code. Most of the time, those integrations can even be added by non-engineers, like product managers and customer success managers.

Unlike other products in the market, we're built from the ground up to serve the needs of developers and make sure we're a stable part of their infrastructure even as their integrations grow more complex. That's led to a few key decisions that differentiates us from the competition:
- We work with your existing API so that data flows through your application before hitting your database
- We allow for historical data sync
- New data and updates to data is on a low latency basis (<2 minutes) so your customers' data is always up to date in your app
- We expose all of the data that the APIs your integrating with offer
- We're fully white-labeled and give you direct access to the underlying API credentials (like OAuth tokens) so you can extend integrations beyond what we do

## About the Role

We're hiring a Senior DevOps Engineer to help us deliver our new project.

Our codebase is organized in a single repository. Our primary application is in Elixir, with some front-end components in Typescript.

Almost all of our infrastructure is in AWS, primarily delivered through a few EC2 instances and RDS, although we do make some use of Elasticbeanstalk and Lambda.

We are huge proponents of Infrastructure-as-code. We believe that as much as possible of our operations should rely on written and reviewed code rather than ad hoc commands. All of our infrastructure is deployed through Ansible, although we plan to migrate to Terraform over time. Our entire deployment is in a single command with zero downtime, and we're able to deploy an entire infrastructure stack into a new AWS account with the same command.

We expect this role to be responsible for maintaining the code that we use to deploy and repair infrastructure. We *do not* expect this role to be responsible for deploying and maintaining that same infrastructure. We have a deeply held belief that application developers write better code when they also deploy and maintain that code - we don't want code "thrown over the wall". That said, writing code to deploy infrastructure is quite different from writing application code, so we need someone on the team who is highly skilled in that area.

### Requirements

- Native-level proficiency in spoken and written English
- 6+ years as a DevOps engineer or similar (SRE, etc)
- Significant professional experience with Ansible and Terraform
- Fully remote, but able to meet at 9am PT once a week

What we look for:
- Strong written and spoken communication skills
- Writes clean code using the dominant idioms of the given language
- Highly productive: able to ship code that makes efficient and safe infrastructure changes quickly
- Developer oriented: strives to empower the other developers on the team and make deploying their code easy
- Customer oriented: thinks through the impacts that infrastructure changes have on the customer and works to minimize them

### Hiring Process

1. Submit a work resume or CV to `jobs@[our main domain]`
2. Submit relevant coding samples
3. Video interview with our CEO
4. 1-2 week (paid) working trial

We rely heavily on working trials to serve as an extended interview for both you and us. We've found they are the best way for us to evaluate candidates and for candidates to judge whether the fast-paced, high autonomy startup style of working is for them.
