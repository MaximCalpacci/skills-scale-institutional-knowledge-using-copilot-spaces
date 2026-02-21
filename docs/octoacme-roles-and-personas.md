# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA/Tester

### Role Summary
QA/Testers ensure delivered features meet all acceptance and quality standards. They design and execute comprehensive test plans to validate that software works as expected and meets user needs before release.

### Responsibilities
- Design and execute test plans for new features and bug fixes
- Perform regression, exploratory, and integration testing
- Document defects and collaborate with Developers for resolution
- Validate acceptance criteria with Product Managers and Developers
- Maintain test suites and automated checks
- Report on quality metrics and test coverage

### Goals
- Prevent defects from reaching production
- Provide timely, actionable feedback to development teams
- Improve automation and test coverage over time
- Ensure software quality meets both technical and user experience standards

### Typical Communication
- PR reviews and bug reports
- Project team standups and sprint planning
- Defect logs and test summary reports
- Quality gates and sign-off communications

### Interactions with Other Roles
- **Developers**: Collaborate on test coverage, validate fixes, and review code for testability
- **Product Managers**: Validate requirements and acceptance criteria, provide quality feedback
- **Project Managers**: Report on testing status, identify risks, and coordinate release readiness
- **UX/UI Designers**: Validate user experience against design specifications
- **Security Champions**: Execute security test cases and validate security requirements

---

## UX/UI Designer

### Role Summary
UX/UI Designers create user-centric interfaces and experiences. They design prototypes, gather user feedback, and ensure a cohesive, accessible user experience in coordination with Product Managers and Developers.

### Responsibilities
- Design user interfaces and interaction patterns
- Create wireframes, mockups, and interactive prototypes
- Conduct user research and usability testing
- Gather and incorporate user feedback into designs
- Maintain design systems and component libraries
- Ensure accessibility standards are met
- Collaborate on acceptance criteria that include UX considerations

### Goals
- Deliver intuitive, accessible user experiences
- Maintain design consistency across products
- Advocate for user needs throughout the development process
- Reduce user friction and improve satisfaction metrics

### Typical Communication
- Design reviews and critique sessions
- User research findings and usability reports
- Design specifications and component documentation
- Sprint planning and backlog refinement sessions

### Interactions with Other Roles
- **Product Managers**: Translate product vision into user experience, validate solutions through research
- **Developers**: Provide design specifications, collaborate on implementation feasibility
- **QA/Testers**: Define expected user experience for validation, participate in acceptance testing
- **Support/Customer Advocates**: Gather user feedback and pain points to inform design improvements

---

## Technical Lead/Architect

### Role Summary
Technical Leads/Architects set technical direction and ensure system architectural integrity. They provide expert guidance on complex technical decisions, establish standards, and mentor developers to build scalable, maintainable solutions.

### Responsibilities
- Define technical architecture and design patterns
- Make critical technical decisions and trade-offs
- Review design documents and complex code changes
- Identify and address technical debt
- Establish coding standards and best practices
- Mentor developers on technical topics
- Evaluate new technologies and tools
- Ensure scalability, performance, and maintainability

### Goals
- Build robust, scalable technical foundations
- Minimize technical debt and architectural risk
- Foster technical excellence across the team
- Enable faster, safer feature delivery

### Typical Communication
- Architecture decision records (ADRs)
- Technical design reviews and RFC discussions
- Weekly technical sync with engineering leads
- Mentoring sessions and technical guidance

### Interactions with Other Roles
- **Developers**: Provide technical guidance, conduct design and code reviews, mentor on best practices
- **Product Managers**: Advise on technical feasibility and constraints, help scope features
- **Project Managers**: Identify technical risks and dependencies, estimate complex work
- **Security Champions**: Collaborate on secure architecture and design patterns
- **QA/Testers**: Define testability requirements and review test strategies

---

## Support/Customer Advocate

### Role Summary
Support/Customer Advocates channel user feedback and incident reports back to product and development teams. They represent the voice of the customer, help prioritize fixes and enhancements based on user needs, and ensure smooth user experiences.

### Responsibilities
- Triage and document customer issues and feedback
- Communicate known issues and workarounds to users
- Advocate for user needs in planning and prioritization
- Track and report on support metrics and trends
- Collaborate with teams to resolve escalated issues
- Provide product documentation and training feedback
- Participate in release planning to understand user impact

### Goals
- Ensure customer issues are resolved quickly and effectively
- Improve product quality through user feedback
- Reduce support volume through proactive improvements
- Build strong relationships between users and product teams

### Typical Communication
- Issue escalations and feedback reports
- Support metrics and trend analysis
- Customer communication and release announcements
- Stakeholder updates on customer sentiment

### Interactions with Other Roles
- **Product Managers**: Provide user feedback and pain points, help prioritize bug fixes and features
- **Developers**: Collaborate on issue resolution, provide reproduction steps and user context
- **Project Managers**: Report on customer impact and urgency, coordinate release communications
- **QA/Testers**: Provide real-world test scenarios and edge cases from customer usage
- **UX/UI Designers**: Share user feedback on experience and usability issues

---

## Security Champion

### Role Summary
Security Champions identify security requirements, review designs and code for vulnerabilities, lead incident response efforts, and communicate security risks. They embed security practices throughout the development lifecycle.

### Responsibilities
- Define security requirements and standards
- Review designs, code, and configurations for security vulnerabilities
- Conduct threat modeling and risk assessments
- Monitor security scanning tools and triage findings
- Lead security incident response and root cause analysis
- Provide security training and awareness
- Stay current with security threats and best practices

### Goals
- Build security into products from the start
- Minimize security vulnerabilities and attack surface
- Respond quickly and effectively to security incidents
- Foster a security-aware culture across the team

### Typical Communication
- Security review feedback and findings
- Threat model documents and risk assessments
- Incident response reports and post-mortems
- Security advisories and guidelines

### Interactions with Other Roles
- **Developers**: Conduct security code reviews, provide secure coding guidance
- **Technical Leads/Architects**: Collaborate on secure architecture and design patterns
- **QA/Testers**: Define security test cases and validate security controls
- **Product Managers**: Communicate security risks and trade-offs, prioritize security work
- **Project Managers**: Identify security risks and dependencies, coordinate security reviews
- **Support/Customer Advocates**: Handle security incident communications and customer impact

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- These expanded roles help clarify responsibilities, improve collaboration, and ensure all key contributors are considered in project planning and execution.

---

*Reference: This update addresses gaps identified in [Issue #4](https://github.com/MaximCalpacci/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4)*
