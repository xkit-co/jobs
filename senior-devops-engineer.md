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

## About the Project

We're expanding the feature set offered by Xkit to help developers build integrations more easily than they can today. This new effort is based on our experience working with companies building integrations over the past year. We have a handful of alpha customers who are guiding our decision-making.

The scope of the project is quite large. It encompasses a significant data engineering effort as well as building out a serverless compute platform, and it offers the ability for non-technical people to build the bulk of these integrations.

We plan to ship this project in the next 8 weeks, so we're looking for additional team members to help us with it.

We hire almost exclusively through contracts like this, so if both you and we think it's a good fit, there are opportunities for more long-term engagements going forward.


## About the Role

We're hiring a Senior DevOps Engineer to help us deliver our new project.

Our codebase is organized in a single repository. Our primary application is in Elixir, with some front-end components in Typescript.

Almost all of our infrastructure is in AWS, primarily delivered through a few EC2 instances and RDS, although we do make some use of Elasticbeanstalk and Lambda.

All of our infrastructure is deployed through Ansible, although we plan to migrate to Terraform over time. Our entire deployment is in a single command with zero downtime, and we're able to deploy an entire infrastructure stack into a new AWS account with the same command.

We expect this role to be responsible for maintaining the code that we use to deploy and repair infrastructure. We *do not* expect this role to be responsible for deploying and maintaining that same infrastructure. We have a deeply held belief that application developers write better code when they also deploy and maintain that code - we don't want code "thrown over the wall". That said, writing code to deploy infrastructure is quite different from writing application code, so we need someone on the team who is highly skilled in that area.

### Requirements

- Native-level proficiency in spoken and written English
- 6+ years as a DevOps engineer or similar (SRE, etc)
- Significant professional experience with Ansible and Terraform
- Fully remote, but able to work 11am - 1pm PT most week days

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

That's it! Part of why we like contract arrangements is that they can serve as an extended interview for both you and us. Interviews and other exercises are notoriously bad ways to evaluate candidates (and companies) and we think the best way is to just work together and see how it goes.
