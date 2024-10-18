# Coding Dojo: Architecture Kata
Tools, guidelines and sheets for an Architecture Kata session


## Architecture Characteristics Worksheet

This worksheet will help you identify what driving architecture characteristics (“-ilities”) are critical for your system.
![architecture-characteristics-worksheet](https://github.com/user-attachments/assets/29e4bead-a5a9-4365-9b9c-16d3338787e4)

Reference of software quality attributes
<dl>
  <dt>Performance</dt>
  <dd>The amount of time it takes for the system to process a business request</dd>

  <dt>Responsiveness</dt>
  <dd>The amount of time it takes to get a response to the user</dd>

  <dt>Availability</dt>
  <dd>The amount of uptime of a system; usually measured in 9's (e.g., 99.9%)</dd>

  <dt>Fault Tolerance</dt>
  <dd>When fatal errors occur, other parts of the system continue to function</dd>

  <dt>Scalability</dt>
  <dd>A function of system capacity and growth over time; as the number of users or requests increase in the system, responsiveness, performance, and error rates remain constant</dd>

  <dt>Elasticity</dt>
  <dd>The system can expand and respond quickly to unexpected or anticipated extreme loads (e.g., going from 20 to 250,000 users instantly)</dd>

  <dt>Data Integrity</dt>
  <dd>The data across the system is correct and there is no data loss in the system</dd>

  <dt>Data Consistency</dt>
  <dd>The data across the system is in sync and consistent across databases and tables</dd>

  <dt>Adaptability</dt>
  <dd>The ease in which a system can adapt to changes in environment and functionality</dd>

  <dt>Concurrency</dt>
  <dd>The ability of the system to process simultaneous requests, in most cases in the same order in which they were received; implied when scalability and elasticity are supported</dd>

  <dt>Interoperability</dt>
  <dd>The ability of the system to interface and interact with other systems to complete a business request</dd>

  <dt>Extensibility</dt>
  <dd>The ease in which a system can be extended with additional features and functionality</dd>

  <dt>Deployability</dt>
  <dd>The amount of ceremony involved with releasing the software, the frequency in which releases occur, and the overall risk of deployment</dd>

  <dt>Testability</dt>
  <dd>The ease of and completeness of testing</dd>

  <dt>Abstraction</dt>
  <dd>The level at which parts of the system are isolated from other parts of the system (both internal and external system interactions)</dd>

  <dt>Workflow</dt>
  <dd>The ability of the system to manage complex workflows that require multiple parts (services) of the system to complete a business request</dd>

  <dt>Configurability</dt>
  <dd>The ability of the system to support multiple configurations, as well as support custom on-demand configurations and configuration updates</dd>

  <dt>Recoverability</dt>
  <dd>The ability of the system to start where it left off in the event of a system crash</dd>

  <dt>Feasibility (implicit)</dt>
  <dd>Considering timeframes, budgets, and developer skills when making architectural choices; tight timeframes and budgets make this a driving architectural characteristic</dd>

  <dt>Security (implicit)</dt>
  <dd>The ability of the system to restrict access to sensitive information or functionality</dd>

  <dt>Maintainability (implicit)</dt>
  <dd>The level of effort required to locate and apply changes to the system</dd>

  <dt>Observability (implicit)</dt>
  <dd>The ability of a system or a service to make available and stream metrics such as overall health, uptime, response times, performance, etc.</dd>
</dl>

## Architecture Styles Worksheet

Star-rated architectural styles that help in determining if you have the right architecture in place for your system.

![architecture-styles-worksheet](https://github.com/user-attachments/assets/7f3554d6-a22b-4503-bab4-8d10d970ed57)
