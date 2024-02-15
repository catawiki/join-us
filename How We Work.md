# Our Tech Stack and How We Work

[`ruby-on-rails`](https://github.com/topics/ruby-on-rails) [`rails`](https://github.com/topics/rails) [`kafka`](https://github.com/topics/kafka) [`nginx`](https://github.com/topics/nginx) [`mysql`](https://github.com/topics/mysql) [`redis`](https://github.com/topics/redis) [`reactjs`](https://github.com/topics/reactjs) [`nextjs`](https://github.com/vercel/next.js) [`git`](https://github.com/topics/github) [`html5`](https://github.com/topics/html5) [`css3`](https://github.com/topics/css3) [`javascript`](https://github.com/topics/javascript) [`sass`](https://github.com/topics/sass) [`haml`](https://github.com/topics/haml) [`android`](https://github.com/topics/android) [`ios`](https://github.com/topics/ios) [`xml`](https://github.com/topics/xml) [`json`](https://github.com/topics/json) [`automated-tests`](https://github.com/topics/automated-tests) [`elasticsearch`](https://github.com/topics/elasticsearch) [`ruby`](https://github.com/topics/ruby) [`go`](https://github.com/topics/go) [`continuous-integration`](https://github.com/topics/continuous-integration) [`python`](https://github.com/topics/python) [`rspec`](https://github.com/topics/rspec) [`tdd`](https://github.com/topics/tdd) [`microservices`](https://github.com/topics/microservices) [`typescript`](https://github.com/topics/typecript)

**High Traffic / Load**

As the biggest online auction platform for special objects in Europe, Catawiki operates in a huge market that brings many unique challenges and opportunities. Having more than 14 million monthly visitors, Catawiki’s Engineering team takes the stability and the scalability of our systems and applications very seriously. To sustain Catawiki’s growth, we strive to build scalable systems that will perform well under load by carefully choosing the technologies for the problem, deciding what algorithms and data structures our programs use, and always estimating and benchmarking our system’s performance.

**Microservice Architecture** (35 different microservices, mainly Ruby and 3 in Go)

Our Engineering team is spread over many Product teams focusing on specific domains (think Search, Localisation, Bidding, etc). To enable our business to grow, experiment and innovate the product, we use a microservice architecture that has shared ownership from our entire Engineering team. Having a plethora of microservices, each of them encapsulating a part of our product domain, allows our Engineering team to iterate on new features quickly, scale each microservice as a separate entity in the system, measure and monitor its performance, and, when needed, effectively isolate, identify and fix production issues.

**Infrastructure as Code**

Maintaining our infrastructure as code allows us to quickly review, provision and scale solutions while maintaining a small, flexible and effective Infrastructure team. The Virtual Machine (VMs) provisioning is automated and reproducible between production, staging and development environments.

**Monitoring and Alerting**

‘If you can’t measure it, you can’t improve it.’ We rely on tens of thousands of collected metrics from the whole stack (browsers, mobile devices, load balancers, web servers, application runtimes, databases, OSs, networks) to quickly identify and resolve operational issues and improve the platform's and product's efficiency. We collect and monitor business and technical metrics to make informed decisions on which areas to concentrate our efforts. Those metrics are readily accessible by the whole organisation over dashboards that provide constant information feeds to our Sales, Marketing, Customer Support, Product and Engineering teams.

On top of our monitoring infrastructure, there is an alerting system that notifies the respective teams of any operational issues (such as elevated error rates, reduced availability or increased latency) within a minute over a variety of channels depending on severity. The alerts help us identify and resolve problems in a timely manner, reducing the potential negative impact on our customers.

**Code Reviews**

Code reviews are one of our most helpful tools in our development process. We have automatic tooling that takes care of style issues, formatting, and other minor tasks. Still, when we're releasing a new feature, we'll usually have at least one other person going through the changelog. This helps us spot issues early, it lets team members understand what everyone else is working on, and it allows us to constantly improve by learning how our peers approach and solve problems.

**A/B Testing**

A/B testing, sometimes called split testing, compares two versions of a web page to see which performs better. We use an in-house built gem to split our users into two (or more) groups to see which version of the website works best. By identifying points of interest, we defined and implemented tracking for a set of important goals. Goals are usually focused on business value or drop-off points for our users, e.g: ‘Seller registrations’ or ‘Lots paid within 24 hours of winning’. Each of our Product teams has a set of goals they are improving.

Before starting a test, we decide what we are testing, what is the expected outcome, and what actions we will take if the test has a negative, neutral or positive conversion. Our A/B test framework also serves as a feature toggle. We can easily turn it on/off to test how certain features behave in production. This is especially useful for moving part of a functionality to a new microservice. As we have millions of visitors, we find A/B testing to be a powerful tool that helps teams evaluate their ideas and iterate on them while knowing exactly what our users want the whole time.

**We group teams around domains** 

Catawiki's Development team contributes towards the versatility, stability, and maintainability of the Catawiki platform by organising itself into teams, each responsible for a specific domain. For example, teams are responsible for the ‘Seller experience’, ‘Search”, ‘Localisation’ and ‘Recommendations’ ...and many more. Our Development team stays flexible by allowing teams to switch focus and concentrate on different domains as and when the business need arises.

